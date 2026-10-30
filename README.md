# lostbannerstudio.github.io

Website for **Banner of Ash**, a medieval kingdom strategy game for Android by Lost Banner Studio.
Served by GitHub Pages at https://lostbannerstudio.github.io/.

## Pages

| Path | Purpose |
| --- | --- |
| `/` | Game homepage with Google Play link |
| `/privacy-policy/` | Privacy policy (linked from the Play Console listing) |
| `/data-deletion-request/` | Data deletion instructions (Play Console data safety form) |
| `/404.html` | Not-found page served by GitHub Pages |
| `/app-ads.txt` | AdMob authorized sellers; must stay at the domain root |

Plain HTML and one stylesheet (`assets/css/site.css`), with no build step. `.nojekyll` turns off Jekyll processing.

## Preview locally

```sh
python -m http.server 8000
```

Then open http://localhost:8000/.

## Images

Screenshots in `assets/img/screens/` have a full-size `.png` (also used for `og:image`) and a 1280px `.webp` that the homepage serves through `<picture>`. When you replace a screenshot, regenerate its `.webp`.
