## Variables

<details>
  <summary>Engine</summary>
  
| Variable       | Type           | Min | Default | Max | Description |
| ---------------| ---------------|-----|---------|-----|-------------|
| allfaces       | Integer        | 0   | 0       | 1   | Allows texturing commands to apply the new texture to all the sides of the selected geometry.
| avatarfov      | Integer        | 10  | 40      | 100 | Field of view of the first person weapon.

</details>

<details>
  <summary>Game</summary>
  
| Variable            | Type               | Min | Default | Max         | Description |
| --------------------|--------------------|-----|---------|-------------|-------------|
| aidebug             | Integer            | 0   | 0       | 6           |
| aiforcegun          | Integer            | -1  | -1      | Max weapons |
| allycrosshair       | Persistent Integer | 0   | 1       | 1
| animoverride        | Integer            |-1   | 0       | Max animations
| autoauth            | Persistent integer | 0   | 1       | 1
| autoswitch          | Persistent integer | 0   | 1       | 1
| blood               | Persistent integer | 0   | 1       | 1
| chatsound           | Persistent integer | 0   | 1       | 1
| deadpush            | Persistent integer | 1   | 2       | 20
| deathfromabove      | Persistent integer | 0   | 1       | 1
| dropwaypoints       | Integer            | 0   | 1       | 1
| footstepssound      | Persistent integer | 0   | 1       | 1
| forceplayermodels   | Persistent integer | 0   | 0       | 1
| gore                | Persistent integer | 0   | 1       | 1
| goreeffect          | Persistent integer | N/A | N/A     | N/A
| hidedead            | Persistent integer | 0   | 0       | 1
| highlightscore      | Persistent integer | 0   | 1       | 1
| hitcrosshair        | Persistent integer | 0   | 400     | 1000
| hitsound            | Persistent integer | 0   | 0       | 2
| hudgun              | Persistent integer | 0   | 1       | 1
| hudgunsway          | Persistent integer | 0   | 1       | 1
| itemtrans           | Persistent integer | 0   | 1       | 1
| killsound           | Persistent integer | 0   | 1       | 2
| maxradarscale       | Persistent integer | 0   | 1024    | 10000
| minimapalpha        | Persistent float   | 0   | 1       | 1
| minradarscale       | Persistent integer | 0   | 384     | 10000
| muzzleflash         | Persistent integer | 0   | 1       | 1
| playercolor         | Persistent integer | 0   | 4       | Max colors
| playercolorblue     | Persistent integer | 0   | 0       | Max blue colors
| playercolorred      | Persistent integer | 0   | 0       | Max red colors
| playermodel         | Persistent integer | 0   | 0       | Max player models
| playersearch        | Persistent integer | 0   | 3       | 10
| playheadshotsound   | Persistent integer | 0   | 1       | 2
| radarteammates      | Persistent integer | 0   | 1       | 1
| ragdoll             | Persistent integer | 0   | 1       | 1
| ragdollfade         | Persistent integer | 0   | 400     | 5000
| ragdollmillis       | Persistent integer | 0   | 10000   | 300000
| regensound          | Persistent integer | 0   | 1       | 1
| showclientnum       | Persistent integer | 0   | 1       | 1
| showconnecting      | Persistent integer | 0   | 1       | 1
| showmodeinfo        | Persistent integer | 0   | 1       | 1
| showping            | Persistent integer | 0   | 1       | 1
| showpj              | Persistent integer | 0   | 1       | 1
| showservinfo        | Persistent integer | 0   | 1       | 1
| showspectators      | Persistent integer | 0   | 1       | 1
| showwaypoints       | Persistent integer | 0   | 1       | 1
| showwaypointsradius | Persistent integer | 0   | 200     | 10000
| smoothdist          | Persistent integer | 0   | 32      | 64
| smoothmove          | Persistent integer | 0   | 75      | 100
| specmode            | Integer            | 0   | 0       | 2
| swayrollfactor      | Floating point     | 1   | 3       | 30
| swayside            | Floating point     | 0   | 0.06f   | 1
| swaystep            | Floating point     | 1   | 39.2f   | 1
| swayup              | Floating point     | -1  | 0.11f   | 1
| teamcolortext       | Persistent integer | 0   | 1       | 1
| teleteam            | Integer            | 0   | 1       | 1
| testanims           | Integer            | 0   | 0       | 1
| testpitch           | Integer            | -90 | 0       | 90
  
