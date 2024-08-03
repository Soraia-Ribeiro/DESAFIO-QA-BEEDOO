Desafio da Beeboo

Etapa 1: Como usuário do sistema Beedoo

         Quero criar, excluir e listar cursos 
         
         Para gerenciar melhor minhas atividades de treinamento.
         
- Decidimos criar uma user story focada na visualização da lista de cursos, pois é o primeiro ponto de interação do usuário.

Casos de Teste
Cenário 1: Criar um Novo Curso

Dado que estou na tela de criação de cursos,

Quando eu preencher todos os campos obrigatórios corretamente e clicar em "cadastrar",

Então o curso deve ser criado e exibido na lista de cursos.

Cenário 2: Criar um Curso com Dados Incompletos

Dado que estou na tela de criação de cursos,

Quando eu tentar salvar o curso sem preencher todos os campos obrigatórios,

Então uma mensagem de erro deve ser exibida, informando quais campos estão faltando.

BUG* Criar um Curso com dados Incompletos

Sistema aceita cadastro sem preencher nenhum campo

Cenário 3: Excluir um Curso

Dado que estou na lista de cursos,

Quando eu selecionar um curso e clicar em "Excluir",

Então o curso deve ser removido da lista de cursos e uma mensagem de confirmação deve ser exibida.

BUG* Excluir um Curso
Ao tentar excluir um curso, o sistema exibe uma mensagem de excluído, mas o curso permanece na lista. 

Cenário 4: Listar Cursos

Dado que estou na tela de cursos,

Quando eu acessar a tela,

Então todos os cursos cadastrados devem ser listados.


[Planilha Desafio Beeboo.xlsx](https://github.com/user-attachments/files/16477884/Planilha.Desafio.Beeboo.xlsx)
