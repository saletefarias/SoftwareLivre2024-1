# Orientações para o Trabalho Final - Nota Etapa 3

O trabalho final da disciplina exigirá que o aluno faça contribuições mínimas para projetos de software livre, há um conjunto de tarefas com seus respectivos pontos e número máximo de vezes que podem ser realizadas. A nota do aluno será a somatória dos pontos dessas atividades, sendo no máximo 10 pontos.
Há 3 atividades que poderão ser desenvolvidas em equipes ou duplas, mas apenas elas. As demais são individuais.
Cada aluno criará um arquivo pessoal na pasta TrabalhoFinal relatando as tarefas feitas, e colocando links (ou arquivos) para as mesmas.
A data de entrega das tarefas será dia 15 de setembro.

-	Todas as atividades devem ter sido desenvolvidas após o dia 15 de abril;
-	Serão consideradas contribuições para projetos próprios ou de alunos matriculados na disciplina, mas no total de 2 tarefas no máximo;
-	Os bugs reports devem ser originais, não duplicados;
-	As criações de funcionalidades não precisam ser aceitas pelo projeto, mas o aluno deve mostrar que a funcionalidade foi de fato implementada;
-	Cada aluno deverá criar um relatório do seu trabalho final baseado no modelo disponibilizado em [TrabalhoFinal.md](TrabalhoFinal.md);
-	Após finalizado o relatório do trabalho, o aluno deverá incluir também suas colaborações no [relatório da turma](trabalho-final-turma.md);

# Tarefas

| Tarefa                                                | Pontuação | Número máximo de repetições | Em dupla/equipe? |
|-------------------------------------------------------|-----------|-----------------------------|-----------|
| Reportar bug                                          | 1 pt      | 2x                          | Não       |
| Melhorar documentação                                | 1 pt      | 2x                          | Não       |
| Realizar tradução                                    | 1 pt      | 2x                          | Não       |
| Corrigir bug                                         | 3 pt      | ---                          | Não       |
| Adicionar pequena funcionalidade                     | 3 pt      | ---                          | Sim       |
| Adicionar grande funcionalidade                      | 7 pt      | ---                          | Sim       |
| Desenvolver estudo original com artigo sobre software livre | 7 pt      | ---                          | Sim       |


# Relatório do Trabalho Final

Nessa pasta cada aluno deve colocar um arquivo que será o relatório do Trabalho Final desenvolvido. Para tanto, devem ser realizados os seguintes passos:
   - Copiar o arquivo [TrabalhoFinal.md](TrabalhoFinal.md) e renomeá-lo para seu nome, por exemplo, DanielX.md;
   -  Preencher os dados solicitados no modelo;
   -  Separar cada tipo de trabalho, da maneira como estão especificados no documento do trabalho final, em subseções de segundo nível (##);
   -  Para cada subseção, dividir em itens (*) as tarefas realizadas, com um texto curto descrevendo-a e colocando o link para a mesma;
   -  O aluno deverá incluir suas contribuições também no relatório final da turma, que listará todas as colaborações feitas por todos em um único arquivo.

Um exemplo de como ficaria o relatório do aluno segue abaixo:

# Relatório do Trabalho Final - Daniel X

- **Nome completo:** Daniel X
- **Nível:** Graduação
- **Matrícula:** XXXXXXXXX
- **Trabalho em Duplas / Equipe / Individual**

## Reportar Bug

- OpenDSSDirect não suporta qualquer distribuição Linux ([OpenDSSDirect#25](https://github.com/Muxelmann/OpenDSSDirect.make/issues/25)).
- Script do PADE tenta utilizar diretório sem acesso de escrita para salvar base de dados ([pade#6](https://github.com/grei-ufc/pade/issues/6)).

## Adicionar pequena funcionalidade

   - Permite que o OpenDSSDirect busque o caminho para o GCC independente da distribuição ([OpenDSSDirect#24](https://github.com/Muxelmann/OpenDSSDirect.make/issues/24)).
   - Adiciona o comando `END REPEAT` para o pacote `algorithms` do LaTeX ([algorithms#1](https://github.com/algorithms/algorithms/issues/1)).


