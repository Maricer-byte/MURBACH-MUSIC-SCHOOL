# Projeto ERP – Escola de Música Murbach

## 1. Identificação da equipe

## 2. Caracterização da empresa
•	Escola de música.
•	Murbach Music School.
•	Educação e Ensino de Música. 
•	Serviços educacionais na área da música, focando em aulas práticas com aplicação imediata.
•	Pessoas interessadas no hobby ou profissionalização da Música.
•	⁠Administração, gerência, recepção e professores.

## 3. Justificativa da escolha
	A Murbach Music School foi selecionada para o projeto de modelagem de dados por apresentar uma estrutura operacional diversa, com demandas reais de gestão e alto potencial de otimização da informação, ela consiste em uma operação complexa envolvendo ciclo de matrículas, alocação de professores, agendamento de aulas individuais, gestão de ensaios de Prática de Banda e organização de eventos. Hoje, existe uma necessidade de gerenciar volumes simultâneos de agendas, frequências, histórico dos alunos, remuneração de professores e acervo de instrumentos/equipamentos, evitando choques e perda de dados. Há uma oportunidade clara de centralizar e automatizar dados — da captura de leads para aulas experimentais ao controle de caixa.

## 4. Problemas identificados
  Retrabalho na hora da contagem de aula, tendo que recriar as planilhas em mês a mês para fazer essa contagem. Tem que refazer a planilha cantina de mês a mês. Todas as planilhas devem ser refeitas e contadas novamente cada mês.
•	Informações de usuários havendo cadastro igual em diferentes planilhas.
•	Tudo é feito manual, há grande probabilidade de perda de informações.
•	Todos os processos são feitos por planilhas e sem automação.
•	Sistema de chamada de aluno, de cantina, administração feitas manualmente.
•	Sim, é precisamos passar para os professores a contagem das aulas no mês e agenda, se o aluno veio ou se não veio, o conteúdo passado na sala, pagamento foi feito ou não, se os professores vieram.
•	Encontrar folhas para pegar informações manualmente ocasionando em perdas de dados.

## 5. Processos de negócio

...

## 6. Requisitos funcionais
   5.1 Requisitos funcionas do setor Financeiro:
•	RF01 Sistema deverá cadastrar as contas a pagar.
•	RF02 Sistema deverá cadastrar as contas a receber, que consta a receita bruta e líquida.
•	RF03 Sistema deverá armazenar dados de Fornecedores.
•	RF04 Sistema deverá histórico das matrículas
•	RF05 Sistema deverá conter os status das transações pendentes 
•	RF06 Sistema deverá ser capaz de aceitar várias formas de pagamento.
•	RF07 sistema deverá mostrar o lucro recebido por aquele mês.

5.2	Requisitos funcionais do setor Aluno:
•	RF01 – Sistema deve cadastrar alunos (nome, CPF, data de nascimento, telefone, e-mail e endereço).
•	RF02 – Sistema deve permitir a matrícula do aluno em uma turma.
•	RF03 – Sistema deve registrar o histórico de matrículas do aluno.
•	RF04 – Sistema deve permitir que um aluno pratique vários instrumentos (relação N:N)
•	RF05 – Sistema deve armazenar a data de início, status e valor de cada instrumento praticado pelo aluno.
•	RF06 – Sistema deve permitir o cancelamento ou trancamento de matrícula.
•	RF07 – Sistema deve listar os alunos matriculados por turma e por instrumento.
•	RF08 – Sistema deve gerar cobrança automática quando o aluno iniciar um novo instrumento.


5.3	Requisitos funcionais do setor Professor:
•	RF01	O sistema deve permitir cadastrar um novo professor.
•	RF02	O sistema deve permitir consultar os dados já cadastrados de um professor.
•	RF03	O sistema deve permitir alterar os dados de um professor.
•	RF04	O sistema deve permitir desligar um professor.
•	RF05	O sistema deve permitir consultar os cursos dados por cada professor.
•	RF06	O sistema deve permitir associar um professor a um ou mais instrumentos musicais.
•	RF07 O sistema deve permitir consultar os instrumentos que um professor pode ensinar.
•	RF08	O sistema deve permitir registrar a formação acadêmica e profissional do professor.
•	RF09	O sistema deve permitir registrar a data de contratação do professor.
•	RF10	O sistema deve permitir registrar a carga horária do professor.
•	RF11	O sistema deve permitir registrar o valor da hora do professor.
•	RF12	O sistema deve permitir cadastrar a disponibilidade de horários do professor.
•	RF13	O sistema deve permitir consultar o histórico de cursos dados pelo professor.

