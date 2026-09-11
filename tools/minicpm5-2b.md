# MiniCPM5-2B

O MiniCPM5-2B é um modelo denso de 2 bilhões de parâmetros, aberto pelo OpenBMB, feito para raciocínio, código e uso de ferramentas em hardware limitado. No índice Agentic da Artificial Analysis, ele ficou no topo entre modelos abaixo de 4B, com nota 20 — o Granite 4.2 8B fez 9. No teste relatado, o modelo foi conectado a um agente de reparo de CI e recebeu um bug real: retry de checkout com a mesma chave de idempotência retornava um total maior ($109 na primeira chamada, $118 no retry). Ele encontrou a causa raiz, corrigiu sem mudar o contrato público da API e validou a suíte de testes.

## Por que importa

Um modelo de 2B que roda localmente e resolve tarefa de agente que exige tool calling e depuração. O score no Agentic Index supera um modelo de 8B, o que indica eficiência real, não só benchmark de conversa. Para quem trabalha com CI ou automação, dá para rodar offline, sem depender de API externa.

## Como começar

Baixe o modelo no repositório do HuggingFace (openbmb/MiniCPM5-2B) e carregue na sua máquina. Conecte-o a um agente ou ferramenta de reparo de CI e passe uma issue concreta. O modelo cuida da análise, da correção e da verificação dos testes.

---

**Fonte / repositório original:** https://huggingface.co/openbmb/MiniCPM5-2B

**Visto primeiro em:** https://x.com/akshay_pachaar/status/2098335388435943840

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
