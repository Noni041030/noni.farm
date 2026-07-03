# noni.farm

The static site for [noni](https://noni.farm) — on-device AI for iPhone.

The site itself lives in [`site/`](site/) and deploys to GitHub Pages on
every push to `main`. The **source of truth** is the `website/` directory
of the (private) app repository; edit there and run
`tools/sync_website.sh` to publish. Direct edits here get overwritten by
the next sync.
