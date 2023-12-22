---
created: 2023-12-14 01:44
tags:
  - Client
  - Insurance
  - P&C
updated: 2023-12-14T10:58
---

# Client Information

**Client Name**: `INPUT[text:client_name]`
**Address**: `INPUT[text:client_address]`
**Email**: `INPUT[text:email:client_email]`
**Phone**: `INPUT[text:phone_number]`
**DOB**: `INPUT[date:client_dob]::Date of Birth`

## Policy Details

**Policy Start Date**: `INPUT[date:policy_start_date]`
**Policy End Date**: `INPUT[date:policy_end_date]`
**Policy Type**: `INPUT[select:policy_type]::Policy Type | Home, Auto, Umbrella, Flood, Other`
**Policy Number**: `INPUT[text:policy_number]`

## Insurance History

**Prior Carrier**: `INPUT[text:prior_carrier]`
**Prior Carrier Premium**: `INPUT[number:prior_carrier_premium]`
**Current Carrier**: `INPUT[text:current_carrier]`
**Current Carrier Premium**: `INPUT[number:current_carrier_premium]`

### Historical Claims

- **Claim #1**: `INPUT[date:claim1_date]::Date` - `INPUT[text:claim1_description]::Description`
- **Claim #2**: `INPUT[date:claim2_date]::Date` - `INPUT[text:claim2_description]::Description`
- Add more as needed...

### Coverage Changes

- **Change #1**: `INPUT[date:coverage_change1_date]::Date` - `INPUT[text:coverage_change1_description]::Description`
- **Change #2**: `INPUT[date:coverage_change2_date]::Date` - `INPUT[text:coverage_change2_description]::Description`
- Add more as needed...

## Notes

`INPUT[textarea:notes]`

(Fields can be added or omitted based on specific client profiles and relevance to the current review or interaction. Use "Add more as needed..." to keep historical records ongoing.)