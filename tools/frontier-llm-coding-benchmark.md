# Frontier LLM Coding Benchmark

Frontier LLM Coding Benchmark é um desafio que mede a capacidade de um modelo de IA gerar código completo, não apenas snippets. No Double Pendulum Challenge, o modelo precisa produzir um único arquivo HTML que simule a física de um pêndulo duplo não linear com integração RK4, e entregar isso como uma experiência visual em Canvas 2D, com glow trail, câmera, HiDPI e coreografia de cena. A tarefa vai além do "fazer funcionar": o modelo precisa manter timestep fixo, conservação de energia e, no modo caos, mostrar que diferenças microscópicas na condição inicial crescem de verdade — não só uma animação falsa.

## Por que importa

O título do vídeo afirma que a OpenAI tirou 97,5 — a nota mais alta, mas não 100. Isso indica que mesmo os melhores modelos atuais erram em algum ponto. O benchmark separa quem decora padrões de quem realmente entende o problema. Exige física numérica correta e, ao mesmo tempo, performance visual. Não dá para apelar para truque de renderização: a física tem que ser real, ou o caos não se manifesta.

O desafio é um bom filtro. Se o modelo entrega um pêndulo duplo que conserva energia e ainda fica bonito, ele tem um nível de competência raro. Caso contrário, fica exposto na comparação.

---

**Fonte original:** https://x.com/AlicanKiraz0/status/2095970338043789323

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
