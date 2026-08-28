# Gemini Omni 1.1 Flash

O Gemini Omni 1.1 Flash é um modelo da Google DeepMind que adiciona geração e controle de vídeo diretamente na API Gemini. Dá para estender cenas, definir primeiro e último frame, fazer rascunhos em 360p, upscale até 4K e incluir referências de vídeo no input multimodal.

## Por que importa
Você controla o início e o fim do vídeo, o que elimina cortes cegos. O upscale 4K e o rascunho 360p permitem iterar rápido sem gastar processamento à toa. E o input multimodal com vídeo de referência abre caminho pra edição guiada por contexto visual.

## Como começo
Acesse o AI Studio (aistudio.google.com) ou chame a Gemini API diretamente. No playground, selecione o modelo "Gemini 1.1 Flash" e teste os parâmetros de vídeo: `firstFrame`, `lastFrame`, `resolution` (360p ou 4K). Para estender cenas, use o campo `extendScene` no prompt. Consulte a documentação oficial para detalhes de autenticação e limites de requisição.

---

**Fonte original:** https://x.com/GoogleAIStudio/status/2093008678118998298

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
