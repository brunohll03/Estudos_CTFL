# SIMULADO CTFL 4.0 – Capítulo 3: Teste Estático (30 questões, nível difícil)

---

## Instruções

- 1 alternativa correta
- Nível: K1 e K2, com cenários e pegadinhas
- Gabarito no final, com o motivo de a correta estar certa e de as outras pegarem

---

## QUESTÕES

### 1. Segundo o syllabus, qual produto de trabalho NÃO é apropriado para testes estáticos?
A) Itens da lista de pendências do produto (backlog)  
B) Cartas de teste  
C) Código executável de terceiros que não pode ser interpretado por humanos nem analisado por ferramentas, por motivos legais  
D) Contratos e modelos  

---

### 2. Qual afirmação sobre os produtos que podem ser examinados por testes estáticos está correta?
A) Qualquer produto de trabalho que possa ser lido e compreendido pode ser revisado, mas a análise estática exige uma estrutura contra a qual verificá-lo (modelos, código ou texto com sintaxe formal)  
B) A análise estática por ferramenta se aplica a qualquer produto de trabalho, inclusive atas de reunião em texto livre  
C) As revisões só se aplicam ao código-fonte  
D) Planos de teste e casos de teste não podem ser examinados por testes estáticos  

---

### 3. Em uma sessão de refinamento do backlog, testadores, desenvolvedores e representantes do negócio fazem perguntas para garantir que as histórias de usuário atendam à Definição de Pronto (DoR), sejam completas, compreensíveis e tenham critérios de aceite testáveis. Essa atividade é um exemplo de:
A) Teste dinâmico de aceite, pois envolve representantes do negócio  
B) Teste estático, ao aplicar técnicas de revisão aos produtos de trabalho  
C) Depuração, pois corrige defeitos nas histórias  
D) Teste de regressão, pois valida mudanças nos requisitos  

---

### 4. Qual exemplo se enquadra em um defeito que NÃO pode ser detectado por testes dinâmicos, mas pode ser identificado por testes estáticos?
A) Falha de desempenho sob carga elevada  
B) Tempo de resposta acima do limite especificado  
C) Vazamento de memória que só aparece após horas de execução  
D) Código inacessível  

---

### 5. Um gerente questiona o custo de implantar revisões formais no projeto. Qual é a resposta alinhada ao syllabus?
A) As revisões são dispendiosas e, por isso, elevam o custo geral do projeto, sendo justificáveis apenas pela qualidade  
B) Embora implementar revisões possa ser dispendioso, os custos gerais do projeto geralmente são muito menores do que sem revisões, pois se gasta menos tempo e esforço para corrigir defeitos mais tarde  
C) As revisões só compensam quando substituem os testes dinâmicos  
D) O custo das revisões é irrelevante, pois elas não encontram defeitos  

---

### 6. Por que o syllabus recomenda envolver uma grande variedade de participantes nos testes estáticos?
A) Para diluir a responsabilidade e evitar "jogos de culpa"  
B) Para que o teste estático substitua a necessidade de testes dinâmicos  
C) Para criar um entendimento compartilhado entre os stakeholders, melhorar a comunicação e permitir que eles se certifiquem de que os requisitos descrevem suas necessidades reais  
D) Para reduzir o custo de cada revisão individual  

---

### 7. Qual afirmação sobre as diferenças entre testes estáticos e dinâmicos está correta?
A) Os testes estáticos encontram defeitos diretamente, enquanto os dinâmicos causam falhas, a partir das quais os defeitos associados são determinados por análises subsequentes  
B) Os testes estáticos causam falhas, a partir das quais os defeitos são determinados, enquanto os dinâmicos encontram defeitos diretamente  
C) Os testes estáticos só podem ser aplicados a produtos de trabalho executáveis  
D) Estáticos e dinâmicos detectam exatamente os mesmos tipos de defeitos, então um deles é dispensável  

---

### 8. A equipe quer avaliar a capacidade de manutenção e a eficiência de performance do sistema. Qual abordagem está alinhada ao syllabus?
A) Ambas por testes dinâmicos  
B) Ambas por testes estáticos  
C) Capacidade de manutenção por testes dinâmicos; eficiência de performance por testes estáticos  
D) Capacidade de manutenção por testes estáticos, pois não depende da execução do código; eficiência de performance por testes dinâmicos, pois depende dela  

