# Imersão Dados com Python - Dashboard Interativo

## Descrição

Este projeto é um dashboard interativo desenvolvido durante a Imersão de Dados com Python da Alura. O objetivo é analisar dados salariais na área de dados, permitindo que os usuários filtrem informações por ano, tipo de contrato e senioridade.

## Tecnologias Utilizadas

- Python
- Streamlit
- Pandas
- Plotly

## Funcionalidades

- Visualização de métricas salariais, como salário médio, máximo e total de registros.
- Filtros dinâmicos para explorar os dados em tempo real.
- Gráficos interativos que mostram a distribuição salarial e os cargos mais frequentes.
- Mapa que exibe a média salarial para o cargo de Cientista de Dados por país.

# 1. Clone este repositório
git clone https://github.com/seu_usuario/imersao_dados_python.git

# 2. Navegue até o diretório do projeto
cd imersao_dados_python

# 3. Crie um ambiente virtual
python -m venv venv

# 4. Ative o ambiente virtual
# Mac / Linux
source venv/bin/activate

# Windows
venv\Scripts\activate

# 5. Instale as dependências do projeto
pip install -r requirements.txt

# 6. Execute o aplicativo Streamlit
streamlit run app.py

# 7. Acesse o dashboard no navegador
# http://localhost:8501
