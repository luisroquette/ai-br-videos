# claude-api prompt-audit

O comando `/claude-api prompt-audit` roda dentro do Claude Code. Ele varre seus skills, `CLAUDE.md` e prompts, identifica o que está desatualizado ou freando o modelo, remove o que não serve e reescreve tudo com base na orientação oficial do Opus 5.5. A premissa é simples: a maioria dos prompts foi escrita para modelos antigos, e isso vira ruído.

## Por que importa

Modelos novos interpretam instruções de forma diferente. Prompt antigo não é só inofensivo — ele gasta contexto e empurra o modelo na direção errada. Esse comando automatiza uma limpeza que normalmente você faria na mão, e ainda alinha tudo com a documentação atual da Anthropic. Para quem mantém vários skills e um `CLAUDE.md` inchado, é uma economia real de tempo.

## Como começar

Abra o Claude Code e digite:

```
/claude-api prompt-audit
```

Deixe a auditoria rodar e veja o que ele sinaliza como obsoleto. Se o seu setup está cheio de instruções acumuladas, o resultado deve aparecer rápido. O autor é @RLanceMartin, engenheiro da Anthropic — vale seguir para acompanhar updates.

---

**Fonte original:** https://x.com/angeldot_/status/2103095295215100189

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
