# What is this

This is a shell script I made to spam messages and change nicknames very quickly in discord.

Messages get send every second and/or nickname gets changed every second depending on what parameters you set.

You can have multiple instances running with multiple accounts.

This was my first real shell script I made so it isn't as clean as I wanted to be.

# Requirements

- [CURL](https://curl.se/)
- POSIX compliant shell
- GNU Coreutils or a similar replacement

# Usage

Message spam:

`discordcrusher -m <token> <channel id> <random/file/message>`

Nickname scrambler:

`discordcrusher -n <token> <server id> <random/file>`

Both:

`discordcrusher -b <token> <server id> <channel id> <random/file/message> <random/file>`

# Notes

Nickname changing can only happen every second so setting it lower will get you rate limited.

Spamming messages can be set to less then 1 second if you manually change the script but might cause some issues (around 0.7 seems fine mostly).

Pinging users: <@userid>

Pinging roles: <@&roleid>

Made for fun and not to break TOS :)
