# SIMULADO — PIRÂMIDE DE TESTE (20 QUESTÕES)

---

## Instruções

- Baseado no documento **Pirâmide de Teste — Versão 1.0** (BSTQB, 2025).
- **Dificuldade: difícil**, com situações práticas e alternativas plausíveis, em estilo de prova CTFL.
- Cada questão contém **quatro alternativas (A–D)** e **apenas uma resposta correta**.
- Não há indicação do assunto no título das questões, para evitar pistas.
- **Gabarito comentado somente ao final**.
- Tempo sugerido: **30 minutos**.

---

## QUESTÕES

### 1.

Uma equipe possui 540 testes automatizados de interface, 110 de integração e 50 de unidade. A execução da suíte é lenta, a manutenção dos testes de UI é onerosa e defeitos de lógica são encontrados tardiamente. Qual diagnóstico e direção de melhoria são MAIS compatíveis com o documento?

**A)** A distribuição caracteriza uma ampulheta; a prioridade é ampliar exclusivamente os testes de interface para compensar as integrações ausentes.

**B)** A distribuição caracteriza um guarda-chuva; a prioridade é descartar todos os testes de UI e substituí-los imediatamente por testes unitários.

**C)** A distribuição se aproxima de um cone de sorvete; convém ampliar a cobertura nas camadas inferiores e reduzir a dependência desnecessária da UI.

**D)** A distribuição representa a pirâmide ideal; a lentidão deve ser corrigida apenas com mais recursos de infraestrutura.

---

### 2.

Em um sistema de pagamentos, os módulos de cobrança e de atualização de pedidos passam em seus testes isolados. Quando conectados, porém, um pagamento aprovado não atualiza corretamente o status do pedido. Em qual camada a investigação por testes está MAIS diretamente alinhada ao objetivo descrito no material?

**A)** Na camada intermediária, verificando a comunicação, o fluxo de dados e as interfaces entre componentes.

**B)** Na base, executando novamente somente os mesmos testes isolados das funções já aprovadas.

**C)** No topo, avaliando exclusivamente a organização dos botões e a legibilidade da interface.

**D)** Na camada superior, substituindo a verificação da integração por uma pesquisa de satisfação dos usuários.

---

### 3.

Uma alteração interna torna uma função mais legível sem modificar o comportamento esperado. Antes de integrar a mudança, os desenvolvedores querem obter rapidamente evidências de que a lógica básica continua funcionando. Qual estratégia se ajusta MELHOR aos benefícios da base da pirâmide?

**A)** Executar prioritariamente fluxos completos de UI, pois a refatoração elimina a utilidade dos testes isolados.

**B)** Aguardar a implantação em produção para observar a reação dos usuários ao novo código.

**C)** Concentrar-se nos testes de usabilidade, pois legibilidade do código é avaliada por usuários finais.

**D)** Executar testes de unidade rápidos e repetíveis, que apoiam a refatoração e fornecem feedback antecipado.

---

### 4.

Uma aplicação legada não permite, por limitações técnicas, introduzir testes automatizados nos níveis de unidade ou serviço no curto prazo. A suíte atual é composta exclusivamente por testes de UI e apresenta instabilidade. Qual plano é o MAIS indicado pelo documento enquanto essa limitação persistir?

**A)** Suspender a automação até a arquitetura permitir testes de unidade, mantendo somente execução manual ocasional.

**B)** Paralelizar a execução, estabilizar cenários, usar seletores robustos e priorizar fluxos críticos na UI.

**C)** Duplicar os mesmos fluxos automatizados para aumentar a contagem de casos e a cobertura aparente.

**D)** Executar a suíte completa apenas no encerramento do projeto, para evitar manutenção ao longo das mudanças.

---

### 5.

Uma equipe quer justificar a manutenção de uma grande suíte de testes unitários. Qual argumento NÃO corresponde aos benefícios que o material atribui diretamente à base da pirâmide?

**A)** As verificações rápidas permitem executar testes repetidamente durante o desenvolvimento.

