Acesta este un proiect de la academia Link Academy
Acesta presupune un program de calculator in limbajul java

1) Pentru a lansa programul este nevoie de deschis programul intrun editor spre exemplu VS code si de rulat comanda 'java Start.java'


# Metrici și Observații

## 1. Metrica LOC (Lines of Code)
- **Număr total de linii de cod**: 103
- **Număr linii efective de cod**: 83
- **Număr linii goale**: 15
- **Număr linii de comentarii**: 5

## 2. Complexitatea Ciclomatică
**evaluateExpression()**:
- E = 15
- N = 12 
- Cyclomatic complexity = 15 - 12 + 2 = 5

**Calculate()**:
- E = 14
- N = 11 
- Cyclomatic complexity = 14 - 11 + 2 = 5
## 3. Complexitatea Cognitiva
**evaluateExpression()**:
- Foarte complex cu un procentaj de: 175%

**Calculate()**:
- Foarte complex cu un procentaj de: 287%

Calculat in IntelijIDEA cu ajutorul extensiei: CodeComplexity
## 4. Observații
- **Calculator.java**:
  - **Linia 28**: Comentariile ar putea explica mai bine logica metodei `evaluateExpression`.
  - **Linia 75-88**: Codul din metoda `Calculate` este redundant și poate fi simplificat.
  - **Linia 60**: Gestionarea erorilor poate fi îmbunătățită pentru a oferi feedback clar utilizatorului.
  - **Linia 19**: Numele metodei `ToString` ar putea fi schimbat în `toString()` pentru consistență.
  - **General**: Ar fi benefic să se scrie teste unitare pentru a verifica funcționalitatea și robustețea codului.

## 5. Concluzii
Proiectul îndeplinește cerințele de bază pentru evaluarea expresiilor matematice, dar este nevoie de îmbunătățiri în organizația codului, gestionarea erorilor și documentarea acestuia pentru o întreținere mai bună în viitor.

