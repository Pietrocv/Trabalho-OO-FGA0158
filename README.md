UnB - Universidade de Brasilia  
FGA - Faculdade do Gama  
OO - Orientação por Objetos  
Prof. André Luiz Peron Martins Lanna  


### Trabalho-OO-FGA0158
Repositório para armazenar o código fonte do trabalho final da matéria de Orientação a Objetos.
Pietro Calegari Visentin  Matricula: 232014754


## Objetivo:  
O objetivo deste trabalho prático é aplicar os conceitos fundamentais de
Orientação por Objetos (OO), em especial os conceitos de Herança e Polimorfismo,
no contexto de um sistema de gestão acadêmico. Utilizando o cenário descrito
abaixo e o conjunto de classes presentes nesse diretório (como ponto de partida
para o trabalho), os grupos de quatro alunos deverão implementar um sistema em
Java que explore ao máximo os conceitos de Orientação por Objetos.

## Cenário da Oficina Mecânica:  
Um sistema de gestão acadêmica é responsável, basicamente, por realizar o
cadastro de todos os elementos pertencentes ao domínio de uma universidade. Por
exemplo, o sistema é responsável por cadastrar todos os alunos e professores,
todas as disciplinas, todas as turmas de cada disciplina e, por fim, todas as
salas de aulas. 

Esse sistem deve também ser capaz de criar turmas para cada disciplina e, para
cada turma, deve ser capaz de associar um professor e matricular os alunos,
ambos já existentes no cadastro. Para cada turma, o sistema deverá ser capaz de
imprimir a lista de presença que contenha, obrigatoriamente, o nome da
disciplina, o nome do professor daquela turma, o código da turma e a lista de
alunos (matricula e nome) matriculados. 

O sistema deverá ainda ser capaz de impedir o cadastro de elementos do domínio
que tenham valores em branco para qualquer um de seus atributos. Nesses casos
deverá lançar uma exceção do tipo "CampoEmBrancoException", em que na mensagem
do objeto de exceção seja informado qual o campo que ficou em branco. Com
relação às turmas, essas não poderão serem cadastradas se não tiver uma
disciplina e / ou um professor associado. Nesses casos deverão ser lançadas as
exceções "DisciplinaNaoAtribuidaException" e "ProfessorNaoAtribuidoException",
respectivamente. 

## Exemplos de Execução:  
https://youtu.be/b0omUCPswL8


