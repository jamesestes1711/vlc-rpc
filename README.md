# VLC-RPC
Updated Discord rich presence for VLC media player.

This is a modified version of the [Pigpog/vlc-discord-rpc project](https://github.com/Pigpog/vlc-discord-rpc), which is no longer being actively maintained. We have updated and enhanced the project by adding new features, such as album and show covers. 

![image](https://user-images.githubusercontent.com/61550272/234398623-02c343fa-c500-421c-a7a8-cb4d33f88a81.png)
![image](https://user-images.githubusercontent.com/61550272/234403580-4a910bd7-41a5-4ceb-8a31-180c2efda417.png)


## Setup
1. Download the code from this repository, then unzip it.
2. Install [Node.js](https://nodejs.org/en/download).
3. Make an application and get your [Discord Application ID](https://discord.com/developers/applications). The name you choose for the application will be what shows in your status.
4. Retrieve your [Spotify API key](https://developer.spotify.com/documentation/web-api/tutorials/getting-started).
5. Add both of these values in the `./Storage/config.js` file under the `richPresenceSettings` and `spotify` area.
6. Open a terminal, move to the folder you downloaded from this repository, and run `npm i` then run `node .`.

