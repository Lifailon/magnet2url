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

The `&tr` parameter adds a list of torrent tracker servers to the magnet link:

```
https://lifailon.github.io/magnet2url#7395a859e8e590418f422e7d0dfe68860de90631&tr
```

redirect to

```
magnet:?xt=urn:btih:7395a859e8e590418f422e7d0dfe68860de90631&tr=http://tr0.torrent4me.com/ann?uk=kCm7WcIM00&tr=http://tr1.torrent4me.com/ann?uk=kCm7WcIM00&tr=http://tr2.torrent4me.com/ann?uk=kCm7WcIM00&tr=http://tr3.torrent4me.com/ann?uk=kCm7WcIM00&tr=http://tr4.torrent4me.com/ann?uk=kCm7WcIM00&tr=http://tr5.torrent4me.com/ann?uk=kCm7WcIM00&tr=http://tr0.tor4me.info/ann?uk=kCm7WcIM00&tr=http://tr1.tor4me.info/ann?uk=kCm7WcIM00&tr=http://tr2.tor4me.info/ann?uk=kCm7WcIM00&tr=http://tr3.tor4me.info/ann?uk=kCm7WcIM00&tr=http://tr4.tor4me.info/ann?uk=kCm7WcIM00&tr=http://tr5.tor4me.info/ann?uk=kCm7WcIM00&tr=http://tr0.tor2me.info/ann?uk=kCm7WcIM00&tr=http://tr1.tor2me.info/ann?uk=kCm7WcIM00&tr=http://tr2.tor2me.info/ann?uk=kCm7WcIM00&tr=http://tr3.tor2me.info/ann?uk=kCm7WcIM00&tr=http://tr4.tor2me.info/ann?uk=kCm7WcIM00&tr=http://tr5.tor2me.info/ann?uk=kCm7WcIM00&tr=http://retracker.local/announce&tr=wss://tracker.openwebtorrent.com&tr=wss://tracker.openwebtorrent.com
```
