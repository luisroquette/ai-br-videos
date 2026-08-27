# Cloud Code

Cloud Code é um projeto open source que roda agentes baseados em Claude diretamente em um celular Android. O exemplo prático: um pipeline com sete agentes que varre o Google Maps, gera mockups de landing page, renderiza vídeos e dispara mensagens de prospecção. Tudo isso sem depender de um servidor dedicado — o hardware é um Android velho.

O custo operacional do experimento foi de US$ 480 em API, com retorno de US$ 18.800 no mês. Não é sobre o valor em si, mas sobre a arquitetura: você coloca um orquestrador de agentes num dispositivo que já tem, paga só o que os modelos consomem e elimina a camada de infraestrutura.

## Por que importa

- Reduz o custo de entrada para automações com múltiplos agentes. Sem VPS, sem Kubernetes.
- O Android vira um worker: ele executa o loop de agentes, não só o client.
- O padrão é replicável. Se o pipeline funciona num celular, funciona em qualquer lugar.

## Como começar

1. Clone o repositório no Android (Termux ou similar).
2. Configure as chaves de API para os modelos Claude.
3. Adapte o pipeline de exemplo para o seu caso de uso — o código é modular.
4. Rode e monitore o custo por execução. O ganho está em otimizar o número de chamadas por tarefa.

O projeto ainda é cru, mas mostra um caminho: automação pesada em hardware descartado. Se você já trabalha com agentes, vale o teste.

---

**Fonte / repositório original:** https://github.com/Janlaywss/cloud-code

**Visto primeiro em:** https://x.com/RoundtableSpace/status/2092767801417056348

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
