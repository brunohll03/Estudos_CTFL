# SIMULADO CTFL 4.0 – CAPÍTULO 5 (20 QUESTÕES)

---

## Instruções

- Conteúdo: **Capítulo 5 — Gerenciamento das Atividades de Teste**, itens **5.1 a 5.5**.
- Dificuldade: **difícil**, com questões autorais no estilo do exame CTFL.
- Níveis cognitivos **K1, K2 e K3** conforme o syllabus.
- Cada questão possui quatro alternativas (A–D) e **exatamente uma resposta correta**.
- Sem identificação do tema no título das questões, para evitar pistas.
- Tempo sugerido: 35 minutos.
- **Gabarito comentado somente no final.**

---

## QUESTÕES

### 1.

Uma equipe elaborou um plano de teste com objetivos, cronograma e responsáveis, mas ainda não decidiu quais níveis de teste utilizar, como determinar a cobertura e quais condições encerrarão a execução. Qual complemento é o MAIS apropriado para o plano?

**A)** Inserir os defeitos efetivamente encontrados e as lições aprendidas após a implantação.

**B)** Registrar apenas as ferramentas aprovadas e deixar os critérios de saída para o relatório final.

**C)** Descrever a abordagem de teste, incluindo níveis, técnicas, métricas, critérios de entrada e saída e requisitos de ambiente.

**D)** Substituir as decisões de teste pelo cronograma de desenvolvimento, mantendo somente o orçamento.

---

### 2.

Em uma organização ágil, um testador participa de dois encontros. No primeiro, ajuda a dividir histórias grandes, analisar riscos da entrega e definir uma abordagem para várias iterações. No segundo, detalha tarefas e estima o esforço de teste das histórias selecionadas para a próxima sprint. Como classificar, respectivamente, os encontros?

**A)** Planejamento de lançamento e planejamento de iteração.

**B)** Planejamento de iteração e retrospectiva.

**C)** Refinamento de defeitos e planejamento de lançamento.

**D)** Monitoramento de testes e planejamento de lançamento.

---

### 3.

Para iniciar os testes de sistema de uma versão, a equipe exige ambiente operacional, massa de dados disponível e aprovação do smoke test. Para declarar os testes concluídos, exige 95% de cobertura dos requisitos e ausência de defeitos críticos abertos. Qual interpretação está CORRETA?

**A)** Ambos os grupos são critérios de entrada, pois precisam ser definidos antes de testar.

**B)** O primeiro grupo contém critérios de entrada, e o segundo, critérios de saída.

**C)** O primeiro grupo contém critérios de saída, e o segundo, critérios de entrada.

**D)** Os dois grupos são critérios de saída, pois dependem de medições técnicas.

---

### 4.

Em projetos comparáveis, uma organização observou uma razão histórica de esforço de desenvolvimento para esforço de teste de 4:3. Para uma nova entrega, estimam-se 280 pessoas-dia de desenvolvimento. Utilizando exclusivamente a estimativa baseada nessa razão, qual será o esforço de teste?

**A)** 70 pessoas-dia.

**B)** 210 pessoas-dia de desenvolvimento e teste somados.

**C)** 373,33 pessoas-dia.

**D)** 210 pessoas-dia de teste.

---

### 5.

O esforço real de teste nas três últimas iterações de tamanho e complexidade semelhantes foi de 26, 34 e 30 horas. A equipe decide estimar quatro novas iterações, também semelhantes, usando a média histórica dessas três e sem ajustes adicionais. Qual é a estimativa TOTAL para as quatro novas iterações?

**A)** 30 horas.

**B)** 90 horas.

**C)** 120 horas.

**D)** 360 horas.

---

### 6.

Um grupo de especialistas estimou um esforço de teste pelo método de três pontos: otimista = 6 horas, mais provável = 12 horas e pessimista = 24 horas. Adotando E = (a + 4m + b)/6 e SD = (b − a)/6, qual resultado está CORRETO?

**A)** 13 ± 3 horas.

**B)** 14 ± 3 horas.

**C)** 13 ± 6 horas.

**D)** 12 ± 3 horas.

---

### 7.

Quatro especialistas estimam individualmente o esforço de uma integração. As estimativas divergentes são apresentadas, o grupo discute premissas e cada especialista estima novamente sem influência direta dos demais. O ciclo se repete até haver consenso. Qual descrição é a MAIS adequada?

