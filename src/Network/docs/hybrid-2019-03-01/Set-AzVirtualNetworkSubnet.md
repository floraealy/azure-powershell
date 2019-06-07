---
external help file:
Module Name: Az.Network
online version: https://docs.microsoft.com/en-us/powershell/module/az.network/set-azvirtualnetworksubnet
schema: 2.0.0
---

# Set-AzVirtualNetworkSubnet

## SYNOPSIS
Creates or updates a subnet in the specified virtual network.

## SYNTAX

### Update1 (Default)
```
Set-AzVirtualNetworkSubnet -ResourceGroupName <String> -SubscriptionId <String> -VirtualNetworkName <String>
 [-Name <String>] [-SubnetParameter <ISubnet>] [-DefaultProfile <PSObject>] [-AsJob] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### UpdateViaIdentityExpanded1
```
Set-AzVirtualNetworkSubnet -InputObject <INetworkIdentity> [-Name <String>] [-AddressPrefix <String>]
 [-DefaultSecurityRule <ISecurityRule[]>] [-DisableBgpRoutePropagation] [-Etag <String>] [-Id <String>]
 [-NetworkSecurityGroupEtag <String>] [-NetworkSecurityGroupId <String>]
 [-NetworkSecurityGroupLocation <String>] [-NetworkSecurityGroupPropertiesProvisioningState <String>]
 [-NetworkSecurityGroupTag <IResourceTags>] [-ProvisioningState <String>] [-ResourceGuid <String>]
 [-ResourceNavigationLink <IResourceNavigationLink[]>] [-Route <IRoute[]>] [-RouteTableEtag <String>]
 [-RouteTableId <String>] [-RouteTableLocation <String>] [-RouteTablePropertiesProvisioningState <String>]
 [-RouteTableTag <IResourceTags>] [-SecurityRule <ISecurityRule[]>]
 [-ServiceEndpoint <IServiceEndpointPropertiesFormat[]>] [-DefaultProfile <PSObject>] [-AsJob] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### UpdateExpanded1
```
Set-AzVirtualNetworkSubnet -ResourceGroupName <String> -SubscriptionId <String> -VirtualNetworkName <String>
 -SubnetName <String> [-Name <String>] [-AddressPrefix <String>] [-DefaultSecurityRule <ISecurityRule[]>]
 [-DisableBgpRoutePropagation] [-Etag <String>] [-Id <String>] [-NetworkSecurityGroupEtag <String>]
 [-NetworkSecurityGroupId <String>] [-NetworkSecurityGroupLocation <String>]
 [-NetworkSecurityGroupPropertiesProvisioningState <String>] [-NetworkSecurityGroupTag <IResourceTags>]
 [-ProvisioningState <String>] [-ResourceGuid <String>] [-ResourceNavigationLink <IResourceNavigationLink[]>]
 [-Route <IRoute[]>] [-RouteTableEtag <String>] [-RouteTableId <String>] [-RouteTableLocation <String>]
 [-RouteTablePropertiesProvisioningState <String>] [-RouteTableTag <IResourceTags>]
 [-SecurityRule <ISecurityRule[]>] [-ServiceEndpoint <IServiceEndpointPropertiesFormat[]>]
 [-DefaultProfile <PSObject>] [-AsJob] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity1
```
Set-AzVirtualNetworkSubnet -InputObject <INetworkIdentity> [-SubnetParameter <ISubnet>]
 [-DefaultProfile <PSObject>] [-AsJob] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Creates or updates a subnet in the specified virtual network.

## EXAMPLES

### Example 1: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

### Example 2: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

## PARAMETERS

### -AddressPrefix
The address prefix for the subnet.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -AsJob
Run the command as a job

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

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
Dynamic: False
```

### -DefaultSecurityRule
The default security rules of network security group.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.ISecurityRule[]
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -DisableBgpRoutePropagation
Gets or sets whether to disable the routes learned by BGP on that route table.
True means disable.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Etag
A unique read-only string that changes whenever the resource is updated.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Id
Resource ID.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -InputObject
Identity Parameter

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.INetworkIdentity
Parameter Sets: UpdateViaIdentityExpanded1, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
Dynamic: False
```

### -Name
The name of the resource that is unique within a resource group.
This name can be used to access the resource.

```yaml
Type: System.String
Parameter Sets: Update1, UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -NetworkSecurityGroupEtag
A unique read-only string that changes whenever the resource is updated.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -NetworkSecurityGroupId
Resource ID.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -NetworkSecurityGroupLocation
Resource location.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -NetworkSecurityGroupPropertiesProvisioningState
The provisioning state of the public IP resource.
Possible values are: 'Updating', 'Deleting', and 'Failed'.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -NetworkSecurityGroupTag
Resource tags.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.IResourceTags
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -ProvisioningState
The provisioning state of the resource.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -ResourceGroupName
The name of the resource group.

```yaml
Type: System.String
Parameter Sets: Update1, UpdateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -ResourceGuid
The resource GUID property of the network security group resource.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -ResourceNavigationLink
Gets an array of references to the external resources using subnet.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.IResourceNavigationLink[]
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Route
Collection of routes contained within a route table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.IRoute[]
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RouteTableEtag
Gets a unique read-only string that changes whenever the resource is updated.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RouteTableId
Resource ID.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RouteTableLocation
Resource location.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RouteTablePropertiesProvisioningState
The provisioning state of the resource.
Possible values are: 'Updating', 'Deleting', and 'Failed'.

```yaml
Type: System.String
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RouteTableTag
Resource tags.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.IResourceTags
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -SecurityRule
A collection of security rules of the network security group.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.ISecurityRule[]
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -ServiceEndpoint
An array of service endpoints.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.IServiceEndpointPropertiesFormat[]
Parameter Sets: UpdateViaIdentityExpanded1, UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -SubnetName
The name of the subnet.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -SubnetParameter
Subnet in a virtual network resource.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.ISubnet
Parameter Sets: Update1, UpdateViaIdentity1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
Dynamic: False
```

### -SubscriptionId
The subscription credentials which uniquely identify the Microsoft Azure subscription.
The subscription ID forms part of the URI for every service call.

```yaml
Type: System.String
Parameter Sets: Update1, UpdateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -VirtualNetworkName
The name of the virtual network.

```yaml
Type: System.String
Parameter Sets: Update1, UpdateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.ISubnet

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.INetworkIdentity

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20171001.ISubnet

## ALIASES

## RELATED LINKS
