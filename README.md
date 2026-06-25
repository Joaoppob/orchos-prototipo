# OrchOS Prototipo

Protótipo interativo do OrchOS: uma exploração de design fiction sobre o agente como sistema operacional.

O projeto é estático, sem build e sem dependências. Pode ser aberto direto pelo `index.html` ou servido localmente com `node serve.js`.

## Modos

- Padrão: desktop inicial com Durin.
- Escrita: abre o editor e puxa o Orientador para o chat.
- Desenvolvimento: abre uma IDE simulada inspirada no VS Code e puxa o Desenvolvedor.
- Conversa: abre a janela de conversas.
- Jogo: limpa janelas abertas, usa a imagem do jogo como fundo do campo central e mantém o chat à direita.

## Rodar localmente

```bash
node serve.js
```

Depois abra:

```text
http://127.0.0.1:8123/
```

## Estrutura

- `index.html`: shell do OrchOS.
- `styles.css`: layout, janelas, modos e identidade visual.
- `tokens.css`: tokens visuais.
- `app.js`: estado, modos, agentes, janelas e interações simuladas.
- `assets/`: imagens usadas no protótipo.
