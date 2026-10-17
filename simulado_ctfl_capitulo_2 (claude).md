# SIMULADO CTFL 4.0 – Capítulo 2: Teste ao Longo do Ciclo de Vida de Desenvolvimento de Software (30 questões, nível difícil)

---

## Instruções

- 1 alternativa correta
- Nível: K1 e K2, com cenários e pegadinhas
- Gabarito no final, com o motivo de a correta estar certa e de as outras pegarem

---

## QUESTÕES

### 1. Segundo o syllabus, qual das alternativas NÃO é um aspecto diretamente impactado pela escolha do ciclo de vida de desenvolvimento de software (SDLC)?
A) O escopo e o cronograma das atividades de teste  
B) O número de requisitos funcionais do produto  
C) A extensão da automação de testes  
D) O papel e as responsabilidades do testador  

---

### 2. Em um projeto em cascata, a equipe está na fase de requisitos e ainda não existe código executável. O que o testador pode fazer nessa fase?
A) Executar testes dinâmicos de componente sobre um protótipo  
B) Aguardar o código ficar pronto para só então iniciar qualquer atividade de teste  
C) Realizar apenas testes de aceite com os usuários  
D) Participar das revisões de requisitos e iniciar a análise e a modelagem de testes, pois testes dinâmicos ainda não podem ser realizados  

---

### 3. Em um modelo iterativo e incremental, cada iteração entrega um incremento funcional do produto. Qual é a implicação para os testes?
A) Testes estáticos e dinâmicos podem ser feitos em todos os níveis a cada iteração, e a entrega frequente exige feedback rápido e testes de regressão extensivos  
B) Os testes dinâmicos só podem ocorrer ao final da última iteração  
C) A regressão se torna desnecessária, pois cada incremento é um produto novo  
D) Apenas o teste de componente faz sentido, pois os demais níveis exigem o sistema completo  

---

### 4. Em um projeto ágil, em que se supõe que mudanças podem ocorrer ao longo do projeto, qual combinação o syllabus indica como favorecida?
A) Documentação detalhada de teste e análise e modelagem extensivas antes de cada iteração, com ênfase em testes manuais roteirizados  
B) Congelamento dos requisitos para reduzir a necessidade de regressão  
C) Documentação leve dos produtos de trabalho, ampla automação para facilitar a regressão e testes manuais baseados em técnicas de experiência  
D) Testes dinâmicos apenas ao final do projeto, em uma fase dedicada  

---

### 5. Qual das alternativas NÃO é uma boa prática de teste que se aplica a qualquer SDLC?
A) Para cada atividade de desenvolvimento, existe uma atividade de teste correspondente  
B) Concentrar a análise e a modelagem de todos os níveis de teste no fim do projeto, quando o código estiver pronto  
C) Dar a cada nível de teste objetivos específicos, para evitar redundância e manter a abrangência  
D) Envolver os testadores na revisão dos produtos de trabalho assim que os rascunhos estiverem disponíveis  

---

### 6. Qual alternativa associa corretamente a abordagem de desenvolvimento à sua característica?
A) TDD: expressa o comportamento desejado em linguagem natural, no formato Dado/Quando/Então  
B) BDD: escreve primeiro os testes unitários, depois o código, e depois refatora ambos  
C) ATDD: deriva testes dos critérios de aceite como parte do processo de desenho do sistema, escritos antes de a parte relacionada do aplicativo ser desenvolvida  
D) ATDD: os testes de aceite são escritos após a conclusão do código, para validar a entrega  

---

### 7. A equipe escreve cenários no formato "Dado / Quando / Então", em linguagem simples que o Product Owner consegue ler e validar. Esses cenários são então traduzidos automaticamente em testes executáveis. Qual abordagem está sendo usada?
A) BDD  
B) TDD  
C) ATDD  
D) DDD  

---

### 8. Qual característica é comum a TDD, ATDD e BDD?
A) Substituem a necessidade de testes de regressão  
B) Só se aplicam a modelos de desenvolvimento sequenciais  
C) Definem os testes após o código estar pronto, para validá-lo  
D) Definem os testes antes do código, implementando o teste antecipado e o shift-left, e seus testes podem persistir como testes automatizados  

---

