# 🛒 Análise de Comportamento e Conversão em E-commerce

**Tecnologias Utilizadas:** Python, Pandas, Numpy, Matplotlib, Seaborn.

## 📌 Contexto do Projeto
[cite_start]Este projeto analisa o comportamento de usuários em uma plataforma de e-commerce multi-categoria para identificar gargalos técnicos e padrões de consumo que afetam a conversão final[cite: 30]. [cite_start]O dataset utilizado simula logs reais de sistema, apresentando desafios comuns de limpeza e integridade de dados[cite: 38].

## 🧹 Etapas de Limpeza e Tratamento de Dados
Para garantir a confiabilidade da análise, realizei os seguintes procedimentos de ETL (Extração, Transformação e Carga):
* [cite_start]**Tratamento de Missing Values**: Imputação de dados ausentes em colunas financeiras (`valor_pedido`) e técnicas utilizando a mediana, preservando a integridade da amostra[cite: 35].
* [cite_start]**Padronização de Categorias**: Uniformização de nomenclaturas de dispositivos e canais de tráfego para evitar redundâncias[cite: 35].
* [cite_start]**Correção de Anomalias**: Ajuste de registros de horários impossíveis (ex: 26:30) e remoção de valores negativos corrompidos[cite: 35].
* [cite_start]**Análise de Outliers**: Identificação e isolamento de transações com valores extremos (acima de R$ 900,00) via método IQR para evitar distorções no ticket médio[cite: 35].

## 📊 Engenharia de Atributos
Criei novas variáveis para facilitar a visualização de insights de negócio:
* [cite_start]**`faixa_faturamento`**: Segmentação de pedidos em Baixo, Médio e Alto valor[cite: 35].
* **`performance_site`**: Classificação do tempo de carregamento em Rápido, Normal ou Lento[cite: 35].
* **`periodo_dia`**: Agrupamento de sessões por turnos (Manhã, Tarde, Noite) para análise de pico de vendas[cite: 35].

## 💡 Principais Insights e Conclusões
* **Impacto Técnico**: Confirmamos que tempos de carregamento superiores a 5 segundos impactam negativamente o engajamento e a conversão do usuário[cite: 30, 42].
* [cite_start]**Comportamento de Compra**: Identificamos que o uso de cupons de desconto está fortemente atrelado ao aumento do volume total do carrinho (Ticket Médio)[cite: 43].
* **Relacionamento de Variáveis**: O tempo de navegação na página não apresenta correlação linear forte com o valor gasto, indicando que clientes decididos compram de forma mais objetiva.

## 🚀 Recomendações Sugeridas
1. [cite_start]**Otimização de Performance**: Focar na redução do tempo de carregamento em dispositivos móveis, visando melhorar o score de qualidade da visita[cite: 30].
2. [cite_start]**Ajuste de Backend**: Implementar validações de entrada para impedir a gravação de logs de horários inconsistentes no banco de dados[cite: 35, 38].
3. **Estratégia de Marketing**: Priorizar campanhas e disparos de e-mail no período da tarde, identificado como o horário de maior conversão real.