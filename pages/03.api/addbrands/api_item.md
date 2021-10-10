---
title: AddBrand
---

! This API call is intended for internal use and VARs only, VARs will be required to contact us to activate this API endpoint.

### Purpose
Add Brand eg. Organisation/Company

### Required Parameters
* brand_name (string, 255)
* brand_bed_limit (numeric)

### Endpoint
https://cloud.completeacm.com/api/brands

### CURL Example

> curl -X POST -H 'Authorization: Bearer YOUR_ACCESS_TOKEN_HERE' -H Content-Type: application/json' -d '{<br/>
>    "brand_name": "Test Brand API",<br/>
>    "brand_bed_limit": "20"<br/>
> }' https://cloud.completeacm.com/api/brands -i<br/>

#### Example Response
> {<br/>
>    "brand_name": "Test Brand API",<br/>
>    "brand_bed_limit": "20",<br/>
>    "brand_status": "active",<br/>
>    "id": "4ce7a3ef-cae7-4770-8a39-a44d16bc6adb",<br/>
>    "updated_at": "2021-10-10T02:37:41.000000Z",<br/>
>    "created_at": "2021-10-10T02:37:41.000000Z"<br/>
>}