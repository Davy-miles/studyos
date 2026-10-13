# StudyOS

Organizador de estudos para celular: tarefas, horários, Pomodoro por matéria, notas, mapas mentais, cards, quiz e tutor com IA (por texto ou voz). Funciona sem internet e se instala no Android como um app.

## Publicar no GitHub Pages

1. Em github.com, toque em **New repository**, use o nome `studyos`, marque **Public** e crie o repositório.
2. Em **Add file > Upload files**, envie todos os arquivos desta pasta (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable.png`, `README.md`) e toque em **Commit changes**.
3. Abra **Settings > Pages**. Em **Build and deployment**, escolha **Source: Deploy from a branch**, **Branch: main**, pasta **/ (root)** e toque em **Save**.
4. Espere de 1 a 2 minutos. O endereço será `https://SEU-USUARIO.github.io/studyos/`.

## Instalar no Android

Abra o endereço no Chrome, toque no menu (três pontos) e escolha **Instalar app** (ou **Adicionar à tela inicial**). O ícone aparece junto com seus outros apps e o StudyOS abre em tela cheia.

## Ativar o Tutor com IA (OpenRouter)

1. Crie uma chave em https://openrouter.ai/keys.
2. No app, abra a aba **Tutor**, cole a chave em **Chave de API** e, se quiser, escreva o nome de um modelo (em branco usa `openrouter/auto`).

A chave fica salva só no navegador do seu aparelho. Nunca a coloque dentro dos arquivos nem no GitHub.

## Seus dados

Tarefas, notas, mapas e cards ficam salvos no navegador deste aparelho. Limpar os dados do site apaga tudo, e cada aparelho tem os seus próprios dados.

## Atualizar o app

Troque os arquivos no repositório e abra o app duas vezes para carregar a versão nova. Se você adicionar arquivos novos, mude `studyos-v1` para `studyos-v2` em `sw.js`.
