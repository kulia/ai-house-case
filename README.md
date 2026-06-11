# AI House · Case daglig leder

Interaktiv casepresentasjon for stillingen som daglig leder i AI House (et initiativ fra Oxidane Venture), av Geir Kulia.

Hele presentasjonen er én selvstendig HTML-fil — [index.html](index.html) — uten byggesteg eller avhengigheter (kun Google Fonts lastes eksternt).

## Kjøre lokalt

Åpne `index.html` direkte i nettleseren, eller kjør en enkel server:

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

## Tastatur

| Tast | Handling |
|---|---|
| `→` / mellomrom / `PgDn` | Neste slide |
| `←` / `PgUp` | Forrige slide |
| `Home` / `End` | Første / siste slide |
| `F` | Fullskjerm |
| `N` | Vis/skjul presentasjonsnotater |
| `Esc` | Lukk notatpanel |

Sveip fungerer på touch-skjermer. Utskrift (`Cmd+P`) gir én side per slide.

## Publisere på GitHub Pages

1. Opprett et repo og push innholdet til `main`.
2. På GitHub: **Settings → Pages → Source: Deploy from a branch**, velg `main` og `/ (root)`.
3. Presentasjonen blir liggende på `https://<brukernavn>.github.io/<repo>/`.

> **Merk:** GitHub Pages er offentlig (også for private repoer på gratisplan). Filen inneholder presentasjonsnotater (`N`-tasten), e-post og telefonnummer — vurder om alt skal med før publisering.

---

Bygget med AI-verktøy · Juni 2026