</details>

<details>
  <summary>Server</summary>

| Variable             | Type                 | Min | Default             | Max        | Description|
| ---------------------|----------------------|-----|---------------------|------------|------------|
| adminpass            | String               | N/A | N/A                 | N/A        | Allows you to gain administrator privileges by `/setmaster password_here`.
| autorecorddemo       | Integer              | 0   | 0                   | 1          | Whether or not to enable server-side demo recording automatically for every match (0 = always, 1 = when requested).
| botnames             | String               | N/A | N/A                 | N/A        | Generates a list of the bot names used in a server.
| ctftkpenalty         | Integer              | 0   | 1                   | 1          | Whether or not teamkilling the flag runner in CTF should disallow the teamkiller from picking up the flag.
| demodir              | Persistent string    | N/A | N/A                 | N/A        | Sets the directory to which demos are saved.
| lockmaprotation      | Integer              | N/A | N/A                 | N/A        | Whether or not to allow players to vote on maps not in the rotation (0 = any vote, 1 = master votes only, 2 = administrator votes only).
| mastername           | String               | N/A | master.tesseract.gg | N/A        | Sets the master server address.
| masterport           | Integer              | 1   | 41999               | 0xFFFF     | Sets the master server port.
| maxclients           | Integer              | 0   | 8                   | 128        | Max players a server can accept.
| maxdupclients        | Integer              | 0   | 0                   | 128        | Maximum number of duplicate clients allowed on a server.
| maxdemos             | Integer              | 0   | 5                   | 25         | Max demos a server can store.
| maxdemosize          | Integer              | 0   | 16                  | 31         | Max size of a demo.
| modifiedmapspectator | Integer              | 0   | 1                   | 2          | Whether or not to automatically spectate players who are playing on a modified version of the current map.
| overtime             | Integer              | 0   | 1                   | 1          | Whether or not overtime is enabled for matches.
| persistteams         | Integer              | 0   | 1                   | 1          | Whether or not teams should persist across matches and avoid autobalancing.
| publicserver         | Integer              | 0   | 1                   | 2          | Level of freedom in the server: when set to 0, allows `/setmaster 1` and locked/private modes. When set to 1, can only gain master by `/auth` or administrator privileges, and does not allow locked/private modes. When set to 2, allows `/setmaster 1` but disallows private modes.
| restrictdemos        | Integer              | 0   | 1                   | 1          | Controls whether administrator privileges are necessary to record a demo.
| restrictgamespeed    | Integer              | 0   | 1                   | 1          | Controls whether master privileges are necessary to change game speed.
| restrictpausegame    | Integer              | 0   | 1                   | 1          | Controls whether master privileges are necessary to pause the current game.
| serverauth           | String               | N/A | N/A                 | N/A        | Domain to use for local authkeys to the server so people can authenticate by `/auth domain_here`; the string must not be empty and should be unique to your server.
| serverbotbalance     | Integer              | 0   | 1                   | 1          | Enables automatic team balancing for bots if 1 and disables it if 0. Only privileged or local players can use this command.
| serverbotlimit       | Integer              | 0   | 8                   | 32         | Max number of bots a server can accept.
| serverip             | String               | N/A | N/A                 | N/A        | Sets the server IP.
| servermotd           | String               | N/A | N/A                 | N/A        | Optional console message to send to players on connect.
| servername           | String               | N/A | N/A                 | N/A        | Name of the server which is primarily displayed on the server browser. In Tesseract this variable is `serverdesc`.
| serverpass           | String               | N/A | N/A                 | N/A        | Optional password required to connect to the server.
| serverport           | Integer              | 0   | 4200                | 0xFFFF     | Specifies the port the server we are hosting should bind/listen to.
| serveruprate         | Integer              | 0   | 0                   | 2147483647 |
| spectatorchat        | Integer              | 0   | 0                   | 1          | Whether or not chat messages sent by spectators should be visible to players. When 0, spectators are allowed to chat with players (default); when 1, spectators are only allowed to chat with other spectators.
| updatemaster         | Integer              | 0   | 1                   | 1          | Toggles whether or not the server should report to the master server.

