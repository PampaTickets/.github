# Como contribuir

Vale para todos os repositórios da organização que não tiverem o próprio `CONTRIBUTING.md`.

## Antes de abrir o pull request

1. Confira se a mudança já está decidida. Arquitetura, contrato de API e regra de produto nascem em [PampaTickets-Docs](https://github.com/PampaTickets/PampaTickets-Docs). Se o contrato muda, o pull request da documentação vem primeiro.
2. Abra o pull request no repositório da frente que você alterou (backend, frontend, mobile ou docs).
3. Descreva o que mudou e como testar. O modelo de pull request pede esses dois pontos.
4. Rode os testes do repositório. O comando está no `README.md` de cada um.

## Commits

Mensagem em português, no modo imperativo, com um destes prefixos:

`feat:`, `fix:`, `refactor:`, `docs:`, `test:`, `chore:`

Use escopo quando o repositório tiver mais de uma área: `feat(monolito): …`. No repositório de documentação, os prefixos `adr:`, `design:` e `api:` também valem.

## Issues

Use o modelo que o GitHub oferecer. Bug pede o que aconteceu, o que você esperava e como repetir. Ideia pede o problema de quem organiza ou de quem compra, antes da solução.

## O que não entra no Git

Senha, token, chave de API, `.env`, `local.properties` e código de recuperação. Se algo disso já foi commitado, avise pelo caminho de [SECURITY.md](SECURITY.md) e troque o segredo.
