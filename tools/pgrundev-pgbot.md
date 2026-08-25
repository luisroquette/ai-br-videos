# pgrundev/pgbot

pgbot é uma skill para agentes de IA (Claude Code, Cursor, Codex) que permite inspecionar bancos PostgreSQL de forma segura. Ele roda diagnósticos read-only e entrega as evidências para o agente interpretar. Os cálculos são feitos em Go, não inventados pelo LLM.

## Por que importa

O problema clássico de dar acesso a banco para um agente de IA é o risco de uma query destrutiva ou uma recomendação alucinada. O pgbot resolve os dois: executa apenas leitura e os findings são computados, não "achados" do modelo. Isso significa que você pode delegar análise de saúde do banco sem medo de quebrar produção.

## Como começar

Instale globalmente com:

```bash
npx skills add pgrundev/pgbot -g
```

Depois, dentro do seu agente, pergunte algo como "Is my Postgres healthy?". O pgbot roda os diagnósticos, coleta as evidências e o agente explica o que importa com base nos dados reais.

Sem mudanças automáticas no banco. Sem acesso de escrita. Só leitura e recomendações com base em evidência.

---

**Fonte / repositório original:** https://pgbot.dev/

**Visto primeiro em:** https://x.com/alxshp/status/2092296368329302092

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
