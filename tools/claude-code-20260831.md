# Claude Code

Claude Code é um agente de IA para codificação direto no terminal, com integração a IDEs como VS Code. A versão 2.1.252 corrige três problemas específicos: sessões remotas travavam quando a API degradava, falhas em tarefas de fundo excediam os limites de conversa e causavam perda de requisições, e permissões "always allow" não persistiam sem o arquivo `.claude/settings.local.json`.

## Por que importa

Travamentos em sessões remotas interrompiam o fluxo de trabalho em conexões instáveis — agora o editor continua responsivo. As falhas em background tasks não descartam mais requisições por estouro de tamanho, e as preferências do projeto sobrevivem sem arquivo local. São bugs que afetavam o uso diário, não features novas. A correção torna o trabalho com o Claude Code mais previsível em ambientes reais, sem depender de rede perfeita ou configuração manual. Também elimina retrabalho: permissões que você já concedeu não somem do nada. Se você usa a ferramenta, vale atualizar para evitar essas dores.

---

**Fonte / repositório original:** https://claude.ai/

**Visto primeiro em:** https://x.com/ClaudeCodeLog/status/2094515521056072147

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
