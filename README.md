# ![LOGO](logo.png) Refuge Restrooms **flow**ground Connector

## Description

A generated **flow**ground connector for the Refuge Restrooms API (version v1).

Generated from: https://api.apis.guru/v2/specs/refugerestrooms.org/v1/swagger.json<br/>
Generated at: 2019-05-07T17:43:50+03:00

## API Description

REFUGE is a web application that seeks to provide safe restroom access for transgender, intersex, and gender nonconforming individuals.

## Authorization

This API does not require authorization.

## Actions

### Get all restroom records ordered by date descending.

*Tags:* `restrooms`

#### Input Parameters
* `page` - _optional_ - Page offset to fetch.
* `per_page` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - Pad a number of results.
* `ada` - _optional_ - Only return restrooms that are ADA accessible.
* `unisex` - _optional_ - Only return restrooms that are unisex.

### Search for restroom records updated or created on or after a given date

*Tags:* `restrooms`

#### Input Parameters
* `page` - _optional_ - Page offset to fetch.
* `per_page` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - Pad a number of results.
* `ada` - _optional_ - Only return restrooms that are ADA accessible.
* `unisex` - _optional_ - Only return restrooms that are unisex.
* `updated` - _optional_ - Return restroom records updated (rather than created) since given date
* `day` - _required_ - Day
* `month` - _required_ - Month
* `year` - _required_ - Year

### Search by location.

*Tags:* `restrooms`

#### Input Parameters
* `page` - _optional_ - Page offset to fetch.
* `per_page` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - Pad a number of results.
* `ada` - _optional_ - Only return restrooms that are ADA accessible.
* `unisex` - _optional_ - Only return restrooms that are unisex.
* `lat` - _required_ - latitude
* `lng` - _required_ - longitude

### Perform full-text search of restroom records.

*Tags:* `restrooms`

#### Input Parameters
* `page` - _optional_ - Page offset to fetch.
* `per_page` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - Pad a number of results.
* `ada` - _optional_ - Only return restrooms that are ADA accessible.
* `unisex` - _optional_ - Only return restrooms that are unisex.
* `query` - _required_ - Your search query.

## License

**flow**ground :- Telekom iPaaS / refugerestrooms-org-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
