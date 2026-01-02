<img width="1016" height="702" alt="image" src="https://github.com/user-attachments/assets/d5440209-32fc-4647-bf31-9a271f813705" />


# 🚕 Análise de Corridas da Uber

Este repositório apresenta uma análise exploratória de dados (EDA) sobre um dataset de corridas da Uber. O objetivo do projeto é investigar padrões e tendências no comportamento das corridas, respondendo a perguntas como:

* Quais são os horários de pico?
* Quais dias da semana têm mais movimento?
* Quais são os principais pontos de partida e de destino?

A análise foi desenvolvida em um Jupyter Notebook utilizando Python e suas principais bibliotecas de análise de dados. Além disso, foi criado um dashboard no Power BI para visualização interativa dos resultados.

## 🛠️ Ferramentas e Bibliotecas Utilizadas

* **Python 3**
* **Pandas:** Para manipulação e limpeza dos dados.
* **Matplotlib & Seaborn:** Para a criação dos gráficos e visualizações.
* **Jupyter Notebook:** Como ambiente de desenvolvimento.
* **Power BI:** Para a criação do dashboard interativo.

## 📦 Dataset

O dataset utilizado contém informações sobre corridas da Uber, incluindo colunas como:
* `PURPOSE*`: O propósito da viagem (Ex: Reunião, Refeição, etc.).
* `START_DATE*`: Data e hora de início da corrida.
* `END_DATE*`: Data e hora de término da corrida.
* `START*`: Local de partida.
* `STOP*`: Local de destino.
* `MILES*`: Distância da corrida em milhas.

*Os dados passaram por um processo de limpeza e tratamento para corrigir inconsistências e valores ausentes antes da análise.*

## 📈 Análises Realizadas e Principais Insights

O notebook explora os dados para extrair os seguintes insights:

1.  **Análise Temporal:**
    * **Horários de Pico:** A análise revelou que a maior concentração de corridas ocorre no período da tarde, especialmente entre 12h e 18h.
    * **Dias da Semana:** Sexta-feira é o dia com o maior volume de corridas, sugerindo um aumento de atividades de negócios e lazer no final da semana.
    * **Análise Mensal:** O mês de dezembro se destaca com o maior número de viagens, possivelmente devido às atividades de final de ano.

2.  **Análise de Propósito da Viagem:**
    * **Principais Motivos:** A maioria das viagens está relacionada a "Reunião" (Meeting) e "Refeição/Buscar Lanche" (Meal/Entertain), indicando um forte uso corporativo ou para atividades cotidianas.

3.  **Análise Geográfica:**
    * **Principais Pontos de Partida:** A localidade de "Cary" aparece como o ponto de partida mais frequente no dataset.

## 📊 Dashboard no Power BI

Para complementar a análise estática do notebook, foi desenvolvido um dashboard interativo no Power BI. Ele permite filtrar os dados dinamicamente e explorar os insights de forma mais visual.

`[Dashboard Power BI]`

`[1. OVERALL - ANALYSIS]`
<img width="1364" height="779" alt="image" src="https://github.com/user-attachments/assets/21f09fc5-e683-4712-ba2e-1be59bfe5666" />


`[2. PAYMENTS - ANALYSIS]`
<img width="1319" height="793" alt="image" src="https://github.com/user-attachments/assets/24630e9e-a626-458a-b985-95f74641aba3" />


`[3. CANCELLATIONS - ANALYSIS]`
<img width="1392" height="791" alt="image" src="https://github.com/user-attachments/assets/fbd44e23-c664-4cf5-858f-3c910a31ea23" />


`[4. ASSESSMENT - ANALYSIS]`
<img width="1341" height="797" alt="image" src="https://github.com/user-attachments/assets/8a134f80-6a14-468e-95a6-d8d5ef815e98" />


## 🚀 Como Executar o Projeto

Para visualizar a análise e executar o código, siga os passos:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/analise-corridas-uber.git](https://github.com/seu-usuario/analise-corridas-uber.git)
    ```

2.  **Acesse a pasta do projeto:**
    ```bash
    cd analise-corridas-uber
    ```

3.  **Instale as dependências:**
    (Recomendação: Crie um ambiente virtual primeiro)
    ```bash
    pip install -r requirements.txt
    ```

4.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook Analise_de_corrida_UBER.ipynb
    ```

## 📂 Estrutura do Repositório

* `dashboard/`: Contém o arquivo do Power BI (`.pbix`) com o dashboard interativo.
* `Analise_de_corrida_UBER.ipynb`: O Jupyter Notebook com todo o código da análise.
* `README.md`: Este arquivo de documentação.
* `requirements.txt`: Arquivo com as bibliotecas Python necessárias.

---

<h1 align="center">🧑🏻‍💻 Marcelo Kudo</h1>

<div align="center">

</div>

<div align="center">

## 🧠 **Sobre Mim**

Profissional com expertise entre **automação industrial** e **inteligência artificial**.

### 🎯 **Expertise Técnica**

| **Área** | **Competências** |
|----------|------------------|
| **🤖 Automação Industrial** | Programação de CLP's, IHM, Inversor de Frequência |
| **👁️ Visão Computacional** | OpenCV, PyTorch, detecção de defeitos, classificação, aplicações industriais |
| **🧠 Machine Learning** | Modelos preditivos, redes neurais, scikit-learn, TensorFlow |
| **⚡ Edge Computing** | NVIDIA Jetson, otimização para hardware embarcado |
| **🤝 Robótica** | Robôs colaborativos UR, robótica industrial |
| **🌐 IIoT** | Integração de sistemas, protocolos industriais |
| **📊 Análise de Dados** | Pandas, NumPy, análise exploratória, visualização com Seaborn/Matplotlib |
| **📈 Dashboards** | Streamlit, Power BI, SQL, relatórios interativos para tomada de decisão |

"Tecnologia é poderosa quando resolve problemas reais."

</div>



