# 🧠 Fuja do PT

Jogo 2D multiplayer online de sobrevivência e pega-pega com tema de apocalipse zumbi.

- Crie uma partida (gera um código de convite) ou entre com o código de um amigo.
- O host escolhe nº de jogadores, tempo, armas e mapa.
- Humanos fogem, barricam portas empurrando móveis e atiram para atordoar zumbis; zumbis infectam por toque.
- Pontos por sobrevivência/infecção compram melhorias na loja (tecla **B**).

Controles: WASD/setas, mouse ou Espaço para atirar, B para a loja.

Multiplayer peer-to-peer (WebRTC via PeerJS): o host é o servidor da partida. Tudo roda em `index.html`.

## Novidades
- Menu inspirado no Braaains.io, com **Loja** (moedas ganhas em partida) e **Personagens** (Marcelo, Vini, JP Prado, Obata, Caio, Bahia, Rosin, Barcelos, F. Ori, Chiang) em pixel art.
- Câmera sempre centralizada no personagem.
- Correção do aviso falso de "host saiu" ao entrar com o código.
- Subtítulo sobre cada jogador na partida: zumbis aparecem como "petista" e humanos como "patriota".
- Skins agora usam a arte pixel art original (rostos extraídos da imagem de referência).
- **Bots (CPU):** botão "Jogar contra bots" no menu e opção de bots no lobby. Os bots completam a partida até o total escolhido (padrão: 50 jogadores), perseguem/fogem usando pathfinding e também empurram móveis.
- Menu e lobby reorganizados (jogar contra bots, criar sala, entrar com código, loja, personagens, como jogar; copiar código; botão de sair na partida).
- v7: personagens com corpo e braços ligados ao tronco; menu rolável em telas baixas.
- v8: o corpo (tronco + braços) gira como uma peça só na direção da mira; a cabeça não gira.
