# Turret [![Build Status](https://secure.travis-ci.org/aperturescience/turret.png?branch=master)](http://travis-ci.org/aperturescience/turret)

Our in-house extension of Winston.
We try to keep this compatible with the existing Winston API.

##Improvements

We've added a couple of more choices for the `colorize` option:
- `'level'`, which will only colorize the level (same as `true`)
- `'message'`, which will only colorize the message
- `'all'`, which will colorize both the level and the message

The default behavior is kept, simply set `colorize` to `true` to colorize the level only, set it to `false` to disable colors.
