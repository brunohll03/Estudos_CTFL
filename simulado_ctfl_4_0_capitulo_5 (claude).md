# SIMULADO CTFL 4.0 – Capítulo 5: Gerenciamento das Atividades de Teste (30 questões, nível difícil, estilo prova)

---

## Instruções

- 1 alternativa correta (as demais são distratores plausíveis)
- Nível: K1, K2 e K3, no estilo do exame CTFL (enunciados curtos, cenários, "NÃO é", "melhor", cálculos)
- As questões K3 (estimativa, priorização e relatório de defeitos) exigem cálculo ou aplicação
- Gabarito no final, com o motivo de a correta estar certa e de as outras pegarem

---

## QUESTÕES

### 1. Qual das alternativas NÃO é conteúdo típico de um plano de teste?
A) Registro de riscos, com riscos de produto e de projeto  
B) Abordagem de teste, incluindo níveis, tipos, técnicas, critérios de entrada e saída e independência do teste  
C) Orçamento e cronograma  
D) Lista de defeitos encontrados na execução, com seus status atuais  

---

### 2. Qual atividade do testador é típica do planejamento de ITERAÇÃO, em contraste com o planejamento de liberação?
A) Determinar a abordagem de teste da versão  
B) Participar da escrita de histórias de usuário e de critérios de aceite testáveis  
C) Dividir as histórias em tarefas, especialmente tarefas de teste, e estimar o esforço de todas as tarefas de teste  
D) Participar das análises de risco do projeto e da qualidade  

---

### 3. Qual afirmação sobre critérios de entrada e critérios de saída está correta?
A) Os critérios de entrada definem o que deve ser alcançado para a atividade ser declarada concluída; os de saída definem as condições prévias  
B) O esgotamento do tempo ou do orçamento pode ser um critério de saída válido, se os stakeholders tiverem analisado e aceitado o risco de entrar em operação sem mais testes  
C) Em equipes ágeis, a Definição de Pronto (DoR) corresponde aos critérios de saída e a Definição de Feito (DoD) corresponde aos critérios de entrada  
D) Os critérios de entrada e de saída devem ser definidos uma única vez para todo o projeto, independentemente do nível de teste  

---

### 4. Qual é um critério de ENTRADA típico para iniciar o teste de sistema?
A) Cobertura de ramificação de 85% alcançada  
B) Nenhum defeito crítico pendente de correção  
C) Todos os testes de fumaça (smoke) da build foram aprovados  
D) Todos os testes de regressão foram automatizados  

---

### 5. Em um projeto anterior da organização, a proporção entre o esforço de desenvolvimento e o esforço de teste foi de 5:2. No novo projeto, estima-se um esforço de desenvolvimento de 800 homens/hora. Usando a estimativa baseada em índices, qual é o esforço de teste estimado?
A) 320 homens/hora  
B) 500 homens/hora  
C) 400 homens/hora  
D) 2.000 homens/hora  

---

### 6. O esforço de teste das três últimas iterações de um projeto foi de 30, 42 e 60 horas. A equipe estima o esforço da próxima iteração como a média das três últimas. Qual é a estimativa, e qual é o nome da técnica?
A) 42 horas, por extrapolação  
B) 45 horas, por extrapolação  
C) 60 horas, por estimativa de três pontos  
D) 44 horas, por extrapolação  

---

### 7. Para uma tarefa de teste, os especialistas fizeram as estimativas: otimista (o) = 8, mais provável (m) = 14 e pessimista (p) = 26 homens/hora. Usando a estimativa de três pontos (E = (o + 4m + p)/6 e SD = (p − o)/6), qual é o resultado?
A) E = 16 ± 6 homens/hora  
B) E = 15 ± 3 homens/hora  
C) E = 14 ± 3 homens/hora  
D) E = 15 ± 18 homens/hora  

---

