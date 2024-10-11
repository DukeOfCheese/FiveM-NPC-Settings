<img src="https://github.com/Gravxd/fivem-enginesound-menu/assets/75702884/95a09e7e-d8aa-4955-ae0a-ae1ce6a639d4" width="100" height="100"><br>
# chroma-NPC-settings - FiveM
Simple & straight forward toggleable NPC script with commands for your server administrators to turn on/off at will
Gets rid of useless loops on the client and disables / enables AI with a simple one-time function whilst also
Allowing server administrators to control the type of NPCs spawned

## Dependencies
- Standalone
- ox_lib

The default permission ace for toggling NPCs is `toggle-npc` - you can give this to a group such as:
`add_ace group.admin toggle-npc allow`

The default permission ace for NPC settings is `npc-settings` - you can give this to a group such as:
`add_ace group.admin npc-settings allow`

If you want to edit the permissions check such as for jobs or your framework, edit the `config.lua`
You can also edit the notification function to integrate your server's notification script - by default it just ox_lib notifications.
