# discord_crypto_alert

Discord bot used to track all Bitcoin, Ethereum and XRP transactions over 500k using the whale_alert API

## Installing Dependencies

`pip install -r requirements.txt`

Note: *Includes Profile and requirements.txt so it can run on servers (i.e Heroku)*


## Updating credentials

Add you whale_alert API key, discord token and channel ID's to `keys.json`.


## Running the Bot

To run the bot, use the following command:

```
python3 main.py
```

or

```
heroku run python3 main.py
```
