# claude-api

A claude-api é uma ferramenta de linha de comando que ataca um problema específico: custo de chamadas à API do Claude. Ela oferece comandos para auditar prompts, ajustar o nível de esforço (effort) e migrar configurações. A ideia central é cortar gastos sem alterar o fluxo de trabalho existente.

## Por que importa

O custo da API do Claude escala rápido com o uso de raciocínio máximo em tarefas triviais. Ajustar o effort para baixo em tarefas que não exigem reasoning pesado é uma economia imediata. Além disso, prompts mal escritos geram tokens desperdiçados — o audit pega isso antes de virar fatura. A mudança de effort no meio da conversa sem invalidar o cache é um detalhe técnico que evita re-processamento caro.

## Como começar

1. Rode `/claude-api cost-optimize` para deixar a ferramenta identificar onde estão os gastos desnecessários.
2. Use `claude-api prompt-audit` para listar prompts ineficientes e corrigi-los.
3. Defina effort baixo para tarefas simples — e altere no meio da conversa se o contexto mudar, sem medo de cache hit.
4. Atualize a configuração da API com `claude-api migrate` quando precisar alinhar com versões novas.

---

**Fonte original:** https://x.com/RoundtableSpace/status/2095289416965083252

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
