# GitNexus

GitNexus cria um grafo de conhecimento do seu repositório local e expõe isso via MCP para agentes como Codex, Cursor ou Claude Code. Em vez de o agente sair lendo arquivo por arquivo, ele consulta um mapa estruturado das relações entre módulos, dependências e fluxos de chamada.

## Por que importa

Agentes de IA falham em repositórios grandes porque perdem o contexto. GitNexus resolve isso na origem: o grafo já vem pronto, então o agente não precisa adivinhar. Você ganha análise de dependências mais precisa e menos alucinação antes de pedir uma mudança. Para codebases com mais de algumas dezenas de arquivos, a diferença é perceptível.

## Como começar

1. Clone o repositório e siga as instruções de build do README.
2. Rode o GitNexus apontando para o diretório do seu projeto.
3. Configure o MCP client (Codex, Cursor ou Claude Code) para apontar para o endpoint local.
4. Faça uma pergunta sobre dependências e veja se o agente responde com base no grafo.

Se você trabalha com monorepo ou código legado, vale o teste. A instalação é direta, mas exige que você já tenha um MCP client funcionando.

---

**Fonte / repositório original:** https://github.com/abhigyanpatwari/GitNexus

**Visto primeiro em:** https://x.com/MoureDev/status/2092961532766212193

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
