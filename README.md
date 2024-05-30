# Projeto Limpeza e transformação de dados com power bi.

<h2>Passo a passo do projeto:</h2>

<h3>Processamento de Dados Simplificado com Power BI: </h3>


1.	Criação de uma instância na Azure para MySQL;
2.	Criar o Banco de dados com base disponível no github da professora;
3.	Integrar o bando de dados da que fiz na azure com o SGBD Workbench;
4.	Integração do Power BI com MySQL no Azure, ou seja, após fazer a integração do meu banco de dados da azure no workbench, após isso eu integrei com o power bi;
5.	Verificar problemas na base a fim de realizar a transformação dos dados;
  

<h3>Diretrizes para transformação dos dados:</h3>

1.	Análise  dos cabeçalhos e tipos de dados;
2.	Modifiquei os valores monetários para o tipo double;
3.	Verifiquei a existência dos nulos e analisei a remoção;
4.	Existiam employees com nulos em Super_ssn e foi anliasado que era um gerente e foi corrigido;
5.	Verifiquei se tinha algum departamento sem gerente;
6.	Separarei colunas complexas, como o endereço que estava tudo numa coluna só;
7.	Mesclei consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla teve como base a tabela employee;
8.	Neste processo eliminei as colunas desnecessárias;
9.	Realizei a mescla dos colaboradores e respectivos gerentes;
10.	Mesclei as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores, para esse caso usei o mesclar pois quero combinar os dados e não atribuir dados;
11.	Agrupei os dados a fim de saber quantos colaboradores existem por gerente e obtive a resposta que tenho 8 colaboradores e desses, 3 são gerentes.
    * Gerente 333445555 - Tem 3 colaboradores;
    * Gerente 987654321 = Tem 2 colaboradores;
    * Gerente 888665555 = Tem 2 colaboradores e é seu próprio gerente, fechando assim a conta de 8 colaboradores.
   
12.	Desenvolvido e analisado por Priscilla Albuquerque.
  
