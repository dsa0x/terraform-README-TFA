## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.13 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_tls"></a> [tls](#provider\_tls) | 3.1.0 |
| <a name="provider_azurerm"></a> [azurerm](#provider\_azurerm) | 2.88.1 |
| <a name="provider_random"></a> [random](#provider\_random) | 3.1.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [azurerm_container_registry.acr](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/container_registry) | resource |
| [azurerm_key_vault.aks-kvt](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/key_vault) | resource |
| [azurerm_key_vault_secret.scrt-adoagnt-ais](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/key_vault_secret) | resource |
| [azurerm_key_vault_secret.scrt-jpbx-ais](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/key_vault_secret) | resource |
| [azurerm_key_vault_secret.sshkey](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/key_vault_secret) | resource |
| [azurerm_key_vault_secret.username](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/key_vault_secret) | resource |
| [azurerm_kubernetes_cluster.aks-clstr](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/kubernetes_cluster) | resource |
| [azurerm_kubernetes_cluster_node_pool.ops](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/kubernetes_cluster_node_pool) | resource |
| [azurerm_linux_virtual_machine.vm-jpbx-ais](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/linux_virtual_machine) | resource |
| [azurerm_linux_virtual_machine_scale_set.vmss-adoagnt-ais](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/linux_virtual_machine_scale_set) | resource |
| [azurerm_log_analytics_workspace.fmz-law-aks](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/log_analytics_workspace) | resource |
| [azurerm_monitor_diagnostic_setting.aks-diagnostic](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/monitor_diagnostic_setting) | resource |
| [azurerm_monitor_diagnostic_setting.diag-kvt-ais](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/monitor_diagnostic_setting) | resource |
| [azurerm_network_interface.nic-jpbx-ais](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/network_interface) | resource |
| [azurerm_private_endpoint.acr](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/private_endpoint) | resource |
| [azurerm_private_endpoint.akv](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/private_endpoint) | resource |
| [azurerm_private_endpoint.pep-stg](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/private_endpoint) | resource |
| [azurerm_resource_group.aks-rgp](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group) | resource |
| [azurerm_resource_group.rgp-adoagnt-ais](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group) | resource |
| [azurerm_resource_group.rgp-jpbx-ais](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group) | resource |
| [azurerm_resource_group.sup_rg](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group) | resource |
| [azurerm_role_assignment.acr_pull](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/role_assignment) | resource |
| [azurerm_role_assignment.aks-rtb](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/role_assignment) | resource |
| [azurerm_role_assignment.aks_kv_certs](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/role_assignment) | resource |
| [azurerm_role_assignment.aks_kv_secrets](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/role_assignment) | resource |
| [azurerm_role_assignment.dns](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/role_assignment) | resource |
| [azurerm_role_assignment.ntwrk](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/role_assignment) | resource |
| [azurerm_role_assignment.tf-akv](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/role_assignment) | resource |
| [azurerm_storage_account.valero](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/storage_account) | resource |
| [azurerm_storage_container.valero](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/storage_container) | resource |
| [azurerm_subnet.agents](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/subnet) | resource |
| [azurerm_subnet.mng](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/subnet) | resource |
| [azurerm_subnet.pep](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/subnet) | resource |
| [azurerm_subnet.systempool](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/subnet) | resource |
| [azurerm_user_assigned_identity.aks-uai](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/user_assigned_identity) | resource |
| [random_password.psswrd-adoagnt-ais](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/password) | resource |
| [random_password.psswrd-jpbx-ais](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/password) | resource |
| [tls_private_key.ssh](https://registry.terraform.io/providers/hashicorp/tls/latest/docs/resources/private_key) | resource |
| [azurerm_client_config.current](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/data-sources/client_config) | data source |
| [azurerm_subscription.current](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/data-sources/subscription) | data source |
| [azurerm_virtual_network.aks](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/data-sources/virtual_network) | data source |

## Inputs

## General Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_org_name"></a> [org\_name](#input\_org\_name) | Name of the Organization, default is fmz | `string` | `"fmz"` | no |
| <a name="input_env"></a> [env](#input\_env) | environment, will be Hub(h) or Core(c) for hub resources | `string` | `"d"` | no |
| <a name="input_location"></a> [location](#input\_location) | location of the Hub vnet, default is eastus2 | `string` | `"eastus2"` | no |
| <a name="input_tier"></a> [tier](#input\_tier) | The tier to which the AKS cluster belongs to, default is app | `string` | `"app"` | no |
| <a name="input_tags"></a> [tags](#input\_tags) | tags | `map(any)` | <pre>{<br>  "Contact": "apaar.sharma@fmglobal.com",<br>  "CreatedBy": "apaar.sharma@fmglobal.com",<br>  "Department": "Cloud Platform",<br>  "Terraform": "True"<br>}</pre> | no |

## Cluster Azure Network Relared Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_vnet_name"></a> [vnet\_name](#input\_vnet\_name) | Name of the virtual network in which the AKS cluster should go | `string` | n/a | yes |
| <a name="input_vnet_resource_group"></a> [vnet\_resource\_group](#input\_vnet\_resource\_group) | Resource group of the virtual network in which the AKS cluster should go | `string` | n/a | yes |
| <a name="input_create_new_aks_subnet"></a> [create\_new\_aks\_subnet](#input\_create\_new\_aks\_subnet) | If set to true, the module will create additional subnets for the AKS cluster and The internal Load Balncer resource, defaults to true. | `bool` | `true` | no |
| <a name="input_aks_subnet_adress_prefix"></a> [aks\_subnet\_adress\_prefix](#input\_aks\_subnet\_adress\_prefix) | If "create\_new\_aks\_subnet" variable is set to true, pass the adress prefix for the new subnet for the AKS cluster. | `string` | `null` | no |
| <a name="input_existing_aks_Subnet_id"></a> [existing\_aks\_Subnet\_id](#input\_existing\_aks\_Subnet\_id) | If create\_new\_aks\_subnet variable is set to false, pass the resource id of an existing subnet for the AKS cluster | `string` | `null` | no |
| <a name="input_aks_route_table_id"></a> [aks\_route\_table\_id](#input\_aks\_route\_table\_id) | Resource ID of the Route table assigned to the AKS nodepool subnet, AKS needs network contributor on this route table | `string` | n/a | yes |
| <a name="input_create_new_pep_subnet"></a> [create\_new\_pep\_subnet](#input\_create\_new\_pep\_subnet) | If set to true, the module will create additional subnets for the private endpointed resources for AKS supporting services like Keyvault, ACR etc, defaults to true. | `bool` | `true` | no |
| <a name="input_pep_subnet_adress_prefix"></a> [pep\_subnet\_adress\_prefix](#input\_pep\_subnet\_adress\_prefix) | If "create\_new\_pep\_subnet" variable is set to true, pass the adress prefix for the new subnet for the Private Endpointed resources. | `string` | `null` | no |
| <a name="input_existing_pep_Subnet_id"></a> [existing\_pep\_Subnet\_id](#input\_existing\_pep\_Subnet\_id) | If create\_new\_pep\_subnet variable is set to false, pass the resource id of an existing subnet for the private endpointed resources | `string` | `null` | no |
| <a name="input_create_new_ado_subnet"></a> [create\_new\_ado\_subnet](#input\_create\_new\_ado\_subnet) | If this variable and the variable "deploy\_ado\_agents" are set to true, the module will create additional subnets for the ADO agents for AKS, defaults to true. | `bool` | `true` | no |
| <a name="input_ado_subnet_adress_prefix"></a> [ado\_subnet\_adress\_prefix](#input\_ado\_subnet\_adress\_prefix) | If "create\_new\_ado\_subnet" variable is set to true, pass the adress prefix for the new subnet for the ADO agent VMSS. | `string` | `null` | no |
| <a name="input_existing_ado_Subnet_id"></a> [existing\_ado\_Subnet\_id](#input\_existing\_ado\_Subnet\_id) | If create\_new\_ado\_subnet variable is set to false, pass the resource id of an existing subnet for the ado agent vmss | `string` | `null` | no |
| <a name="input_create_new_jpbx_subnet"></a> [create\_new\_jpbx\_subnet](#input\_create\_new\_jpbx\_subnet) | If this variable and the variable "deploy\_a\_jumpbox" are set to true, the module will create additional subnets for the jumpbox to access the AKS cluster, defaults to true. | `bool` | `true` | no |
| <a name="input_jpbx_subnet_adress_prefix"></a> [jpbx\_subnet\_adress\_prefix](#input\_jpbx\_subnet\_adress\_prefix) | If "create\_new\_jpbx\_subnet" variable is set to true, pass the adress prefix for the new subnet for the Jumpbox. | `string` | `null` | no |
| <a name="input_existing_jpbx_Subnet_id"></a> [existing\_jpbx\_Subnet\_id](#input\_existing\_jpbx\_Subnet\_id) | If create\_new\_jpbx\_subnet variable is set to false, pass the resource id of an existing subnet for the jumpbox | `string` | `null` | no |


## Private DNS Zones Related Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_aks_dns_zone_id"></a> [aks\_dns\_zone\_id](#input\_aks\_dns\_zone\_id) | resource ID for the AKS DNS zone | `string` | `"/subscriptions/8dde437e-bb01-4a4c-a6de-e971e2a1656c/resourceGroups/fmz-e-h-rgp-dns-01/providers/Microsoft.Network/privateDnsZones/privatelink.eastus2.azmk8s.io"` | no |
| <a name="input_keyvault_dns_zone_id"></a> [keyvault\_dns\_zone\_id](#input\_keyvault\_dns\_zone\_id) | Resource ID for the keyvault DNS zone | `string` | `"/subscriptions/8dde437e-bb01-4a4c-a6de-e971e2a1656c/resourceGroups/fmz-e-h-rgp-dns-01/providers/Microsoft.Network/privateDnsZones/privatelink.vaultcore.azure.net"` | no |
| <a name="input_acr_dns_zone_id"></a> [acr\_dns\_zone\_id](#input\_acr\_dns\_zone\_id) | Resource ID for the ACR DNS zone | `string` | `"/subscriptions/8dde437e-bb01-4a4c-a6de-e971e2a1656c/resourceGroups/fmz-e-h-rgp-dns-01/providers/Microsoft.Network/privateDnsZones/privatelink.azurecr.io"` | no |
| <a name="input_blob_dns_zone_id"></a> [blob\_dns\_zone\_id](#input\_blob\_dns\_zone\_id) | Resource ID for the blob DNS zone | `string` | `"/subscriptions/8dde437e-bb01-4a4c-a6de-e971e2a1656c/resourceGroups/fmz-e-h-rgp-dns-01/providers/Microsoft.Network/privateDnsZones/privatelink.blob.core.windows.net"` | no |

## General AKS Related Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_kubernetes_version"></a> [kubernetes\_version](#input\_kubernetes\_version) | Specify which Kubernetes release to use. The default used is the latest Kubernetes version available in the region | `string` | `null` | no |
| <a name="input_sku_tier"></a> [sku\_tier](#input\_sku\_tier) | The SKU Tier for the Kubernetes Cluster. Possible values are Free and Paid | `string` | `"Paid"` | no |
| <a name="input_admin_username"></a> [admin\_username](#input\_admin\_username) | The username of the local administrator to be created on the Kubernetes cluster | `string` | `"adminuser"` | no |
| <a name="input_public_ssh_key"></a> [public\_ssh\_key](#input\_public\_ssh\_key) | An ssh key set in the main variables of the terraform-azurerm-aks module, if left empty the module will create one for you and store it in the Keyvault | `string` | `""` | no |
| <a name="input_enable_auto_scaling"></a> [enable\_auto\_scaling](#input\_enable\_auto\_scaling) | Enable node pool autoscaling or not | `bool` | `true` | no |

## Agent Pool Related

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_orchestrator_version"></a> [orchestrator\_version](#input\_orchestrator\_version) | Specify which Kubernetes release to use for the orchestration layer. if not set then the latest version will be used | `string` | `null` | no |
| <a name="input_agents_count"></a> [agents\_count](#input\_agents\_count) | The number of Agents that should exist in the Agent Pool. to be used when autoscaling is not enabled | `number` | `null` | no |
| <a name="input_agents_max_count"></a> [agents\_max\_count](#input\_agents\_max\_count) | Maximum number of nodes in a pool, when autoscaling is enabled | `number` | `6` | no |
| <a name="input_agents_min_count"></a> [agents\_min\_count](#input\_agents\_min\_count) | Minimum number of nodes in a pool, when autoscaling is enabled | `number` | `1` | no |
| <a name="input_enable_node_public_ip"></a> [enable\_node\_public\_ip](#input\_enable\_node\_public\_ip) | (Optional) Decides if the nodes in this Node Pool have a Public IP Address. Defaults to false. | `bool` | `false` | no |
| <a name="input_agents_size"></a> [agents\_size](#input\_agents\_size) | The default virtual machine size for the Kubernetes agents, defaults to Standard\_DS3\_v2 | `string` | `"Standard_DS3_v2"` | no |
| <a name="input_os_disk_size_gb"></a> [os\_disk\_size\_gb](#input\_os\_disk\_size\_gb) | Disk size of nodes in GBs. defaults to 50 | `number` | `50` | no |
| <a name="input_agents_availability_zones"></a> [agents\_availability\_zones](#input\_agents\_availability\_zones) | (Optional) A list of Availability Zones across which the Node Pool should be spread | `list(string)` | `[]` | no |
| <a name="input_agents_labels"></a> [agents\_labels](#input\_agents\_labels) | (Optional) A map of Kubernetes labels which should be applied to nodes in the Default Node Pool. | `map(string)` | `{}` | no |
| <a name="input_agents_type"></a> [agents\_type](#input\_agents\_type) | (Optional) The type of Node Pool which should be created. Possible values are AvailabilitySet and VirtualMachineScaleSets. Defaults to VirtualMachineScaleSets. | `string` | `"VirtualMachineScaleSets"` | no |
| <a name="input_agents_max_pods"></a> [agents\_max\_pods](#input\_agents\_max\_pods) | (Optional) The maximum number of pods that can run on each agent. | `number` | `null` | no |
| <a name="input_agents_taints"></a> [agents\_taints](#input\_agents\_taints) | (Optional) list Taints on the system node pool | `list(any)` | `[]` | no |
| <a name="input_enable_host_encryption"></a> [enable\_host\_encryption](#input\_enable\_host\_encryption) | Enable Host Encryption for default node pool. This feature should be enabled on the subscription first | `bool` | `false` | no |
| <a name="input_upgrade_max_surge"></a> [upgrade\_max\_surge](#input\_upgrade\_max\_surge) | Maximum node surge during an upgrade | `string` | `"33%"` | no |


## AKS Identity Related Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_client_id"></a> [client\_id](#input\_client\_id) | (Optional) The Client ID (appId) for the Service Principal used for the AKS deployment | `string` | `""` | no |
| <a name="input_client_secret"></a> [client\_secret](#input\_client\_secret) | (Optional) The Client Secret (password) for the Service Principal used for the AKS deployment | `string` | `""` | no |
| <a name="input_identity_type"></a> [identity\_type](#input\_identity\_type) | (Optional) The type of identity used for the managed cluster. Possible values are `SystemAssigned` and `UserAssigned`. If `UserAssigned` is set, a `user_assigned_identity_id` must be set as well otherwise leave it as null. | `string` | `"UserAssigned"` | no |

## AKS Add On Related Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_enable_http_application_routing"></a> [enable\_http\_application\_routing](#input\_enable\_http\_application\_routing) | Enable HTTP Application Routing Addon. | `bool` | `false` | no |
| <a name="input_enable_azure_policy"></a> [enable\_azure\_policy](#input\_enable\_azure\_policy) | Enable Azure Policy Addon. | `bool` | `true` | no |
| <a name="input_enable_kube_dashboard"></a> [enable\_kube\_dashboard](#input\_enable\_kube\_dashboard) | Enable Kubernetes Dashboard. | `bool` | `false` | no |
| <a name="input_enable_log_analytics_workspace"></a> [enable\_log\_analytics\_workspace](#input\_enable\_log\_analytics\_workspace) | Enable the creation of azurerm\_log\_analytics\_workspace and azurerm\_log\_analytics\_solution or not | `bool` | `true` | no |
| <a name="input_enable_open_service_mesh"></a> [enable\_open\_service\_mesh](#input\_enable\_open\_service\_mesh) | Enable Installation of Open Service Mesh or not | `bool` | `true` | no |

## AKS Networking Related Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_network_plugin"></a> [network\_plugin](#input\_network\_plugin) | Network plugin to use for networking. possible values are kubenet and azure | `string` | `"kubenet"` | no |
| <a name="input_network_policy"></a> [network\_policy](#input\_network\_policy) | (Optional) Sets up network policy to be used with Azure CNI. Network policy allows us to control the traffic flow between pods. Currently supported values are calico and azure. | `string` | `"calico"` | no |
| <a name="input_net_profile_dns_service_ip"></a> [net\_profile\_dns\_service\_ip](#input\_net\_profile\_dns\_service\_ip) | (Optional) IP address within the Kubernetes service address range that will be used by cluster service discovery (kube-dns). | `string` | `null` | no |
| <a name="input_net_profile_docker_bridge_cidr"></a> [net\_profile\_docker\_bridge\_cidr](#input\_net\_profile\_docker\_bridge\_cidr) | (Optional) IP address (in CIDR notation) used as the Docker bridge IP address on nodes. | `string` | `null` | no |
| <a name="input_net_profile_outbound_type"></a> [net\_profile\_outbound\_type](#input\_net\_profile\_outbound\_type) | (Optional) The outbound (egress) routing method which should be used for this Kubernetes Cluster. Possible values are loadBalancer and userDefinedRouting. Defaults to loadBalancer. | `string` | `"userDefinedRouting"` | no |
| <a name="input_net_profile_pod_cidr"></a> [net\_profile\_pod\_cidr](#input\_net\_profile\_pod\_cidr) | (Optional) The CIDR to use for pod IP addresses. This field can only be set when network\_plugin is set to kubenet.This field can only be set when network\_plugin is set to kubenet | `string` | `null` | no |
| <a name="input_net_profile_service_cidr"></a> [net\_profile\_service\_cidr](#input\_net\_profile\_service\_cidr) | (Optional) The Network Range used by the Kubernetes service. | `string` | `null` | no |

## AKS Autoscaler Related Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_aks_autoscaler_profile"></a> [aks\_autoscaler\_profile](#input\_aks\_autoscaler\_profile) | This variable is a map object which contains the configuration for the AKS cluster autoscaler profile <br><br>  It takes the following arguments:<br>  1) balance\_similar\_node\_groups : (Bool) Detect similar node groups and balance the number of nodes between them, default = false <br><br>  2) max\_graceful\_termination\_sec: (String) Maximum number of seconds the cluster autoscaler waits for pod termination when trying to scale down a node, default = 600 <br><br>  3) scale\_down\_delay\_after\_add : (string) How long after the scale up of AKS nodes the scale down evaluation resumes, default = 10m <br><br>  4) scale\_down\_delay\_after\_delete: (string) How long after node deletion that scale down evaluation resumes, default = 10s <br><br>  5) scale\_down\_delay\_after\_failure: (string) "How long after scale down failure that scale down evaluation resumes, deafult = 10m <br><br>  6) scan\_interval: (string) How often the AKS Cluster should be re-evaluated for scale up/down, default = 10s <br><br>  7) scale\_down\_unneeded: (string) How long a node should be unneeded before it is eligible for scale down, default = 10m <br><br>  8) scale\_down\_unready: (string) How long an unready node should be unneeded before it is eligible for scale down, default = 10m <br><br>  9) scale\_down\_utilization\_threshold: (string) Node utilization level, defined as sum of requested resources divided by capacity, below which a node can be considered for scale down, default = 0.5 <br> | <pre>object({<br>    balance_similar_node_groups = bool<br>    max_graceful_termination_sec = string<br>    scale_down_delay_after_add = string<br>    scale_down_delay_after_delete = string<br>    scale_down_delay_after_failure = string<br>    scan_interval = string<br>    scale_down_unneeded = string<br>    scale_down_unready = string<br>    scale_down_utilization_threshold = string<br>  })</pre> | <pre>{<br>  "balance_similar_node_groups": false,<br>  "max_graceful_termination_sec": "600",<br>  "scale_down_delay_after_add": "10m",<br>  "scale_down_delay_after_delete": "10s",<br>  "scale_down_delay_after_failure": "10m",<br>  "scale_down_unneeded": "10m",<br>  "scale_down_unready": "10m",<br>  "scale_down_utilization_threshold": "0.5",<br>  "scan_interval": "10s"<br>}</pre> | no |

## AKS AD integration Related Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_enable_role_based_access_control"></a> [enable\_role\_based\_access\_control](#input\_enable\_role\_based\_access\_control) | Enable Role Based Access Control. | `bool` | `true` | no |
| <a name="input_rbac_aad_managed"></a> [rbac\_aad\_managed](#input\_rbac\_aad\_managed) | Is the Azure Active Directory integration Managed, this means that Azure will create/manage the Service Principal used for integration. | `bool` | `true` | no |
| <a name="input_rbac_aad_admin_group_object_ids"></a> [rbac\_aad\_admin\_group\_object\_ids](#input\_rbac\_aad\_admin\_group\_object\_ids) | list of Object ID of groups with admin access. | `list(string)` | `[]` | no |
| <a name="input_rbac_aad_client_app_id"></a> [rbac\_aad\_client\_app\_id](#input\_rbac\_aad\_client\_app\_id) | The Client ID of an Azure Active Directory Application. Set if the AAD integradtion is not manged | `string` | `null` | no |
| <a name="input_rbac_aad_server_app_id"></a> [rbac\_aad\_server\_app\_id](#input\_rbac\_aad\_server\_app\_id) | The Server ID of an Azure Active Directory Application. Set if the AAD integradtion is not manged | `string` | `null` | no |
| <a name="input_rbac_aad_server_app_secret"></a> [rbac\_aad\_server\_app\_secret](#input\_rbac\_aad\_server\_app\_secret) | The Server Secret of an Azure Active Directory Application. Set if the AAD integradtion is not manged | `string` | `null` | no |

## Additional Node Pools Related Variables

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_node_pools"></a> [node\_pools](#input\_node\_pools) | Addons node pools | <pre>list(object({<br>    name                = string<br>    vm_size             = string<br>    os_disk_size_gb     = number<br>    enable_auto_scaling = bool<br>    node_count          = number<br>    min_count           = number<br>    max_count           = number<br>    max_pods            = number<br>    node_taints         = list(string)<br>    node_labels         = map(string)<br>  }))</pre> | <pre>[<br>  {<br>    "enable_auto_scaling": true,<br>    "max_count": 6,<br>    "max_pods": null,<br>    "min_count": 1,<br>    "name": "fmzedshrd01",<br>    "node_count": null,<br>    "node_labels": {},<br>    "node_taints": [],<br>    "os_disk_size_gb": 50,<br>    "vm_size": "Standard_DS3_v2"<br>  }<br>]</pre> | no |
| <a name="input_use_existing_log_analytics_workspace"></a> [use\_existing\_log\_analytics\_workspace](#input\_use\_existing\_log\_analytics\_workspace) | True/false should an existing Log Analytics workspace be used to push AKS and supporting services logs and metrics | `bool` | `false` | no |
| <a name="input_existing_log_analytics_workspace_id"></a> [existing\_log\_analytics\_workspace\_id](#input\_existing\_log\_analytics\_workspace\_id) | Pass the value of this variable when the variable (use\_existing\_log\_analytics\_workspace) is set to true, The resource ID of the existing log analytics workspace | `string` | `null` | no |
| <a name="input_valero_storage"></a> [valero\_storage](#input\_valero\_storage) | This variable is a map object which accepts variables regarding the Valero storage account.<br>  It takes the following attributes:<br>  1) enabled (true/false) : This attribute decides whether the storage account is deployed or not.<br>  2) allowed\_ips : This is a list of Ip adresses that need to be white listed on the valero storage account's paas network firewall.<br>  3) virtual\_network\_subnet\_ids : This is list of subnet resource IDs to be whitelisted on the valero storage account's PaaS network firewall. | <pre>object({<br>    enabled = bool<br>    allowed_ips = list(string)<br>    virtual_network_subnet_ids = list(string)<br>  })</pre> | <pre>{<br>  "allowed_ips": [<br>    "159.221.0.0/16",<br>    "20.41.6.0/23",<br>    "20.37.158.0/23"<br>  ],<br>  "enabled": true,<br>  "virtual_network_subnet_ids": [<br>    "/subscriptions/9e7b9f81-0b8b-4bad-b897-b4155280133d/resourceGroups/FMZ-E-N-U-RGP-NET-01/providers/Microsoft.Network/virtualNetworks/FMZ-E-N-U-VNET-01/subnets/fmz-e-n-u-aci-snt-t-10.128.172.16_28",<br>    "/subscriptions/7ca972ef-75d0-496e-9c4e-601a39bc99a6/resourceGroups/fmz-e-p-eut-rgp-net-01/providers/Microsoft.Network/virtualNetworks/fmz-e-p-eut-dmz-vnet-01/subnets/fmz-e-p-eut-dmz-snt-t-10.128.168.0_23",<br>    "/subscriptions/7ca972ef-75d0-496e-9c4e-601a39bc99a6/resourceGroups/FMZ-E-P-EUT-RGP-NET-01/providers/Microsoft.Network/virtualNetworks/FMZ-E-P-EUT-VNET-01/subnets/FMZ-E-P-EUT-VDI-SNT-T-10.128.178.0_23"<br>  ]<br>}</pre> | no |
| <a name="input_keyvault_firewall"></a> [keyvault\_firewall](#input\_keyvault\_firewall) | this variable is a map that accept's the network firewall rule for the keyvault | <pre>object({<br>    allowed_ips                = list(string)<br>    virtual_network_subnet_ids = list(string)<br>  })</pre> | <pre>{<br>  "allowed_ips": [<br>    "159.221.0.0/16",<br>    "20.41.6.0/23",<br>    "20.37.158.0/23"<br>  ],<br>  "virtual_network_subnet_ids": [<br>    "/subscriptions/9e7b9f81-0b8b-4bad-b897-b4155280133d/resourceGroups/FMZ-E-N-U-RGP-NET-01/providers/Microsoft.Network/virtualNetworks/FMZ-E-N-U-VNET-01/subnets/fmz-e-n-u-aci-snt-t-10.128.172.16_28",<br>    "/subscriptions/7ca972ef-75d0-496e-9c4e-601a39bc99a6/resourceGroups/fmz-e-p-eut-rgp-net-01/providers/Microsoft.Network/virtualNetworks/fmz-e-p-eut-dmz-vnet-01/subnets/fmz-e-p-eut-dmz-snt-t-10.128.168.0_23",<br>    "/subscriptions/7ca972ef-75d0-496e-9c4e-601a39bc99a6/resourceGroups/FMZ-E-P-EUT-RGP-NET-01/providers/Microsoft.Network/virtualNetworks/FMZ-E-P-EUT-VNET-01/subnets/FMZ-E-P-EUT-VDI-SNT-T-10.128.178.0_23"<br>  ]<br>}</pre> | no |
| <a name="input_container_registry"></a> [container\_registry](#input\_container\_registry) | this variable is a map that accept's the network firewall rule for the ACR<br>    The first object of the map, "deploy" is a boolean which decides if a container registry is deployed or not. | <pre>object({<br>    deploy                     = bool<br>    allowed_ips                = list(string)<br>    virtual_network_subnet_ids = list(string)<br>  })</pre> | <pre>{<br>  "allowed_ips": [<br>    "159.221.0.0/16",<br>    "20.41.6.0/23",<br>    "20.37.158.0/23"<br>  ],<br>  "deploy": true,<br>  "virtual_network_subnet_ids": []<br>}</pre> | no |
| <a name="input_jumpbox"></a> [jumpbox](#input\_jumpbox) | This variable contains the information needed for the jumpbox:<br>  The variable is a map and takes the following parameters. <br><br>  1) enabled (true/false) : Decides if jumpbox is deployed or not. Defaults to false <br><br>  3) size: size of the Jumpbox virtual machine <br><br>  3) admin\_username: username for the admin user of the VM, the password is automatically stored in the keyvault by the module. <br><br>  4) source\_image\_id : resource id of the source image for the vm. <br> | <pre>object({<br>    enabled         = bool<br>    size            = string<br>    admin_username  = string<br>    source_image_id = string<br>  })</pre> | <pre>{<br>  "admin_username": "adminuser",<br>  "enabled": false,<br>  "size": "Standard_DS1_v2",<br>  "source_image_id": "/subscriptions/9e7b9f81-0b8b-4bad-b897-b4155280133d/resourceGroups/FMZ-E-N-U-RGP-ADOBLD-01/providers/Microsoft.Compute/galleries/AzureDevOps_Build_Image_Gallery/images/Azure_Ubuntu_Agents"<br>}</pre> | no |
| <a name="input_build_agents"></a> [build\_agents](#input\_build\_agents) | This variable contains the information needed for the jumpbox:<br>  The variable is a map which takes the following parameters: <br><br>  1) enabled (true/false): Decides if the ADO agents are deloyed or not, defaults to false. <br><br>  2) sku : Sku for the virtual machines in the build agent VMSS. <br><br>  3) admin\_username: admin username for the Virtual machines, inside the VMSS, the password for the vms is automatically stored in the keyvault. <br><br>  4) use\_custom\_image (true/false): decides if a custom image should be used for the Vms (The ubuntu build agent image used by DevSecOps is the default) <br><br>  5) source\_image\_id = It is used when use\_custom\_image is set to true, default is the Ubuntu Build agent image used by DevSecOps.<br>  6) source\_image\_reference = It is used when custom image is set to false, It's a map consisting of the, Publisher, offer, sku and version. | <pre>object({<br>    enabled          = bool<br>    sku              = string<br>    admin_username   = string<br>    use_custom_image = string<br>    source_image_id  = string<br>    source_image_reference = object({<br>      publisher = string<br>      offer     = string<br>      sku       = string<br>      version   = string<br>    })<br>  })</pre> | <pre>{<br>  "admin_username": "adminuser",<br>  "enabled": false,<br>  "sku": "Standard_D2_v3",<br>  "source_image_id": "/subscriptions/9e7b9f81-0b8b-4bad-b897-b4155280133d/resourceGroups/FMZ-E-N-U-RGP-ADOBLD-01/providers/Microsoft.Compute/galleries/AzureDevOps_Build_Image_Gallery/images/Azure_Ubuntu_Agents",<br>  "source_image_reference": {<br>    "offer": "UbuntuServer",<br>    "publisher": "Canonical",<br>    "sku": "18.04-LTS",<br>    "version": "latest"<br>  },<br>  "use_custom_image": true<br>}</pre> | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_client_key"></a> [client\_key](#output\_client\_key) | n/a |
| <a name="output_client_certificate"></a> [client\_certificate](#output\_client\_certificate) | n/a |
| <a name="output_cluster_ca_certificate"></a> [cluster\_ca\_certificate](#output\_cluster\_ca\_certificate) | n/a |
| <a name="output_host"></a> [host](#output\_host) | n/a |
| <a name="output_username"></a> [username](#output\_username) | n/a |
| <a name="output_password"></a> [password](#output\_password) | n/a |
| <a name="output_node_resource_group"></a> [node\_resource\_group](#output\_node\_resource\_group) | n/a |
| <a name="output_location"></a> [location](#output\_location) | n/a |
| <a name="output_aks_id"></a> [aks\_id](#output\_aks\_id) | n/a |
| <a name="output_kube_config_raw"></a> [kube\_config\_raw](#output\_kube\_config\_raw) | n/a |
| <a name="output_http_application_routing_zone_name"></a> [http\_application\_routing\_zone\_name](#output\_http\_application\_routing\_zone\_name) | n/a |
| <a name="output_system_assigned_identity"></a> [system\_assigned\_identity](#output\_system\_assigned\_identity) | n/a |
| <a name="output_kubelet_identity"></a> [kubelet\_identity](#output\_kubelet\_identity) | n/a |
| <a name="output_admin_client_key"></a> [admin\_client\_key](#output\_admin\_client\_key) | n/a |
| <a name="output_admin_client_certificate"></a> [admin\_client\_certificate](#output\_admin\_client\_certificate) | n/a |
| <a name="output_admin_cluster_ca_certificate"></a> [admin\_cluster\_ca\_certificate](#output\_admin\_cluster\_ca\_certificate) | n/a |
| <a name="output_admin_host"></a> [admin\_host](#output\_admin\_host) | n/a |
| <a name="output_admin_username"></a> [admin\_username](#output\_admin\_username) | n/a |
| <a name="output_admin_password"></a> [admin\_password](#output\_admin\_password) | n/a |
