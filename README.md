# bilder

Quell-Artikelbilder für **blechziegel.de** — Aluminium-Blank-Originale je Hersteller/Modell, sortiert nach Hook-Variante.

## Struktur

```
mit Haken/    Aluminium-Blank-Bilder mit Dachhaken-Aufsatz
ohne Haken/   Aluminium-Blank-Bilder ohne Dachhaken
```

## Datei-Konvention

```
pv-dachziegel-{hersteller}-{modell}-aluminium-blank-{mit|ohne}-haken.{png|jpg}
```

## Workflows (lokal, separates Repo)

| Tool | Zweck |
|---|---|
| `convert_blechziegel_artikelbilder.py` | WebP-Konvertierung (Q88, max 2400 px, weißer Hintergrund) |
| `generate_blechziegel_product_variants.py` | RAL-7021 / RAL-8004 Varianten + Aluminium-Output (1600×1600 Studio-Look) |

Tool-Pfade: `c:/Users/Administrator/blechziegel-admin-tools/`
Outputs landen in `<source>/YYYY-MM-DD/` (per `.gitignore` ausgeschlossen — werden nicht ins Repo gepusht).
