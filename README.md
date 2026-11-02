# NorLearn lesson feed

This repository is the remote content feed for the NorLearn iOS app.

`lessons.json` contains additional Nor-Lingo lessons. The app downloads it when the Nor-Lingo screen opens, caches it for offline use, and combines it with the built-in lessons.

Each lesson supports:

- `title`, `subtitle`, optional SF Symbol `icon`, and theme `color`
- `items`: Norwegian/English phrase pairs with an optional teaching `tip`
- `wordPairs`: individual words used by matching exercises

Increment `version` whenever the feed structure changes.
