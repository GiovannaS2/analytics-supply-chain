# 📦 Planeamento de Demanda e Análise de Sazonalidade
Este projeto foi desenvolvido com foco em Engenharia de Produção e Supply Chain Intelligence, simulando o cenário logístico de uma fábrica de colecionáveis de alto padrão. O objetivo principal é identificar padrões de venda, mensurar os impactos da sazonalidade e calcular o erro de previsão para estruturar políticas de stock eficientes.

## 🚀 Tecnologias e Ferramentas Utilizadas
- **Python (Pandas & NumPy):** Tratamento da base de dados histórica, modelagem e cálculo estatístico de métricas de erro.
- **Power BI:** Desenvolvimento de um dashboard executivo e dinâmico para suporte à tomada de decisão.
- **Engenharia de Prompt:** Uso estratégico de IA para otimização de scripts e aceleração do desenvolvimento.

## 📊 Principais Descobertas e Insights de Engenharia
1. **Pico Sazonal Agressivo:** Através da análise mensal, identificou-se um aumento acentuado de procura nos meses de novembro (Black Friday) e dezembro (Natal), onde o volume de vendas disparou até 250% em relação à média anual.
2. **O Risco do Fenômeno "Lag" (Atraso):** Ao testar o modelo preditivo de **Média Móvel**, ficou evidente que algoritmos simples falham em antecipar picos repentinos. O modelo gerou previsões severamente abaixo do real para o fim de ano, o que na prática causaria uma **Ruptura de Stock (Stockout)** catastrófica.
3. **Métrica MAD e Dimensionamento de Segurança:** O modelo apresentou um **MAD (Desvio Médio Absoluto) de 53.6 unidades**. Com base nessa volatilidade de erro, determinou-se a necessidade de um **Stock de Segurança Mínimo de 65 a 80 unidades** para proteger o nível de serviço ao cliente sem gerar custos excessivos de armazenagem (*Overstock*).

## 📈 Dashboard Dinâmico (Power BI)
Ao integrar os dados no Power BI, a estrutura permite analisar o comportamento geral da fábrica ou filtrar dinamicamente a curva de tendência para cada produto específico (como a *Escultura de Biscuit Luxo*, líder de vendas anual).


🎨 *Projeto desenvolvido por Giovanna Maria Mazzei Céllia como parte do portfólio técnico de Engenharia e Análise de Dados.*