**A)** Extrapolação, pois o esforço é projetado a partir de iterações anteriores.

**B)** Estimativa por razões, porque converte o esforço de desenvolvimento em esforço de teste.

**C)** Estimativa de três pontos, porque identifica os valores mínimo, médio e máximo.

**D)** Wideband Delphi, técnica baseada em especialistas da qual o Planning Poker é uma variante.

---

### 8.

Após a análise de risco, um caso de teste de pagamento (CT-P) recebe prioridade máxima, enquanto o caso de criação de conta (CT-C) recebe prioridade média. Entretanto, CT-P só pode ser executado se CT-C tiver criado previamente uma conta válida. Ambos estão disponíveis no ambiente. Qual ordem de execução é a MAIS adequada?

**A)** CT-P primeiro, pois a prioridade de risco sempre prevalece sobre dependências.

**B)** CT-C antes de CT-P, pois a dependência precisa ser satisfeita mesmo com prioridade inferior.

**C)** Executar os dois simultaneamente, porque a prioridade dos testes determina sua independência.

**D)** Adiar CT-C até que CT-P seja aprovado, preservando a ordenação por risco.

---

### 9.

Uma suíte precisa priorizar testes por cobertura ADICIONAL. Há oito requisitos R1–R8 e os casos cobrem: CT1={R1,R2,R3,R5,R6}; CT2={R2,R3,R4,R5,R6,R7}; CT3={R1,R4,R7,R8}; CT4={R3,R4,R8}. Qual sequência dos DOIS PRIMEIROS casos maximiza a cobertura total após duas execuções?

**A)** CT2 seguido de CT3.

**B)** CT1 seguido de CT2.

**C)** CT3 seguido de CT4.

**D)** CT2 seguido de CT4.

---

### 10.

Uma equipe automatizou poucos testes isolados de componentes e centenas de testes ponta a ponta com interface gráfica. As verificações ficaram lentas e frágeis. Qual alteração está MAIS alinhada ao conceito de pirâmide de testes?

**A)** Aumentar a proporção de testes ponta a ponta, pois executam mais funcionalidades por caso.

**B)** Substituir todas as verificações de componentes por testes manuais de aceitação.

**C)** Ampliar a base de testes pequenos, rápidos e isolados e manter relativamente poucos testes ponta a ponta.

**D)** Padronizar o mesmo tempo de execução e a mesma granularidade em todas as camadas.

---

### 11.

Durante o planejamento, a equipe separa (I) testes exploratórios de usabilidade orientados ao usuário e (II) testes automatizados de carga e segurança para avaliar características técnicas do produto. Nos quadrantes ágeis, em quais grupos eles se encaixam MELHOR, respectivamente?

**A)** Q2 e Q1.

**B)** Q4 e Q2.

**C)** Q1 e Q3.

**D)** Q3 e Q4.

---

### 12.

Em uma análise quantitativa, o nível de risco é calculado por probabilidade × impacto. Três funcionalidades têm os seguintes valores: F1 (0,20; impacto 9), F2 (0,60; impacto 4) e F3 (0,40; impacto 5). Qual deve receber a maior atenção inicial se esse produto for o ÚNICO critério de ordenação?

**A)** F1, pois apresenta o maior impacto isolado.

**B)** F2, pois seu nível calculado é 2,4.

**C)** F3, pois seu nível calculado é 2,0 e supera os demais.

**D)** F1 e F3 empatadas, pois a probabilidade de F1 é a menor.

---

### 13.

Um projeto enfrenta duas ameaças: (I) o ambiente de homologação pode não ficar pronto antes da sprint; (II) uma falha de autorização pode mostrar pedidos de um cliente para outro. Qual classificação corresponde MELHOR a esses riscos?

**A)** Ambos são riscos de produto, pois podem interferir na qualidade final.

**B)** I é risco de produto; II é risco de projeto.

**C)** I é risco de projeto; II é risco de produto.

**D)** Ambos são riscos de projeto, pois podem atrasar a entrega.

---

### 14.

A análise de riscos identificou alta probabilidade e alto impacto para uma possível exposição de dados pessoais por uma API. Qual mudança de abordagem de teste é a MAIS consistente com o gerenciamento de riscos do produto?

**A)** Priorizar testes de autorização e segurança, ampliar sua profundidade e atribuir profissionais com competências adequadas.

**B)** Distribuir igualmente o esforço entre todas as funcionalidades, pois risco não influencia abrangência.

