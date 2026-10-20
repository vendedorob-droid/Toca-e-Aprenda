# Toca e Aprende

Jogo de toque para crianças pequenas (feito para 1 ano e meio). Sete jogos com botões grandes:

- **Animais** — 32 bichinhos, cada toque toca o som de verdade do animal.
- **Família** — mamãe, papai, vovó, vovô, titia, titio, irmãos, primos, dinda e dindo; a voz fala cada um.
- **Frutas** — 17 frutas; a voz fala o nome de cada uma.
- **Veículos** — 16 veículos com seus sons.
- **Cores** — 12 cores; uma voz suave fala o nome de cada uma.
- **Números** — de 1 a 100; a voz fala "Um", "Dois", "Três"...
- **ABC** — letras de A a Z; a voz fala "A", "Bê", "Cê"...

Funciona como app: dá para instalar na tela inicial do celular e usar sem internet.

## Como publicar (GitHub Pages)

1. No GitHub, abra **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)**, e salve.
3. Em 1 ou 2 minutos o jogo fica em `https://vendedorob-droid.github.io/Toca-e-Aprenda/`.

## Como instalar no celular

- **Android (Chrome):** abra o link, toque nos três pontinhos e em **Instalar app** (ou **Adicionar à tela inicial**).
- **iPhone (Safari):** abra o link, toque em **Compartilhar** e em **Adicionar à Tela de Início**.

Depois de aberto uma vez com internet, o jogo funciona offline.

Dica: deixe o volume alto e, no iPhone, a chave lateral fora do modo silencioso.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | O jogo inteiro, com sons e vozes embutidos |
| `manifest.webmanifest` | Nome, cores e ícone do app |
| `sw.js` | Guarda o jogo no aparelho para funcionar offline |
| `icons/` | Ícones do app |

## Créditos dos sons

- **Animais:** gravações do Wikimedia Commons e do Pixabay, reunidas no projeto [shiv19/animal-sounds](https://github.com/shiv19/animal-sounds) (licenças CC0, domínio público, CC BY e CC BY-SA). A lista com autor de cada som aparece em **Créditos dos sons**, na tela inicial do jogo.
- **Gato e veículos:** conjunto [ESC-50](https://github.com/karolpiczak/ESC-50) de K. J. Piczak, clipes do Freesound, licença CC BY-NC 3.0 (uso não comercial).
- **Coruja, campainha da bicicleta, buzina do ônibus, navio e foguete:** sons criados para o jogo.
- **Voz do menu, cores, números e letras:** gerada no [ElevenLabs](https://elevenlabs.io) (voz Carla).
- **Voz da família:** gerada com o modelo Kokoro.
- **Voz das frutas:** gerada no [ElevenLabs](https://elevenlabs.io) (voz Tara).

Por causa da licença CC BY-NC de parte dos sons, este projeto é para uso pessoal, não comercial.
