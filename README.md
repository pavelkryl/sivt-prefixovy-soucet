# Prefixový součet

**vstup**: Pole čísel A o délce n

**výstup**: Pole, které na pozici _i_ má číslo, odpovídající součtu prvků původního pole _A_ od začátku až do indexu _i_

**postup**
- inicializace: Vytvoříme nové pole _S_ o délce _n_ pro uložení preﬁxových součtů.
- první prvek: Nastavíme `S[0] = A[0]`
- iterace: Pro každé _i_ od _1_ do _n − 1_ provedeme: `S[i] = S[i − 1] + A[i]`
