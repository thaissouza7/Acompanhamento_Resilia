# Acompanhamento_Resilia

### - :one: Existem outras entidades além dessas três?  
Pode haver outras entidades se necessário, mas em meu projeto, somente a entidade "Facilitadores" foi adicionada, além das entidades "Turma", "Curso" e "Aluno"  

### - :two:  Quais são os principais campos e tipos?
Os campos principais mais utilizados foram os ids e nomes de acordo com a tabela criada, para Ids utilizei o tipo INT e para nomes o tipo VARCHAR

### - :three: Como essas entidades estão relacionadas?
A tabela "turma" com "curso" tem uma relação de muitos para um (N:1), já que pode existir muitos cursos e turma pode ter apenas um curso
A tabela "turma" com "facilitador" tem uma relação de muitos para muitos (N:N), já que facilitador pode ter várias turmas e turma pode possuir vários facilitadores
A tabela "turma" com "alunos" tem uma relação de muitos para muitos (N:N), pois alunos podem pertencer a várias turmas, assim como turmas podem possuir muitos alunos

!



