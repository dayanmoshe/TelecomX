#TelecomX

#  Análise de Churn de Clientes

Bem-vindo ao repositório do projeto **Churn de Clientes da Telecom X**! Este projeto visa analisar o fenômeno de evasão de clientes (churn) em uma empresa de telecomunicações, através de técnicas de ETL e Análise Exploratória de Dados (EDA) utilizando Python.

---

## 🏆 Propósito da Análise

A Telecom X enfrenta um alto índice de perda de clientes e precisa entender os motivos dessa evasão para criar estratégias de retenção mais eficazes. A análise tem como objetivos:

- **Identificar padrões e causas principais do churn**
- **Explorar características dos clientes propensos à evasão**
- **Fornecer insights e recomendações para reduzir a evasão**

---

## 📂 Estrutura do Projeto

```plaintext
/

│── TelecomX_BR.ipynb  # Notebook principal da análise
|── telefom_churn_model.csv  #base de modelo preditivo
|── TelecomX_dicionario # definicoes de cada coluna da base
|── TelecomX_Data.json
└── README.md                # Este arquivo
/
````
Principais Insights Gerais:

Contratos mensais e fatura eletrônica aumentam o risco de churn.
Clientes sem serviços adicionais (proteção, backup, suporte técnico) têm maior evasão.
Sugere-se estimular upgrades de contrato e promover combos de serviços premium.

⚙️ Instruções para Executar o Notebook

1. Clone este repositório:
  git clone https://github.com/dayanmoshe/TelecomX.git
  cd TelecomX_Churn

2. Crie e ative um ambiente virtual

  python -m venv venv
  source venv/bin/activate  # No Windows: venv\Scripts\activate

3. Instale as dependencias
   pip install -r requirements.txt

4. Execute o notebook
   jupyter notebook

🛠️ Tecnologias Utilizadas
Python 3.x
Pandas
NumPy
Seaborn, Matplotlib
Jupyter Notebook
👏 Contribuição
Sugestões, dúvidas ou melhorias são bem-vindas! Abra uma issue ou envie um pull request.

Feito com dedicação pela equipe de Data Science da Telecom X 🚀

Licença: MIT
