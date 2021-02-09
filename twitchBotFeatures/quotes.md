# TASagent TwitchBot Quotes

TASagentPuppet features a relatively simple Quote System.

* `!quote` - Return a random quote
* `!quote add "<quote>"` - Add a quote attributed to the streamer. Ex: `!quote add "Hmmm, intriguing"`
    * alias: `!addquote "<quote>"` - Added this alias for compatibility with other bots
* `!quote add "<quote>" <username>` - Add a quote attributed to the specified user. Ex: `!quote add "Hmmm, intriguing" TASagentPuppet`
    * alias: `!addquote "<quote>" <username>` - Added this alias for compatibility with other bots
* `!quote #<id>` - Return the quote with the matching id. Ex: `!quote #4`
* `!quote <searchText>` - Return a random quote containing matching text. Ex: `!quote bananas`
* `!quote remove #<id>` - Remove a quote. Ex: `!quote remove #5"`.
    * Normal users can only remove quotes they made in the last 15 minutes.
    * Moderators can remove quotes made by any non-moderator in the last 15 minutes.
    * Admins can remove any quotes

## Fake News Quotes

Since there has been an epidemic of Fake News quotes, the admin alone can now set warnings on Fake News quotes with the following commands:

* `!set quote #<id> fakenews` - Sets the specified quote as fake news. Ex: `!set quote #4 fakenews`.
* `!set quote #<id> fakenews <description>` - Sets the specified quote as fake news with the provided description. Ex: `!set quote #4 fakenews "I never said that"`.
* `!set quote #<id> realnews` - Returns a quote to original "real news" status. Ex: `!set quote #4 realnews`.
