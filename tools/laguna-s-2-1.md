# Laguna S 2.1

A Laguna S 2.1 é um modelo MoE com 117,6 bilhões de parâmetros no total, mas apenas 8,5 bilhões ativos por token. Roda nativamente com quantização NVFP4, uma versão compactada que cabe em GPUs de consumo. Nos testes divulgados, uma RTX PRO 6000 entrega 108 tokens por segundo; um conjunto de 4x RTX 5090 chega a 145 tok/s. Sem nuvem, na sua própria máquina.

## Por que importa

Rodar um modelo desse porte localmente elimina a dependência de API e resolve questões de privacidade e latência. A quantização NVFP4 é nativa, não um hack de pós-processamento — isso preserva a qualidade. O MoE com 8,5B ativos mantém a velocidade alta. Os números são práticos: 108 tok/s numa GPU desktop são suficientes para chatbots, agentes ou processamento em batch. Não é mais cenário teórico.

---

**Fonte original:** https://x.com/RoundtableSpace/status/2094096557100368378

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
