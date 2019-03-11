---
layout: page
title: Avaliação
permalink: /avaliacao/
---

# Política sobre plágio e direitos autorais

Não é permitido plágio em quaisquer das atividades avaliativas. Durante as provinhas, é admitido consultar material impresso ou escrito, mas não é permitido qualquer tipo de comunicação ou uso de qualquer dispositivo capaz de conectar-se à rede. Nos laboratórios e no projeto, será aplicado o verificador de similaridade [Moss](https://theory.stanford.edu/~aiken/moss/), sendo considerado plágio qualquer resultado com alto índice de similaridade.

**IMPORTANTE**: Não é permitido compartilhar nem publicar códigos dos laboratórios ou do projeto, seja durante ou após o término da disciplina. Violar esta política pode atrapalhar o andamento da disciplina oferecida no MIT, cujos professores estão gentilmente cedendo material didático. Lembrem-se que vocês estão representando não somente a UFSCar como instituição, mas também o Brasil, então **levem esta política bastante a sério**. Devido à seriedade da situação, qualquer violação será **severamente punida**, com reprovação sumária na disciplina e todas as medidas administrativas e judiciais cabíveis por violação de direitos autorais.


# Laboratórios

Os laboratórios podem ser realizados em grupos de até 4 alunos. Para os laboratórios, os grupos podem ser constituídos por integrantes de diferentes turmas e códigos de disciplina (grade nova e grade antiga).

**IMPORTANTE**: Sempre antes de entregar cada um dos laboratórios, os grupos devem ser **cadastrados novamente** no Autolab e todos os integrantes **devem aceitar** novamente o convite. Essa exigência existe para assegurar que todos os alunos inseridos em um grupo estejam realmente participando daquele grupo, e para permitir que os alunos troquem de grupo ao longo da disciplina se assim desejarem.

Na data limite de entrega de cada laboratório (ou na sexta-feira seguinte a essa data), o professor sorteará alguns estudantes para que expliquem individualmente (em cerca de 10 minutos) sua resolução do trabalho. O sorteio será realizado por um gerador pseudoaleatório com distribuição uniforme, independente de sorteios anteriores. Isso significa que:

 * o mesmo estudante pode ser sorteado em múltiplas ocasiões (laboratórios diferentes);

 * diferentes estudantes pertencentes a um mesmo grupo podem ser sorteados para explicar o mesmo laboratório.

Nunca conte com a sorte. Esse procedimento torna imprevisível quais estudantes serão chamados, forçando todos a se preparar para explicar a resolução.

Caso o estudante sorteado esteja ausente, sua nota na atividade será zerada. Caso o desempenho do estudante na explicação ou resposta a perguntas do docente seja considerado insatisfatório, a nota na atividade também será zerada. Em caso de desempenho intermediário, a nota na atividade será reduzida com relação à nota atribuída pela correção automática.


# Projeto

O projeto pode ser realizado em grupos de até 8 alunos. A apresentação do projeto será em grupo, mas poderá ser seguida de perguntas individuais a integrantes do grupo. **Todos os integrantes do grupo precisam estar presentes em um mesmo horário para a apresentação do projeto**, portanto recomenda-se que estejam inscritos na mesma turma e código de disciplina.


# Cálculo das notas

## Nota de Teoria

A Nota de Teoria (NT) é calculada como a média das 5 melhores notas em provinhas:

```python
NT = sum(sorted([P1, P2, P3, P4, P5, P6])[-5:]) / 5
```

## Nota de Laboratório

A Nota de Laboratório (NL) é calculada como a média ponderada das notas nos laboratórios (com peso 1) e da nota de projeto (com peso 2):

```python
NL = (Lab1 + Lab2 + Lab3 + Lab4 + Lab5 + Lab6 + Lab7 + Lab8 + 2*Projeto) / 10
```

## Nota Final

 * Alunos inscritos na disciplina da grade nova recebem nota final `NF = (NT + NL) / 2`.

 * Alunos inscritos na disciplina teórica recebem nota final `NF = NT`.

 * Alunos inscritos na disciplina de laboratório recebem nota final `NF = NL`.


## Ponto por contribuição

Haverá uma recompensa de até 1 ponto na Nota Final por contribuições ao material didático da disciplina. O material original está em inglês, portanto é bem-vinda qualquer ajuda para traduzi-lo, adicionando comentários ao PDF (vide primeira aula da disciplina para exemplo). A quantidade exata somada à Nota Final dependerá dos seguintes fatores:

 * abrangência das contribuições da turma como um todo (abrangem toda as aulas?)
 * pontualidade (as anotações foram adicionadas antes de ocorrer a aula correspondente?)
 * parcela contribuída por cada estudante (contribuiu com a mesma quantidade de anotações que os outros estudantes?)

Para contribuir, solicite ao professor que dê à sua conta Google permissão para adicionar comentários nos PDFs. Somente serão contabilizadas contribuições associadas à conta Google do estudante.
