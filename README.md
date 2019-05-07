# ![LOGO](logo.png) SubscriptionClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionClient API (version 2016-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/resources-subscriptions/2016-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:47+03:00

## API Description

All resource groups and resources exist within subscriptions. These operation enable you get information about your subscriptions and tenants. A tenant is a dedicated instance of Azure Active Directory (Azure AD) for your organization.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Microsoft.Resources REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.

### Gets all subscriptions for a tenant.

*Tags:* `Subscriptions`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.

### Gets details about a specified subscription.

*Tags:* `Subscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `api-version` - _required_ - The API version to use for the operation.

### Gets all available geo-locations.

> This operation provides all the locations that are available for resource providers; however, each resource provider may support a subset of this list.

*Tags:* `Subscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `api-version` - _required_ - The API version to use for the operation.

### Gets the tenants for your account.

*Tags:* `Tenants`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.

## License

**flow**ground :- Telekom iPaaS / azure-com-resources-subscriptions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
