Acesta este un proiect de la academia Link Academy
Acesta presupune un program de calculator in limbajul java

 Pentru a lansa programul este nevoie de deschis programul intrun editor spre exemplu VS code si de rulat comanda 'java Start.java'

## 1. Metrica LOC (Lines of Code)
- **Număr total de linii de cod**: 103
- **Număr linii efective de cod**: 83
- **Număr linii goale**: 15
- **Număr linii de comentarii**: 5

## 2. Complexitatea Ciclomatică
- **evaluateExpression**:
  - **Arce (E)**: 8
  - **Noduri (N)**: 21
  - **Ieșiri (P)**: 1
  - **Complexitate Cyclică (V(G))**: \( V(G) = 8 - 21 + 2(1) = -11 \)

- **Calculate**:
  - **Arce (E)**: 8
  - **Noduri (N)**: 22
  - **Ieșiri (P)**: 1
  - **Complexitate Cyclică (V(G))**: \( V(G) = 8 - 22 + 2(1) = -12 \)

## 3. Observații
- **Calculator.java**:
  - **Linia 28**: Comentariile ar putea explica mai bine logica metodei `evaluateExpression`.
  - **Linia 75-88**: Codul din metoda `Calculate` este redundant și poate fi simplificat.
  - **Linia 60**: Gestionarea erorilor poate fi îmbunătățită pentru a oferi feedback clar utilizatorului.
  - **Linia 19**: Numele metodei `ToString` ar putea fi schimbat în `toString()` pentru consistență.
  - **General**: Ar fi benefic să se scrie teste unitare pentru a verifica funcționalitatea și robustețea codului.

## 4. Concluzii
Proiectul îndeplinește cerințele de bază pentru evaluarea expresiilor, dar este nevoie de îmbunătățiri în organizația codului, gestionarea erorilor și documentarea acestuia.

Adăugat metrici și observații în README.md
