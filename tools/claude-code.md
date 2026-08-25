# Claude Code

Claude Code 2.1.245 saiu. A atualização tem um foco claro: corrigir um crash de inicialização em distribuições Linux com glibc 2.44. Se você rodava Claude Code nesse ambiente e ele morria na largada, agora ele sobe.

Além do fix, a CLI mudou. Foram 26 comandos adicionados e 19 removidos. Isso altera o que você pode automatizar via script. Se você depende de comandos específicos da versão anterior, vale revisar seus workflows antes de atualizar.

## Por que importa

O crash em glibc 2.44 era um bloqueio real para quem usa distros recentes. Agora o CLI volta a funcionar nesses sistemas. A mudança no conjunto de comandos é maior: 45 alterações no total. Isso significa que sua automação pode quebrar se usava algum dos 19 comandos removidos. É uma mudança que exige atenção, não só um update automático.

## Como começar

1. Atualize o Claude Code para a versão 2.1.245.
2. Rode `claude --help` para listar os comandos disponíveis.
3. Compare com os scripts que você usa. Se algum comando sumiu, ajuste o script.
4. Teste a inicialização na sua distro com glibc 2.44 para confirmar o fix.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2092120356664271227

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
