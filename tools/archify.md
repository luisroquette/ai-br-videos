# Archify

Archify é um skill open source que transforma uma descrição ou um repositório inteiro em um diagrama de arquitetura interativo. O resultado não é Mermaid nem um screenshot de Excalidraw: é um HTML auto-contido, com motion, tracing de rotas, busca e focus de nós, exportação para PNG, SVG e WebM, e cards prontos para compartilhar em 1200×630.

O diferencial está na validação. O skill usa um JSON IR tipado com checks atômicos, então ele não inventa conexões. Se a relação entre componentes não está no código ou na descrição, ela não aparece no diagrama. Isso evita aquele problema clássico de diagramas gerados por IA que parecem bonitos mas estão conceitualmente errados.

## Por que importa

Diagramas de arquitetura gerados por IA normalmente são inúteis porque alucinam dependências. Archify resolve isso com um modelo de dados tipado que força o agente a justificar cada aresta. Para times que usam Cursor, Claude Code, Codex ou OpenCode, é uma forma de transformar um repositório legado em documentação visual sem esforço manual — e sem precisar confiar cegamente no que o modelo "achou" que entendia.

## Como começar

O projeto está no GitHub com 16k estrelas. O fluxo básico: instale o skill no seu agente de código, aponte para um repositório ou cole uma descrição, e ele gera o HTML interativo. A partir daí você exporta PNG, SVG ou WebM para compartilhar onde precisar.

---

**Fonte original:** https://x.com/UnTalNixon_exe/status/2092424305455825164

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
