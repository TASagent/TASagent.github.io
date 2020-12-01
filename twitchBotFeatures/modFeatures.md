# TASagent Twitchbot Mod Features

Features available to Moderators

## User Permissions

User access to the bot is gated through several tiers of access.  From most to least powerful, they are: _administrator_, _moderator_, _elevated_, _normal_, and _restricted_.

### User Permission Management

Moderators and Admins can adjust the permissions of users

* `!permit <user>` - Increase non-mod user permissions by a level
    * Aliases: `!elevate`, `!promote`
* `!revoke <user>` - Decrease non-mod user permissions by a level
    * Alias: `!demote`
* `!restrict <user>` - Sets user permissions to Restricted

Admins alone can grant and revoke moderator permissions

* `!mod <user>` - Sets a user to the Mod tier
* `!unmod <user>` - Removes a user from the Mod tier

## TTS Management

* `!set tts enabled` - Enables TTS
* `!set tts disabled` - Disables TTS
* `!set tts timeout <timeout>` -  Sets the per-user TTS timeout (in seconds)


## Command Management

* `!add <command> <commandText>` - Adds a new command
* `!edit <command> <commandText>` - Edits the text of a command
* `!remove <command>` - Removes a command
* `!enable <command>` - Enables an existing (disabled) command
* `!disable <command>` - Disables an existing (enabled) command

## Bot Management

* `!quit` - Makes the bot shut down

