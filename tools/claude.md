# Claude

Sete agentes Claude rodando num MacBook resolvem tarefas de marketing que normalmente exigiriam uma equipe. O fluxo mostrado no vídeo: eles varrem o Google Maps, geram mockups de landing pages, renderizam vídeos e disparam mensagens frias. Tudo isso antes do operador acordar. O resultado relatado é de US$ 18.800 por mês em receita, contra US$ 480 em custos de API.

## Por que importa

O exemplo não é sobre "IA mágica", é sobre orquestração. Cada agente faz uma tarefa estreita e bem definida, e o conjunto trabalha em pipeline. O custo operacional é quase zero comparado a contratar gente ou alugar escritório. Para quem já trabalha com automação, o salto aqui é a coordenação entre múltiplos agentes — não a capacidade de um modelo sozinho.

## Como começar

Não dá para replicar o setup exato sem ver o código, mas o padrão é claro:

1. Defina etapas discretas do seu funil (prospecção, criação, envio).
2. Atribua um agente Claude para cada etapa, com instruções específicas.
3. Use a API da Anthropic para conectar os agentes entre si e a ferramentas externas (Google Maps, renderização, e-mail).
4. Monitore os custos por chamada — a margem entre receita e API é o que torna o modelo viável.

O gargalo vai ser a qualidade do output e a taxa de erro. Agente que alucina endereço ou envia mensagem errada custa caro. Teste cada etapa isolada antes de ligar o pipeline completo.

---

**Fonte original:** https://x.com/RoundtableSpace/status/2092767801417056348

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
