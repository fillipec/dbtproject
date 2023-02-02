# Projeto DBT (data build tool)

O atual projeto permitiu orquestrar todo o fluxo de trabalho, criar modelos compilando SQL, controlar versão (git hub) e documentar os modelos.

Utilizei o conjunto de dados Northwind, disponibizado pela A Microsoft. "Northwind" é o nome de uma empresa fictícia utilizada com o objetivo de estudo e treinamento.

Segue o diagrama de Entidade-Relacionamento:

![image](https://user-images.githubusercontent.com/16392877/216207393-b50aa9d2-8dd7-4acb-b9dc-61ced583eccd.png)
fonte: https://en.wikiversity.org/wiki/Database_Examples/Northwind

Qual o objetivo de ter feito esse projeto?

  1 - Utilizar o Redshift, a mais importante ferramenta de Datawarehouse (AWS);
  2 - Criar um modelo de transformação para remover duplicados;
  3 - Criar um modelo com campos cálculados;
  4 - Desnormalizar tabelas, criando uma tabela Fato;
  5 - Criar modelos de particionamento de dados;
  6 - Criar testes unitários no projeto;
  7 - Criar hooks, que são funções que são executadas antes ou depois da criação de um modelo;
  8 - Produzir documentação do projeto.

Segue o diagrama da primeira versão do projeto:
![image](https://user-images.githubusercontent.com/16392877/216202394-4493c7c5-d00d-4e6a-b859-ada02e6f510f.png)

