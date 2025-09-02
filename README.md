# chess-system

Sistema de xadrez desenvolvido em Java para fins didáticos, permitindo jogar partidas de xadrez no terminal. O projeto simula as regras do jogo, movimentação das peças, captura, promoção de peões, xeque e xeque-mate.

## Funcionalidades
- Exibição do tabuleiro de xadrez no terminal com cores ANSI
- Movimentação das peças conforme as regras oficiais
- Validação de movimentos e posições
- Captura de peças adversárias
- Promoção de peões
- Detecção de xeque e xeque-mate
- Histórico de peças capturadas

## Tecnologias Utilizadas
- Java (sem frameworks externos)
- ANSI escape codes para colorização no terminal

## Como Executar
1. Clone o repositório: https://github.com/jrsrezende/chess-system.git
2. Abra o projeto em sua IDE Java (ex: IntelliJ IDEA).
3. Execute o arquivo src/application/Program.java.
4. Siga as instruções no terminal para jogar.

## Camadas do Projeto
- `application/`: Interface com o usuário e ponto de entrada do sistema.
- `BoardGame/`: Estruturas genéricas para jogos de tabuleiro.
- `Chess/`: Lógica específica do xadrez, incluindo regras e peças.
- `Chess/pieces/`: Implementação das peças do xadrez.
