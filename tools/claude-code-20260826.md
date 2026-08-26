# Claude Code

Claude Code 2.1.246 chegou com uma mudança relevante: agora dá para lançar agentes dedicados para tarefas complexas de múltiplas etapas. Na prática, você isola subagentes em fluxos de trabalho próprios, em vez de deixar tudo rodando no contexto principal. Isso reduz ruído e evita que o modelo se perca no meio do caminho.

Outra atualização importante está no `/permissions`. A nova aba "Auto mode" permite visualizar e editar as regras do classificador de auto-modo. Você ganha controle fino sobre o que o Claude pode executar automaticamente. Também aumentaram o timeout do safety-check para chamadas de ferramentas em auto-modo — sessões grandes não devem mais sofrer negações temporárias.

## Por que importa

Se você trabalha com pipelines longos ou refatorações que exigem várias etapas, o ganho é direto: menos troca de contexto, mais foco. E o controle sobre o auto-modo resolve um problema clássico — ou a ferramenta era permissiva demais, ou você passava o tempo todo aprovando cada passo.

## Como começar

Atualize para a versão 2.1.246 no seu ambiente. Depois, explore o novo `/permissions` para ajustar as regras do auto-mode conforme seu fluxo. Para testar os agentes dedicados, crie uma tarefa que envolva múltiplas etapas e veja se o isolamento ajuda na execução.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2092383817587658996

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
