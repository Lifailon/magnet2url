## magnet2url

Converts the transferred info hash torrent or magnet uri to a url address (https format) for redirect to the default torrent client. This approach is used in cases where the magnet link is not perceived as a url for redirection, for example, in the Telegram bot.

Pass info hash to the address bar after the `#` symbol:

```
https://lifailon.github.io/magnet2url/#7395a859e8e590418f422e7d0dfe68860de90631
```

or transfer the entire magnet uri:

```
https://lifailon.github.io/magnet2url/#magnet:?xt=urn:btih:7395A859E8E590418F422E7D0DFE68860DE90631
```

redirect to

```
magnet:?xt=urn:btih:7395A859E8E590418F422E7D0DFE68860DE90631
```
