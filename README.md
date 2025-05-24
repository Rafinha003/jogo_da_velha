# 🎮 Jogo da Velha com IA 🤖

Este projeto implementa uma Inteligência Artificial que joga **Jogo da Velha** de forma ideal utilizando o algoritmo **Minimax**. O objetivo é garantir que a IA jogue perfeitamente, nunca perdendo uma partida! 🏆

## 📁 Estrutura do Projeto

- `tictactoe.py`: Toda a lógica do jogo e da IA está aqui. 🧠
- `runner.py`: Interface gráfica simples para jogar contra a IA. 🎨

## Inicie o jogo:

python runner.py

🛠️ Funcionalidades Implementadas
✅ initial_state()
Retorna o tabuleiro inicial vazio.

✅ player(board)
Retorna de quem é a vez: 'X' ou 'O'.

✅ actions(board)
Retorna todas as ações possíveis (casas vazias).

✅ result(board, action)
Retorna um novo tabuleiro após a jogada.

✅ winner(board)
Verifica se há um vencedor (X, O ou None).

✅ terminal(board)
Verifica se o jogo acabou (vitória ou empate).

✅ utility(board)
Retorna a pontuação:

1 se X venceu

-1 se O venceu

0 se empate

✅ minimax(board)

Usa o algoritmo Minimax para retornar a jogada ideal! ♟️

🧠 Sobre o Algoritmo Minimax
O algoritmo Minimax simula todas as possíveis jogadas até o fim do jogo e escolhe o caminho com melhor resultado para o jogador atual. Idealmente:

X sempre tenta maximizar o placar.

O sempre tenta minimizar o placar.

👉 Resultado: Se ambos jogarem perfeitamente, o jogo sempre termina em empate.
