# TASagent Twitchbot Mod Powers

TASagentPuppet features a few powers specifically for Moderators

## General Powers

* `!so <username>` - Trigger a shoutout message regarding the indicated user
* `!pleaseclap` - Trigger a moment of silent shame

## Notification Management

* `!replay` - Replay the last notification event
* `!replay <id>` - Replay notification with the indicated id
* `!skip` - Kills the audio for the current TTS or sound effect.

## User Permissions

User permissions for the bot is controlled through several tiers of access.  From most to least powerful, they are: _administrator_, _moderator_, _elevated_, _normal_, and _restricted_.

### User Permission Management

Moderators and Admins can adjust the permissions of users.

* `!permit <user>` - Increase non-mod user permissions by a level
    * Aliases: `!elevate`, `!promote`
* `!revoke <user>` - Decrease non-mod user permissions by a level
    * Alias: `!demote`
* `!restrict <user>` - Sets user permissions to Restricted

Admins alone can grant and revoke moderator permissions

* `!mod <user>` - Sets a user to the Mod tier
* `!unmod <user>` - Removes a user from the Mod tier

## Command Management

Moderators and Admins can add, remove, and modify generic informational chat commands.

* `!add <command> <commandText>` - Adds a new command
* `!edit <command> <commandText>` - Edits the text of a command
* `!remove <command>` - Removes a command, deleting its definition
* `!enable <command>` - Enables an existing (disabled) command
* `!disable <command>` - Disables an existing (enabled) command, preserving its definition

### Sloppy Mode

Sometimes chat gets a bit cheeky and starts dropping in unicode characters that look like exclamation points to pretend that this bot is ignoring commands.  Moderators and Admins can shatter their dreams with SloppyMode.  In SloppyMode, the character `ǃ` (LATIN LETTER RETROFLEX CLICK), as well as anything with "Exclamation" in its unicode character description, will work to trigger commands.

* `!set sloppymode enabled` - Enables SloppyMode
* `!set sloppymode disabled` - Disables SloppyMode
* `!sloppymode` - Reports the current state of SloppyMode, as well as active Command Triggers if SloppyMode is turned on
* `!sloppymode state` - Reports the current state of SloppyMode
* `!sloppymode triggers` - Reports the SloppyMode command triggers
* `!set sloppymode add <trigger>` - Adds the specified trigger character to the persistent list of SloppyMode command triggers
* `!set sloppymode remove <trigger>` - Removes the specified trigger character from the persistent list of SloppyMode command triggers

## TTS Management

* `!set tts enabled` - Enables TTS
* `!set tts disabled` - Disables TTS
* `!set tts timeout <timeout>` -  Sets the per-user TTS timeout (in seconds)
* `!set tts bitthreshold <value>` - Sets the bit cheer thereshold to trigger TTS

## Bot Management

* `!quit` - Makes the bot shut down
