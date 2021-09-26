# Telegram File To Link Generation Bot
A Telegram bot that can stream Telegram files to users over HTTP.


# Diploy

### With Bot Token & Session String
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TGExplore/TG-Files-to-Link)

### Without Session String
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TGExplore/TG-Files-to-Link/tree/Merging)

### Get String Sesson
[![Run](https://img.shields.io/badge/Run%20Online-Black)](https://generatestringsession.tgexplore.repl.run/)


### Environment variables
* `TG_API_ID` (required) - Your Telegram API ID.
* `TG_API_HASH` (required) - Your Telegram API hash.
* `TG_SESSION_NAME` (defaults to `tgfilestream`) - The name of the Telethon session file to use.
* `TG_BOT_FATHER_TOKEN` - Your bot token, as a string..
* `PORT` (defaults to `8080`) - The port to listen at.
* `HOST` (defaults to `localhost`) - The host to listen at.
* `PUBLIC_URL` (defaults to `http://localhost:8080`) - The prefix for links that the bot gives.
* `TRUST_FORWARD_HEADERS` (defaults to false) - Whether or not to trust X-Forwarded-For headers when logging requests.
* `DEBUG` (defaults to false) - Whether or not to enable extra prints.
* `LOG_CONFIG` - Path to a Python basic log config. Overrides `DEBUG`.
* `REQUEST_LIMIT` (default 5) - The maximum number of requests a single IP can have active at a time.
* `CONNECTION_LIMIT` (default 20) - The maximum number of connections to a single Telegram datacenter.
* `TG_START_MESG` - The message that should be shown in Telegram chat, in case of non-media message.



## Special Credits

[Orginal Repo Owner](https://github.com/tulir/tgfilestream)<br><br>
![Repo Owner](https://github.com/tulir.png?size=100px)

## Report Any Bug

[King Amda](https://t.me/KingAmdaContactBot)<br><br>
![King Amda](https://github.com/King-Amda.png?size=100px)

