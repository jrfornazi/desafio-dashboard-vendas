# 📊 Dashboard de Vendas - Estúdio Fotográfico

## 🎯 Objetivo do Projeto
Este projeto foi desenvolvido como parte de um desafio de dados focado em organização e visualização. O objetivo principal é transformar dados brutos de vendas em informações visuais claras e úteis, permitindo uma análise eficaz do desempenho e suporte à tomada de decisões estratégicas.

O cenário prático escolhido foi o gerenciamento financeiro de um estúdio de fotografia, analisando o faturamento de serviços prestados nas regiões de Mimoso do Sul e Alegre.

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Python (Pandas):** Utilizado para a etapa de Engenharia de Dados (ETL). Um script foi criado no Google Colab para estruturar a base de dados, calcular automaticamente o Lucro Líquido e exportar os agrupamentos de dados.
* **Microsoft Excel:** Utilizado para a estruturação das Tabelas Dinâmicas finais e para o design do painel visual (Dashboard).

## 📈 Principais Insights do Dashboard
O painel foi estruturado para responder a três perguntas cruciais de negócio de forma imediata:
1.  **Desempenho Regional:** Comparativo de faturamento bruto por cidade de atuação.
2.  **Top Serviços:** Identificação de quais tipos de pacotes fotográficos (ex: Eventos Corporativos, Ensaios, Newborn) geram o maior volume de vendas.
3.  **Conversão por Canal:** Análise da origem dos clientes (Instagram, Google, Indicação) para entender onde o esforço de marketing traz mais retorno.

## 📂 Estrutura dos Dados
A base de dados (`.xlsx`) está organizada da seguinte forma:
* Aba **Dashboard**: O painel visual limpo para o usuário final.
* Abas de **Resumo**: Contêm as agregações matemáticas que alimentam os gráficos.
* Aba **Base de Dados**: Contém os registros com as colunas: `Data`, `Cliente`, `Serviço`, `Cidade`, `Valor Bruto`, `Custo Fixo`, `Canal de Venda` e `Lucro`.

## 🚀 Como Reproduzir e Utilizar
1.  Faça o clone deste repositório ou baixe o arquivo `Dashboard_Estudio_jrfornazi.xlsx` diretamente.
2.  Abra o arquivo no Microsoft Excel.
3.  Navegue até a aba **Dashboard** para visualizar o painel gerencial.

---
*Projeto desenvolvido para o desafio de visualização de dados.*
