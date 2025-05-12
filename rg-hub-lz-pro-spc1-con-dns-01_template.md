# Detalles de recursos definidos en rg-hub-lz-pro-spc1-con-dns-01_template.json

<details><summary>🧭 <strong>privateDnsZones_privatelink_vaultcore_azure_net_name</strong> — <em>Microsoft.Network/privateDnsZones</em></summary>

| Propiedad | Valor |
|----------|--------|
| type | Microsoft.Network/privateDnsZones |
| location | global |
| name | [parameters('privateDnsZones_privatelink_vaultcore_azure_net_name')] |
| apiVersion | 2024-06-01 |

</details>

<details><summary>🔐 🧭 <strong>privateDnsZones_privatelink_vaultcore_azure_net_name, /kv-hub-lz-pro-spc1-01</strong> — <em>Microsoft.Network/privateDnsZones/A</em></summary>

| Propiedad | Valor |
|----------|--------|
| name | [concat(parameters('privateDnsZones_privatelink_vaultcore_azure_net_name'), '/kv-hub-lz-pro-spc1-01')] |
| properties.aRecords[0].ipv4Address | 10.248.4.132 |
| dependsOn[0] | [resourceId('Microsoft.Network/privateDnsZones', parameters('privateDnsZones_privatelink_vaultcore_azure_net_name'))] |
| apiVersion | 2024-06-01 |
| type | Microsoft.Network/privateDnsZones/A |
| properties.ttl | 10 |
| properties.metadata.creator | created by private endpoint pe-kv-hub-lz-pro-spc1-01 with resource guid 5a0afd8d-5c8e-400a-bf80-372f01bc954b |

</details>

<details><summary>🧭 <strong>privateDnsZones_privatelink_vaultcore_azure_net_name, /@</strong> — <em>Microsoft.Network/privateDnsZones/SOA</em></summary>

| Propiedad | Valor |
|----------|--------|
| name | [concat(parameters('privateDnsZones_privatelink_vaultcore_azure_net_name'), '/@')] |
| properties.soaRecord.retryTime | 300 |
| properties.soaRecord.expireTime | 2419200 |
| dependsOn[0] | [resourceId('Microsoft.Network/privateDnsZones', parameters('privateDnsZones_privatelink_vaultcore_azure_net_name'))] |
| apiVersion | 2024-06-01 |
| properties.soaRecord.minimumTtl | 10 |
| properties.ttl | 3600 |
| type | Microsoft.Network/privateDnsZones/SOA |
| properties.soaRecord.host | azureprivatedns.net |
| properties.soaRecord.serialNumber | 1 |
| properties.soaRecord.refreshTime | 3600 |
| properties.soaRecord.email | azureprivatedns-host.microsoft.com |

</details>

<details><summary>🧭 <strong>privateDnsZones_privatelink_vaultcore_azure_net_name, /, privateDnsZones_privatelink_vaultcore_azure_net_name</strong> — <em>Microsoft.Network/privateDnsZones/virtualNetworkLinks</em></summary>

| Propiedad | Valor |
|----------|--------|
| name | [concat(parameters('privateDnsZones_privatelink_vaultcore_azure_net_name'), '/', parameters('privateDnsZones_privatelink_vaultcore_azure_net_name'))] |
| dependsOn[0] | [resourceId('Microsoft.Network/privateDnsZones', parameters('privateDnsZones_privatelink_vaultcore_azure_net_name'))] |
| apiVersion | 2024-06-01 |
| type | Microsoft.Network/privateDnsZones/virtualNetworkLinks |
| location | global |
| properties.registrationEnabled | ❌ |
| properties.resolutionPolicy | Default |
| properties.virtualNetwork.id | [parameters('virtualNetworks_vnet_hub_lz_pro_spc1_con_01_externalid')] |

</details>


