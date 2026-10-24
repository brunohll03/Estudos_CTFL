# SIMULADO CTFL 4.0 – Capítulo 4: Análise e Modelagem de Teste (30 questões, nível difícil)

---

## Instruções

- 1 alternativa correta
- Nível: K2 e K3 (várias questões exigem cálculo ou aplicação da técnica)
- Convenção usada nas questões de análise de valor limite: os valores de limite considerados são o mínimo e o máximo da partição **válida**
- As questões 14 a 17 compartilham o mesmo cenário
- Gabarito no final, com o motivo de a correta estar certa e de as outras pegarem

---

## QUESTÕES

### 1. Qual afirmação distingue corretamente as técnicas de teste caixa-preta, caixa-branca e baseadas na experiência?
A) Caixa-preta: baseada na estrutura interna do objeto de teste; os casos só podem ser criados depois da implementação  
B) Caixa-preta: os casos independem de como o software é implementado e continuam úteis se só a implementação mudar; caixa-branca: os casos dependem do projeto ou da implementação; baseadas na experiência: a eficácia depende muito das habilidades do testador, e complementam as demais  
C) Baseadas na experiência: a eficácia independe das habilidades do testador, e por isso substituem as técnicas caixa-preta e caixa-branca  
D) Caixa-branca: baseada em especificações; os casos continuam úteis mesmo que a implementação mude  

---

### 2. Um sistema calcula a tarifa conforme a idade (número inteiro): 0 a 12 anos (criança), 13 a 17 (adolescente), 18 a 64 (adulto) e 65 ou mais (idoso). Idades negativas são rejeitadas. Considerando apenas essas partições, qual é o número mínimo de casos de teste para atingir 100% de cobertura de partições de equivalência?
A) 4  
B) 6  
C) 5  
D) 8  

---

### 3. No mesmo sistema da questão anterior (partições: negativa; 0–12; 13–17; 18–64; 65 ou mais), a equipe executou testes com as idades 7, 15 e 40. Qual é a cobertura de partições de equivalência?
A) 60%  
B) 75%  
C) 40%  
D) 30%  

---

### 4. Uma função recebe três parâmetros: tipo de cliente (Regular, Premium, VIP), forma de pagamento (Cartão, Boleto, Pix, Voucher) e valor do pedido (≤ 0, de 1 a 500, acima de 500). Qual é o número mínimo de casos de teste para atingir 100% de cobertura de cada escolha (Each Choice Coverage)?
A) 3  
B) 10  
C) 36  
D) 4  

---

### 5. Qual afirmação sobre o particionamento de equivalência está correta?
A) As partições podem se sobrepor, desde que cada valor seja testado uma única vez  
B) As partições não devem se sobrepor e devem ser conjuntos não vazios; podem ser identificadas para entradas, saídas, valores internos e valores relacionados ao tempo, entre outros  
C) Só podem ser identificadas para dados de entrada, e a técnica exige vários valores por partição  
D) A definição de valores válidos e inválidos é única e igual para todas as equipes  

---

### 6. Um campo aceita quantidades inteiras de 1 a 99, e valores fora desse intervalo são rejeitados. Considerando como limites apenas o mínimo e o máximo da partição válida, quantos valores distintos são necessários para atingir 100% de cobertura pela análise de valor limite de 3 valores?
A) 4  
B) 5  
C) 6  
D) 8  

---

### 7. Um campo de desconto aceita inteiros de 10 a 20. Qual é o conjunto mínimo de valores para atingir 100% de cobertura pela análise de valor limite de 2 valores?
A) 9, 10, 20 e 21  
B) 10, 11, 19 e 20  
C) 9, 10, 11, 19, 20 e 21  
D) 10, 15 e 20  

---

### 8. Um sensor aceita temperaturas de 0,0 a 100,0, com uma casa decimal (passo de 0,1). Qual é o conjunto mínimo de valores para 100% de cobertura pela análise de valor limite de 2 valores?
A) −1, 0, 100 e 101  
B) 0,0; 0,1; 99,9 e 100,0  
C) −0,1; 0,0; 0,1; 99,9; 100,0 e 100,1  
D) −0,1; 0,0; 100,0 e 100,1  

---

