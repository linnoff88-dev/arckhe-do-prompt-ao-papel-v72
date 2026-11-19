# Do prompt ao papel

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso aberto e gratuito do INEMA.CLUB, em 8 aulas (formato INEMA Learning v7.2), em portuguÃªs, inglÃªs e espanhol.

**https://inematds.github.io/do-prompt-ao-papel-v72/** Â· [English](https://inematds.github.io/do-prompt-ao-papel-v72/en/) Â· [EspaÃ±ol](https://inematds.github.io/do-prompt-ao-papel-v72/es/)

Primeiro a gente escrevia o pedido palavra por palavra (engenharia de prompt). Depois aprendeu a dar contexto (engenharia de contexto). Agora a IA trabalha como alguÃ©m da equipe, e a habilidade que vale Ã© gerenciar (engenharia de papel).

| # | aula | prÃ¡tica |
|---|---|---|
| 1 | TrÃªs eras: do prompt ao papel | diagnosticar 5 pedidos reais |
| 2 | A era do prompt: o que morreu e o que ficou | auditar um prompt por subtraÃ§Ã£o |
| 3 | A era do contexto | arquivo de regras + liÃ§Ã£o de um erro real |
| 4 | A era do papel: a ficha de funÃ§Ã£o | ficha conferida na pÃ¡gina |
| 5 | Objetivo que dÃ¡ para medir (SMART) | simulaÃ§Ã£o com um agente novo + objetivo conferido |
| 6 | Treinar em ciclo | 5 rodadas, lista de correÃ§Ãµes, procedimento padrÃ£o |
| 7 | Custo | tabela de tarefas e uma semana anotada |
| 8 | A mesma tarefa nas trÃªs eras | comparaÃ§Ã£o + plano com datas |

## O processo, do inÃ­cio ao fim

1. ðŸ§  Plano das aulas (`PLANO.md`).
2. ðŸ§  ConteÃºdo em `conteudo/pt/` (JSON); imagens em `assets/img/` (Codex image_gen, capa composta por `capa/compor-capa.cjs`).
3. âš™ï¸ `python3 gerar.py && python3 validar.py --links` e `node ~/.claude/skills/formato-curso-v72/scripts/conferir-tela.cjs .`
4. ðŸ¤– Revisor independente (agente novo, persona do pÃºblico).
5. âš™ï¸ `python3 ~/.claude/skills/formato-curso-v72/scripts/traduzir.py . en es` (tradutor central, assinatura) â†’ `gerar.py --lang en|es` â†’ validar.
6. ðŸ§  Commit + push (GitHub Pages da raiz da main). VÃ­deos na release `video-v1.0.0`.

ConteÃºdo: CC BY 4.0 Â· INEMA.CLUB, conteÃºdo aberto e gratuito.

## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/387-do-prompt-ao-papel-gerencie-a-ia-como-alguem-da-equipe/)
- [Guia: como aprender inteligÃªncia artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>