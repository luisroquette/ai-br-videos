# Claude Code

O Claude Code é um agente de IA que roda direto no terminal. A versão 2.1.268 saiu com 96 mudanças na CLI. O pacote mistura correção de bugs e ajustes de segurança que merecem atenção, principalmente se você expõe o agente fora da sua máquina.

## Por que importa

O destaque é o aviso de exposição. Se a lista `access_control.allow_cidrs` estiver vazia, o startup agora alerta. E a primeira requisição pública dispara um flag. Isso reduz a chance de você deixar o agente acessível na rede sem perceber.

A correção do regex de Artifact resolve o HTTP 400 em endpoints Anthropic-compatible de terceiros. Integrações que estavam quebradas voltam a funcionar sem retrabalho.

E os teammates recriados não herdam mais tools ou prompts de arquivos com o mesmo nome vindos de fontes não confiáveis. Isso bloqueia a injeção de ferramentas inesperadas em fluxos automatizados.

## Como começar

Atualize para a versão 2.1.268. Depois, confira se `access_control.allow_cidrs` está preenchido. Se você usa endpoints de terceiros compatíveis com Anthropic, teste o fluxo de Artifact para confirmar que o HTTP 400 sumiu.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2098151328975319296

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
