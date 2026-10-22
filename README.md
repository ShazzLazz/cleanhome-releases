# Clean Home releases

Updates for the Clean Home TV launcher. Each release has `CleanHome.apk` and `version.json`; TVs check
here once a day and install from **Settings → Updates**.

`tvs.json` holds per-TV settings, keyed by each TV's name. Change a TV's `rev` to have it apply its
settings again on its next check. `rows` lists the Home rows that TV shows:
`episodes`, `films`, `shows`, `malayalam`, `tamil`, `kdrama`, `anime`.
