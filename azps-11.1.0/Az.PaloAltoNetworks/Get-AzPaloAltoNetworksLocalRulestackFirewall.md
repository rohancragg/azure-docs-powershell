---
external help file: 
Module Name: Az.PaloAltoNetworks
online version: https://learn.microsoft.com/powershell/module/az.paloaltonetworks/get-azpaloaltonetworkslocalrulestackfirewall
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/PaloAltoNetworks/PaloAltoNetworks/help/Get-AzPaloAltoNetworksLocalRulestackFirewall.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/PaloAltoNetworks/PaloAltoNetworks/help/Get-AzPaloAltoNetworksLocalRulestackFirewall.md
---

# Get-AzPaloAltoNetworksLocalRulestackFirewall

## SYNOPSIS
List of Firewalls associated with Rulestack

## SYNTAX

```
Get-AzPaloAltoNetworksLocalRulestackFirewall -LocalRulestackName <String> -ResourceGroupName <String>
 [-SubscriptionId <String[]>] [-DefaultProfile <PSObject>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
List of Firewalls associated with Rulestack

## EXAMPLES

### Example 1: List of Firewalls associated with Rulestack.
```powershell
Get-AzPaloAltoNetworksLocalRulestackFirewall -LocalRulestackName azps-panlr -ResourceGroupName azps_test_group_pan
```

```output
azps-firewall(azps_test_group_pan)
```

List of Firewalls associated with Rulestack.

## PARAMETERS

### -DefaultProfile
The DefaultProfile parameter is not functional.
Use the SubscriptionId parameter when available if executing the cmdlet against a different subscription.

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

### -LocalRulestackName
LocalRulestack resource name

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
The name is case insensitive.

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
The ID of the target subscription.

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: (Get-AzContext).Subscription.Id
Accept pipeline input: False
Accept wildcard characters: False
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
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.PaloAltoNetworks.Models.Api20220829.IListFirewallsResponse

## NOTES

ALIASES

## RELATED LINKS

