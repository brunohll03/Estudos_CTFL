# SIMULADO CTFL 4.0 — CAPÍTULO 4 (20 QUESTÕES)

---

## Instruções

- **Capítulo:** 4 — Análise e Modelagem de Teste (seções 4.1 a 4.5.3).
- **Dificuldade:** difícil, no estilo da certificação ISTQB/BSTQB CTFL 4.0.
- **Níveis cognitivos:** K2 (compreender) e K3 (aplicar).
- **Formato:** quatro alternativas (A, B, C e D), com **uma única resposta correta**.
- **Tempo sugerido:** 40 minutos.
- **Gabarito comentado apenas após a questão 20**. Não há títulos com os temas das perguntas.

---

## QUESTÕES

### 1.

Uma equipe precisa preparar testes para uma API. Primeiro, define entradas com base no contrato; depois, cria testes para exercitar ramificações do código; por fim, inclui ataques inspirados em defeitos semelhantes vistos em projetos anteriores. Como classificar essas três abordagens, respectivamente?

**A)** Baseada na experiência, caixa-branca e caixa-preta.

**B)** Caixa-branca, caixa-preta e baseada na experiência.

**C)** Caixa-preta, caixa-branca e baseada na experiência.

**D)** Caixa-preta, baseada na experiência e caixa-branca.

---

### 2.

Um campo aceita apenas idades inteiras de 0 a 100. As respostas previstas são: 'menor' de 0 a 17, 'adulto' de 18 a 64, 'idoso' de 65 a 100, e 'inválido' fora do intervalo. Quantas partições de equivalência distintas existem para esse campo, considerando valores inteiros?

**A)** 5 partições.

**B)** 6 partições.

**C)** 4 partições.

**D)** 3 partições.

---

### 3.

Um formulário contém dois parâmetros independentes. O primeiro possui três partições de equivalência; o segundo possui duas. Para satisfazer SOMENTE a cobertura 'cada escolha' (each choice), sem exigir todas as combinações, qual é o número MÍNIMO de casos de teste?

**A)** 5 casos de teste.

**B)** 6 casos de teste.

**C)** 2 casos de teste.

**D)** 3 casos de teste.

---

### 4.

Um benefício é válido exclusivamente para clientes com idade inteira entre 21 e 65 anos, inclusive. Considerando análise de valor-limite de DOIS valores nas fronteiras da única faixa válida, qual conjunto contém exatamente os dados necessários?

**A)** 20, 21, 22, 64, 65 e 66.

**B)** 20, 21, 65 e 66.

**C)** 19, 20, 66 e 67.

**D)** 21, 22, 64 e 65.

---

### 5.

Uma regra aceita quantidades inteiras entre 10 e 20, inclusive. Qual conjunto representa 100% dos itens de cobertura da análise de valor-limite de TRÊS valores para as duas fronteiras dessa faixa?

**A)** 10, 11, 19 e 20.

**B)** 9, 10, 11, 19, 20 e 21.

**C)** 9, 10, 20 e 21.

**D)** 8, 9, 10, 20, 21 e 22.

---

### 6.

Para a faixa inteira de 10 a 20, inclusive, um conjunto de testes de análise de valor-limite de TRÊS valores executou somente 9, 10, 19 e 20. Qual a cobertura alcançada considerando os itens das duas fronteiras?

**A)** 4 de 4 itens, ou 100%.

**B)** 2 de 6 itens, aproximadamente 33,3%.

**C)** 4 de 6 itens, aproximadamente 66,7%.

**D)** 4 de 5 itens, ou 80%.

---

### 7.

Um serviço aprova uma operação somente quando a conta está ativa E o saldo é suficiente. Todas as quatro combinações entre essas duas condições são possíveis. A equipe executou três combinações distintas. Qual a cobertura das regras de uma tabela de decisão completa, sem minimização?

**A)** 25%, porque somente uma ação aprova a operação.

**B)** 50%.

**C)** 100%, se o resultado 'aprovado' foi observado.

**D)** 75%.

---

### 8.

Uma tabela determina que uma compra será recusada sempre que o cadastro estiver suspenso, independentemente de haver cupom. Para cadastro ativo, a presença do cupom afeta o desconto. Qual simplificação é CORRETA para as regras com cadastro suspenso?

