# Brasil Rush 3D

Um jogo de corrida infinita em 3D inspirado no estilo de jogos como Subway Surfers, criado como projeto de desenvolvimento. A proposta é controlar um personagem em pistas, desviar de obstáculos, coletar moedas e tentar superar o próprio recorde.

**[Jogar Brasil Rush 3D](https://sgdavi488-cell.github.io/subway/)**

## Como jogar

O objetivo é permanecer na pista pelo maior tempo possível. A velocidade aumenta conforme a partida avança.

- Desvie dos obstáculos.
- Colete moedas pelo caminho.
- Acompanhe a pontuação e o tempo desde a última moeda.
- Tente bater o recorde salvo no navegador.

### Controles

| Ação | Computador | Celular |
|---|---|---|
| Mover para a esquerda | A ou ← | Deslizar para a esquerda |
| Mover para a direita | D ou → | Deslizar para a direita |
| Pular | W, ↑ ou Espaço | Deslizar para cima |
| Deslizar/abaixar | S ou ↓ | Deslizar para baixo |

No menu inicial, também é possível escolher entre os personagens disponíveis antes de começar.

## O que o jogo tem

- Cenário tridimensional com três pistas.
- Obstáculos com comportamentos diferentes.
- Moedas que podem ser coletadas durante a corrida.
- Pontuação, contador de moedas e indicador de tempo sem coletar moedas.
- Recorde salvo no LocalStorage do navegador.
- Personagens selecionáveis inspirados em referências brasileiras de esporte e entretenimento.

Os personagens são representações estilizadas feitas para este projeto independente. O jogo não é afiliado, patrocinado ou endossado pelas pessoas retratadas, nem pelos criadores de Subway Surfers.

## Tecnologias

- HTML5
- CSS3
- JavaScript com módulos ES
- [Three.js](https://threejs.org/) para renderização 3D
- LocalStorage para guardar o recorde

O Three.js é carregado por CDN, portanto é necessária conexão com a internet para carregar a biblioteca.

## Estrutura

A versão atual concentra a interface, a lógica do jogo e a configuração da cena no arquivo `index.html`. A biblioteca Three.js é importada diretamente nesse arquivo.

## Executar localmente

Como o projeto utiliza um módulo JavaScript e importa o Three.js pela internet, execute-o por um servidor local em vez de abrir o arquivo HTML diretamente.

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto no VS Code.
3. Inicie um servidor local, por exemplo com a extensão Live Server.
4. Acesse o endereço local no navegador.

Também é possível jogar pela versão publicada no GitHub Pages usando o link no início deste README.

## Ideias para futuras versões

- Separar a lógica do jogo em módulos.
- Adicionar novos cenários, obstáculos e padrões de moedas.
- Melhorar animações e efeitos sonoros.
- Ampliar as opções de personagens e personalização.

---

Projeto de estudo e portfólio desenvolvido por Davi.
