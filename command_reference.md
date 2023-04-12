## Variables

### Engine

| Variable       | Type           | Min | Default | Max | Description |
| ---------------| ---------------|-----|---------|-----|-------------|
| allfaces       | Integer        | 0   | 0       | 1   | Allows texturing commands to apply the new texture to all the sides of the selected geometry.
| avatarfov      | Integer        | 10  | 40      | 100 | Field of view of the first person weapon.

### Game
*Coming soon™*

### Server

| Variable             | Type                 | Min | Default             | Max        | Description|
| ---------------------|----------------------|-----|---------------------|------------|------------|
| adminpass            | String               | N/A | N/A                 | N/A        | Allows you to gain administrator privileges by `/setmaster password_here`.
| autorecorddemo       | Integer              | 0   | 0                   | 1          | Whether or not to enable server-side demo recording automatically for every match (0 = always, 1 = when requested).
| botnames             | String               | N/A | N/A                 | N/A        | Generates a list of the bot names used in a server.
| ctftkpenalty         | Integer              | 0   | 1                   | 1          | Whether or not teamkilling the flag runner in CTF should disallow the teamkiller from picking up the flag.
| demodir              | Persistent string    | N/A | N/A                 | N/A        | Sets the directory to which demos are saved.
| lockmaprotation      | Integer              | N/A | N/A                 | N/A        | Whether or not to allow players to vote on maps not in the rotation (0 = any vote, 1 = master votes only, 2 = administrator votes only).
| mastername           | String               | N/A | master.tesseract.gg | N/A        | N/A | Sets the master server address.
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

## Commands

### Engine
*Coming soon™*

### Game
*Coming soon™*

### Server

| Command           | Arguments  | Description
| ------------------|------------|---------------------
| adduser           | 4          |
| clearipbans       | N/A        | Forgets about all of the issued IP bans.
| clearusers        | N/A        |
| ipban             | 1          | Issues an IP ban.
| maprotation       | 4          | Triggered when a game ends and intermission starts.
| maprotationreset  | N/A        | Resets map rotation in a server.
| startlistenserver | N/A        | Starts a listen server from within a running game client.
| stoplistenserver  | N/A        | Stops a listen server from within a running game client.
| teamkillkick      | 3          | Triggered when a map loading has finished.
| teamkillkickreset | N/A        | Triggered everytime our client spawns.