### 8. Em outra tarefa, as estimativas são: otimista = 10, mais provável = 16 e pessimista = 34 homens/hora. Usando a estimativa de três pontos, qual é a faixa de esforço (E ± SD)?
A) De 14 a 22 homens/hora  
B) De 12 a 24 homens/hora  
C) De 10 a 34 homens/hora  
D) De 16 a 20 homens/hora  

---

### 9. Qual alternativa descreve corretamente a técnica Wideband Delphi?
A) Coletam-se números de projetos anteriores da organização para derivar indicadores padrão  
B) A estimativa final é a média ponderada (o + 4m + p)/6  
C) Cada especialista estima isoladamente; se houver desvios fora dos limites acordados, discutem e cada um refaz a estimativa isoladamente, repetindo até chegar a um consenso; o Planning Poker é uma variante  
D) A estimativa se baseia nas medições da iteração atual, extrapoladas por um modelo matemático  

---

### 10. Os casos de teste abaixo devem ser priorizados com base em risco (maior nível de risco primeiro). Em caso de empate, executa-se primeiro o de menor número. Um caso de teste dependente só pode ser executado depois de seu pré-requisito.

| Caso de teste | Nível do risco coberto | Dependência |
|---|---|---|
| TC1 | Alto | Depende de TC4 |
| TC2 | Médio | – |
| TC3 | Médio | – |
| TC4 | Baixo | – |
| TC5 | Baixo | – |

Qual é a ordem de execução mais adequada?
A) TC1, TC2, TC3, TC4, TC5  
B) TC4, TC1, TC2, TC3, TC5  
C) TC5, TC4, TC3, TC2, TC1  
D) TC1, TC4, TC2, TC3, TC5  

---

### 11. Uma suíte tem quatro casos de teste, que cobrem as seguintes instruções (de um total de 10 instruções, numeradas de 1 a 10):

- TC1: {1, 2, 3, 4, 5, 6}
- TC2: {1, 2, 3, 4, 5}
- TC3: {7, 8, 9}
- TC4: {7, 8, 9, 10}

Qual é a ordem dos dois primeiros casos de teste na priorização de cobertura adicional?
A) TC1 e TC2  
B) TC1 e TC3  
C) TC4 e TC1  
D) TC1 e TC4  

---

### 12. Qual afirmação sobre a priorização de casos de teste está correta?
A) Na priorização baseada em requisitos, os casos de teste relacionados aos requisitos mais importantes, segundo as prioridades definidas pelos stakeholders e rastreadas até os casos, são executados primeiro  
B) Na priorização baseada em risco, executam-se primeiro os casos que cobrem os riscos de menor nível  
C) Se um caso de teste de maior prioridade depende de um de menor prioridade, executa-se primeiro o de maior prioridade  
D) A disponibilidade de ambientes de teste e de pessoas não deve influenciar a ordem de execução  

---

### 13. Qual afirmação sobre a pirâmide de teste está correta?
A) A camada inferior contém testes de ponta a ponta, lentos e em pequeno número  
B) A camada superior contém testes pequenos, isolados e rápidos, em grande número  
C) A camada inferior contém testes pequenos, isolados e rápidos, necessários em grande número para uma cobertura razoável; a camada superior contém testes complexos de alto nível, mais lentos e em menor número  
D) O número de camadas é sempre três e a nomenclatura é fixa  

---

### 14. Qual associação entre tipo de teste e quadrante de teste está correta?
A) Testes de componente: Q2  
B) Testes exploratórios e testes de aceite do usuário: Q3  
C) Testes de usabilidade: Q4  
D) Testes de API: Q1  

---

### 15. Uma equipe ágil tem testes de componente e de integração de componentes automatizados no CI, testes de API e exemplos de histórias de usuário, além de smoke tests e testes de performance automatizados. Ela não possui nenhum teste exploratório, de usabilidade ou de aceite do usuário. Qual quadrante está sem cobertura?
A) Q1  
B) Q2  
C) Q4  
D) Q3  

---

