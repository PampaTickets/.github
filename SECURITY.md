# Como reportar uma falha de segurança

Use este caminho para falha que exponha conta, pagamento, ingresso, QR Code ou dado pessoal de organizador ou participante.

Não abra issue pública, discussão ou pull request descrevendo a falha. Um relato público entrega o problema a quem ainda não deveria vê-lo.

## Para onde enviar

No repositório afetado, abra um relatório privado em **Security → Report a vulnerability**.

| Onde a falha está | Repositório |
|---|---|
| API, pagamento, ingresso, autenticação | [PampaTickets-Backend](https://github.com/PampaTickets/PampaTickets-Backend/security/advisories/new) |
| Interface web | [PampaTickets-Frontend](https://github.com/PampaTickets/PampaTickets-Frontend/security/advisories/new) |
| App Android | [PampaTickets-Mobile](https://github.com/PampaTickets/PampaTickets-Mobile/security/advisories/new) |
| Outro repositório da organização | A aba Security desse repositório |

O relatório privado precisa estar habilitado no repositório (Settings → Advanced Security → Private vulnerability reporting). Sem isso, o link acima não abre o formulário.

## O que escrever

- O que a falha permite fazer e quem é afetado.
- O repositório, a rota ou a tela.
- Os passos que você usou, com o mínimo de detalhe necessário para repetir.
- Se você chegou a ver dado real de outra pessoa. Se chegou, pare o teste ali.

Conta e cartão de teste bastam. Não use dado real de comprador para demonstrar o problema.

## O que acontece depois

Quem mantém o repositório confirma o recebimento, corrige e combina com você o momento de tornar o relato público. Até lá, o detalhe fica no relatório privado.
