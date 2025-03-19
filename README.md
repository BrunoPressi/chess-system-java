# Chess System - Projeto de Jogo de Xadrez em Java

## Descrição
Este é um projeto desenvolvido no curso de **Programação Orientada a Objetos com Java**, ministrado pelo Prof. Dr. Nelio Alves. O objetivo é aplicar conceitos de POO na implementação de um sistema de jogo de xadrez baseado em console.

## Funcionalidades
- Representação do tabuleiro e peças de xadrez
- Movimentação de peças respeitando as regras do jogo
- Controle de turnos e alternância entre jogadores
- Tratamento de jogadas inválidas com exceções
- Implementação de regras especiais:
  - Roque
  - En Passant
  - Promoção do Peão
- Detecção de xeque e xeque-mate
- Interface simples baseada em console

## Tecnologias Utilizadas
- **Java** (linguagem principal)
- **Paradigma Orientado a Objetos**
- **Estruturas de Dados** (matrizes, listas)
- **Tratamento de Exceções**

## Como Executar
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/chess-system-java.git
   ```
2. Acesse o diretório do projeto:
   ```sh
   cd chess-system-java
   ```
3. Compile o código-fonte:
   ```sh
   javac application/Program.java
   ```
4. Execute o programa:
   ```sh
   java application.Program
   ```

## Estrutura do Projeto
```
chess-system-java/
├── application/
│   ├── Program.java  # Classe principal
├── boardgame/
│   ├── Board.java  # Representação do tabuleiro
│   ├── Piece.java  # Representação de uma peça genérica
│   ├── Position.java  # Representação de uma posição no tabuleiro
├── chess/
│   ├── ChessMatch.java  # Gerencia a partida de xadrez
│   ├── ChessPiece.java  # Representa uma peça de xadrez
│   ├── ChessPosition.java  # Converte coordenadas do xadrez para matriz
│   ├── Peças (King.java, Rook.java, Bishop.java, etc.)  # Implementação das peças
├── ui/
│   ├── UI.java  # Interface baseada em console
```

## Autor
Projeto desenvolvido com base no curso de **Programação Orientada a Objetos com Java** do professor **Nelio Alves**.

## Licença
Este projeto é de uso educacional e não possui uma licença específica.

