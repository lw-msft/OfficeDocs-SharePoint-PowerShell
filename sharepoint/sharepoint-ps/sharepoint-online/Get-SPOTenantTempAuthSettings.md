---
external help file: sharepointonline.xml
Module Name: Microsoft.Online.SharePoint.PowerShell
online version: https://learn.microsoft.com/powershell/module/sharepoint-online/get-spotenanttempauthsettings
applicable: SharePoint Online
title: Get-SPOTenantTempAuthSettings
schema: 2.0.0
author: laurenwong
ms.author: laurenwong
ms.reviewer:
manager: bhaveshd
---

# Get-SPOTenantTempAuthSettings

## SYNOPSIS

Gets the temp auth settings for the tenant.

## SYNTAX

```powershell
Get-SPOTenantTempAuthSettings [<CommonParameters>]
```

## DESCRIPTION

Gets the temp auth settings for the tenant, including whether temp auth is disabled overall, the allow list, and the deny list.

## EXAMPLES

### EXAMPLE 1

```powershell
Get-SPOTenantTempAuthSettings | ConvertTo-Json
```

Gets all the temp auth settings for the tenant. Note that this example uses `ConvertTo-Json` to display the settings in JSON format since more complex Allow or Deny lists may be hard to read as an object.

## RELATED LINKS

[Set-SPOTenantTempAuthSettings](Set-SPOTenantTempAuthSettings.md)