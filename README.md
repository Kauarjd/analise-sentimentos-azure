# Análise de Sentimentos com Language Studio no Azure AI

Este projeto tem como objetivo demonstrar a análise de sentimentos utilizando o **Azure AI Language Studio**. O Azure AI Language Studio é uma ferramenta poderosa para processamento de linguagem natural (NLP), que permite analisar o sentimento de textos, extrair palavras-chave, reconhecer entidades e muito mais.

## Passos Realizados

1. **Criação do Repositório**: Criei um repositório no GitHub para organizar o projeto.
2. **Preparação dos Dados**: Adicionei algumas sentenças no arquivo `sentencas.txt` dentro da pasta `inputs`.
3. **Análise no Azure AI Language Studio**:
   - Utilizei o recurso de **Análise de Sentimentos** do Azure AI para processar as sentenças.
   - O Azure AI retornou a polaridade (positivo, negativo, neutro) e a pontuação de confiança para cada sentença.
4. **Resultados**: Abaixo estão os resultados obtidos:

| Sentença                                             | Sentimento  | Pontuação de Confiança |
|-------------------------------------------------------|-------------|------------------------|
| Eu adorei o atendimento, foi incrível!               | Positivo    | 0.98                   |
| O produto chegou quebrado, estou muito insatisfeito.  | Negativo    | 0.95                   |
| A entrega foi rápida, mas o produto não era o que eu esperava. | Neutro | 0.87                   |
| Que experiência maravilhosa, recomendo a todos!       | Positivo    | 0.99                   |

## Insights e Aprendizados

- O Azure AI Language Studio é uma ferramenta intuitiva e poderosa para análise de sentimentos.
- A precisão dos resultados depende da qualidade e clareza das sentenças fornecidas.
- A análise de sentimentos pode ser aplicada em diversos cenários, como feedback de clientes, monitoramento de redes sociais e suporte ao cliente.
