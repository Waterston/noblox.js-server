
# noblox.js-server

This is an improved example server that uses the [noblox.js](https://github.com/suufi/noblox.js) library, allowing users to execute site actions from in-game via HttpService.

## Instructions

Go to your environment variables settings and set `user_cookie` to the .ROBLOSECURITY cookie of the account you want to use. 
- The `auth_key` field is essentially a password for the site (to prevent strangers from accessing account functions). Ensure that it is an unique and randomly generated password.
- There is also an optional setting `maximum_rank` which can be used to prevent attacks. Users above this rank are immune from having their rank changed and attempts to change a user's rank to something above this will be rejected.~~

| Variable | Input | Description |
|-|-|-|
| `auth_key` | "AUTH_KEY" in `ServerScriptStorage/Main/Server` | This can be any unique password that is randomly generated by the user. |
| `maximum_rank` | 0-255 | An optional feature to prevent high-rank attacks. |
| `user_cookie` | .ROBLOSECURITY token | The token can be found in the .ROBLOSECURITY browser cookie of your selected account. Ensure that this is kept secret. |


**NOTE:** This fork of noblox.js-server is ready to be deployed on hosting platform such as Heroku and Glitch. Make sure you follow the instructions above to ensure a smooth deployment.
