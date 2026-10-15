# SIMULADO CTFL 4.0 – Capítulo 1: Fundamentos de Teste (30 questões, nível difícil)

---

## Instruções

- 1 alternativa correta
- Nível: K1 e K2, com cenários e pegadinhas
- Gabarito no final, com o motivo de a correta estar certa e de as outras pegarem

---

## QUESTÕES

### 1. Em um refinamento, antes de qualquer código existir, uma testadora analisa as histórias de usuário e aponta critérios de aceite ambíguos e contraditórios. Qual objetivo típico de teste está sendo atendido?
A) Provocar falhas no software em execução  
B) Avaliar produtos de trabalho  
C) Garantir a cobertura necessária do código  
D) Validar o sistema em seu ambiente operacional  

---

### 2. Qual das alternativas NÃO é um objetivo típico de teste?
A) Fornecer informações aos stakeholders para decisões informadas  
B) Verificar a conformidade com requisitos contratuais, legais e normativos  
C) Demonstrar que o objeto de teste está livre de defeitos  
D) Criar confiança na qualidade do objeto de teste  

---

### 3. Todos os requisitos especificados foram verificados e todos os casos de teste passaram. Após o lançamento, os usuários dizem que o aplicativo não atende ao que precisam. O que foi insuficiente?
A) A verificação, pois os requisitos especificados não foram atendidos  
B) A validação, pois não se checou se o sistema atende às necessidades dos usuários e stakeholders em seu ambiente operacional  
C) A depuração, pois os defeitos não foram corrigidos  
D) O teste de confirmação, pois não se repetiram os testes que falharam  

---

### 4. Um teste dinâmico acionou uma falha. O processo típico de depuração consiste em:
A) Diagnosticar, reproduzir e corrigir  
B) Corrigir, reproduzir e executar o teste de confirmação  
C) Diagnosticar, corrigir e executar o teste de regressão  
D) Reproduzir a falha, diagnosticar a causa e corrigir a causa  

---

### 5. Durante uma revisão de código (teste estático), um defeito é identificado diretamente no código. Sobre a depuração nesse caso, é correto afirmar:
A) Ela se limita a remover o defeito, pois não há necessidade de reprodução nem de diagnóstico  
B) Ela exige reproduzir a falha antes de qualquer correção  
C) Ela não existe, pois o teste estático só encontra falhas, não defeitos  
D) Ela deve ser precedida por um teste de regressão para localizar o defeito  

---

### 6. Após a correção de um defeito, qual afirmação sobre teste de confirmação e teste de regressão está correta?
A) A confirmação verifica se a correção causou falhas em outras partes; a regressão verifica se a correção resolveu o problema  
B) Ambos devem ser feitos, preferencialmente, por uma pessoa diferente da que executou o teste inicial  
C) A confirmação verifica se a correção resolveu o problema, de preferência feita por quem executou o teste inicial; a regressão verifica efeitos colaterais em outras partes  
D) A depuração inclui o teste de confirmação como sua última etapa  

---

### 7. Um projeto não consegue envolver usuários representativos por causa do custo e da indisponibilidade. Como o teste contribui para o sucesso do projeto nessa situação?
A) Os testadores garantem que o entendimento das necessidades dos usuários seja considerado ao longo do SDLC, representando-os indiretamente  
B) Os testes substituem a participação dos usuários, dispensando o teste de aceite  
C) Os testes removem diretamente os defeitos que afetariam os usuários  
D) Apenas a equipe de testes pode contribuir para a qualidade nesse cenário  

---

### 8. Qual alternativa relaciona corretamente teste, QA e QC?
A) QA é corretivo e orientado ao produto; QC é preventivo e orientado ao processo  
B) Teste e QA são equivalentes, e os termos são intercambiáveis  
C) QA é responsabilidade exclusiva da equipe de testes; QC é de todos no projeto  
D) O teste é uma forma de QC (corretivo e orientado ao produto); QA é preventivo, orientado ao processo e responsabilidade de todos  

---

### 9. Os resultados dos testes mostraram que muitos defeitos nascem de requisitos mal escritos. A equipe decide criar um padrão de escrita de requisitos e treinar os analistas. Essa iniciativa é principalmente:
A) QC, pois corrige defeitos já existentes  
B) QA, pois é preventiva e orientada a processo, usando o feedback dos testes para melhorar o processo  
C) Depuração, pois busca a causa dos defeitos  
D) Teste de regressão, pois evita que os defeitos voltem  

