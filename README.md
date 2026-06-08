# mvp-cep-concreto
## Sobre o projeto
MVP desenvolvido para a disciplina de Controle Estatístico de 
Processos. Aplica ferramentas de CEP e Machine Learning ao dataset 
de resistência à compressão do concreto (UCI Repository) para 
monitorar a qualidade do processo produtivo, detectar anomalias 
e identificar as variáveis que causam oscilações na resistência.

## Estrutura do notebook

| Parte | Conteúdo |
|-------|----------|
| Parte 1 | Análise exploratória — estatísticas, correlações, normalidade |
| Parte 2 | Cartas de Controle I e MR com detecção de anomalias (Regras de Nelson) |
| Parte 3 | Análise de capacidade do processo (Cp, Cpk — ABNT NBR 12655) |
| Parte 4 | Modelos ML para identificar variáveis discrepantes e simular cenários |
| Parte 5 | Relatório final consolidado com recomendações |

## Dataset
- Fonte: UCI Machine Learning Repository
- Conteúdo: 1030 experimentos de resistência à compressão do concreto
- Variáveis: cimento, escória, cinza volante, água, 
  superplastificante, agregado graúdo, agregado miúdo, idade
- Variável alvo: resistência à compressão (MPa)
- Norma de referência: ABNT NBR 5739 (ensaios aos 28 dias)

## Como executar
1. Abra o arquivo MVP_CEP_Concreto.ipynb no Google Colab
2. Execute Runtime > Run all
3. Os gráficos e o relatório são gerados automaticamente

## Bibliotecas
- pandas, numpy — manipulação de dados
- matplotlib, seaborn — visualizações
- scipy — testes estatísticos
- scikit-learn — modelos de Machine Learning

## Principais resultados
- Status do processo: [preencher após rodar]
- Anomalias detectadas: [X] pontos sinalizados de 419
- Cpk do processo: [preencher após rodar]
- Variáveis mais críticas: [preencher após rodar]