</details>

## Commands

<details>
  <summary>Engine</summary>
  Coming soon™
</details>

<details>
  <summary>Game</summary>

| Command                 | Arguments  | Description
| ------------------------|------------|---------------------
| allowthirdperson        | N/A        | Command that returns a boolean value: 1 if `thirdperson` is allowed, 0 if not.
| auth                    |
| authkey                 |
| authkick                |
| botadd                  | 1          | Adds a bot with a random player model and name and the skill specified by the first argument.
| botbalance              |
| botdel                  | N/A        | Kicks the most recent bot that was added.
| botlimit                |            |
| checkmaps               |            |
| clearbans               | N/A        | Clears every ban that has been issued. Bans are automatically cleared when a server is empty.
| cleardemos              | N/A        | Clears all demos saved in a server.
| clearwaypoints          | N/A        | Clears all waypoints without needing to reload a map.
| clearwpcache            |            | Clears waypoints cache.
| cycleweapon             |            |
| dauth                   |            |
| dauthkick               |            |
| delselwaypoints         | N/A        | Clears waypoints inside grid selection.
| dropflag                | N/A        | Drops the flag we are holding in CTF modes.
| follow                  | N/A        |
| gamespeed               |            |
| genauthkey              |            |
| getaccuracy             |            |
| getclientammo           |            |
| getclientcolor          |            |
| getclientcolorname      |            |
| getclientdeaths         |            |
| getclientfrags          |            |
| getclienthealth         |            |
| getclientmaxhealth      |            |
| getclientmodel          |            |
| getclientname           |            |
| getclientnum            |            |
| getclientpowerup        |            |
| getclientpowerupmillis  |            |
| getclientprivilege      |            |
| getclientscore          |            |
| getclientshield         |            |
| getclientteam           |            |
| getclientweapon         |            |
| getdeaths               |            |
| getdemo                 |            |
| getflags                |            |
| getfollow               |            |
| getfrags                |            |
| getkillfeedactor        |            |
| getkillfeedcrit         |            |
| getkillfeedtarget       |            |
| getkillfeedweap         |            |
| getmap                  | N/A        | Downloads the map that is available on the server if it has been sent with `sendmap`. Only used in the map editor.
| getmastermode           |            |
| getmastermodename       |            |
| getmode                 |            |
| getmodename             |            |
| getmodeprettyname       |            |
| getmutators             |            |
| getmutdesc              |            |
| getname                 |            |
| getnextmode             |            |
| getnextmutators         |            |
| getplayercolor          |            |
| getscorelimit           |            |
| getservauth             |            |
| getservdesc             |            |
| getteam                 |            |
| getteamname             |            |
| getteamscore            |            |
| gettotaldamage          |            |
| gettotalshots           |            |
| getweapon               |            |
| goto                    |            |
| gotosel                 |            |
| hasauthkey              |            |
| hashpwd                 |            |
| ignore                  |            |
| intermission            | N/A        | Returns a boolean value: 1 if the game has ended (intermission), 0 if not.
| isadmin                 |            |
| isai                    |            |
| isauth                  |            |
| isdead                  |            |
| isignored               |            |
| islagged                |            |
| ismaster                |            |
| isspectator             |            |
| kick                    |            |
| listclients             |            |
| listdemos               |            |
| loadwaypoints           |            |
| loopscoreboard          |            |
| map                     |            |
| mastermode              |            |
| melee                   |            |
| mode                    |            |
| movewaypoints           |            |
| mutator                 |            |
| mute                    |            |
| name                    |            |
| nextfollow              |            |
| nextweapon              |            |
| numscoreboard           |            |
| paused                  |            |
| pausegame               |            |
| prettygamespeed         |            |
| primary                 | N/A        | Fires the primary fire of the selected weapon. In other Cube games, this command is usually replaced with `shoot`. If used when dead, the player is also respawned.
| recorddemo              |            |
| refreshscoreboard       |            |
| registertip             |            |
| respawn                 | N/A        | Respawns our client if the spawn delay has expired.
| sauth                   |            |
| sauthkick               |            |
| saveauthkeys            |            |
| savewaypoints           |            |
| say                     |            |
| sayteam                 |            |
| scoreboardhighlight     |            |
| scoreboardmap           |            |
| scoreboardmode          |            |
| scoreboardmultiplayer   |            |
| scoreboardping          |            |
| scoreboardpj            |            |
| scoreboardservinfo      |            |
| scoreboardshowclientnum |            |
| scoreboardshowfrags     |            |
| scoreboardstatus        |            |
| scoreboardtime          |            |
| secondary               | N/A        | Fires the secondary fire of the selected weapon. If used when dead, the player is also respawned.
| sendmap                 | N/A        | Sends the map to the server so that it can be downloaded with `getmap`.
| servcmd                 |            |
| servinfoicon            |            |
| servinfomastermode      |            |
| servinfomastermodename  |            |
| servinfomode            |            |
| servinfomodename        |            |
| servinfotime            |            |
| setmaster               |            |
| setteam                 |            |
| setweapon               |            |
| spectating              | N/A        | Returns a boolean value: 1 if our client is spectating, 0 if not.
| spectator               |            |
| stopdemo                |            |
| suicide                 | N/A        | Immediately kills our player.
| taunt                   | N/A        | Plays the current character's taunt animation and voice line if available.
| team                    |            |
| timeremaining           |            |
| unignore                |            |
| unmute                  |            |
| useitem                 |            |
| weapon                  |            |
| whisper                 |            |

