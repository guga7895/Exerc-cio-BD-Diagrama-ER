# Exercicio-BD-Diagrama-ER
Diagrama Entidade-Relacionamento para os seguinte problemas de uma lista de exercícios da disciplina Banco de Dados 1:

## Exercício 1:
Uma rede de hospitais deseja construir um sistema para armazenamento e gerenciamento
de informações importantes. Um hospital da rede apresenta como atributo único a sua
localização. Um hospital possui várias alas, sendo que cada ala possui um enfermeiro
responsável. Cada ala em um hospital possui um identificador (ID). Para cada enfermeiro
deve-se armazenar o seu nome completo, número de CRE (único) e o enfermeiro-chefe a
quem ele se reporta. Enfermeiros podem atender a apenas uma ala. O hospital atende a
planos de saúde e, para cada um destes, é necessário saber quais são os médicos
credenciados. Cada plano de saúde possui um nome (único) e números de telefone para
contato. Para cada médico deve-se registrar o CRM (único), o nome e a especialidade.
Qualquer atendimento de um médico a um paciente deve ser registrado com a data e a hora
em que este ocorreu. Um mesmo paciente pode ser atendido por mais de um médico. Cada
paciente deve ter registrado o seu CPF, nome, endereço completo e telefones de contato.
Desenhe um diagrama ER para essa aplicação. Discuta todas as considerações feitas
por você, justificando suas escolhas para o projeto.

## Exercício 2:
Uma empresa responsável por controle de impressões de livros precisa armazenar
informações sobre os mesmos. Cada livro é identificado pelo seu ISBN. Outras informações
a respeito dos livros, como título e data de publicação, também são armazenadas. Há
também a necessidade de se armazenarem informações a respeito das editoras dos livros. De
cada editora serão armazenados um número de identificação único, seu nome e endereço.
Um livro pode estar associado a uma editora somente. Deseja-se ainda controlar informações
a respeito dos autores dos livros, como número de identidade, nome e endereço. Cada livro
pode ser escrito por um ou mais autores. Quando um livro precisa ser impresso, é enviado
para a gráfica da própria empresa, ou pode ser enviado para uma gráfica terceirizada. A
gráfica da própria empresa possui um número de identificação e nome. Para as gráficas
terceirizadas são armazenados um número único de identificação, seu nome e endereço,
além de ser assinado um contrato para uma determinada impressão que possui um número único 
de identificação, nome do responsável e valor contratado. Para a gráfica designada a
executar um serviço é informado o número de cópias pretendido e definida a data de entrega
da impressão. Algumas vezes, um mesmo livro pode ter suas cópias feitas por mais de uma
gráfica, pois o número de cópias requisitadas pode exceder a capacidade de produção de
uma gráfica.
Desenhe um diagrama EER para essa aplicação. Discuta todas as considerações feitas
por você, justificando suas escolhas para o projeto.