---

### 10. Sob pressão de prazo, um desenvolvedor entendeu errado a regra de frete grátis e codificou uma condição invertida. Ao fechar um pedido acima do valor mínimo, o cliente é cobrado pelo frete. Qual associação está correta?
A) Erro: condição invertida no código; Defeito: entendimento errado; Falha: cobrança indevida  
B) Erro: cobrança indevida; Defeito: condição invertida; Falha: entendimento errado  
C) Erro: entendimento equivocado do desenvolvedor; Defeito: condição invertida no código; Falha: cobrança indevida no checkout  
D) Erro: pressão de prazo; Defeito: entendimento errado; Falha: condição invertida  

---

### 11. O firmware de um equipamento apresentou comportamento incorreto devido a um campo eletromagnético intenso, sem qualquer erro humano no desenvolvimento. Segundo o syllabus:
A) Falhas também podem ser causadas por condições ambientais, e não apenas por erros e defeitos  
B) Não é uma falha, pois falhas só ocorrem quando há defeito no código  
C) É um defeito do script de teste, pois o ambiente deveria estar controlado  
D) É um erro humano indireto, pois alguém deveria ter previsto o ambiente  

---

### 12. Qual afirmação sobre defeitos é VERDADEIRA?
A) Todo defeito presente no código resulta em falha quando executado  
B) Defeitos só podem existir no código-fonte  
C) Defeitos em artefatos produzidos no início do SDLC, se não detectados, raramente afetam artefatos posteriores  
D) Alguns defeitos só resultam em falha em circunstâncias específicas, e outros podem nunca resultar em falha  

---

### 13. Após uma falha em produção, a equipe realiza uma análise de causa-raiz. O propósito dessa análise é:
A) Identificar quem cometeu o erro, para responsabilizá-lo  
B) Identificar o motivo fundamental do problema, para tentar evitar ou reduzir a frequência de falhas e defeitos semelhantes  
C) Reproduzir a falha em ambiente controlado  
D) Confirmar que a correção aplicada resolveu o problema  

---

### 14. Uma suíte com 2.000 casos de teste foi executada e nenhum defeito foi encontrado. O gerente declara: "o sistema está livre de defeitos". Qual princípio de teste contradiz essa conclusão?
A) O teste mostra a presença, não a ausência, de defeitos  
B) Testes exaustivos são impossíveis  
C) Os testes se degradam  
D) Falácia da ausência de defeitos  

---

### 15. Uma tela possui dezenas de campos com muitas combinações possíveis de entrada. O líder propõe testar todas as combinações. O que o syllabus recomenda em vez disso?
A) Aumentar a equipe até cobrir todas as combinações  
B) Testar apenas o caminho feliz  
C) Aplicar técnicas de teste, priorização de casos de teste e testes baseados em riscos  
D) Automatizar tudo, pois a automação torna viável o teste exaustivo  

---

### 16. Um defeito em um requisito é encontrado em uma revisão, antes do design, em vez de ser descoberto em produção. Qual é a justificativa do princípio "testes antecipados economizam tempo e dinheiro"?
A) As revisões substituem os testes dinâmicos, que passam a ser desnecessários  
B) Defeitos encontrados cedo são sempre mais fáceis de reproduzir  
C) Testar cedo significa executar um protótipo do código o quanto antes  
D) Defeitos removidos cedo não geram defeitos subsequentes nos produtos de trabalho derivados, reduzindo o custo da qualidade  

---

### 17. O módulo de pagamentos concentra cerca de 60% dos defeitos encontrados nas últimas versões. Qual é a melhor decisão alinhada ao syllabus?
A) Distribuir o esforço de teste uniformemente entre todos os módulos  
B) Usar os agrupamentos de defeitos previstos e observados como entrada para o teste baseado em riscos, concentrando o esforço  
C) Interromper os testes nos demais módulos até estabilizar pagamentos  
D) Descartar o dado, pois os testes se degradam  

---

