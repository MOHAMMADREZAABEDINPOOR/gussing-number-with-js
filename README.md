<div align="center">

<img src="assets/readme/hero.gif" width="1200" alt="GUESS THE NUMBER · JS — rotating 3D geometry" />

**[English](README.md) · [فارسی](README.fa.md)**

<img src="assets/readme/identity.svg" width="1200" alt="learning / English and Persian documentation" />

</div>

# GUESS THE NUMBER · JS

A small browser game with a random answer in the range 0–999, higher/lower hints and ten incorrect-guess opportunities.

[GitHub](https://github.com/MOHAMMADREZAABEDINPOOR/gussing-number-with-js) · [PIMX / Profile](https://github.com/MOHAMMADREZAABEDINPOOR) · [Static artwork](assets/readme/hero.png)

## Features

- Browser-only HTML/JavaScript
- Remaining-lives display
- Color-coded attempt feedback
- Reset/reload control

## Stack

| Tool | Version / source |
|---|---|
| HTML / CSS / JavaScript | `static files` |

## Getting started

A modern browser; Python is optional for the local HTTP server.

```bash
git clone https://github.com/MOHAMMADREZAABEDINPOOR/gussing-number-with-js.git
cd gussing-number-with-js

python -m http.server 8000
```

## Configuration

No standard environment template is defined. Standalone exercises need no external configuration; inspect any service constants or paths in the source before running.

## Usage

Open 1.html, enter a number and click Check. Reset reloads the page and selects a new answer.

## Project structure

| Path | Role |
|---|---|
| [`assets/`](assets/) | Brand/media/README assets |
| [`1.html`](1.html) | Project entry/configuration file |

## Commands and checks

No automated test command is declared in a manifest. Verify behavior through a local example run.

## Deployment

This is a local learning exercise, not a public service. Browser exercises can use static hosting.

## Limitations

The answer is stored client-side and can be inspected. Progress is not persisted.

## Troubleshooting

- Wrong page: open the HTML entry point or the relevant Week directory.
- Missing assets: serve the complete directory and retain relative paths.

## Contributing

Create a focused branch, verify the affected behavior and explain the change clearly. Keep private data, build outputs and local databases out of commits.

## License

No repository-level license file is included in this snapshot. Public visibility alone does not grant reuse rights; contact the repository owner for terms.

---

Part of **PIMX** · Documentation in English and Persian.
