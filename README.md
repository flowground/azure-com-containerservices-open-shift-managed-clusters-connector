# ![LOGO](logo.png) ContainerServiceClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ContainerServiceClient API (version 2018-09-30-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/containerservices-openShiftManagedClusters/2018-09-30-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:51+03:00

## API Description

The Container Service Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a list of OpenShift managed clusters in the specified subscription.

> Gets a list of OpenShift managed clusters in the specified subscription. The operation returns properties of each OpenShift managed cluster.

*Tags:* `OpenShiftManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists OpenShift managed clusters in the specified subscription and resource group.

> Lists OpenShift managed clusters in the specified subscription and resource group. The operation returns properties of each OpenShift managed cluster.

*Tags:* `OpenShiftManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.

### Deletes an OpenShift managed cluster.

> Deletes the OpenShift managed cluster with a specified resource group and name.

*Tags:* `OpenShiftManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the OpenShift managed cluster resource.

### Gets a OpenShift managed cluster.

> Gets the details of the managed OpenShift cluster with a specified resource group and name.

*Tags:* `OpenShiftManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the OpenShift managed cluster resource.

### Updates tags on an OpenShift managed cluster.

> Updates an OpenShift managed cluster with the specified tags.

*Tags:* `OpenShiftManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the OpenShift managed cluster resource.

### Creates or updates an OpenShift managed cluster.

> Creates or updates a OpenShift managed cluster with the specified configuration for agents and OpenShift version.

*Tags:* `OpenShiftManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the OpenShift managed cluster resource.

## License

**flow**ground :- Telekom iPaaS / azure-com-containerservices-open-shift-managed-clusters-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
