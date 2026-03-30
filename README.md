# ClickSaver
ClickSaver for Anarchy Online

This is an *unofficial* fork of ClickSaver (if you want to call the current situation as *official*) based on historical sources from AOU [1] and Darkbane [2]. Current development is hosted at `https://github.com/galku/ClickSaver` and includes PRK-style Anarchy Online install support.


## Compilation

VS2022 with the toolchain set to v141_xp to get CS to still run under WinXP additonal to all newer Windows versions.
The solution should still work in all VS versions down to VS2010 if the toolset is changed to the latest version supported by that version.

## PRK/AO fork support

This fork adds a new install-directory option for PRK-style Anarchy Online installs. The UI now includes:

- an editable install path field
- a `Browse...` button for folder selection
- a `Validate` button to confirm the selected or typed directory

The app accepts both classic AO install roots and PRK install layouts.

## Fork and push

This code is currently available at `https://github.com/galku/ClickSaver` and supports PRK installs via the `prk-install-ui` branch.

Create your own GitHub fork, then add it as a remote and push the feature branch:

```bash
git remote add myfork https://github.com/<your-user>/ClickSaver.git
git push myfork prk-install-ui
```


## Quick history tour

From what I could gather these were the official places/developers you could get CS from in the past. While lots of others contributed fixes and ideas throughout the lifetime. Correct me if I'm wrong.

* Originally created by MORB
  - [Homepage](http://a.chavasse.free.fr/ClickSaver) (down)

* Gnarf
  - [Homepage](http://clicksaver.notumwars.com) (down)

* Covenant
  - [Homepage](http://www.halorn.com/clicksaver.html) (down)

* Kimi
  - [Homepage](http://arpa3.net/ao/clicksaver.html)
  - While he also has newer versions on his site (v2.4.x and v3.x), the sources are not available and these are not considered official.

* AO Universe
  - [Download page](http://www.ao-universe.com/index.php?id=29&mid=1&site=AO-Universe%2FMultimedia%2FDownloads%2FTools%2F)
  - [Guide](http://www.ao-universe.com/index.php?id=14&mid=1&site=AO-Universe%2FKnowledge%2FClassic+AO%2F&pid=13&highlight=clicksaver)
  - Only hosts the sources and binaries for v2.3.5 (not sure where it actually comes from), which needs updates from Darkbane to run with the current version of AO.
  - Currently considered to be the official version together with the replacement binaries from Darkbane below.

* Darkbane
  - Provides replacement binaries for v2.3.5 from AOU for [Win7+](http://forums.anarchy-online.com/showthread.php?598983-No-more-clicksaver-item-assistant&p=6073780#post6073780) and [WinXP](http://forums.anarchy-online.com/showthread.php?598983-No-more-clicksaver-item-assistant&p=6077212&viewfull=1#post6077212).


## References

[1] [CS v2.3.5 source download](http://www.ao-universe.com/index.php?id=29&mid=1&site=AO-Universe%2FMultimedia%2FDownloads%2FTools%2F&fid=14&action=download)

[2] [CS v2.4.0 source download](http://www.lastmanut.pwp.blueyonder.co.uk/CS240_Source.zip)
