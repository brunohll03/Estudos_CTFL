# SIMULADO CTFL 4.0 – FUNDAMENTOS DE TESTE (20 questões)

## Instruções

- Conteúdo: Capítulo 1, itens 1.1 a 1.5.3.
- Dificuldade: difícil.
- Níveis cognitivos: K1 e K2.
- Quatro alternativas (A, B, C e D), com apenas uma correta.
- Tempo sugerido: 30 minutos.
- Gabarito comentado no final.

---

## QUESTÕES

### 1. O que é teste?

Durante a validação de um sistema bancário, o gerente afirma: “Se todos os testes planejados forem aprovados, poderemos garantir que o sistema não possui defeitos”. Qual resposta está MAIS alinhada aos objetivos dos testes?

A) A aprovação dos testes comprova a ausência de defeitos nas funcionalidades verificadas.  
B) Os testes podem reduzir riscos e aumentar a confiança na qualidade, mas não demonstram ausência de defeitos.  
C) O principal objetivo é corrigir todos os defeitos identificados antes da liberação.  
D) Os testes asseguram a qualidade do produto, desde que todos os requisitos tenham sido cobertos.

---

### 2. Teste e depuração

Um teste automatizado identificou um valor incorreto no cálculo de juros. O desenvolvedor reproduziu a falha, localizou uma condição errada no código, corrigiu-a e executou um teste para verificar o resultado. Qual atividade caracteriza especificamente a depuração?

A) Executar o teste que revelou inicialmente o cálculo incorreto.  
B) Registrar a diferença entre resultado esperado e resultado obtido.  
C) Reexecutar o caso de teste após disponibilizada a correção.  
D) Investigar a causa do comportamento incorreto e eliminar o defeito correspondente.

---

### 3. Verificação e validação

Uma equipe desenvolveu um módulo exatamente conforme a especificação aprovada. Entretanto, durante a avaliação, os usuários perceberam que o módulo não atendia ao fluxo necessário para suas atividades diárias. Qual conclusão é a MAIS apropriada?

A) A verificação pode ter sido satisfeita, mas a validação revelou inadequação às necessidades dos usuários.  
B) A validação foi satisfeita porque o software corresponde integralmente à especificação.  
C) A verificação falhou necessariamente, pois qualquer insatisfação do usuário é um defeito de implementação.  
D) Nenhuma conclusão é possível, pois testes não abrangem avaliação de necessidades de negócio.

---

### 4. Por que os testes são necessários?

Em um sistema hospitalar, um defeito de cálculo poderia resultar em uma dose incorreta de medicamento. A equipe decide priorizar testes nessa funcionalidade. Qual justificativa é a MAIS consistente com o syllabus?

A) Todas as funcionalidades devem receber esforço de teste idêntico para evitar viés.  
B) O número de linhas de código determina, isoladamente, quais funcionalidades devem ser mais testadas.  
C) O potencial impacto de uma falha justifica maior atenção aos testes e à redução de riscos.  
D) A criticidade do sistema permite demonstrar formalmente que não existem defeitos.

---

### 5. QA e testes

Uma empresa utiliza revisões de processo, padrões de desenvolvimento e auditorias para reduzir a introdução de defeitos. Paralelamente, executa testes sobre o produto. Qual alternativa descreve CORRETAMENTE essa relação?

A) QA é uma atividade exclusivamente de detecção de defeitos, enquanto testes são preventivos.  
B) QA e testes são sinônimos, pois ambos exigem executar o software.  
C) Os testes substituem QA quando o percentual de casos aprovados é suficientemente alto.  
D) QA é orientada a processos e à prevenção, enquanto testes são uma forma de controle de qualidade orientada ao produto.

---

### 6. Causa raiz, erro, defeito e falha

Um desenvolvedor interpretou incorretamente uma regra tributária porque recebeu treinamento insuficiente. Ele implementou uma fórmula errada e, durante a execução, o sistema calculou imposto abaixo do valor esperado. Qual sequência representa MELHOR os acontecimentos?

A) Defeito → causa raiz → falha → erro.  
B) Causa raiz → erro humano → defeito → falha.  
C) Erro humano → falha → causa raiz → defeito.  
D) Causa raiz → defeito → erro humano → falha.

---

### 7. Princípios de teste

Após executar 800 casos de teste sem encontrar novos defeitos, a equipe concluiu que o sistema não apresentará falhas em produção. Qual princípio de teste contraria DIRETAMENTE essa conclusão?

A) Os testes mostram a presença, não a ausência de defeitos.  
B) Os testes dependem do contexto.  
C) Os defeitos se agrupam.  
D) A falácia da ausência de erros.

---

### 8. Testes exaustivos

Uma API recebe três parâmetros: tipo de cliente (5 valores), região (20 valores) e código promocional (10.000 valores). O gerente solicita testar todas as combinações, mas o prazo é limitado. Qual estratégia está MAIS alinhada aos princípios de teste?

