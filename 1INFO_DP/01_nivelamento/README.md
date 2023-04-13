# Nivelamento 1INFO

_Resolva os problemas abaixo, sobre os diversos temas que serão abordados em Programação I._

## Variáveis e Operadores
### **<u>Problema 01: Campanha promocional</u>**
Pergunte ao usuário o preço da garrafa de refrigerante. Considere que o mercado está fazendo uma campanha e, ao comprar duas garrafas, serão dados 10% de desconto em cada garrafa. Ao comprar 3 garrafas, serão dados 15% de desconto em cada garrafa.

    Ao final do programa, apresente o valor de venda para uma garrafa, para duas garrafas e para três garradas.

### **<u>Problema 02: Quantidade de tijolos</u>**
Pergunte ao usuário o tamanho da parede a ser construída (área em M²). Calcule a quantidade de tijolos que serão necessários para construir toda a parede, considerando que o tijolo possui 19cm x 19cm e deverão ser subtraídos 3% da área da parede, que corresponde com o cimento que une os tijolos.

    Ao final do programa, apresente a quantidade de tijolos que serão necessários para a área informada pelo usuário.

## Estrutura de Decisão
### **<u>Problema 03: Caixa eletrônico</u>**
Faça um script para um caixa eletrônico. O script deverá perguntar ao usuário a valor do saque e depois informar quantas notas de cada valor serão fornecidas. As notas disponíveis serão as de 1, 5, 10, 50 e 100 reais. O valor mínimo é de 10 reais e o máximo de 600 reais. O script não deve se preocupar com a quantidade de notas existentes na máquina.

    Exemplo: Para sacar a quantia de 256 reais, o script fornece duas notas de 100, uma nota de 50, uma nota de 5 e uma nota de 1;
    
    Exemplo: Para sacar a quantia de 399 reais, o script fornece três notas de 100, uma nota de 50, quatro notas de 10, uma nota de 5 e quatro notas de 1.


### **<u>Problema 04: Investigação criminal</u>**
Faça um script que faça 5 perguntas para uma pessoa sobre um crime. As perguntas são:

    1. "Telefonou para a vítima?"
    2. "Esteve no local do crime?"
    3. "Mora perto da vítima?"
    4. "Devia para a vítima?"
    5. "Já trabalhou com a vítima?"

O script deve no final emitir uma classificação sobre a participação da pessoa no crime. Se a pessoa responder positivamente a 2 questões ela deve ser classificada como "Suspeita", entre 3 e 4 como "Cúmplice" e 5 como "Assassino". Caso contrário, ele será classificado como "Inocente".

## Usando Switch-Case
### **<u>Problema 05: Nota para conceito</u>**
Converta a nota para conceito, conforme a tabela abaixo:

    // Nota                     Conceito
    // Entre 10.0 e 9.0            A
    // Entre 8.9 e 8.0             B
    // Entre 7.9 e 7.0             C
    // Entre 6.9 e 6.0             D
    // Entre 5.9 e zero            E

## Usando Operador Ternário
### **<u>Problema 06: Aumento de preço</u>**
Recebe o preço do produto e calcula o aumento do preço, baseado no seguinte critério:

    Preço	            - Produto
    Até 280(inclusive)	- Aumento de 20 %
    Até 700(inclusive)	- Aumento de 15 %
    Até 1500(inclusive)	- Aumento de 10 %
    Acima de 1500	    - Aumento de 5 %

### **<u>Problema 07: Dificuldade da prova</u>**
Após a realização da Prova de Recuperação de Programação I, os alunos serão abordados para avaliar o nível de dificuldade da prova.
Peça para o programa perguntar para o usuário quantos alunos fizeram a prova de Programação I.

Em cada aluno abordado, deverá ser perguntado o nível de dificuldade da prova, num intervalo de 1 a 5, sendo que o nível 1 é mais fácil e o nível 5 é mais difícil. Também contabilize, entre os alunos abordados, quantos desses são Meninos (O) e quantos são Meninas (A).

    Ao final do programa, apresente os seguintes dados:
    - Quantos alunos avaliaram com grau de dificuldade menor ou igual a 2
    - Quantos alunos avaliaram com grau de dificuldade alto, igual a 5
    - Qual a média de dificuldade da prova, segundo avaliação dos alunos
    - O número de meninos e o número de meninas que realizaram a prova de recuperação.

### **<u>Problema 08: Média de notas</u>**
Peça para o Professor informar as notas dos seus 8 alunos.
Verifique quais notas estão acima e quais notas estão abaixo da média e separe-as em duas listas.

    Ao fim do programa, apresente as notas que estão acima da média e a quantidade de notas.
    Da mesma forma, apresente também as notas que estão abaixo da média e a quantidade de notas.