---

### 9. Qual das alternativas NÃO é um defeito típico que seja mais fácil e/ou mais barato de encontrar por testes estáticos?
A) Variáveis não declaradas no código  
B) Lentidão do sistema com 1.000 usuários simultâneos  
C) Número, tipo ou ordem de parâmetros incompatíveis em uma especificação de interface  
D) Contradições e ambiguidades nos requisitos  

---

### 10. Qual afirmação sobre testes estáticos e dinâmicos é VERDADEIRA?
A) O teste estático substitui o dinâmico, por encontrar defeitos diretamente  
B) O teste dinâmico detecta com mais facilidade defeitos em caminhos de código raramente executados  
C) Os dois se complementam: têm objetivos semelhantes, mas alguns tipos de defeito só são encontrados por um ou por outro  
D) O teste estático só pode ser realizado quando já existe código executável  

---

### 11. Qual das alternativas NÃO é um benefício do feedback antecipado e frequente dos stakeholders?
A) Eliminar a necessidade de testes dinâmicos de aceite ao final do projeto  
B) Evitar mal-entendidos sobre os requisitos  
C) Garantir que as alterações nos requisitos sejam compreendidas e implementadas mais cedo  
D) Permitir que a equipe se concentre nos recursos que agregam mais valor e têm maior impacto sobre os riscos identificados  

---

### 12. Em uma revisão, define-se o objetivo, o produto de trabalho a ser revisado, as características de qualidade a avaliar, as áreas de foco, os critérios de saída, o esforço e os prazos. Qual atividade do processo de revisão é essa?
A) Início da revisão  
B) Revisão individual  
C) Comunicação e análise de problemas  
D) Planejamento  

---

### 13. Qual associação entre atividade do processo de revisão e sua descrição está correta?
A) Planejamento: cada revisor aplica listas de verificação para identificar anomalias  
B) Início da revisão: definir o escopo, os critérios de saída, o esforço e os prazos  
C) Revisão individual: cada revisor avalia a qualidade do produto e identifica anomalias, recomendações e perguntas, aplicando técnicas como revisão baseada em lista de verificação ou em cenário  
D) Correção e relatório: decidir o status, a propriedade e as ações de cada anomalia  

---

### 14. Um revisor registrou 15 anomalias durante a revisão individual. Qual afirmação sobre o tratamento dessas anomalias está correta?
A) Todas as anomalias são defeitos e geram relatório de defeitos imediatamente  
B) Nem toda anomalia é defeito; cada uma deve ser analisada e discutida, decidindo-se status, propriedade e ações, normalmente em uma reunião de revisão em que também se avalia o nível de qualidade do produto e as ações de acompanhamento  
C) Apenas o autor decide o status de cada anomalia, após a reunião  
D) Anomalias não precisam ser analisadas quando os critérios de saída são mensuráveis  

---

### 15. Sobre o processo de revisão definido pela norma ISO/IEC 20246, é correto afirmar:
A) É um framework genérico, estruturado porém flexível, que pode ser adaptado; revisões mais formais exigem mais tarefas, e produtos grandes demais podem exigir que o processo seja invocado várias vezes  
B) É um processo rígido, que deve ser seguido integralmente em qualquer revisão  
C) Aplica-se somente às inspeções  
D) Todo produto de trabalho deve ser coberto por uma única revisão, independentemente do tamanho  

---

### 16. Qual função da revisão garante o andamento eficaz das reuniões, incluindo mediação, gerenciamento do tempo e um ambiente seguro no qual todos possam falar livremente?
A) Gerente  
B) Relator  
C) Líder da revisão  
D) Moderador (facilitador)  

---

### 17. Qual associação entre função e responsabilidade nas revisões está correta?
A) Relator: cria e corrige o produto de trabalho em análise  
B) Autor: reúne as anomalias dos revisores e registra as informações da reunião  
C) Líder da revisão: assume a responsabilidade geral, decide quem estará envolvido e organiza quando e onde a revisão será realizada  
D) Gerente: garante o andamento eficaz das reuniões e um ambiente seguro para todos falarem  

---

### 18. O autor conduz os revisores, passo a passo, pelo produto de trabalho, com o objetivo de instruí-los e obter consenso. Os revisores podem ter feito uma revisão individual antes, mas isso não é obrigatório. Qual é o tipo de revisão?
A) Revisão informal  
B) Walkthrough  
C) Revisão técnica  
D) Inspeção  

