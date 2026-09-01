# Claude Code

Claude Code é o agente de IA da Anthropic para terminal. Ele lê o repositório, entende o contexto e escreve ou edita código. A versão 2.1.257 chegou com 104 mudanças na CLI. O modelo padrão agora é o Claude Fable 5.1, com 1 milhão de tokens de contexto. Preço: US$ 10/US$ 50 por milhão de tokens, e US$ 0,25 por milhão em leituras de cache.

## Por que importa

1 milhão de tokens é relevante para quem trabalha com repositórios grandes. Dá para manter o projeto inteiro no contexto sem picar arquivos. O Auto mode também ganhou limites: pede confirmação antes de ler arquivos fora dos diretórios de trabalho, e bloqueia auto-aprovação para metadados de nuvem, egress evasion e cross-tenant reach. Isso reduz exposição em ambientes multi-tenant.

## Como começar

Atualize o CLI para a versão 2.1.257. Antes de rodar em produção, revise as novas opções do Auto mode. Teste o Fable 5.1 em um repositório grande para medir o consumo de tokens.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2094851915007828101

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
