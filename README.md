# Memória de Números

Jogo de memória em português. Escolha começar com uma sequência de 4 a 10 números; ao acertar, avance até o nível 10. Inclui teclado na tela, teclado físico, botão para cancelar o desafio e suporte PWA.

## Arquivos
- `index.html`: jogo.
- `manifest.json`: configuração para instalação como aplicativo.
- `sw.js`: cache/offline e atualização dos arquivos no navegador.
- `icon-192.png` e `icon-512.png`: ícones do aplicativo.
- `apple-touch-icon.png`: ícone para adicionar à tela inicial do iPhone.

## Testar no computador
Extraia os arquivos e abra `index.html` no navegador. O service worker é registrado quando o jogo está hospedado em HTTPS, como no GitHub Pages.

## Publicar no GitHub Pages
Envie todos os arquivos para a raiz do repositório. Em `Settings → Pages`, escolha a branch `main` e a pasta `/(root)`, depois clique em `Save`.
