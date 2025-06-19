# 🗂️ Kanban do Projeto — Warp Waste Classification

## 🔖 Legenda dos Status nas Etapas do Projeto

| Símbolo      | Status da Etapa                                  | Significado                                                                                     |
|---------------|--------------------------------------------------|-------------------------------------------------------------------------------------------------|
| `[ ]`         | **Não iniciada**                                | Nenhuma tarefa da etapa foi iniciada.                                                           |
| `[~]` ou `[-]`| **Em andamento**                                | A etapa possui tarefas em progresso, mas não está totalmente concluída.                         |
| `[✔]`         | **Concluída**                                   | Todas as tarefas da etapa foram finalizadas e entregues.                                        |

---

## 🚀 Etapas do Projeto

- [ ] **ET-01 — Análise do Dataset**  
➡️ Preparar o dataset, garantindo sua qualidade, consistência, organização e integridade para uso na modelagem.  
✔️ **Inclui:** Download, organização, verificação de integridade, análise de metadados, remoção de duplicatas e análise da distribuição das classes.

- [ ] **ET-02 — Modelagem Base e Melhorias**  
➡️ Implementar modelos da literatura como baseline, propor melhorias, ajustar hiperparâmetros e desenvolver modelos próprios.  
✔️ **Inclui:** Execução de modelos da literatura, avaliação de resultados, ajustes finos, desenvolvimento de modelos próprios e comparação de performances.

- [ ] **ET-03 — Avaliação, Conclusões e Entrega**  
➡️ Avaliar o desempenho dos modelos, gerar relatórios, documentar resultados e preparar os materiais finais para apresentação e entrega.  
✔️ **Inclui:** Consolidação de metodologia, gráficos, tabelas, análise final dos resultados, preparação dos slides, organização dos arquivos e atualização do README.

---

## 🔖 Legenda dos Status das Tarefas
| Status            | Descrição                                                               |
|-------------------|-------------------------------------------------------------------------|
| 🔄 **Backlog**     | Tarefas planejadas, aguardando priorização ou início.                   |
| 🟩 **To Do**       | Tarefas selecionadas para o sprint atual, prontas para serem iniciadas. |
| 🏗️ **In Progress** | Tarefas que estão em desenvolvimento.                                  |
| 🔍 **Review/Test** | Tarefas em revisão de código, testes ou validação. (Opcional)          |
| ✅ **Done**        | Tarefas concluídas.                                                     |

---

## 📌 Status das Tarefas

