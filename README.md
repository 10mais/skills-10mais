# Skills 10+

Skills de IA da 10+ para Claude. Cada pasta é uma skill com o seu SKILL.md.

## Skills

| Skill | O que faz |
|---|---|
| planejamento-cliente | Cria o deck de planejamento estratégico de um cliente novo: diagnóstico ITAE, fluxo criativo, tráfego em 3 cenários e playbook de 60 dias. |

## planejamento-cliente: o que enviar

O contrato não é obrigatório. O mínimo para gerar o planejamento é:

1. **A lista de entregas** do cliente. Pode ser em tópicos simples, por exemplo:
   - 12 posts e 4 reels por mês
   - 1 captação mensal
   - Tráfego pago Meta (verba de R$ 1.200)
   - Landing page
2. **A logomarca do cliente** em PNG ou JPG. O fundo branco é removido automaticamente. Sem logo, a capa sai com um espaço reservado escrito "Logomarca do cliente".

Quanto mais contexto, mais personalizado fica o deck. Opcionalmente, envie também:

- Contrato ou proposta (PDF, Word ou texto colado)
- Documento mestre ou briefing (segmento, público, tom de voz, o que evitar)
- Anotações da reunião de venda
- Data de início do contrato. Sem ela, o playbook de 60 dias começa na data do envio.

O que faltar vira um campo entre colchetes no deck, por exemplo [__/__] ou [R$ ____], para preencher na reunião.

Nunca envie senhas ou acessos junto com o material. Eles não entram no deck e devem seguir por um canal seguro.

## Como usar

Para instalar no Claude Code, copie a pasta da skill para `~/.claude/skills/`.
No Claude (app), suba a skill em Configurações › Capabilities › Skills.

Toda skill nova entra em uma pasta própria, com o `SKILL.md` dentro, e ganha uma linha na tabela acima.
