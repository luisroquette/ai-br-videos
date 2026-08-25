# CLAUDE FACILITA CONEXAO DE FERRAMENTAS PARA EMPRESAS COM NOVA AUTENTICACAO

A Anthropic liberou em geral o gerenciamento de autenticação para conectores MCP no Claude. Para admins de planos Team e Enterprise, a autorização agora é centralizada no provedor de identidade da empresa. Isso elimina a necessidade de configurar OAuth individual para cada usuário.

Na prática, o fluxo muda: o admin define as permissões uma vez, e as ferramentas e dados conectam automaticamente para todos os usuários autorizados. O usuário final não lida com tokens nem fluxos de login para cada integração.

## Por que importa

- Reduz atrito operacional: menos tempo configurando integrações e mais tempo usando as ferramentas.
- Segurança centralizada: o controle de acesso fica no IdP que a empresa já usa, sem credenciais espalhadas.
- Escala real: viável para equipes grandes, onde OAuth individual vira gargalo.

## Como começar

Se você é admin do Claude Team ou Enterprise, verifique se o seu provedor de identidade é suportado. A configuração é feita no painel administrativo do Claude, onde você define as políticas de acesso por grupo. Depois disso, os conectores MCP disponíveis para a organização passam a usar essa autenticação automaticamente.

---

**Fonte original:** https://x.com/ClaudeDevs/status/2091953609185657251

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
