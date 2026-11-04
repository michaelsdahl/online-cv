# msdahl.com

Michael Slavensky Dahls offentlige bestyrelsesprofil.

Den offentlige profil vedligeholdes direkte i `index.html`, med design i
`styles.css`, adfærd i `site.js` og portræt i
`assets/michael-slavensky-dahl.webp`. GitHub Pages publicerer fra `main`.

`/print`, `/print.html` og `/print/` omdirigerer til forsiden. Den tidligere
Jekyll-baserede CV-visning, dens data, skabeloner og PDF-funktion er fjernet.
Det separate bestyrelses-CV skal ikke tilføjes til repositoryet eller hjemmesiden.

Gamle temabilleder og tredjepartsaktiver i `assets/images` og `assets/plugins`
er udelukket fra publicering via `_config.yml`, ligesom denne dokumentation
og udviklingsfiler. Historiske versioner findes fortsat i Git-historikken.

## Lokal forhåndsvisning

```sh
bundle install
bundle exec jekyll serve
```

## Oprindelse og licens

Repositoryet var oprindeligt baseret på Orbit af Xiaoying Riley / 3rd Wave Media,
konverteret til Jekyll af sharu725. Se `LICENSE.md` for den oprindelige licens.