### 16. Quatro riscos foram avaliados quantitativamente. Qual deles tem o maior nível de risco e deve ser tratado primeiro?

| Risco | Probabilidade | Impacto |
|---|---|---|
| R1 | 0,2 | 10 |
| R2 | 0,5 | 5 |
| R3 | 0,9 | 2 |
| R4 | 0,1 | 20 |

A) R2  
B) R1  
C) R3  
D) R4  

---

### 17. Qual das alternativas é um risco de PRODUTO?
A) Falência do fornecedor da ferramenta de automação  
B) Habilidades insuficientes da equipe de testes  
C) Algoritmo de cálculo de juros que pode produzir resultados incorretos  
D) Atraso na entrega do ambiente de teste  

---

### 18. Qual alternativa contém apenas riscos de PROJETO?
A) Tempo de resposta inadequado; vulnerabilidade de segurança  
B) Falta de pessoal de teste; desvio de escopo  
C) Funcionalidade ausente; arquitetura ruim  
D) Experiência ruim do usuário; atraso na entrega de produtos de trabalho  

---

### 19. Qual das alternativas NÃO é uma forma de uso dos resultados da análise de risco do produto?
A) Determinar o escopo dos testes e os níveis e tipos de teste a serem realizados  
B) Determinar as técnicas de teste a empregar e a cobertura a ser alcançada  
C) Priorizar os testes para encontrar os defeitos críticos o mais cedo possível  
D) Dispensar o monitoramento dos riscos durante o projeto  

---

### 20. Qual das ações abaixo é uma mitigação de risco do produto por meio de testes?
A) Selecionar testadores com o nível de experiência e habilidade adequado ao tipo de risco e aplicar um nível adequado de independência  
B) Transferir o risco, contratando um seguro contra os prejuízos  
C) Aceitar o risco e não tomar nenhuma ação  
D) Preparar um plano de contingência com um procedimento alternativo de operação  

---

### 21. Qual é o objetivo do monitoramento de riscos do produto?
A) Implementar as ações propostas na avaliação de riscos para reduzir o nível de risco  
B) Gerar uma lista abrangente dos riscos do produto  
C) Garantir que as ações de mitigação sejam eficazes, obter mais informações para melhorar a avaliação de riscos e identificar riscos emergentes  
D) Determinar a probabilidade e o impacto de cada risco identificado  

---

### 22. Qual é um exemplo de diretriz de CONTROLE de testes?
A) Coletar o número de casos de teste aprovados e reprovados  
B) Repriorizar os testes quando um risco identificado se torna um problema  
C) Calcular a densidade de defeitos do período  
D) Elaborar o relatório de conclusão do teste  

---

### 23. Qual associação entre métrica e categoria está correta?
A) Casos de teste executados e não executados: métrica de qualidade do produto  
B) Tempo médio até a falha: métrica de custo  
C) Cobertura de requisitos: métrica de risco  
D) Densidade de defeitos: métrica de defeitos  

---

### 24. Qual item é típico de um relatório de CONCLUSÃO de teste, mas não de um relatório de PROGRESSO de teste?
A) Lições aprendidas relevantes para o teste  
B) Testes planejados para o próximo período  
C) Riscos novos e alterados durante o período de teste  
D) Período de teste  

---

### 25. Uma equipe de testes está distribuída em três fusos horários, e a comunicação face a face nem sempre é possível. Qual abordagem para comunicar o status dos testes está alinhada ao syllabus?
A) Usar exclusivamente comunicação verbal informal com todos os stakeholders  
B) Usar o mesmo relatório, sem adaptações, para todos os stakeholders  
C) Adotar uma comunicação mais formal (como relatórios e documentação on-line), adaptando a informação ao interesse de cada stakeholder  
D) Evitar painéis, pois não servem para comunicar o status dos testes  

---

