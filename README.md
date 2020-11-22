# TETRIO-browser-rpc
![rpc](https://user-images.githubusercontent.com/14810839/99894328-26ceeb00-2c51-11eb-92a6-3476fa3cf268.png)

Discord rich presence for those who play TETR.IO in browser.

**NOTE:** this is heavily based on Jinzulen's Mangadex-RPC, which you can find [here](https://github.com/Jinzulen/Mangadex-RPC)

this script will allow you to display all the same presences that the official TETR.IO desktop client has, as well as some extras. it supports all the standard in-game and in-menu presences for all the gamemodes(as well as league queue), displays your account like the official client, and also has added states for watching replays, viewing the tetra channel menu, and playing ZEN while waiting in quickplay. it will also stop displaying the rich presence after the game's tab has been out of focus for 5 minutes or more, until focus returns.

How to use:
* have discord open

* have Java installed, then download and run [DiscordPipeSocket.jar](https://github.com/PATXS/TETRIO-browser-rpc/raw/main/DiscordPipeSocket.jar).

  * this will need to be running any time you play TETR.IO, but it runs silently in the background. you can run it once and forget, until you manually exit it or log out. if you're running windows and don't want to manually start it every time you boot up or log in, put it in `%appdata%\Microsoft\Windows\Start Menu\Programs\Startup` and it will run on boot.
  * (i did not make this program, i've only uploaded it to this repo to provide a permanent link to it.)
  
* have a userscript injector installed in your browser, such as tampermonkey ([chrome web store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)/[firefox add-on store](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)), and install the userscript from [here](https://raw.githubusercontent.com/PATXS/TETRIO-browser-rpc/main/TETRIO-RPC.js).

* if you're running firefox, go to `about:config` and change `network.websocket.allowInsecureFromHTTPS` to `true`.

that's all!

if anything ever stops working and i haven't fixed it, please open an issue!
