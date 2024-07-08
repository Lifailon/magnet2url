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

The `#tr` parameter adds to the magnet link a list of torrent tracker servers used in [Kinozal](https://kinozal.tv), [RuTracker](https://rutracker.org), [NoNameClub](https://nnmclub.to), [RuTor](https://rutor.org/) and [WebTorrent](https://github.com/webtorrent/webtorrent-desktop).

```
https://lifailon.github.io/magnet2url#7395a859e8e590418f422e7d0dfe68860de90631#tr
```

redirect to

```
magnet:?xt=urn:btih:7395a859e8e590418f422e7d0dfe68860de90631&tr=http%3A%2F%2Fretracker.local%2Fannounce&tr=http%3A%2F%2Ftr0.torrent4me.com%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr1.torrent4me.com%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr2.torrent4me.com%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr3.torrent4me.com%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr4.torrent4me.com%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr5.torrent4me.com%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr0.tor4me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr1.tor4me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr2.tor4me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr3.tor4me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr4.tor4me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr5.tor4me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr0.tor2me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr1.tor2me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr2.tor2me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr3.tor2me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr4.tor2me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Ftr5.tor2me.info%2Fann%3Fuk%3DkCm7WcIM00&tr=http%3A%2F%2Fbt.t-ru.org%2Fann&tr=http%3A%2F%2Fbt2.t-ru.org%2Fann&tr=http%3A%2F%2Fbt3.t-ru.org%2Fann&tr=http%3A%2F%2Fbt4.t-ru.org%2Fann&tr=http%3A%2F%2Fbt01.nnm-club.info%3A2710%2Fannounce&tr=http%3A%2F%2Fbt02.nnm-club.info%3A2710%2Fannounce&tr=http%3A%2F%2Fbt01.nnm-club.cc%3A2710%2Fannounce&tr=http%3A%2F%2Fbt02.nnm-club.cc%3A2710%2Fannounce&tr=udp%3A%2F%2Fopentor.net%3A6969&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.grepler.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.dler.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.bitsearch.to%3A1337%2Fannounce&tr=http%3A%2F%2Fh1.trakx.nibba.trade%3A80%2Fannounce&tr=http%3A%2F%2Fh2.trakx.nibba.trade%3A80%2Fannounce&tr=http%3A%2F%2Fh3.trakx.nibba.trade%3A80%2Fannounce&tr=http%3A%2F%2Fh4.trakx.nibba.trade%3A80%2Fannounce&tr=http%3A%2F%2Fh5.trakx.nibba.trade%3A80%2Fannounce&tr=wss%3A%2F%2Ftracker.openwebtorrent.com&tr=wss%3A%2F%2Ftracker.btorrent.xyz&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337&tr=udp%3A%2F%2Ftracker.empire-js.us%3A1337&tr=udp%3A%2F%2Fexplodie.org%3A6969
```