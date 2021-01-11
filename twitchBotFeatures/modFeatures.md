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

## Command Management

* `!add <command> <commandText>` - Adds a new command
* `!edit <command> <commandText>` - Edits the text of a command
* `!remove <command>` - Removes a command, deleting its definition
* `!enable <command>` - Enables an existing (disabled) command
* `!disable <command>` - Disables an existing (enabled) command, preserving its definition

## TTS Management

* `!set tts enabled` - Enables TTS
* `!set tts disabled` - Disables TTS
* `!set tts timeout <timeout>` -  Sets the per-user TTS timeout (in seconds)
* `!set tts bitthreshold <value>` - Sets the bit cheer thereshold to trigger TTS

## Bot Management

* `!quit` - Makes the bot shut down