**A)** Fundir as duas regras em uma, representando o cupom como condição irrelevante (‘–’).

**B)** Marcar a existência de cupom como combinação inviável (‘N/A’) para cadastro suspenso.

**C)** Manter obrigatoriamente as duas regras porque cada condição booleana deve ocupar colunas diferentes.

**D)** Remover todas as regras de cadastro suspenso, pois são negativas.

---

### 9.

Um documento começa no estado Rascunho. São permitidas as transições: Rascunho→Em revisão (enviar); Em revisão→Rascunho (devolver); Em revisão→Aprovado (aprovar); Aprovado→Arquivado (arquivar). Qual sequência ÚNICA de eventos cobre todas as transições válidas pelo menos uma vez, partindo de Rascunho?

**A)** enviar, aprovar, arquivar.

**B)** enviar, devolver, enviar, aprovar, arquivar.

**C)** devolver, enviar, aprovar, arquivar.

**D)** enviar, devolver, aprovar, arquivar.

---

### 10.

Uma máquina de estados possui três estados alcançáveis: Pendente, Ativo e Bloqueado. Suas únicas transições válidas são Pendente→Ativo, Ativo→Bloqueado e Bloqueado→Ativo. Um teste percorre Pendente→Ativo→Bloqueado. Qual cobertura é obtida?

**A)** 2/3 dos estados e 100% das transições válidas.

**B)** 100% dos estados e 100% das transições válidas.

**C)** 100% dos estados e 2/3 das transições válidas.

**D)** 2/3 dos estados e 2/3 das transições válidas.

---

### 11.

Considere o pseudocódigo: `se autorizado: emitir_recibo()` e, após o bloco condicional, `registrar_tentativa()`. Um único teste com autorizado = verdadeiro executa todas as instruções executáveis. Qual afirmação é a MAIS apropriada?

**A)** Há 100% de cobertura de instruções, mas o resultado falso da decisão não foi exercitado.

**B)** Há necessariamente 100% de cobertura de ramificações porque todas as instruções foram executadas.

**C)** A cobertura de instruções não pode ser calculada em códigos que possuem condicionais.

**D)** Não há 100% de cobertura de instruções porque a condição falsa não executa nenhum comando próprio.

---

### 12.

Considere as relações entre cobertura de instruções e cobertura de ramificações definidas no CTFL 4.0. Qual afirmação está CORRETA?

**A)** 100% de cobertura de instruções implica 100% de cobertura de ramificações, mas não o contrário.

**B)** As duas coberturas são sempre numericamente iguais quando existem decisões booleanas.

**C)** Cobertura de ramificações mede exclusivamente instruções com defeitos identificados.

**D)** 100% de cobertura de ramificações implica 100% de cobertura de instruções, mas o contrário não é garantido.

---

### 13.

Uma implementação não contém uma funcionalidade obrigatória especificada nos requisitos. A equipe executa testes estruturais com alta cobertura sobre todo o código existente. Qual limitação é MAIS relevante?

**A)** Os testes de caixa-branca não podem detectar defeitos quando a especificação está incompleta.

**B)** A cobertura estrutural prova que o software atende às necessidades de negócio, desde que todos os ramos sejam exercitados.

**C)** Qualquer requisito omitido será identificado automaticamente com 100% de cobertura de ramificações.

**D)** A técnica pode não revelar a omissão de funcionalidades ausentes do código, apesar da alta cobertura estrutural.

---

### 14.

Após várias falhas anteriores relacionadas a fusos horários, uma QA decide testar novamente datas em viradas de horário de verão, apesar de não haver indicação explícita desses casos na história. Qual técnica está sendo usada PRINCIPALMENTE?

**A)** Tabela de decisão, pois todo problema temporal possui combinações booleanas.

**B)** Suposição de erro, orientada pelo histórico de falhas e conhecimento da testadora.

**C)** Particionamento de equivalência, porque se trata necessariamente de uma única classe válida.

**D)** Cobertura de ramificação, pois datas sempre representam decisões de código.

---

### 15.

