# SIMULADO CTFL 4.0 – CAPÍTULO 2 (20 questões)

## Testes ao longo do Ciclo de Vida de Desenvolvimento de Software

---

## Instruções

- **Abrangência:** itens 2.1 a 2.3.1 do syllabus CTFL 4.0.
- **Dificuldade:** difícil, com cenários práticos e pegadinhas conceituais.
- **Níveis cognitivos:** K1 e K2, conforme os objetivos de aprendizagem do capítulo.
- **Formato:** 20 questões, com quatro alternativas (A, B, C e D), apenas uma correta.
- **Tempo sugerido:** 30 minutos.
- **Gabarito comentado:** ao final do documento.

---

## QUESTÕES

### 1. Ciclo de vida e momento dos testes (2.1.1)

Uma organização migra de um modelo sequencial, com entrega única após meses de implementação, para entregas incrementais a cada duas semanas. Qual mudança no teste é **MAIS** coerente com essa decisão?

A) Os testes de sistema passam a ser desnecessários porque cada incremento é pequeno.  
B) Toda a análise de teste deve ocorrer apenas depois que o último incremento estiver pronto.  
C) As atividades de teste passam a ocorrer repetidamente ao longo dos incrementos, exigindo feedback frequente e atenção à regressão.  
D) Os testes de aceitação devem ocorrer somente antes da primeira implementação.

---

### 2. Boas práticas entre modelos de desenvolvimento (2.1.2)

Uma empresa mantém dois projetos: um segue o modelo em V e outro usa desenvolvimento ágil. Qual prática deve ser incentivada **EM AMBOS**?

A) Iniciar a análise e a modelagem dos testes o mais cedo possível, de acordo com os artefatos disponíveis.  
B) Executar todos os níveis de teste apenas depois do desenvolvimento integral.  
C) Exigir que os testadores sejam sempre externos à organização.  
D) Proibir revisões de requisitos antes de existirem componentes executáveis.

---

### 3. Abordagens orientadas por testes (2.1.3)

Uma equipe escreve primeiro um teste automatizado para um pequeno comportamento, implementa o mínimo necessário para fazê-lo passar e refatora o código. Que abordagem está sendo aplicada **PRINCIPALMENTE**?

A) ATDD, pois todo teste escrito antes do código é necessariamente de aceite.  
B) BDD, pois o uso de testes automatizados exige linguagem de negócio.  
C) Desenvolvimento em cascata, porque a implementação segue uma especificação anterior.  
D) TDD, baseado em um ciclo de teste, implementação e refatoração.

---

### 4. Diferenças entre TDD, BDD e ATDD (2.1.3)

Antes de implementar uma funcionalidade, representantes de negócio, desenvolvedores e testadores definem exemplos que serão usados como critérios de aceite testáveis. Qual abordagem é **MAIS** diretamente caracterizada?

A) TDD, pois qualquer critério escrito antes do código é um teste de componente.  
B) ATDD, pois testes e exemplos de aceite ajudam a orientar o desenvolvimento.  
C) Teste de regressão, pois os critérios de aceite só podem verificar funcionalidades existentes.  
D) Teste de manutenção, pois a funcionalidade ainda não foi disponibilizada.

---

### 5. BDD e entendimento compartilhado (2.1.3)

Uma equipe utiliza exemplos de comportamentos escritos em linguagem compreensível para pessoas técnicas e não técnicas, frequentemente estruturados como **Dado/Quando/Então**. Qual afirmação é **MAIS** adequada?

A) A prática caracteriza o BDD e favorece o entendimento compartilhado do comportamento esperado.  
B) A prática elimina a necessidade de testes não funcionais e exploratórios.  
C) A prática caracteriza obrigatoriamente teste caixa-branca.  
D) A prática é incompatível com automação, porque depende de linguagem natural.

---

### 6. DevOps e automação (2.1.4)

