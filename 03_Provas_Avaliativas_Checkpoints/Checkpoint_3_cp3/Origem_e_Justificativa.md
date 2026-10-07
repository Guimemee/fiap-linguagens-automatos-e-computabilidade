# Origem e Justificativa do Problema

**Disciplina:** Linguagens, Autômatos e Computabilidade
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 3

### Enunciado do Problema
Utilizar o Lema do Bombeamento (Pumping Lemma) para provar por contradição que a linguagem L = {a^n b^n | n >= 0} não é regular e não pode ser reconhecida por nenhum AFD.

### Formulação Formal
$$\forall w \in L, |w| \ge p \implies w = xyz, \quad |xy| \le p, \quad |y| \ge 1, \quad \forall i \ge 0: x y^i z \in L$$
