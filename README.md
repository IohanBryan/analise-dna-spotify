# 🎵 Análise de Dados Musical: DNA do Top 50 Spotify

## 📌 Descrição do Projeto

Este projeto utiliza **Python** para analisar as características musicais das 50 músicas mais ouvidas do **Spotify**. O objetivo é extrair parâmetros técnicos como **Batidas por Minuto (BPM)**, **Energia**, **Dançabilidade** e **Volume**, e transformá-los em uma identidade visual única — chamada de **DNA Musical** — por meio de um **gráfico polar (radar) interativo**.

O projeto demonstra como tratar dados brutos provenientes de arquivos **CSV**, aplicar **normalização de escalas técnicas** e convertê-las em representações visuais intuitivas, facilitando a análise de tendências no mercado fonográfico.

---

## 🎯 Objetivos

* Processar dados estatísticos de streaming musical
* Realizar a normalização de escalas (BPM e Volume) para visualização comparativa
* Gerar um **Gráfico de Radar interativo** utilizando Plotly
* Identificar o **perfil médio** das músicas de maior sucesso no Spotify

---

## 🛠️ Tecnologias Utilizadas

* **Python**
* **Pandas** – Tratamento e manipulação de dados
* **Plotly Express** – Criação de gráficos interativos e dinâmicos
* **Dataset CSV** – Top 50 Spotify Songs (2019)

---

## 📂 Estrutura do Projeto

```bash
Analise_Spotify/
│
├── main.py        # Script principal com lógica de análise e geração dos gráficos
├── top50.csv      # Base de dados com atributos musicais
└── README.md      # Documentação do projeto
```

---

## 📈 Análises Realizadas

Durante o processamento dos dados, foram selecionadas métricas essenciais que ajudam a definir a "vibe" de uma música:

* **BPM (Beats Per Minute):** Ritmo e velocidade da música
* **Energy:** Intensidade e nível de atividade da faixa
* **Danceability:** Grau de adequação da música para dança
* **Volume (Loudness):** Amplitude sonora média da faixa
* **Valence:** Positividade emocional transmitida pela melodia

Para garantir uma visualização equilibrada, os dados de **BPM** e **Volume** foram normalizados para se ajustarem à **escala de 0 a 100**, utilizada pelas demais métricas.

---

## 📊 Visualizações Geradas

O projeto gera um **Gráfico Polar interativo**, que representa visualmente o DNA musical médio das faixas Top 50, com os seguintes recursos:

* **Área preenchida:** Facilita a visualização do volume ocupado pelo perfil musical
* **Indicadores dinâmicos (Hover):** Exibição do nome da métrica e do valor exato ao passar o mouse

---

## 📌 Conclusão

Este projeto apresenta um fluxo objetivo de **Análise Exploratória de Dados** com Python, partindo da leitura e tratamento de um dataset do Top 50 do Spotify até a criação de uma visualização interativa em gráfico polar. A normalização de métricas como **BPM** e **Volume**, aliada ao cálculo das médias das características musicais, permitiu sintetizar o perfil sonoro predominante das músicas mais populares em um **DNA Musical** claro e intuitivo, demonstrando habilidades essenciais de limpeza, análise e visualização de dados em um projeto de escopo enxuto.

---

## 👤 Autor

**Iohan Bryan da Silva Fortaleza**
Analista de Dados em formação

📧 Email: [yohanbryan2000@gmail.com](mailto:yohanbryan2000@gmail.com)
🔗 LinkedIn: [https://www.linkedin.com/in/iohan-bryan-566a6a398/](https://www.linkedin.com/in/iohan-bryan/)
📷 Instagram: [https://www.instagram.com/iohanbryan_2/](https://www.instagram.com/iohanbryan_2/)
