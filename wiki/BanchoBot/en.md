# BanchoBot

![BanchoBot's user card](https://rinarii.de/images/wiki/banchobot.png "BanchoBot's user card")

BanchoBot is Rinari's in-game chat bot that assists players by announcing 
game-related messages and responding to certain commands.

## Commands

All BanchoBot commands start with an exclamation mark (`!`) followed by the 
command name. These commands can be used in chat channels or through private 
messages with BanchoBot.

If a command is sent in a public channel, other users will not see it — the 
response will be displayed in a private message with BanchoBot.

- [Help](#help)
- [Roll](#roll)
- [Stats](#stats)
- [Where](#where)
- [FAQ](#faq)
- [Report](#report)

### Help

`!help` shows a list of all available BanchoBot commands.
```
13:00 pippi: !help
13:00 BanchoBot: Standard Commands (!COMMAND or /msg BanchoBot COMMAND):
13:00 BanchoBot: WHERE <user>
13:00 BanchoBot: STATS <user>
13:00 BanchoBot: FAQ <item>|list
13:00 BanchoBot: REPORT <reason> - call for an admin
13:00 BanchoBot: ROLL <number> - roll a dice and get random result from 1 to number(default 100)
```

### Roll

`!roll <number>` draws a random number from 1 to the selected number. 
If no number is specified or an argument is given, the maximum defaults to 100.
```
13:00 pippi: !roll 1000
13:00 BanchoBot: pippi rolls 109 point(s)
```
```
13:01 pippi: !roll probability of failure
13:01 BanchoBot: pippi rolls 75 point(s)
```

### Stats

`!stats <username>` displays a user's game statistics and current status, based 
on the game mode they last played.
```
13:01 pippi: !stats his kitten
13:01 BanchoBot: Stats for his kitten:
13:01 BanchoBot: Score: 8,526,315,776 (#2)
13:01 BanchoBot: Plays: 478 (lv96)
13:01 BanchoBot: Accuracy: 99.80%
```

Available statuses: Editing, Idle, Lobby, Modding, Multiplayer, Multiplaying 
and Playing.
```
13:01 pippi: !stats his kitten
13:01 BanchoBot: Stats for his kitten is Playing:
13:01 BanchoBot: Score: 8,526,315,776 (#2)
13:01 BanchoBot: Plays: 478 (lv96)
13:01 BanchoBot: Accuracy: 99.80%
```

### Where

`!where <username>` shows the user's current location. By default shows only 
the user's country. If the user has city sharing enabled, it will also display 
their city.
```
13:02 pippi: !where his kitten
13:02 BanchoBot: his kitten is in Canada
```

### FAQ

`!faq <entry>` shows the contents of a FAQ entry. Use `!faq list` to see all 
available entries.
```
13:03 pippi: !faq rules
13:03 BanchoBot: Please follow the rules! https://rinarii.de/wiki/en/Rules
```

### Report

`!report <user> <reason>` reports a user to the 
[[People/GMT|Global Moderation Team]] for inappropriate behaviour. 
If a username has spaces, replace them with underscores.
```
13:10 pippi: !report someuser spamming in #osu
13:10 BanchoBot: Chat moderators have been alerted. Thanks for your help.
```

## Contact
- [Rinari Discord](https://discord.gg/fSmtpH3HSK)
- [support@rinarii.de](mailto:support@rinarii.de)