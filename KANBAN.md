# 🗂️ Kanban do Projeto — Warp Waste Classification

## 🚀 Etapas do Projeto
- **ET-01 — Análise do Dataset**
- **ET-02 — Modelagem Base e Melhorias**
- **ET-03 — Avaliação, Conclusões e Entrega**

---

## 🔖 Legenda dos Status
| Status            | Descrição                                                                 |
|-------------------|---------------------------------------------------------------------------|
| 🔄 **Backlog**     | Todas as tarefas inicialmente planejadas (ainda não priorizadas)         |
| 🟩 **To Do**       | Tarefas selecionadas para o sprint atual, prontas para começar           |
| 🏗️ **In Progress** | Tarefas em desenvolvimento, em andamento                                |
| 🔍 **Review/Test** | (Opcional) Tarefas que estão em revisão de código, testes ou validação   |
| ✅ **Done**        | Tarefas concluídas                                                       |

---

## 📌 Status das Tarefas

| ID    | Status        | Etapa  | Tarefa                                              | Descrição                                                                                      | Responsável | Prioridade |
|-------|----------------|--------|-----------------------------------------------------|------------------------------------------------------------------------------------------------|-------------|------------|
| 01.1  | 🔄 Backlog     | ET-01  | Baixar e organizar o dataset                       | Fazer download no Kaggle e estruturar na pasta /data                                           |             | Alta       |
| 01.2  | 🔄 Backlog     | ET-01  | Verificar integridade dos arquivos                 | Conferir se todas as imagens e metadados existem e estão corretos                             |             | Alta       |
| 01.3  | 🔄 Backlog     | ET-01  | Verificar formatos de imagem                       | Garantir que todas as imagens estejam no mesmo formato (.jpg, .png)                           |             | Alta       |
| 01.4  | 🔄 Backlog     | ET-01  | Analisar consistência dos metadados                | Checar se há valores ausentes, inconsistentes ou fora do padrão                               |             | Alta       |
| 01.5  | 🔄 Backlog     | ET-01  | Verificar qualidade das imagens                    | Detectar imagens corrompidas ou inutilizáveis                                                 |             | Média      |
| 01.6  | 🔄 Backlog     | ET-01  | Analisar distribuição das classes                  | Verificar se as classes estão balanceadas ou há desequilíbrios                                |             | Alta       |
| 01.7  | 🔄 Backlog     | ET-01  | Identificar imagens duplicadas                     | Remover duplicatas para não enviesar o modelo                                                 |             | Alta       |
| 01.8  | 🔄 Backlog     | ET-01  | Documentar análise do dataset (notebook e slides)  | Criar notebook e slides sobre a análise feita                                                 |             | Alta       |
| 01.9  | 🔄 Backlog     | ET-01  | Atualizar README da pasta `/data`                  | Inserir orientações de organização e uso dos dados                                            |             | Média      |
| 02.1  | 🔄 Backlog     | ET-02  | Pesquisar modelos da literatura                    | Investigar notebooks relacionados no Kaggle e artigos científicos                             |             | Alta       |
| 02.2  | 🔄 Backlog     | ET-02  | Implementar modelo baseline                        | Executar um modelo já validado na comunidade para ter uma referência                          |             | Alta       |
| 02.3  | 🔄 Backlog     | ET-02  | Testar mais de um modelo da literatura             | Executar 2 ou mais abordagens da literatura                                                   |             | Alta       |
| 02.4  | 🔄 Backlog     | ET-02  | Avaliar resultados dos modelos                     | Calcular métricas: acurácia, F1, precisão, recall, matriz de confusão                         |             | Alta       |
| 02.5  | 🔄 Backlog     | ET-02  | Propor melhorias na arquitetura                    | Sugerir e implementar uma arquitetura mais leve, rápida ou eficiente                          |             | Alta       |
| 02.6  | 🔄 Backlog     | ET-02  | Ajuste de hiperparâmetros                          | Testar tuning: learning rate, batch size, epochs, otimização                                  |             | Alta       |
| 02.7  | 🔄 Backlog     | ET-02  | Testar redução do dataset                          | Avaliar se é possível reduzir o número de imagens sem perder desempenho                       |             | Média      |
| 02.8  | 🔄 Backlog     | ET-02  | Implementar modelo próprio                         | Criar uma arquitetura modificada ou híbrida baseada nos estudos                               |             | Alta       |
| 02.9  | 🔄 Backlog     | ET-02  | Comparar baseline x modelo próprio                 | Gerar gráfico, tabelas e análises comparativas                                                |             | Alta       |
| 02.10 | 🔄 Backlog     | ET-02  | Documentar metodologia e resultados                | Criar notebooks, documentação e slides                                                        |             | Alta       |
| 03.1  | 🔄 Backlog     | ET-03  | Consolidar metodologia final                       | Descrever dataset, pré-processamento, modelos, tuning, resultados                             |             | Alta       |
| 03.2  | 🔄 Backlog     | ET-03  | Gerar gráficos e tabelas                           | Matriz de confusão, comparação de métricas entre modelos                                      |             | Alta       |
| 03.3  | 🔄 Backlog     | ET-03  | Analisar e discutir resultados                     | Apontar vantagens, limitações e possíveis melhorias                                           |             | Alta       |
| 03.4  | 🔄 Backlog     | ET-03  | Elaborar conclusões e próximos passos              | Redigir as conclusões e sugerir próximos passos                                               |             | Alta       |
| 03.5  | 🔄 Backlog     | ET-03  | Preparar slides da apresentação final              | Montar apresentação da etapa ET-03 com metodologia, resultados e conclusões                   |             | Alta       |
| 03.6  | 🔄 Backlog     | ET-03  | Atualizar README.md do repositório                 | Documentar descrição, objetivos, pipeline, execução e autores                                 |             | Alta       |
| 03.7  | 🔄 Backlog     | ET-03  | Organizar a pasta `/docs` com os materiais finais  | Deixar todos os materiais organizados no repositório                                          |             | Média      |
| 03.8  | 🔄 Backlog     | ET-03  | Verificar branch correta e enviar link do projeto  | Checar se está na branch solicitada e enviar link no padrão solicitado                        |             | Alta       |

---

## 💡 Atividades Contínuas e Suporte Ágil
| ID   | Tarefa                                        | Descrição                                                                         | Prioridade |
|------|-----------------------------------------------|-----------------------------------------------------------------------------------|------------|
| C.01 | Checkpoint semanal                            | Verificar avanço coletivo, redefinir prazos, alinhar pendências                   | Alta       |
| C.02 | Utilizar pull requests com revisão de código  | Subir alterações sempre via PR, com revisão e aprovação de colegas                | Alta       |
| C.03 | Atualizar quadro Kanban                       | Movimentar tarefas entre "A fazer", "Fazendo" e "Feito"                           | Alta       |

---
