---
id: campaign-reports-config
title: CampaignReportsConfig
pagination_label: CampaignReportsConfig
sidebar_label: CampaignReportsConfig
sidebar_class_name: powershellsdk
keywords: ['powershell', 'PowerShell', 'sdk', 'CampaignReportsConfig', 'CampaignReportsConfig'] 
slug: /tools/sdk/powershell/v3/models/campaign-reports-config
tags: ['SDK', 'Software Development Kit', 'CampaignReportsConfig', 'CampaignReportsConfig']
---


# CampaignReportsConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IdentityAttributeColumns** | **[]String** | list of identity attribute columns | [optional] 

## Examples

- Prepare the resource
```powershell
$CampaignReportsConfig = Initialize-CampaignReportsConfig  -IdentityAttributeColumns [firstname, lastname]
```

- Convert the resource to JSON
```powershell
$CampaignReportsConfig | ConvertTo-JSON
```


[[Back to top]](#) 

