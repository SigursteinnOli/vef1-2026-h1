
# Vefforritun – Hópverkefni 1

## Um verkefnið

Verkefnið er vefsíða fyrir Forritið, unnin í HTML og SCSS/Sass samkvæmt hönnun í Figma.

Vefsíðan inniheldur forsíðu, innskráningarsíðu og teymissíðu.
Ekki var náð að klára teymissíðuna og mobile útgáfu af öllu.

## Keyrsla verkefnis

Til að setja upp verkefnið þarf Node.js og npm.

Setja upp pakka:

```bash
npm install
```

Ræsa þróunarumhverfi:

```bash
npm run dev
```

Keyra Stylelint á Sass-skrár:

```bash
npm run lint
```

## Uppsetning verkefnis

- `index.html` – forsíða verkefnisins.
- `sidur/` – aðrar HTML-síður, meðal annars innskráning og teymissíða.
- `styles/` – SCSS-skrár fyrir mismunandi hluta vefsíðunnar.
- `styles/styles.scss` – aðalskrá sem tengir saman SCSS-skrárnar.
- `styles.css` – CSS sem er búið til úr Sass.
- `myndir/` – myndir og tákn.
- `fonts/` – leturskrár.
- `gogn/` – gögn verkefnisins.
- `package.json` – npm-skriftur og pakkar.

SCSS er skipt niður eftir hlutum síðunnar, til dæmis `_header.scss`, `_footer.scss`, `_hero.scss` og `_features.scss`. Sameiginlegir stílar og breytur eru í `_global.scss` og `_config.scss`.

## Höfundar

| Nafn | HÍ-notandanafn | GitHub-notandanafn |
|---|---|---|
| Sigursteinn Óli Þorsteinsson | sot27@hi.is | [SigursteinnOli |
| Andrea Eiríksdóttir | ane28@hi.is | andreaei |
