# Chess System

Este projeto é um sistema de xadrez desenvolvido em Java para fins didáticos, permitindo jogar partidas de xadrez no console. O objetivo é praticar conceitos de orientação a objetos, tratamento de exceções e estruturação de projetos em camadas.

## Tecnologias Utilizadas

- Java
- IntelliJ IDEA

## Como executar

1. Clone o repositório: git clone https://github.com/jrsrezende/chess-system.git
2. Execute o programa principal no terminal: java -cp src application.Program


## Estrutura do projeto

- `application/`: Contém a interface com o usuário (Program.java, UI.java), responsável pela interação via console.
- `BoardGame/`: Implementa as classes genéricas do tabuleiro, peças e posições, além do tratamento de exceções relacionadas ao tabuleiro.
- `Chess/`: Contém as regras específicas do xadrez, peças, lógica de movimentos, exceções e controle da partida.
- `Chess/pieces/`: Implementa as classes das peças específicas do xadrez (Rei, Rainha, Torre, Bispo, Cavalo, Peão).