5.4	Requisitos funcionais do setor RH:
•	RF1: sistema deve registrar quando o funcionário bater o ponto
•	RF2: sistema deve mostrar, se o funcionário tem horas extras ou está devendo.
•	RF3: sistema precisa receber o atestado e validar, verificar se é legítimo com CRM, e Cid médico corretos.
•	RF4: sistema deve pegar o funcionário até o quinto dia útil com o salário correto que está no contrato.
•	RF5: sistema deve avisar se estiver alguma documentação errada de algum funcionário.

## 7. Requisitos não funcionais
   6.1 Requisitos não funcionais do setor Financeiro:
•	RNF01 As trocas de informações devem ser rápidas.
•	RNF02 Precisa que haja criptografia na hora do pagamento da matrícula.

6.2	Requisitos não funcionais do setor Aluno:
•	RNF01 o sistema deve possuir disponibilidade. 
•	RNF02 o sistema deve apresentar bom desempenho.
•	RNF03 o sistema deve realizar validação de dados.
•	RNF04 Os dados pessoais do aluno (CPF, endereço, telefone) devem ser armazenados com criptografia.
•	RNF05 O sistema deve garantir integridade referencial entre Aluno, Matrícula, Turma e Instrumento.
•	RNF06 A interface de cadastro de aluno deve ser simples e intuitiva para uso por secretaria.
•	RNF07 O histórico de matrículas e instrumentos praticados deve ser mantido por no mínimo 5 anos.

6.3	Requisitos não funcionais do setor Professor:
•	RNF01 Somente usuários autorizados devem poder cadastrar, alterar ou desligar professores.
•	RNF02 O sistema deve garantir segurança dos dados cadastrados dos professores.
•	RNF03 O sistema deve impedir o cadastro de dois professores utilizando o mesmo CPF.
•	RNF04 O sistema deve manter o histórico das informações relevantes do professor, evitando perda de dados.
•	RNF05 O sistema deve possuir uma interface simples para facilitar o cadastro e a consulta dos professores.
•	RNF06 O sistema deve realizar validações nos dados inseridos para evitar informações inválidas ou incompletas.

6.4	Requisitos não funcionais do setor RH:
•	RNF01: O RH não está à disposição de qualquer funcionário apenas gestores.
•	RFN02: o funcionário não pode esquecer de bater o ponto, caso contrário será descontado.
•	RNF03: sistema não pode atrasar o pagamento de nenhum funcionário.

## 8. Regras de negócio

8. •	Matrícula e Cobrança: A mensalidade é fixa, pré-paga e cobrada em dia específico independentemente do número de semanas no mês, exigindo taxa inicial de adesão para reserva de vaga e gerando bloqueio de agendamento em caso de atraso superior a 10 dias.
•	Faltas e Reposições: O cancelamento de aula por parte do aluno exige aviso prévio de no mínimo 3 horas para gerar direito a reposição, com limite máximo de 2 reposições por semestre com validade de 30 dias; cancelamentos pelo professor geram reposição obrigatória ou crédito na mensalidade seguinte, enquanto feriados oficiais do calendário não geram desconto ou reposição.
•	Uso de Estrutura e Instrumentos: A escola fornece instrumentos fixos de grande porte (piano, bateria), médio e baixo porte (cordas) para as aulas.
•	Gestão de Professores e Cancelamento: A remuneração docente ocorre por hora/aula ministrada com cláusula de não concorrência direta com alunos da instituição, e o encerramento do contrato de matrícula exige solicitação prévia formal de 30 dias.
•	Controle de Agendamento: O sistema deve validar e confirmar automaticamente a reserva do horário do aluno no ato da matrícula ou remarcação, impedindo a existência de aulas ativas sem sala ou horário atribuídos na grade.
•	Remuneração Docente: O fechamento da folha do professor deve ser conciliado com o diário de classe confirmado, impedindo o pagamento duplicado de uma mesma aula ou a omissão do repasse de aulas efetivamente ministradas.
•	Notificação de Horários: A grade de aulas do professor deve ser enviada e atualizada de forma automática com antecedência mínima, sendo obrigatório o envio de alertas operacionais para garantir a entrada no horário correto.
•	Zelo por Equipamentos: Qualquer dano, avaria ou mau funcionamento de instrumentos e equipamentos da escola deve ser notificado imediatamente à administração no momento da ocorrência para registro e manutenção.
•	Liberação de Acesso: O início das atividades acadêmicas do aluno é condicionado à assinatura prévia do contrato e à confirmação do pagamento da taxa de matrícula e primeira mensalidade.