Uma empresa adotou integração e entrega contínuas. O gerente conclui que não será mais necessário testar manualmente nenhuma funcionalidade, pois o pipeline executará verificações automatizadas. Qual resposta é **MAIS** apropriada?

A) Correto, porque DevOps substitui todos os testes não automatizados por monitoramento.  
B) Correto, desde que a implantação seja automática e diária.  
C) Incorreto, porque DevOps proíbe automação dos testes de aceitação.  
D) Incorreto, porque a automação favorece feedback rápido, mas nem todas as avaliações de qualidade são adequadas à automação.

---

### 7. Riscos da adoção de DevOps (2.1.4)

Uma equipe acelera as entregas com pipelines automatizados, mas percebe que uma falha em testes intermitentes bloqueia implantações e que os ambientes de teste nem sempre reproduzem produção. Que conclusão está **MAIS** alinhada ao syllabus?

A) DevOps torna irrelevante a estabilidade dos ambientes porque as entregas são frequentes.  
B) O pipeline precisa executar somente testes de componente para evitar gargalos.  
C) A adoção de DevOps traz benefícios, mas exige atenção à estabilidade dos testes, ambientes e recursos de automação.  
D) Um teste intermitente deve ser considerado aprovado quando passa em pelo menos uma execução.

---

### 8. Shift-Left (2.1.5)

Qual iniciativa representa **MELHOR** a abordagem Shift-Left?

A) Transferir todos os testes de sistema para uma equipe externa após a publicação.  
B) Revisar requisitos e critérios de aceitação antes da implementação, além de executar verificações antecipadas.  
C) Executar os mesmos testes de regressão somente no último dia da sprint.  
D) Substituir os testes dinâmicos por revisões estáticas em todas as situações.

---

### 9. Limites do Shift-Left (2.1.5)

Após investir em revisões de requisitos e testes de componentes antecipados, o líder propõe eliminar testes de sistema e aceitação. Qual avaliação é **MAIS** correta?

A) A proposta é inadequada: antecipar testes não significa eliminar avaliações necessárias nos estágios posteriores.  
B) A proposta é correta porque defeitos detectados cedo deixam de existir em níveis mais altos.  
C) A proposta é correta somente quando os testes de componente atingem 100% de cobertura de instruções.  
D) A proposta é obrigatória em projetos ágeis e DevOps.

---

### 10. Retrospectivas e melhoria contínua (2.1.6)

Ao final de uma iteração, a equipe percebe que requisitos ambíguos causaram repetidos retrabalhos. Qual ação aproveita **MELHOR** a retrospectiva como instrumento de melhoria?

A) Registrar os culpados e transferir a responsabilidade por futuras ambiguidades ao QA.  
B) Aumentar o número de testes executados no final, mantendo inalterada a definição dos requisitos.  
C) Encerrar o tema após identificar o problema, porque retrospectivas não devem gerar ações.  
D) Definir uma prática de revisão colaborativa dos critérios de aceitação e acompanhar sua efetividade nas próximas iterações.

---

### 11. Nível de teste: componente (2.2.1)

Um desenvolvedor executa verificações isoladas em uma função responsável por calcular descontos, substituindo dependências externas por objetos simulados. Qual nível de teste é **MAIS** provável?

A) Integração de sistemas.  
B) Sistema.  
C) Componente.  
D) Aceitação.

---

### 12. Integração de componentes versus integração de sistemas (2.2.1)

Em um produto, os módulos internos **Pagamento** e **Pedidos** são conectados e testados. Depois, a aplicação completa é testada em comunicação com um serviço externo de antifraude. Quais níveis correspondem, respectivamente, aos dois testes?

A) Sistema e componente.  
B) Integração de componentes e integração de sistemas.  
C) Aceitação e componente.  
D) Integração de sistemas e integração de componentes.

---

### 13. Teste de sistema versus aceite (2.2.1)

Um portal foi testado como produto completo pela equipe técnica, incluindo fluxos ponta a ponta e requisitos não funcionais. Em seguida, representantes do negócio verificaram se ele estava pronto para uso operacional conforme critérios de aceite. Quais níveis estão representados, **RESPECTIVAMENTE**?

