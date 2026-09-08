# Zambo

Zambo é uma camada de execução e checkpoint que fica ao lado do agente de IA que você já usa. Ele não substitui Claude, ChatGPT, Cursor ou Cline — ele se conecta via MCP e intercepta o ciclo antes e depois da ação. O loop é direto: Plan, Check, Act, Verify, Prove. Antes de agir, ele verifica se a ação é autorizada, se a informação é atual, se a fonte é confiável, se a operação é segura. Quando o agente diz "done", Zambo pergunta: "prove it". Sem evidência, a tarefa fica incompleta. Não há confiança cega em resposta confiante.

## Por que importa

Elimina o calcanhar de aquiles de agentes autônomos: a resposta plausível sem comprovação. Em vez de aceitar o relatório do agente, você recebe um resultado observável, com checkpoint. Se algo falha, ele para ou espera aprovação. Isso transforma automação em processo auditável.

## Como começar

Conecte seu agente ao Zambo via MCP. A mesma conexão funciona para Claude, ChatGPT, Cursor, Windsurf ou Cline. Defina as políticas de autorização e as fontes confiáveis antes de rodar o primeiro plano. Depois é rodar o loop Plan-Check-Act-Verify-Prove e exigir a prova ao final.

---

**Fonte / repositório original:** https://zambo.dev/

**Visto primeiro em:** https://x.com/brennanzambo/status/2097367643388883033

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
