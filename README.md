# ![LOGO](logo.png) Adyen Checkout Utility Service **flow**ground Connector

## Description

A generated **flow**ground connector for the Adyen Checkout Utility Service API (version 1).

Generated from: https://api.apis.guru/v2/specs/adyen.com/CheckoutUtilityService/1/openapi.json<br/>
Generated at: 2019-05-07T17:34:47+03:00

## API Description

A web service containing utility functions available for merchants integrating with Checkout APIs.
## Authentication
Each request to the Checkout Utility API must be signed with an API key. For this, obtain an API Key from your Customer Area, as described in [How to get the Checkout API key](https://docs.adyen.com/developers/user-management/how-to-get-the-checkout-api-key). Then set this key to the `X-API-Key` header value, for example:

```
curl
-H "Content-Type: application/json" \
-H "X-API-Key: Your_Checkout_API_key" \
...
```
Note that when going live, you need to generate a new API Key to access the [live endpoints](https://docs.adyen.com/developers/api-reference/live-endpoints).

## Versioning
Checkout API supports versioning of its endpoints through a version suffix in the endpoint URL. This suffix has the following format: "vXX", where XX is the version number.

For example:
```
https://checkout-test.adyen.com/v1/originKeys
```

## Authorization

This API does not require authorization.

## Actions

### Create originKey values for one or more merchant domains.

> This operation takes the origin domains and returns a JSON object containing the corresponding origin keys for the domains.

## License

**flow**ground :- Telekom iPaaS / adyen-com-checkout-utility-service-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
