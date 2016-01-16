## Update User Profile
Update the profile for a specific user account.

`PUT /account/{userId}/profile`

## Headers
- **AuthSessionId** - Identifier for current session
- **AuthSessionSecret** - Secret for current session

## Parameters
- **userId** - Identifier for current user

## Body
- **username** - Username to update to
- **email** - E-mail address to update to

## Example Request
`GET /account/1692/profile`
```
{
 username: "NewUsername",
 email: "Email@Email.com"
}
```

## Example Error
`GET /account/10/profile`
```
{
 error: "Could not find user profile"
}
```

## Example Response
`GET /account/1692/profile`
```
{
 success: true
}
```