A) Executar exclusivamente os casos positivos, porque representam o uso esperado.  
B) Manter todas as combinações e eliminar verificações dos resultados para reduzir tempo.  
C) Selecionar testes com base em riscos, técnicas de teste e prioridades, reconhecendo a inviabilidade prática da exaustividade.  
D) Executar combinações aleatórias até não aparecerem novos defeitos, considerando então a cobertura integral.

---

### 9. Paradoxo do pesticida

Durante seis meses, uma equipe executou os mesmos testes de regressão, sem modificações. Embora novos defeitos tenham surgido em produção, a suíte continuou apresentando resultados satisfatórios. Qual ação responde MELHOR a esse problema?

A) Executar os mesmos testes mais vezes, sem alterar entradas nem condições.  
B) Excluir os testes antigos porque sua repetição deixa de agregar qualquer valor.  
C) Aumentar somente o número de execuções paralelas da suíte existente.  
D) Revisar e atualizar testes e dados, criando novos casos para explorar condições ainda não verificadas.

---

### 10. Ausência de erros

Uma aplicação de agendamento passou por extensos testes e apresentou poucos defeitos. Após o lançamento, os usuários rejeitaram o produto porque ele não oferecia a funcionalidade central de que necessitavam. Qual princípio é MAIS bem exemplificado?

A) Agrupamento de defeitos.  
B) Falácia da ausência de erros.  
C) Teste antecipado economiza tempo e dinheiro.  
D) Os testes dependem do contexto.

---

### 11. Atividades de teste

Uma analista examina histórias de usuário e critérios de aceitação, identifica funcionalidades testáveis, encontra ambiguidades e registra condições de teste, sem ainda definir os casos detalhados. Qual atividade está sendo executada PRINCIPALMENTE?

A) Análise de teste.  
B) Modelagem de teste.  
C) Implementação de teste.  
D) Execução de teste.

---

### 12. Modelagem e implementação

Uma equipe já definiu os casos de teste para uma API. Agora organiza esses casos em procedimentos executáveis, prepara massas de dados, configura o ambiente e monta a suíte para execução. Qual atividade predomina?

A) Análise de teste, porque os requisitos ainda podem conter ambiguidades.  
B) Modelagem de teste, porque o trabalho continua vinculado aos casos de teste.  
C) Conclusão de teste, porque os casos já foram especificados.  
D) Implementação de teste, porque estão sendo preparados procedimentos, dados e ambiente para execução.

---

### 13. Monitoramento e controle

Durante uma sprint, o QA identifica que apenas 40% dos testes planejados foram executados, embora o objetivo fosse alcançar 80% nessa data. O líder decide redistribuir recursos e priorizar cenários críticos. Como classificar as duas atividades, respectivamente?

A) Controle de teste e planejamento de teste.  
B) Análise de teste e modelagem de teste.  
C) Monitoramento de teste e controle de teste.  
D) Execução de teste e conclusão de teste.

---

### 14. Processo de teste no contexto

Duas equipes desenvolvem sistemas com tecnologias e riscos diferentes: uma cria um aplicativo de entretenimento; a outra, software médico sujeito a exigências regulatórias. Qual afirmação é a MAIS adequada?

A) Ambas devem executar o mesmo processo de teste, com procedimentos e documentação idênticos.  
B) O processo e o rigor dos testes devem ser adaptados aos riscos, requisitos regulatórios e demais fatores do contexto.  
C) O projeto médico dispensa testes exploratórios porque possui documentação formal.  
D) O aplicativo de entretenimento não necessita de atividades de planejamento e conclusão de testes.

---

### 15. Testware

Em um projeto, são produzidos um plano de teste, condições de teste, casos de teste, scripts de execução e um relatório de conclusão. Qual interpretação está CORRETA?

A) Todos podem ser considerados testware, pois são produtos de trabalho gerados durante atividades de teste.  
B) Somente scripts automatizados são considerados testware, porque executam testes.  
C) Apenas casos e dados de teste são testware; planos e relatórios são documentos de gestão externos ao processo.  
D) Testware corresponde exclusivamente aos produtos de trabalho criados após a execução dos testes.

---

### 16. Rastreabilidade

Após uma mudança em um requisito de autenticação, o QA precisa identificar quais condições de teste, casos e resultados estão relacionados à regra alterada. Qual prática oferece o benefício MAIS direto?

A) Aumentar a quantidade de casos de teste sem relacioná-los aos requisitos.  
B) Guardar somente o relatório final de execução, sem referência às condições verificadas.  
C) Concentrar a rastreabilidade no relacionamento entre defeitos e desenvolvedores responsáveis.  
D) Manter rastreabilidade entre base de teste, testware e resultados, permitindo análise de impacto e avaliação da cobertura.

---

### 17. Papéis no teste

Em um projeto, uma pessoa define a estratégia, planeja recursos e acompanha os testes; outra analisa requisitos, modela casos, implementa procedimentos e executa testes. Qual associação é a MAIS adequada?

A) A primeira exerce exclusivamente atividades de depuração; a segunda, de gerenciamento.  
B) A primeira atua no gerenciamento de testes; a segunda, na função de teste.  
C) Ambas exercem obrigatoriamente o mesmo papel porque pertencem à área de QA.  
D) A primeira realiza apenas garantia da qualidade; a segunda é responsável por toda a qualidade do produto.

