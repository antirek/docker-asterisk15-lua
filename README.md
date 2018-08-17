# docker-asterisk15-lua

## What is it?

- Asterisk 15 latest
- Lua 5.1 for dialplan
- most useful luarocks packages
- dbs driver for lua
- g729 support

## Usage

use in Dockerfile

`````
FROM antirek/asterisk15-lua:18.08.1

...

CMD asterisk && tail -f /var/log/asterisk/messages

`````
also see https://github.com/antirek/docker-asterisk15-lua-pjsip-sample

## 18.08.1

- add luarocks luchia, statsd
- up luarocks luasec to 0.7
- up luarocks to 2.4.4

## 18.07.1

- asterisk 15.5.0
- enabled res_chan_stats, res_endpoint_stats

