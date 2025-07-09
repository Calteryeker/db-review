# Construindo um Esquema Conceitual para Banco De dados
Arquivos com o esquema de uma banco de dados de uma oficina

## Objetivo:
Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

## Narrativa:
. Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
. Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
. Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
. A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
. O valor de cada peça também irá compor a OS.
. O cliente autoriza a execução dos serviços
. A mesma equipe avalia e executa os serviços
. Os mecânicos possuem código, nome, endereço e especialidade
. Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

![alt text](https://github.com/Calteryeker/db-review/blob/main/Construindo%20um%20Esquema%20Conceitual%20para%20Banco%20De%20dados/oficina_1.png)