### 9. O requisito diz "se (x ≤ 10), execute a ação", mas o código foi implementado como "se (x = 10)". Qual afirmação sobre a capacidade de detecção da análise de valor limite está correta?
A) O BVA de 2 valores é mais rigoroso e detecta tudo o que o de 3 valores detecta  
B) Os dados do BVA de 2 valores (x = 10 e x = 11) não detectam o defeito, mas o x = 9, incluído no BVA de 3 valores, provavelmente detecta  
C) O BVA pode ser aplicado a partições não ordenadas, como categorias de cliente  
D) O BVA de 3 valores gera menos itens de cobertura do que o de 2 valores  

---

### 10. Considere a tabela de decisão minimizada abaixo, que define o desconto de uma compra.

| Condição / Ação | R1 | R2 | R3 | R4 | R5 |
|---|---|---|---|---|---|
| C1: Pedido ≥ R$ 100? | V | V | V | F | F |
| C2: Cliente Premium? | V | F | F | – | – |
| C3: Cupom válido? | – | V | F | V | F |
| Desconto de 15% | X | | | | |
| Desconto de 10% | | X | | | |
| Desconto de 5% | | | | X | |
| Sem desconto | | | X | | X |

A equipe executou três testes, com as combinações (C1, C2, C3) = (V, V, F), (V, F, V) e (F, V, F). Qual é a cobertura do teste de tabela de decisão?
A) 37,5%  
B) 40%  
C) 60%  
D) 100%  

---

### 11. Sobre o teste de tabela de decisão, qual afirmação está correta?
A) O símbolo "–" indica que o valor da condição é irrelevante para o resultado, e "N/A" indica que a condição é inviável para a regra; os itens de cobertura são as colunas com combinações viáveis  
B) O símbolo "–" indica condição inviável, e "N/A" indica condição irrelevante; os itens de cobertura são as linhas da tabela  
C) Nas tabelas de entrada limitada, as condições podem assumir intervalos numéricos e partições de equivalência  
D) A técnica não ajuda a encontrar lacunas ou contradições nos requisitos  

---

### 12. Um fluxo de checkout tem três condições booleanas: C1 (usuário logado), C2 (carrinho com itens) e C3 (pagamento aprovado). O pagamento só pode ser aprovado para usuário logado, e não há outras restrições. Para 100% de cobertura da tabela de decisão completa, após excluir as combinações inviáveis, quantos casos de teste são necessários?
A) 8  
B) 4  
C) 2  
D) 6  

---

### 13. Uma regra de negócio tem 5 condições booleanas, sem combinações inviáveis. Quantas colunas tem a tabela de decisão completa e o que o syllabus sugere se não houver tempo para executar todas?
A) 10 colunas; é obrigatório executar todas  
B) 32 colunas; pode-se usar uma tabela de decisão minimizada ou uma abordagem baseada em risco  
C) 32 colunas; a técnica exige executar todas, sem alternativas  
D) 25 colunas, pois o número de regras cresce linearmente com o número de condições  

---

#### Cenário para as questões 14 a 17

Um pedido de e-commerce possui cinco estados: **Novo**, **Pago**, **Enviado**, **Entregue** e **Cancelado**. Os eventos possíveis são: *pagar*, *enviar*, *entregar* e *cancelar*. As transições válidas são:

- Novo → Pago (pagar)
- Novo → Cancelado (cancelar)
- Pago → Enviado (enviar)
- Pago → Cancelado (cancelar)
- Enviado → Entregue (entregar)

Todo pedido começa no estado Novo. Entregue e Cancelado são estados finais (sem transições de saída). Qualquer outra combinação de estado e evento é inválida.

---

### 14. Qual é o número mínimo de casos de teste (sequências de eventos a partir de Novo) para atingir 100% de cobertura de todos os estados?
A) 1  
B) 3  
C) 2  
D) 5  

---

### 15. Qual é o número mínimo de casos de teste para atingir 100% de cobertura de transições válidas (0-switch)?
A) 3  
B) 2  
C) 5  
D) 4  

---

### 16. Foram executados dois casos de teste: TC1 = pagar, enviar, entregar; e TC2 = cancelar (a partir de Novo). Quais são as coberturas de todos os estados e de transições válidas, respectivamente?
A) 100% e 100%  
B) 80% e 80%  
C) 80% e 100%  
D) 100% e 80%  

