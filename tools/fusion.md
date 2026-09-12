# Fusion

Fusion é um harness de codificação multi-modelo. Ele combina modelos de fronteira como GPT-6 Astra e Claude Fable 5.1, e troca de modelo conforme a tarefa. A ideia: o modelo base resolve o problema principal; um sidekick — mais barato ou gratuito — cuida de subtarefas. Isso mantém a performance dos modelos grandes e corta o custo. É o primeiro agente multi-modelo a entrar no Artificial Analysis Coding Agent Index.

## Por que importa

Rodar dois modelos de fronteira juntos costuma sair caro. A Fusion reduz esse custo sem abrir mão da qualidade, porque delega partes do trabalho para modelos menores — alguns gratuitos, como SWE e GLM. Tudo é configurável: modelo base (Fable, Astra, Sol ou Opus), sidekick (SWE, Luna, Sol, GLM), velocidade (Normal ou Fast) e nível de raciocínio. Você ajusta o balanço entre latência, custo e qualidade por tarefa, em vez de aceitar um preset fixo.

## Como começar

A configuração é explícita. Escolha o modelo base. Escolha o sidekick — para custo baixo, use SWE ou GLM. Defina a velocidade e o nível de raciocínio conforme a complexidade da tarefa. Se o custo for prioridade, comece com sidekick gratuito e suba o reasoning só quando precisar.

---

**Fonte original:** https://x.com/dabit3/status/2098557144580735156

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
