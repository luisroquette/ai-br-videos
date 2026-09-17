# Office Hour Simulator

O Office Hour Simulator é um projeto da Y Combinator que usa versões em IA dos sócios da aceleradora para conversar com fundadores. O objetivo é dar a mais pessoas a chance de discutir problemas de startup com uma mentoria simulada. No vídeo, a YC explica que precisava de um modelo rápido o bastante para manter uma conversa sem travar. Eles testaram modelos leves da Gemini e da OpenAI, mas a qualidade das respostas não sustentava a experiência.

A solução veio com o GLM-5.2 na plataforma Wafer. A YC fez um deploy dedicado, ajustado para a carga do simulador. Em uma comparação em produção, a configuração com Wafer obteve latência média de 379ms. O GPT-4.1 mini da OpenAI ficou em 546ms. O Gemma 4 31B na Cerebras, em 674ms. A diferença não é só número: os sócios simulados passaram a parecer mais realistas e os usuários relataram gostar mais de conversar.

## Por que importa

Latência baixa muda a percepção de uma conversa com IA. A 379ms, a resposta chega rápido o bastante para manter o fluxo natural. A 546ms ou mais, a pausa quebra a imersão. Esse caso mostra como a escolha de infraestrutura pode impactar diretamente a experiência do usuário em uma aplicação de chat. O teste de produção da YC é um bom benchmark para quem está avaliando modelos de baixa latência em produtos conversacionais.

---

**Fonte original:** https://x.com/gpuemi/status/2100315462961934608

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