**C)** Executar apenas o fluxo positivo principal, já que reduz o tempo de teste.

**D)** Reduzir a cobertura da API até que sejam encontrados defeitos em funcionalidades menos críticas.

---

### 15.

Para tratar o risco de acessos indevidos, a equipe (I) acrescenta testes de autorização e revisões de regras; depois (II) acompanha se as ações reduziram o risco e identifica riscos novos. Como classificar I e II, respectivamente?

**A)** Aceitação de risco e transferência de risco.

**B)** Identificação de risco e análise de risco.

**C)** Monitoramento de risco e mitigação de risco.

**D)** Mitigação de risco e monitoramento de risco.

---

### 16.

No meio da execução, o responsável constata que só 45% dos testes planejados foram executados, contra uma meta de 75% para aquela data. A equipe então redistribui pessoas e altera a ordem dos testes para tratar os riscos mais altos. Qual classificação das atividades, respectivamente, é MAIS precisa?

**A)** Planejamento e conclusão.

**B)** Monitoramento e controle.

**C)** Controle e monitoramento.

**D)** Análise e implementação.

---

### 17.

Ao final do dia, uma suíte planejada com 150 casos contém 90 casos aprovados, 30 reprovados e 30 ainda não executados. Considerando como executados os casos aprovados ou reprovados, quais são, respectivamente, o percentual executado e a taxa de aprovação ENTRE OS EXECUTADOS?

**A)** 60% e 75%.

**B)** 80% e 60%.

**C)** 80% e 75%.

**D)** 75% e 80%.

---

### 18.

Durante uma sprint, a equipe publica diariamente obstáculos, métricas, riscos alterados e trabalho de teste planejado. Ao concluir uma liberação, consolida desvios do plano, defeitos pendentes, riscos residuais e lições aprendidas para gestores. Qual afirmação é a MAIS adequada?

**A)** O primeiro é relatório de progresso, e o segundo, de conclusão; a comunicação deve ser ajustada ao público.

**B)** Ambos são relatórios de conclusão, pois contêm métricas e riscos.

**C)** O primeiro é relatório de defeitos, e o segundo, plano de teste.

**D)** O segundo elimina a necessidade de registrar riscos residuais, por se destinar a gestores.

---

### 19.

Uma falha foi observada em homologação, mas não pode ser reproduzida depois de uma atualização. Há suspeita de que um serviço dependente e a massa de dados tenham mudado. Qual prática oferece o suporte MAIS direto à reprodução confiável do resultado anterior?

**A)** Arquivar somente o relatório final sem informações das versões.

**B)** Identificar e versionar a configuração do ambiente, os componentes, os testes e os dados, preservando uma baseline rastreável.

**C)** Fixar apenas a versão do aplicativo principal e permitir mudanças não registradas nos demais componentes.

**D)** Considerar a falha irreproduzível e descartá-la independentemente das mudanças de ambiente.

---

### 20.

Ao testar uma API, o QA observa que uma requisição com credencial de teste expirada devolve HTTP 200 e dados de um cliente, embora a especificação determine rejeição com HTTP 401. Qual registro seria o relatório de defeito MAIS útil para investigação e correção?

**A)** “Falha grave na API; corrigir autenticação urgentemente”, sem passos nem versão, mas com prioridade alta.

**B)** “A API pode estar errada”, incluindo somente uma imagem da tela, sem resposta esperada ou observada.

**C)** “Autenticação falha às vezes”, com nome do QA e sem dados de reprodução por serem testes automatizados.

**D)** Título preciso, ambiente e build, pré-condição de credencial expirada, passos, resultado esperado 401, resultado obtido 200, evidências e gravidade/prioridade.

---

## GABARITO COMENTADO

