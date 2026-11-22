# Relatório Técnico: TP2 (RotaViva / Scrumban)

## Visão geral

Este pacote reúne as respostas dos 10 exercícios do TP2, organizadas por número de exercício, em arquivos `.md` separados. O trabalho parte do cenário do RotaViva após a adoção do Scrum no TP1 e analisa a transição para Scrumban, motivada pela chegada de urgências do suporte que não cabem no ciclo fixo de duas semanas. A base conceitual usada foi o Guia Scrum 2020, os princípios do Kanban (WIP, sistema pull, classes de serviço) e a literatura sobre Scrumban, sem slides da disciplina disponíveis.

## Organização dos arquivos

- `01-Ex.md`: origem do Scrumban, o que herda de Scrum e de Kanban, condições de adequação e recomendação ao Product Owner.
- `02-Ex.md`: comparação entre planejamento por Sprint e fluxo contínuo, convivência dos dois no RotaViva e risco de mistura sem regras.
- `03-Ex.md`: limites de WIP por coluna, justificativa e comportamento esperado quando o limite é atingido.
- `04-Ex.md`: sistema pull, momento de puxar item e redução de sobrecarga individual.
- `05-Ex.md`: impacto de limites altos, exemplo numérico com a Lei de Little e ajuste recomendado.
- `06-Exe.md`: valores hipotéticos, cálculo do CD3 e explicação do resultado ao Product Owner.
- `07-Ex.md`: trade-offs entre valor e complexidade, critério prático e crítica à priorização só por valor.
- `08-Ex.md`: classificação de seis itens, critério de atribuição e sinalização visual no board.
- `09-Ex.md`: política de expedite com limite de um item, prevenção de acúmulo e efeito no fluxo normal.
- `10-Ex.md`: políticas por perfil de stakeholder, relação com classes de serviço e custo de atraso, formato de publicação.

## Decisões tomadas por exercício

**Exercício 1.** A explicação da origem do Scrumban foi separada em duas partes, o que ele herda de cada framework, porque o enunciado pede isso explicitamente. A recomendação ao Product Owner foi escrita em linguagem não técnica, sem termos como WIP ou pull, para atender ao pedido de explicação acessível.

**Exercício 2.** A comparação foi feita pelo que cada abordagem otimiza, e não por uma lista de diferenças soltas. O risco da mistura foi tratado como risco de colapso da previsibilidade, que é o problema que o RotaViva já vive, e as três regras de mitigação foram amarradas a esse risco.

**Exercício 3.** Os limites de WIP foram definidos em função de uma squad de quatro desenvolvedores, coerente com a composição recomendada no TP1. O limite de revisão ficou menor que o de desenvolvimento porque a revisão é atividade de par e tende a virar fila de espera.

**Exercício 4.** O sistema pull foi explicado em contraste com a atribuição antecipada, e o momento de puxar foi amarrado aos limites do Exercício 3, para manter a coerência entre os exercícios.

**Exercício 5.** O exemplo numérico foi construído com a Lei de Little, WIP dividido pela vazão, para mostrar o efeito do limite sobre o tempo de atravessamento. O ajuste recomendado foi o de reduzir primeiro o limite de revisão, porque é onde o acúmulo costuma aparecer primeiro.

**Exercício 6.** Os valores hipotéticos foram justificados pela lógica de custo crescente do bug e de ganho recorrente do ajuste. O cálculo do CD3 foi mostrado completo, e a explicação ao Product Owner foi escrita sem fórmula, para atender ao pedido de linguagem acessível.

**Exercício 7.** O critério prático foi o de priorização em duas etapas, valor e depois viabilidade técnica, com fatiamento de itens de alto valor que têm dependência grande. A crítica à priorização só por valor foi feita pelo argumento de que valor sem viabilidade é promessa, não entrega.

**Exercício 8.** A classificação usou seis itens com justificativa objetiva por classe, e a regra de que item sem consequência imediata mensurável não é expedite foi explicitada para evitar o tudo urgente. A sinalização visual foi descrita por cor e por posição no board, com o limite de expedite visível.

**Exercício 9.** A política de expedite fixou o limite de um item por vez, com aprovação conjunta de Product Owner e Scrum Master. O efeito no fluxo normal foi descrito com o item planejado pausado e visível no board, para tornar o custo da interrupção transparente.

**Exercício 10.** As políticas foram organizadas por perfil de stakeholder, cada uma amarrada a uma classe de serviço e ao custo de atraso. O formato de publicação foi descrito em quatro seções, com linguagem direta e sem jargão, para que stakeholders consultem sem depender do time.

