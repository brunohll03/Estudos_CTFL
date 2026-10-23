# SIMULADO CTFL 4.0 – CAPÍTULO 3: TESTE ESTÁTICO (20 questões)

---

## Instruções

- 20 questões de dificuldade **difícil**.
- Apenas uma alternativa correta (A, B, C ou D).
- Níveis K1 e K2, de acordo com o syllabus CTFL 4.0.
- Gabarito comentado somente no final.

---

## QUESTÕES

### 1. Produtos de trabalho examináveis
Uma equipe deseja aplicar testes estáticos antes de existir uma versão executável. Qual conjunto contém SOMENTE produtos de trabalho examináveis estaticamente?

A) Requisitos, diagramas de arquitetura e código-fonte ainda não executado.
B) Logs de execução, resultados de carga e falhas observadas em produção.
C) Respostas de uma API em execução, tempos de resposta e consumo de memória.
D) Transações executadas no banco, sessões de usuário e métricas de produção.

---

### 2. Análise estática
Uma ferramenta aponta uma variável atribuída, mas nunca utilizada, sem iniciar a aplicação. Qual classificação é MAIS adequada?

A) Teste dinâmico com cobertura de instruções.
B) Teste estático por análise automatizada.
C) Depuração guiada por execução.
D) Teste de integração estrutural.

---

### 3. Valor do teste estático
Um requisito informa que o pagamento será “processado rapidamente”. A ambiguidade é identificada numa revisão antes da implementação. Qual benefício é MAIS diretamente demonstrado?

A) Eliminação da necessidade de testes de desempenho.
B) Garantia de que o comportamento final não terá falhas.
C) Detecção antecipada de um defeito no produto de trabalho, evitando potencial retrabalho.
D) Comprovação de que os requisitos foram integralmente validados em produção.

---

### 4. Qualidade e comunicação
Durante uma revisão de histórias de usuário, QA, negócio e desenvolvimento descobrem interpretações incompatíveis sobre o limite de transferências. Qual resultado exemplifica MELHOR o valor da revisão?

A) Transferir aos testadores a responsabilidade exclusiva pela regra.
B) Dispensar critérios de aceite, já que houve consenso verbal.
C) Transformar uma revisão em teste dinâmico por envolver desenvolvedores.
D) Construir entendimento comum e melhorar a consistência dos requisitos antes de implementá-los.

---

### 5. Estático versus dinâmico
Um QA encontra uma condição contraditória num fluxograma. Depois, executa o software e observa uma resposta HTTP incorreta. Como classificar, respectivamente, essas observações?

A) Defeito identificável estaticamente e falha observada dinamicamente.
B) Duas falhas dinâmicas, pois ambas afetam o sistema.
C) Dois defeitos que exigem necessariamente execução.
D) Primeiro depuração; depois revisão informal.

---

### 6. Complementaridade dos testes
Um líder afirma que é preciso escolher entre revisões de código e execução de testes, porque ambas detectam exatamente os mesmos problemas. Qual avaliação é MAIS correta?

A) A afirmação procede quando há alta cobertura automatizada.
B) A afirmação procede apenas em sistemas sem interface.
C) Revisões e testes dinâmicos são complementares e podem revelar tipos diferentes de problemas.
D) Revisões detectam somente falhas de desempenho, enquanto testes dinâmicos detectam ambiguidades.

---

### 7. Critério de distinção
Um analista lê o código de uma função para planejar entradas que cubram seus ramos e, em seguida, executa essas entradas. Qual descrição distingue corretamente as atividades?

A) Ambas são estáticas, porque se baseiam na estrutura interna.
B) A leitura é análise sem execução; a execução dos casos planejados é teste dinâmico.
C) Ambas são dinâmicas, porque o objetivo final é avaliar código.
D) A leitura é obrigatoriamente inspeção formal, e a execução é depuração.

---

### 8. Feedback antecipado
Num projeto, representantes de negócio revisam frequentemente protótipos e histórias antes do desenvolvimento. Qual benefício é o MAIS consistente com o syllabus?

A) Evitar que stakeholders solicitem mudanças após a primeira revisão.
B) Aumentar a quantidade de documentação exigida, independentemente do contexto.
C) Garantir aprovação automática de todos os requisitos.
D) Detectar mal-entendidos cedo e permitir ajustes com menor custo potencial.

---

### 9. Feedback frequente
Um time recebe feedback somente após seis meses de implementação. Em outro projeto semelhante, recebe feedback sobre pequenos incrementos a cada sprint. Qual risco tende a ser MENOR no segundo?

A) Descobrir tardiamente que a solução diverge das necessidades dos interessados.
B) Existirem mudanças na percepção dos interessados durante o projeto.
C) Ser necessário esclarecer decisões em algum momento.
D) Precisar executar testes após a implementação.

---

### 10. Planejamento da revisão
Uma revisão formal será iniciada. É necessário definir escopo, objetivos, participantes, critérios de entrada e saída e cronograma. A qual atividade essas decisões pertencem PRINCIPALMENTE?

A) Comunicação e análise.
B) Planejamento.
C) Correção e relatório.
D) Revisão individual.

---

### 11. Iniciação e revisão individual
Após o planejamento, os participantes recebem os documentos e instruções necessárias. Depois, cada revisor examina o material e registra anomalias. Qual é a sequência MAIS apropriada?

A) Revisão individual → planejamento.
B) Comunicação e análise → correção e relatório.
C) Iniciação da revisão → revisão individual.
D) Correção e relatório → iniciação da revisão.

---

### 12. Comunicação e análise
Três revisores registraram a mesma suspeita de inconsistência. A equipe reúne as observações, discute se existe um defeito e define ações necessárias. Qual atividade predomina?

