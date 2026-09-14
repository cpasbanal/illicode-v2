# ILLI'CODE v2 — Illiers-Combray

A redesigned "v2" of the [ILLI'CODE](https://github.com/cpasbanal/illicode) site — the street-art & géocaching trail
run by the Accueil Jeunes of Familles Rurales Illiers-Combray — as a single self-contained HTML page (modern
landing-page layout, same Familles Rurales branding, same content: presentation, objectifs, partenaires, les jeunes,
contact, and the full 8-riddle game).

`index.html` is a standalone bundle (fonts/most images inlined). The `assets/` folder holds the images the bundle
references by relative path (8 riddle artworks, correct-answer illustrations, location photos, partner logos, the
20 team-member avatars, and the bravo/mauvaise-réponse banners) — these are the same original assets used in
[v1](https://github.com/cpasbanal/illicode).

## Preview locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000/
