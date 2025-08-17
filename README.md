# Sistema de Análise e Previsão de Séries Temporais

Este projeto é uma aplicação web interativa desenvolvida com Streamlit para análise e previsão de séries temporais. O sistema permite ao usuário carregar arquivos de dados, visualizar gráficos e obter previsões futuras utilizando modelos estatísticos.

## Funcionalidades

- Upload de arquivo CSV
- Seleção de período inicial para análise
- Definição do horizonte de previsão (em meses)
- Visualização da decomposição da série temporal
- Previsão de valores futuros com modelo SARIMAX
- Exibição de gráficos interativos e tabela de resultados

## Como usar

1. Execute o Streamlit:
   ```bash
   streamlit run aplicacao-analise.py
   ```
2. Carregue seu arquivo CSV na barra lateral.
3. Selecione o período inicial e o número de meses para previsão.
4. Clique em "Processar Dados" para visualizar os resultados.

## Requisitos

- Python 3.8+
- streamlit
- pandas
- statsmodels
- matplotlib

Instale as dependências com:

```bash
pip install streamlit pandas statsmodels matplotlib
```

## Sobre o modelo

O sistema utiliza o modelo SARIMAX para previsão de séries temporais, além de decomposição sazonal para análise dos componentes da série.

## Desenvolvedor

- **Giulliano Veiga**
- Cientista de Dados
- WhatsApp: [+55 85 98170-8027](https://wa.me/5585981708027)
- Instagram: [@giullianoveiga](https://instagram.com/giullianoveiga)
- GitHub: [giullianoveiga](https://github.com/giullianoveiga)
- LinkedIn: [Giulliano Veiga](https://www.linkedin.com/in/giulliano-veiga/)