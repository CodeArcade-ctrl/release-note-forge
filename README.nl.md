# Release Note Forge

Zet commitregels om in overzichtelijke, bewerkbare Markdown-releasenotes. Prefixen volgens Conventional Commits worden gegroepeerd in functies, fixes, prestaties, documentatie en meer.

**Live demo:** [Probeer Release Note Forge](https://codearcade-ctrl.github.io/release-note-forge/)

**Talen:** [English](README.md) | [Nederlands](README.nl.md)

## Functies

- Groepeert Conventional Commit-typen zoals `feat`, `fix` en `docs`
- Behoudt scopes zoals `feat(api): ...`
- Zet andere commitregels onder Overig
- Bewerkbare uitvoer met versiekop, kopieerknop en `.md`-download
- Engelse en Nederlandse labels
- Lokale verwerking zonder dependencies of uploads

## Gebruiken

Open `index.html`, plak één commitregel per regel, stel een versie in en klik op **Notities maken**. Controleer de tekst voordat je deze publiceert.

## Publiceren met GitHub Pages

Push naar de branch `main`. De meegeleverde GitHub Actions-workflow publiceert de site naar GitHub Pages. Stel bij de repository-instellingen zo nodig **Pages > Build and deployment > Source** in op **GitHub Actions**.

## Licentie

MIT. Zie [LICENSE](LICENSE).
