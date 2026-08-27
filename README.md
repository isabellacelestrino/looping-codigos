# Terminal Infinito

Terminal simulado em tela cheia, feito para rodar em loop nos monitores da oficina de programação do SENAC Casa Aberta.

Ele digita, com efeito de máquina de escrever, um pequeno projeto web (`index.html` → `style.css` → `script.js`) e volta ao início indefinidamente — sem precisar de nenhuma interação depois de aberto.

## Como usar

1. Abra o arquivo [`index.html`](./index.html) em qualquer navegador (duplo clique funciona).
2. Pressione **F11** para entrar em tela cheia.
3. Deixe rodando — o loop é infinito e não depende de internet depois de carregado (exceto a fonte, que vem do Google Fonts).

## Personalizar

Os trechos de código exibidos ficam no array `SNIPPETS`, dentro da tag `<script>` de `index.html`. Basta editar o texto de `code`, `file` e `label` de cada item para trocar o conteúdo mostrado no loop.