---

### 18. Habilidades essenciais

Um QA identifica um possível defeito crítico, mas não consegue reproduzi-lo consistentemente. O desenvolvedor discorda da classificação de gravidade e o prazo de entrega está próximo. Qual combinação de habilidades oferece a abordagem MAIS adequada?

A) Insistência na própria avaliação, conhecimento técnico e comunicação exclusivamente por relatórios.  
B) Capacidade de execução rápida, independência absoluta e redução da interação com desenvolvedores.  
C) Pensamento crítico, conhecimento técnico, comunicação construtiva e colaboração para investigar as evidências.  
D) Habilidade de negociação para retirar o defeito do escopo e preservar o cronograma.

---

### 19. Abordagem de equipe completa

Em uma equipe ágil, desenvolvedores, analistas de negócio e testadores colaboram na definição de critérios de aceitação e na prevenção de problemas desde o início. Qual benefício caracteriza MELHOR a abordagem de equipe completa?

A) A qualidade passa a ser responsabilidade compartilhada, com melhor comunicação e aproveitamento das diferentes competências.  
B) A independência total dos testadores torna-se obrigatória para todas as decisões técnicas.  
C) Os testadores deixam de executar testes e passam a se dedicar somente aos requisitos.  
D) Os desenvolvedores passam a ser os únicos responsáveis por definir os critérios de aceitação.

---

### 20. Independência dos testes

Uma organização considera transferir todos os testes para uma equipe externa, acreditando que isso eliminará os vieses e garantirá a identificação de todos os defeitos. Qual avaliação está MAIS alinhada ao CTFL 4.0?

A) A independência externa elimina vieses cognitivos e torna desnecessários os testes feitos pelos desenvolvedores.  
B) A independência sempre prejudica a qualidade porque testadores externos não conhecem a implementação.  
C) Uma equipe independente assume integralmente a responsabilidade pela qualidade e evita conflitos com os desenvolvedores.  
D) A independência pode trazer novas perspectivas, mas também gerar isolamento, problemas de comunicação e perda do senso de responsabilidade dos desenvolvedores.

---

## GABARITO COMENTADO

| # | Resp. | Explicação |
|---|:---:|---|
| 1 | **B** | Testar contribui para avaliar a qualidade, reduzir riscos e identificar defeitos ou falhas, mas não prova a ausência de defeitos. |
| 2 | **D** | Depuração envolve localizar, analisar e eliminar as causas de falhas; detecção e confirmação da correção são atividades de teste. |
| 3 | **A** | Verificação avalia conformidade com requisitos especificados; validação, adequação às necessidades dos usuários. |
| 4 | **C** | Funcionalidades cujas falhas têm impacto grave justificam atenção proporcional aos riscos. |
| 5 | **D** | QA concentra-se nos processos e na prevenção; testes integram o controle de qualidade e avaliam o produto. |
| 6 | **B** | Treinamento insuficiente (causa raiz) → interpretação incorreta (erro humano) → fórmula incorreta (defeito) → cálculo errado em execução (falha). |
| 7 | **A** | Mesmo centenas de testes bem-sucedidos não demonstram que o sistema está livre de defeitos. |
| 8 | **C** | Testes exaustivos costumam ser inviáveis; usar riscos, técnicas de teste e prioridades permite selecionar cenários relevantes. |
| 9 | **D** | Testes repetidos sem atualização podem perder capacidade de revelar novos defeitos; revisar e ampliar os cenários é recomendado. |
| 10 | **B** | Um produto com poucos defeitos ainda pode ser inadequado se não atender às necessidades reais. |
| 11 | **A** | A análise de teste identifica e prioriza condições de teste com base na análise dos requisitos. |
| 12 | **D** | Implementação de teste prepara procedimentos, suítes, dados e ambiente para execução. |
| 13 | **C** | Monitoramento compara o progresso com o planejado; controle define ações corretivas diante de desvios. |
| 14 | **B** | O processo de teste é adaptado ao contexto, incluindo riscos, domínio, requisitos regulatórios e restrições. |
| 15 | **A** | Testware compreende produtos de trabalho de teste, entre eles planos, condições, casos, scripts e relatórios. |
| 16 | **D** | Rastreabilidade entre requisitos, testware e resultados apoia análise de impacto e avaliação de cobertura. |
| 17 | **B** | Gerenciamento aborda planejamento e acompanhamento; a função de teste realiza análise, modelagem, implementação e execução. |
| 18 | **C** | Pensamento crítico, conhecimento técnico, comunicação e colaboração favorecem a investigação objetiva de problemas. |
| 19 | **A** | Na abordagem de equipe completa, a qualidade é responsabilidade compartilhada e diferentes competências colaboram. |
| 20 | **D** | A independência traz novas perspectivas, mas pode causar isolamento, dificuldades de comunicação e menor responsabilidade compartilhada. |

---

**Referência:** [Syllabus CTFL 4.0 — BSTQB](https://bstqb.qa/files/syllabus_ctfl_4.0br.pdf). Questões autorais de estudo; não são questões oficiais de exame.
