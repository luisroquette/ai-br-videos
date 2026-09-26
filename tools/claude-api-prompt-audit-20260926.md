# claude-api prompt-audit

O comando `/claude-api prompt-audit` roda dentro do Claude Code e audita seus arquivos de instrução — CLAUDE.md, skills e prompts. Ele procura frases genéricas como "double check your work" e "think step by step". Essas linhas foram escritas para modelos antigos. Em modelos atuais como o Opus 5.5, elas adicionam ruído e pioram a saída. O comando corta o que não ajuda e reescreve o restante com base nas diretrizes oficiais da Anthropic.

## Por que importa

A maioria dos prompts acumula instruções que faziam sentido há algumas gerações de modelo. Hoje elas só atrapalham. Uma auditoria de 5 minutos remove esse peso e deixa o modelo responder de forma mais direta. É manutenção de prompt como quem faz refactor de código.

## Como começar

Abra o Claude Code e execute:

`/claude-api prompt-audit`

Ele escaneia skills, CLAUDE.md e prompts, mostra o que cortar e sugere a reescrita. Revise as mudanças antes de aplicar. Se você versiona prompts, commite o diff.

---

**Fonte original:** https://x.com/cyrilXBT/status/2103722485242118308

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