| ID    | Status     | Etapa  | Tarefa                                         | Descrição                                                                                               | Início     | Entrega    | Responsável | Prioridade |
|-------|------------|--------|------------------------------------------------|---------------------------------------------------------------------------------------------------------|------------|------------|-------------|------------|
| 01.1  | 🔄 Backlog | ET-01  | Baixar e organizar o dataset                   | Fazer download do dataset no Kaggle, criar a estrutura de pastas, organizar imagens e metadados na pasta `/data`. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 01.2  | 🔄 Backlog | ET-01  | Verificar integridade dos arquivos             | Validar se todas as imagens listadas nos metadados existem na pasta e vice-versa, garantindo consistência. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 01.3  | 🔄 Backlog | ET-01  | Verificar formatos de imagem                   | Verificar e padronizar todos os arquivos de imagem para um único formato (.jpg ou .png) para evitar erros no pipeline. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 01.4  | 🔄 Backlog | ET-01  | Analisar consistência dos metadados            | Realizar limpeza dos metadados, verificando campos nulos, dados fora do padrão e corrigindo inconsistências. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 01.5  | 🔄 Backlog | ET-01  | Verificar qualidade das imagens                | Detectar e remover imagens corrompidas, danificadas, com má resolução ou que não atendem ao padrão esperado. | DD/MM/2025 | DD/MM/2025 |             | Média      |
| 01.6  | 🔄 Backlog | ET-01  | Analisar distribuição das classes              | Gerar gráficos para verificar o balanceamento entre as classes (ex.: papel, plástico, vidro, metal) e identificar desequilíbrios. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 01.7  | 🔄 Backlog | ET-01  | Identificar imagens duplicadas                 | Realizar análise de similaridade e hashing para detectar e remover imagens duplicadas que possam enviesar o modelo. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 01.8  | 🔄 Backlog | ET-01  | Documentar análise do dataset                  | Documentar todos os passos da análise de dados (EDA) em notebook e criar slides para apresentação da etapa. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 01.9  | 🔄 Backlog | ET-01  | Atualizar README da pasta `/data`              | Criar ou atualizar o README da pasta `/data` com informações de organização, estrutura dos dados e orientações para uso. | DD/MM/2025 | DD/MM/2025 |             | Média      |
| 02.1  | 🔄 Backlog | ET-02  | Pesquisar modelos da literatura                | Levantar modelos, arquiteturas, técnicas e melhores práticas utilizadas em problemas similares de classificação de imagens. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 02.2  | 🔄 Backlog | ET-02  | Implementar modelo baseline                    | Implementar um modelo simples de classificação (ex.: CNN básica) para servir de referência e benchmarking inicial. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 02.3  | 🔄 Backlog | ET-02  | Testar mais de um modelo da literatura         | Implementar pelo menos dois modelos da literatura (ex.: MobileNet, ResNet, EfficientNet) para comparação de performance. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 02.4  | 🔄 Backlog | ET-02  | Avaliar resultados dos modelos                 | Avaliar os modelos usando métricas como acurácia, precisão, recall, F1-Score, matriz de confusão e curvas ROC/AUC. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 02.5  | 🔄 Backlog | ET-02  | Propor melhorias na arquitetura                | Projetar uma arquitetura mais otimizada, leve e eficiente para reduzir custo computacional e tempo de treino, mantendo a acurácia. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 02.6  | 🔄 Backlog | ET-02  | Ajuste de hiperparâmetros                      | Realizar tuning dos hiperparâmetros utilizando GridSearch, RandomSearch ou técnicas avançadas como Bayesian Optimization. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 02.7  | 🔄 Backlog | ET-02  | Testar redução do dataset                      | Realizar testes para verificar se é possível reduzir o tamanho do dataset sem perda significativa de desempenho no modelo. | DD/MM/2025 | DD/MM/2025 |             | Média      |
| 02.8  | 🔄 Backlog | ET-02  | Implementar modelo próprio                     | Desenvolver um modelo proprietário, combinando elementos dos modelos anteriores, técnicas de regularização e data augmentation. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 02.9  | 🔄 Backlog | ET-02  | Comparar baseline x modelo próprio             | Construir uma análise comparativa usando gráficos, tabelas de métricas e matriz de confusão entre o baseline e o modelo próprio. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 02.10 | 🔄 Backlog | ET-02  | Documentar metodologia e resultados            | Elaborar notebook técnico, README detalhado e slides apresentando toda a metodologia, modelos testados e resultados obtidos. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 03.1  | 🔄 Backlog | ET-03  | Consolidar metodologia final                   | Compilar o pipeline completo (dados, pré-processamento, modelos, tuning, resultados) e descrever formalmente a metodologia adotada. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 03.2  | 🔄 Backlog | ET-03  | Gerar gráficos e tabelas                       | Gerar gráficos de desempenho, matriz de confusão e tabelas com métricas comparativas dos modelos desenvolvidos. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 03.3  | 🔄 Backlog | ET-03  | Analisar e discutir resultados                 | Realizar uma análise crítica dos resultados obtidos, identificando pontos fortes, limitações e possíveis melhorias. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 03.4  | 🔄 Backlog | ET-03  | Elaborar conclusões e próximos passos          | Escrever conclusões do projeto, principais aprendizados, limitações e sugestões para trabalhos futuros ou melhorias. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 03.5  | 🔄 Backlog | ET-03  | Preparar slides da apresentação final          | Criar uma apresentação clara, objetiva e bem estruturada para exposição dos resultados, metodologia e aprendizados. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 03.6  | 🔄 Backlog | ET-03  | Atualizar README.md do repositório             | Atualizar o README principal do repositório com detalhes sobre o projeto, execução, resultados e contribuições. | DD/MM/2025 | DD/MM/2025 |             | Alta       |
| 03.7  | 🔄 Backlog | ET-03  | Organizar a pasta `/docs`                      | Organizar toda a documentação, incluindo notebooks, apresentações, gráficos e relatórios finais. | DD/MM/2025 | DD/MM/2025 |             | Média      |
| 03.8  | 🔄 Backlog | ET-03  | Verificar branch correta e enviar link do projeto | Garantir que o projeto esteja na branch correta (`main`, `final`, ou conforme instruído) e gerar link público do GitHub. | DD/MM/2025 | DD/MM/2025 |             | Alta       |

---

## 💡 Atividades Contínuas e Suporte Ágil

| ID   | Tarefa                                      | Descrição                                                                                                                                                      | Prioridade |
|------|---------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| C.01 | Checkpoint semanal                          | Realizar reuniões semanais para revisar o progresso, identificar bloqueios e replanejar atividades, se necessário.                                            | Alta       |
| C.02 | Branches separadas + revisão antes da main  | Cada membro deve criar uma branch no padrão `tarefa-{ID}-{nome}` (ex.: `tarefa-02.2-francis`). Nenhuma alteração deve ser feita diretamente na `main`. Após concluir a tarefa e validação da equipe, integrar na branch `main`. | Alta       |
| C.03 | Atualizar o quadro Kanban                   | Manter o quadro Kanban atualizado, movendo as tarefas entre os status: Backlog → To Do → In Progress → Review/Test → Done.                                    | Alta       |

---
