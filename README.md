# [BDSelf v3.0](https://telegram.me/BeyondTeam)

Professional Self-Bot Based On NEW TG-CLI


* * *

## Commands

| Command | Description |
|--------|------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the self-bot.
cd $HOME
git clone https://github.com/BeyondTeam/BDSelf.git
cd BDSelf
chmod +x beyond.sh
./beyond.sh install
./beyond.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/BeyondTeam/BDSelf.git && cd BDSelf && chmod +x beyond.sh && ./beyond.sh install && ./beyond.sh
```

* * *

### Sudo And Bot

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {157059515, YourID}
```
add your ID at line 131 in bot.lua
Then restart Bot.

* * *

# Developers!

[
# Special thanks to
[rizaumami](https://github.com/rizaumami) ([Telegram](https://telegram.me/kuncen))

[Vysheng](https://github.com/Vysheng) ([Telegram](https://telegram.me/Vysheng