### 26. Qual afirmação sobre o gerenciamento de configuração (CM) em testes está correta?
A) Itens de configuração aprovados para teste podem ser alterados livremente, pois os testes exigem agilidade  
B) Um item de configuração aprovado para teste torna-se uma baseline e só pode ser alterado por um processo formal de controle de alterações; é possível reverter para uma baseline anterior para reproduzir resultados de testes anteriores  
C) O CM se aplica ao código, mas não aos produtos de trabalho de teste, como casos de teste e relatórios  
D) O CM é incompatível com pipelines de CI/CD  

---

### 27. Um defeito relatado há duas semanas não é mais reproduzido, porque o ambiente de teste foi atualizado desde então. Como o gerenciamento de configuração apoia a equipe nessa situação?
A) Aumentando a severidade do defeito para forçar a correção  
B) Executando todos os testes de regressão novamente  
C) Reabrindo o relatório de defeitos  
D) Revertendo o ambiente para a baseline anterior, cujos itens, relacionamentos e versões estão registrados, para reproduzir o resultado  

---

### 28. Qual das alternativas NÃO é um item típico de um relatório de defeitos registrado durante um teste dinâmico?
A) A causa-raiz confirmada e a linha de código-fonte responsável  
B) Os resultados esperados e os resultados reais  
C) A severidade e a prioridade de correção  
D) A identificação do objeto de teste e do ambiente de teste  

---

### 29. Durante a execução do caso de teste TC-045, em 20/10/2026, no ambiente de homologação HML-02, versão 2.3.1 do app PagaFácil, a testadora Ana Souza (Analista de QA) tenta pagar um boleto de R$ 150,00 com saldo suficiente. O app exibe "Erro 500" e o valor não é debitado. O resultado esperado era a confirmação do pagamento e o débito do valor. Qual relatório de defeitos é o mais adequado?
A) Título: "Pagamento não funciona". Descrição: "O pagamento está com problema e precisa ser corrigido com urgência."  
B) Título: "Erro de programação no módulo de pagamento". Descrição: "O desenvolvedor responsável cometeu um erro na validação de saldo." Evidências: nenhuma.  
C) Título: "Erro 500 ao pagar boleto de R$ 150,00 com saldo suficiente". Contexto: TC-045; PagaFácil 2.3.1; HML-02; 20/10/2026; autora Ana Souza (Analista de QA). Passos: (1) entrar na conta; (2) escolher pagar boleto; (3) informar o código do boleto de R$ 150,00; (4) confirmar. Resultado esperado: pagamento confirmado e valor debitado. Resultado real: Erro 500 e nenhum débito. Evidências: captura de tela e log. Severidade: alta; prioridade: alta.  
D) Título: "Erro 500 ao pagar boleto". Passos: (1) entrar na conta; (2) pagar boleto de R$ 150,00. Resultado real: Erro 500. Sem resultado esperado, versão do aplicativo ou ambiente.  

---

### 30. Qual afirmação sobre o gerenciamento de defeitos está correta?
A) Toda anomalia relatada é um defeito real, e relatórios de defeitos só são gerados por testes dinâmicos  
B) O fluxo de trabalho inclui registrar, analisar, classificar, decidir a resposta e fechar o relatório; as anomalias relatadas podem se tornar defeitos reais ou outra coisa (como falso positivo ou solicitação de mudança); convém tratar os defeitos dos testes estáticos de forma semelhante  
C) O status "reaberto" não existe, pois todo defeito fechado é definitivo  
D) O processo deve ser seguido apenas pela equipe de testes  

---

## GABARITO

