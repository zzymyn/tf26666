# Harder wave 666 and server.

If you know what you're doing with running a server and just need the pop file, it can be found at: [server/tf/scripts/population/mvm_ghost_town_6666.pop](server/tf/scripts/population/mvm_ghost_town_6666.pop)

Simply download this file and place in your server's tf/scripts/population folder.

## Installing and Running a Public TF2 Server (windows)

1. Checkout this repository somewhere.
2. Download steamcmd from: `https://steamcdn-a.akamaihd.net/client/installer/steamcmd.zip`
3. Extract `steamcmd.zip` to `./steamcmd/steamcmd.exe`
4. Open `update.bat`, this will download and install the latest tf2 server. You can run this again whenever you want to check for updates.
5. Copy file `server/tf/cfg/server_priv_template.cfg` to `server/tf/cfg/server_priv.cfg`.
6. Edit `server/tf/cfg/server_priv.cfg` to set your server name and password etc...
7. Open `run.bat` to start the server on Ghost Town running mission 6666.
8. The server listens on port `28000` by default, you will have to open this port through your router to allow others to join.