**B)** O isolamento de unidades tende a facilitar a localização de problemas e a depuração.

**C)** Os testes de unidade podem funcionar como documentação ativa do comportamento das funções.

**D)** A execução isolada das funções confirma, por si só, a experiência completa de navegação e acessibilidade do usuário.

---

### 6.

Dois serviços trocam mensagens. Nenhuma exceção é gerada e ambos permanecem disponíveis, mas um campo é interpretado em unidade monetária incorreta, alterando silenciosamente o resultado. Qual justificativa sustenta MELHOR incluir testes no nível intermediário?

**A)** A ausência de exceções demonstra que a integração foi validada, restando apenas avaliar a aparência do formulário.

**B)** Somente os testes unitários podem examinar dados, pois testes entre serviços verificam exclusivamente disponibilidade.

**C)** Testes de integração podem detectar problemas silenciosos de interface e manipulação de dados que surgem quando componentes interagem.

**D)** A existência de dois serviços transforma automaticamente o problema em acessibilidade, pertencente ao topo da pirâmide.

---

### 7.

Um aplicativo executa corretamente suas regras de negócio e suas integrações. Ainda assim, usuários com deficiência visual não conseguem percorrer o processo de compra por leitor de tela, e os botões são difíceis de compreender. Que avaliação complementa MAIS diretamente as camadas inferiores?

**A)** Testes de interface, usabilidade e acessibilidade, direcionados à interação e às necessidades dos usuários finais.

**B)** Testes exclusivamente unitários, porque problemas de acessibilidade são detectados ao isolar funções.

**C)** Testes apenas de integração, porque leitores de tela exercitam somente a comunicação entre serviços.

**D)** Repetição dos testes unitários aprovados, pois isso substitui a observação da experiência de uso.

---

### 8.

Uma equipe pretende diminuir o intervalo entre a alteração do código e a descoberta de uma regressão. Qual prática representa MELHOR a combinação de automação e execução contínua defendida pelo documento?

**A)** Concentrar todos os testes automatizados de interface em uma única execução antes da entrega final.

**B)** Integrar testes automatizados ao fluxo de CI para execução frequente a cada alteração, priorizando feedback rápido nos níveis inferiores.

**C)** Executar testes somente quando um usuário registrar defeito, evitando consumo de recursos do pipeline.

**D)** Substituir os testes de regressão por uma revisão semestral das métricas de cobertura.

---

### 9.

Um gerente interpreta o exemplo de distribuição de 70% de testes de unidade, 20% de serviço e 10% de UI como regra obrigatória para qualquer projeto. Qual análise corresponde ao que o material efetivamente afirma?

**A)** A distribuição é obrigatória inclusive quando não existem recursos técnicos para testes inferiores.

**B)** A distribuição deve ser invertida em projetos ágeis, para manter a UI sempre como maior camada.

**C)** A proporção é ilustrativa; o estado-alvo deve ser ajustado conforme viabilidade, complexidade, recursos e prioridades do negócio.

**D)** A proporção só pode ser empregada quando todos os testes da suíte são manuais.

---

### 10.

Uma organização possui muitos testes unitários e muitos testes completos de interface, mas pouquíssimos testes de serviço. Defeitos na comunicação entre APIs só aparecem nos testes de ponta a ponta. Qual combinação de diagnóstico e ação é a MAIS adequada?

**A)** Cone de sorvete; adicionar somente novos testes de UI para reproduzir as falhas das APIs.

**B)** Guarda-chuva; eliminar os testes de unidade para simplificar a suíte existente.

**C)** Pirâmide ideal; considerar as falhas de integração como problema exclusivo de documentação.

**D)** Ampulheta; fortalecer o nível de serviço e avaliar a migração de verificações de lógica de negócio da UI para APIs.

---

### 11.

O documento menciona desempenho tanto ao explicar testes de integração quanto ao descrever os testes de interface e usabilidade. Qual interpretação evita transformar esses exemplos em uma restrição inexistente?

