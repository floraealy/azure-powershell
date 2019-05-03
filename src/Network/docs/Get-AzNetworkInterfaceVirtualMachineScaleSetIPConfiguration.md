---
external help file: Az.Network-help.xml
Module Name: Az.Network
online version: https://docs.microsoft.com/en-us/powershell/module/az.network/get-aznetworkinterfacevirtualmachinescalesetipconfiguration
schema: 2.0.0
---

# Get-AzNetworkInterfaceVirtualMachineScaleSetIPConfiguration

## SYNOPSIS
Get the specified network interface ip configuration in a virtual machine scale set.

## SYNTAX

### ListSubscriptionIdViaHost (Default)
```
Get-AzNetworkInterfaceVirtualMachineScaleSetIPConfiguration -NetworkInterfaceName <String>
 -ResourceGroupName <String> -VirtualMachineScaleSetName <String> -VirtualmachineIndex <String>
 [-Expand <String>] [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### GetSubscriptionIdViaHost
```
Get-AzNetworkInterfaceVirtualMachineScaleSetIPConfiguration -IPConfigurationName <String>
 -NetworkInterfaceName <String> -ResourceGroupName <String> -VirtualMachineScaleSetName <String>
 -VirtualmachineIndex <String> [-Expand <String>] [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### Get
```
Get-AzNetworkInterfaceVirtualMachineScaleSetIPConfiguration -IPConfigurationName <String>
 -NetworkInterfaceName <String> -ResourceGroupName <String> -SubscriptionId <String>
 -VirtualMachineScaleSetName <String> -VirtualmachineIndex <String> [-Expand <String>]
 [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### List
```
Get-AzNetworkInterfaceVirtualMachineScaleSetIPConfiguration -NetworkInterfaceName <String>
 -ResourceGroupName <String> -SubscriptionId <String> -VirtualMachineScaleSetName <String>
 -VirtualmachineIndex <String> [-Expand <String>] [-DefaultProfile <PSObject>] [<CommonParameters>]
```

## DESCRIPTION
Get the specified network interface ip configuration in a virtual machine scale set.

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: System.Management.Automation.PSObject
Parameter Sets: (All)
Aliases: AzureRMContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Expand
Expands referenced resources.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IPConfigurationName
The name of the ip configuration.

```yaml
Type: System.String
Parameter Sets: GetSubscriptionIdViaHost, Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NetworkInterfaceName
The name of the network interface.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
The name of the resource group.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionId
The subscription credentials which uniquely identify the Microsoft Azure subscription.
The subscription ID forms part of the URI for every service call.

```yaml
Type: System.String
Parameter Sets: Get, List
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VirtualmachineIndex
The virtual machine index.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VirtualMachineScaleSetName
The name of the virtual machine scale set.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.INetworkInterfaceIPConfiguration
## NOTES

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/az.network/get-aznetworkinterfacevirtualmachinescalesetipconfiguration](https://docs.microsoft.com/en-us/powershell/module/az.network/get-aznetworkinterfacevirtualmachinescalesetipconfiguration)
