# Avaliação Sprint 1
<p align="center"><img src = "https://live.staticflickr.com/1951/30234801997_86f8232201_b.jpg"></p>

## 🚀 SPACEX API - Dados dos foguetes
- Todos os dados serão capturados através da API da [SpaceX](https://www.spacex.com/);
- [GitHub da SpaceX](https://github.com/r-spacex/SpaceX-API) com a documentação;

## 🗒 Descrição do projeto
A ideia deste projeto é capturar os dados através de uma API da SpaceX, utilizando Python e OOP, inserir no banco MongoDB, e fazer uma consulta inteligente.

## 🛠 Tecnologias 
- Python3
- MongoDB
- API da SpaceX

## 📈 Fluxo de trabalho
- 1. Capturar os dados da API
- 2. Inserir no banco MongoDB
- 3. Visualizar esses dados no Python3

## 📁 Classes e funções
- **Database**:
-- configurar database - __init __(self, hostname, db)
-- criar collection - criarCollection(self, collection)
-- inserir um registro - inserirUmRegistro(self, query)
-- inserir vários registros - inserirVariosRegistros(self, query)
-- achar um registro - acharUm(self, query)
-- achar vários registros - acharVariosSemQuery(self)
- **API**:
-- configurar API - __init __(self)
-- retornar lista com informações da API - retornaLista(self, url)



## 📣 Disclaimer
- Não estarei utilizando a biblioteca SpaceX-Py para produzir os requests!

## 👨‍🚀 Autor

 <b>[João Victor Palhares Barbosa](https://github.com/vicpb)</b>
