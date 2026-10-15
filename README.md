# 🧠 Fuja do PT

Jogo 2D multiplayer online de sobrevivência e pega-pega com tema de apocalipse zumbi.

- Crie uma partida (gera um código de convite) ou entre com o código de um amigo.
- O host escolhe nº de jogadores, tempo, armas e mapa.
- Humanos fogem, barricam portas empurrando móveis e atiram para atordoar zumbis; zumbis infectam por toque.
- Pontos por sobrevivência/infecção compram melhorias na loja (tecla **B**).

Controles: WASD/setas, mouse ou Espaço para atirar, B para a loja.

Multiplayer peer-to-peer (WebRTC via PeerJS): o host é o servidor da partida. Tudo roda em `index.html`.

## Novidades
- Menu inspirado no Braaains.io, com **Loja** (moedas ganhas em partida) e **Personagens** (Bahia, Caio, Vini, Chiang, Marcelo, Felipe, Prado).
- Câmera sempre centralizada no personagem.
- Correção do aviso falso de "host saiu" ao entrar com o código.
