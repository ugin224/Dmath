My Descrete Math Repository
===========================
Homework 2 - 202355524 KIM WOO JIN 
----------------------------------
### 2.1 Equation Editing

| # | Text | Formula |
|:--|:-------------------------------|:-------------------------------|
| 1 | IF (P AND Q) THEN R            | $(P \land Q) \rightarrow R$ |
| 2 | (P XOR Q) OR R                 | $(P \oplus Q) \lor R$ |
| 3 | NOT P IFF Q                    | $\neg P \leftrightarrow Q$ |
| 4 | FOR ALL x, P(x)                | $(\forall x) P(x)$ |
| 5 | THERE EXISTS AN x, NOT Q(x)    | $(\exists x) \neg Q(x)$ |
| 6 | IF P THEN Q ≡ NOT P OR Q       | $P \rightarrow Q \equiv \neg P \lor Q$ |
| 7 | Euler's Identity               | $e^{i\pi} + 1 = 0$ |
| 8 | SUM from 1 to 100 = 5050       | $\sum_{n=1}^{100} n = 5050$ |

### 2.2 Translation

Using the propositions
- $p$ = "I study"
- $q$ = "I will pass the course"
- $r$ = "The professor accepts bribes"

Translate the following into statements of propositional logic:

1. If I do not study, then I will only pass the course if the professor accepts bribes.  
$\neg p \rightarrow (q \rightarrow r)$
2. If the professor accepts bribes, then I do not study.    
$r \rightarrow \neg p$
3. The professor does not accept bribes, but I study and will pass the course.  
$\neg r\land p \land q$
4. If I study, the professor will accept bribes and I will pass the course.   
$p \rightarrow (r \land q)$
5. I will not pass the course but the professor accepts bribes.    
$\neg q \land r$
