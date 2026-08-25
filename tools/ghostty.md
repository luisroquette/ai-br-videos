# Ghostty

Ghostty é um terminal emulator open-source. O repositório [ghostty-org/ghostty](https://github.com/ghostty-org/ghostty) acaba de implementar o protocolo Kitty clipboard por completo, permitindo que aplicações leiam e escrevam dados não-textuais, como imagens, direto do terminal. É o primeiro terminal fora do projeto Kitty a suportar o protocolo inteiro.

## Por que importa

Isso resolve um gargalo real: antes, colar uma imagem num terminal ou extrair dados binários de uma aplicação de linha de comando era impossível ou exigia gambiarras. Com o protocolo completo, ferramentas como Claude Code conseguem trabalhar com imagens diretamente no fluxo do terminal, sem precisar abrir navegador ou app externo. A implementação já está no nightly da versão 1.4 e também na libghostty, então dá pra usar como biblioteca em outros projetos.

## Como começar

1. Instale o nightly do Ghostty — o pacote estável ainda não tem a feature.
2. Teste com uma aplicação que suporte o protocolo, como o Claude Code.
3. Se for desenvolver, a libghostty já expõe o protocolo completo para integrar em ferramentas próprias.

Sem hype: é uma feature de interoperabilidade bem executada, que destrava casos de uso específicos mas relevantes. Se você trabalha com IA no terminal, vale o teste.

---

**Fonte / repositório original:** https://github.com/ghostty-org/ghostty

**Visto primeiro em:** https://x.com/mitchellh/status/2092001755055972800

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
