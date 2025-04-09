# Regressão para Marketing

## 📌 Visão Geral do Projeto
Este projeto analisa a relação entre investimentos em diferentes canais de publicidade (YouTube, Facebook e Jornais) e o retorno em vendas para uma empresa de e-commerce. Utilizamos técnicas de análise de dados e modelagem preditiva para identificar os canais mais eficientes e prever o retorno sobre o investimento (ROI).

## 🎯 Objetivos
- Identificar quais canais de marketing têm maior impacto nas vendas.
- Desenvolver um modelo preditivo para estimar vendas baseadas nos investimentos.
- Fornecer insights estratégicos para otimização do orçamento de marketing.

## 📊 Dados
O conjunto de dados contém informações históricas de investimentos e vendas:

| Coluna     | Descrição                          | Tipo de Dado  |
|------------|------------------------------------|---------------|
| youtube    | Valor investido no YouTube ($)     | Numérico      |
| facebook   | Valor investido no Facebook ($)    | Numérico      |
| newspaper  | Valor investido em Jornais ($)     | Numérico      |
| sales      | Valor total de vendas gerado ($)   | Numérico      |

## 🛠️ Ferramentas Utilizadas
- **SQL**: Para consulta e manipulação inicial dos dados
- **Python**: Para análise e modelagem
  - Bibliotecas: Pandas, NumPy, Matplotlib, Seaborn
- **Python Graph Gallery**: Para visualizações avançadas
- **SciKit Learn**: Para construção de modelos de machine learning
- **Google Colab**: Ambiente de desenvolvimento

## 📈 Metodologia

### Etapa 01: Análise Descritiva
- Estatísticas descritivas básicas (média, mediana, desvio padrão)
- Distribuição dos investimentos por canal
- Correlação entre investimentos e vendas

### Etapa 02: Análise Exploratória
- Visualização das relações entre variáveis

   ![image](https://github.com/user-attachments/assets/6862b395-9087-4e55-880c-c41e7dfe1bf1)
  
- Identificação de outliers e padrões
- Análise de distribuição conjunta

### Etapa 03: Modelagem
- Separação em conjuntos de treino e teste
- Teste de múltiplos algoritmos de regressão:
  - Regressão Linear Múltipla
  - Random Forest
  - Gradient Boosting
- Avaliação de desempenho com métricas:
  - R²
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Square Error)

### Etapa 04: Cálculo de Predições
- Aplicação do modelo escolhido para fazer previsões
- Criação de cenários hipotéticos de investimento
- Cálculo do ROI esperado para cada canal

## 📌 Principais Resultados
- [Inserir conclusões principais sobre qual canal tem melhor ROI]
- [Inserir precisão do modelo escolhido]
- [Inserir recomendações estratégicas]

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/renantorres0/Regressao_Marketing.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd Regressao_Marketing
   ```
3. Execute o notebook principal

## 🤝 Contribuição
Contribuições são bem-vindas! Siga esses passos:
1. Faça um fork do projeto
2. Crie sua branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some amazing feature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## ✉️ Contato
Renan Torres - nantorres0@gmail.com
