# Jogo do Termo em Java Swing

Bem-vindo ao Jogo do Termo! Este é um jogo educativo desenvolvido em Java Swing, onde o jogador deve completar uma matriz de letras com base na análise de uma palavra sorteada.

# Instalação e Execução

Certifique-se de ter o ambiente Java configurado em seu sistema. Para executar o jogo:

1. Clone o repositório:

   ```
   git clone https://seu-repositorio/JogoDoTermo.git
   ```

2. Navegue até o diretório do projeto:

   ```
   cd JogoDoTermo
   ```

3. Compile e execute o jogo:

   ```
   javac Main.java
   java Main
   ```

# Estrutura do Projeto

O projeto é dividido em três partes principais: o `Controller`, que gerencia a lógica do jogo; o `JFrameTermo`, que cuida da interface gráfica usando Java Swing; e o `ModelTermo`, responsável pela lógica de sorteio de palavras e verificação das letras.

- **`Controller`:** Gerencia a interação entre a interface gráfica e a lógica do jogo.

- **`JFrameTermo`:** Cria a interface gráfica usando Java Swing, incluindo a matriz de letras e botões de interação.

- **`JTextFieldTermo`:** Estende `JTextField` para criar células personalizadas que exibem as letras do jogo com cores específicas.

- **`ModelTermo`:** Lida com a lógica do jogo, incluindo a seleção aleatória de palavras e a verificação das letras inseridas pelo jogador.


# Como Jogar

1. **Preencher a Matriz:**
   - Use as setas direcionais ou clique nas células para navegar pela matriz.
   - Digite uma letra em cada célula da linha atual.

2. **Conferir Palavra:**
   - Pressione "Enter" para conferir a palavra digitada na linha atual.
   - Cada letra será destacada com cores diferentes:
     - **Letra Certa no Lugar Certo:** Fundo verde.
     - **Letra Certa no Lugar Errado:** Fundo amarelo.
     - **Letra Errada:** Fundo vermelho.

3. **Ganhar ou Perder:**
   - O jogo é concluído após preencher todas as linhas ou acertar todas as letras em uma linha.
   - Se acertar todas as letras em uma linha, você ganha o jogo!



## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias, corrigir bugs ou adicionar novos recursos. Certifique-se de seguir as boas práticas de desenvolvimento.

## Licença

Este projeto é licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter detalhes.

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- Tymotheo Trisch
- tymotheo.dev@gmail.com
- Seu GitHub: [TymotheoTrisch](https://github.com/TymotheoTrisch)
