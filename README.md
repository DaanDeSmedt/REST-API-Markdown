## Get User Profile
Get the profile for a specific sessions user account.

**URL** | /api/v1/profile
--- | ---
**Method** | GET
**Content-Type** | application/json
**Authentication** | Required

### Parameters
 Key | Type | Description
--- | --- | ---
**sessionId** | String | Session identifier
**sessionSecret** | String | Session secret

### Response
 Key | Type | Description
--- | --- | ---
**userId** | Integer | User identifier for account
**username** | String | Username for account
**email** | String | E-mail address for account