| #  | Resp | Explicação |
|----|------|------------|
| 1  | D | (K2 · 5.1.1) O plano de teste inclui contexto, premissas e restrições, stakeholders, comunicação, registro de riscos, abordagem de teste, orçamento e cronograma. A lista de defeitos e seus status pertence aos relatórios de defeitos e de progresso, não ao plano. |
| 2  | C | (K1 · 5.1.2) Dividir as histórias em tarefas (especialmente de teste) e estimar o esforço de todas as tarefas é do planejamento de iteração. **A**, **B** e **D** são do planejamento de liberação. **D** é a pegadinha: a análise de risco do projeto e da qualidade é da liberação, e a análise detalhada das histórias é da iteração. |
| 3  | B | (K2 · 5.1.3) O esgotamento de tempo ou orçamento pode ser critério de saída válido se os stakeholders aceitaram o risco. **A** inverte entrada e saída. **C** inverte DoR (critério de entrada) e DoD (critério de saída). **D** erra: devem ser definidos para cada nível de teste. |
| 4  | C | (K2 · 5.1.3) A qualidade inicial do objeto de teste (como "todos os testes de fumaça foram aprovados") é critério de entrada. **A**, **B** e **D** são medidas de precisão ou de conclusão, típicas de critérios de saída. |
| 5  | A | (K3 · 5.1.4) Estimativa baseada em índices: proporção 5:2, então teste = 800 × 2/5 = 320 h. **D** (800 × 5/2) inverte a proporção; **C** é 800/2. |
| 6  | D | (K3 · 5.1.4) Extrapolação: média das três últimas iterações = (30 + 42 + 60)/3 = 132/3 = 44 h. **A** é a mediana; **B** é o ponto médio de 30 e 60; **C** é o último valor e mistura a técnica com a de três pontos. |
| 7  | B | (K3 · 5.1.4) E = (8 + 4×14 + 26)/6 = 90/6 = 15; SD = (26 − 8)/6 = 3, então 15 ± 3. **A** usa média simples ((8+14+26)/3 ≈ 16) e (p−o)/3; **C** usa só a estimativa mais provável. |
| 8  | A | (K3 · 5.1.4) E = (10 + 4×16 + 34)/6 = 108/6 = 18; SD = (34 − 10)/6 = 4. Faixa: 18 ± 4 = de 14 a 22 homens/hora. **C** é a faixa otimista–pessimista, e não E ± SD. |
| 9  | C | (K2 · 5.1.4) Wideband Delphi: estimativas isoladas, discussão dos desvios, nova estimativa isolada, repetição até o consenso. O Planning Poker é uma variante. **A** é a baseada em índices; **B** é a de três pontos; **D** é a extrapolação. |
| 10 | B | (K3 · 5.1.5) Por risco: TC1 (alto), depois TC2 e TC3 (médio), depois TC4 e TC5 (baixo). Como TC1 depende de TC4 (de prioridade menor), TC4 deve vir antes: TC4, TC1, TC2, TC3, TC5. **A** ignora a dependência; **D** executa TC1 antes do seu pré-requisito. |
| 11 | D | (K3 · 5.1.5) TC1 cobre mais (6 instruções) e é o primeiro. Na cobertura adicional, TC2 acrescenta 0, TC3 acrescenta 3 ({7,8,9}) e TC4 acrescenta 4 ({7,8,9,10}). O segundo é TC4. **A** é a ordem da priorização por cobertura simples (TC1, TC2). |
| 12 | A | (K2 · 5.1.5) Priorização baseada em requisitos usa as prioridades definidas pelos stakeholders. **B** inverte a de risco; **C** inverte a regra de dependência (o de menor prioridade vai primeiro); **D** erra: os recursos disponíveis devem ser considerados. |
| 13 | C | (K1 · 5.1.6) Camadas inferiores: testes pequenos, isolados, rápidos e numerosos. Camadas superiores: testes complexos, de ponta a ponta, mais lentos e em menor número. O número e a nomenclatura das camadas podem variar. |
| 14 | B | (K2 · 5.1.7) Q3 (negócios, avalia o produto): exploratórios, usabilidade, aceite do usuário. **A** é Q1; **C** erra, pois usabilidade é Q3 e Q4 traz os não funcionais exceto usabilidade; **D** erra, pois testes de API são Q2. |
| 15 | D | (K2 · 5.1.7) Q1: componente e integração. Q2: funcionais, exemplos, histórias, API. Q4: smoke e não funcionais. Falta o Q3 (voltado para negócios, avalia o produto): exploratório, usabilidade e aceite do usuário, geralmente manuais. |
| 16 | A | (K3 · 5.2.1) Nível quantitativo = probabilidade × impacto. R1 = 2,0; R2 = 2,5; R3 = 1,8; R4 = 2,0. O maior é R2. **C** tem a maior probabilidade, mas o menor nível. |
| 17 | C | (K2 · 5.2.2) Cálculo incorreto é risco de produto (característica de qualidade). **A**, **B** e **D** são riscos de projeto (fornecedores, pessoal e organizacional). |
| 18 | B | (K2 · 5.2.2) Falta de pessoal e desvio de escopo são riscos de projeto. **A** e **C** são só de produto; **D** mistura (a experiência do usuário é de produto, o atraso de produtos de trabalho é de projeto). |
| 19 | D | (K2 · 5.2.3) Os resultados definem escopo, níveis e tipos, técnicas e cobertura, esforço, prioridade e outras atividades além de testes. O monitoramento de riscos faz parte do controle de riscos e continua sendo necessário. |
| 20 | A | (K2 · 5.2.4) Selecionar testadores adequados e aplicar independência adequada são mitigações por meio de testes. **B** é transferência; **C** é aceite; **D** é plano de contingência (outras respostas ao risco). |
| 21 | C | (K2 · 5.2.4) Monitorar é garantir a eficácia das ações de mitigação, obter mais informações e identificar riscos emergentes. **A** é a mitigação; **B** é a identificação; **D** é a avaliação. |
| 22 | B | (K2 · 5.3) Repriorizar testes quando um risco se torna problema é diretriz de controle. **A** e **C** são monitoramento (coleta de informações e métricas); **D** é conclusão do teste. |
| 23 | D | (K1 · 5.3.1) Densidade de defeitos é métrica de defeitos. **A** é de progresso do teste; **B** é de qualidade do produto; **C** é de cobertura. |
| 24 | A | (K2 · 5.3.2) Lições aprendidas aparecem nos relatórios de conclusão. **B**, **C** e **D** são itens do relatório de progresso (período, riscos novos e alterados, testes do próximo período). |
| 25 | C | (K2 · 5.3.3) Uma comunicação mais formal pode ser mais apropriada para equipes distribuídas, e a comunicação deve ser adaptada, pois stakeholders diferentes querem informações diferentes. Painéis são opções válidas (**D** erra). |
| 26 | B | (K2 · 5.4) Item aprovado vira baseline e só muda por controle formal de alterações; é possível reverter a uma baseline anterior. O CM abrange também planos, casos, scripts, resultados, registros e relatórios, e costuma estar automatizado no pipeline de DevOps. |
| 27 | D | (K2 · 5.4) O CM registra os itens que compõem um ambiente, seus relacionamentos e versões, e permite reverter a uma baseline anterior para reproduzir resultados de testes anteriores. |
| 28 | A | (K2 · 5.5) O relatório inclui identificador, título, data, autor, objeto de teste e ambiente, contexto, descrição da falha, resultados esperados e reais, severidade, prioridade, status e referências. A causa-raiz confirmada e a linha de código são resultados da análise e da correção. |
| 29 | C | (K3 · 5.5.1) Relatório completo: identificador/título claro, data, autora, objeto e ambiente, contexto (TC-045), passos reproduzíveis, esperado × real, evidências, severidade e prioridade. **A** é vago; **B** culpa pessoas, sem evidências nem passos; **D** omite o esperado, a versão e o ambiente. |
| 30 | B | (K2 · 5.5) O fluxo mínimo: registrar, analisar, classificar, decidir a resposta e fechar. Anomalias podem ser falsos positivos ou solicitações de mudança; "reaberto" é um status típico; o processo deve ser seguido por todos os stakeholders; defeitos de testes estáticos devem ser tratados de forma semelhante. |
