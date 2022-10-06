# Projeto01_2223

## Descrição sucinta do problema: 
Elaborar um programa em Java para executar, a partir de um menu, o que for escolhido pelo utilizador.

## Objetivo: 
Consolidação do aprendizado da linguagem Java (estilo livre) 

## Aplicação: 
Escreva um programa que desenha o menu abaixo e executa as ações correspondentes:

(1)	Desenho de padrões

(2)	Jogo do adivinha

(3)	Sudoku simplificado

(4)	Sair

### Caso o utilizador selecione a opção 1:

Deve ser apresentado no ecrã 3 padrões distintos:
#Padrão A

1

1 2

1 2 3

1 2 3 4

1 2 3 4 5

#Padrão B

1 2 3 4 5

1 2 3 4

1 2 3

1 2

1

#Padrão C
        1
        
      2 1
      
    3 2 1
    
  4 3 2 1
  
5 4 3 2 1


Sendo que a figura acima é apenas um exemplo, ou seja, não é obrigatório o número ir até 5, podendo variar, conforme a escolha do utilizador. O número entretanto tem que ser um inteiro positivo menor ou igual a 10.

### Caso o utilizador selecione a opção 2:

O utilizador jogará um jogo com o computador. O computador gera um número aleatório entre 0 e 1000 e a tarefa do utilizador é tentar adivinhar esse número. Por cada tentativa o computador indica se o número introduzido é maior ou menor que o número gerado. Quando for fornecida a resposta correta, o programa escreve o número de tentativas que foram efetuadas e termina. Para gerar um número aleatório pode usar o subprograma Math.random()

### Caso o utilizador selecione a opção 3:

O utilizador jogará uma versão simplificada do jogo Sudoku. O objetivo do jogo é preencher as células vazias de uma matriz de 9x9 com números de 1 a 9, de modo que em cada linha e em cada coluna não haja números repetidos. As células vazias devem ser preenchidas com 0 (zeros).
Nesta versão simplificada:

a)	Crie um subprograma que preencha e devolva uma matriz 9x9. As células da matriz devem ser preenchidas com números aleatórios entre 0 e 9. No preenchimento da matriz deve garantir-se a regra de não repetição de números descrita acima. Esta regra aplica-se apenas aos números de 1 a 9.

b)	Crie um subprograma que, recebendo uma destas tabelas, e as coordenadas x e y de uma posição, crie e devolva um vetor contendo os números que, nesse momento podem ocupar essa posição da tabela, ou seja, todos os que não pertencem à linha e coluna em causa.

c)	Quando o utilizador escolher qual número ele escolheu para a posição pretendida, um daqueles mostrado no vetor, o programa deve mostrar toda a tabela criada, com o valor escolhido pelo usuário na posição indicada por este.

### Caso o utilizador selecione a opção 4:

O programa deve informar algo indicando que a execução irá terminar.

Atenção: O programa só deve terminar quando o utilizador escolher a opção 4!

O objetivo deste projeto assenta no aprendizado da linguagem Java e uso de suas estruturas de dados. Não é necessário neste projeto seguir o paradigma orientado a objetos. O programa deve ser consistente e robusto naquilo que implementa. Devem ser feitas todas as validações relevantes. Não é necessário criar interfaces gráficas para este projeto. 

A aplicação terá que funcionar com um “double-click”. Para isso deve ser feito o “deployment” adequado. A entrega será efetuada através do e-learning, com recurso a um ficheiro “ZIP”(NÃO usar o rar) onde deverá ser incluído: 

•O jar correspondente ao deployment da aplicação; 

•As sources da aplicação 

•Relatório

### Entrega do trabalho: 31/10/2022

### Relatório:

Composto no mínimo pelas seguintes seções:
1.	Capa: nome dos alunos que fizeram o trabalho (grupos de 2 elementos, não são permitidos trabalhos individuais), nome da disciplina, curso, nome da professora e demais informações que considerar relevantes.
2.	Introdução. Breve introdução sobre o problema abordado e objetivo da aplicação, ferramentas usadas e versão do Java usada.
3.	Aplicação. Descrição da aplicação em si.  Um mini guião de como devemos interagir com a aplicação.
4.	Conclusão. Comentários que sejam relevantes sobre o trabalho, dificuldades encontradas, pontos positivos, pontos negativos, etc..

### Avaliação:

•	Máximo de 17 valores se conseguir fazer funcionar com tudo o que foi pedido.

•	Valorização por partes:

•	Mostra o Menu: 0,5

•	Opção 1 funciona como o esperado: 4,5 valores

•	Opção 2 funciona como o esperado: 4,0 valores

•	Opção 3 funciona como o esperado: 7,0 valores

•	Opção 4 funciona como o esperado: 1,0 valores

•	Acresce 1 valor se tiver comentários adequados (tanto em número como em significado).

•	Acresce 2 valores se for feita as devidas validações de modo que impeçam a saída abrupta do programa.

•	Há penalização de até 3 valores se o relatório não for entregue ou estiver incompleto.

No que este enunciado foi ausente, os alunos deverão tomar decisões de implementação e expô-las devidamente no relatório, o qual é de entrega obrigatória, de forma a minimizar a necessidade de esclarecimento de dúvidas por parte da professora.
A facilidade de compreensão do trabalho realizado através da leitura do relatório e dos comentários ao código poderá ser fundamental na valorização do trabalho. Quanto mais fácil for para a professora a compreensão das decisões tomadas na análise e implementação, melhores serão as possibilidades do grupo em termos de avaliação.
O prazo de entrega não é negociável, atrasos são tolerados, mas acarretam em 1 valor a menos na nota final por cada dia de atraso.

### Discussão:

A discussão deste trabalho será realizada no dia 11/11/2022 feita em grupo mas avaliados individualmente. A nota obtida neste dia pode ser diminuída de até a totalidade dos valores se ficar comprovado que nem todo o grupo participou do trabalho de forma equitativa.
Caso seja verificada cópia entre trabalhos, aos trabalhos em causa será atribuída valor ZERO.
