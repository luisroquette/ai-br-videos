# Graft

Graft é uma ferramenta open source que ataca um problema específico de code review: o tamanho do diff não diz nada sobre o risco dele. Um PR de 10 linhas pode quebrar tanta coisa quanto um de 10.000. A ferramenta gera um mapa de impacto para cada pull request — o que mudou, o que depende daquela mudança e se existe teste cobrindo aquele trecho. O objetivo é eliminar a parte de "rastreamento manual" da revisão, que é onde o tempo vai embora.

## Por que importa

O gargalo de review não é ler o diff, é rastrear dependências. Graft automatiza esse rastreamento e entrega o resultado junto com o PR. O diferencial é que ele funciona sem LLM e sem chave de API — o que significa que roda local, sem vazar código pra serviço de terceiro. Nada sai do seu ambiente.

## Como começar

O fluxo é direto: a ferramenta analisa seu PR e devolve o mapa de risco antes de você mergulhar na revisão. O repositório não foi identificado neste contexto, então o caminho de instalação depende de você buscar o projeto oficial. Mas a promessa é clara: menos tempo caçando o que pode quebrar, mais tempo decidindo se o código está certo.

---

**Fonte original:** https://x.com/benyuls/status/2092694620576882740

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
