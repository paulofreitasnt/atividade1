# Atividade 1 — Exemplo didático de modelagem em grafo

Este repositório contém uma atividade (exemplo didático) de modelagem de dados em banco de grafos. O objetivo é demonstrar, de forma simples, como representar filmes, séries e suas relações (diretores, atores, gêneros, avaliações) usando Cypher/Neo4j.

Aviso importante: este projeto é uma atividade de estudo e exemplo didático — não é uma aplicação de produção.

## Conteúdo do repositório
- README.md — este arquivo.
- cypher.txt — arquivo com os comandos Cypher usados para criar os nós e relacionamentos (importar no Neo4j Browser).
  - URL: https://github.com/paulofreitasnt/atividade1/blob/main/cypher.txt
- visualisation.png — imagem que apresenta o schema do banco (diagrama/visualização do grafo).
  - URL: https://github.com/paulofreitasnt/atividade1/blob/main/visualisation.png

A imagem do schema também está incluída neste README abaixo:

![Schema do banco](https://github.com/paulofreitasnt/atividade1/blob/main/visualisation.png)

## Fonte dos dados
As informações de filmes e séries (títulos e avaliações) foram obtidas do site IMDb — correspondem aos cinco melhores avaliados (top 5) considerados na data da criação desta atividade. Use esses dados apenas para fins educacionais e de aprendizagem.

## Como usar / executar
1. Instale o Neo4j (Neo4j Desktop, Neo4j Aura ou outra distribuição compatível).
2. Crie ou selecione um database (padrão) e abra o Neo4j Browser (ou a interface de sua escolha).
3. Abra o arquivo `cypher.txt` e copie os comandos Cypher.
4. Cole e execute os comandos no Neo4j Browser. Os comandos criarão nós (Movie, Series, Person, Genre, etc.) e relacionamentos entre eles.
5. Após a execução, use a visualização gráfica do Neo4j Browser para explorar o grafo. A imagem `visualisation.png` mostra o esquema/resultados esperados.

Dica: execute os blocos de comandos do `cypher.txt` em ordem para evitar problemas de referência entre nós.

## Objetivos pedagógicos
- Demonstrar modelagem de um domínio (entretenimento) em grafo.
- Praticar criação de nós, propriedades e relacionamentos em Cypher.
- Visualizar como entidades se conectam (atores, diretores, gêneros, avaliações).