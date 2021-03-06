## 1.13.0 (Unreleased)
## 1.12.0 (August 30, 2019)

FEATURES:

* **New Resource:** `opentelekomcloud_ecs_instance_v1` ([#347](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/347))

ENHANCEMENTS:

* `resource/opentelekomcloud_cce_cluster_v3`: Add CCE cluster certificates ([#349](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/349))
* `resource/opentelekomcloud_cce_cluster_v3`: Add multi-az support for CCE cluster ([#350](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/350))
Add detailed error message for 404 ([#352](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/352))

BUG FIXES:

* `resource/opentelekomcloud_vpc_subnet_v1`: Fix dns_list type issue ([#351](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/351))
* `resource/opentelekomcloud_cce_node_v3`: Fix data_volumes type issue ([#354](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/354))
Fix common user ak/sk authentication issue with domain_name ([#362](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/362))
* `resource/opentelekomcloud_rds_instance_v3`: Fix backup_strategy parameter issue ([#363](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/363))


## 1.11.0 (August 01, 2019)

FEATURES:

* **New Data Source:** `opentelekomcloud_sdrs_domain_v1` ([#328](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/328))
* **New Resource:** `opentelekomcloud_sdrs_protectiongroup_v1` ([#326](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/326))

ENHANCEMENTS:

* `resource/opentelekomcloud_vpc_v1`: Add enable_shared_snat support ([#333](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/333))
* `resource/opentelekomcloud_networking_floatingip_v2`: Add default value for floating_ip pool ([#335](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/335))
* `resource/opentelekomcloud_blockstorage_volume_v2`: Add device_type argument support ([#338](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/338))
* `resource/opentelekomcloud_blockstorage_volume_v2`: Add wwn attribute support ([#339](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/339))

BUG FIXES:

* `resource/opentelekomcloud_sfs_file_system_v2`: Set availability_zone to Computed ([#330](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/330))
* `resource/opentelekomcloud_rds_configuration_v3`: Fix RDS parametergroup acc test ([#331](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/331))

## 1.10.0 (July 01, 2019)

FEATURES:

* **New Resource:** `opentelekomcloud_waf_whiteblackip_rule_v1` ([#313](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/313))
* **New Resource:** `opentelekomcloud_waf_datamasking_rule_v1` ([#315](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/315))
* **New Resource:** `opentelekomcloud_waf_falsealarmmasking_rule_v1` ([#317](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/317))
* **New Resource:** `opentelekomcloud_waf_ccattackprotection_rule_v1` ([#320](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/320))
* **New Resource:** `opentelekomcloud_waf_preciseprotection_rule_v1` ([#322](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/322))
* **New Resource:** `opentelekomcloud_waf_webtamperprotection_rule_v1` ([#324](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/324))

ENHANCEMENTS:

* `resource/opentelekomcloud_mrs_cluster_v1`: Add master/core data volume support to MRS cluster ([#308](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/308))
* `resource/opentelekomcloud_mrs_cluster_v1`: Add SAS volume type support to MRS cluster ([#310](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/310))

BUG FIXES:

* `resource/opentelekomcloud_identity_project_v3`: Fix project creation issue ([#305](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/305))

## 1.9.0 (June 06, 2019)

FEATURES:

* **New Resource:** `opentelekomcloud_waf_certificate_v1` ([#285](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/285))
* **New Resource:** `opentelekomcloud_waf_domain_v1` ([#286](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/286))
* **New Resource:** `opentelekomcloud_waf_policy_v1` ([#293](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/293))
* **New Resource:** `opentelekomcloud_rds_parametergroup_v3` ([#290](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/290))

ENHANCEMENTS:

* The provider is now compatible with Terraform v0.12, while retaining compatibility with prior versions.
* `resource/opentelekomcloud_rds_instance_v3`: Add import support ([#274](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/274))
* `resource/opentelekomcloud_cce_node_v3`: Add private_ip attribute ([#280](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/280))

BUG FIXES:

* `resource/opentelekomcloud_cce_node_v3`: Fix eip_count issue ([#279](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/279))

## 1.8.0 (May 06, 2019)

FEATURES:

* **New Data Source:** `opentelekomcloud_networking_port_v2` ([#263](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/263))
* **New Data Source:** `opentelekomcloud_rds_flavors_v3` ([#267](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/267))
* **New Resource:** `opentelekomcloud_identity_role_v3` ([#213](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/213))
* **New Resource:** `opentelekomcloud_css_cluster_v1` ([#255](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/255))
* **New Resource:** `opentelekomcloud_rds_instance_v3` ([#267](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/267))

ENHANCEMENTS:

* `resource/opentelekomcloud_dns_zone_v2`: Add support for attaching multi routers to dns zone ([#261](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/261))
* `resource/opentelekomcloud_cce_cluster_v3`: Add authentication mode option support for CCE cluster ([#262](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/262))
* `provider`: Add security_token option for OBS federated authentication ([#264](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/264))
* `resource/opentelekomcloud_rds_instance_v1`: Add RDS tag support ([#268](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/268))

BUG FIXES:

* `resource/opentelekomcloud_dms_group_v1`: Fix wrong error message ([#260](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/260))
* `data_source/opentelekomcloud_cce_node_v3`: Fix node data source with node_id ([#265](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/265))
* `resource/opentelekomcloud_cce_node_v3`: Remove Abnormal from cce node creating target state ([#266](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/266))

## 1.7.0 (March 20, 2019)

NOTES/DEPRECATIONS:

* provider: The `region`, `tenant_id`, `domain_id`, `user_id` arguments have been deprecated and `tenant_name`, `domain_name` changed to be `required`. Please update your configurations as it might be removed in the future releases.

FEATURES:

* **New Resource:** `opentelekomcloud_identity_agency_v3` ([#232](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/232))

ENHANCEMENTS:

* `provider`: Remove region, tenant_id, domain_id, user_id parameters ([#230](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/230))
* `resource/opentelekomcloud_compute_instance_v2`: Add support of security_groups update ([#234](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/234))
* `resource/opentelekomcloud_nat_snat_rule_v2`: Add `cidr` and `source_type` parameters support ([#237](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/237))

BUG FIXES:

* `resource/opentelekomcloud_identity_role_assignment_v3`: Fix attributes set issue ([#226](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/226))
* `resource/opentelekomcloud_csbs_backup_policy_v1`: Fix csbs policies parameters issue ([#244](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/244))

## 1.6.1 (February 18, 2019)

BUG FIXES:

* `provider authentication`: Fix authentication with tenant ([#216](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/216))
* `resource/opentelekomcloud_dcs_instance_v1`: Update `password` and `engine_version` of dcs instance from Option to Required ([#217](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/217))
* `resource/opentelekomcloud_smn_topic_v2`: Fix some smn topic parameters issue ([#218](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/218))

## 1.6.0 (February 01, 2019)

FEATURES:

* **New Data Source:** `opentelekomcloud_identity_role_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Data Source:** `opentelekomcloud_identity_project_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Data Source:** `opentelekomcloud_identity_user_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Data Source:** `opentelekomcloud_identity_group_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Resource:** `opentelekomcloud_identity_project_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Resource:** `opentelekomcloud_identity_role_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Resource:** `opentelekomcloud_identity_role_assignment_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Resource:** `opentelekomcloud_identity_user_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Resource:** `opentelekomcloud_identity_group_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))
* **New Resource:** `opentelekomcloud_identity_group_membership_v3` ([#167](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/167))

BUG FIXES:

* `resource/opentelekomcloud_rts_stack_v1`: Re-sign for 302 redirect in ak/sk scenario ([#204](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/204))
* `resource/opentelekomcloud_elb_listener`: Fix elb listener update error for backend_port ([#209](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/209))

## 1.5.2 (January 11, 2019)

BUG FIXES:

* `resource/opentelekomcloud_compute_instance_v2`: Fix instance tag update error ([#178](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/178))
* `resource/opentelekomcloud_dns_recordset_v2`: Fix dns records update error ([#179](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/179))
* `resource/opentelekomcloud_dns_recordset_v2`: Fix dns entries re-sort issue ([#185](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/185))

## 1.5.1 (January 08, 2019)

BUG FIXES:

* Fix ak/sk authentication issue ([#176](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/176))

## 1.5.0 (January 07, 2019)

FEATURES:

* **New Data Source:** `opentelekomcloud_dcs_az_v1` ([#154](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/154))
* **New Data Source:** `opentelekomcloud_dcs_maintainwindow_v1` ([#154](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/154))
* **New Data Source:** `opentelekomcloud_dcs_product_v1` ([#154](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/154))
* **New Resource:** `opentelekomcloud_networking_floatingip_associate_v2` ([#153](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/153))
* **New Resource:** `opentelekomcloud_dcs_instance_v1` ([#154](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/154))

BUG FIXES:

* `resource/opentelekomcloud_vpc_subnet_v1`: Remove UNKNOWN status to avoid error ([#158](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/158))
* `resource/opentelekomcloud_rds_instance_v1`: Suppress rds name change ([#161](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/161))
* `resource/opentelekomcloud_kms_key_v1`: Add default value of pending_days ([#163](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/163))
* `all resources`: Expose real error message of BadRequest error ([#164](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/164))
* `resource/opentelekomcloud_sfs_file_system_v2`: Suppress sfs system metadata ([#168](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/168))

ENHANCEMENTS:

* Add AKSK authentication support ([#157](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/157))
* `data/opentelekomcloud_images_image_v2`: Add properties filter support for images data source ([#165](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/165))
* `resource/opentelekomcloud_compute_instance_v2`: Add key/value tag support ([#169](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/169))
* `data/opentelekomcloud_vpc_subnet_v1`: Sort vpc subnet ids by network ip availabilities ([#171](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/171))

## 1.4.0 (December 10, 2018)

FEATURES:

* **New Data Source:** `opentelekomcloud_cts_tracker_v1` ([#135](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/135))
* **New Data Source:** `opentelekomcloud_antiddos_v1` ([#138](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/138))
* **New Data Source:** `opentelekomcloud_cce_node_v3` ([#140](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/140))
* **New Data Source:** `opentelekomcloud_cce_cluster_v3` ([#140](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/140))
* **New Resource:** `opentelekomcloud_compute_bms_server_v2` ([#132](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/132))
* **New Resource:** `opentelekomcloud_cts_tracker_v1` ([#135](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/135))
* **New Resource:** `opentelekomcloud_antiddos_v1` ([#138](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/138))
* **New Resource:** `opentelekomcloud_cce_node_v3` ([#140](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/140))
* **New Resource:** `opentelekomcloud_cce_cluster_v3` ([#140](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/140))
* **New Resource:** `opentelekomcloud_maas_task_v1` ([#142](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/142))

## 1.3.0 (November 05, 2018)

FEATURES:

* **New Data Source:** `opentelekomcloud_vbs_backup_policy_v2` ([#121](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/121))
* **New Data Source:** `opentelekomcloud_vbs_backup_v2` ([#121](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/121))
* **New Resource:** `opentelekomcloud_vbs_backup_policy_v2` ([#121](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/121))
* **New Resource:** `opentelekomcloud_vbs_backup_v2` ([#121](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/121))
* **New Resource:** `opentelekomcloud_vbs_backup_share_v2` ([#121](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/121))
* **New Resource:** `opentelekomcloud_mrs_cluster_v1` ([#126](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/126))
* **New Resource:** `opentelekomcloud_mrs_job_v1` ([#126](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/126))

BUG FIXES:

* `resource/opentelekomcloud_elb_loadbalancer`: Fix ELB client error ([#129](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/129))

## 1.2.0 (October 01, 2018)

FEATURES:

* **New Data Source:** `opentelekomcloud_deh_host_v1` ([#98](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/98))
* **New Data Source:** `opentelekomcloud_deh_server_v1` ([#98](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/98))
* **New Data Source:** `opentelekomcloud_rts_software_config_v1` ([#97](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/97))
* **New Data Source:** `opentelekomcloud_rts_software_deployment_v1` ([#97](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/97))
* **New Data Source:** `opentelekomcloud_vpc_v1` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Data Source:** `opentelekomcloud_vpc_subnet_v1` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Data Source:** `opentelekomcloud_vpc_subnet_ids_v1` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Data Source:** `opentelekomcloud_vpc_route_v2` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Data Source:** `opentelekomcloud_vpc_route_ids_v2` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Data Source:** `opentelekomcloud_vpc_peering_connection_v2` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Data Source:** `opentelekomcloud_compute_bms_nic_v2` ([#101](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/101))
* **New Data Source:** `opentelekomcloud_compute_bms_keypairs_v2` ([#101](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/101))
* **New Data Source:** `opentelekomcloud_compute_bms_flavors_v2` ([#101](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/101))
* **New Data Source:** `opentelekomcloud_compute_bms_server_v2` ([#101](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/101))
* **New Data Source:** `opentelekomcloud_rts_stack_v1` ([#95](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/95))
* **New Data Source:** `opentelekomcloud_rts_stack_resource_v1` ([#95](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/95))
* **New Data Source:** `opentelekomcloud_sfs_file_system_v2` ([#92](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/92))
* **New Data Source:** `opentelekomcloud_csbs_backup_v1` ([#117](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/117))
* **New Data Source:** `opentelekomcloud_csbs_backup_policy_v1` ([#117](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/117))
* **New Resource:** `opentelekomcloud_deh_host_v1` ([#98](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/98))
* **New Resource:** `opentelekomcloud_rts_software_config_v1` ([#97](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/97))
* **New Resource:** `opentelekomcloud_rts_software_deployment_v1` ([#97](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/97))
* **New Resource:** `opentelekomcloud_vpc_v1` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Resource:** `opentelekomcloud_vpc_subnet_v1` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Resource:** `opentelekomcloud_vpc_route_v2` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Resource:** `opentelekomcloud_vpc_peering_connection_v2` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Resource:** `opentelekomcloud_vpc_peering_connection_accepter_v2` ([#87](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/87))
* **New Resource:** `opentelekomcloud_sfs_file_system_v2` ([#92](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/92))
* **New Resource:** `opentelekomcloud_rts_stack_v1` ([#95](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/95))
* **New Resource:** `opentelekomcloud_nat_gateway_v2` ([#107](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/107))
* **New Resource:** `opentelekomcloud_nat_snat_rule_v2` ([#107](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/107))
* **New Resource:** `opentelekomcloud_as_configuration_v1` ([#108](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/108))
* **New Resource:** `opentelekomcloud_as_group_v1` ([#108](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/108))
* **New Resource:** `opentelekomcloud_as_policy_v1` ([#108](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/108))
* **New Resource:** `opentelekomcloud_dms_queue_v1` ([#114](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/114))
* **New Resource:** `opentelekomcloud_dms_group_v1` ([#114](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/114))
* **New Resource:** `opentelekomcloud_csbs_backup_v1` ([#117](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/117))
* **New Resource:** `opentelekomcloud_csbs_backup_policy_v1` ([#117](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/117))
* **New Resource:** `opentelekomcloud_networking_vip_v2` ([#119](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/119))
* **New Resource:** `opentelekomcloud_networking_vip_associate_v2` ([#119](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/119))

## 1.1.0 (May 26, 2018)

FEATURES:

* **New Data Source:** `opentelekomcloud_kms_key_v1` ([#14](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/14))
* **New Data Source:** `opentelekomcloud_kms_data_key_v1` ([#14](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/14))
* **New Data Source:** `opentelekomcloud_rds_flavors_v1` ([#15](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/15))
* **New Resource:** `opentelekomcloud_kms_key_v1` ([#14](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/14))
* **New Resource:** `opentelekomcloud_rds_instance_v1` ([#15](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/15))
* **New Resource:** `opentelekomcloud_vpc_eip_v1` ([#48](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/48))

ENHANCEMENTS:
* resource/opentelekomcloud_compute_instance_v2: Add `auto_recovery` argument ([#20](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/20))
* resource/opentelekomcloud_networking_router_v2: Add `enable_snat` argument ([#53](https://github.com/terraform-providers/terraform-provider-opentelekomcloud/issues/53))

## 1.0.0 (December 08, 2017)

Initial release of the OpenTelekom Cloud Provider
