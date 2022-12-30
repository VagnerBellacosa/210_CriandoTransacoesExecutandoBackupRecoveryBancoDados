# 210_CriandoTransacoesExecutandoBackupRecoveryBancoDados
Criando Transações, Executando Backup e Recovery de Banco de Dados



[**](https://web.dio.me/track/formacao-sql-db-specialist)

##### Criando Transações, Executando Backup e Recovery de Banco de Dados

**

[**](https://web.dio.me/lab/criando-transacoes-executando-backup-e-recovery-de-banco-de-dados/learning/792d0ce7-f189-4e90-a191-eaa8f3f5c8d9)[**](https://web.dio.me/lab/criando-transacoes-executando-backup-e-recovery-de-banco-de-dados/learning/3bdbf4c1-d4b5-45a8-90f8-aad880409878)

<iframe id="ytc68" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" title="Criando Transações, Executando Backup e Recovery de Banco de Dados" width="100%" height="100%" src="https://www.youtube.com/embed/i55W8Kq3hFw?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-12="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



02:11

 

07:14







normal

auto

- CONTEÚDOS
- INFORMAÇÕES

- [Criando Transações, Executando Backup e Recovery de Banco de Dados](https://web.dio.me/lab/criando-transacoes-executando-backup-e-recovery-de-banco-de-dados/learning/792d0ce7-f189-4e90-a191-eaa8f3f5c8d9)
- [Entendendo o Desafio](https://web.dio.me/lab/criando-transacoes-executando-backup-e-recovery-de-banco-de-dados/learning/3bdbf4c1-d4b5-45a8-90f8-aad880409878)



[**](https://web.dio.me/track/formacao-sql-db-specialist)

##### Criando Transações, Executando Backup e Recovery de Banco de Dados

**

[**](https://web.dio.me/lab/criando-transacoes-executando-backup-e-recovery-de-banco-de-dados/learning/792d0ce7-f189-4e90-a191-eaa8f3f5c8d9)[**](https://web.dio.me/lab/criando-transacoes-executando-backup-e-recovery-de-banco-de-dados/learning/undefined)

**PARTE 1 – TRANSAÇÕES** 

Objetivo:  

Neste desafio você irá lidar com transações para executar modificações na base de dados. Sendo assim, vamos relamenbrar como executar uma transação. Primeiramente, é preciso desabilitar o autocommit do MySQL. Caso contrário, cada instrução SQL executada será confirmada. 

CODE 1



Essa primeira transação pode ser executada sem utilizar outros recursos como procedures. Dessa forma, você irá executar statements de consultas e modificações de dados persistidos no banco de dados via transações.  

 

CODE 2



**PARTE 2 - TRANSAÇÃO COM PROCEDURE** 

Você deverá criar outra transação, contudo, esta será definida dentro de uma procedure. Neste caso, assim como no exemplo em aula, deverá haver uma verificação de erro. Essa verificação irá acarretar um ROLLBACK, total ou parcial (SAVEPOINT). 

CODE 3



**PARTE 3 – BACKUP E RECOVERY** 

Objetivo: 

Neste etapa do desafio, você irá executar o backup do banco de dados e-commerce. Realize o backup e recovery do banco de dados; 

- Utilize o mysqdump para realizar o backup e recovery do banco de dados e-commerce; 
- Realize o backup de diferentes bancos de dados e inseria os recursos como: procedures, eventos e outros. 
- Adicione o arquivo de backup ao github juntamente com o script; 

 

 

- CONTEÚDOS
- INFORMAÇÕES

[Criando Transações, Executando Backup e Recovery de Banco de Dados](https://web.dio.me/lab/criando-transacoes-executando-backup-e-recovery-de-banco-de-dados/learning/792d0ce7-f189-4e90-a191-eaa8f3f5c8d9)[Entendendo o Desafio](https://web.dio.me/lab/criando-transacoes-executando-backup-e-recovery-de-banco-de-dados/learning/3bdbf4c1-d4b5-45a8-90f8-aad880409878)



