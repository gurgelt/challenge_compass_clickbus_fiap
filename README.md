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
# 1. Abra a pasta "Visualização Streamlit" no link do Google Drive

# 2. Baixe a pasta "clickbuss"

# 3. Abra a pasta no VSCODE

# 3. Abra o arquivo app.py

# 4. Instale as dependências necessárias no console
pip install numpy pandas streamlit plotly

# 5. Altere o caminho da sua pasta local dentro do código para rodar

# Local exato em que você irá trocar o código e sua pasta
default_dirs = [
    r"C:\Users\paulo.gurgel\Desktop\Solução ComPass\Visualização Streamlit\clickbuss",   # <- Aqui você deverá alterar para o caminho da sua pasta "clickbuss" em que estão os arquivos
    os.path.join(os.getcwd(), "clickbuss"),  # pasta relativa
    "/content/drive/MyDrive/clickbuss"       # Colab/Drive
]

# 6. Execute o arquivo app.py com o streamlit
streamlit run app.py

# 7. Dê um scroll para baixo ao lado esquerdo da navbar para visualizar as opções de segmentação, previsão de compra e previsão de próximo destino.
<img width="241" height="251" alt="image" src="https://github.com/user-attachments/assets/7269ae64-a555-4df2-964c-ab65a2672676" />

# 8. Aproveite os Insights :)
