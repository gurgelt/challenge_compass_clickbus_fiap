# Challenge Compass / ClickBus - FIAP

Repositório para a entrega do desafio da FIAP em parceria com a ClickBus.

---

## 🧭 Sumário

- [Sobre](#sobre)  
- [Funcionalidades / Objetivos](#funcionalidades--objetivos)  
- [Arquitetura / Tecnologias](#arquitetura--tecnologias)  
- [Como executar / rodar localmente](#como-executar--rodar-localmente)  
- [Visualização (Streamlit)](#visualização-streamlit)  
- [Colaboração / Contribuição](#colaboração--contribuição)  
- [Contato / Autores](#contato--autores)  

---

## Sobre

Este projeto corresponde ao desafio proposto pela FIAP, em parceria com a ClickBus.  
O objetivo principal é apresentar uma solução de **Modelos de Machine Learning**, **Visualização de Dados** e futuras composições que auxiliarão a **ClickBus** a tomarem decisões estratégicas baseado em dados, que atenda aos requisitos definidos no desafio (Segmentação de Clientes, Previsão de Próxima Compra, Previsão de Próximo Destino)

---

## Funcionalidades / Objetivos

- Preprocessamento de dados  
- Feature engineering  
- Modelagem e validação  
- Modelos de Previsões 
- Visualização interativa com **Streamlit**  
- Insights com base nas visualizações

---

## Arquitetura / Tecnologias

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  
- Streamlit  

---

## Como executar / rodar localmente

### Pré-requisitos

- Ter **Python 3.x** instalado  
- Ambiente virtual configurado com as bibliotecas necessárias

### Passo a passo de como rodar o Streamlit

### Atenção: 

- Todos os arquivos necessários para rodar o STREAMLIT são grandes demais para serem armazenados no GitHub, por isso postamos eles no Google Drive também para vocês poderem baixar e assim conseguirem executar corretamente a nossa solução.

- Link do Google Drive para baixar o restante dos arquivos: https://drive.google.com/drive/folders/1J86ENa-IBWder4iiuaqtgxwg113dgFrB?usp=sharing

```bash
# 1. Clone o repositório
git clone https://github.com/gurgelt/challenge_compass_clickbus_fiap.git
cd challenge_compass_clickbus_fiap

# 2. Instale dependências
pip install numpy pandas streamlit plotly

# 3. Altere o caminho da sua pasta local para rodar

default_dirs = [
    r"C:\Users\paulo.gurgel\Desktop\Solução ComPass\Visualização Streamlit\clickbuss",   # <- Aqui você deverá alterar para o caminho da sua pasta em que estão os arquivos
    os.path.join(os.getcwd(), "clickbuss"),  # pasta relativa
    "/content/drive/MyDrive/clickbuss"       # Colab/Drive
]

# 4. Execute o arquivo app.py
streamlit run app.py
