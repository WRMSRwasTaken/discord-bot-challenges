# WRMSR's and Eugene's bot test suite
## -or-
# stop making shitty discord bots!

### There are so many shitty discord bots out there wasting resources that could be spared for discord users waiting for their messages to be sent...
### This document should help identify if a discord bot is a shitty bot or not (at last to some degree)

### The test list, your bot should:
 - Have a `info`command
 - Have a `help` command
 - Should handle @mention messages (`@mention help` for example)
 - Should handle message edits (either the bot should edit it's answer or delete the previous answer to send a new answer)
 -- It should also delete it's message if the user message changed from a bot call to a non-bot call
 -- Also if a edit changes to a bot call, it should handle it like a new message
 - Should handle message deletes (the bot should delete it's answer then)
 - It should handle DM commands without any prefixes
 - It should handle multiple spaces between arguments and between the prefix and the command
