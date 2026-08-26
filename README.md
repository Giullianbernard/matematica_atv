# matematica_atv

# ==============================================================================
# GABARITO RESOLVIDO E COM CÁLCULOS: TEORIA DOS CONJUNTOS
# ==============================================================================

# ------------------------------------------------------------------------------
# Questão 1: Cardinalidade do conjunto A = {1, 2, 3, 4, 5}
# 
# |A| = quantidade de elementos distintos contidos em A

# |A| = 1 + 1 + 1 + 1 + 1 = 5
# RESPOSTA: B. 5

# ------------------------------------------------------------------------------
# Questão 2: A = {x ∈ N | 0 < x < 1}
# 
# Conjunto dos Naturais N = {0, 1, 2, 3, ...}

# Não existe número inteiro n tal que 0 < n < 1.

# Logo, n_elementos = 0  =>  A = ∅
# RESPOSTA: D. A = ∅

# ------------------------------------------------------------------------------
# Questão 3: Relação A ⊂ B (Subconjunto próprio)
# 
# A ⊂ B  <=>  (∀ x ∈ A, x ∈ B) e (∃ y ∈ B | y ∉ A)

# Significa que todos os elementos de A estão em B, mas |A| < |B|.

# RESPOSTA: B. Todo elemento de A está em B, e existe pelo menos um elemento de B que não está em A.

# ------------------------------------------------------------------------------
# Questão 4: A = {2, 4, 6} e B = {4, 6, 8, 10}. Determinar A ∪ B.
# 
# A ∪ B = {x | x ∈ A ou x ∈ B}
# Elementos de A: 2, 4, 6

# Elementos de B: 4, 6, 8, 10

# A ∪ B = {2, 4, 6} ∪ {4, 6, 8, 10} = {2, 4, 6, 8, 10}
# RESPOSTA: B. {2, 4, 6, 8, 10}

# ------------------------------------------------------------------------------
# Questão 5: A = {2, 4, 6} e B = {4, 6, 8, 10}. Determinar A ∩ B.
# Cálculo:
# A ∩ B = {x | x ∈ A e x ∈ B}
# 
# 2 ∈ A, mas 2 ∉ B
# 4 ∈ A e 4 ∈ B  -> SIM

# 6 ∈ A e 6 ∈ B  -> SIM

# A ∩ B = {4, 6}
# RESPOSTA: A. {4, 6}

# ------------------------------------------------------------------------------
# Questão 6: A = {1, 2, 3} e B = {3, 4, 5}. Determinar B - A.
# 
# B - A = {x ∈ B | x ∉ A}
# Testando os elementos de B:
# 3 ∈ B e 3 ∈ A  -> Remove 3

# 4 ∈ B e 4 ∉ A  -> Mantém 4

# 5 ∈ B e 5 ∉ A  -> Mantém 5
# B - A = {4, 5}
# RESPOSTA: C. {4, 5}


# ------------------------------------------------------------------------------
# Questão 7: Fórmula equivalente para Diferença Simétrica (A ⊖ B)
# 
# A ⊖ B = (A - B) ∪ (B - A)

# Pela propriedade das operações: (A - B) ∪ (B - A) = (A ∪ B) - (A ∩ B)
# RESPOSTA: A. (A ∪ B) - (A ∩ B)

# ------------------------------------------------------------------------------
# Questão 8: A = {1, 2, 3} e B = {3, 4, 5}. Calcular A ⊖ B.
# 
# Passo 1: A ∪ B = {1, 2, 3, 4, 5}


# Passo 2: A ∩ B = {3}
# Passo 3: A ⊖ B = (A ∪ B) - (A ∩ B) = {1, 2, 3, 4, 5} - {3} = {1, 2, 4, 5}

# RESPOSTA: C. {1, 2, 4, 5}


# ------------------------------------------------------------------------------
# Questão 9: A e B disjuntos (A ∩ B = ∅). Calcular A ⊖ B.

# 
# A ⊖ B = (A ∪ B) - (A ^ B)
# Substituindo A ∩ B = ∅:

# A ⊖ B = (A ∪ B) - ∅ = A ∪ B
# RESPOSTA: D. A ∪ B