---

### 17. Quantos itens de cobertura existem para o critério de cobertura de todas as transições, considerando a tabela de estados completa (5 estados × 4 eventos)?
A) 5  
B) 20  
C) 15  
D) 9  

---

### 18. Sobre os critérios de cobertura do teste de transição de estado, qual afirmação está correta?
A) A cobertura de todos os estados é mais forte do que a de transições válidas  
B) A tabela de estados oculta as transições inválidas, ao contrário do diagrama de transição de estados  
C) Alcançar a cobertura de todas as transições garante a cobertura de todos os estados e de transições válidas; ao testar transições inválidas, convém testar apenas uma por caso de teste, para evitar o mascaramento de falhas  
D) A cobertura de transições válidas (0-switch) é o critério mais fraco e raramente utilizado  

---

### 19. Considere o trecho de código abaixo. As instruções executáveis são as linhas 1, 2, 3, 4, 6, 7, 9 e 11, e as ramificações condicionais são os resultados verdadeiro e falso das decisões das linhas 3 e 6 (4 ramificações no total).

```
1  ler(a, b)
2  x = 0
3  se (a > 10) então
4      x = a - 10
5  fim se
6  se (b < 0) então
7      x = x + 1
8  senão
9      x = x + 2
10 fim se
11 imprimir(x)
```

Foram executados dois testes: T1 com a = 20 e b = −1; e T2 com a = 20 e b = 3. Quais são as coberturas de instrução e de ramificação, respectivamente?
A) 100% e 75%  
B) 100% e 100%  
C) 87,5% e 75%  
D) 75% e 100%  

---

### 20. Considere o trecho abaixo:

```
1  ler(n)
2  r = 0
3  se (n > 0) então
4      r = 100 / n
5  fim se
6  imprimir(r)
```

Quantos casos de teste são necessários, no mínimo, para atingir 100% de cobertura de instrução e 100% de cobertura de ramificação, respectivamente?
A) 1 e 1  
B) 2 e 2  
C) 2 e 3  
D) 1 e 2  

---

### 21. Sobre a cobertura de instrução, qual afirmação está correta?
A) A cobertura de 100% de instrução implica 100% de cobertura de ramificação  
B) Com 100% de cobertura de instrução, cada instrução com defeito é executada, o que pode causar uma falha, mas isso não garante detectar todos os defeitos (como os que dependem de dados) nem que toda a lógica de decisão foi testada  
C) Atingir 100% de cobertura de ramificação não garante a cobertura de todas as instruções  
D) A cobertura de 100% de instrução elimina os defeitos que dependem de dados, como a divisão por zero  

---

### 22. A especificação de um sistema está vaga e desatualizada, e um requisito (exportar relatório em PDF) nunca foi implementado. Qual afirmação sobre o valor do teste caixa-branca está correta?
A) Ele não detecta defeitos quando a especificação é vaga, pois depende dela  
B) Ele detecta o requisito não implementado, pois mede toda a implementação  
C) Como considera toda a implementação, facilita detectar defeitos mesmo com especificação vaga, desatualizada ou incompleta; porém, se um requisito não for implementado, pode não detectar o defeito resultante  
D) Ele dispensa o teste caixa-preta, pois mede a cobertura real do código  

---

### 23. Um testador monta uma lista de erros, defeitos e falhas prováveis, a partir dos dados de defeitos de versões anteriores e de falhas de aplicativos semelhantes, e modela testes para expor cada item da lista. Qual abordagem está sendo usada?
A) Ataque a falhas, uma abordagem metódica de suposição de erro  
B) Teste exploratório baseado em sessões  
C) Teste baseado em lista de verificação  
D) Particionamento de equivalência  

---

### 24. Qual afirmação sobre o teste exploratório está correta?
A) Os testes são projetados antes da execução e documentados em detalhe  
B) Dispensa a carta de teste, mesmo na abordagem baseada em sessões  
C) Exige especificações completas e detalhadas para ser eficaz  
D) Os testes são modelados, executados e avaliados simultaneamente enquanto o testador aprende sobre o objeto; na abordagem baseada em sessões há um período definido, uma carta de teste e uma reunião de informação; é útil com especificações inadequadas ou pressão de tempo  

