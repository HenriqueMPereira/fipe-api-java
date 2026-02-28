# 🚗 Consulta de Veículos - API Tabela FIPE

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/apache_maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

Aplicação desenvolvida em **Java** para consultar e exibir dados de veículos (marcas, modelos, anos e preços) consumindo a API pública da Tabela FIPE. 

Este projeto foi construído para aplicar na prática conceitos de back-end, requisições HTTP e manipulação de dados utilizando recursos modernos da linguagem.

## 🛠️ Tecnologias e Ferramentas

* **Java**
* **Maven:** Gerenciamento de dependências.
* **Jackson (`com.fasterxml.jackson`):** Desserialização dos dados em formato JSON retornados pela API para objetos Java.
* **API Pública:** Integração com a API de consulta da Tabela FIPE.

## 🧠 Conceitos Aplicados

Durante o desenvolvimento deste projeto, foram colocados em prática os seguintes fundamentos e técnicas:

* **Programação Orientada a Objetos (POO):** Modelagem das classes e Records para representar os retornos da API.
* **Consumo de APIs REST (HTTP):** Criação de requisições para buscar dados externos baseados na interação do usuário.
* **Desserialização JSON:** Mapeamento e transformação de textos JSON em instâncias de classes Java.
* **Manipulação de Coleções:** Uso de **Stream API** e **Expressões Lambda** para filtrar, transformar, ordenar e exibir os dados recebidos de forma limpa e declarativa.

## ⚙️ Como Executar o Projeto

### Pré-requisitos
Para rodar este projeto, você precisará ter instalado em sua máquina:
* **Java 11** (ou versão superior).
* **Git** (para clonar o repositório).

### Passo a Passo

**1. Clone o repositório:**
Abra o seu terminal e rode o comando abaixo:
```bash
git clone [https://github.com/HenriqueMPereira/fipe-api-java.git](https://github.com/HenriqueMPereira/fipe-api-java.git)
