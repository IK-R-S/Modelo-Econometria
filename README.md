## Análise Estatística: Diferença no Uso de IA entre Turnos

### 🎯 Objetivo da Análise
Testar a hipótese de que **o turno (MANHÃ ou NOITE) influencia o uso de Inteligência Artificial (IA)** pelos estudantes para apoio nas disciplinas da faculdade.

---

### 🧪 Hipótese Estatística

- **Hipótese Nula (H₀):** Não há diferença significativa no uso de IA entre os turnos.
- **Hipótese Alternativa (H₁):** Há diferença significativa no uso de IA entre os turnos.

---

### 📊 Variáveis Utilizadas

- `v7` → Turno do curso (MANHÃ ou NOITE)
- `v20` → Indicador se o aluno já utilizou IA para auxílio nas disciplinas
- `usa_ia_professor` → Variável binária derivada de `v20`:
  - `1` = Sim, já utilizou IA
  - `0` = Não utilizou

---

### 📋 Método Estatístico Utilizado

#### Teste Qui-Quadrado de Independência

Este teste avalia se há associação entre duas variáveis categóricas — neste caso, **turno** e **uso de IA**.

##### Requisitos:
- Dados categóricos
- Amostras independentes
- Frequência esperada mínima em cada célula (preferencialmente ≥ 5)

##### Fórmula base da estatística:
\[
\chi^2 = \sum \frac{(O - E)^2}{E}
\]

Onde:
- \( O \) = frequência observada
- \( E \) = frequência esperada (sob hipótese nula)

---

### 🧮 Resultados

| Métrica             | Valor         |
|---------------------|---------------|
| Estatística χ²      | 0.00          |
| p-valor             | 1.00          |
| Graus de liberdade  | 1             |

---

### ✅ Interpretação

Com **p-valor = 1.00**, não há evidência estatística para rejeitar a hipótese nula. Ou seja:

> **O uso de IA pelos alunos é estatisticamente semelhante entre os turnos MANHÃ e NOITE.**

---

### 📌 Conclusão

Com base nos dados coletados, **o turno em que o aluno estuda não influencia significativamente o uso de Inteligência Artificial para apoio nas disciplinas**.

