# Análise de Dados de Vendas

## Descrição

Este projeto realiza uma análise descritiva de um dataset fictício de vendas, com o objetivo de extrair insights relevantes sobre produtos, clientes e canais de venda.

---

## Estrutura do Projeto

* `data/` → arquivo CSV com os dados de vendas
* `src/` → script principal de análise (`analise.py`)
* `outputs/` → arquivos gerados (opcional)
* `requirements.txt` → dependências do projeto

---

## Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/analise-vendas.git
cd analise-vendas
```

2. Crie e ative um ambiente virtual:

```bash
python -m venv venv
venv\Scripts\activate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute o script:

```bash
python src/analise.py
```

---

## Bibliotecas Utilizadas

* pandas → manipulação e análise de dados
* matplotlib / seaborn → visualização de dados

---

## 📊 Análises Realizadas

* Ranking de produtos mais vendidos
* Faturamento mensal
* Ticket médio por cliente
* Top produtos por faturamento
* Análise de canais de venda
* Identificação dos principais clientes

---

## Principais Insights

* O faturamento apresenta crescimento ao longo do ano, com leve queda nos últimos meses.
* Produtos de maior valor agregado (kits) lideram em faturamento.
* O canal de VAREJO concentra a maior parte das vendas.
* Há concentração de receita em poucos clientes, indicando possível dependência.

---

## Decisões Técnicas

* Utilização da biblioteca pandas pela sua eficiência na manipulação de dados tabulares.
* Conversão da coluna de datas para formato datetime para permitir análises temporais.
* Criação de coluna de mês para agregações.
* Consideração apenas de pedidos com status "FATURAMENTO" para garantir consistência dos dados.

---

## Melhorias Futuras

* Criação de dashboards interativos
* Automatização do pipeline de análise
* Inclusão de testes e validações de dados