### 18. Uma suíte manual de 40 casos é executada sem alteração há dois anos e já não encontra novos defeitos. Paralelamente, uma suíte de regressão automatizada roda a cada commit. Qual afirmação está correta?
A) A repetição dos mesmos testes tende a ser ineficaz para novos defeitos, exigindo modificar testes e dados ou escrever novos; porém, em regressão automatizada, a repetição pode ser benéfica  
B) As duas suítes devem ser aposentadas, pois ambas se degradaram  
C) A repetição é sempre benéfica, pois confirma a estabilidade do sistema  
D) O princípio vale apenas para testes manuais; testes automatizados nunca se degradam  

---

### 19. Todos os requisitos foram testados e todos os defeitos encontrados foram corrigidos, mas os clientes migraram para um concorrente porque o sistema não atendia às suas expectativas. Qual princípio explica o ocorrido?
A) Os testes dependem do contexto  
B) Testes exaustivos são impossíveis  
C) Falácia da ausência de defeitos  
D) Os defeitos se agrupam  

---

### 20. Qual das alternativas NÃO é um dos sete princípios de teste do syllabus?
A) Testes antecipados economizam tempo e dinheiro  
B) Os testes dependem do contexto  
C) Os testes se degradam  
D) A automação dos testes elimina a necessidade de testes manuais  

---

### 21. Uma testadora analisa a base de teste, identifica as funcionalidades testáveis, define e prioriza as condições de teste e avalia a testabilidade. Qual atividade de teste ela executa?
A) Planejamento de teste  
B) Análise de teste  
C) Modelagem de teste  
D) Implementação de teste  

---

### 22. Qual conjunto contém apenas produtos de trabalho da IMPLEMENTAÇÃO de teste?
A) Cartas de teste e itens de cobertura  
B) Condições de teste priorizadas e relatórios de defeitos na base de teste  
C) Procedimentos de teste, scripts automatizados, conjuntos de teste, dados de teste e elementos do ambiente (stubs e drivers)  
D) Registros de testes e relatórios de defeitos da execução  

---

### 23. Ao fim da iteração, a equipe encerra o ambiente de teste em um estado acordado, arquiva o testware útil, registra as lições aprendidas e emite um relatório aos stakeholders. Qual atividade é essa?
A) Conclusão do teste  
B) Monitoramento e controle de teste  
C) Execução do teste  
D) Implementação do teste  

---

### 24. Qual das alternativas NÃO é um fator contextual que influencia o processo de teste?
A) Restrições do projeto (escopo, tempo, orçamento)  
B) Domínio do negócio (criticidade, normas legais)  
C) Fatores organizacionais (estrutura, políticas, práticas)  
D) A preferência individual do testador por determinada técnica  

---

### 25. Qual alternativa associa corretamente a rastreabilidade ao seu uso?
A) Casos de teste aos requisitos: avaliar o risco residual; resultados dos testes aos riscos: verificar se os requisitos estão cobertos  
B) Casos de teste aos requisitos: verificar se os requisitos estão cobertos; resultados dos testes aos riscos: avaliar o nível de risco residual  
C) Casos de teste aos requisitos: medir o número de defeitos; resultados dos testes aos riscos: definir os critérios de saída  
D) A rastreabilidade serve apenas para auditorias e não tem relação com cobertura  

---

### 26. Sobre os papéis no teste, é correto afirmar:
A) O gerenciamento de teste foca em planejamento, monitoramento e controle e conclusão; o testador foca em análise, modelagem, implementação e execução; uma pessoa pode assumir ambos os papéis  
B) O testador foca em planejamento e conclusão; o gerenciamento de teste foca em modelagem e execução  
C) Os dois papéis são exclusivos e uma mesma pessoa não pode acumulá-los  
D) O papel de gerenciamento de teste só existe fora da equipe de desenvolvimento, inclusive em contextos ágeis  

---

### 27. Um testador relata um defeito crítico e o autor do código reage de forma defensiva, dizendo que está sendo criticado. Qual prática está alinhada ao syllabus?
A) Omitir os detalhes técnicos para evitar conflito  
B) Registrar apenas os defeitos cuja autoria esteja identificada  
C) Comunicar as informações sobre defeitos e falhas de forma construtiva, ciente de que os resultados podem ser percebidos como crítica e de que o viés de confirmação dificulta aceitar informações que discordem das crenças atuais  
D) Escalar ao gerente antes de conversar com o autor  

