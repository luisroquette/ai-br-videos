# Claude Code

Claude Code é um agente de IA que roda direto no terminal. Ele lê o contexto do projeto, edita arquivos e executa comandos de desenvolvimento. A versão 2.1.276 corrige um erro específico: o HTTP 400 com a mensagem "Input tag advisor_20260301" quando `ANTHROPIC_BASE_URL` é usado junto com um proxy.

## Por que importa

O bug travava requisições inteiras em setups que redirecionam o tráfego da API por um proxy — comum em ambientes corporativos ou com gateways customizados. Quem dependia desse fluxo ficava sem resposta do agente sem motivo aparente. A correção restaura o funcionamento normal sem mudar a configuração existente. Se você usa `ANTHROPIC_BASE_URL`, vale atualizar.

## Como começar

Atualize o Claude Code para a versão 2.1.276. Depois, se você usa `ANTHROPIC_BASE_URL` com proxy, rode uma sessão normal e confirme que as requisições passam sem o erro 400. Detalhes completos estão no thread do release.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2100772791796613348

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
