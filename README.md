Jogo da Memória 🤔💭

Descrição:

Jogo da Memória é um jogo de cartas que desafia o jogador a encontrar pares de cartas idênticas. O jogo utiliza uma interface gráfica atraente e animações para criar uma experiência de jogo interativa. 
Esse jogo foi feito para um projeto meu no meu curso de Ti, por isso ele tem esse tema de pão de queijo, pois o mascoque do projeto era um pão de queijo

Funcionalidades:

- O jogo possui um conjunto de cartas que podem ser viradas para revelar a imagem oculta.
- O jogador pode clicar em uma carta para virá-la e, se encontrar um par, as cartas permanecem viradas.
- O jogo possui uma tela de vitória que aparece quando o jogador encontra todos os pares.
- O jogo utiliza animações para criar uma experiência de jogo interativa.

Tecnologias utilizadas:

- HTML: utilizado para criar a estrutura do jogo.
- CSS: utilizado para estilizar o jogo e criar as animações.
- JavaScript: utilizado para criar a lógica do jogo e interagir com o jogador.

Arquivos e pastas:

- public/index.html: arquivo principal do jogo que contém a estrutura HTML.
- public/styles/main.css: arquivo de estilo que contém as regras de estilo para o jogo.
- public/scripts/index.js: arquivo de script que contém a lógica do jogo.
- public/styles/card.css: arquivo de estilo que contém as regras de estilo para as cartas.
- public/styles/responsive.css: arquivo de estilo que contém as regras de estilo para a responsividade do jogo.
- public/styles/win.css: arquivo de estilo que contém as regras de estilo para a tela de vitória.

Como jogar:

1- Abra o arquivo public/index.html em um navegador.

2- Clique em uma carta para virá-la e encontrar um par.

3- Tente encontrar todos os pares para vencer o jogo.

Créditos:

- Dayvid Ornelas: criador do jogo.

Algumas explicação sobre o código:

Animações:

O jogo utiliza animações para criar uma experiência de jogo interativa. As animações são criadas através do uso de CSS Keyframes. Aqui estão os trechos do código responsáveis pelas animações:

![Captura de tela 2024-11-19 152229](https://github.com/user-attachments/assets/35118bca-e4cd-4a9a-90c7-a37eb8ad578c)

Esses trechos de código criam as animações para as cartas, para a tela de vitória e para a responsividade do jogo. 
A animação das cartas é responsável por fazer as cartas se virarem, enquanto as animações da tela de vitória e da responsividade são responsáveis por criar uma atmosfera de jogo mais realista.

Funcionalidades: 

1- Embaralhamento de cartas: Este trecho de código, localizado no arquivo public/scripts/index.js, embaralha as cartas quando o jogo é iniciado. Ele usa a função shuffle (embaralhar) para atribuir uma ordem aleatória a cada carta.

![Captura de tela 2024-11-19 152626](https://github.com/user-attachments/assets/e17eeb0e-d68a-4d38-bc5f-5d75db1b99d3)

2- Função flipCard: Esta função, também localizada no arquivo public/scripts/index.js, é chamada quando uma carta é clicada. Ela adiciona a classe flip à carta, o que faz com que a imagem de verso seja exibida.

![Captura de tela 2024-11-19 152651](https://github.com/user-attachments/assets/45a4d767-8a5e-4fd3-84fd-7b3bbca2e54e)

3- Função checkForMatch: Esta função, também localizada no arquivo public/scripts/index.js, é chamada quando duas cartas são viradas. Ela verifica se as duas cartas são iguais e, se forem, desabilita as cartas.

![Captura de tela 2024-11-19 152719](https://github.com/user-attachments/assets/4322b1cc-ea39-4b4a-ac06-27ddbfc9907f)

Esses trechos são responsáveis pelas funcionalidades principais do jogo e fazem com que ele funcione da forma que ele funciona, tornando-o um jogo dinâmico e atrativo, mas principalmente, funcional.