---

### 28. Sobre a abordagem de equipe completa, é correto afirmar:
A) É uma prática do Scrum em que somente os testadores respondem pela qualidade  
B) É sempre adequada e dispensa a independência dos testes  
C) A colocalização dos membros da equipe é irrelevante para sua eficácia  
D) É uma prática proveniente da Extreme Programming, em que qualquer membro com as habilidades necessárias pode executar qualquer tarefa e todos são responsáveis pela qualidade; pode não ser adequada em contextos críticos para a segurança  

---

### 29. Qual alternativa associa corretamente o nível de independência dos testes?
A) Testadores de fora da equipe do autor, mas dentro da organização: alta independência  
B) Colegas do autor na mesma equipe: nenhuma independência  
C) Testadores de fora da organização: alta independência  
D) O próprio autor: alguma independência  

---

### 30. Qual das alternativas NÃO é uma desvantagem da independência dos testes?
A) Isolamento da equipe de desenvolvimento, com problemas de comunicação  
B) Desenvolvedores perderem o senso de responsabilidade pela qualidade  
C) Reconhecer tipos diferentes de falhas e defeitos por ter formação e perspectivas distintas  
D) Testadores serem vistos como gargalo ou responsabilizados por atrasos  

---

## GABARITO

| #  | Resp | Explicação |
|----|------|------------|
| 1  | B | (K2 · 1.1.1) Avaliar produtos de trabalho (requisitos, histórias, projetos, código) é objetivo típico. **A** é pegadinha: sem código em execução não há falha, o defeito está no artefato. **C** e **D** não descrevem a situação. |
| 2  | C | (K1 · 1.1.1) O teste não demonstra ausência de defeitos, só reduz a chance de eles passarem despercebidos. As demais constam da lista de objetivos. |
| 3  | B | (K2 · 1.1 e princípio 7) Verificar é checar se o sistema atende aos requisitos especificados; validar é checar se atende às necessidades dos usuários e stakeholders no ambiente operacional. **A** inverte: a verificação foi feita. |
| 4  | D | (K2 · 1.1.2) A sequência é reproduzir, diagnosticar e corrigir. O teste de confirmação vem depois e **não** faz parte da depuração. |
| 5  | A | (K2 · 1.1.2) O teste estático encontra o defeito diretamente e não causa falhas, então não há o que reproduzir nem diagnosticar. **C** erra: o teste estático encontra defeitos. |
| 6  | C | (K2 · 1.1.2) Confirmação verifica se a correção resolveu, de preferência pela mesma pessoa do teste inicial. Regressão verifica efeitos colaterais. **A** inverte os conceitos; **B** contraria a preferência do syllabus. |
| 7  | A | (K2 · 1.2.1) Os testes dão aos usuários uma representação indireta no projeto. **B** exagera ao dizer que "substituem" e dispensam o aceite. **C** erra: quem remove defeitos é a depuração, que não é atividade de teste. |
| 8  | D | (K1 · 1.2.2) O teste é uma forma de QC (corretivo, orientado ao produto). A QA é preventiva, orientada ao processo e de responsabilidade de todos. **A** inverte QA e QC; **B** é o equívoco clássico; **C** erra a responsabilidade. |
| 9  | B | (K2 · 1.2.2) Melhorar o processo para prevenir defeitos é QA, e os resultados dos testes servem de feedback sobre o desempenho dos processos. **A** e **C** tratam de corrigir defeitos existentes (QC e depuração). |
| 10 | C | (K2 · 1.2.3) O ser humano comete o erro (equívoco), que produz o defeito (no código), que pode causar a falha (comportamento observado na execução). Pressão de prazo é um motivo para o erro, não o erro em si. |
| 11 | A | (K2 · 1.2.3) Condições ambientais, como radiação ou campo eletromagnético, também causam falhas. Por isso nem toda falha vem de erro humano ou defeito no código. |
| 12 | D | (K2 · 1.2.3) Alguns defeitos sempre causam falha, outros só em circunstâncias específicas, e outros nunca. **A** erra por generalizar; **B** erra porque defeitos existem também em documentação, scripts e arquivos de compilação; **C** erra porque defeitos iniciais geralmente propagam para artefatos posteriores. |
| 13 | B | (K2 · 1.2.3) Causa-raiz é o motivo fundamental do problema. Tratá-la pode evitar ou reduzir falhas e defeitos semelhantes. O objetivo não é culpar pessoas. |
| 14 | A | (K2 · 1.3) Princípio 1: o teste mostra a presença, não a ausência de defeitos. **B** é pegadinha (verdadeiro, mas não contradiz diretamente a afirmação). **D** trata de o sistema não atender às necessidades, mesmo sem defeitos. |
| 15 | C | (K2 · 1.3) Princípio 2: em vez de testar exaustivamente, use técnicas, priorização e teste baseado em riscos. **D** erra: automatizar não torna o teste exaustivo viável. |
| 16 | D | (K2 · 1.3) Princípio 3: defeitos removidos cedo não geram defeitos nos produtos derivados e reduzem o custo da qualidade. **A** erra: estático e dinâmico se complementam. |
| 17 | B | (K2 · 1.3) Princípio 4 (Pareto): agrupamentos previstos e reais são entrada importante para o teste baseado em riscos. **C** é extremo. **D** mistura princípios. |
| 18 | A | (K2 · 1.3) Princípio 5: repetir os mesmos testes os torna ineficazes para novos defeitos, mas a repetição pode ser benéfica em regressão automatizada. **C** e **D** são absolutos. |
| 19 | C | (K2 · 1.3) Princípio 7: testar todos os requisitos e corrigir todos os defeitos ainda pode gerar um sistema que não atende às necessidades dos usuários. É preciso validação, além da verificação. |
| 20 | D | (K1 · 1.3) A automação não está entre os sete princípios. Os princípios são os das alternativas A, B e C, mais: o teste mostra a presença de defeitos, testes exaustivos são impossíveis, defeitos se agrupam e falácia da ausência de defeitos. |
| 21 | B | (K2 · 1.4.1) A análise de teste responde "o que testar?" (condições de teste, riscos, testabilidade). A modelagem responde "como testar?" (casos de teste, itens de cobertura, dados, ambiente). |
| 22 | C | (K2 · 1.4.3) Implementação: procedimentos, scripts automatizados, conjuntos, dados e elementos do ambiente. **A** é modelagem; **B** é análise; **D** é execução. |
| 23 | A | (K2 · 1.4.1) Conclusão de teste: ocorre em marcos do projeto, arquiva o testware, encerra o ambiente, registra lições aprendidas e emite o relatório de conclusão. |
| 24 | D | (K2 · 1.4.2) Os fatores listados são: stakeholders, membros da equipe, domínio do negócio, fatores técnicos, restrições do projeto, fatores organizacionais, SDLC e ferramentas. Preferência pessoal por técnica não consta. |
| 25 | B | (K2 · 1.4.4) Casos para requisitos verificam a cobertura dos requisitos. Resultados para riscos avaliam o risco residual. **A** inverte os usos. A rastreabilidade também permite avaliar o impacto de mudanças e apoia auditorias. |
| 26 | A | (K2 · 1.4.5) Gerenciamento: planejamento, monitoramento e controle, conclusão. Testador: análise, modelagem, implementação, execução. Uma pessoa pode acumular os papéis, e em ágil parte do gerenciamento pode ser feita pela própria equipe. |
| 27 | C | (K2 · 1.5.1) Comunique os defeitos de forma construtiva. O syllabus destaca que os resultados podem soar como crítica ao produto e ao autor, e que o viés de confirmação atrapalha a aceitação. |
| 28 | D | (K1 · 1.5.2) A prática vem da XP (**A** erra ao citar Scrum). A colocalização facilita a comunicação (**C** erra). Em contextos críticos para a segurança, pode ser necessário alto nível de independência (**B** erra). |
| 29 | A | (K2 · 1.5.3) Autor: sem independência; colegas da mesma equipe: alguma; fora da equipe, dentro da organização: alta; fora da organização: muito alta. Cada alternativa errada troca um desses níveis. |
| 30 | C | (K2 · 1.5.3) Reconhecer tipos diferentes de falhas e defeitos é um **benefício** da independência. As demais são desvantagens listadas no syllabus. |
