# FlowStudy · Trilha Hermes

Peças soltas para quem usa o [Hermes Agent](https://hermes-agent.nousresearch.com/docs/). Instala uma. Não leva a loja inteira. Não é outro Hermes.

Duas gavetas: **kit** (encaixa e tira) e **receita** (jeito do agente escrever/agir).

## Kits

Peça com `doctor`, dry-run, instalar e desinstalar.

| | O que você ganha | Estado |
|---|---|---|
| [Knowledge](https://github.com/flowstudy-ai/hermes-knowledge-kit) | Seus `.md` ficam organizados para o agente achar de novo. | `v0.1.0` |
| [Oracle](https://github.com/flowstudy-ai/hermes-oracle-kit) | O agente consulta a documentação do Hermes nesta máquina, sem inventar. Dá para tirar depois. | `v0.1.0` |

## Receitas

Skill + texto. Sem instalador que finja ligar WhatsApp ou conta.

| | O que você ganha | Estado |
|---|---|---|
| [Briefing de grupos WhatsApp](https://github.com/flowstudy-ai/hermes-recipes/tree/main/whatsapp-briefing) | Um recado por dia, em português claro, a partir do que entrou nos grupos. Chip, QR e ToS são com você. | `v0.1.0` |
| [Escada de pesquisa web](https://github.com/flowstudy-ai/hermes-recipes/tree/main/web-research-ladder) | Busca de graça, página paga, arquivo se bloquear. Não queima scrape na busca. | `v0.1.0` |

O catálogo: [hermes-recipes](https://github.com/flowstudy-ai/hermes-recipes).

## Como escolher

1. Leia o que o repo **não** faz.
2. Kit: rode o diagnóstico e o dry-run numa pasta de teste.
3. Receita: copie a skill; não espere um botão mágico.
4. Só então use no Hermes de verdade.

Não force receita a virar kit.

## Regras

- Um problema por repo.
- Dá para desfazer (kit) ou é só arquivo (receita).
- Na dúvida de segurança, para — não aprova no escuro.
- Sem senha, número real ou conversa no git.
- O README diz o que foi testado de verdade.

## Nome dos repos

```text
hermes-<problema>-kit      # instalador
hermes-recipes             # catálogo de receitas
```

Um kit só entra na tabela quando existir artefato e jeito de tirar. Uma receita só entra quando skill + prompt + limites existirem.

## Participar

Issue no repo do item. Conversa sobre a trilha: issue neste portal.

## Independência

FlowStudy é independente. Hermes Agent é da Nous Research.

## Licença

MIT.
