# 🌍 Projeto de Visualização de Dados: Índice de Felicidade Mundial

**Autores:**  
- Diego Renan Cavalcante Silva  
- Isaac Brito Cajá Freitas  
- João Vitor dos Santos Santana

---

## 🎯 Objetivo

Este projeto foi desenvolvido como parte das atividades acadêmicas com o objetivo de aplicar conceitos de ciência de dados, análise exploratória e visualização interativa. A proposta central foi explorar dados sobre o nível de felicidade em diferentes países do mundo com base em indicadores sociais, econômicos e de bem-estar.

---

## 🗂️ Base de Dados

A base utilizada foi o **World Happiness Report 2023**, um levantamento global amplamente reconhecido que avalia o bem-estar dos cidadãos de diversos países com base nos seguintes indicadores:

- `Country`: Nome do país  
- `Happiness Score`: Pontuação de felicidade (0 a 10)  
- `GDP per Capita`: PIB per capita  
- `Social Support`: Apoio social  
- `Healthy Life Expectancy`: Expectativa de vida saudável  
- `Freedom to make life choices`: Liberdade de escolha  
- `Perceptions of Corruption`: Percepção de corrupção  

O arquivo original foi fornecido em formato `.csv` e posteriormente limpo e tratado para garantir sua compatibilidade com ferramentas de visualização.

---

## 🧹 Processamento de Dados

Utilizamos a biblioteca **pandas** (Python) para:

- Tratar valores nulos e colunas irrelevantes;
- Padronizar nomes de países para compatibilidade com o mapa mundial (TopoJSON);
- Salvar os dados processados em um repositório no **GitHub** para facilitar a leitura pelo **Observable HQ**.

---

## 📊 Visualizações Interativas (Observable + Vega-Lite)

Criamos um projeto no [Observable HQ](https://observablehq.com) utilizando **Vega-Lite** para gerar visualizações e contar uma narrativa com base nos dados analisados.

### Visualizações Desenvolvidas:

1. **🗺️ Mapa Mundial da Felicidade**  
   Mapa coroplético destacando os países mais e menos felizes com base na pontuação.

2. **📉 Gráfico de Barras (Ranking Global)**  
   Exibe todos os países ordenados do mais ao menos feliz.

3. **📈 Gráfico de Dispersão (PIB vs Felicidade)**  
   Analisa a correlação entre PIB per capita e índice de felicidade, com destaque para os 10 países mais e menos felizes.

---

## 🧠 Conclusões

- Países nórdicos lideram consistentemente os rankings de felicidade.
- Há uma correlação positiva entre PIB per capita e felicidade, mas outros fatores como apoio social e liberdade de escolha também são determinantes importantes.
- Regiões com crises sociais ou econômicas tendem a apresentar os menores índices de felicidade.

---

## 🛠️ Tecnologias Utilizadas

- **Python (Pandas)** – Análise e limpeza dos dados  
- **GitHub** – Armazenamento dos dados processados  
- **Observable HQ** – Criação das visualizações interativas  
- **Vega-Lite** – Biblioteca de visualização declarativa

---

## 📎 Acesse

🔗 Visualização completa no Observable: [link para o projeto Observable]([https://observablehq.com/...](https://observablehq.com/d/63b7de6259bf5fee))  
📁 Repositório com os dados e scripts: [link para o repositório GitHub]([https://github.com/...](https://github.com/vitorsantanajv/projeto_indice_de_felicidade))

---

> Projeto acadêmico desenvolvido na disciplina de Ciência de Dados.