# ------------------------------------------------------------------------------
# Questão 10: Princípio da Inclusão-Exclusão para dois conjuntos.
# 
# Ao somar |A| e |B|, a interseção |A ^ B| é contada duas vezes.

# Portanto, deve-se subtrair a interseção uma vez:

# |A ∪ B| = |A| + |B| - |A ∩ B|
# RESPOSTA: C. |A| + |B| - |A ∩ B|


# ------------------------------------------------------------------------------
# Questão 11: Total = 100 alunos | |Python| = 60 | |Java| = 50 | |Python ∩ Java| = 20
# 
# |P ∪ J| = |P| + |J| - |P ∩ J|
# |P ∪ J| = 60 + 50 - 20


# |P ∪ J| = 110 - 20 = 90



# RESPOSTA: A. 90

# ------------------------------------------------------------------------------
# Questão 12: Quantos alunos NÃO programam nem em Python nem em Java?
# 
# |(P ∪ J)'| = Total_Alunos - |P ∪ J|
# |(P ∪ J)'| = 100 - 90 = 10
# RESPOSTA: A. 10

# ------------------------------------------------------------------------------
# Questão 13: Número máximo de subconjuntos disjuntos em Diagrama de Venn para n = 4.
# 

# Cada elemento do universo pode estar contido ou não em cada um dos n conjuntos (2 opções por conjunto).
# N_regioes = 2^n



# N_regioes = 2^4 = 2 * 2 * 2 * 2 = 16
# RESPOSTA: D. 16

# ------------------------------------------------------------------------------
# Questão 14: Junção INNER JOIN no SQL em relação à Teoria dos Conjuntos.
# 

# INNER JOIN retorna apenas os registros que possuem correspondência em AMBAS as tabelas.
# Matematicamente: x ∈ TabelaA AND x ∈ TabelaB  => Intersecção (A ∩ B)


# RESPOSTA: C. Intersecção (A ∩ B)

# ------------------------------------------------------------------------------
# Questão 15: Cardinalidade de A é |A| = 4. Qual é a cardinalidade de P(A)?
# 
# |P(A)| = 2^|A|
# |P(A)| = 2^4 = 16


# RESPOSTA: D. 16

# ------------------------------------------------------------------------------
# Questão 16: A = {x, y} e B = {1, 2}. Produto Cartesiano A x B.
# 
# A x B = {(a, b) | a ∈ A e b ∈ B}
# |A x B| = |A| * |B| = 2 * 2 = 4 pares ordenados.
# Pares: (x, 1), (x, 2), (y, 1), (y, 2)
# A x B = {(x, 1), (x, 2), (y, 1), (y, 2)}
# RESPOSTA: C. {(x, 1), (x, 2), (y, 1), (y, 2)}

# ------------------------------------------------------------------------------
# Questão 17: Sobre o Produto Cartesiano A x B.
# 


# Por definição de par ordenado, (a, b) z (b, a) quando a ≠ b.
# Logo, A x B z B x A (não comutativo).

# RESPOSTA: C. Ele não é comutativo, pois a ordem dos elementos nos pares ordenados importa.

# ------------------------------------------------------------------------------
# Questão 18: Lei de De Morgan para o complementar da interseção (A ∩ B)'
#
# A negação/complemento da interseção é a união dos complementos:
# (A ∩ B)' = A' ∪ B'  (ou Ā ∪ B̄)
# RESPOSTA: B. Ā ∪ B̄

# ------------------------------------------------------------------------------
# Questão 19: Lei da Absorção: A ∪ (A ∩ B)
# 


# Como (A ∩ B) ⊆ A, ao fazer a união de A com um subconjunto dele mesmo, o resultado é o próprio A.
# A ∪ (A ∩ B) = A
# RESPOSTA: C. A

# ------------------------------------------------------------------------------
# Questão 20: Condições para uma partição válida de um conjunto U.
# 
# Uma coleção {A1, A2, ...} é partição de U se:
# 1) Ai ≠ ∅ para todo i


