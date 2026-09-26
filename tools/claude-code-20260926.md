# Claude Code

O Claude Code é o agente de código da Anthropic. A versão 2.1.283 trouxe 94 mudanças na CLI. O destaque é o `load_test_mode`: ele constrói e assina requisições, bloqueia o envio para o upstream e responde com dados fixos. Dá para fazer teste de carga sem tocar em servidor real.

## Por que importa

Teste de carga geralmente exige ambiente dedicado ou risco de derrubar produção. Com o `load_test_mode`, o servidor recebe o mesmo formato de requisição, mas não sofre impacto. Outro ponto: `availableModelsMatch='exact'` trava o modelo na versão nomeada. Nada de release novo quebrar seu ambiente por surpresa. O cabeçalho `x-claude-code-prompt-id` ajuda a correlacionar requisições de um mesmo prompt em gateways de LLM.

## Como começar

Atualize o Claude Code para a versão 2.1.283. Para testar carga, ative o `load_test_mode` na configuração e rode o cenário. Para fixar modelo, use `availableModelsMatch='exact'` com a versão desejada. O changelog completo está no thread do release.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2103606260356526414

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
