# IRC - Telegram gateway

tgirc is a simple IRC - Telegram bidirectional gateway.

It is written in TCL and requires tcllib only.

## What does it do

All messages coming into IRC channel are sent to Telegram group.

All messages coming into Telegram group are sent to IRC channel.

## How to run it

* Rename tgirc.settings.default to tgirc.settings
* Edit tgirc.settings to your liking
* Run ./tgirc

## Limitations

Anything other than text in Telegram messages is not sent back to IRC.