### 9. Qual é um benefício do DevOps do ponto de vista dos testes?
A) A eliminação total dos testes manuais, inclusive os feitos da perspectiva do usuário  
B) Feedback rápido sobre a qualidade do código e sobre se as alterações afetam negativamente o código existente  
C) A dispensa de ambientes de teste estáveis, pois o pipeline os recria sempre  
D) A redução do esforço necessário para estabelecer e manter a automação de testes  

---

### 10. Qual é um risco ou desafio do DevOps citado no syllabus?
A) Redução da visão sobre características não funcionais, como performance e confiabilidade  
B) Aumento do risco de regressão em razão da automação  
C) Fim da necessidade de recursos para automação, pois o pipeline gera os testes sozinho  
D) O pipeline de entrega precisa ser definido e estabelecido, as ferramentas de CI/CD precisam ser introduzidas e mantidas, e a automação de testes exige recursos adicionais  

---

### 11. Qual das práticas abaixo NÃO ilustra a abordagem shift-left?
A) Revisar a especificação sob a perspectiva de testes, buscando ambiguidades, incompletude e inconsistências  
B) Escrever os casos de teste antes de o código ser escrito  
C) Adiar a análise estática do código-fonte para depois do teste dinâmico de sistema  
D) Iniciar testes não funcionais já no nível de teste de componente, sempre que possível  

---

### 12. Um gerente, após adotar o shift-left, propõe reduzir os testes de sistema e de aceite. Qual afirmação sobre o shift-left está correta?
A) Testar mais cedo não significa negligenciar os testes posteriores; a abordagem pode exigir treinamento, esforço ou custos adicionais no início, com expectativa de economia no final  
B) O shift-left implica dispensar os testes de sistema e de aceite  
C) O shift-left reduz custos desde o primeiro dia e não exige convencer os stakeholders  
D) O shift-left se restringe aos testes dinâmicos de componente  

---

### 13. Qual afirmação sobre retrospectivas está correta?
A) Ocorrem somente ao final do projeto e envolvem apenas os testadores  
B) Podem ocorrer ao fim de um projeto ou iteração, em um marco de lançamento ou quando necessário; envolvem também desenvolvedores, arquitetos e Product Owner; seus resultados são registrados e, em geral, fazem parte do relatório de conclusão do teste  
C) Servem apenas para listar o que deu certo, pois o que deu errado já foi tratado pela depuração  
D) As melhorias recomendadas são opcionais e dispensam acompanhamento  

---

### 14. Qual das alternativas NÃO é um benefício típico das retrospectivas?
A) Aumento da eficácia e da eficiência do teste  
B) Aumento da qualidade do material de teste  
C) Garantia de que os defeitos remanescentes serão encontrados na iteração seguinte  
D) Melhor cooperação entre desenvolvimento e testes  

---

### 15. Um desenvolvedor testa isoladamente a classe que calcula juros compostos, usando um framework de testes unitários e dublês para as dependências. Qual é o nível de teste?
A) Teste de componente  
B) Teste de integração de componentes  
C) Teste de sistema  
D) Teste de aceite  

---

### 16. A equipe verifica a interação entre o módulo de carrinho e o módulo de estoque por meio de uma interface interna, combinando os módulos de forma bottom-up. Qual é o nível de teste?
A) Teste de componente  
B) Teste de sistema  
C) Teste de integração de sistema  
D) Teste de integração de componentes  

---

### 17. Uma equipe independente executa fluxos de ponta a ponta (cadastro, compra e pagamento simulado) e avalia a usabilidade em um ambiente de teste representativo, tomando como base as especificações do sistema. Qual é o nível de teste?
A) Teste de integração de componentes  
B) Teste de sistema  
C) Teste de aceite  
D) Teste de integração de sistema  

---

### 18. O sistema de e-commerce passa a se comunicar com um gateway de pagamento externo e com a API de uma transportadora. A equipe testa essas interfaces em um ambiente semelhante ao operacional. Qual é o nível de teste?
A) Teste de componente  
B) Teste de integração de componentes  
C) Teste de integração de sistema  
D) Teste de aceite operacional  

---

### 19. Qual afirmação sobre o teste de aceite está correta?
A) Foca na validação e na demonstração da disposição para a implantação, e deve ser realizado, preferencialmente, pelos usuários previstos  
B) Foca nas interfaces entre o sistema e serviços externos  
C) É realizado sempre por desenvolvedores em seus ambientes de desenvolvimento  
D) Deriva exclusivamente da estrutura do código, sendo um teste caixa-branca  

