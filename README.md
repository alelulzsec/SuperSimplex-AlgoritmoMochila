# SuperSimplex-AlgoritmoMochila

Repositório para a implementação do algoritmo Simplex e Mochila.

Projeto de Pesquisa Operacional
5º Semestre BCC UNIVEM

Integrantes:

  Alexandre Junior

  Caio Henrique

  Gabriel Geraldino 
  

O Simplex permite que se encontre valores ideais em situações em que diversos aspectos precisam ser respeitados. Diante de um problema, são estabelecidas inequações que representam restrições para as variáveis. A partir daí, testa-se possibilidades de maneira a otimizar, isto é, maximizar ou minimizar o resultado da forma mais rápida possível.

O algoritmo da mochila consiste em preencher a mochila com objetos diferentes de pesos e valores. O objetivo é que preencha a mochila com o maior valor possível, não ultrapassando o peso máximo.


## Ferramentas

- Javascript
- JQuery
- Html5
- Css3
- GitHub para hospedagem e versionamento

## Nota de realease a ser publicado

###Simplex

- Algoritmo Simplex para problemas de maximização.
- Algoritmo Simplex para problemas de minimização.
- É exibido o passo a passo das tabelas geradas pelo método Simplex
- Tabela de Sensibilidade.

###Mochila

- Apresentação da solução, dos itens a serem considerados e a tabela de cálculo.

##Entradas personalizadas para:

###Simplex

- Limite máximo de iterações
- Tipo de Simplex (MAX ou MIN)
- Quantidade de variáveis e restrições

###Mochila
- Capacidade da mochila
- Peso e valor dos itens


###Simplex

- Em cada variável da função objetivo e das restrições deve conter apenas o número, sem a adição do 'x', separando os números por ';' e caso tenha alguma variável nula, é necessário inserir o 0.


###Mochila

- Não utilizar itens com pesos iguais
- Serão permitidos somente valores inteiros


##Datas Importantes

###Simplex

Datas | Eventos
--------- | ------
30/03/16    | Início do Planejamento
31/03/16    | Criação da Estrutura Principal
02/04/16    | Criação do Cabeçalho da Matriz Principal
03/04/16    | Cálculo
03/04/16    | Geração da Matriz Principal
05/04/16    | Criação das Funções de Parada
16/04/16    | Inserindo o Minimizar
20/04/16    | Criação do Layout
20/04/16    | Inserindo a Análise de Sensibilidade
20/04/16    | Alterações no Readme
23/04/16    | Estruturação da Função Objetivo
23/04/16    | Arrumando a função Minimizar
29/04/16    | Readme modificado
01/05/16    | Limpar tela
01/05/16    | Alteração no campo de restrições
01/05/16    | Tabela de Sensibilidade
01/05/16    | Criando o passo a passo
01/05/16    | Ajustes nos inputs das restrições
15/06/16    | Arrumando link do simplex
15/06/16    | Ajustando tabelas simplex
15/06/16    | Análise de sensibilidade
15/06/16    | Atualizando README


###Mochila

Datas | Eventos
--------- | ------
05/06/16    | Início do Planejamento
06/06/16    | Inserindo inputs
06/06/16    | Inserindo o paralax
07/06/16    | Finalização do projeto da mochila
08/06/16    | Atualizando o Read Me
14/06/16    | Refatoração do layout da Mochila e index
15/06/16    | Atualizando README

##Compatibilidade

Requisitos | Ferramentas
--------- | ------
Navegadores     | Mozila Firefox, Chrome, Internet Explorer
Sistema Operacional    | Ubuntu, Windows, Mac

##Tecnologias

Tecnologias | Ferramentas
--------- | ------
Front-End     | HTML, Javascript, JQuery
Back-End    | Javascript
Framework WEB    | Materialize
Editor de Texto  | Visual Studio Code e Sublime Text 3
Design pattern  |
Servidor Web    | https://github.io/alelulzsec

##Atividades Realizadas no Período

###Simplex

Código | Título | Tarefa | Situação | Observação
--------- | ------ | -------| -------| -------
1 | Maximizar | Montar a Tabela Simplex, e possibilitar o usuário a maximizar modelos de simplex com sistemas lineares. | Concluído | Apenas restrições de “<=”
2 | Minimizar | Montar a Tabela Simplex, e possibilitar o usuário a minimizar modelos de simplex com sistemas lineares. | Concluído | Apenas restrições de “<=”
3 | Adição de restrições | Possibilitar o usuário a adicionar inputs para maiores números de restrições. | Concluído |
4 | Remoção de restrições | Possibilitar o usuário a remover inputs para menores números de restrições. | Concluído |
5 | Demonstrar passo a passo | Demonstrar ao usuário as alterações na tabela causada pelas iterações do método simplex. | Concluído|
6  | Tabela de sensibilidade | Demonstrar ao usuário a tabela de sensibilidade. |Concluído|

###Mochila

Código | Título | Tarefa | Situação | Observação
--------- | ------ | -------| -------| -------
1 | Tabela de solução | Demonstrar ao usuário as etapas do algortimo | Concluído |
2 | Solução do problema | Mostrar ao usuário os itens selecionados pelo algoritmo como qualificados | Concluído |
