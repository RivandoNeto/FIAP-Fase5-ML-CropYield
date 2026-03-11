# FarmTech Solutions - Previsao de Rendimento de Safra com Machine Learning

**Curso:** IA - FIAP | Fase 5

**Integrantes do Grupo:**

| Nome | RM |
|------|-----|
| Joao Rafael Goncalves Ramos | rm567908 |
| Leticia Angelim Guerra | rm567501 |
| Matheus Guimaraes Franca | rm567144 |
| Rivando Bezerra Cavalcanti Neto | rm568235 |
| Tales Ferraz de Arruda Domienikan | rm567483 |

## Sobre o Projeto

Este projeto foi desenvolvido para a FarmTech Solutions, empresa que presta servicos de Inteligencia Artificial para uma fazenda de medio porte (200 hectares) que produz diversas culturas agricolas.

O objetivo e analisar uma base de dados com informacoes de condicoes de solo e temperatura, relacionadas ao tipo de produto agricola, para:

1. **Explorar os dados** e entender as relacoes entre as variaveis climaticas e o rendimento das safras
2. **Identificar tendencias** por meio de clusterizacao (aprendizado nao supervisionado) e detectar outliers
3. **Prever o rendimento** da safra utilizando cinco modelos de regressao supervisionada

## Dataset

O dataset `crop_yield.csv` contem 155 registros de 4 culturas com as seguintes variaveis:

| Variavel | Descricao |
|----------|-----------|
| Crop | Nome da cultura agricola |
| Precipitation (mm day-1) | Precipitacao em milimetros por dia |
| Specific Humidity at 2 Meters (g/kg) | Umidade especifica a 2 metros do solo |
| Relative Humidity at 2 Meters (%) | Umidade relativa a 2 metros do solo |
| Temperature at 2 Meters (C) | Temperatura a 2 metros do solo |
| Yield | Rendimento em toneladas por hectare |

## Estrutura do Repositorio

```
ATV5_1/
├── README.md
├── crop_yield.csv
└── RivandoBezerra_rm568235_pbl_fase4.ipynb
```

## Notebook

Todo o desenvolvimento, analise e conclusoes estao documentados no Jupyter Notebook:

**[RivandoBezerra_rm568235_pbl_fase4.ipynb](./RivandoBezerra_rm568235_pbl_fase4.ipynb)**

O notebook esta organizado nas seguintes secoes:

1. **Analise Exploratoria (EDA)** - Estatisticas descritivas, distribuicoes, correlacoes e visualizacoes
2. **Clusterizacao** - Metodo do cotovelo, KMeans, visualizacao com PCA e deteccao de outliers
3. **Modelos Preditivos** - Cinco algoritmos de regressao supervisionada:
   - Regressao Linear
   - Ridge Regression
   - Lasso Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
4. **Comparacao de Modelos** - Metricas R2, MAE, MSE, RMSE e validacao cruzada
5. **Conclusoes** - Pontos fortes, limitacoes e recomendacoes

## Como Executar

1. Certifique-se de ter Python 3.8+ instalado
2. Instale as dependencias:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Abra o notebook:
   ```bash
   jupyter notebook RivandoBezerra_rm568235_pbl_fase4.ipynb
   ```

## Video Demonstrativo

[Link do video no YouTube](INSERIR_LINK_AQUI)

## Tecnologias Utilizadas

- Python 3
- Pandas e NumPy (manipulacao de dados)
- Matplotlib e Seaborn (visualizacao)
- Scikit-learn (Machine Learning)
- Jupyter Notebook
