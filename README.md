# JogoDaMemoria
Resumo: Jogo da memória que embaralha os cards a cada turno. Aceito ajuda!

Cada card irá conter 4 informações:
1 - Área em branco com centenas de pequenos quadrados em branco que quando clicado fica preto, que será usada para criar uma imagem. A imagem que será o par desta será criada automaticamente apenas invertendo as cores da imagem criada inicialmente.
2 - Dígito indicando quanto falta para retorno a posição 1.
3 - Número que indique se é a primeira ou a segunda parte da imagem.
4 - Um local com 5 slots para colocar as coornenadas da carta em um determinado turno, serão 5 slots, apenas um ficará disponivel para ser preenchido ele será selecionado de forma aleatória e nunca será o mesmo turno que a carta foi aberta ou o turno anterior.

O jogo é composto por turnos e ciclos, cada ciclo tem 5 turnos, em cada turno será definido uma coordenada para dois ou quatro cards, dependendo da escolha do jogado.
O jogador poderá abrir dois ou quatro cards por turno, se optar por abri 2 por turdo no quinto turno abrirá obrigatoriamente 4.
A quantidade de ciclos que o jogo terá será definido por quantos cards o jogador abriu por ciclo. Se o jogador abrir quatro cards em cada um dos 5 turnos então o jogo terá 5 ciclos, sendo que o jogador terá que indicar as coordenadas de cada carta ao fim do 5 ciclo. Um turno que o jogador abriu dois cards em 4 turnos adicionará um turno extra, podendo assim contabilizar até 10 ciclos, sendo que todos após o 5 ciclos serão obrigatóriamente de turnos com dois cards e 4 no quinto turno.

Logo após desvirar um card a figura muda de local, mas indica em quantos movimentos ela voltará para aquela posição
  
O card cria um caminho aleatório a cada ciclo, então após esse período ela começa a repetir o caminho após completar o primeiro ciclo.
 - Carro em A-1 dígito 4 parte 01
 - O Carro vai para uma posição aleatória e assim por diante até a quinta virada de card e então volta para A-1

** O jogo classico terá 16 posições, 4x4
** O jogo simples terá 4 posições, 2x2
** Inicialmente não existirá nenhuma figura e nem uma casa definida, apenas após abrir a primeira que ira ser escolhida uma primeira imagem e o seu par será gerado respectivamente

****VERSÃO MULTIPLAYER****

Cada face é de um player, vencer o que na sua vez conseguir desvirar todas em sequencia
