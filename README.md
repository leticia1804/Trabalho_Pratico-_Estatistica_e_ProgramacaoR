## ==============================================
## Estatística e Probabilidade Aplicada à Astronomia
## Pós-Graduação em Ciência de Dados - UNICARIOCA
## ==============================================

## Trabalho Prático: Calibração de Brilho em Estrelas Variáveis
---
Aluna: Letícia de Barros dos Santos

Professores Orientadores
- Sérgio Monteiro, D.Sc.
- Manuel Martins, D.Sc.
  
---

## Descrição do Problema
Na astronomia observacional, a medição do brilho aparente de estrelas está sujeita a diversas fontes de ruído, incluindo interferências atmosféricas e limitações instrumentais dos telescópios. Imagine que uma equipe de astrofísicos está monitorando uma estrela específica e sabe que, devido às propriedades físicas do astro, as medições de brilho tendem a seguir uma Distribuição Gaussiana (Normal) em torno de um valor central (μ), com uma variabilidade inerente (σ).

Este projeto propõe a simulação computacional de observações de brilho estelar utilizando a linguagem R. A partir dessas observações, foram aplicadas técnicas de estatística descritiva, inferência estatística e diagnóstico de outliers para avaliar o comportamento das medições astronômicas..
Os resultados indicaram aderência ao modelo gaussiano esperado e demonstraram a importância do tratamento estatístico em análises científicas.

---

## Objetivo
O objetivo é simular um conjunto de 1.000 observações de brilho para esta estrela, realizar uma análise de inferência para estimar se a média observada condiz com o valor teórico esperado e identificar possíveis anomalias nos dados captados.

 # Objetivos Específicos

- Simular 1.000 observações de brilho estelar utilizando distribuição normal;
- Realizar análise estatística descritiva dos dados;
- Construir visualizações gráficas profissionais utilizando `ggplot2`;
- Estimar intervalos de confiança para a média populacional;
- Executar testes de hipótese para validação estatística da média;
- Detectar observações discrepantes (outliers);
- Avaliar o impacto estatístico dos outliers na estimativa final.

## Ferramentas Utilizadas
- Google Colab --Linguagem R

## Etapas Desenvolvidas
- Simulação de dados
- Estatística descritiva
- Histogramas e visualizações
- Intervalo de confiança
- Teste de hipótese
- Diagnóstico de outliers

# Resultados Obtidos

Os resultados demonstraram forte aderência das observações simuladas à distribuição normal teórica esperada para medições astronômicas.

A análise descritiva evidencia a estabilidade estatística dos dados simulados.

O teste de hipótese mostrou que a média amostral não apresentou diferença estatisticamente significativa em relação ao valor teórico estabelecido.

Além disso, a análise de outliers revelou pequena influência de observações extremas na estimativa final da média populacional.

---

## Conclusão
O presente estudo demonstrou a aplicação integrada de técnicas de estatística descritiva, inferência estatística e análise exploratória de dados em um cenário simulado de observação astronômica.

A simulação das medições de brilho estelar apresentou comportamento consistente com uma Distribuição Normal, conforme evidenciado pelas análises gráficas e métricas descritivas.

Os resultados inferenciais indicaram compatibilidade entre a média amostral observada e o parâmetro populacional previamente definido, reforçando a estabilidade estatística do modelo adotado.

Adicionalmente, a identificação de outliers evidenciou a relevância do tratamento de observações discrepantes em aplicações científicas reais, sobretudo em contextos sujeitos a ruídos experimentais e limitações instrumentais.

Dessa forma, o trabalho demonstra como ferramentas estatísticas e computacionais podem contribuir significativamente para a validação e interpretação de dados astronômicos em ambientes de ciência de dados.
