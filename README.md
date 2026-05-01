# chesscom-to-lichess

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Extensão para Firefox que adiciona um botão na [chess.com](http://chess.com) — quando uma partida termina, um clique exporta a partida direto para a análise do [Lichess.org](http://Lichess.org).

## Por que existe
A análise do Lichess é gratuita e mais profunda. Antes desta extensão era preciso copiar PGN e colar manualmente no Lichess.

## Instalação (modo dev)
1. Clone o repositório.
2. No Firefox, acesse `about:debugging#/runtime/this-firefox`.
3. Clique em **Load Temporary Add-on** e selecione `manifest.json`.

## Como usar
1. Termine uma partida na [chess.com](http://chess.com).
2. Clique no botão **Analisar no Lichess** que aparece ao lado do placar.
3. A partida abre no Lichess pronta para análise.

## Stack
- WebExtensions API (Firefox / MV2)
- JavaScript vanilla, sem dependências externas

## Roadmap
- [ ] Suporte a Chrome (MV3)
- [ ] i18n (pt/en/es)

## Licença
MIT — ver `LICENSE`.
