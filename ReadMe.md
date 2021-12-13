# BotStatus
Updates your bot status in the message, every two hours.

**_NOTE:_** This branch uses github workflows to host your code, and doesn't rely on another hosting platform. If you want to deploy on heroku/vps/whereever, go to [this branch](https://github.com/xditya/BotStatus/tree/deploy).

# Secrets.

### Heroku Deploy 
The easiest way to deploy this Bot is via Heroku.

<p align="left"><a href="https://heroku.com/deploy?template=https://github.com/Heyaaman-UB/BotStatus"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

Add them to [Settings ⇢ Secrets ⇢ New Repository Secret.](https://docs.github.com/en/actions/reference/encrypted-secrets)

- `APP_ID` and `API_HASH` from [my.telegram.org](https://my.telegram.org).
- `BOTS` - TG UserName of your bots separated by space.
- `SESSION` - Telethon SessionString of the User to edit the message.
- `REPO_NAME` - yourGitHubUserName/RepositoryName, eg: xditya/BotStatus (fork this repo first).
- `CHANNEL_ID` - ID of your channel.
- `MESSAGE_ID` - ID of the message to edit.

# Credits
- [Jainam Oswal](https://github.com/jainamoswal/BotStatus).
- [Me](https://xditya.me)