</details>

<details>
  <summary>Server</summary>

| Command           | Arguments  | Description
| ------------------|------------|---------------------
| adduser           | 4          |
| clearipbans       | N/A        | Forgets about all of the issued IP bans.
| clearusers        | N/A        |
| ipban             | 1          | Issues an IP ban.
| maprotation       | 4          | Defines server's map rotation.
| maprotationreset  | N/A        | Resets map rotation in a server.
| startlistenserver | N/A        | Starts a listen server from within a running game client.
| stoplistenserver  | N/A        | Stops a listen server from within a running game client.
| teamkillkick      | 3          | Specifies the gamemode in which the teamkill limit is used, the maximum number of teamkills a player is allowed to commit and the duration of teamkill auto-kicks.
| teamkillkickreset | N/A        | Removes automatic kicks triggered by an excessive amount of teamkills (specified with `teamkillkick`).

</details>

## CubeScript Hooks

<details>
  <summary>Engine</summary>
  
| Name              | Description                                                                                              
| ------------------|----------------------------------------------------------------------------------------------------|
| resetgl           | Triggers when we apply settings changes and we need to reset OpenGL.                               |
| resetshaders      | Triggers when we apply settings changes and we need to reset the shaders.                          |
| resetsound        | Triggers when we apply settings changes and we need to reset audio.                                |

</details>

<details>
  <summary>Game</summary>
  
| Name              | Description                                                                                              
| ------------------|----------------------------------------------------------------------------------------------------|
| on_connect        | Triggers every time our client successfully connects to a server, being it local or not.           |
| on_death          | Triggers each time our client dies.                                                                |
| on_disconnect     | Triggers every time our client disconnects from a server, being it local or not.                   |
| on_edittoggle     | Triggers when we enter edit mode (originally `edittoggled`).                                       |
| on_intermission   | Triggers when a game ends and intermission starts (originally `intermission`).                     |
| on_kill           | Triggers when our client kills another.                                                            |
| on_killfeed       | Triggers each time a player dies.                                                                  |
| on_mainmenutoggle | Triggers when the main menu is opened (usually by pressing "ESC") (originally `mainmenutoggled`).  |
| on_mapstart       | Triggers when a map has finished loading (originally `mapstart`).                                  |
| on_spawn          | Triggers when our client spawns.                                                                   |
| on_suicide        | Triggers each time we kill our own player.                                                         |
| on_teamkill       | Triggers each time we kill an ally.                                                                |

</details>