# 2) Ai ∩ Aj = ∅ para i ≠ j (mutuamente disjuntos)
# 3) A1 ∪ A2 ∪ ... = U (a união forma U)
# RESPOSTA: B. A união dos subconjuntos deve formar U e eles devem ser mutuamente disjuntos.

# ------------------------------------------------------------------------------
# Questão 21: U = N, T0 = pares, T1 = ímpares. {T0, T1} é partição de N pois:
# 


# T0 ∩ T1 = ∅ (nenhum número é par e ímpar ao mesmo tempo)
# T0 ∪ T1 = N (todo número natural é par ou ímpar)
# RESPOSTA: A. T0 ∩ T1 = ∅ e T0 ∪ T1 = N.


# ------------------------------------------------------------------------------
# Questão 22: Lei da Diferença para reescrever A - B.
# 
# Pertencer a (A - B) significa pertencer a A E NÃO pertencer a B (isto é, pertencer a B').
# A - B = A ∩ B' (ou A ∩ B̄)

# RESPOSTA: B. A ∩ B̄

# ------------------------------------------------------------------------------
# Questão 23: Resultado da operação A ∪ A' (conjunto unido ao seu complementar).
# 


# Por definição de complementar, A' = U - A.
# A ∪ A' = A ∪ (U - A) = U (Conjunto Universo)
# RESPOSTA: B. Conjunto Universo (U).

# ------------------------------------------------------------------------------
# Questão 24: Lei Comutativa da Interseção.
# 
# A ordem dos operandos não altera a interseção:
# A ∩ B = B ∩ A
# RESPOSTA: B. A ∩ B = B ∩ A

# ------------------------------------------------------------------------------
# Questão 25: Operador bitwise/lógico equivalente à interseção (∩).
# 
# x ∈ (A ∩ B) <=> (x ∈ A) AND (x ∈ B)
# Operador correspondente: AND (∧)

# RESPOSTA: C. AND (∧)

# ------------------------------------------------------------------------------
# Questão 26: |A| = 10, |B| = 15, |A ∪ B| = 20. Qual o valor de |A ∩ B|?
# 
# |A ∪ B| = |A| + |B| - |A ∩ B|
# 20 = 10 + 15 - |A ∩ B|
# 20 = 25 - |A ∩ B|

# |A ∩ B| = 25 - 20
# |A ∩ B| = 5

# RESPOSTA: B. 5

# ------------------------------------------------------------------------------
# Questão 27: Princípio da Inclusão-Exclusão para 3 conjuntos:
# 
# |A ∪ B ∪ C| = |A| + |B| + |C| - |A ∩ B| - |A ∩ C| - |B ∩ C| + |A ∩ B ∩ C|

# A parcela |A ∩ B ∩ C| foi subtraída 3 vezes e somada 3 vezes nas etapas anteriores,

# devendo ser SOMADA ao final para correção de contagem.
# RESPOSTA: B. Somada.

# ------------------------------------------------------------------------------
# Questão 28: C = {x ∈ Z | x mod 2 = 0}
# 
# Se x mod 2 == 0, o resto da divisão de x por 2 é zero.
# Números inteiros divisíveis por 2 são por definição números pares.
# C = {..., -4, -2, 0, 2, 4, ...}
# RESPOSTA: D. Todos os inteiros pares.

# ------------------------------------------------------------------------------
# Questão 29: Estrutura de dados nativa em Python para conjuntos:
# 
# - Elimina duplicatas automaticamente.
# - Suporta `&` para interseção e `|` para união.

# - Nome da tipo nativo: `set`

# RESPOSTA: D. set

# ------------------------------------------------------------------------------
# Questão 30: Prova teórica: Se A ⊖ B = ∅, o que concluímos sobre A e B?
# 

# A ⊖ B = (A - B) ∪ (B - A) = ∅
# Para que a união de dois conjuntos seja vazia, ambos devem ser vazios:
# 1) A - B = ∅  =>  A ⊆ B


# 2) B - A = ∅  =>  B ⊆ A
# Como A ⊆ B e B ⊆ A, conclui-se obrigatoriamente que A = B.

# RESPOSTA: C. Os conjuntos são idênticos (A = B).