---

### 25. Qual dos itens abaixo é adequado para uma lista de verificação (checklist) de testes?
A) "O sistema é de boa qualidade?"  
B) "O código-fonte compila sem erros?"  
C) "Toda mensagem de erro exibida ao usuário indica qual ação ele deve tomar para corrigir o problema?"  
D) "Os critérios de saída do nível de teste foram atendidos?"  

---

### 26. Qual alternativa associa corretamente os três aspectos críticos de uma história de usuário (3C)?
A) Cartão: os critérios de aceite; Conversação: o meio em que a história é descrita; Confirmação: a explicação de uso  
B) Cartão: o meio em que a história é descrita; Conversação: a explicação de como o software será usado (documentada ou verbal); Confirmação: os critérios de aceite  
C) Cartão: a explicação de uso; Conversação: os critérios de aceite; Confirmação: o meio em que a história é descrita  
D) Cartão: os critérios de aceite; Conversação: o meio em que a história é descrita; Confirmação: a estimativa da equipe  

---

### 27. Considere os critérios de aceite de uma história sobre saque em caixa eletrônico:

- **(I)** "Dado que o saldo é R$ 100, quando o cliente tenta sacar R$ 150, então o sistema recusa a operação e exibe a mensagem de saldo insuficiente."
- **(II)** "O saque diário máximo é R$ 1.000; o saldo nunca pode ficar negativo; o comprovante é emitido a cada saque."
- **(III)** Uma tabela com o tipo de conta nas linhas e a tarifa de saque correspondente nas colunas.

Qual classificação dos formatos está correta?
A) (I) orientado a cenários; (II) e (III) orientados por regras  
B) (I) e (II) orientados a cenários; (III) orientado por regras  
C) (I) orientado por regras; (II) e (III) orientados a cenários  
D) (I), (II) e (III) orientados a cenários  

---

### 28. Em um refinamento, um stakeholder diz que não sabe como testar uma história de usuário. Segundo o syllabus, o que isso pode indicar?
A) Que a história é Independente e Pequena, conforme o INVEST  
B) Que os critérios de aceite são dispensáveis  
C) Que a história não está suficientemente clara, ou não reflete algo valioso para o stakeholder, ou que ele precisa apenas de ajuda para testar  
D) Que a história é Estimável, mas não Negociável  

---

### 29. História: "Como cliente, quero redefinir minha senha por e-mail, para recuperar o acesso à minha conta." Critérios de aceite: o link de redefinição é válido por 30 minutos; a nova senha deve ter no mínimo 8 caracteres e pelo menos 1 número. Qual conjunto de casos de teste está mais alinhado ao ATDD?
A) Apenas casos negativos: link expirado, senha com 7 caracteres e senha sem número  
B) Redefinição com senha de 8 caracteres e número; redefinição com senha de 12 caracteres e número; link expirado  
C) Redefinição com sucesso; link expirado; senha com 7 caracteres; senha sem número; login por impressão digital  
D) Redefinição com link válido e senha de 8 caracteres com número (sucesso); link expirado (rejeita); senha com 7 caracteres (rejeita); senha sem número (rejeita)  

---

### 30. Qual é a sequência típica do desenvolvimento orientado por testes de aceite (ATDD)?
A) Workshop de especificação para analisar e escrever a história e seus critérios de aceite, resolvendo lacunas e ambiguidades; criação dos casos de teste (positivos, depois negativos e depois não funcionais); automação dos testes, que passam a ser requisitos executáveis  
B) Implementação da história; criação dos casos de teste após a conclusão do código; workshop de especificação para revisar os resultados  
C) Casos de teste negativos primeiro, depois positivos, ignorando as características não funcionais  
D) Criação dos casos de teste apenas pelos desenvolvedores, após a implementação, sem participação do cliente  

---

## GABARITO

