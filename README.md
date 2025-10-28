## Classe de Avaliação de Notas em Java
### → Descrição

Está classe, utiliza o JOptionPane para criar um sistema simples de avaliação de alunos.
Ele solicita as notas de duas provas e um trabalho, calcula a média e informa se o aluno está aprovado ou reprovado conforme a média obtida.

### → Objetivo

Demonstrar o uso do JOptionPane:

Entrada e saída de dados com JOptionPane

Conversão de dados (String → double)

Estruturas condicionais (if / else)

Tratamento de erros (try/catch)

Formatação de valores numéricos com String.format

### → Funcionamento do Programa

O usuário informa a nota das provas:

Entra o valor da Primeira Nota ↓

Nota da 1ª prova

Entra o valor da Segunda Nota ↓

Nota da 2ª prova

Entra o valor da terceira Nota do trabalho ↓

Nota do trabalho

O programa calcula a média aritmética:

A média se da pela soma dos valores informados, e a divisão por 3.​


A média é analisada:

Se média é igual ou maior que 6.0, então → o aluno está Aprovado

Caso contrário, está Reprovado

O resultado é exibido em uma caixa de mensagem com:

A média formatada com duas casas decimais e a situação final do aluno.

### → Exemplo de Execução ↓

### →Entradas: ↓

Nota 1: 7.0
Nota 2: 8.0
Trabalho: 6.0


### → Saída: ↓

Média: 7.00
Situação: Aprovado

### → Requisitos

Java JDK 8 ou superior

Editor ou IDE (Eclipse, IntelliJ IDEA, NetBeans, VS Code, etc.)

### → Como Executar

Salve o arquivo com o nome:
ClassSistemaAvaliacao.java

Compile a Classe no terminal:

javac ClassSistemaAvaliacao.java


Execute a classe:

java ClassSistemaAvaliacao
