# Lemos & Ferraz · Advocacia de Família

Conceito de site para um escritório fictício de direito de família em Gravataí e Porto Alegre (RS), feito como peça de portfólio.

- Abertura em "aba anônima": as dúvidas que as pessoas pesquisam à noite são digitadas sozinhas e respondidas por uma área do escritório (divórcio, guarda, pensão, união estável, inventário, testamento). Tem pausa e atalhos por área.
- Atendimento por vídeo e WhatsApp até as 23h, com status pela hora de Brasília
- Barra fixa "Pergunte em sigilo": a pessoa escreve a dúvida e ela abre no WhatsApp já preenchida
- HTML, CSS e JavaScript puros, sem dependências (fontes Fraunces e Inter Tight embutidas); versão para celular

Escritório, pessoas e endereços são fictícios. Fotos: [Pexels](https://www.pexels.com).

Para ligar o WhatsApp de verdade, preencha `const WHATSAPP = ''` no `index.html` (só dígitos, ex.: 5551999999999). Vazio, os botões mostram um aviso de demonstração.

## Para adaptar a um escritório real

- Trocar nomes, números da OAB (`OAB/RS 00.000`), endereços e telefone, também no bloco `application/ld+json` do `<head>` (SEO local).
- Nota e trechos de avaliações: usar só os reais, do perfil do Google, falando do atendimento (nunca de casos ou resultados).
- Vídeo da advogada: preencher `const VIDEO = ''` com um .mp4 ou link do YouTube.
- Lighthouse mobile (versão publicada): desempenho 97, acessibilidade 100, boas práticas 100, SEO 100.
