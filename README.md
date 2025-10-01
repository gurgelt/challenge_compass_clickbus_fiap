<img width="1231" height="193" alt="image" src="https://github.com/user-attachments/assets/5cdf317a-0d47-47bd-97e2-125a7e5a186f" />


# Challenge Compass / ClickBus - FIAP

Repositório para a entrega do desafio da FIAP em parceria com a ClickBus.

---

## Importante:

- Para que seja compreendido além do que está no GitHub, pedimos educadamente que visualizem também o arquivo PDF da nossa apresentação, juntamente com o vídeo pitch (link no slide final do arquivo pdf), para compreender melhor ainda a nossa missão e compromisso com a ClickBus.

## 🧭 Sumário

- Sobre
- Funcionalidades / Objetivos
- Tecnologias
- Arquitetura Futura
- Como executar o Streamlit
- Como executar o Modelo de Machine Learning
- Contato / Autores
---

## Sobre

Este projeto corresponde ao desafio proposto pela ClickBus, em parceria com a FIAP.

O objetivo principal é apresentar uma solução de:
- **Modelos de Machine Learning**
- **Visualização de Dados** e
- **Futuras composições que auxiliarão a ClickBus a tomarem decisões estratégicas baseado em dados**

Que atenda aos requisitos definidos no desafio (Segmentação de Clientes, Previsão de Próxima Compra, Previsão de Próximo Destino)

<img width="1051" height="579" alt="image" src="https://github.com/user-attachments/assets/a23428dd-260f-4f0b-b72d-5b8e3ea2b68f" />


---

## Funcionalidades / Objetivos

- Preprocessamento de dados  
- Feature engineering  
- Modelagem e validação  
- Modelos de Previsões 
- Visualização interativa com **Streamlit**  
- Insights com base nas visualizações

  <img width="1034" height="506" alt="image" src="https://github.com/user-attachments/assets/8d7efb6c-89a7-48a3-b6a4-5d9fd89a3221" />


---

## Tecnologias

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  
- Streamlit  

---

## Arquitetura Futura para a ClickBus

<img width="1229" height="678" alt="image" src="https://github.com/user-attachments/assets/78541385-b687-4de5-b860-57027ced82e6" />

Para escalar a solução que criamos, essa é a arquitetura que planejamos para o futuro, um pipeline de dados 100% serverless e automatizado na AWS.

1. Nossa jornada começa extraindo os dados direto da fonte, que pode ser o MongoDB  (ou banco em nuvem que vocês utilizam), e centralizando tudo de forma segura em S3, que funcionará como nosso grande repositório de dados.

2. A partir daí, a orquestração fica por conta do MWAA, que comanda todo o fluxo de forma automática, sem nenhuma intervenção manual. É ele quem aciona o AWS Glue para transformar os dados brutos em informações limpas e prontas para o consumo, criando um catálogo de dados para facilitar qualquer consulta.

3. Com os dados preparados, entra em cena o nosso cérebro, o SageMaker. Ele utiliza essas informações para treinar e rodar os modelos de segmentação e de propensão, gerando as previsões de próxima compra e destino que o negócio precisa.

4. E claro, damos total visibilidade e poder de análise para vocês. Com o Athena, seu time de dados pode fazer consultas exploratórias diretamente nos dados processados. E na ponta final, o QuickSight consome tudo isso para entregar dashboards dinâmicos e visuais, permitindo que o time de marketing e produto acompanhe os segmentos e a performance das previsões em tempo real.

Em resumo, é uma arquitetura que não só resolve os desafios de hoje, mas que prepara a ClickBus para o futuro, transformando dados brutos em inteligência de negócio de forma contínua, escalável e eficiente.


---


## Como executar o Streamlit / rodar localmente

### Pré-requisitos

- Ter **Python 3.x** instalado  
- Ambiente virtual configurado com as bibliotecas necessárias

### Passo a passo de como rodar o Streamlit

### Atenção: 

- Todos os arquivos necessários para executar o Streamlit são grandes demais para serem armazenados no GitHub. Por isso, disponibilizamos eles no Google Drive, para que vocês possam baixar e rodar a aplicação corretamente.

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

# 8. Aproveite os Insights :)
```
---
## Como executar o Modelo de Machine Learning

### Passo a passo de como rodar o código:

```bash
# 1. Abra a pasta "Código Machine Learning"

# 2. Baixe ou copie o arquivo "ClickBus_Entrega_Completa_v5.ipynb" para seu Google Colab

# 3. Visualize o resultado dos modelos que foram gerados
```
---
### Contato / Autores

<img width="1228" height="687" alt="image" src="https://github.com/user-attachments/assets/d6d0d64b-4e4d-4a1a-878f-c0f748f86c27" />

### Nosso LinkedIn:

- [Paulo Gurgel](https://www.linkedin.com/in/paulo-tudini/)
- [Mike Lucio Rubiml](https://www.linkedin.com/in/mike-rubim-155735130/)
- [Augusto Giannattasio Lopes](https://www.linkedin.com/in/augusto-giannattasio-lopes/)
- [Pedro Pereira](https://www.linkedin.com/in/pedro-pereira-8334a9211/)

# Guiamos a sua empresa na direção correta >>>>

