# ![LOGO](logo.png) Azure Activity Log Alerts **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Activity Log Alerts API (version 2017-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-activityLogAlerts_API/2017-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:25+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get a list of all activity log alerts in a subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Get a list of all activity log alerts in a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.

### Delete an activity log alert.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `activityLogAlertName` - _required_ - The name of the activity log alert.
* `api-version` - _required_ - Client Api Version.

### Get an activity log alert.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `activityLogAlertName` - _required_ - The name of the activity log alert.
* `api-version` - _required_ - Client Api Version.

### Updates an existing ActivityLogAlertResource's tags. To update other fields use the CreateOrUpdate method.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `activityLogAlertName` - _required_ - The name of the activity log alert.
* `api-version` - _required_ - Client Api Version.

### Create a new activity log alert or update an existing one.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `activityLogAlertName` - _required_ - The name of the activity log alert.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-activity-log-alerts-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
