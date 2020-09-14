## Aula 03

### Análise Léxica
- A primeira fase da compilação
- Recebe os caracteres de entrada do programa e os converte
em um fluxo de tokens
- Tokens são unidades lógicas que representam um ou mais
caracteres:
    - Cada palavra­chave é um token. Ex: then, begin, integer
    - Cada identificador é um token. Ex: a, soma, var1
    - Cada constante é um token. Ex: 123, 123.456, 1.2E3
    - Cada sinal é um token. Ex: (, <, <=, +
- A análise léxica é, usualmente, invocada pelo parser cada vez
que um novo token é necessário
- A análise léxica é uma fase que processa caracter por caracter.
Assim, velocidade é um ponto crítico no projeto de analisadores
léxicos
- A análise léxica é dividida em dois processos (executados
nesta ordem):
    - Scanning: remove comentários, remove espaços
desnecessários
    - Análise léxica: agrupa os caracteres em tokens

**Token:** é um par consistindo de um nome de token e um valor de
atributo opcional. O nome do token é um símbolo abstrato
representando um tipo de unidade léxica. Ex: palavra­chave,
identificador, número, etc.
