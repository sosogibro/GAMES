O meu trabalho é um jogo da cobrinha feito em JavaScript, utilizando o Canvas do HTML para desenhar os elementos na tela. Primeiro, defini o tamanho do espaço do jogo e criei as variáveis responsáveis pela posição e pela movimentação da cobrinha, das comidas e dos obstáculos.

Depois, desenvolvi a parte que controla os movimentos da cobrinha. Ela pode ser movimentada pelas setas do teclado ou pelas teclas W, A, S e D. O objetivo é comer as comidas que aparecem na tela para ganhar pontos e aumentar o tamanho da cobrinha.

O jogo possui dois tipos de comida: a normal, que vale 10 pontos, e a especial, que vale 30 pontos. A comida especial aparece de vez em quando e desaparece depois de seis segundos se não for comida. Também existem obstáculos que aparecem aleatoriamente e ficam na tela por oito segundos.

Outra parte importante do código é a detecção de colisões. Se a cobrinha bater na parede, no próprio corpo ou em um obstáculo, o jogo termina e a partida é reiniciada. Além disso, implementei um sistema de recorde que salva a maior pontuação e as iniciais do jogador no navegador, mesmo depois que a página é atualizada.

Para fazer tudo funcionar, utilizei funções que atualizam os movimentos, desenham os elementos na tela, criam as comidas e os obstáculos e verificam as colisões. Por fim, criei um loop que mantém o jogo funcionando continuamente.

A principal mudança que fiz foi retirar os portais do código original, deixando o jogo mais simples. Assim, o objetivo é conseguir a maior pontuação possível sem bater nas paredes, no próprio corpo ou nos obstáculos.
