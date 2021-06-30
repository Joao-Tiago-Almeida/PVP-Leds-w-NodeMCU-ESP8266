# PVP-Leds-w-NodeMCU-ESP8266

O aplicação consiste num PvP, com base em 5 mini-jogos que envolvem LEDS.
Ao fim de cada jogada, aparece no terminal um site onde os jogadores podem ler as regras do jogo, e um frase onde pede aos jogadores para inserirem um número de 1 a 5. Que corresponde a cada mini-jogo.
No primeiro jogo, o semáforo está a vermelha e pode passar ou não pelo amarelo. Ao verde, o primeiro a premir o botão ganha.
No segundo jogo, a ordem pela qual as cores e os LEDS acedem é random. Quando aparecer a luz verde, o primeiro a premir o botão ganha.
No terceiro jogo, há um contagem decrescente em binário, o primeiro jogador que premir o botão quando a contagem já tenha sido acaba ganha.
No quarto jogo, as LEDS vão se acender um determinado número de vezes. No final é perguntado a cada jogador, quantas vezes cada LED se acendem na forma de um número de 4 dígitos, LED: 1234. Neste mini-jogo o botão é inútil, devendo os jogadores responder no terminal.
No quinto jogo, todos os LEDS vão estar ligados, quando uma cor é repetida, o primeiro jogador.a carregar no botão perde.
Optei por não retirar pontos, nem parar a jogada, quando um jogador pressiona o botão antes. Apenas no mini-jogo 4, se o jogador errar, perde pontos.
Para introduzir o número do mini-jogo, o jogador tem de fazer scroll para baixo no écran e depois de introduzir o número do mini-jogo, tem de fazer scroll para cima.
No Serial Monitor, podemos ver se e quando o dispositivo se encontra conectado.
