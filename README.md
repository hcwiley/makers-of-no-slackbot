#makers of no slackbot

you should ask @hcwiley in the [slack](http://makersofno.slack.com) for the .env file

## setup

I'm assuming you already have python, pip, and virtualenv setup (_[help here if not](https://gist.github.com/pithyless/1208841)_).

```bash
virtualenv makers-of-no-slackbot
source makers-of-no-slackbot/bin/activate
pip install -r requirements.txt
```

## running

```bash
source .env
python main-bot.py
```

## explaining

* `print_bot_id.py` is helper python file that prints out the bots id. @hcwiley used this to setup the bot.
* `main-bot.py` is where everything is right now. At some point we will make a `commands.py` or something to store commands