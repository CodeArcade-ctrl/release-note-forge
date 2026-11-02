# Release Note Forge

Transform commit subjects into tidy, editable Markdown release notes. Conventional Commit prefixes are grouped into features, fixes, performance, documentation, and more.

**Live demo:** [Try Release Note Forge](https://codearcade-ctrl.github.io/release-note-forge/)

**Languages:** [English](README.md) | [Nederlands](README.nl.md)

## Features

- Groups conventional commit types such as `feat`, `fix`, and `docs`
- Preserves scopes like `feat(api): ...`
- Keeps non-conventional subjects under Other
- Editable output with version heading, clipboard copy, and `.md` download
- English and Dutch labels
- Local-only processing; no dependencies or uploads

## Use it

Open `index.html`, paste one commit subject per line, set a version, and select **Generate notes**. Review the generated notes before publishing.

## Publish with GitHub Pages

Push to the `main` branch. The included GitHub Actions workflow publishes the site to GitHub Pages. In repository settings, set **Pages > Build and deployment > Source** to **GitHub Actions** if it is not selected automatically.

## License

MIT. See [LICENSE](LICENSE).