---

### 20. Qual das alternativas NÃO é uma das principais formas de teste de aceite?
A) Teste de aceite do usuário (UAT)  
B) Teste de aceite contratual e normativo  
C) Teste beta  
D) Teste de integração de sistema  

---

### 21. Sobre a relação entre níveis de teste e o SDLC, é correto afirmar:
A) Nos modelos sequenciais, os critérios de saída de um nível geralmente fazem parte dos critérios de entrada do próximo; em alguns modelos iterativos isso pode não se aplicar, e os níveis podem se sobrepor no tempo  
B) Os níveis de teste nunca se sobrepõem no tempo  
C) Em todos os SDLCs, os critérios de saída de um nível são obrigatoriamente os de entrada do seguinte  
D) Um nível de teste é definido unicamente pela ferramenta usada na execução  

---

### 22. A equipe valida que a função de busca responde em até 2 segundos com 500 usuários simultâneos, reaproveitando os mesmos casos funcionais da busca. Qual é a melhor classificação?
A) Teste funcional, avaliando a adequação funcional  
B) Teste não funcional, avaliando a eficiência de performance  
C) Teste não funcional, avaliando a usabilidade  
D) Teste caixa-branca, avaliando a cobertura de decisão  

---

### 23. Qual das alternativas NÃO é uma característica não funcional de qualidade citada na classificação da ISO/IEC 25010 apresentada no syllabus?
A) Compatibilidade  
B) Portabilidade  
C) Adequação funcional  
D) Capacidade de manutenção  

---

### 24. Uma testadora usa a estrutura interna do código (decisões e laços) para derivar testes, com o objetivo de cobrir essa estrutura até um nível aceitável. Qual é o tipo de teste?
A) Teste funcional  
B) Teste não funcional  
C) Teste caixa-preta  
D) Teste caixa-branca  

---

### 25. Sobre tipos de teste e níveis de teste, é correto afirmar:
A) O teste caixa-branca só ocorre no nível de componente, e o teste funcional só nos níveis de sistema e de aceite  
B) Os quatro tipos de teste (funcional, não funcional, caixa-preta e caixa-branca) podem ser aplicados a todos os níveis, com foco diferente em cada um  
C) Os tipos de teste são mutuamente exclusivos em cada nível  
D) O teste não funcional só pode ser feito depois de o sistema completo estar disponível, nunca em nível de componente  

---

### 26. Um defeito de arredondamento foi corrigido e confirmado. Antes de liberar a versão, a equipe quer definir a extensão da regressão. Qual afirmação está correta?
A) O teste de regressão confirma que o defeito original foi corrigido, enquanto o de confirmação verifica consequências adversas  
B) O teste de regressão se restringe ao componente em que a alteração foi feita  
C) É aconselhável fazer antes uma análise de impacto para otimizar a extensão da regressão, pois ela mostra quais partes do software podem ser afetadas  
D) A regressão é desnecessária após uma correção já confirmada  

---

### 27. No fim da sprint, com pouco tempo, um defeito crítico foi corrigido. Qual é a abordagem mínima aceitável para o teste de confirmação, segundo o syllabus?
A) Executar as etapas que deveriam reproduzir a falha e verificar que ela não ocorre mais  
B) Dispensar a confirmação e executar apenas a regressão  
C) Reexecutar todos os testes do sistema  
D) Escrever novos testes de aceite com os usuários  

---

### 28. Qual afirmação sobre testes de regressão e automação está correta?
A) Os conjuntos de regressão são pequenos e estáveis, e a automação deve começar apenas no fim do projeto  
B) A regressão só é necessária no nível de sistema  
C) Com a integração contínua (CI), a regressão torna-se desnecessária  
D) Os conjuntos de regressão são executados muitas vezes e tendem a crescer a cada iteração ou versão, sendo fortes candidatos à automação, que deve começar no início do projeto  

---

### 29. Uma empresa migra seu sistema para outra plataforma e, no mesmo projeto, importa para ele os dados de outro aplicativo. Quais testes de manutenção o syllabus indica como pertinentes?
A) Apenas regressão do software, pois o ambiente é irrelevante  
B) Somente testes de aceite contratual  
C) Testes associados ao novo ambiente e ao software alterado, além de testes de conversão de dados  
D) Somente testes de arquivamento e de restauração  

