# endles-run
Jogo de corrida sem fim no qual o personagem precisa correr de um dinossauro na era jurassic, ele precisará passar por obstaculos para não bater e não ser comido 

Etapa_1: 1. Escolha da Engine:
Unity: excelente para projetos 2D e 3D, grande quantidade de tutoriais.
Para um projeto simples de corrida infinita, Godot ou Unity 2D são escolhas muito populares.

Etapa_2: 2. Cenário Infinito

Implementar um sistema de scroll lateral:

Mova o cenário para a esquerda continuamente.
Quando uma parte do fundo sair da tela, reposicione-a à direita.
Utilize pelo menos duas imagens idênticas para criar o efeito contínuo.

Etapa_3: 3. Criação do Personagem

Funcionalidades básicas:

Pular
Aplicar força vertical.
Verificar se está no chão antes de permitir outro salto.
Agachar
Reduzir a altura da colisão.
Trocar a animação do personagem.
criar  o design do personagem:

Etapa_4: 4. Inimigo Perseguidor

O dinossauro deve permanecer logo atrás do jogador.

Estratégia simples:
O personagem corre automaticamente.
O dinossauro acompanha uma posição fixa atrás.
Em modos mais avançados, o dinossauro pode acelerar gradualmente para aumentar a dificuldade.

Etapa_5: 5. Sistema de Obstáculos

Criar um Spawner que gere obstáculos em intervalos aleatórios.

Exemplos:
Pedra
Tronco
Cacto
Pterodáctilo

Etapa_6: 6. Condição de Derrota

Utilize colisores para detectar impactos.

Derrota quando:

O personagem toca um obstáculo.
Dinossauro alcança o personagem.

Etapa_7: 7. Pontuação por Distância

A pontuação aumenta conforme o tempo de sobrevivência.

Resumo do jogo:
  O jogo Jurassic run consiste em um personagem que esta na era jurassica e tem que fugir de T-Rex faminto. E um jogo sem fim, ou seja, o personagem corre comtinuamente pelo caminho, saltando obstaculos, escolhendo caminhos, subindo arvores e pulando de galho em galho. com um curto tempo de jogo a velocidade do personagem vai aumentando e com ela também os obstaculos. dentro do jogo tera as chamadas "Dino moedas" (moedas que o personagem ira coletar ao longo do caminho), que ira servir para "Upar" o personagem e até mesmo trocar de personagem.
  O gênero do jogo será de corrida e estara disponivel para dipositivos "Android e Pc" com o publico alvo sendo as pessoas em geral acima de 12 anos.
  Quando o dinossauro pegar o personagem(caso ele bata num obstáculo ou caia) é Gamer Over!

  Historia do jogo:
    Kan, vive em uma ilha cheia de dinossauros e tem que fugir para sobreviver! 
