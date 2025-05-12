# Detalles de recursos definidos en rg-hub-lz-pro-spc1-con-sec-01_template.json

<details><summary>💻 <strong>networkInterfaces_vm_hub_lz_pro_spc1_fortimanager_01_mgmt_name</strong> — <em>Microsoft.Network/networkInterfaces</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.ipConfigurations[0].name | mgmt |
| properties.enableIPForwarding | ✅ |
| location | spaincentral |
| properties.auxiliaryMode | None |
| properties.ipConfigurations[0].type | Microsoft.Network/networkInterfaces/ipConfigurations |
| properties.ipConfigurations[0].properties.primary | ✅ |
| properties.nicType | Standard |
| properties.ipConfigurations[0].properties.publicIPAddress.id | [parameters('publicIPAddresses_pip_hub_lz_pro_spc1_forti_01_externalid')] |
| properties.enableAcceleratedNetworking | ❌ |
| apiVersion | 2024-05-01 |
| properties.ipConfigurations[0].id | [concat(resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fortimanager_01_mgmt_name')), '/ipConfigurations/mgmt')] |
| type | Microsoft.Network/networkInterfaces |
| properties.ipConfigurations[0].properties.privateIPAllocationMethod | Static |
| properties.ipConfigurations[0].properties.privateIPAddress | 10.248.4.165 |
| properties.ipConfigurations[0].properties.privateIPAddressVersion | IPv4 |
| kind | Regular |
| properties.auxiliarySku | None |
| properties.ipConfigurations[0].properties.subnet.id | [concat(parameters('virtualNetworks_vnet_hub_lz_pro_spc1_con_01_externalid'), '/subnets/snet-hub-lz-pro-con-forti-mng-01')] |
| properties.disableTcpStateTracking | ❌ |
| name | [parameters('networkInterfaces_vm_hub_lz_pro_spc1_fortimanager_01_mgmt_name')] |

</details>

<details><summary>💻 <strong>networkInterfaces_vm_hub_lz_pro_spc1_fw_01_mg_name</strong> — <em>Microsoft.Network/networkInterfaces</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.enableAcceleratedNetworking | ❌ |
| location | spaincentral |
| properties.ipConfigurations[0].properties.privateIPAllocationMethod | Dynamic |
| properties.ipConfigurations[0].id | [concat(resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_mg_name')), '/ipConfigurations/internal')] |
| properties.ipConfigurations[0].properties.privateIPAddress | 10.248.4.36 |
| name | [parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_mg_name')] |
| properties.ipConfigurations[0].properties.primary | ✅ |
| properties.ipConfigurations[0].properties.subnet.id | [concat(parameters('virtualNetworks_vnet_hub_lz_pro_spc1_con_01_externalid'), '/subnets/snet-hub-lz-pro-con-paloalto-mng-01')] |
| properties.enableIPForwarding | ❌ |
| kind | Regular |
| properties.disableTcpStateTracking | ❌ |
| properties.nicType | Standard |
| properties.ipConfigurations[0].name | internal |
| properties.ipConfigurations[0].properties.privateIPAddressVersion | IPv4 |
| properties.auxiliarySku | None |
| apiVersion | 2024-05-01 |
| type | Microsoft.Network/networkInterfaces |
| properties.ipConfigurations[0].type | Microsoft.Network/networkInterfaces/ipConfigurations |
| properties.auxiliaryMode | None |

</details>

<details><summary>💻 <strong>networkInterfaces_vm_hub_lz_pro_spc1_fw_01_trust_name</strong> — <em>Microsoft.Network/networkInterfaces</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.enableAcceleratedNetworking | ❌ |
| location | spaincentral |
| properties.ipConfigurations[0].properties.privateIPAllocationMethod | Dynamic |
| properties.ipConfigurations[0].id | [concat(resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_trust_name')), '/ipConfigurations/internal')] |
| properties.ipConfigurations[0].properties.privateIPAddress | 10.248.4.100 |
| name | [parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_trust_name')] |
| properties.ipConfigurations[0].properties.primary | ✅ |
| properties.ipConfigurations[0].properties.subnet.id | [concat(parameters('virtualNetworks_vnet_hub_lz_pro_spc1_con_01_externalid'), '/subnets/snet-hub-lz-pro-con-paloalto-trust-01')] |
| properties.enableIPForwarding | ❌ |
| kind | Regular |
| properties.disableTcpStateTracking | ❌ |
| properties.nicType | Standard |
| properties.ipConfigurations[0].name | internal |
| properties.ipConfigurations[0].properties.privateIPAddressVersion | IPv4 |
| properties.auxiliarySku | None |
| apiVersion | 2024-05-01 |
| type | Microsoft.Network/networkInterfaces |
| properties.ipConfigurations[0].type | Microsoft.Network/networkInterfaces/ipConfigurations |
| properties.auxiliaryMode | None |

</details>

<details><summary>💻 <strong>networkInterfaces_vm_hub_lz_pro_spc1_fw_01_untrust_name</strong> — <em>Microsoft.Network/networkInterfaces</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.enableAcceleratedNetworking | ❌ |
| location | spaincentral |
| properties.ipConfigurations[0].properties.privateIPAllocationMethod | Dynamic |
| properties.ipConfigurations[0].id | [concat(resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_untrust_name')), '/ipConfigurations/internal')] |
| properties.ipConfigurations[0].properties.privateIPAddress | 10.248.4.68 |
| name | [parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_untrust_name')] |
| properties.ipConfigurations[0].properties.primary | ✅ |
| properties.ipConfigurations[0].properties.subnet.id | [concat(parameters('virtualNetworks_vnet_hub_lz_pro_spc1_con_01_externalid'), '/subnets/snet-hub-lz-pro-con-paloalto-untrust-01')] |
| properties.enableIPForwarding | ❌ |
| kind | Regular |
| properties.disableTcpStateTracking | ❌ |
| properties.nicType | Standard |
| properties.ipConfigurations[0].name | internal |
| properties.ipConfigurations[0].properties.privateIPAddressVersion | IPv4 |
| properties.auxiliarySku | None |
| apiVersion | 2024-05-01 |
| type | Microsoft.Network/networkInterfaces |
| properties.ipConfigurations[0].type | Microsoft.Network/networkInterfaces/ipConfigurations |
| properties.auxiliaryMode | None |

</details>

<details><summary>💻 <strong>networkInterfaces_vm_hub_lz_pro_spc1_fw_02_mg_name</strong> — <em>Microsoft.Network/networkInterfaces</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.enableAcceleratedNetworking | ❌ |
| location | spaincentral |
| properties.ipConfigurations[0].properties.privateIPAllocationMethod | Dynamic |
| properties.ipConfigurations[0].id | [concat(resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_mg_name')), '/ipConfigurations/internal')] |
| properties.ipConfigurations[0].properties.privateIPAddress | 10.248.4.37 |
| name | [parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_mg_name')] |
| properties.ipConfigurations[0].properties.primary | ✅ |
| properties.ipConfigurations[0].properties.subnet.id | [concat(parameters('virtualNetworks_vnet_hub_lz_pro_spc1_con_01_externalid'), '/subnets/snet-hub-lz-pro-con-paloalto-mng-01')] |
| properties.enableIPForwarding | ❌ |
| kind | Regular |
| properties.disableTcpStateTracking | ❌ |
| properties.nicType | Standard |
| properties.ipConfigurations[0].name | internal |
| properties.ipConfigurations[0].properties.privateIPAddressVersion | IPv4 |
| properties.auxiliarySku | None |
| apiVersion | 2024-05-01 |
| type | Microsoft.Network/networkInterfaces |
| properties.ipConfigurations[0].type | Microsoft.Network/networkInterfaces/ipConfigurations |
| properties.auxiliaryMode | None |

</details>

<details><summary>💻 <strong>networkInterfaces_vm_hub_lz_pro_spc1_fw_02_trust_name</strong> — <em>Microsoft.Network/networkInterfaces</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.enableAcceleratedNetworking | ❌ |
| location | spaincentral |
| properties.ipConfigurations[0].properties.privateIPAllocationMethod | Dynamic |
| properties.ipConfigurations[0].id | [concat(resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_trust_name')), '/ipConfigurations/internal')] |
| properties.ipConfigurations[0].properties.privateIPAddress | 10.248.4.101 |
| name | [parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_trust_name')] |
| properties.ipConfigurations[0].properties.primary | ✅ |
| properties.ipConfigurations[0].properties.subnet.id | [concat(parameters('virtualNetworks_vnet_hub_lz_pro_spc1_con_01_externalid'), '/subnets/snet-hub-lz-pro-con-paloalto-trust-01')] |
| properties.enableIPForwarding | ❌ |
| kind | Regular |
| properties.disableTcpStateTracking | ❌ |
| properties.nicType | Standard |
| properties.ipConfigurations[0].name | internal |
| properties.ipConfigurations[0].properties.privateIPAddressVersion | IPv4 |
| properties.auxiliarySku | None |
| apiVersion | 2024-05-01 |
| type | Microsoft.Network/networkInterfaces |
| properties.ipConfigurations[0].type | Microsoft.Network/networkInterfaces/ipConfigurations |
| properties.auxiliaryMode | None |

</details>

<details><summary>💻 <strong>networkInterfaces_vm_hub_lz_pro_spc1_fw_02_untrust_name</strong> — <em>Microsoft.Network/networkInterfaces</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.enableAcceleratedNetworking | ❌ |
| location | spaincentral |
| properties.ipConfigurations[0].properties.privateIPAllocationMethod | Dynamic |
| properties.ipConfigurations[0].id | [concat(resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_untrust_name')), '/ipConfigurations/internal')] |
| properties.ipConfigurations[0].properties.privateIPAddress | 10.248.4.69 |
| name | [parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_untrust_name')] |
| properties.ipConfigurations[0].properties.primary | ✅ |
| properties.ipConfigurations[0].properties.subnet.id | [concat(parameters('virtualNetworks_vnet_hub_lz_pro_spc1_con_01_externalid'), '/subnets/snet-hub-lz-pro-con-paloalto-untrust-01')] |
| properties.enableIPForwarding | ❌ |
| kind | Regular |
| properties.disableTcpStateTracking | ❌ |
| properties.nicType | Standard |
| properties.ipConfigurations[0].name | internal |
| properties.ipConfigurations[0].properties.privateIPAddressVersion | IPv4 |
| properties.auxiliarySku | None |
| apiVersion | 2024-05-01 |
| type | Microsoft.Network/networkInterfaces |
| properties.ipConfigurations[0].type | Microsoft.Network/networkInterfaces/ipConfigurations |
| properties.auxiliaryMode | None |

</details>

<details><summary>🧩 <strong>networkSecurityGroups_nsg_spc1_pro_console_01_name</strong> — <em>Microsoft.Network/networkSecurityGroups</em></summary>

| Propiedad | Valor |
|----------|--------|
| location | spaincentral |
| properties.securityRules[0].properties.sourcePortRange | * |
| properties.securityRules[0].properties.sourceAddressPrefix | * |
| apiVersion | 2024-05-01 |
| properties.securityRules[0].properties.access | Allow |
| properties.securityRules[0].properties.destinationPortRanges[2] | 443 |
| type | Microsoft.Network/networkSecurityGroups |
| properties.securityRules[0].properties.destinationPortRanges[1] | 80 |
| properties.securityRules[0].properties.destinationAddressPrefix | * |
| properties.securityRules[0].name | AllowManagementconsole |
| properties.securityRules[0].id | [resourceId('Microsoft.Network/networkSecurityGroups/securityRules', parameters('networkSecurityGroups_nsg_spc1_pro_console_01_name'), 'AllowManagementconsole')] |
| properties.securityRules[0].properties.protocol | Tcp |
| properties.securityRules[0].properties.destinationPortRanges[0] | 22 |
| properties.securityRules[0].properties.priority | 100 |
| properties.securityRules[0].properties.direction | Inbound |
| properties.securityRules[0].type | Microsoft.Network/networkSecurityGroups/securityRules |
| name | [parameters('networkSecurityGroups_nsg_spc1_pro_console_01_name')] |

</details>

<details open><summary>💻 <strong>virtualMachines_vm_hub_lz_pro_spc1_fortimanager_01_name</strong> — <em>Microsoft.Compute/virtualMachines</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.storageProfile.osDisk.writeAcceleratorEnabled | ❌ |
| properties.osProfile.linuxConfiguration.patchSettings.patchMode | ImageDefault |
| location | spaincentral |
| properties.networkProfile.networkInterfaces[0].properties.primary | ✅ |
| apiVersion | 2024-11-01 |
| properties.storageProfile.imageReference.publisher | fortinet |
| properties.osProfile.computerName | activefgt |
| dependsOn[0] | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fortimanager_01_mgmt_name'))] |
| plan.name | fortinet-fortimanager |
| properties.osProfile.linuxConfiguration.enableVMAgentPlatformUpdates | ❌ |
| properties.diagnosticsProfile.bootDiagnostics.enabled | ❌ |
| plan.product | fortinet-fortimanager |
| properties.storageProfile.osDisk.createOption | FromImage |
| properties.priority | Regular |
| properties.networkProfile.networkInterfaces[0].id | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fortimanager_01_mgmt_name'))] |
| type | Microsoft.Compute/virtualMachines |
| properties.storageProfile.osDisk.osType | Linux |
| properties.osProfile.linuxConfiguration.disablePasswordAuthentication | ❌ |
| properties.osProfile.linuxConfiguration.provisionVMAgent | ✅ |
| properties.osProfile.requireGuestProvisionSignal | ✅ |
| properties.storageProfile.imageReference.sku | fortinet-fortimanager |
| properties.storageProfile.osDisk.caching | ReadWrite |
| properties.osProfile.linuxConfiguration.patchSettings.assessmentMode | ImageDefault |
| zones[0] | 2 |
| properties.storageProfile.imageReference.version | 7.0.12 |
| properties.storageProfile.osDisk.deleteOption | Detach |
| properties.storageProfile.imageReference.offer | fortinet-fortimanager |
| properties.hardwareProfile.vmSize | Standard_D4s_v3 |
| properties.extensionsTimeBudget | PT1H30M |
| properties.osProfile.adminUsername | AdminF0rti01 |
| properties.osProfile.allowExtensionOperations | ✅ |
| properties.storageProfile.osDisk.managedDisk.id | [resourceId('Microsoft.Compute/disks', 'vm-hub-lz-pro-spc1-forti-01_Disk')] |
| properties.storageProfile.osDisk.name | vm-hub-lz-pro-spc1-forti-01_Disk |
| name | [parameters('virtualMachines_vm_hub_lz_pro_spc1_fortimanager_01_name')] |
| plan.publisher | fortinet |

</details>

<details><summary>🧩 <strong>networkSecurityGroups_nsg_spc1_pro_console_01_name, /AllowManagementconsole</strong> — <em>Microsoft.Network/networkSecurityGroups/securityRules</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.destinationPortRanges[2] | 443 |
| properties.protocol | Tcp |
| name | [concat(parameters('networkSecurityGroups_nsg_spc1_pro_console_01_name'), '/AllowManagementconsole')] |
| properties.destinationAddressPrefix | * |
| properties.sourceAddressPrefix | * |
| properties.direction | Inbound |
| dependsOn[0] | [resourceId('Microsoft.Network/networkSecurityGroups', parameters('networkSecurityGroups_nsg_spc1_pro_console_01_name'))] |
| properties.sourcePortRange | * |
| type | Microsoft.Network/networkSecurityGroups/securityRules |
| properties.priority | 100 |
| apiVersion | 2024-05-01 |
| properties.access | Allow |
| properties.destinationPortRanges[1] | 80 |
| properties.destinationPortRanges[0] | 22 |

</details>

<details open><summary>💻 <strong>virtualMachines_vm_hub_lz_pro_spc1_fw_01_name</strong> — <em>Microsoft.Compute/virtualMachines</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.storageProfile.osDisk.writeAcceleratorEnabled | ❌ |
| properties.osProfile.linuxConfiguration.patchSettings.patchMode | ImageDefault |
| location | spaincentral |
| properties.networkProfile.networkInterfaces[0].properties.primary | ❌ |
| apiVersion | 2024-11-01 |
| properties.storageProfile.imageReference.publisher | paloaltonetworks |
| properties.osProfile.computerName | [parameters('virtualMachines_vm_hub_lz_pro_spc1_fw_01_name')] |
| dependsOn[0] | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_untrust_name'))] |
| properties.networkProfile.networkInterfaces[1].id | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_trust_name'))] |
| plan.name | byol |
| plan.product | vmseries-flex |
| properties.storageProfile.osDisk.createOption | FromImage |
| dependsOn[1] | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_trust_name'))] |
| properties.networkProfile.networkInterfaces[2].id | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_mg_name'))] |
| properties.networkProfile.networkInterfaces[0].id | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_untrust_name'))] |
| dependsOn[2] | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_01_mg_name'))] |
| properties.storageProfile.osDisk.osType | Linux |
| properties.osProfile.linuxConfiguration.disablePasswordAuthentication | ❌ |
| properties.osProfile.linuxConfiguration.provisionVMAgent | ✅ |
| properties.osProfile.requireGuestProvisionSignal | ✅ |
| properties.storageProfile.imageReference.sku | byol |
| properties.storageProfile.osDisk.caching | ReadWrite |
| properties.networkProfile.networkInterfaces[1].properties.primary | ❌ |
| type | Microsoft.Compute/virtualMachines |
| properties.osProfile.linuxConfiguration.patchSettings.assessmentMode | ImageDefault |
| zones[0] | 2 |
| properties.storageProfile.imageReference.version | 11.1.407 |
| properties.storageProfile.osDisk.deleteOption | Detach |
| properties.storageProfile.imageReference.offer | vmseries-flex |
| properties.hardwareProfile.vmSize | Standard_DS3_v2 |
| plan.publisher | paloaltonetworks |
| properties.osProfile.adminUsername | UserAdminIlunion$ |
| properties.networkProfile.networkInterfaces[2].properties.primary | ✅ |
| properties.osProfile.allowExtensionOperations | ✅ |
| properties.storageProfile.osDisk.managedDisk.id | [resourceId('Microsoft.Compute/disks', concat(parameters('virtualMachines_vm_hub_lz_pro_spc1_fw_01_name'), '-disk'))] |
| properties.storageProfile.osDisk.name | [concat(parameters('virtualMachines_vm_hub_lz_pro_spc1_fw_01_name'), '-disk')] |
| name | [parameters('virtualMachines_vm_hub_lz_pro_spc1_fw_01_name')] |

</details>

<details open><summary>💻 <strong>virtualMachines_vm_hub_lz_pro_spc1_fw_02_name</strong> — <em>Microsoft.Compute/virtualMachines</em></summary>

| Propiedad | Valor |
|----------|--------|
| properties.storageProfile.osDisk.writeAcceleratorEnabled | ❌ |
| properties.osProfile.linuxConfiguration.patchSettings.patchMode | ImageDefault |
| location | spaincentral |
| properties.networkProfile.networkInterfaces[0].properties.primary | ❌ |
| apiVersion | 2024-11-01 |
| properties.storageProfile.imageReference.publisher | paloaltonetworks |
| properties.osProfile.computerName | [parameters('virtualMachines_vm_hub_lz_pro_spc1_fw_02_name')] |
| dependsOn[0] | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_untrust_name'))] |
| properties.networkProfile.networkInterfaces[1].id | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_trust_name'))] |
| plan.name | byol |
| plan.product | vmseries-flex |
| properties.storageProfile.osDisk.createOption | FromImage |
| dependsOn[1] | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_trust_name'))] |
| properties.networkProfile.networkInterfaces[2].id | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_mg_name'))] |
| properties.networkProfile.networkInterfaces[0].id | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_untrust_name'))] |
| dependsOn[2] | [resourceId('Microsoft.Network/networkInterfaces', parameters('networkInterfaces_vm_hub_lz_pro_spc1_fw_02_mg_name'))] |
| properties.storageProfile.osDisk.osType | Linux |
| properties.osProfile.linuxConfiguration.disablePasswordAuthentication | ❌ |
| properties.osProfile.linuxConfiguration.provisionVMAgent | ✅ |
| properties.osProfile.requireGuestProvisionSignal | ✅ |
| properties.storageProfile.imageReference.sku | byol |
| properties.storageProfile.osDisk.caching | ReadWrite |
| properties.networkProfile.networkInterfaces[1].properties.primary | ❌ |
| type | Microsoft.Compute/virtualMachines |
| properties.osProfile.linuxConfiguration.patchSettings.assessmentMode | ImageDefault |
| zones[0] | 3 |
| properties.storageProfile.imageReference.version | 11.1.407 |
| properties.storageProfile.osDisk.deleteOption | Detach |
| properties.storageProfile.imageReference.offer | vmseries-flex |
| properties.hardwareProfile.vmSize | Standard_DS3_v2 |
| plan.publisher | paloaltonetworks |
| properties.osProfile.adminUsername | UserAdminIlunion$ |
| properties.networkProfile.networkInterfaces[2].properties.primary | ✅ |
| properties.osProfile.allowExtensionOperations | ✅ |
| properties.storageProfile.osDisk.managedDisk.id | [resourceId('Microsoft.Compute/disks', concat(parameters('virtualMachines_vm_hub_lz_pro_spc1_fw_02_name'), '-disk'))] |
| properties.storageProfile.osDisk.name | [concat(parameters('virtualMachines_vm_hub_lz_pro_spc1_fw_02_name'), '-disk')] |
| name | [parameters('virtualMachines_vm_hub_lz_pro_spc1_fw_02_name')] |

</details>