**A)** Avaliação de desempenho pertence exclusivamente à base, porque apenas funções isoladas podem ser medidas.

**B)** A integração pode incluir avaliação inicial de desempenho; a camada de interface também pode verificar atrasos e tempos de resposta percebidos na interação.

**C)** Qualquer avaliação de desempenho elimina a necessidade de testes funcionais de componentes e de UI.

**D)** A avaliação de desempenho deve ser deslocada totalmente para o topo, pois é incompatível com testes de integração.

---

### 12.

Antes de planejar a transformação de sua suíte, um time registra quantidade de testes por camada, cobertura, eficácia, proporção manual/automatizada e gargalos. Qual é a finalidade MAIS direta desse trabalho no processo de otimização proposto?

**A)** Construir uma baseline do estado atual para identificar lacunas e possibilitar comparação posterior com o estado-alvo.

**B)** Definir automaticamente o estado-alvo definitivo, sem considerar necessidades das partes interessadas.

**C)** Comprovar que a distribuição de testes, por si só, garante a ausência de falhas em produção.

**D)** Substituir a análise dos testes por uma única métrica de quantidade de scripts automatizados.

---

### 13.

Uma equipe identifica grande distância entre sua distribuição de testes e a pirâmide desejada. O orçamento, a infraestrutura e o cronograma não permitem atingir rapidamente a proporção planejada. Qual decisão está MAIS alinhada ao método do documento?

**A)** Manter a proporção desejada sem qualquer adaptação, ainda que o projeto não disponha dos meios necessários.

**B)** Cancelar o planejamento e limitar os testes à camada com maior número histórico de scripts.

**C)** Definir metas sem participação de stakeholders, pois as metas de testes não devem refletir prioridades de negócio.

**D)** Estabelecer um estado-alvo viável com stakeholders, considerando recursos, prazos e requisitos de qualidade, e otimizar progressivamente.

---

### 14.

Durante a reorganização de testes de serviço, uma integração com um provedor externo torna os testes imprevisíveis. O time deseja testar partes do fluxo sem depender da disponibilidade real desse provedor. Que prática aparece no documento como apoio à otimização?

**A)** Replicar todos os testes afetados na interface gráfica, mantendo a dependência em todas as execuções.

**B)** Desativar as verificações afetadas até que a integração externa fique permanentemente estável.

**C)** Usar dublês de teste, como mocks, stubs ou simuladores, para isolar dependências externas em testes apropriados.

**D)** Restringir o isolamento de dependências a testes manuais de aceitação, sem uso de automação.

---

### 15.

Uma equipe automatizou o mesmo cálculo de regras de desconto em dezenas de cenários de UI e em testes rápidos de serviço. Os testes de interface são lentos e frequentemente quebram após alterações visuais. Qual é a melhoria MAIS compatível com a estratégia descrita?

**A)** Revisar a redundância e deslocar verificações adequadas da lógica para níveis inferiores, preservando cenários de UI relevantes para o usuário.

**B)** Remover todos os testes de interface, incluindo navegação, design e acessibilidade, porque qualquer cobertura inferior os substitui.

**C)** Duplicar os testes de UI em todos os navegadores disponíveis, independentemente da criticidade dos fluxos.

**D)** Manter as redundâncias sem revisão, pois a quantidade total é a principal medida de eficiência da pirâmide.

---

### 16.

Uma estratégia de testes utiliza grande volume de testes unitários, quantidade intermediária de testes de serviço e uma suíte menor de interface. Qual justificativa explica MELHOR o formato proposto no documento?

**A)** Os testes superiores dispensam qualquer execução sempre que a base alcançar alta cobertura de código.

**B)** Os níveis inferiores tendem a oferecer feedback mais rápido e econômico, enquanto verificações de interface mais abrangentes permanecem em menor volume.

**C)** Os testes de integração devem ser evitados, pois apenas testes unitários e de interface avaliam requisitos reais.

