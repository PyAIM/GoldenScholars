# Number Theory and Combinatorics

## Number Theory: Beyond the Greeks

The Greek inheritance in number theory was Euclid's arithmetical books (VII–IX, including perfect numbers and the infinitude of primes) and Nicomachus's more mystical *Introduction*. The Islamic tradition added genuine theorems.

**Amicable numbers.** The pair (220, 284), each the sum of the other's proper divisors, was known to the Greeks as a curiosity. [Thabit ibn Qurra](../scholars/era-01-foundations.md#thabit-ibn-qurra) (9th c.) proved the first general generating theorem: if \(p = 3\cdot 2^{n-1}-1\), \(q = 3\cdot 2^{n}-1\), and \(r = 9\cdot 2^{2n-1}-1\) are prime, then \((2^n pq,\ 2^n r)\) is an amicable pair. [Kamal al-Din al-Farisi](../scholars/era-06-fourteenth.md#kamal-al-din-al-farisi) (c. 1300) reproved the rule on a new foundation: a worked-out theory of divisors built from prime factorization (with combinatorial counting of divisors), one of the earliest deployments of the fundamental theorem of arithmetic as a working tool. The pair (17296, 18416), often called "Fermat's pair" (1636), appears in the Islamic tradition centuries earlier (attribution discussions include Ibn al-Banna's school and al-Farisi). Euler's eventual generalization (18th c.) closes an arc that Thabit opened.

**Fermat-flavored problems.** [al-Khujandi](../scholars/era-02-tenth-century.md#al-khujandi) claimed (with a defective proof) that \(x^3+y^3=z^3\) has no integer solutions, the cubic case of what became Fermat's Last Theorem. Al-Khazin treated congruent-number-type problems and representations as sums of squares within the Diophantine tradition that Qusta ibn Luqa's translation of Diophantus had opened.

**Sums of powers.** Closed forms for \(\sum k\), \(\sum k^2\), \(\sum k^3\) were inherited and reproved; [Ibn al-Haytham](../scholars/era-03-golden-age.md#ibn-al-haytham) derived \(\sum k^4\) with a method extending to all exponents, motivated by volume computations. These identities, with al-Karaji's and al-Samawal's induction-style proofs, put the tradition at the doorstep of the finite calculus.

**Magic squares.** A substantial Arabic literature (from the 10th-century Ikhwan al-Safa onward, with treatises by al-Buni and others of varying mathematical seriousness) developed general construction methods for magic squares of arbitrary order, work studied in detail by Jacques Sesiano, who credits the tradition with the first general theory.

## Combinatorics: Counting Becomes a Science

Two independent motives drove combinatorial mathematics:

**Language.** Arabic lexicographers beginning with al-Khalil ibn Ahmad (8th c., the first Arabic dictionary) counted the possible roots formable from the alphabet, permutations and combinations of letters, arguably the first large-scale combinatorial enterprise in history.

**The binomial table.** [al-Karaji](../scholars/era-02-tenth-century.md#al-karaji) (c. 1000) constructed the triangle of binomial coefficients with its additive rule for algebraic ends (expanding \((a+b)^n\)); [al-Samawal](../scholars/era-04-twelfth-century.md#al-samawal) preserves the account. In the Maghreb, **Ibn Munim** (d. 1228, Marrakesh) built the same triangle for **counting problems**, words formable from letter sets, combinations of colors of silk tassels, reading \(\binom{n}{k}\) combinatorially; [Ibn al-Banna](../scholars/era-05-maragha.md#ibn-al-banna) then stated the multiplicative formula \(\binom{n}{k} = \frac{n(n-1)\cdots(n-k+1)}{k!}\) and the identity linking combinations to figurate numbers. This Maghrebi line is among the earliest anywhere to treat combinatorics as a general method rather than a scattering of puzzles. (The triangle itself has independent appearances in India, China, and later Europe, "Pascal's triangle" is the historically youngest of its names.)

## Connection to Modern Mathematics

Amicable-number research is alive (the Thabit rule generates pairs still used as examples; whether infinitely many amicable pairs exist remains open). The divisor-counting function \(d(n)\) and multiplicative structure al-Farisi exploited are bedrock analytic number theory. The binomial coefficient identities of al-Karaji, Ibn Munim, and Ibn al-Banna are the opening chapter of every modern combinatorics course, and the lexicographic counting problems of the Arabic grammarians are, in modern dress, problems about words over finite alphabets, the raw material of formal-language theory and information theory. For a cybersecurity-minded reader: al-Kindi's frequency analysis (see [Era I](../scholars/era-01-foundations.md#al-kindi)) is applied combinatorics-and-statistics on letter distributions, the ancestral form of statistical cryptanalysis.

*Sources: Rashed, The Development of Arabic Mathematics (amicable numbers, al-Farisi); Katz (Ibn Munim, Maghrebi combinatorics); Djebbar; J. Sesiano, Magic Squares in the Tenth Century and related studies; Berggren, Episodes.*
