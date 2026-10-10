# 🧹 Processamento e Transformação de Dados com Power BI e DAX

> **Desafio de Projeto** – Formação Power BI Analyst (DIO)  
> **Instrutora:** Juliana Mascarenhas  

---

## 🎯 Objetivo

Aplicar técnicas avançadas de **ETL (Extract, Transform, Load)** no Power Query e criar cálculos em **DAX** para sanar inconsistências, otimizar o modelo de dados e preparar a base para geração de relatórios analíticos.

---

## 🛠️ Etapas do Processo de Transformação

### 1. Limpeza e Validação de Dados (Power Query)
* **Tratamento de Nulos:** Remoção e substituição de registros nulos em colunas essenciais.
* **Ajuste de Tipagem:** Garantia de que cada campo utilize o tipo correto (Texto, Data, Número Inteiro ou Decimal fixo/moeda).
* **Tratamento de Textos:** Divisão de colunas (ex: separação de endereço/nome) e remoção de espaços em branco sobressalentes (*Trim/Clean*).

### 2. Mescla e Combinação de Consultas
* Junção de tabelas com base em chaves estrangeiras.
* Garantia de integridade referencial mantendo a cardinalidade correta (`1:N`).

### 3. Modificações em DAX
* Criação de colunas e medidas calculadas para complementar a análise e validar os totais transformados.

---

## 📁 Estrutura de Arquivos

* `Transformacao_Dados.pbix`: Arquivo do Power BI com todo o histórico de etapas aplicadas.
* `README.md`: Documentação das transformações.
