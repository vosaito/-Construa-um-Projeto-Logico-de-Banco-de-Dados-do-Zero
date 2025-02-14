# Projeto Oficina - Construa um Projeto Lógico de Banco de Dados do Zero

 Realização do desafio proposto pela instrutora Juliana da Digital Innovation One.  
 Foi feito um sistema de banco de dados para um serviço de cadastro de clientes/serviços de um oficina.

 ### 

### Escopo do Projeto
Objetivo  
* Criar/aprimorar o esquema conceitual para o contexto de Oficina;
* Criar uma banco de dados a partir do esquema desenvolvido;
* Persistir dados para testes do banco de dados;
* Elaborar queries para consulta/insights a partir de dados fictícios.  
\
Diretrizes para elaboração das queries
- Recuperações simples com SELECT Statement;
- Filtros com WHERE Statement;
- Crie expressões para gerar atributos derivados;
- Defina ordenações dos dados com ORDER BY;
- Condições de filtros aos grupos – HAVING Statement;
- Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados;
- Não há um mínimo de queries a serem realizadas;
- Os tópicos supracitados devem estar presentes nas queries;
- Elabore perguntas que podem ser respondidas pelas consultas;
- As cláusulas podem estar presentes em mais de uma query.

### Desafio Realizado
Os principais pontos feitos para a criação do esquema conceitual do sistema para oficina foram:
* Criação de entidades "Orçamento" e "Ordem de serviço para separação dos serviços realizados e orçados aprovados ou não (no caso de querer arquivar todos os orçamentos);
* Criação de duas entidades para cadastro de peças e serviços para diferentes itens e valores de ambas;
* Criação de entidade para "veículos" para cadastros de diversos carros por cliente. Cada cliente pode ter um ou mais carros.

Queries elaboradas para consulta ao banco de dados
* Relação de carros já arrumados
* Relação de serviços de manutenção para cada orçamento
* Relação dos clientes que solicitaram o orçamento e como está o status
* Relação de mecânicos responsáveis e quantas horas de trabalho para cada serviço de cada orçamento
* Lista de peças utilizadas em cada orçamento e as quantidades de cada peça
* Valor total de cada Orçamento (Peças+Mão de obra)
* Orçamentos com valores totais maiores de 3000 reais
* Quantidade de vezes cada serviço foi orçado