| #  | Resp | Explicação |
|----|------|------------|
| 1  | B | (K2 · 4.1.1) Caixa-preta: casos independem da implementação. Caixa-branca: dependem do projeto/implementação, então só podem ser criados depois. Experiência: eficácia depende das habilidades do testador e complementa as demais. **A** e **D** trocam as definições; **C** erra ao dizer que "substituem". |
| 2  | C | (K3 · 4.2.1) Partições: negativa (inválida), 0–12, 13–17, 18–64 e 65 ou mais = 5 partições. Um teste por partição, inclusive a inválida. **A** esquece a inválida; **B** e **D** inventam partições. |
| 3  | A | (K3 · 4.2.1) Os testes 7 (0–12), 15 (13–17) e 40 (18–64) cobrem 3 das 5 partições = 60%. Faltam a partição negativa e a de 65 ou mais. |
| 4  | D | (K3 · 4.2.1) Na Each Choice Coverage, cada partição de cada conjunto deve ser exercitada ao menos uma vez, sem considerar combinações. O mínimo é o tamanho do maior conjunto (pagamento, com 4 partições). **C** (3 × 4 × 3 = 36) é a pegadinha das combinações. |
| 5  | B | (K2 · 4.2.1) As partições não se sobrepõem, não são vazias, valem para entradas, saídas, valores internos, tempo e parâmetros de interface, e a definição de válido/inválido varia entre equipes. Basta um teste por partição. |
| 6  | C | (K3 · 4.2.2) No BVA de 3 valores, cada limite gera três itens: o valor e seus dois vizinhos. Limite 1: 0, 1, 2. Limite 99: 98, 99, 100. Total: 6 valores. **A** é o BVA de 2 valores. |
| 7  | A | (K3 · 4.2.2) No BVA de 2 valores, cada limite gera o valor e seu vizinho na partição adjacente: 10 e 9; 20 e 21. **C** é o conjunto do BVA de 3 valores (também cobre, mas não é o mínimo). **B** usa vizinhos dentro da partição válida. |
| 8  | D | (K3 · 4.2.2) Com passo de 0,1, o vizinho abaixo de 0,0 é −0,1, e o vizinho acima de 100,0 é 100,1. O conjunto de 2 valores é −0,1; 0,0; 100,0; 100,1. **A** assume inteiros. |
| 9  | B | (K2 · 4.2.2) Exemplo do syllabus: com x = 10 e x = 11 (BVA de 2 valores) o defeito passa despercebido, mas x = 9 (BVA de 3 valores) provavelmente o detecta. O BVA de 3 valores é mais rigoroso, e o BVA só se aplica a partições ordenadas. |
| 10 | C | (K3 · 4.2.3) (V,V,F) cobre R1; (V,F,V) cobre R2; (F,V,F) cobre R5 (C2 é irrelevante). 3 de 5 colunas = 60%. **A** (3/8) é a pegadinha de usar a tabela completa em vez da minimizada. |
| 11 | A | (K2 · 4.2.3) "–" é irrelevante, e "N/A" é inviável. Os itens de cobertura são as colunas com combinações viáveis. A técnica ajuda a achar lacunas e contradições. **C** descreve a tabela de entrada estendida. |
| 12 | D | (K3 · 4.2.3) A tabela completa tem 2³ = 8 colunas. As combinações "não logado + pagamento aprovado" (2 colunas, uma para cada valor de C2) são inviáveis. Restam 6 colunas viáveis. |
| 13 | B | (K3 · 4.2.3) 2⁵ = 32 colunas. O número de regras cresce exponencialmente com o número de condições, e o syllabus indica a tabela minimizada ou uma abordagem baseada em risco para reduzir a execução. |
| 14 | C | (K3 · 4.2.4) Uma sequência (pagar, enviar, entregar) visita Novo, Pago, Enviado e Entregue. O Cancelado exige outro caso (cancelar), pois é estado final. Mínimo: 2. |
| 15 | A | (K3 · 4.2.4) Duas transições chegam a Cancelado (Novo → Cancelado e Pago → Cancelado), e como é estado final, cada uma exige um caso. O terceiro caso cobre a sequência até Entregue (pagar, enviar, entregar). Mínimo: 3. |
| 16 | D | (K3 · 4.2.4) Estados visitados: Novo, Pago, Enviado, Entregue e Cancelado (5/5 = 100%). Transições válidas executadas: 4 de 5 (falta Pago → Cancelado) = 80%. Mostra que a cobertura de todos os estados é mais fraca que a de transições válidas. |
| 17 | B | (K3 · 4.2.4) Na cobertura de todas as transições, os itens são todas as células da tabela de estados: 5 estados × 4 eventos = 20 (5 válidas e 15 inválidas). |
| 18 | C | (K2 · 4.2.4) Todas as transições garantem todos os estados e todas as transições válidas, e uma transição inválida por caso evita o mascaramento de falhas. **A** inverte a força; **B** inverte (a tabela de estados mostra as inválidas, como células vazias); **D** erra porque 0-switch é o critério mais usado. |
| 19 | A | (K3 · 4.3.1 e 4.3.2) T1 executa 1, 2, 3, 4, 6, 7, 11 e T2 executa 1, 2, 3, 4, 6, 9, 11. A união cobre as 8 instruções (100%). Ramificações: a decisão da linha 3 só foi verdadeira (a = 20 nos dois testes), e a da linha 6 foi verdadeira e falsa, então 3 de 4 = 75%. |
| 20 | D | (K3 · 4.3.1 e 4.3.2) Com n = 5 todas as instruções são executadas (1 caso). Para a ramificação falsa da decisão é preciso outro caso (n ≤ 0), então 2 casos. Mostra que a cobertura de ramificação é mais forte que a de instrução. |
| 21 | B | (K2 · 4.3.1) A execução de uma instrução com defeito pode causar falha, mas não detecta defeitos dependentes de dados (divisão por zero) nem garante que as decisões foram testadas. **A** e **D** erram; **C** erra porque 100% de ramificação implica 100% de instrução, mas não o inverso. |
| 22 | C | (K2 · 4.3.3) Ponto forte: considera toda a implementação, mesmo com especificação vaga, desatualizada ou incompleta. Ponto fraco: se um requisito não é implementado, o caixa-branca pode não detectar a ausência. |
| 23 | A | (K2 · 4.4.1) Ataques a falhas são a abordagem metódica da suposição de erro, usando uma lista de possíveis erros, defeitos e falhas, criada com base na experiência, nos dados de defeitos e falhas ou no conhecimento comum sobre por que o software falha. |
| 24 | D | (K2 · 4.4.2) No teste exploratório, os testes são modelados, executados e avaliados simultaneamente. Na abordagem baseada em sessões há período definido, carta de teste, reunião de informação e fichas de sessão. É útil com especificações inadequadas ou pressão de tempo. |
| 25 | C | (K2 · 4.4.3) Os itens devem ser formulados como pergunta e ser verificáveis separadamente e diretamente. Não devem ser muito gerais (**A**), verificáveis automaticamente (**B**) nem mais adequados como critérios de entrada/saída (**D**). |
| 26 | B | (K2 · 4.5.1) Cartão: o meio onde a história é descrita; Conversação: a explicação de como o software será usado (pode ser documentada ou verbal); Confirmação: os critérios de aceite. Estes costumam ser resultado da Conversação. |
| 27 | A | (K2 · 4.5.2) (I) usa Dado/Quando/Então (Given/When/Then, do BDD): orientado a cenários. (II) é uma lista de pontos de verificação e (III) é uma forma tabulada de mapeamento de entrada e saída: ambas orientadas por regras. |
| 28 | C | (K2 · 4.5.1) O syllabus indica três possibilidades: a história não é clara, não reflete algo valioso para ele, ou ele só precisa de ajuda para testar. O INVEST (Independentes, Negociáveis, Valiosas, Estimáveis, Small, Testáveis) inclui a testabilidade como atributo. |
| 29 | D | (K3 · 4.5.3) Os primeiros casos são positivos, depois os negativos. Os casos devem abranger todas as características da história e não ir além dela (**C** inclui impressão digital), e dois casos não devem descrever as mesmas características (**B** repete a redefinição com senha válida). **A** não tem caso positivo. |
| 30 | A | (K2 · 4.5.3) Primeiro vem o workshop de especificação, depois a criação dos casos de teste (positivos, negativos e não funcionais, em linguagem compreensível pelos stakeholders), e então a automação, que torna os testes de aceite requisitos executáveis. Os casos são criados **antes** da implementação. |
