# Challenge Compass / ClickBus FIAP

Repositório para a entrega do desafio da FIAP em parceria com a ClickBus.

---

## 🧭 Sumário

- [Sobre](#sobre)  
- [Funcionalidades / Objetivos](#funcionalidades--objetivos)  
- [Arquitetura / Tecnologias](#arquitetura--tecnologias)  
- [Como executar / rodar localmente](#como-executar--rodar-localmente)  
- [Estrutura de pastas](#estrutura-de-pastas)  
- [Uso / Exemplos](#uso--exemplos)  
- [Colaboração / Contribuição](#colaboração--contribuição)  
- [Contato / Autor](#contato--autor)  

---

## Sobre

Este projeto corresponde ao desafio proposto pela FIAP, em parceria com a ClickBus. O objetivo principal é apresentar uma solução (por exemplo, de modelagem de dados, predictor de demanda, interface ou pipeline) que atenda aos requisitos definidos no desafio.

---

## Funcionalidades / Objetivos

Basicamente, este projeto pretende:

- Implementar um modelo de **machine learning / análise de dados** (ou similar) para o problema proposto  
- Processar, transformar e explorar dados  
- Avaliar e validar métricas de performance  
- Apresentar os resultados (via relatório, dashboard ou outro meio)  

Você pode listar especificamente o que foi entregue:

- Preprocessamento de dados  
- Feature engineering  
- Modelagem e validação  
- Avaliação com métricas (ex: RMSE, acurácia, etc.)  
- Apresentação/relatório final  

---

## Arquitetura / Tecnologias

Ferramentas e bibliotecas utilizadas (exemplos — altere conforme o seu projeto real):

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn, XGBoost (ou outra biblioteca de ML)  
- Jupyter Notebook / JupyterLab  
- Matplotlib / Seaborn / Plotly  
- Possivelmente (se aplicável) Flask, FastAPI ou Streamlit para interface  

---

## Como executar / rodar localmente

Aqui está um passo a passo para você ou outros desenvolvedores rodarem o projeto localmente:

### Pré-requisitos

- Ter **Python 3.x** instalado  
- Ferramenta de ambiente virtual (venv, conda, etc.)  
- (Opcional) GPU / CUDA se modelos pesados forem usados  

### Passo a passo

```bash
# 1. Clone o repositório
git clone https://github.com/gurgelt/challenge_compass_clickbus_fiap.git
cd challenge_compass_clickbus_fiap

# 2. Crie e ative ambiente virtual (ex: venv)
python3 -m venv venv
source venv/bin/activate       # no macOS/Linux
# ou (Windows)
# venv\Scripts\activate

# 3. Instale dependências
pip install -r requirements.txt

# 4. Execute os notebooks / scripts principais
# Por exemplo:
jupyter notebook
# ou
jupyter lab

# Se houver script principal, por exemplo:
python main.py     # altere conforme nome real