A) Comunicação e análise.
B) Planejamento.
C) Revisão individual.
D) Iniciação da revisão.

---

### 13. Correção e relatório
Após discussão das anomalias, o autor atualiza a especificação. A equipe verifica o tratamento dos achados, registra resultados e avalia critérios de saída. Qual atividade predomina?

A) Iniciação.
B) Revisão individual.
C) Planejamento.
D) Correção e relatório.

---

### 14. Papéis — facilitador
Durante uma revisão formal, uma pessoa conduz a reunião, gerencia tempo e participação e procura manter o debate produtivo. Qual papel descreve MELHOR essa responsabilidade?

A) Autor.
B) Facilitador (moderador).
C) Escriba.
D) Gerente.

---

### 15. Papéis — registro
Uma revisão precisa de alguém que registre anomalias e decisões tomadas durante a reunião. Qual papel é o MAIS diretamente responsável pelo registro?

A) Autor.
B) Gerente.
C) Escriba.
D) Revisor.

---

### 16. Papéis — autor e revisor
Uma pessoa criou a especificação analisada, enquanto outra examina criticamente o documento em busca de anomalias. Qual correspondência é CORRETA?

A) Criador: autor; examinador: revisor.
B) Criador: moderador; examinador: gerente.
C) Criador: escriba; examinador: autor.
D) Criador: revisor; examinador: facilitador.

---

### 17. Walkthrough
Um desenvolvedor conduz colegas por sua própria proposta de solução, explicando decisões e solicitando sugestões. A atividade tem caráter educacional e pode revelar anomalias. Qual tipo de revisão é MAIS compatível?

A) Inspeção.
B) Revisão técnica, necessariamente dirigida por moderador.
C) Análise estática automatizada.
D) Walkthrough (passo a passo).

---

### 18. Inspeção
Uma organização exige revisão com processo rigoroso, papéis definidos, critérios estabelecidos, coleta de métricas e foco explícito em encontrar defeitos. Qual tipo é o MAIS adequado?

A) Revisão informal.
B) Inspeção.
C) Walkthrough.
D) Teste exploratório.

---

### 19. Revisão técnica
Arquitetos e desenvolvedores avaliam uma proposta de integração para discutir abordagens alternativas, confirmar adequação técnica e construir consenso. Qual revisão corresponde MELHOR ao objetivo?

A) Inspeção exclusivamente orientada a métricas.
B) Revisão informal sem objetivo definido.
C) Revisão técnica.
D) Walkthrough necessariamente conduzido pelo autor.

---

### 20. Fatores de sucesso
Em uma revisão, o gerente usa as anomalias encontradas para avaliar negativamente o desempenho individual dos autores. As reuniões tornam-se defensivas e surgem poucos comentários. Qual medida está MAIS alinhada às boas práticas?

A) Criar ambiente de confiança, focar a qualidade do produto e evitar usar resultados para julgar pessoas.
B) Ampliar as reuniões sem definir objetivo ou preparação prévia.
C) Retirar revisores de outras áreas para reduzir divergências.
D) Cancelar o registro de achados para diminuir conflitos.

---

## GABARITO COMENTADO

| # | Resp. | Explicação |
|---|:---:|---|
| 1 | **A** | Requisitos, modelos e código podem ser examinados sem executar o software; as demais alternativas se referem a observações de execução. |
| 2 | **B** | A análise estática automatizada examina código sem executá-lo; variáveis não utilizadas são um exemplo de achado. |
| 3 | **C** | A revisão identifica ambiguidade precocemente e pode evitar retrabalho. Não elimina testes futuros nem garante ausência de falhas. |
| 4 | **D** | Revisões facilitam comunicação, consenso e consistência de requisitos entre os envolvidos. |
| 5 | **A** | Contradição em artefato pode ser detectada estaticamente; resposta HTTP errada é falha observada na execução. |
| 6 | **C** | Testes estáticos e dinâmicos são complementares e podem detectar problemas diferentes. |
| 7 | **B** | A leitura do código ocorre sem execução, enquanto a execução de casos para exercitar ramos é dinâmica. |
| 8 | **D** | Feedback frequente permite detectar divergências de entendimento mais cedo e reduzir possível retrabalho. |
| 9 | **A** | Feedback ao longo do projeto reduz o risco de descobrir somente no final que a solução não atende às necessidades. |
| 10 | **B** | Planejamento define objetivos, participantes, escopo, critérios e organização da revisão. |
| 11 | **C** | A iniciação disponibiliza material e instruções; a revisão individual examina o produto e registra anomalias. |
| 12 | **A** | Comunicação e análise discute achados, examina anomalias e decide ações. |
| 13 | **D** | Correção e relatório envolve tratamento dos achados, acompanhamento, documentação e avaliação dos critérios de saída. |
| 14 | **B** | O facilitador conduz as reuniões e ajuda a manter uma dinâmica produtiva. |
| 15 | **C** | O escriba registra anomalias e decisões da revisão. |
| 16 | **A** | O autor cria o produto de trabalho; o revisor o examina em busca de anomalias. |
| 17 | **D** | No walkthrough, normalmente o próprio autor conduz a apresentação e solicita comentários. |
| 18 | **B** | A inspeção é o tipo de revisão mais formal, com critérios, papéis, estrutura e métricas definidos. |
| 19 | **C** | A revisão técnica pode avaliar alternativas técnicas, promover consenso e identificar defeitos. |
| 20 | **A** | Revisões têm melhores resultados com segurança psicológica, objetivos claros e foco na qualidade do produto, não em culpar pessoas. |

---

## Referência

Syllabus oficial ISTQB/BSTQB CTFL 4.0, capítulo 3, seções **3.1.1 a 3.2.5**. Questões autorais para estudo, não extraídas da prova oficial.
