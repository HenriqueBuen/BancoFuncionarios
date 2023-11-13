Atividade de Banco de Dados SQL

Este repositório contém a solução para uma atividade prática envolvendo operações básicas em um banco de dados usando SQL. A atividade foi dividida em várias etapas, cada uma requerendo consultas ou atualizações específicas no banco de dados.
Estrutura do Banco de Dados

O banco de dados é projetado para representar uma empresa fictícia com diferentes departamentos, incluindo tecnologia, administração, finanças, transportes, inovações e uma tabela de informações familiares. Cada tabela reflete as relações entre funcionários, departamentos e regiões.
Como Foi Feito

Para cada etapa da atividade, foram utilizados comandos SQL específicos. Aqui está um resumo das principais operações:

    Inclusão de Informações Pessoais:
        Utilizou-se o comando INSERT para adicionar informações pessoais ao departamento de tecnologia.

    Contratação de Funcionários na Administração:
        Inserção de novos funcionários na tabela de administração usando INSERT.

    Estatísticas de Funcionários:
        Utilização de comandos SELECT para contar o número total de funcionários na empresa, determinar a quantidade no departamento de finanças e calcular a média salarial na tecnologia.

    Gastos com Salários no Departamento de Transportes:
        Utilização de SELECT e SUM para calcular o total gasto em salários no departamento de transportes.

    Criação do Departamento de Inovações:
        Inserção de um novo departamento, "Inovações", com INSERT INTO.

    Contratação de Funcionários na Inovação:
        Adição de três novos funcionários na tabela de inovações, cada um com suas informações específicas.

    Atualização Salarial na Inovação:
        Utilização de UPDATE para ajustar os salários dos novos funcionários com base na média salarial dos departamentos de administração e finanças.

    Informações Geográficas:
        Uso de SELECT e JOIN para obter uma lista de todas as regiões e seus países correspondentes.

    Relacionamentos Familiares:
        Utilização de SELECT para descobrir quem é o pai de Joe Sciarra, se Jose Manuel possui filhos e se Karen Partners tem um cônjuge.

    Atualização de Informações Pessoais:
        Uso de UPDATE para adicionar informações sobre o departamento na tabela de tecnologia.

Executando os Comandos

Para executar os comandos, certifique-se de ter um servidor MySQL em execução. Importe o script SQL fornecido neste repositório para criar o banco de dados e suas tabelas.
