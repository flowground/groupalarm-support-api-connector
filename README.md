# ![LOGO](logo.png) groupalarm Support API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm Support API API (version 1.15.0).

Generated from: https://app.groupalarm.com/api/v1/support<br/>
Generated at: 2019-07-26T13:59:36+03:00

## API Description

The support service implements a way for our support agents to transparently work with the customer in their organization<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### AllowAccess
> Used by organizations admins to give our support access to their organization<br/>

*Tags:* `support`

#### Input Parameters
* `organizationID` - _required_

### DisallowAccess
> Used by organizations admins to remove our support's access to their organization<br/>

*Tags:* `support`

#### Input Parameters
* `organizationID` - _required_

## License

**flow**ground :- Telekom iPaaS / groupalarm-support-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
