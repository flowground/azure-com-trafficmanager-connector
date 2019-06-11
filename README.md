# ![LOGO](logo.png) TrafficManagerManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the TrafficManagerManagementClient API (version 2018-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/trafficmanager/2018-04-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:33+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Checks the availability of a Traffic Manager Relative DNS name.

*Tags:* `Profiles`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Gets the default Geographic Hierarchy used by the Geographic traffic routing method.

*Tags:* `GeographicHierarchies`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Delete a subscription-level key used for Real User Metrics collection.

*Tags:* `RealUserMetrics`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Get the subscription-level key used for Real User Metrics collection.

*Tags:* `RealUserMetrics`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a subscription-level key used for Real User Metrics collection.

*Tags:* `RealUserMetrics`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all Traffic Manager profiles within a subscription.

*Tags:* `Profiles`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all Traffic Manager profiles within a resource group.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager profiles to be listed.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a Traffic Manager profile.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager profile to be deleted.
* `profileName` - _required_ - The name of the Traffic Manager profile to be deleted.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a Traffic Manager profile.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager profile.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Update a Traffic Manager profile.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager profile.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a Traffic Manager profile.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager profile.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets latest heatmap for Traffic Manager profile.

*Tags:* `HeatMaps`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager endpoint.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `heatMapType` - _required_ - The type of HeatMap for the Traffic Manager profile.
    Possible values: default.
* `topLeft` - _optional_ - The top left latitude,longitude pair of the rectangular viewport to query for.
* `botRight` - _optional_ - The bottom right latitude,longitude pair of the rectangular viewport to query for.
* `api-version` - _required_ - Client Api Version.

### Deletes a Traffic Manager endpoint.

*Tags:* `Endpoints`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager endpoint to be deleted.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `endpointType` - _required_ - The type of the Traffic Manager endpoint to be deleted.
* `endpointName` - _required_ - The name of the Traffic Manager endpoint to be deleted.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a Traffic Manager endpoint.

*Tags:* `Endpoints`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager endpoint.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `endpointType` - _required_ - The type of the Traffic Manager endpoint.
* `endpointName` - _required_ - The name of the Traffic Manager endpoint.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Update a Traffic Manager endpoint.

*Tags:* `Endpoints`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager endpoint to be updated.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `endpointType` - _required_ - The type of the Traffic Manager endpoint to be updated.
* `endpointName` - _required_ - The name of the Traffic Manager endpoint to be updated.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a Traffic Manager endpoint.

*Tags:* `Endpoints`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager endpoint to be created or updated.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `endpointType` - _required_ - The type of the Traffic Manager endpoint to be created or updated.
* `endpointName` - _required_ - The name of the Traffic Manager endpoint to be created or updated.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-trafficmanager-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
