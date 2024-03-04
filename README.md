# Classificação de Intervalos

Este exercício de estruruta condicional simples feito em Java determina em qual intervalo um número se encontra e exibe a mensagem correspondente. Os intervalos são definidos como:

- [0,25] : Intervalo fechado à esquerda e aberto à direita.
- (25,50] : Intervalo aberto à esquerda e fechado à direita.
- (50,75] : Intervalo aberto à esquerda e fechado à direita.
- (75,100] : Intervalo aberto à esquerda e fechado à direita.

Se o valor não estiver em nenhum destes intervalos, será exibida a mensagem "Fora de intervalo".

## Como Usar

1. Certifique-se de ter o Java instalado em seu sistema.
2. Clone este repositório ou baixe o arquivo `classificacao-de-intervalos.java`.
3. Compile o código Java:

   ```bash
   javac Main.java
   ```

4. Execute o programa:

   ```bash
   java Main
   ```

5. Insira um número quando solicitado.

   O programa determinará em qual intervalo o número se encontra e exibirá a mensagem correspondente.

## Exemplos

- Se o usuário inserir `15`, a saída será "Intervalo [0, 25]".
- Se o usuário inserir `50`, a saída será "Intervalo (25, 50]".
- Se o usuário inserir `75`, a saída será "Intervalo (50, 75]".
- Se o usuário inserir `101`, a saída será "Fora de intervalo".

## Detalhes do Código

- O programa utiliza estruturas condicionais `if-else` para determinar o intervalo do número inserido.
- Os intervalos são tratados como descrito na descrição do problema.
- Se o número estiver fora dos intervalos especificados, é exibida a mensagem "Fora de intervalo".
---
