# Minion.Assets

Public, non-proprietary assets referenced from documentation and support content across every MinionWare product -- primarily images embedded in Freshdesk help articles (and any in-app or local Markdown help that needs a publicly reachable picture, since the actual product repos are private).

Nothing in here should ever be proprietary source, config, or anything else that isn't meant to be public -- this repo exists specifically because the product repos are **not** public, so a raw GitHub URL from one of them isn't reachable by a customer's browser or a search-engine crawler.

## Layout

One folder per product, e.g.:

```
Minion.Agent/
  help/
    <topic-or-article>/
      screenshot.png
```

Reference an image from a Freshdesk article (or a local `docs/help/*.md` file) as:

```
https://raw.githubusercontent.com/MinionWare/Minion.Assets/master/Minion.Agent/help/<path>/<file>.png
```
