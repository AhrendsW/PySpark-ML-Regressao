### Projeto: PySpark-ML-Regression

Este projeto utiliza PySpark para trabalhar com modelos de regressão, visando prever os valores de imóveis a partir de um conjunto de dados em formato JSON. O processo consiste nas seguintes etapas:

1. **Vetorização dos Dados**: Transformação dos dados em vetores para serem utilizados nos modelos de regressão.
2. **Modelos de Regressão**:
   - Regressão Linear
   - Árvore de Decisão
   - Random Forest
3. **Avaliação de Métricas**: Avaliação dos modelos utilizando métricas como R² e RMSE.
4. **Validação Cruzada**: Aplicação de cross-validation para otimizar o modelo.
5. **Comparação de Modelos**: Comparação dos resultados para determinar o melhor modelo.
6. **Previsão de Valores**: Criação de um DataFrame com características de um imóvel específico usando PySpark e previsão do valor necessário para a compra desse imóvel com o modelo escolhido.

O objetivo final é identificar o modelo de regressão mais preciso para prever valores imobiliários e aplicá-lo para calcular o valor de um imóvel com base em suas características.

**Lembrete**: O conjunto de dados se chama `imoveis.json` e está localizado na pasta `data`. É necessário atualizar o caminho de leitura do arquivo no código para garantir que o arquivo seja lido corretamente.
