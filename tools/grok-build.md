# Grok Build

Grok Build agora tem memória entre sessões. Guarda o estado do projeto — codebase, comandos, convenções, decisões e fatos — em arquivos markdown. Cada turno de trabalho atualiza essas notas. Na próxima sessão, ele lê esse contexto antes de mexer no código relacionado. O agente não parte mais do zero toda vez.

## Por que importa

Agentes sem memória repetem perguntas, ignoram convenções e tomam decisões inconsistentes. Com este mecanismo, o contexto persiste como documentação viva. Você pode fechar o terminal, voltar amanhã e ele sabe onde está. As notas ficam auditáveis, em markdown legível por humanos.

## Como começar

1. Ative a memória: `GROK_MEMORY=1`.
2. Inicie uma sessão nova com `/new`.
3. Trabalhe um turno normal.
4. Revise as notas com `/memory browse`.
5. Quando acumulem notas, consolide com `/dream`.

---

**Fonte / repositório original:** https://github.com/xai-org/grok-build

**Visto primeiro em:** https://x.com/minchoi/status/2100620070968000605

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
