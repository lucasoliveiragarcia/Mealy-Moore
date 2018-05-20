#  Autores
O Trabalho foi desenvolvido pelos alunos Olavo Curatola e Lucas Garcia.
# Descrição do Projeto
Trabalho desenvolvido para a disciplina de LFA do curso de Sistemas de Informação. O objetivo do trabalho é a Conversão de Máquina de Mealy para Máquina de Moore equivalente e vice versa, foi desenvolvido usando a linguagem Java.
# Estrutura do Projeto
O projeto encontra-se dentro da pasta compactada MealyMoore.zip . Dentro do pacote mealymoore encontram-se os arquivos abaixo:
- `MealyMoore.java` : Programa principal. Identifica se é um arquivo de entrada Mealy e converte para Moore e vice versa. 
- `Mealy.java` : Funções para conversão de Mealy para Moore.
- `Moore.java` : Funções para conversão de Moore para Mealy.
- `SexExp.java` : Tratamento de S-Expressions.

Na raiz da pasta do projeto encontra-se o arquivo build e no pacote defaultpackage contém os arquivos de teste.

# Modo de uso
Os programas foram desenvolvidos em java 8, e atrvés da IDE NetBeans 8.2tanto  no windows10 como no Ubuntu 17.10.
O programa principal MealyMoore é construido usando a própria IDE gerando um executável na pasta "dist" dentro da estrutura de pastas da IDE. A execução via linha de comando precisa chamar o executável na referida pasta, com o endereço completo ou dentro da própria pasta.
Foi executado diversas vezes via linha de comando em ambos os sistemas operacionais. 
No Ubuntu a própria IDE recomenda o endereço do executável entre aspas duplas, e os arquivos de entrada e saida com endereços completos depois do fechamento da aspas.
Procuramos usar a classe scanner e o split considerando que o tokenizer esta assinalado como "deprecated".
Exemplo da linha de comando no windows10:  
C:\Users\Olavo>java -jar C:\Users\Olavo\Documents\MealyMoore\dist\MealyMoore.jar  -i C:\Users\Olavo\Documents\MealyMoore\src\defaultpackage\testeMealyB.txt -o C:\Users\Olavo\Documents\MealyMoore\src\defaultpackage\saidaMealyB.txt
No Ubuntu 17.10 temos a seguite linha de comando como exemplo:
