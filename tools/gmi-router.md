# GMI Router

GMI Router é um middleware que decide qual modelo de IA executar cada requisição. No vídeo, três tarefas diferentes — análise de vendas, problema de matemática sobre cache/API e bug de performance em JavaScript — foram enviadas no modo Balanced. O roteador escolheu um modelo diferente para cada uma: Qwen3.7-Max, GPT-5.6-Luna e DeepSeek-V4-Flash, respectivamente. A seleção considera a tarefa, a qualidade esperada e o custo, entre 21 modelos disponíveis.

## Por que importa
O ganho é puramente econômico. Comparado com rodar tudo em um modelo único e caro (Claude Opus 4.8), o GMI Router economizou $0.02–$0.03 por prompt. Em milhares de requisições, isso vira uma redução relevante de custo sem abrir mão de qualidade — porque cada tarefa vai para o modelo mais adequado ao invés de forçar um “faz-tudo” superdimensionado.

---

**Fonte original:** https://x.com/Shruti_0810/status/2093038929897541849

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
