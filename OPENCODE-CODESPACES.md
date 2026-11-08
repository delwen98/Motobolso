# OpenCode no GitHub Codespaces

Esta configuração prepara um ambiente Ubuntu no Codespaces e instala o OpenCode CLI.

## Iniciar
1. Abra este branch no GitHub: `setup/opencode-codespaces`.
2. Crie um Codespace usando o arquivo `.devcontainer/devcontainer.json`.
3. No terminal do Codespace, execute `opencode web --hostname 0.0.0.0 --port 4096`.
4. Abra a porta encaminhada 4096.
5. Configure um provedor/modelo em Settings > Providers. Use apenas credenciais oficiais e nunca compartilhe tokens.

## Custos
O repositório e o OpenCode são gratuitos. O Codespaces tem cotas gratuitas limitadas conforme a conta GitHub. Modelos gratuitos dependem da cota e das condições do provedor; não há créditos Claude incluídos.

## Segurança
Não exponha a porta publicamente. Use a URL privada encaminhada pelo Codespaces e encerre o Codespace quando terminar.
