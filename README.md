# Comparação de Pipelines de Dados: ETL vs ELT 📊

Este repositório contém uma atividade prática desenvolvida para a disciplina de Engenharia de Dados do curso de Análise e Desenvolvimento de Sistemas (ADS). O objetivo principal é simular e comparar as duas principais abordagens de integração de dados — ETL (Extract, Transform, Load) e ELT (Extract, Load, Transform) — utilizando Python e a biblioteca Pandas.

## 🎯 Objetivos do Projeto

* **Simulação de Fluxos ETL/ELT**: Implementação de pipelines utilizando dados fictícios de vendas e CRM.
* **Análise Crítica**: Avaliar o momento ideal para a transformação de dados em diferentes contextos, como Data Warehouses e ambientes de Big Data.
* **Desempenho**: Medir e comparar o tempo de execução e a latência de cada abordagem.
* **Visualização**: Gerar gráficos comparativos para validar a integridade dos dados transformados.

## 🛠️ Tecnologias Utilizadas

* **Linguagem**: Python 3
* **Manipulação de Dados**: Pandas
* **Visualização**: Matplotlib e Numpy
* **Ambiente**: Google Colab

## 🚀 Como Executar

O projeto foi desenvolvido para rodar diretamente no ambiente do Google Colab:

1. Acesse o arquivo `.ipynb` neste repositório.
2. Clique no botão "Open in Colab" (se disponível).
3. Execute as células sequencialmente para observar a extração, os processos de transformação e os resultados de performance.

## 📈 Resultados Obtidos

Durante o experimento, foram validados os seguintes pontos:
* **Integridade**: Ambas as abordagens resultaram nos mesmos valores calculados (R$ 4.400,00 no total acumulado), garantindo a precisão da lógica de negócio.
* **Performance**: Em baixa escala (amostras pequenas), o ETL demonstrou uma leve vantagem em milissegundos devido ao processamento direto em memória. Contudo, a análise teórica reforça que o ELT é superior em cenários de Big Data devido ao processamento distribuído no destino.

## 📝 Conclusão

A atividade demonstrou que enquanto o ETL é ideal para garantir a qualidade e consistência estrita dos dados antes da carga final, o ELT oferece a flexibilidade necessária para ambientes modernos, permitindo correções ágeis e preservação do histórico bruto dos dados.

---
**Autor:** Lucas da Costa Souza  
**Curso:** Análise e Desenvolvimento de Sistemas (ADS)
