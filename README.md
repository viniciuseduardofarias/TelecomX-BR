<h1 align="center">Análise Exploratória de Churn - Telecom X</h1>

<p align="center">
  <a href="https://github.com/viniciuseduardofarias/TelecomX-BR">
    <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/0*TMvhLMMOy0NHzNIy.gif" alt="Visão Geral do Projeto" />
  </a>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"></a>
  <a href="#"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"></a>
  <a href="#"><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"></a>
  <a href="#"><img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"></a>
  <a href="#"><img src="https://img.shields.io/badge/Seaborn-1A5276?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn"></a>
  <a href="https://www.linkedin.com/in/viniciuseduardofarias/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<h4 align="center">Projeto de Análise de Dados 📊</h4>

<h4 align="center">
  :white_check_mark: Concluído
</h4>

---

## Contextualização

A evasão de clientes, conhecida como *churn*, é um dos maiores desafios para empresas que trabalham com serviços recorrentes, impactando diretamente o faturamento e o custo operacional. Considerando que reter um cliente é muito mais barato do que conquistar um novo, entender os motivos que levam à desistência torna-se fundamental para direcionar estratégias eficazes.

Este projeto tem como propósito analisar os dados de churn da empresa Telecom X, explorando padrões e indicadores que auxiliem na antecipação da evasão e no planejamento de ações para aumentar a fidelização.

---

## Metodologia

O processo seguiu etapas essenciais para garantir qualidade e relevância dos resultados:

- **Coleta e Preparação dos Dados:** Extração dos dados via API, transformação do formato JSON para uma tabela estruturada, e limpeza para remoção de inconsistências e valores faltantes.
- **Engenharia de Atributos:** Criação de variáveis derivadas, como a média diária dos gastos, para melhor entendimento do comportamento financeiro dos clientes.
- **Análise Exploratória:** Uso de estatísticas descritivas e visualizações gráficas para identificar relações entre as variáveis e a evasão.
- **Correlação:** Avaliação estatística para detectar associações fortes entre características dos clientes e a probabilidade de cancelamento.

---

## Principais Descobertas

- Clientes com contratos mensais apresentam maior risco de churn, enquanto contratos anuais ou bienais tendem a promover maior fidelidade.
- A duração do contrato é um fator protetor: quanto mais tempo de vínculo, menor a chance de evasão.
- Formas de pagamento automatizadas, como cartão de crédito e débito em conta, estão associadas a menor churn em comparação a métodos manuais.
- Contas diárias com valores mais altos estão relacionadas a maior probabilidade de cancelamento, indicando sensibilidade a preços.
- A fibra óptica, apesar de popular, registra as maiores taxas de evasão, sinalizando a necessidade de atenção na qualidade ou condições do serviço.

---

## Recomendações para Negócio

- Incentivar a migração para planos de maior duração por meio de benefícios e descontos.
- Priorizar campanhas de retenção para clientes com menor tempo de contrato e alto custo diário.
- Revisar processos relacionados ao serviço de fibra óptica para identificar causas do churn elevado.
- Automatizar e facilitar métodos de pagamento para reduzir desistências por inadimplência ou dificuldades financeiras.

---

## Tecnologias e Bibliotecas Utilizadas

- Python  
- Pandas  
- Requests  
- JSON  
- NumPy  
- Matplotlib  
- Seaborn  

## Estrutura do Projeto

- `TelecomX_BR.ipynb`: Notebook com as etapas de extração, transformação, análise e relatório final.  
- `TelecomX_dicionario.md`: Dicionário de dados com a descrição das colunas do dataset.  
- `TelecomX_Data.json`: Dados brutos carregados diretamente da API.

## Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/viniciuseduardofarias/TelecomX-BR.git
```

2. Instale as dependências (recomendo usar um ambiente virtual):

```bash
pip install pandas requests numpy matplotlib seaborn
```

3. Execute o notebook TelecomX_BR.ipynb no Jupyter Notebook ou Google Colab.

## Autor

Vinicius Eduardo Farias Silva  
[LinkedIn](https://www.linkedin.com/in/vinicius-eduardo-farmacia/)




