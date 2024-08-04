### Projeto: PySpark-ML-Regression

Este projeto utiliza PySpark para trabalhar com modelos de regressão, visando prever os valores de imóveis a partir de um conjunto de dados em formato JSON. O processo consiste nas seguintes etapas:

1. **Método Dummy**: Aplicação do método dummy para variáveis categóricas.
2. **Vetorização dos Dados**: Transformação dos dados em vetores para serem utilizados nos modelos de regressão.
3. **Modelos de Regressão**:
   - Regressão Linear
   - Árvore de Decisão
   - Random Forest
4. **Avaliação de Métricas**: Avaliação dos modelos utilizando métricas como R² e RMSE.
5. **Validação Cruzada**: Aplicação de cross-validation para otimizar o modelo.
6. **Comparação de Modelos**: Comparação dos resultados para determinar o melhor modelo.
7. **Previsão de Valores**: Criação de um DataFrame com características de um imóvel específico usando PySpark e previsão do valor necessário para a compra desse imóvel com o modelo escolhido.

O objetivo final é identificar o modelo de regressão mais preciso para prever valores imobiliários e aplicá-lo para calcular o valor de um imóvel com base em suas características.

**Lembrete**: O conjunto de dados se chama `imoveis.json` e está localizado na pasta `data`. É necessário atualizar o caminho de leitura do arquivo no código para garantir que o arquivo seja lido corretamente.
