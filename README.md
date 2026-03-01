# Análise Exploratória de Dados — Consumo Elétrico em Redes AMI

Análise exploratória completa de dados de medidores inteligentes, cobrindo o ciclo completo de tratamento de dados.

Este projeto simula **6 meses de leituras horárias de 50 medidores**, com problemas de qualidade injetados intencionalmente para tornar o tratamento realista.

# 🎯 Objetivos

- Realizar diagnóstico completo de qualidade do dataset
- Aplicar técnicas de limpeza e pré-processamento de dados de séries temporais
- Extrair padrões de consumo por perfil de consumidor, horário e sazonalidade
- Produzir visualizações analíticas para apoio à tomada de decisão
- Documentar o processo e exportar metadados estruturados

# 📈 Análises Realizadas
**Distribuição e perfis**
- Comparação de consumo médio entre perfis Residencial, Comercial e Industrial
- Curvas de densidade (KDE) e boxplots por categoria
**Padrões temporais**
- Perfil horário médio de consumo — identificação de horários de pico
- Heatmap consumo × hora do dia × dia da semana
- Análise de diferença entre dias úteis e fins de semana
**Série temporal**
- Evolução do consumo total diário da rede ao longo dos 6 meses
- Consumo mensal por perfil de consumidor
**Qualidade elétrica**
- Distribuição da tensão nos medidores vs. valor nominal (220V)
- Matriz de correlação entre variáveis numéricas
