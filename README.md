
# noblox.js-server

  

[![ROBLOX API Discord](https://img.shields.io/badge/discord-roblox%20api%20chat-blue.svg?style=flat-square)](https://discord.gg/EDXNdAT)

  

This is an improved example server that uses the [noblox.js](https://github.com/suufi/noblox.js) library, allowing users to execute site actions from in-game via HttpService.

~~## Instructions~~

~~- Go to `config.json` and set `user_cookie` to the .ROBLOSECURITY cookie of the account you want to use. 
- The `auth_key` field is essentially a password for the site (to prevent strangers from accessing account functions).  I recommend generating a random string or just smashing your keyboard since this will typically be accessed by a script from Roblox.
- There is also an optional setting `maximum_rank` which can be used to prevent attacks. User's above this rank are immune from having their rank changed and attempts to change a user's rank to something above this will be rejected.~~

~~**NOTE:** If you choose to use Hosting such as glitch.me for this server, it is *highly* recommended you move the `config.json` variables into a `.env` file for added security.
(Note that if you do this you must update the `.js` files to point to `process.env` as the new `configs` file.
i.e. `config.auth_key` will become `process.env.auth_key`~~