Uma tester recebe a missão de investigar o fluxo de recuperação de senha, com pouca documentação disponível. Em uma sessão de 45 minutos, projeta e executa testes enquanto aprende sobre o sistema; registra descobertas e faz uma conversa de encerramento. Qual caracterização é MAIS precisa?

**A)** Inspeção formal, pois existe registro das observações da sessão.

**B)** Teste baseado em checklist, porque todas as entradas são conhecidas antecipadamente.

**C)** Teste exploratório organizado em sessão, com objetivo, intervalo de tempo e avaliação contínua.

**D)** Teste de confirmação, já que a sessão precisa verificar uma correção específica.

---

### 16.

Uma equipe mantém uma lista de pontos para testar acessibilidade. Após novas falhas encontradas em produção, quer aprimorar a lista sem transformá-la num roteiro excessivamente prescritivo. Qual ação está MAIS alinhada ao syllabus?

**A)** Atualizar periodicamente os itens com base nos defeitos observados, mantendo verificações específicas e administráveis.

**B)** Substituir os itens verificáveis por objetivos vagos, como 'validar toda a qualidade'.

**C)** Congelar a lista permanentemente para garantir que o comportamento dos testadores nunca mude.

**D)** Transferir para a lista somente condições de entrada e saída do processo de testes.

---

### 17.

Uma história diz: 'Como cliente, quero acompanhar meus pedidos para saber quando receber a entrega'. Na reunião, negócio esclarece as expectativas, desenvolvimento discute restrições e QA propõe exemplos que confirmam o comportamento esperado. Qual associação dos três C's está CORRETA?

**A)** Card contém somente critérios técnicos; Conversation é executada pelo QA; Confirmation descreve os recursos do sprint.

**B)** Card é o conjunto de defeitos; Conversation define o código; Confirmation corresponde à cobertura estrutural.

**C)** Card define todos os testes; Conversation substitui documentação; Confirmation equivale à aprovação em produção.

**D)** Card registra a história; Conversation constrói entendimento; Confirmation expressa os critérios de aceite.

---

### 18.

Uma equipe registra um critério de aceite como 'Dado que o usuário está autenticado; quando solicitar o extrato; então o sistema deve apresentar as transações do período'. Qual classificação está MAIS adequada?

**A)** Critério de saída de testes, pois determina quando terminar a execução.

**B)** Critério de cobertura de ramificações, pois contém pré-condições.

**C)** Critério de aceite orientado a cenário, usando Dado/Quando/Então.

**D)** Critério orientado a regra, pois toda condição escrita é uma regra independente.

---

### 19.

Uma equipe está adotando ATDD para uma história de reembolso. Qual sequência representa MELHOR essa abordagem?

**A)** Negócio, desenvolvimento e QA discutem critérios; derivam testes de aceite antes da implementação; implementam e executam os testes.

**B)** QA automatiza exclusivamente cenários positivos e dispensa testes negativos para cumprir o requisito de agilidade.

**C)** O PO escreve testes unitários durante a implementação e transforma sua execução em substituto da validação de negócio.

**D)** Desenvolvedores implementam toda a funcionalidade; QA define depois critérios de aceite; negócio apenas aprova a entrega.

---

### 20.

Uma loja virtual tem estas regras: entregas para cidades NÃO atendidas impedem a conclusão do pedido; para cidades atendidas, o frete é gratuito quando o total é maior ou igual a R$ 150; abaixo disso, o frete custa R$ 15. Qual conjunto de testes de aceite oferece a cobertura MAIS adequada dessas três decisões?

**A)** Cidade atendida/R$ 149 → frete grátis; atendida/R$ 150 → frete R$ 15; não atendida/R$ 200 → impedido.

**B)** Cidade atendida/R$ 149 → frete R$ 15; atendida/R$ 150 → frete grátis; não atendida/R$ 200 → pedido impedido.

**C)** Cidade atendida/R$ 150 → frete grátis; atendida/R$ 180 → frete grátis; não atendida/R$ 200 → impedido.

**D)** Cidade atendida/R$ 149 → frete R$ 15; atendida/R$ 150 → frete grátis; não atendida/R$ 200 → frete R$ 15.

