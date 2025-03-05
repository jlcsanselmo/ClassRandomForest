#  Classificação Supervisionada de Imagens - Random Forest

Este projeto realiza **Classificação Supervisionada de Imagens SENTINEL Raster** utilizando **Random Forest (RF)** com base em amostras de treinamento fornecidas em um **Shapefile**.

📌 **Principais etapas:**
1. **Carregar a imagem raster** (GeoTIFF).
2. **Carregar o shapefile de amostras** contendo as classes.
3. **Extrair valores dos pixels correspondentes às amostras**.
4. **Treinar um modelo de Machine Learning (Random Forest)**.
5. **Classificar toda a imagem raster**.
6. **Salvar o resultado como um novo raster classificado**.
7. **Avaliar a precisão da classificação** com métricas como acurácia e matriz de confusão.

