# FlowStudy · Trilha Hermes

Uma coleção aberta de kits pequenos, verificáveis e reversíveis para quem usa o [Hermes Agent](https://hermes-agent.nousresearch.com/docs/).

A proposta não é criar uma plataforma paralela. Cada kit resolve um problema concreto, instala de forma isolada e pode ser removido sem sequestrar o ambiente do usuário.

## Comece aqui

| Ordem | Kit | O que resolve | Estado |
|---|---|---|---|
| 1 | [Hermes Knowledge Kit](https://github.com/flowstudy-ai/hermes-knowledge-kit) | Organiza Markdown como conhecimento recuperável, auditável e portátil | `v0.1.0` |

## Como escolher

1. Abra o repositório do kit.
2. Leia requisitos e limitações.
3. Execute primeiro o diagnóstico e o dry-run.
4. Instale em ambiente descartável se estiver avaliando.
5. Só depois aplique no profile desejado.

## Princípios da trilha

- **Um problema por kit:** releases, testes e issues independentes.
- **Reversível:** uninstall e rollback fazem parte do produto.
- **Fail-closed:** dúvida de segurança termina com erro, não com falsa aprovação.
- **Sem segredos:** exemplos fictícios e scanner antes de publicação.
- **Poucas dependências:** biblioteca padrão quando suficiente.
- **Prova antes de promessa:** cada kit documenta o que foi realmente testado.

## Próximos kits

Ideias em avaliação, não promessas de entrega:

- backup sanitizado e verificável;
- diagnóstico de segurança;
- organização de produção de conteúdo;
- rotinas de saúde e manutenção do Hermes.

## Convenção dos repositórios

```text
hermes-<problema>-kit
```

Cada projeto deve conter README, licença, política de segurança, contribuição, changelog, testes e CI. Um kit só aparece nesta trilha quando houver artefato funcional e instrução de reversão.

## Participar

Abra uma issue no repositório específico para bugs ou sugestões. Discussões sobre a trilha e propostas de novos kits podem ser abertas neste portal.

## Independência

FlowStudy é uma iniciativa independente. Hermes Agent é um projeto da Nous Research e não faz parte desta organização.

## Licença

Conteúdo deste portal sob licença MIT.
