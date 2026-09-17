# Wafer

O Wafer é uma plataforma de inferência para LLMs que a Y Combinator usou para rodar o Office Hour Simulator — uma versão em voz dos seus sócios para discutir ideias de startup. A YC testou modelos leves da OpenAI e Gemini antes de migrar para o GLM-5.2 em um endpoint dedicado no Wafer.

Na comparação com GPT-4.1 mini (OpenAI) e Gemma 4 31B (Cerebras), o Wafer entregou 31% menos latência média que a OpenAI e 44% menos que a Cerebras. O efeito prático: usuários ficaram 2,5 minutos a mais conversando com os sócios simulados.

## Por que importa

Latência não é métrica de benchmark — é a diferença entre uma conversa fluida e uma espera constrangedora. Em interfaces de voz, cada 100ms extra quebra o ritmo e faz o usuário desistir. Os números da YC mostram que a escolha do provedor de inferência impacta diretamente o engajamento: menos latência, mais tempo de conversa. Para quem constrói agentes de voz, o caso serve como referência prática de que modelo leve não compensa se a infraestrutura atrasa a resposta.

---

**Fonte original:** https://x.com/wafer_ai/status/2100315312449364066

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