A) Sistema e aceitação.  
B) Integração de componentes e sistema.  
C) Aceitação e integração de sistemas.  
D) Componente e aceitação.

---

### 14. Objeto e objetivo do nível de teste (2.2.1)

Uma equipe quer verificar o comportamento de um aplicativo completo, incluindo processamento de entradas pela interface e respostas percebidas pelo usuário, sem que o objetivo principal seja verificar comunicação com sistemas externos. Qual nível é **MAIS** adequado?

A) Teste de componente.  
B) Teste de integração de componentes.  
C) Teste de integração de sistemas.  
D) Teste de sistema.

---

### 15. Tipos de teste: funcional e não funcional (2.2.2)

Um analista verifica se uma transferência bancária é processada no valor correto. Depois mede o tempo de resposta da mesma operação sob carga elevada. Qual classificação corresponde, respectivamente, às duas verificações?

A) Não funcional e funcional.  
B) Funcional e não funcional.  
C) Caixa-branca e confirmação.  
D) Regressão e integração de sistemas.

---

### 16. Tipos de teste versus níveis (2.2.2)

Qual afirmação diferencia **CORRETAMENTE** tipo de teste e nível de teste?

A) Teste funcional é um nível, enquanto teste de sistema é um tipo.  
B) Testes não funcionais só podem ser realizados no nível de sistema.  
C) Níveis organizam o teste conforme o objeto e os objetivos; tipos classificam características ou abordagens verificadas e podem aparecer em diferentes níveis.  
D) Caixa-preta e caixa-branca são níveis de teste executados após o teste de integração.

---

### 17. Caixa-preta versus caixa-branca (2.2.2)

Dois testadores avaliam a mesma regra. O primeiro deriva casos exclusivamente dos requisitos, sem considerar a implementação; o segundo seleciona caminhos com base na estrutura interna do código. Qual associação é **CORRETA**?

A) Primeiro: caixa-preta; segundo: caixa-branca.  
B) Primeiro: caixa-branca; segundo: caixa-preta.  
C) Ambos: caixa-preta, pois o sistema é o mesmo.  
D) Ambos: caixa-branca, pois qualquer teste automatizado verifica código.

---

### 18. Confirmação e regressão (2.2.3)

Um defeito fazia uma API retornar HTTP 500 ao receber um identificador válido. Depois da correção, o QA repete o cenário que falhou e também verifica outras operações que poderiam ter sido afetadas pela alteração. Como classificar essas duas iniciativas, **RESPECTIVAMENTE**?

A) Regressão e confirmação.  
B) Sistema e aceite.  
C) Manutenção e integração de componentes.  
D) Confirmação e regressão.

---

### 19. Acionadores dos testes de manutenção (2.3.1)

Um sistema está estável em produção e não recebeu novas funcionalidades, mas precisa migrar para uma nova versão do sistema operacional e atualizar componentes de infraestrutura. Qual conclusão é **MAIS** correta?

A) Não há motivo para testar porque os requisitos funcionais permanecem inalterados.  
B) Alterações de ambiente podem acionar testes de manutenção, inclusive testes de regressão, mesmo sem nova funcionalidade.  
C) Os testes devem se restringir à confirmação de defeitos previamente reportados.  
D) Testes de manutenção somente são acionados pela retirada definitiva de um sistema.

---

### 20. Planejamento de testes de manutenção (2.3.1)

Uma aplicação será parcialmente descontinuada: algumas funcionalidades deixarão de existir e os dados históricos precisam permanecer acessíveis em outro sistema. Qual estratégia de teste é **MAIS** apropriada?

A) Não executar testes, porque descontinuação é uma atividade administrativa.  
B) Testar somente a interface visual remanescente e ignorar os dados históricos.  
C) Avaliar os riscos da retirada, verificar migração ou arquivamento de dados e testar as funcionalidades e integrações impactadas.  
D) Executar exclusivamente testes de componente no código que será removido.