**D)** A distribuição decorre de uma exigência numérica fixa, válida para todos os sistemas e estágios de maturidade.

---

### 17.

Em um projeto novo, o time escreve testes para funções antes de implementar essas funções e utiliza o resultado para orientar a construção de código modular. Qual prática mencionada no material está sendo aplicada?

**A)** Desenvolvimento orientado a testes (TDD), apoiado pela elaboração antecipada de testes de unidade.

**B)** Teste de usabilidade, cujo objetivo principal é validar a experiência real de navegação.

**C)** Teste de interface, pois todo teste criado antes do código pertence ao topo da pirâmide.

**D)** Paralelização de testes de UI, que pressupõe escrever todos os testes depois da implementação.

---

### 18.

Após implantar automação em diferentes camadas, um time percebe que alguns scripts estão desatualizados e a cobertura numérica aumentou sem melhora perceptível dos resultados. Qual conjunto de práticas melhor responde ao problema segundo o documento?

**A)** Avaliar apenas o total de scripts e deixar a atualização deles para a próxima grande versão.

**B)** Substituir critérios de aceite por porcentagens fixas de distribuição da pirâmide.

**C)** Manter os scripts desatualizados desde que a execução no pipeline termine rapidamente.

**D)** Atualizar os testes, acompanhar cobertura e outras métricas de eficácia, revisar o ciclo e estabelecer critérios de aceite claros.

---

### 19.

Uma organização identifica a forma de guarda-chuva: somente testes de UI. Os testes inferiores ainda não podem ser implementados, mas há tempo para melhorar a confiabilidade da suíte atual. Qual opção descreve corretamente a abordagem recomendada?

**A)** Tratar a configuração atual como pirâmide ideal e aumentar o volume de UI sem modificar os scripts existentes.

**B)** Reclassificar os testes de UI como unitários para atender visualmente ao modelo de pirâmide.

**C)** Reduzir tempo de execução e instabilidade com execução paralela, manutenção de seletores, investigação de falhas e prioridade a cenários críticos.

**D)** Eliminar imediatamente a UI automatizada e aguardar até que a camada de serviços seja tecnicamente viável.

---

### 20.

Uma equipe pretende reduzir drasticamente o número de testes de interface após fortalecer os testes de unidade e integração. Ela também precisa preservar a confiança dos usuários na navegação, na acessibilidade e na facilidade de uso. Que decisão equilibra MELHOR os objetivos apresentados no material?

**A)** Eliminar os testes de usabilidade e acessibilidade, pois a integração de componentes já assegura a experiência final.

**B)** Manter uma camada superior enxuta e relevante para a experiência do usuário, enquanto amplia verificações rápidas de unidade e integração.

**C)** Usar exclusivamente UI para avaliar as regras de negócio, ainda que os serviços permitam testes mais rápidos e estáveis.

**D)** Transferir todos os testes de integração para unidades isoladas, sem verificar a comunicação real entre módulos.

---

## GABARITO COMENTADO

