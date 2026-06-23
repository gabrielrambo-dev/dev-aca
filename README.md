# CodeStudy Pro Stable

Versão corrigida para APK.

## O que foi mudado

- O app agora usa um único `index.html` com HTML, CSS, JavaScript e aulas juntos.
- Não depende de `app.js`, `data.js`, `styles.css`, `manifest` ou `service worker` para abrir.
- Isso evita tela bugada/branca no APK quando algum arquivo externo não carrega.
- O workflow usa Node 24 e Java 21.
- Capacitor fixado em 7.4.3.

## Como gerar APK

1. Extraia o ZIP.
2. Envie os arquivos extraídos para um repositório GitHub.
3. Vá em Actions.
4. Rode `Build Android APK`.
5. Baixe o APK em Artifacts.

## Dica

Se instalou uma versão antiga no celular, desinstale antes de instalar esta. Assim você remove cache/dados antigos.
