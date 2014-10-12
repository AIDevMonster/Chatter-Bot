# ChatterBot

This is a chat bot program that takes input and returns a response based on known conversations.

[![Package Version](https://badge.fury.io/py/ChatterBot.png)](http://badge.fury.io/py/ChatterBot)
[![Build Status](https://travis-ci.org/gunthercox/ChatterBot.svg?branch=master)](https://travis-ci.org/gunthercox/ChatterBot)
[![PyPi](https://pypip.in/d/ChatterBot/badge.png)](https://pypi.python.org/pypi/ChatterBot)

## Installation

This package can be installed using
```
pip install chatterbot
```

## Useage

Create a new chat bot
```
from engram import Engram
chatbot = Engram()
```

Getting a response
```
response = chatbot.engram("Good morning!")
print(response)
```

Terminal mode (User and chat bot)
```
chatbot.terminal()
```

Have the chat bot talk with CleverBot
```
chatbot.talk_with_cleverbot()
```

## Requirements

To install required packages for this project run the command:
```sudo pip install -r requirements.md```

## A general warning

This program is capable of retrieving conversation data from various social networks
in order to provide more accurate replies to input text. Because of this,
responces generated by the chat bot can contain insulting statements completely at random.
I have plans to address this issue, however they are not yet implemented.

## Notes

This program is not designed to be an open source version of CleverBot.
Although this **Chat Bot** returns responces, the code here handles communication
much differently then [CleverBot](http://www.cleverbot.com) does.
