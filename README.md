# Fronteira Selvagem

Protótipo inicial de um jogo de sobrevivência 3D para navegador, pensado primeiro para celulares Android.

## Como jogar
- Cuide da vida, fome e sede: fome e sede diminuem com o tempo; cada suprimento recupera ambas.
- Se fome ou sede chegar a zero, sua vida começa a diminuir. Se a vida acabar, reinicie a missão.
- Abra **index.html** no GitHub Pages ou em um servidor web estático.
- Toque em **Iniciar missão**.
- Use o controle circular esquerdo para andar. Árvores e pedras bloqueiam a passagem.
- Arraste a parte direita da tela para girar a câmera.
- Aproxime-se de um suprimento verde e toque em **AÇÃO** para recolhê-lo; ele recupera fome e sede.
- Procure os montes de madeira e pedras espalhados pela mata e use **AÇÃO** perto deles para coletar materiais.

## Controles
- Celular: joystick virtual (esquerda/direita corrigidas), arrasto na área direita para câmera, botão **CORRER** (segure) para acelerar e botão **AÇÃO** para interagir.
- Para recolher: fique a poucos passos do suprimento e toque em **AÇÃO**.
- Computador: WASD ou setas para andar; mouse para girar a câmera.

## Estado do projeto
Versão 0.4 — inclui barras de vida, fome e sede; os suprimentos recuperam fome e sede; quando uma delas zera, a vida diminui até o fim da partida. Mantém cenário 3D procedural, colisão aproximada com troncos e pedras, corrida, deslizamento lateral e coleta contextual pelo botão **AÇÃO**, inventário de madeira e pedra e dez pontos de coleta de materiais. O motor PlayCanvas é carregado por CDN, então é necessária conexão com a internet.

## Próximas etapas
1. Testar em aparelhos Android reais e otimizar desempenho.
2. Melhorar personagem, animações, colisões e interação contextual.
3. Adicionar fabricação de ferramentas e construção de abrigo.
4. Adicionar ameaças, salvamento e progressão.
4. Planejar multiplayer somente depois de estabilizar a experiência solo.

Este é um protótipo inicial: ainda não é um jogo completo nem possui multiplayer.
