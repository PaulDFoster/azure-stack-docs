---
title: Set-AksEdgeNodeConnectivityMode for AKS Edge
author: rcheeran
description: The Set-AksEdgeNodeConnectivityMode PowerShell command sets AksEdge Linux node connectivity mode.
ms.topic: reference
ms.date: 02/02/2023
ms.author: rcheeran 
ms.lastreviewed: 02/02/2023
#ms.reviewer: jeguan

---

# Set-AksEdgeNodeConnectivityMode

Sets tje AKS Edge Essentials Linux node connectivity mode.

## Syntax

```powershell
Set-AksEdgeNodeConnectivityMode
```

## Description

Sets the AKS Edge Essentials Linux node connectivity mode.


## Examples

### Turn off connectivity 

```powershell
Set-AksEdgeNodeConnectivityMode -mode "Off"
```


## Parameters

### -mode

This parameter specifies the connectivity mode. Expected values are 'on' or 'off'.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```


### Common parameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## Next steps

[AksEdge PowerShell Reference](./index.md)
