## magnet2url

Converts the transferred info hash torrent or magnet uri to a web url address (https) for redirect to the default torrent client.

This approach is used in cases where the magnet link is not perceived as a url for redirection, for example, in the Telegram bot.

---

Pass info hash to the address bar after the `#` symbol:

```
https://lifailon.github.io/magnet2url#7395a859e8e590418f422e7d0dfe68860de90631
```

or transfer the entire magnet uri:

```
https://lifailon.github.io/magnet2url#magnet:?xt=urn:btih:7395A859E8E590418F422E7D0DFE68860DE90631
```

redirect to

```
magnet:?xt=urn:btih:7395A859E8E590418F422E7D0DFE68860DE90631
```

the operating system will redirect you to the default torrent client.

---

The `#tr` parameter adds a list of torrent tracker servers to the magnet link:

```
https://lifailon.github.io/magnet2url#7395a859e8e590418f422e7d0dfe68860de90631#tr
```

redirect to

```
magnet:?xt=urn:btih:7395A859E8E590418F422E7D0DFE68860DE90631&tr=wss://tracker.btorrent.xyz&tr=wss://tracker.openwebtorrent.com&tr=udp://tracker.btorrent.xyz:80&tr=udp://tracker.openwebtorrent.com:80&tr=udp://tracker.openwebtorrent.com:1337&tr=udp://retracker.local:80&tr=udp://tr0.torrent4me.com:80&tr=udp://tr1.torrent4me.com:80&tr=udp://tr2.torrent4me.com:80&tr=udp://tr3.torrent4me.com:80&tr=udp://tr4.torrent4me.com:80&tr=udp://tr0.tor4me.info:80&tr=udp://tr1.tor4me.info:80&tr=udp://tr2.tor4me.info:80&tr=udp://tr3.tor4me.info:80&tr=udp://tr4.tor4me.info:80&tr=udp://tr0.tor2me.info:80&tr=udp://tr1.tor2me.info:80&tr=udp://tr2.tor2me.info:80&tr=udp://tr3.tor2me.info:80&tr=udp://tr4.tor2me.info:80
```
