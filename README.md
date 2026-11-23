# pe-de-cabra

Cortes de vídeo sugeridos por IA a partir da legenda, revisados por uma pessoa e renderizados com ffmpeg. Este repositório guarda só as versões publicadas: os instaladores, os pacotes de atualização e as notas de cada versão.

**Última versão: [0.1.0](https://github.com/ai-driven-projects/pe-de-cabra-releases/releases/tag/v0.1.0)** (2026-11-23). Os links abaixo baixam sempre a versão mais recente.

## Baixar

| Sistema | Instalador | Sem instalar |
| --- | --- | --- |
| Mac com Apple Silicon | [PeDeCabra-osx-arm64-Setup.pkg](https://github.com/ai-driven-projects/pe-de-cabra-releases/releases/latest/download/PeDeCabra-osx-arm64-Setup.pkg) | [PeDeCabra-osx-arm64-Portable.zip](https://github.com/ai-driven-projects/pe-de-cabra-releases/releases/latest/download/PeDeCabra-osx-arm64-Portable.zip) |
| Mac com Intel | [PeDeCabra-osx-x64-Setup.pkg](https://github.com/ai-driven-projects/pe-de-cabra-releases/releases/latest/download/PeDeCabra-osx-x64-Setup.pkg) | [PeDeCabra-osx-x64-Portable.zip](https://github.com/ai-driven-projects/pe-de-cabra-releases/releases/latest/download/PeDeCabra-osx-x64-Portable.zip) |
| Windows | [PeDeCabra-win-x64-Setup.exe](https://github.com/ai-driven-projects/pe-de-cabra-releases/releases/latest/download/PeDeCabra-win-x64-Setup.exe) | [PeDeCabra-win-x64-Portable.zip](https://github.com/ai-driven-projects/pe-de-cabra-releases/releases/latest/download/PeDeCabra-win-x64-Portable.zip) |

Para saber qual é o seu Mac: menu Apple > **Sobre Este Mac** > Chip (Apple M…) ou Processador (Intel).

## Primeira abertura

O aplicativo ainda não é assinado pela Apple nem pela Microsoft:

- **macOS:** se o sistema recusar abrir o instalador ou o aplicativo, clique nele com o **botão direito** e escolha **Abrir** (ou vá em Ajustes do Sistema > Privacidade e Segurança > **Abrir Mesmo Assim**). Só na primeira vez.
- **Windows:** se aparecer "O Windows protegeu o computador", clique em **Mais informações** > **Executar assim mesmo**.
- **Linux:** dê permissão de execução ao `.AppImage` (`chmod +x`) e abra-o.

## Pré-requisitos

- [ffmpeg](https://ffmpeg.org/download.html), para renderizar os cortes.
- [VLC](https://www.videolan.org/vlc/), só no Linux, para o player (no macOS e no Windows ele vem junto).
- [Claude Code](https://claude.com/claude-code), instalado e logado, para sugerir os cortes.

## Atualizações

Só é preciso baixar uma vez. O aplicativo procura versões novas ao abrir e a cada 6 horas, baixa em segundo plano e mostra a faixa **Reiniciar e atualizar**.

As notas de cada versão ficam em [Releases](https://github.com/ai-driven-projects/pe-de-cabra-releases/releases). Os outros arquivos de cada release (`*.nupkg`, `releases.*.json`, `assets.*.json`, `RELEASES-*`) são os que o próprio aplicativo usa para se atualizar.
