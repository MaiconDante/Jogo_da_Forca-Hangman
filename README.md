# Jogo da Forca em Python (HANGMAN)

Este é um simples jogo de forca feito em Python, no qual o usuário tenta adivinhar uma palavra sorteada dentro de um limite de tentativas. O jogo é executado no terminal e utiliza funções básicas da linguagem.

## Como funciona

O jogo sorteia uma palavra aleatória de uma lista pré-definida e exibe no terminal um desenho representando o enforcamento, conforme o número de tentativas erradas. O jogador precisa adivinhar a palavra correta antes que o limite de tentativas seja atingido.

## Regras do Jogo

1. A palavra é sorteada aleatoriamente de uma lista de palavras.
2. O jogador possui 6 tentativas para adivinhar a palavra.
3. A cada tentativa incorreta, uma parte do desenho do enforcado é exibida.
4. Se o jogador acertar a palavra antes de esgotar as tentativas, ele vence.
5. Se o jogador esgotar todas as tentativas sem acertar a palavra, ele perde.

## Estrutura do Código

- **Função `limpa_tela()`:** Limpa a tela, compatível com sistemas Windows e Mac.
- **Variáveis:**
  - `palavras_aleatorias`: Lista de palavras para o sorteio.
  - `palavra_sorteada`: Palavra escolhida aleatoriamente para a partida.
  - `limite_jogada`: Número máximo de tentativas.
  - `tabuleiro`: Desenho do enforcado, exibido conforme os erros.
- **Loop principal:** Exibe o tabuleiro, solicita a entrada do jogador e verifica se a letra digitada está correta.

## Como Executar

Para rodar o jogo, certifique-se de ter Python instalado. Em seguida, salve o código em um arquivo com extensão `.py`, e execute o comando:

Exemplo de Uso
O jogo irá exibir:

==================================================
>>>>>>>>>>>>>>>>>>>> HANGMAN <<<<<<<<<<<<<<<<<<<<
==================================================
+--------+
|        |
|        0
|       /|\
|       / \
|
===========
==================================================
Digite uma letra para ver se advinha a palavra R ->

### Requisitos

Python 3.6+

### Contribuição

Sinta-se à vontade para melhorar o código, adicionar novas funcionalidades ou otimizar a lógica.