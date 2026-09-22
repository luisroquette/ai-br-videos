# ECC

ECC é uma configuração de Claude Code que venceu um hackathon da Anthropic e teve o código aberto sob licença MIT. Ela empacota 68 subagentes, 286 habilidades e 94 comandos. O objetivo é transformar o assistente em uma organização de engenharia. O fluxo é rígido: planejamento antes de qualquer linha, teste falho antes da correção, revisão de diff a frio (sem contexto de autoria), revisor distinto por linguagem, reparo de build por cadeia de ferramentas — inclui PyTorch e CUDA — e varredura OWASP mais checagem de injeção na própria configuração do agente.

## Por que importa

A diferença não está na quantidade de agentes, mas no processo. A maioria dos setups de IA age no piloto automático: planeja pouco, testa depois, revisa sem rigor. ECC impõe etapas que forçam o agente a se comportar como um time: planejar, falhar no teste, corrigir, ser revisado por outra “pessoa” sem contexto. Separar revisores por linguagem e corretores por ferramenta ataca pontos que normalmente quebram: compatibilidade com stack, segurança e erros de arquitetura. Isso é acionável. Se você usa Claude Code, vale ler o código e adaptar o que fizer sentido.

---

**Fonte original:** https://x.com/S0N_IA/status/2102367320953827710

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
