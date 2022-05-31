# Monitor Missed Blocks Application

MMB is an automation that analyzes and alerts lost blocks by cosmos blockchain network validators.

The application runs on Node.js and queries data from validators in a REST or GRPC query from a validator node on the network.

It uses SQLite 3 to persist the data and discord.js library to integrate the Discord platform that provides consultation through interactions with the bot and notifications to a channel through Webhook calls.


## Bot commands

### $missed

![Missed command](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-missed-command-bot-01.png)

This command can be used to query the current missing blocks information for a specific validator.

### $status

![Status command](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-status-command-bot-01.png)

This command allows you to check which validators are active on the network, and general information about a specific validator if you pass the validator's name as a parameter.

### $help

![Help command](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-help-command-bot.png)

This command returns a brief description of how to use the bot's commands.

### link

![Link command](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-link-command-bot-01.png)
![Link command](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-link-command-bot-02.png)

This command returns the link of the explorer of the blockchain network or the direct link of the validator in the website explorer if the name of the validator is passed as a parameter.

## Alert Messages

### New validator

![New Validator alert message](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-new-validator-message.png)

### Modify validator info

![Modify info validator alert message](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-validator-info-modify-message.png)

### Low performance

![Low performance alert message](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-low-performance-alert-01.png)
![Low performance alert message](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-low-performance-alert-02.png)

### Validator Jailed

![Jailed validator alert message](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-validator-jailed-message.png)

### Validator recovered

![Recovered validator alert message](https://github.com/Michel-Leidson/mmb-features/blob/main/img/discord-recovered-alert.png)