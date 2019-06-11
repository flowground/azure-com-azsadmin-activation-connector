# ![LOGO](logo.png) AzureBridgeAdminClient **flow**ground Connector

## Description

A generated **flow**ground connector for the AzureBridgeAdminClient API (version 2016-01-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-Activation/2016-01-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:31+03:00

## API Description

AzureBridge Admin Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns the list of activations.

*Tags:* `Activations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - The resource group the resource is located under.
* `api-version` - _required_ - Client Api Version.

### Delete an activation.

*Tags:* `Activations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - The resource group the resource is located under.
* `activationName` - _required_ - Name of the activation.
* `api-version` - _required_ - Client Api Version.

### Returns activation name.

*Tags:* `Activations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - The resource group the resource is located under.
* `activationName` - _required_ - Name of the activation.
* `api-version` - _required_ - Client Api Version.

### Create a new activation.

*Tags:* `Activations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - The resource group the resource is located under.
* `activationName` - _required_ - Name of the activation.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-activation-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
