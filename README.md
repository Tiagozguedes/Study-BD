# escolaTech - OracleSql

Mini projeto de banco de dados para praticar comandos DDL e DML no Oracle.

## Estrutura

- `sql/ddl.sql`: cria tabelas, sequences, gatilhos e uma view de relatório para o cenário de uma escola de tecnologia.
- `sql/dml.sql`: insere dados de exemplo nas tabelas e ajusta informações derivadas (como vagas ocupadas).
- `sql/autorizacoes.txt`: orientações de privilégios mínimos que o usuário do Oracle precisa ter para executar os scripts.

## Como utilizar

1. Solicite a um DBA (ou utilize um usuário com privilégios administrativos) para garantir os acessos descritos em `sql/autorizacoes.txt`.
2. Crie ou escolha um usuário dedicado no Oracle (por exemplo, `STUDYBD`).
3. Execute o script `sql/ddl.sql` para criar toda a estrutura do banco.
4. Em seguida, execute `sql/dml.sql` para popular as tabelas com dados iniciais.
5. Utilize a view `vw_resumo_matriculas` para consultar um resumo das ofertas de cursos e matrículas.

Os scripts foram pensados para o SQL*Plus ou ferramentas compatíveis com o Oracle Database.