| # | Resp. | Explicação |
|:--:|:--:|---|
| 1 | **C** | O plano de teste deve explicitar a abordagem, incluindo níveis, técnicas, critérios, métricas, ambiente e outros aspectos necessários para atingir os objetivos. Defeitos finais e lições aprendidas pertencem principalmente ao acompanhamento e à conclusão. |
| 2 | **A** | O planejamento de lançamento olha para o backlog e a abordagem de teste ao longo das iterações; o planejamento de iteração detalha o trabalho e as estimativas para uma iteração específica. |
| 3 | **B** | Critérios de entrada são pré-condições para iniciar uma atividade; critérios de saída definem o que deve ser alcançado para encerrá-la. Em Agile, os conceitos se relacionam à Definition of Ready e à Definition of Done. |
| 4 | **D** | A razão desenvolvimento:teste é 4:3. Logo, esforço de teste = 280 × (3/4) = 210 pessoas-dia. O total de desenvolvimento e teste seria 490, mas a pergunta solicita apenas teste. |
| 5 | **C** | A média das três iterações é (26 + 34 + 30)/3 = 30 horas por iteração. Para quatro novas iterações semelhantes: 30 × 4 = 120 horas. Trata-se de extrapolação baseada em medições do projeto. |
| 6 | **A** | E = (6 + 4×12 + 24)/6 = 78/6 = 13 horas. SD = (24 − 6)/6 = 3 horas. Portanto 13 ± 3 horas, conforme a forma de estimativa apresentada no syllabus. |
| 7 | **D** | Wideband Delphi combina estimativas individuais, discussão de divergências e novas rodadas para chegar a consenso. Planning Poker é uma variante; extrapolação e razões usam métricas, e três pontos usa avaliações otimista, provável e pessimista. |
| 8 | **B** | A priorização baseada em risco é importante, mas as dependências operacionais podem obrigar a executar primeiro um teste de menor prioridade que prepara o estado requerido pelo teste prioritário. |
| 9 | **A** | CT2 cobre inicialmente seis requisitos. Restam R1 e R8, ambos cobertos por CT3, chegando a oito requisitos após dois testes. CT2+CT4 não cobre R1, e as demais duplas também não atingem oito. |
| 10 | **C** | A pirâmide sugere muitos testes pequenos, isolados e rápidos na base e menos testes complexos e lentos no topo. A quantidade e os nomes das camadas podem variar. |
| 11 | **D** | Q3 é orientado ao negócio e critica o produto, incluindo exploração e usabilidade. Q4 é orientado à tecnologia e critica o produto, incluindo testes não funcionais como carga e segurança. Q1 suporta o time tecnicamente e Q2 o suporta pelo negócio. |
| 12 | **B** | F1=0,20×9=1,8; F2=0,60×4=2,4; F3=0,40×5=2,0. F2 possui o maior nível de risco sob a regra quantitativa fornecida. |
| 13 | **C** | Indisponibilidade de ambiente ameaça a execução do projeto e é risco de projeto. Exposição indevida de pedidos é possível falha do produto em operação e caracteriza risco de produto. |
| 14 | **A** | Análise de risco do produto orienta escopo, níveis, tipos, técnicas, profundidade e prioridades. Alto risco de exposição de dados justifica testes específicos e maior rigor nesse aspecto. |
| 15 | **D** | Implementar controles para reduzir risco é mitigação. Acompanhar eficácia, atualizar avaliações e descobrir riscos emergentes é monitoramento. Ambas integram o controle de riscos do produto. |
| 16 | **B** | Constatar progresso e compará-lo com metas é monitoramento. Decidir e executar medidas corretivas com base nessa informação é controle de testes. |
| 17 | **C** | Foram executados 90+30=120 de 150 casos: 120/150=80%. Entre os 120 executados, 90 passaram: 90/120=75%. A taxa de aprovação não deve usar os 150 planejados nesse enunciado. |
| 18 | **A** | Relatórios de progresso apresentam situação corrente e próximos passos; relatórios de conclusão consolidam avaliação final, desvios, riscos não mitigados, defeitos abertos e lições aprendidas. O formato e a frequência dependem do público. |
| 19 | **B** | Gerenciamento de configuração identifica, versiona, rastreia relações e mudanças entre itens como software, dados, ambiente e testware. Baselines permitem recuperar configurações anteriores e reproduzir resultados. |
| 20 | **D** | Um relatório de defeito eficaz registra o contexto e a configuração do teste, reprodução, resultados esperado/obtido, evidências, impacto e prioridade de correção, além de identificação e referências. Não é necessário expor o valor secreto da credencial. |

---

## Referências

- [ISTQB — CTFL Syllabus v4.0.1 (oficial)](https://istqb.org/wp-content/uploads/2024/11/ISTQB_CTFL_Syllabus_v4.0.1.pdf), capítulo 5, páginas 47–57.
- [BSTQB — CTFL 4.0 em português](https://bstqb.online/files/syllabus_ctfl_4.0br.pdf).

> Simulado autoral para preparação. Não são questões oficiais do exame ISTQB.
