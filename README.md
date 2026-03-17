# FarmTech Solutions - Previsão de Rendimento de Safra com Machine Learning

**Curso:** IA - FIAP | Fase 5
**Grupo:** 8 | Turma: 1TIAOR

**Integrantes do Grupo:**

| Nome | RM |
|------|-----|
| João Rafael Gonçalves Ramos | rm567908 |
| Letícia Angelim Guerra | rm567501 |
| Matheus Guimarães França | rm567144 |
| Rivando Bezerra Cavalcanti Neto | rm568235 |
| Tales Ferraz de Arruda Domienikan | rm567483 |

## Sobre o Projeto

Este projeto foi desenvolvido para a FarmTech Solutions, empresa que presta serviços de Inteligência Artificial para uma fazenda de médio porte (200 hectares) que produz diversas culturas agrícolas.

O objetivo é analisar uma base de dados com informações de condições de solo e temperatura, relacionadas ao tipo de produto agrícola, para:

1. **Explorar os dados** e entender as relações entre as variáveis climáticas e o rendimento das safras
2. **Identificar tendências** por meio de clusterização (aprendizado não supervisionado) e detectar outliers
3. **Prever o rendimento** da safra utilizando cinco modelos de regressão supervisionada

## Dataset

O dataset `crop_yield.csv` contém 155 registros de 4 culturas com as seguintes variáveis:

| Variável | Descrição |
|----------|-----------|
| Crop | Nome da cultura agrícola |
| Precipitation (mm day-1) | Precipitação em milímetros por dia |
| Specific Humidity at 2 Meters (g/kg) | Umidade específica a 2 metros do solo |
| Relative Humidity at 2 Meters (%) | Umidade relativa a 2 metros do solo |
| Temperature at 2 Meters (C) | Temperatura a 2 metros do solo |
| Yield | Rendimento em toneladas por hectare |

## Estrutura do Repositório

```
ATV5_1/
├── README.md
├── crop_yield.csv
└── RivandoBezerra_rm568235_pbl_fase4.ipynb
```

## Notebook

Todo o desenvolvimento, análise e conclusões estão documentados no Jupyter Notebook:

**[RivandoBezerra_rm568235_pbl_fase4.ipynb](./RivandoBezerra_rm568235_pbl_fase4.ipynb)**

O notebook está organizado nas seguintes seções:

1. **Análise Exploratória (EDA)** - Estatísticas descritivas, distribuições, correlações e visualizações
2. **Clusterização** - Método do cotovelo, KMeans, visualização com PCA e detecção de outliers
3. **Modelos Preditivos** - Cinco algoritmos de regressão supervisionada:
   - Regressão Linear
   - Ridge Regression
   - Lasso Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
4. **Comparação de Modelos** - Métricas R², MAE, MSE, RMSE e validação cruzada
5. **Conclusões** - Pontos fortes, limitações e recomendações

## Como Executar

1. Certifique-se de ter Python 3.8+ instalado
2. Instale as dependências:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Abra o notebook:
   ```bash
   jupyter notebook RivandoBezerra_rm568235_pbl_fase4.ipynb
   ```

## Vídeo Demonstrativo

[Link do vídeo no YouTube](https://youtu.be/rW4sRL_B4HM)

## Tecnologias Utilizadas

- Python 3
- Pandas e NumPy (manipulação de dados)
- Matplotlib e Seaborn (visualização)
- Scikit-learn (Machine Learning)
- Jupyter Notebook
