# 🏋️ Análise de Gestão de Academia — Projeto SQL
*SQL • MySQL • Análise de Dados*

![Header](Imagens/header.png)

Este projeto simula a gestão operacional e financeira de uma academia, utilizando SQL para explorar dados e gerar insights estratégicos. Foram desenvolvidas **23 consultas analíticas**, abrangendo evolução financeira, perfil dos alunos, padrões de utilização, vendas de produtos e distribuição de recursos.

Todos os dados são fictícios e foram criados exclusivamente para fins de estudo e portfólio.

---

## 🧠 Principais Habilidades

* SQL para análise de dados
* Joins, CTEs e funções de janela
* Modelagem relacional
* Desenvolvimento de KPIs
* Análise exploratória de dados
* Storytelling com dados
* Interpretação de indicadores de negócio

---

## 📂 Estrutura da Base de Dados

O projeto é composto pelas seguintes tabelas:

* **alunos**: informações cadastrais e situação dos alunos;
* **planos**: tipos de planos e valores;
* **pagamentos**: histórico de pagamentos e formas de pagamento;
* **modalidades**: atividades oferecidas pela academia;
* **frequencia**: registros de presença dos alunos;
* **produtos**: suplementos, acessórios e vestuário;
* **vendas_produtos**: vendas realizadas na loja da academia;
* **professores**: dados dos profissionais e salários;
* **professor_modalidade**: associação entre professores e modalidades;
* **despesas** e **pagamentos_despesas**: custos operacionais da academia.

---

## 📊 Principais Análises Desenvolvidas

### 📈 Evolução do Negócio

* Evolução anual dos custos;
* Evolução anual das receitas;
* Crescimento das matrículas;
* Receita acumulada por ano;
* Custos acumulados por ano;
* Evolução das vendas de produtos.

### 👥 Perfil e Comportamento dos Alunos

* Perfil predominante dos frequentadores;
* Comparação por faixa etária;
* Distribuição geográfica dos alunos;
* Ticket médio por aluno;
* Ticket médio por bairro.

### 🏋️ Padrões de Utilização

* Horários de maior movimento;
* Dias da semana mais movimentados;
* Modalidades mais praticadas;
* Ticket médio por modalidade;
* Produtos mais vendidos.

### 💰 Indicadores Financeiros e Estratégicos

* Comparação entre receitas e despesas;
* Professores com maiores salários;
* Distribuição dos alunos por plano;
* Participação da receita por plano;
* Métodos de pagamento mais utilizados;
* Professores responsáveis por múltiplas modalidades.

---

## 🛠 Ferramentas Utilizadas

* MySQL
* SQL
* MySQL Workbench

---

## 📁 Estrutura do Projeto

```
1 - Evolução do Negócio
2 - Perfil dos Alunos
3 - Padrões de Utilização
4 - Indicadores Financeiros e Estratégicos
5 - Base de Dados
README.md
```

---

## 🚀 Como Utilizar

1. Clone este repositório;
2. Importe as tabelas da base de dados em seu SGBD;
3. Execute as consultas SQL disponíveis;
4. Explore os indicadores e adapte as análises conforme necessário.

---

## 📌 Observações

A base de dados foi inteiramente gerada para fins educacionais e não representa pessoas ou empresas reais.

As consultas utilizam recursos como:

* CTEs (`WITH`);
* Funções de janela;
* Funções de data;
* Agregações e subconsultas;
* Joins entre múltiplas tabelas.

---

⭐ Projeto desenvolvido para fins de estudo e composição de portfólio em Análise de Dados.
