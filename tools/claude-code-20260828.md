# Claude Code

Claude Code é um CLI da Anthropic para desenvolvimento assistido. Essa versão 2.1.248 traz 49 mudanças na linha de comando. O destaque é a flag `--restricted`: ela remove ferramentas de execução de código/comandos e bloqueia WebFetch (a menos que explicitamente incluída em `--tools`). Também habilita `SendMessage` e `ListAgents` em Bedrock, Vertex e Foundry com telemetria desligada, permitindo comunicação entre agentes na mesma máquina. Além disso, corrige um bug no prompt-cache que descartava o contexto de pensamento estendido a cada hora, o que quebrava sessões longas.

## Por que importa

`--restricted` dá um controle fino sobre o que o agente pode executar no terminal — útil para ambientes que exigem isolamento ou revisão manual antes de rodar comandos. A correção do cache de prompt resolve um problema real em sessões de debugging ou refatoração longas, onde o modelo perdia o fio da meada a cada hora. Quem usa Claude Code em esteiras ou com modelos hospedados (Bedrock, Vertex) ganha interoperabilidade básica sem enviar telemetria.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2093104161684369626

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