---

## GABARITO COMENTADO

| # | Resp. | Explicação |
|---|:---:|---|
| 1 | **C** | Modelos iterativos e incrementais promovem testes recorrentes, feedback frequente e atenção ao impacto das mudanças. Não eliminam testes de níveis superiores. |
| 2 | **A** | É boa prática iniciar atividades de teste cedo, independentemente do ciclo de vida adotado, adaptando-as aos produtos de trabalho disponíveis. |
| 3 | **D** | TDD costuma seguir o ciclo **vermelho → verde → refatoração**: criar teste que falha, escrever o mínimo de código para passar e melhorar a implementação. |
| 4 | **B** | ATDD utiliza critérios e exemplos de aceitação definidos colaborativamente para orientar a implementação e os testes. |
| 5 | **A** | BDD usa exemplos de comportamento em linguagem compartilhada; Dado/Quando/Então é uma forma frequente de expressá-los. Não elimina outros testes. |
| 6 | **D** | DevOps favorece automação e feedback rápido, mas a avaliação humana, os testes exploratórios e outras atividades podem continuar necessários. |
| 7 | **C** | Pipelines e ambientes instáveis geram riscos e gargalos. A automação exige manutenção, confiabilidade e infraestrutura adequada. |
| 8 | **B** | Shift-Left significa deslocar atividades de teste para momentos mais cedo, por exemplo com revisões antecipadas e verificações antes da integração final. |
| 9 | **A** | Antecipação complementa, mas não substitui automaticamente testes posteriores de integração, sistema e aceitação. |
| 10 | **D** | Retrospectivas devem produzir melhorias concretas e verificáveis; identificar o problema sem acompanhar ações não garante melhoria. |
| 11 | **C** | Testes de componente focam unidades isoladas do software, frequentemente com substituição de dependências por dublês de teste. |
| 12 | **B** | Integração de componentes verifica interfaces entre módulos do produto; integração de sistemas verifica interfaces entre sistemas distintos. |
| 13 | **A** | Teste de sistema avalia o comportamento do sistema completo; teste de aceitação verifica sua adequação a necessidades, critérios e prontidão para uso. |
| 14 | **D** | O foco é o comportamento do sistema completo. A integração com outros sistemas não é o objetivo principal descrito. |
| 15 | **B** | Resultado do cálculo é comportamento funcional; tempo de resposta sob carga é característica não funcional, ligada a desempenho. |
| 16 | **C** | Níveis e tipos são dimensões diferentes. Um mesmo nível pode envolver testes funcionais, não funcionais, caixa-preta e caixa-branca. |
| 17 | **A** | Caixa-preta deriva testes da especificação/comportamento externo; caixa-branca se apoia na estrutura interna. Automação não define essa classificação. |
| 18 | **D** | Confirmação verifica a correção do defeito específico; regressão procura efeitos adversos da alteração em outras partes do sistema. |
| 19 | **B** | Migrações e alterações de ambiente são acionadores típicos de testes de manutenção, mesmo sem mudanças funcionais aparentes. |
| 20 | **C** | A retirada de parte de um sistema também pode exigir testes de manutenção, especialmente de migração/arquivamento de dados e impacto no que permanece em operação. |

---

## REFERÊNCIAS

- ISTQB — *Certified Tester Foundation Level Syllabus*, v4.0.1, capítulo 2: https://istqb.org/wp-content/uploads/2024/11/ISTQB_CTFL_Syllabus_v4.0.1.pdf
- Edição CTFL 4.0 em português: https://isqi.org/media/bf/53/55/1768563732/syllabus_ctfl_4.0br_bp.pdf

> **Observação:** Questões autorais para estudo, não retiradas de provas oficiais. O grau de dificuldade foi elevado nas alternativas, respeitando os níveis cognitivos K1 e K2 previstos para o capítulo.
