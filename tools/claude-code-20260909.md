# Claude Code

O Claude Code é a ferramenta de linha de comando da Anthropic que permite usar modelos de IA diretamente no terminal para escrever e editar código. A versão 2.1.266, lançada recentemente, corrige uma regressão que fazia a ferramenta ignorar a variável de ambiente `CLAUDE_CODE_USE_GATEWAY`. Essa variável é usada para redirecionar o tráfego para um gateway ou proxy, um requisito comum em ambientes corporativos com políticas de segurança rígidas.

## Por que importa

Sem essa correção, empresas que dependem de gateways para controlar o acesso à API da Anthropic viam o Claude Code se conectar diretamente, violando políticas de rede e potencialmente expondo dados. A atualização restaura o comportamento esperado: se a variável estiver definida, o tráfego passa pelo gateway configurado. Isso desbloqueia o uso da ferramenta em ambientes que exigem esse tipo de mediação.

## Como começar

Atualize sua instalação para a versão 2.1.266 (use o gerenciador de pacotes ou o atualizador nativo). Depois, confirme que a variável `CLAUDE_CODE_USE_GATEWAY` está definida no ambiente com o valor esperado. Por fim, teste uma chamada simples para verificar se o tráfego está passando pelo gateway.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2097476972322370027

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
