# Descritivo

O projeto trata-se de uma ferramenta de processamento e análise de dados acadêmicos contidos na plataforma Lattes buscando um melhor motor de busca e indexação, assim como customizar os dados contidos na plataforma com informações fornecidas pela instituição.

Atualmente o projeto se encontra escrito na linguagem `python` e `php`, sendo distribuída em três repositórios independentes para suas camadas de processamento e com mais um repositório para a camada de apresentação e um repositório auxiliar para armazenamento de metadados e informações complementares.

Esses repositórios serão referidos como módulos conforme a seguinte organização:

- Coleta
- Armazenamento
- Processamento
- Busca
- Visualização

## Armazenamento

É o primeiro módulo a ser configurado, trata-se de um projeto escrito em `php` utilizando a biblioteca **Laravel**.
Este módulo contem as informações sobre cada currículos a ser coletado para uma dada instituição.

Ele ser preenchido de forma massiva, utilizando um arquivo no formato csv que é usando para popular o banco de dados.

## Coleta

Este módulo trata-se de uma interface de programação que busca facilitar o uso da `API` fornecida pelo CNPQ, dando ao usuário um método de coleta e armazenamento para os currículos no formato `xml`.

O módulo de coleta se comunica com o módulo de armazenamento, através de requisições `http`, para obter informações sobre cada currículos a ser coletado.

A primeira requisição a ser realizada obtém todos os identificadores que serão utilizados para a realização da coleta. Seguindo essa requisição.

## Processamento

Criação de índice de busca
Criação de arquivos `json` de usados na visualização

## Busca

Descritivo

## Visualização

Descritivo

<!-- # Diagrama de Requisitos -->
<!--  -->
<!-- # Tabela de Requisitos -->
<!-- # Casos de uso -->
<!-- # Entidade Relacionamento -->
<!-- # CRUD -->
<!-- # Diagrama de Classes -->
