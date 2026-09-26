# prompt-audit

O prompt-audit é um comando que roda dentro do Claude API (`/claude-api prompt-audit`) e faz duas coisas: audita sua configuração atual e reescreve prompts antigos seguindo as diretrizes do Opus 5.5 da Anthropic. A ideia é resolver o problema de prompts escritos para versões anteriores do modelo — em vez de reescrever tudo na mão, o comando identifica o que está segurando sua setup e ajusta.

## Por que importa

Modelos novos mudam a forma como interpretam instruções. Um prompt que funcionava bem em versões anteriores pode ficar verboso, redundante ou até contraditório no Opus 5.5. Auditar e reescrever manualmente é lento e subjetivo. Um comando único padroniza esse processo e aplica as boas práticas da própria Anthropic sem depender de chute.

## Como começar

Rode `/claude-api prompt-audit` no seu ambiente Claude. Ele analisa a configuração atual, aponta o que está travando os prompts e reescreve com base nas diretrizes do Opus 5.5. Revise o resultado antes de aplicar.

---

**Fonte original:** https://x.com/RoundtableSpace/status/2103548840754471385

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
