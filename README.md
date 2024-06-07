# Jogo da Velha em C++

## Descrição

Este é um projeto simples de um jogo da velha (tic-tac-toe) desenvolvido em C++. O jogo é jogado em um tabuleiro 3x3 e permite que dois jogadores participem, alternando turnos até que um deles vença ou o jogo termine em empate.

## Requisitos

- Compilador C++ (g++ ou equivalente)
- Sistema operacional que suporte a execução de programas em C++ (Linux, Windows, macOS)

## Como Compilar

Para compilar o código fonte do jogo, abra o terminal (ou prompt de comando) e navegue até o diretório onde o arquivo `main.cpp` está localizado. Execute o seguinte comando:

```sh
g++ -o jogo_da_velha main.cpp
Este comando irá gerar um executável chamado jogo_da_velha.

Como Executar
Após a compilação, execute o programa gerado com o seguinte comando:

sh
./jogo_da_velha

Regras do Jogo
O jogo é jogado em um tabuleiro 3x3.
Dois jogadores se revezam para marcar suas posições no tabuleiro.
O jogador 1 usa o símbolo X.
O jogador 2 usa o símbolo O.
Para marcar uma posição, o jogador deve fornecer o número da linha e da coluna onde deseja colocar seu símbolo.
O jogo continua até que um jogador consiga alinhar três de seus símbolos horizontalmente, verticalmente ou diagonalmente, ou até que todas as posições do tabuleiro estejam preenchidas, resultando em empate.
Estrutura do Código
main.cpp: Contém a implementação principal do jogo, incluindo a lógica de jogo, interação com o usuário e exibição do tabuleiro.
Exemplo de Uso
Após iniciar o jogo, o tabuleiro vazio será exibido.
O jogador 1 é solicitado a inserir a linha e a coluna onde deseja colocar o símbolo X.
O tabuleiro é atualizado e exibido novamente.
O jogador 2 é solicitado a inserir a linha e a coluna onde deseja colocar o símbolo O.
O processo se repete até que haja um vencedor ou o jogo termine em empate.
Melhorias Futuras
Implementação de uma interface gráfica.
Adição de um modo de jogo contra a IA.
Salvamento e carregamento de jogos.
Suporte a diferentes tamanhos de tabuleiro.
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para relatar bugs ou sugerir melhorias, e enviar pull requests para implementar novas funcionalidades.

Licença
Este projeto é licenciado sob a MIT License.