---

## GABARITO COMENTADO

| Questão | Resposta | Explicação |
|:---:|:---:|---|
| 1 | **C** | A especificação sustenta caixa-preta; a estrutura interna sustenta caixa-branca; o histórico de defeitos fundamenta técnicas baseadas na experiência. |
| 2 | **A** | Existem três partições válidas (0–17, 18–64 e 65–100) e duas inválidas (abaixo de 0 e acima de 100): cinco ao todo. |
| 3 | **D** | Com três testes é possível cobrir as três partições do primeiro parâmetro e, ao mesmo tempo, as duas do segundo. Cobertura 'cada escolha' não exige as seis combinações. |
| 4 | **B** | Em BVA de dois valores são testados o próprio limite da partição e seu vizinho na partição adjacente: 20/21 e 65/66. |
| 5 | **B** | A análise de três valores contempla cada limite e seus dois vizinhos imediatos: 9, 10, 11 e 19, 20, 21. |
| 6 | **C** | Os itens são 9, 10, 11, 19, 20 e 21. Quatro dos seis foram exercitados: 4/6 ≈ 66,7%. |
| 7 | **D** | Duas condições booleanas independentes geram quatro regras viáveis. Exercitar três das quatro colunas corresponde a 3/4 = 75% de cobertura. |
| 8 | **A** | Se a presença do cupom não altera o resultado quando o cadastro está suspenso, as duas colunas podem ser unificadas com um traço para condição irrelevante; isso difere de uma condição inviável. |
| 9 | **B** | Para exercitar a devolução e ainda alcançar a aprovação, é preciso voltar a Em revisão: enviar → devolver → enviar → aprovar → arquivar. |
| 10 | **C** | Os três estados foram visitados, mas a transição Bloqueado→Ativo não foi exercitada. Portanto, estados = 3/3 e transições válidas = 2/3. |
| 11 | **A** | Com autorizado verdadeiro, ambas as instruções são executadas. O ramo em que a condição é falsa continua não exercitado, embora todas as instruções executáveis tenham sido cobertas. |
| 12 | **D** | A cobertura de ramificações subsume a de instruções: todos os ramos exercitados garantem todas as instruções executáveis exercitadas, mas não ocorre necessariamente o inverso. |
| 13 | **D** | A caixa-branca avalia a implementação existente; defeitos por omissão de requisitos podem escapar, pois não há código para exercitar a funcionalidade ausente. |
| 14 | **B** | A suposição de erro utiliza experiência sobre falhas anteriores, comportamentos comuns e erros recorrentes para imaginar condições capazes de expor problemas. |
| 15 | **C** | No teste exploratório, aprendizado, projeto, execução e avaliação ocorrem simultaneamente. Sessões podem ter charter, timebox, registro e debriefing. |
| 16 | **A** | Listas de verificação devem ser específicas e revisadas regularmente com base em defeitos e conhecimento novo, evitando itens vagos ou listas extensas demais. |
| 17 | **D** | Os 3 C's são Card, Conversation e Confirmation: registro da história, diálogo colaborativo e critérios usados para confirmar sua aceitação. |
| 18 | **C** | O formato Dado/Quando/Então organiza contexto, ação e resultado esperado, caracterizando critério de aceite orientado a cenário. |
| 19 | **A** | No ATDD os interessados colaboram para esclarecer critérios e criar testes de aceite antes de desenvolver a história; os testes podem ser manuais ou automatizados. |
| 20 | **B** | A primeira opção verifica a cobrança abaixo de 150, a gratuidade exatamente no limite e o bloqueio de uma cidade não atendida. As outras opções erram resultados ou deixam a regra de frete pago sem cobertura. |

---

## Referências

- ISTQB — *Certified Tester Foundation Level Syllabus*, v4.0.1, capítulo 4, páginas 38–46: https://istqb.org/wp-content/uploads/2024/11/ISTQB_CTFL_Syllabus_v4.0.1.pdf
- BSTQB — *CTFL 4.0*, capítulo 4 em português: https://bstqb.qa/files/syllabus_ctfl_4.0br.pdf

**Observação:** questões autorais para estudo, não extraídas de exames oficiais.
