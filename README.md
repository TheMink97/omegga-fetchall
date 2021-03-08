# omegga-fetchall
Fetches all players in your server to you or to a player you specify. 

## Usage
Syntax: `/fetchall [optional: playername]`

Example: `/fetchall cake` (Teleports all players in the server to the player cake)

Example: `/fetchall` (Teleports all players to you)

If no playername is provided, all players will be teleported to the player that used the command. Furthermore, the plugin can only be used by players who have been assigned roles. To add or remove roles that should be allowed to use the command, go to the Omegga WebUI. You can see how it's done in the next section. 

## Configuration
For /fetchall you can specify in the Omegga WebUI which roles have permission to use the command (hosts are an exception and can always use the command, regardless of their role). By default "Admins" can use the command, but more roles can be added by separating more roles with a comma. You can see an example here in the picture below:

<img src="https://i.gyazo.com/a78956d726353f19b3479056031c5762.png" width="512"/>
