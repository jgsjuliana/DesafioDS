## Contexto do projeto

Este repositório apresenta a exploração dos dados e aplicação de um modelo de predição, para identificar valores ausentes de GDP growth (Gross Domestic Product) e predição dos valores para os anos de 2024 a 2028, do projeto Certificação Data Science pela Indicium. 

## Passo a passo para inicialização do projeto

### Clonando o projeto
Primeiramente, é necessário clonar o repositório localmente. O projeto pode ser clonado via SSH ou HTTPS utilizando-se o comando `git clone` no link.
- `https://github.com/jgsjuliana/DesafioDS.git`

### Criando um ambiente virtual
Será necessária a criação de um ambiente virtual na pasta home do projeto.
- `python3 -m venv venv` ou
- `py -3.8 -m venv venv` para Bash no Windows.
A **versão do Python** utilizada neste projeto é a **3.8.9**.

### Ativação do ambiente virtual
Ao criar a vitual env, será preciso realizar a ativação do ambiente.
- `source venv/bin/activate` no Linux ou
- `source venv/Scripts/activate` em bash no Windows, ou ainda
- `.\venv\Scripts\activate.ps1` no Windows PowerShell

Garanta que você está na pasta onde o ambiente virtual foi criado. Se ele for ativado corretamente, o terminal terá uma flag apontando ***(venv)*** na frente do nome do usuário antes de cada comando. Para desativar o ambiente virtual, basta rodar: 

- `deactivate`.

### Instalando as bibliotecas

Para instalação das bibliotecas precisamos executar o comando `pip install -r requirements.txt` na linha de comando.

### Rodando o projeto

Abra o arquivo *EDA_e_Modelo_Desafio_DS_JulianaSantos.ipynb* e rode por completo com `run all`. Este arquivo contém a exploração de dados e a aplicação do modelo autoarima.

Ao finalizar, o arquivo gerará um csv de nome: *predicted.csv* com os valores do GDP real para os anos de 1980 até 2023 e a projeção de 2024 até 2028.

## Ferramentas utilizadas
- Python 3.8.9
- jupyter notebook

## Fontes utilizadas:
- Real GDP growth (Annual percent change) [International Monetary Fund] (https://www.imf.org/external/datamapper/NGDP_RPCH@WEO/CAQ)
- Country Composition of Regions for IMF Data Mapper [International Monetary Fund] (https://www.imf.org/external/datamapper/region.htm)
- World Economic Outlook Database [International Monetary Fund] (https://www.imf.org/en/Publications/WEO/weo-database/2023/April/select-countries?grp=995&sg=All-countries/)
- Autoarima (https://miqbalrp.medium.com/exploring-autoarima-in-python-for-multiple-time-series-forecasting-2f3004ba5a49)