| Nº | Resposta | Explicação | Referência no documento |
|:--:|:--:|---|---|
| 1 | **C** | O cone de sorvete concentra muitos testes de UI e poucos de unidade. O material recomenda transferir gradualmente cenários adequados para API ou integração e fortalecer a base, sem afirmar que toda UI deva ser eliminada. | 3.1 e 3.2, pp. 10–12 |
| 2 | **A** | O defeito aparece na interação entre módulos que funcionam separadamente. O meio da pirâmide é destinado a verificar integração, comunicação, interfaces e fluxo de dados ou controle. | 1.1.2, pp. 6–7 |
| 3 | **D** | O documento destaca a velocidade, o isolamento de problemas e o apoio dos testes unitários à refatoração e à detecção de regressões. | 1.1.1, p. 5 |
| 4 | **B** | Quando camadas inferiores não são viáveis, o material recomenda otimizar os testes de UI existentes com paralelização, manutenção proativa, estabilização e priorização dos cenários críticos. | 3.1 e 3.2, pp. 10–12 |
| 5 | **D** | A experiência de navegação e acessibilidade está associada principalmente aos testes de interface e usabilidade, no topo. Rapidez, isolamento e documentação ativa são benefícios descritos para testes unitários. | 1.1.1 e 1.1.3, pp. 5 e 7 |
| 6 | **C** | O material destaca a detecção de erros de interface, problemas no fluxo de dados e erros silenciosos como benefícios dos testes de integração. | 1.1.2, p. 6 |
| 7 | **A** | O topo da pirâmide abrange experiência do usuário, design, navegação, usabilidade e acessibilidade. O êxito nas camadas inferiores não substitui essa avaliação. | 1.1.3, pp. 7–8 |
| 8 | **B** | O texto relaciona integração contínua à execução automatizada a cada alteração e enfatiza os testes rápidos da base como mecanismo de feedback precoce. | 2, p. 9 |
| 9 | **C** | O texto apresenta 70/20/10 como exemplo de meta e afirma explicitamente que as proporções devem ser ajustadas conforme a complexidade, as prioridades, os recursos e o cronograma. | 3.2, p. 11 |
| 10 | **D** | A ampulheta concentra testes na base e no topo, com deficiência na camada de serviço. O material recomenda fortalecer o meio e transferir verificações apropriadas para níveis inferiores. | 3.1 e 3.2, pp. 10–12 |
| 11 | **B** | O material cita avaliação inicial de desempenho em integração e avaliação da performance da interface no topo. Portanto, não determina exclusividade de uma dessas camadas. | 1.1.2 e 1.1.3, pp. 6–7 |
| 12 | **A** | O mapeamento inicial gera uma referência quantitativa e qualitativa, permitindo comparar o estado atual às metas e reconhecer gargalos e lacunas. | 3.2, p. 11 |
| 13 | **D** | A definição do estado-alvo deve ser realista e considerar prazo, equipe, ferramentas, infraestrutura e prioridades de negócio, envolvendo as partes interessadas. | 3.2, p. 11 |
| 14 | **C** | O texto recomenda dublês de teste (mocks, stubs e simuladores) para isolar dependências externas ao fortalecer a automação de unidade e serviço. | 3.2, p. 11 |
| 15 | **A** | O material propõe eliminar redundâncias, migrar cenários elegíveis de UI para API/integração e manter atenção aos testes de interface e usabilidade relevantes. | 1.1.3 e 3.2, pp. 7 e 11–12 |
| 16 | **B** | A lógica da pirâmide é favorecer maior volume nos níveis rápidos e econômicos e menor volume no topo, que tende a ser mais complexo e custoso, preservando a complementaridade. | 1.1 e 3.1, pp. 4 e 10 |
| 17 | **A** | O texto relaciona a base da pirâmide ao desenvolvimento orientado a testes (TDD), no qual os testes são escritos antes da implementação para favorecer código modular e manutenção. | 1.1.1, p. 5 |
| 18 | **D** | O material recomenda manutenção regular, critérios de aceite, acompanhamento de métricas e avaliação recorrente do ciclo para aperfeiçoar a estratégia. | 2, p. 9 |
| 19 | **C** | No guarda-chuva, a dependência exclusiva da UI leva a lentidão e manutenção cara. Se os níveis inferiores não forem viáveis, deve-se otimizar a UI existente, conforme as ações detalhadas no documento. | 3.1 e 3.2, pp. 10–12 |
| 20 | **B** | O documento sustenta uma distribuição balanceada: testes inferiores numerosos e rápidos e uma camada superior menor, mas indispensável para aspectos de interface, usabilidade e acessibilidade. | 1.1.2, 1.1.3 e 3, pp. 6–10 |

---

## Referência

BSTQB — *Pirâmide de Teste*, Material de Apoio para Estudo, versão 1.0, 14 de julho de 2025, 14 páginas.

Questões autorais elaboradas exclusivamente a partir do documento fornecido. Este simulado **não** corresponde a questões oficiais da prova ISTQB/CTFL.