## 9. Restrições e políticas organizacionais
  Quem pode aprovar uma operação ou transação? 
Apenas o Coordenador pode aprovar uma operação ou transação

•	Quem pode alterar os registros de cadastro? 
As alterações nos registros de cadastro devem ser feitas apenas pelo gestor. 

•	Poderia haver desconto na empresa? 
Não é permitido a liberação de descontos na empresa, exceto na taxa de matrícula, visto que, pode haver um desconto de 25% na realização de matrículas. 

•	Quais são os pagamentos aceitos para matrícula? 
Para a matrícula são aceitos todo tipo de pagamento. 

•	Como funciona o cancelamento da matrícula da empresa? 
Aviso prévio de 30 dias para acontecer o reembolso, se avisar em cima do vencimento deve pagar a próxima mensalidade. E caso acabe o plano e não ocorrer renovação, não há penalidade.

•	Como funciona a manutenção dos instrumentos da escola? 
Cabe ao Coordenador realizar a manutenção dos instrumentos, porém o piano tem uma terceirização, essa manutenção só acontece se houver uma reclamação do instrumento.

•	Quem tem acesso a maioria das informações da empresa? A maioria das informações da empresa são de acesso limitado ao setor da Gerência e coordenação.

## 10. Fluxogramas

Os fluxogramas representam os principais processos do projeto.

![Fluxograma](FLUXOGRAMA.jpeg)

## 11. Entidades

As principais entidades identificadas no projeto são:

- Pessoa
- Fornecedor
- Despesa
- Movimento Financeiro
- Receita
- Matrícula
- Curso
- Instrumento
- Aluno_Instrumento
- Aluno
- Turma
- Professor
- Disciplina
- Disciplina_Professor
- Funcionário
- Folha de Pagamento
- Registro Ponto
- Dependente
- Benefício
- Cargo
- Telefone
- E-mail
- Endereço

- ## 12. Atributos

### Pessoa
- CPF
- Nome
- Data de nascimento
- Telefone
- E-mail
- Endereço

### Aluno
- ID Aluno
- Nome
- CPF
- Data de nascimento
- Telefone
- E-mail
- Endereço
- Status

- ## 13. Relacionamentos

Os principais relacionamentos identificados foram:

- Pessoa — Mora — Endereço
- Pessoa — Tem — E-mail
- Pessoa — Possui — Telefone
- Pessoa — É — Aluno
- Pessoa — É — Funcionário
- Pessoa — É — Fornecedor
- Aluno — Participa — Turma
- Turma — Possui — Curso
- Disciplina — Pertence — Curso
- Curso — Contém — Instrumento
- Aluno — Tem — Professor
- Funcionário — Coloca — Dependente
- Funcionário — Recebe — Benefício
- Funcionário — Ocupa — Cargo
- Funcionário — Registra — Registro_Ponto
- Fornecedor — Gera — Despesa
- Matrícula — Gera — Receita

- ## 14. Cardinalidades

- Pessoa 1:N Endereço
- Pessoa 1:N E-mail
- Pessoa 1:N Telefone
- Pessoa 1:1 Aluno
- Pessoa 1:1 Funcionário
- Pessoa 1:1 Fornecedor
- Funcionário 1:N Registro_Ponto
- Funcionário 1:N Benefício
- Fornecedor 1:N Despesa
- Matrícula 1:N Receita

- ## 15. Dicionário de dados conceitual

O dicionário de dados apresenta as entidades, seus atributos,
descrições e regras/observações.

### Pessoa

| Atributo | Descrição | Regra/Observação |
|---|---|---|
| CPF | Cadastro da pessoa | Obrigatório e único |
| Nome | Nome completo | Obrigatório |
| Data_nascimento | Data de nascimento | Obrigatório |

## 16. DER

O Diagrama Entidade-Relacionamento representa graficamente
as entidades, atributos, relacionamentos e cardinalidades
do projeto.

![Diagrama Entidade-Relacionamento](DER.jpeg)

## 17. Justificativas técnicas

As principais decisões de modelagem foram definidas com base
nas regras de negócio e na necessidade de organizar os dados
da escola de música.

## 18. Conclusão

O projeto de modelagem de banco de dados da Murbach Music School
permitiu identificar os principais processos, requisitos, regras
de negócio, entidades e relacionamentos da instituição.

A modelagem busca organizar as informações da escola, reduzindo
a dependência de controles manuais e facilitando o gerenciamento
de alunos, professores, funcionários, matrículas e informações
financeiras.