---

### 19. Dois arquitetos discordam sobre a solução de integração a adotar. A equipe convoca revisores tecnicamente qualificados, com um moderador à frente, para obter consenso e tomar uma decisão técnica. Qual é o tipo de revisão?
A) Revisão técnica  
B) Walkthrough  
C) Inspeção  
D) Revisão informal  

---

### 20. Qual afirmação sobre a inspeção está correta?
A) O autor pode atuar como líder da revisão para agilizar o processo  
B) Não segue processo definido e não exige resultado documentado  
C) Seu objetivo principal é obter consenso sobre uma decisão técnica  
D) Segue o processo genérico completo, busca encontrar o número máximo de anomalias, coleta métricas para aprimorar o SDLC e o próprio processo de inspeção, e o autor não pode ser líder nem relator  

---

### 21. Qual das alternativas NÃO é um fator que determina o nível de formalidade necessário em uma revisão?
A) O SDLC que está sendo seguido  
B) A maturidade do processo de desenvolvimento  
C) O tempo de empresa do autor do produto de trabalho  
D) Os requisitos legais ou regulamentares e a necessidade de uma trilha de auditoria  

---

### 22. Um desenvolvedor pede a um colega que dê uma olhada rápida em seu código antes do commit. Não há processo definido nem registro formal do resultado. Qual é o tipo de revisão e o seu principal objetivo?
A) Inspeção, para encontrar o número máximo de anomalias  
B) Revisão informal, cujo principal objetivo é detectar anomalias  
C) Walkthrough, para instruir o revisor  
D) Revisão técnica, para obter consenso técnico  

---

### 23. Qual associação entre tipo de revisão e característica está correta?
A) Walkthrough: exige revisão individual prévia obrigatória  
B) Revisão técnica: conduzida pelo autor, sem moderador  
C) Inspeção: tipo menos formal, sem processo definido  
D) Walkthrough: conduzido pelo autor, pode instruir os revisores e obter consenso, e a revisão individual prévia é opcional  

---

### 24. Qual das alternativas NÃO é um fator de sucesso para revisões?
A) Usar o tipo de revisão mais formal (inspeção) em todos os produtos de trabalho, independentemente dos objetivos e do contexto  
B) Definir objetivos claros e critérios de saída mensuráveis  
C) Fornecer feedback das revisões aos stakeholders e aos autores  
D) Tornar as revisões parte da cultura da organização  

---

### 25. Uma equipe revisa um documento de 120 páginas em uma única reunião de 8 horas. Os revisores perdem a concentração e a quantidade de achados cai ao longo do dia. Qual fator de sucesso foi ignorado?
A) Fornecer feedback das revisões aos stakeholders e aos autores  
B) Escolher sempre o tipo de revisão mais formal  
C) Realizar revisões em pequenas partes  
D) Obter apoio da gerência para o processo de revisão  

---

### 26. Um gerente propõe usar o número de defeitos encontrados por cada revisor para avaliar o desempenho individual da equipe. Qual é a avaliação correta, segundo o syllabus?
A) É compatível com as boas práticas, pois motiva os revisores  
B) Contraria um fator de sucesso: a avaliação dos participantes nunca deve ser um objetivo da revisão  
C) É aceitável em revisões informais, mas não nas formais  
D) É aceitável apenas em inspeções, por coletarem métricas  

---

### 27. Uma equipe recém-formada não sabe como desempenhar suas funções na revisão, e as reuniões se arrastam sem controle. Quais fatores de sucesso estão em falta?
A) Realizar revisões em pequenas partes e escolher o tipo adequado  
B) Apoio da gerência e feedback aos stakeholders  
C) Critérios de saída mensuráveis e tempo de preparação  
D) Treinamento adequado a todos os participantes e facilitação das reuniões  

---

### 28. Qual afirmação sobre a análise estática está correta?
A) Pode identificar problemas antes dos testes dinâmicos, muitas vezes com menos esforço (não exige casos de teste e costuma usar ferramentas), é frequentemente incorporada à integração contínua e também avalia capacidade de manutenção e segurança  
B) Exige casos de teste e a execução do código para detectar defeitos  
C) Detecta apenas defeitos de código, sem relação com manutenção ou segurança  
D) Aplica-se somente a código de terceiros  

