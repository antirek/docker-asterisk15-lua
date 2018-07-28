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
FROM antirek/asterisk15-lua:18.07.1

...
`````
also see https://github.com/antirek/docker-asterisk15-lua-pjsip-sample

## 18.07.1

- asterisk 15.5.0
- enabled res_chan_stats, res_endpoint_stats

