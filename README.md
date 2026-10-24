# Vida Aberta 0.12.0

Versão web instalável (PWA) do simulador de vida **Vida Aberta**, por Fire.

**Endereço do jogo após ativar o GitHub Pages:** https://firechargeblox-tech.github.io/Vida-Aberta-Jogar/

## Ativar a publicação (uma vez)

1. Abra **Settings → Pages** neste repositório: https://github.com/firechargeblox-tech/Vida-Aberta-Jogar/settings/pages
2. Em **Build and deployment → Source**, selecione **GitHub Actions**.
3. Abra a aba **Actions**, selecione **Publicar jogo Vida Aberta** e execute **Re-run jobs** (ou **Run workflow**).

O workflow extrai automaticamente o pacote `Vida-Aberta-PWA-0.12.0.zip`, verifica os arquivos e publica somente o jogo, sem depender do repositório privado de desenvolvimento.

## Instalar no iPhone

Depois que o site estiver publicado, abra-o pelo **Safari**, use **Compartilhar → Adicionar à Tela de Início** e abra o ícone Vida Aberta. O armazenamento do progresso é local. Exporte backups JSON regularmente porque o iOS pode remover dados locais.

Código-fonte disponibilizado nos termos da [licença MIT](LICENSE). Não é necessário ter uma Conta Apple ou OpenAI para jogar.