---

### 30. Uma correção urgente (hot fix) será aplicada ao sistema em produção. Qual afirmação sobre o teste de manutenção está correta?
A) O teste inclui avaliar se a alteração foi bem-sucedida e verificar regressões nas partes inalteradas (geralmente a maior parte do sistema); o escopo depende do risco da mudança, do tamanho do sistema existente e do tamanho da mudança  
B) Hot fixes dispensam testes, pois são versões não planejadas  
C) A análise de impacto só pode ser feita depois de a mudança ser implementada  
D) O escopo depende apenas do tamanho da mudança  

---

## GABARITO

| #  | Resp | Explicação |
|----|------|------------|
| 1  | B | (K2 · 2.1.1) O SDLC impacta: escopo e cronograma dos testes, nível de detalhamento da documentação, técnicas e abordagem, extensão da automação, e papel e responsabilidades do testador. O número de requisitos do produto não está na lista. |
| 2  | D | (K2 · 2.1.1) Em modelos sequenciais, os testadores participam das revisões de requisitos, da análise e da modelagem de testes nas fases iniciais. O código executável só surge depois, então testes dinâmicos não podem ocorrer cedo. **B** erra: há muito a fazer antes do código. |
| 3  | A | (K2 · 2.1.1) Em cada iteração, testes estáticos e dinâmicos podem ocorrer em todos os níveis. A entrega frequente exige feedback rápido e regressão extensiva. **C** inverte: a regressão é ainda mais necessária. |
| 4  | C | (K2 · 2.1.1) Em projetos ágeis são favorecidas a documentação leve e a ampla automação para regressão. Os testes manuais tendem a usar técnicas baseadas na experiência, que não exigem análise e modelagem prévias extensivas. **A** descreve o oposto. |
| 5  | B | (K1 · 2.1.2) A análise e a modelagem de cada nível começam durante a fase de desenvolvimento correspondente, em respeito ao teste antecipado. Concentrá-las no fim viola o princípio. As demais são boas práticas citadas. |
| 6  | C | (K1 · 2.1.3) **A** descreve o BDD, não o TDD; **B** descreve o TDD, não o BDD; **D** contraria o ATDD, em que os testes são escritos antes do desenvolvimento da parte relacionada. |
| 7  | A | (K1 · 2.1.3) O BDD expressa o comportamento em linguagem natural simples, geralmente no formato Dado/Quando/Então, e traduz os casos automaticamente em testes executáveis. **C** é a pegadinha: o ATDD parte dos critérios de aceite. |
| 8  | D | (K1 · 2.1.3) As três abordagens definem os testes antes do código, aplicam o teste antecipado e o shift-left, apoiam o desenvolvimento iterativo, e seus testes podem persistir como automatizados. Não substituem a regressão (**A**). |
| 9  | B | (K2 · 2.1.4) Feedback rápido é um benefício citado. **A** erra: os testes manuais, especialmente da perspectiva do usuário, continuam necessários. **D** erra: a automação exige recursos adicionais e pode ser difícil de manter. |
| 10 | D | (K2 · 2.1.4) Os desafios incluem definir o pipeline, introduzir e manter as ferramentas de CI/CD, e dispor de recursos para a automação. **A** e **B** invertem benefícios: o DevOps aumenta a visão sobre características não funcionais e reduz o risco de regressão. |
| 11 | C | (K2 · 2.1.5) A boa prática é concluir a análise estática **antes** do teste dinâmico (ou como parte de um processo automatizado). As demais ilustram o shift-left. |
| 12 | A | (K2 · 2.1.5) O shift-left sugere testar mais cedo, mas isso não significa negligenciar os testes posteriores. Pode exigir treinamento, esforço ou custos adicionais no início, e é importante convencer os stakeholders. |
| 13 | B | (K2 · 2.1.6) As retrospectivas envolvem vários papéis, ocorrem em momentos variados conforme o SDLC, e seus resultados são registrados, normalmente no relatório de conclusão. Todas as melhorias recomendadas devem ser acompanhadas (**D** erra). |
| 14 | C | (K2 · 2.1.6) Nenhum processo garante que defeitos serão encontrados na iteração seguinte. As demais constam como benefícios, junto com o vínculo e o aprendizado da equipe e a melhoria da qualidade da base de teste. |
| 15 | A | (K2 · 2.2.1) O teste de componente (ou de unidade) testa componentes isoladamente, em geral com frameworks de teste unitário, e normalmente é feito por desenvolvedores em seu ambiente. |
| 16 | D | (K2 · 2.2.1) Interfaces e interações entre componentes, dependendo de estratégias como bottom-up, top-down ou big-bang, caracterizam a integração de componentes. **C** é a pegadinha: a integração de sistema trata de interfaces com outros sistemas e serviços externos. |
| 17 | B | (K2 · 2.2.1) O teste de sistema foca no comportamento geral, com testes funcionais de ponta a ponta e não funcionais (como usabilidade), pode ser feito por equipe independente e se relaciona às especificações do sistema. O uso de simulações de subsistemas é permitido. |
| 18 | C | (K2 · 2.2.1) Interfaces com sistemas e serviços externos, em ambiente semelhante ao operacional, são o foco da integração de sistema. **D** é pegadinha: aceite operacional é uma forma de aceite, não o nível do enunciado. |
| 19 | A | (K2 · 2.2.1) O aceite valida e demonstra a disposição para implantação, preferencialmente pelos usuários previstos. **B** descreve a integração de sistema; **C** descreve o teste de componente. |
| 20 | D | (K1 · 2.2.1) As formas principais são: UAT, aceite operacional, aceite contratual e normativo, teste alfa e teste beta. A integração de sistema é um nível, não uma forma de aceite. |
| 21 | A | (K2 · 2.2) Nos modelos sequenciais, a saída de um nível alimenta a entrada do próximo, mas em alguns modelos iterativos isso pode não valer, e os níveis podem se sobrepor. Os níveis se diferenciam por objeto, objetivos, base, defeitos e falhas, e abordagem e responsabilidades. |
| 22 | B | (K2 · 2.2.2) O teste não funcional avalia "quão bem" o sistema se comporta, e muitos testes não funcionais derivam de testes funcionais, verificando uma restrição não funcional (aqui, o tempo). O tempo de resposta é eficiência de performance. |
| 23 | C | (K2 · 2.2.2) A lista não funcional é: eficiência de performance, compatibilidade, usabilidade, confiabilidade, segurança, capacidade de manutenção e portabilidade. A adequação funcional é objetivo do teste funcional. |
| 24 | D | (K2 · 2.2.2) O teste caixa-branca é baseado na estrutura e deriva testes da implementação ou estrutura interna, para cobrir essa estrutura até o nível aceitável. A caixa-preta deriva dos documentos externos ao objeto de teste. |
| 25 | B | (K2 · 2.2.2) Todos os quatro tipos podem ser aplicados a todos os níveis, embora o foco difira, e várias técnicas podem derivar casos para todos eles. O teste não funcional pode começar cedo, inclusive em componentes (**D** erra). |
| 26 | C | (K2 · 2.2.3) A análise de impacto mostra quais partes podem ser afetadas e ajuda a dimensionar a regressão. **A** inverte confirmação e regressão; **B** erra porque as consequências podem afetar outros componentes, sistemas conectados e o ambiente; **D** erra porque a regressão cobre inclusive correções já confirmadas. |
| 27 | A | (K2 · 2.2.3) Com pouco tempo ou dinheiro, a confirmação pode se restringir a executar as etapas que reproduziam a falha e verificar que ela não ocorre. Com mais folga, executam-se todos os casos que falharam e/ou novos testes, conforme o risco. |
| 28 | D | (K2 · 2.2.3) Regressões são executadas muitas vezes e crescem a cada iteração ou versão. A automação deve começar no início do projeto, e com CI é boa prática incluir regressão automatizada, inclusive em diferentes níveis. |
| 29 | C | (K2 · 2.3) Migração de plataforma exige testes do novo ambiente e do software alterado; migração de dados de outro aplicativo exige testes de conversão de dados. Arquivamento e restauração (**D**) estão ligados à aposentadoria do sistema. |
| 30 | A | (K2 · 2.3) O teste de manutenção avalia o sucesso da mudança e verifica regressões nas partes inalteradas. O escopo depende do risco da mudança e dos tamanhos do sistema e da mudança. A análise de impacto pode ser feita **antes** da alteração, para decidir se ela deve ser feita (**C** erra). |