---

### 29. Ao revisar a rastreabilidade, um testador percebe que um critério de aceite não possui nenhum caso de teste associado. Que tipo de achado é esse e como foi detectado?
A) Defeito de projeto, detectado por teste dinâmico  
B) Falha de desempenho, detectada por análise de carga  
C) Lacuna na cobertura da base de testes, tipicamente detectada por teste estático  
D) Vulnerabilidade de segurança, detectada por análise estática  

---

### 30. Qual afirmação sobre o teste estático e os conceitos de verificação e validação está correta?
A) O teste estático serve apenas para verificação; a validação exige a execução do código  
B) Ao revisar os requisitos documentados, os stakeholders podem se certificar de que eles descrevem suas necessidades reais, o que mostra que o teste estático também apoia a validação  
C) A validação só é possível pelo teste de aceite com usuários, nunca por revisões  
D) O teste estático avalia apenas a sintaxe do código  

---

## GABARITO

| #  | Resp | Explicação |
|----|------|------------|
| 1  | C | (K1 · 3.1.1) Quase todos os produtos podem ser examinados: requisitos, código, planos e casos de teste, itens de backlog, cartas de teste, documentação de projeto, contratos e modelos. Não servem os que humanos não conseguem interpretar e ferramentas não conseguem analisar, como código executável de terceiros por motivos legais. |
| 2  | A | (K1 · 3.1.1) Revisão: qualquer produto que possa ser lido e compreendido. Análise estática: exige estrutura (modelos, código, texto com sintaxe formal). **B** é a pegadinha (texto livre não tem estrutura formal); **D** erra: planos e casos de teste constam da lista. |
| 3  | B | (K2 · 3.1) Testadores, representantes do negócio e desenvolvedores aplicam técnicas de revisão para garantir histórias completas, compreensíveis e com critérios de aceite testáveis, e ao fazer as perguntas certas exploram, desafiam e melhoram as histórias. Não há execução de código, logo não é teste dinâmico. |
| 4  | D | (K2 · 3.1.2) Exemplos citados: código inacessível, padrões de projeto não implementados conforme desejado e defeitos em produtos de trabalho não executáveis. **A**, **B** e **C** são características que dependem da execução, logo são domínio do teste dinâmico. |
| 5  | B | (K2 · 3.1.2) Implementar revisões pode ser dispendioso, mas os custos gerais costumam ser muito menores do que sem revisões, pois se gasta menos para corrigir defeitos depois. Isso se alinha ao princípio do teste antecipado. |
| 6  | C | (K2 · 3.1.2) Os testes estáticos no início do SDLC criam entendimento compartilhado, melhoram a comunicação e permitem que os stakeholders confirmem que os requisitos refletem suas necessidades reais. **B** erra: os dois se complementam. **D** erra: mais participantes tendem a aumentar o custo por revisão. |
| 7  | A | (K2 · 3.1.3) Estáticos encontram defeitos diretamente; dinâmicos causam falhas e os defeitos são determinados depois. **B** inverte. **C** inverte: o estático se aplica também a produtos não executáveis. **D** erra: alguns defeitos só são encontrados por um dos dois. |
| 8  | D | (K2 · 3.1.3) O estático mede características que não dependem da execução (como capacidade de manutenção); o dinâmico mede as que dependem dela (como eficiência de performance). |
| 9  | B | (K2 · 3.1.3) Desempenho sob carga depende da execução. As demais estão na lista: variáveis não declaradas, parâmetros de interface incompatíveis e defeitos em requisitos (inconsistências, ambiguidades, contradições, omissões, imprecisões, duplicações). |
| 10 | C | (K2 · 3.1.3) As duas práticas se complementam. **B** é a pegadinha invertida: o estático detecta com mais facilidade defeitos em caminhos raramente executados ou difíceis de alcançar. **D** erra: o estático aplica-se justamente a produtos não executáveis. |
| 11 | A | (K1 · 3.2.1) Os benefícios incluem comunicação precoce de problemas, menos mal-entendidos, mudanças compreendidas mais cedo e foco no que agrega valor. O feedback não elimina o teste dinâmico de aceite. |
| 12 | D | (K2 · 3.2.2) O planejamento define o escopo: objetivo, produto, características de qualidade, áreas de foco, critérios de saída, informações de apoio (como padrões), esforço e prazos. |
| 13 | C | (K2 · 3.2.2) Na revisão individual, cada revisor avalia o produto e registra anomalias, recomendações e perguntas, aplicando técnicas como lista de verificação ou cenário. **A** e **B** trocam atividades; **D** descreve a comunicação e análise de problemas. |
| 14 | B | (K2 · 3.2.2) As anomalias identificadas não são necessariamente defeitos. Cada uma é analisada, com decisão sobre status, propriedade e ações, normalmente na reunião de revisão. Só para os defeitos confirmados se cria o relatório de defeitos, na etapa de correção e relatório. |
| 15 | A | (K2 · 3.2.2) A ISO/IEC 20246 é um framework estruturado e flexível. Revisões mais formais exigem mais tarefas, e produtos grandes demais podem exigir várias invocações do processo. |
| 16 | D | (K1 · 3.2.3) O moderador (facilitador) conduz as reuniões. **C** é a pegadinha: o líder da revisão tem a responsabilidade geral, decide quem participa e organiza quando e onde. |
| 17 | C | (K1 · 3.2.3) **A** descreve o autor; **B** descreve o relator; **D** mistura gerente com moderador (o gerente decide o que revisar e fornece recursos). |
| 18 | B | (K2 · 3.2.4) O walkthrough é conduzido pelo autor e atende a muitos objetivos (avaliar qualidade, instruir revisores, obter consenso, gerar ideias). A revisão individual prévia é opcional. |
| 19 | A | (K2 · 3.2.4) A revisão técnica é feita por revisores tecnicamente qualificados, liderada por um moderador, com o objetivo de obter consenso e tomar decisões sobre problemas técnicos. |
| 20 | D | (K2 · 3.2.4) A inspeção é o tipo mais formal, segue o processo genérico completo, busca o máximo de anomalias, coleta métricas, e o autor não pode ser líder nem relator. **B** descreve a revisão informal; **C** descreve a revisão técnica. |
| 21 | C | (K2 · 3.2.4) Os fatores são: SDLC seguido, maturidade do processo, importância e complexidade do produto, requisitos legais ou regulamentares e necessidade de trilha de auditoria. O tempo de empresa do autor não consta. |
| 22 | B | (K2 · 3.2.4) A revisão informal não segue processo definido e não exige resultado formal documentado; seu principal objetivo é detectar anomalias. |
| 23 | D | (K2 · 3.2.4) **A** erra: a revisão individual prévia não é obrigatória no walkthrough. **B** erra: a revisão técnica é liderada por moderador. **C** erra: a inspeção é a mais formal. |
| 24 | A | (K1 · 3.2.5) O tipo de revisão deve ser apropriado aos objetivos, ao tipo de produto, aos participantes e ao contexto. Usar sempre o mais formal contraria esse fator. As demais alternativas são fatores listados. |
| 25 | C | (K1 · 3.2.5) Revisões em pequenas partes evitam que os revisores percam a concentração na revisão individual e/ou na reunião. |
| 26 | B | (K1 · 3.2.5) Ao definir objetivos claros e critérios de saída mensuráveis, a avaliação dos participantes nunca deve ser um objetivo. **D** é a pegadinha: coletar métricas na inspeção serve para melhorar o processo, não para avaliar pessoas. |
| 27 | D | (K1 · 3.2.5) Os fatores em falta são treinamento adequado a todos os participantes (para saberem desempenhar suas funções) e facilitação de reuniões. |
| 28 | A | (K2 · 3.1) A análise estática costuma exigir menos esforço (sem casos de teste, geralmente com ferramentas), muitas vezes está na CI e avalia também capacidade de manutenção e segurança. Verificadores ortográficos e ferramentas de legibilidade também são exemplos. |
| 29 | C | (K2 · 3.1.3) "Lacunas ou imprecisões na cobertura da base de testes (p. ex., testes ausentes para um critério de aceite)" constam entre os defeitos típicos mais fáceis ou baratos de encontrar por testes estáticos. |
| 30 | B | (K2 · 3.1) O teste estático pode ser aplicado tanto para verificação quanto para validação. Ao verificar requisitos documentados, os stakeholders confirmam que eles descrevem suas necessidades reais. |
