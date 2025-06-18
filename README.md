O jogo é um simulador 2D de fazenda com visão de cima, feito inteiramente com comandos de desenho do p5.js, sem uso de imagens externas. O jogador controla um personagem que pode andar livremente pelo mapa usando as teclas W, A, S e D.
Existe também um carro no jogo, que o jogador pode entrar e sair. Quando está dentro do carro, a velocidade de movimento aumenta significativamente, mas apenas enquanto estiver dirigindo. A câmera segue o jogador, deixando sempre o personagem no centro
da tela.
O mapa do jogo é dividido em três áreas principais: a fazenda, a estrada e a cidade. A fazenda contém o terreno onde o jogador pode plantar e colher. Este terreno é quadriculado, com solo desenhado com uma textura de quadrados, simulando os espaços de 
plantio. Cada espaço do solo pode conter uma planta em diferentes estágios de crescimento. As plantas passam por um ciclo de cores: começam mais claras e vão escurecendo até atingir o ponto de colheita. O crescimento das plantas é rápido, levando 
aproximadamente 10 minutos de tempo de jogo para ficarem maduras. Cada planta tem seu próprio contador de crescimento, o que faz com que cresçam em tempos ligeiramente diferentes se plantadas em momentos diferentes.
O jogador começa o jogo com um pequeno terreno de plantio e uma casa simples. Conforme o jogador acumula dinheiro, ele pode fazer upgrades na casa. A casa evolui visualmente, representada por emojis que mudam de uma cabana simples para casas maiores e 
mais sofisticadas. A cada upgrade, o terreno de plantio aumenta, permitindo mais espaço para cultivo. O código foi ajustado para garantir que a casa e o novo terreno fiquem sempre longe da estrada, evitando que o solo de plantio invada a área da 
estrada.
Além do plantio manual, o jogador pode contratar trabalhadores. Existem três tipos: um para plantar, outro para colher e outro para fazer as entregas até a cidade. Cada trabalhador é representado visualmente com um emoji diferente e só aparece no mapa 
depois que for contratado pelo jogador. Eles são adquiridos através de uma loja na cidade, usando o dinheiro ganho com a venda das colheitas.
A cidade fica afastada da fazenda, acessível por uma estrada horizontal. Dentro da cidade, todas as lojas estão reunidas em um único lugar, fora da estrada, criando uma área de comércio organizada. O jogador pode vender as colheitas numa fazenda de 
venda localizada no final da estrada, comprar novas ferramentas que melhoram suas habilidades de plantio e colheita (como plantar ou colher múltiplas plantas ao mesmo tempo) e contratar os trabalhadores.
O jogo tem um sistema de tempo contínuo, com horas e dias que avançam automaticamente. Há um ciclo de dia e noite, com a tela escurecendo gradualmente durante a noite para simular a iluminação natural. Além disso, o jogo começa com um tutorial 
automático, que explica ao jogador como jogar: como plantar, colher, vender, contratar funcionários e fazer upgrades na casa.
O HUD (painel de informações na tela) mostra ao jogador dados como dinheiro disponível, dia e hora do jogo e a quantidade de itens no inventário, como sementes e colheitas. Toda a movimentação, o plantio, a colheita e as interações com o mapa usam 
apenas códigos de desenho do p5.js, garantindo que tudo seja leve e visualmente coeso dentro do estilo pixelado e simples do projeto.
Foi utilizado a IA chatgpt para corrigir e acrescentar detalhes ao projeto.
