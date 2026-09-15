# Mac-1

Mac-1 é um SLM fine-tunado para controlar 487 apps nativos do macOS. O autor queria uma Siri melhor e diz que conseguiu. O modelo roda localmente no Mac. Para chegar lá, ele usou o Codex GPT 5.5 para desenhar o pipeline de fine-tuning: dataset, escolha do modelo base, treino e execução local. Na prática, usou dois Qwen: um 2B para classificação e um 4B para tool calling e respostas.

## Por que importa

O caso mostra um caminho concreto para substituir assistentes de nuvem por um modelo local. Dá para controlar apps nativos com baixa latência e sem mandar dados para fora. Também demonstra que um LLM grande pode orquestrar o fine-tuning de modelos pequenos — o trabalho braçal continua, mas o desenho fica mais acessível.

## Como começar

Pelo relato, o processo foi:

1. Usar um modelo forte (como Codex GPT 5.5) para planejar a estrutura do fine-tuning.
2. Definir o dataset — o autor cita pelo menos 20k exemplos.
3. Escolher SLMs para tarefas específicas: um pequeno para classificação, outro maior para tool calling.
4. Fine-tunar e rodar localmente.

Não há repo público identificado, então os detalhes param por aí.

---

**Fonte original:** https://x.com/cjzafir/status/2099887347437560009

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
