# Varga–Prakrtri— The Cakravala Method of its Solution and the Regular Continued–Fractions

- Author Display: P Singh
- Year: 1984
- Journal Label: IJHS-19-1984-Issue-1
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol19_1_1_PSingh.pdf

<!-- source: gemini page-chunk extraction -->

Indian Journal of History of Science, 19 (1): 1—17 (1983)

# VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION AND THE REGULAR CONTINUED-FRACTIONS

PARMANAND SINGH
R. N. College, Hajipur (Vaishali), Bihar
(Received 13 January 1982)
The article explains the *cakravāla* process with the help of regular (continued-fractions) expansion. It establishes the recursive character of the process which at once proves that the process always leads to the solution of $Nx^2 + c = y^2, (c = 1)$. It is also shown that all quantities produced in the process have simple counter-parts in the regular expansion.

## Cakravāla method for the solution of the equation

$$Nx^2 + c = y^2 \quad \dots (1)$$

and specially $Nx^2 + 1 = y^2 \quad \dots (1\text{a})$
as given by Ācārya Jayadeva[^1] (prior to 1073 A.D.), Bhāskara[^2] (1150 A.D.), and Nārāyaṇa Paṇḍita[^3] (1356 A.D.) etc., is considered to be the absolute climax of the old Indian science and so of all Oriental mathematics. Datta and Singh[^4], Shukla[^5], Srinivasienagar[^6] and others have dealt with the method in detail but none of them has explained the recursive character of the process. Even Ayyangar's[^7] continued-fractions did not at all explain the rules of the cakravāla process specially the interaction between *varga-prakṛti* and *kuṭṭaka*.
Recently Selenius has explained the process with the help of his ideal (semi-regular) continued-fractions (expansion). In this paper, we shall consider the regular (continued-fractions) expansion.
Let $a_n, b_n$ and $r_n$ be defined[^8] by the relations,

$$\frac{\sqrt{N} + b_n}{r_n} = a_n + \frac{\sqrt{N} - b_{n+1}}{r_n} = a_n + \frac{r_{n+1}}{\sqrt{N} + b_{n+1}} \quad \dots (2)$$

for values of $n = 1, 2, 3, \dots$ where $a_n$ is an integer such that

$$a_n < (\sqrt{N} + b_n) / r_n < a_n + 1 \quad \dots (2\text{a})$$

$$\text{and } b_{n+1} = a_n r_n - b_n \quad \dots (2\text{b})$$

$$r_n r_{n+1} = N - b_{n+1}^2 \quad \dots (2\text{c})$$

leading to

$$\sqrt{N} = a_1 + \frac{1}{a_2 +} \frac{1}{a_3 +} \dots \frac{1}{a_{c-1} +} \frac{1}{a_c +} \frac{1}{2a_1 +} \frac{1}{a_2 +} \dots \quad \dots (2\text{d})$$

---
2 PARMANAND SINGH
so that the number of elements in the recurring cycle is $c$. Let $p_r/q_r$ denote the $r\text{th}$ convergent of the continued-fraction.
Ācārya Jayadeva writes[^9], "*Prakṛtau tāvaddadyād yāvati vargo bhavet chepāt*" i.e., "A number should be added to the *prakṛti* until it becomes a square". The same process, of addition (or subtraction) till the *prakṛti* becomes a square, is consistently followed by Bhāskara and Nārāyaṇa. This gives $p_1$ with $q_1 = 1$ if the nearest square is in defect and $p_2$ with $q_2 = 1$ (and $a_2 = 1$) if otherwise. Thus, initially we get (see note 1)

$$
\left.
\begin{aligned}
Nq_1^2 - r_2 &= p_1^2 \\
\text{or } Nq_2^2 + r_3 &= p_2^2
\end{aligned}
\right\}
\quad \dots (3)

$$
Hindu terms for $r_n, q_n$ and $p_n$ are *kṣepa* (the interpolator), *hrasva mūla* (the lesser root) and *jyeṣṭha mūla* (the greater root) respectively (with wider implications).
Now at any stage of the solution let,

$$Nq_{n-1}^2 + (-1)^{n-1} r_n = p_{n-1}^2 \quad \dots (3\text{a})$$

Also, $N.1^2 + (m^2 - N) = m^2$, identically.
So, by Brahmagupta's rule,

$$N(q_{n-1} m + p_{n-1})^2 + (-1)^{n-1} r_n (m^2 - N) = (p_{n-1} m + Nq_{n-1})^2$$

$$\text{or, } N \left( \frac{q_{n-1} m + p_{n-1}}{(-1)^{n-1} r_n} \right)^2 + \frac{m^2 - N}{(-1)^{n-1} r_n} = \left( \frac{p_{n-1} m + Nq_{n-1}}{(-1)^{n-1} r_n} \right)^2 \quad \dots (3\text{b})$$

Nārāyaṇa says[^10], "*Hrasvajyeṣṭhakṣepān bhājyaprakṣepabhājakāna kṛtvā kalpyo guṇo yathā*", i.e., "Making the lesser root, greater root and interpolator (of a square-nature) the dividend, addend and divisor (respectively of a pulveriser), the indeterminate multiplier of it should be determined in the way described before."
So, the equation, $\frac{q_{n-1} \cdot m + p_{n-1}}{(-1)^{n-1} r_n} = s$, an integer $\quad \dots (3\text{c})$
is solved by the method of *kuṭṭaka*. The solution is (see note 2)

$$m = b_{n+1} + (-1)^{n-1} r_n \cdot t \quad \dots (3\text{d})$$

which is of the same form as

$$m = [b_{n+1} + k(-1)^{n-1} r_n] + (-1)^{n-1} r_n \cdot t' \quad \dots (3\text{e})$$

where $k$ is an integer and $t' = t - k$.
---
VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION 3
Now Ācārya Jayadeva and Bhāskara suggest to take only that value of $m$ which makes $m^2 - N$ least.
Least value for $m^2 - N$ is (see note 3) obtained when either

$$
\begin{aligned}
m &= b_{n+1} &\quad \dots (3\text{f}) \\
\text{or } m &= b_{n+1} + r_n &\quad \dots (3\text{g})
\end{aligned}

$$
The solution of the problem can be proceeded with by taking any one out of these two least values provided in the latter case when $m^2 - N$ is not least (numerically), $m$ be nearer to $b_{n+1} + r_n$ in comparison to $b_{n+1}$.
Nārāyaṇa clearly shows his acquaintance with the rule for he is not only silent on making $m^2 - N$ least but takes an example for illustration where a situation is created when two (equal) least values for $m^2 - N$ are obtained by giving to $m$ the above two values. In the same problem, at one stage, he proceeds with the other value instead of the least and that too when $m = b_{n+1} + r_n$ but when $N$ is nearer to $b_{n+1} + r_n$ in comparison to $b_{n+1}$.
Further Nārāyaṇa writes[^11], "*Yathā tadvargāt saṃśodhayet prakṛtim. Prakṛter-guṇavarge vā viśodhite jāyate tu yaccheṣam. Tat kṣepahṛtaṃ kṣepo guṇavargaviśodhite vyastam*", i.e. "The *prakṛti* being subtracted from the square of that or the square of the multiplier being subtracted from the *prakṛti*, the remainder divided by the (original) interpolator is the interpolator (of a new square-nature); and it will be reversed in sign in case of subtraction of the square of the multiplier." Thus, the two separate cases [i.e., when $m(=b_{n+1}) < \sqrt{N}$ and when $m(=b_{n+1} + r_n) > \sqrt{N}$] are clearly recognised.

### Case I.

Let $m = b_{n+1}$, so that, $\frac{m^2 - N}{\pm r_n} = \frac{b_{n+1}^2 - N}{\pm r_n} = \mp r_{n+1}$
and so $m [=b_{n+1}] < \sqrt{N}$.
This is same as using the relation,

$$b_{n+1}^2 - N = -r_n r_{n+1} \quad \dots (4)$$

and so $b_{n+1}^2 < N$.
Simultaneously, $\frac{q_{n-1} b_{n+1} + p_{n-1}}{\pm r_n}$ is obtained as $\pm q_n \quad \dots (4\text{a})$
i.e. $(\pm r_n) (\pm q_n) = b_{n+1} q_{n-1} + p_{n-1} \quad \dots (4\text{b})$
and $\frac{p_{n-1} b_{n+1} + N q_{n-1}}{\pm r_n}$ is obtained as $\pm p_n \quad \dots (4\text{c})$
i.e. $(\pm r_n) (\pm p_n) = b_{n+1} p_{n-1} + N q_{n-1} \quad \dots (4\text{d})$
---
4 PARMANAND SINGH

### Case II.

Let $m = b_{n+1} + r_n$. If $\sqrt{N}$ be nearer to $b_{n+1} + r_n$ in comparison to $b_{n+1}$ then (see note 4) $a_{n+1} = 1$.
Now, $\frac{m^2 - N}{r_n} = \left[ \frac{(b_{n+1} + r_n)^2 - N}{r_n} \right] = r_{n+2}$
and so $m [=b_{n+1} + r_n] > \sqrt{N}$.
The rule is (see note 5) same as using the relation,

$$(b_{n+1} + r_n)^2 - N = r_n r_{n+2} \quad \dots (5)$$

when $a_{n+1} = 1$
and so $(b_{n+1} + r_n)^2 > N$.
Simultaneously, $\frac{q_{n-1}(b_{n+1} + r_n) + p_{n-1}}{\pm r_n}$ is obtained as $\pm q_{n+1} \quad \dots (5\text{a})$
i.e., $(\pm r_n) (\pm q_{n+1}) = (b_{n+1} + r_n) q_{n-1} + p_{n-1} \quad \dots (5\text{b})$
and $\frac{p_{n-1}(b_{n+1} + r_n) + N q_{n-1}}{\pm r_n}$ is obtained as $\pm p_{n+1} \quad \dots (5\text{c})$
i.e., $(\pm r_n) (\pm p_{n+1}) = (b_{n+1} + r_n) p_{n-1} + N q_{n-1} \quad \dots (5\text{d})$
Relations (5b) and (5d) are (see note 6) in fact,

$$(\pm r_n) (\pm q_{n+1}) = \left( \frac{N + b_{n+1} b_{n+2}}{r_{n+1}} \right) q_{n-1} + \left( \frac{b_{n+1} + b_{n+2}}{r_{n+1}} \right) p_{n-1} \quad \dots (5\text{e})$$

and $(\pm r_n) (\pm p_{n+1}) = \left( \frac{N + b_{n+1} b_{n+2}}{r_{n+1}} \right) p_{n-1} + N \left( \frac{b_{n+1} + b_{n+2}}{r_{n+1}} \right) q_{n-1} \quad \dots (5\text{f})$
respectively.
Nārāyaṇa says[^12], "*Labdhiḥ kaniṣṭhamūlaṃ tannijaguṇakāhatam viyuktam ca. Purvālpadapadaparaprakṣiptyorghātena jāyate jyeṣṭham*", i.e., "the quotient (corresponding to that value of the multiplier) is the lesser root (of the new square-nature); and that multiplied by the multiplier and diminished by the product of the previous lesser root and (new) interpolator will be its greater root."
Former part of the statement incorporates the relations (4a) and (5a) and the latter part, (4c) and (5c). Here, Hindu term for $b_{n+1}$ (or $b_{n+1} + r_n$) is *guṇaka* (i.e., the multiplier).
While solving the problem, $103x^2 + 1 = y^2$, Nārāyaṇa writes[^13], "*Ṛnadhanamūlayoruttare karmaṇi kriyamāṇe na viśeṣaḥ tasmādṛṇamūlayordhanatvaṃ prakalpya....*" i.e., "after obtaining the negative and positive roots there is no difference in the (future) process. Therefore, supposing the negative roots as positive...." So we conclude that equivalent forms of formulae (4), (4a), (4c) and (5), (5a), (5c) have been used by Indian mathematicians knowing their full implications,
---
VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION 5
Thus we observe that from $(p_{n-1}, q_{n-1}, r_n)$ is obtained either $b_{n+1}$ or $b_{n+1} + r_n$. The former leads to $(p_n, q_n, r_{n+1})$ and the latter, to $(p_{n+1}, q_{n+1}, r_{n+2})$. In the latter case, the modern process is contracted, $(p_n, q_n, r_{n+1})$ is annihilated and we jump to $(p_{n+1}, q_{n+1}, r_{n+2})$. If $r_n$ is negative $(p_n, q_n)$ or $(p_{n+1}, q_{n+1})$, as the case may be, are obtained as negatives and for further operations their signs are to be changed.
Since initially $(p_1, q_1, r_2)$ or $(p_2, q_2, r_3)$ is obtained and each successive step leads to a convergent of order higher by one or two than the preceding according as $b_{n+1}$ or $b_{n+1} + r_n$ is taken, this proves the recursive character of the cakravāla process, completely.
As an immediate consequence we get a proof that the cakravāla process always leads to a solution of (1a).
From what has been stated above it is clear that all quantities in the cakravāla process have simple counter-parts in the regular (continued-fractions) expansion.
The process is brilliantly shortened by the use of Brahmagupta's Lemma[^14] at a suitable stage. From (3) we have, $Nq_n^2 - p_n^2 = (-1)^{n-1} r_{n+1}$
and $Nq_m^2 - p_m^2 = (-1)^{m+1} r_{m+1}$
So, $N(p_m q_n + q_m p_n)^2 - (N q_m q_n + p_m p_n)^2 = (-1)^{m+n+1} r_{m+1} r_{n+1}$
or, $N(p_m q_n + q_m p_n)^2 \div (-1)^{m+n} r_{m+1} r_{n+1} + (-1)^{m+n+1} r_{m+1} r_{n+1} = (p_m p_n + N q_m q_n)^2 \quad \dots (6)$
The relation becomes useful when,

$$(-1)^{m+n} r_{m+n+1} = (-1)^p r_{p+1} \quad \dots (6\text{a})$$

Let us consider the different cases.

### Case I.

Let $m+n = c(=p)$. Then, from (6a) $r_{m+1}^2 (\approx r_{c+1}) = 1$ as $m+n=c$ so[^15] $r_{m+1} = r_{n+1}$.
Therefore, $r_{m+1}$ divides $p_m q_n + q_m p_n$ and $p_m p_n + N q_m q_n$ separately and $(p_c, q_c)$ is obtained from the Composition of Unequals. Here,

$$
\left.
\begin{aligned}
p_c &= \frac{(p_m p_n + N q_m q_n)}{r_{m+1}} \\
\text{and } q_c &= \frac{(p_m q_n + q_m p_n)}{r_{m+1}}
\end{aligned}
\right\}
\quad \dots (6\text{b})

$$

### Case II.

Let $m = n = c/2$. Due to the above facts $(p_c, q_c)$ can be obtained in this case from $(p_m, q_m)$ by Composition of Equals. Here,
---

### NOTES

[^1]: Shukla, K. S., *Ācārya Jayadeva, the Mathematician*, Gaṇita, 5(1), 1954, p. 1-20.

[^2]: (Bhāskarīya) *Bijagaṇitam*, R. 70-82.

[^3]: *Bījagaṇitāvataṃśa*, i, R. 70-80. Gaṇita Kaumudī, x, R. 1-11.

[^4]: Datta, B. B. and Singh, A. N., *History of Hindu Mathematics*, Motilal Banarsidas, Vol. 2, 1938, p. 141-181.

[^5]: Shukla, K. S., Ibid.

[^6]: Srinivasienagar, C. N., *The History of Ancient Indian Mathematics*, The World Press Pvt. Ltd., p. 110-134.

[^7]: Selenius, C. O., *Rationale of the Cakravāla process of Jayadeva and Bhāskara II*, Historia Mathematica, 2 (1975), p. 167-184.

[^8]: Barnard, S. and Child, J. M., *Higher Algebra*, Macmillan and Co. Ltd., London, 1952, p. 530-531.

**Note (1):** It so happens because in the former case the relation (2a) with $n=1, b_1=0$ and $r_1=1$ gives the value of $a_1$ leading to the above value of $(p_1, q_1)$ with negative interpolator and in the latter case $a_2=1$ leads to $(p_2, q_2)$ with positive interpolator.
**Note (2):** For, from (3c) and (4b)

$$q_{n-1} \cdot m + p_{n-1} = (-1)^{n-1} r_n \cdot s \text{ and}$$

$$q_{n-1} \cdot b_{n+1} + p_{n-1} = (-1)^{n-1} r_n \cdot q_n$$

So, by subtraction, $q_{n-1}(m - b_{n+1}) = (-1)^{n-1} r_n (s - q_n)$
or $\frac{m - b_{n+1}}{(-1)^{n-1} r_n} = \frac{s - q_n}{q_{n-1}} = t$, an integer
or $m = b_{n+1} + (-1)^{n-1} r_n t$ which is the same as (3d) or of the form as (3e).
**Note (3):** It so happens because $b_{n+1} < \sqrt{N} < b_{n+1} + r_n \dots \dots$ from (4) and (5) and any other value for $m$ from (3d) or (3e) will be either less than $b_{n+1}$ or greater than $b_{n+1} + r_n$. Any one out of these two values for $m$ may make $m^2 - N$ least (numerically), the former making it negative and the latter positive.
**Note (4):** For, $b_{n+1} + r_n / 2 < \sqrt{N} < b_{n+1} + r_n$
i.e., $\frac{1}{2} < \frac{\sqrt{N} - b_{n+1}}{r_n} < 1$
But, $\frac{\sqrt{N} - b_{n+1}}{r_n} = \frac{r_{n+1}}{\sqrt{N} + b_{n+1}}$ from (2c)
<<<CONTINUE>>>

6
PARMANAND SINGH

$$ \left. \begin{aligned} p_c &= \frac{1}{2}(p_m^2 + Nq_m^2) \\ q_c &= p_m q_m \end{aligned} \right\} \dots (6c) $$

Case III. Let $m=n$, $r_{m+1}^2 = k^2 r_{p+1}$, $k = 1, 2, p_m$ or $q_m$ and let $p$ be even. Then $(p_p, q_p)$ may be obtained from $(p_m, q_m)$ by Composition of Equals, Here,

$$ \left. \begin{aligned} p_p &= \frac{Nq_m^2 + p_m^2}{k} \\ q_p &= \frac{2p_m q_m}{k} \end{aligned} \right\} \dots (6d) $$

Case III of the rule is not of universal application.
Use of Composition of equal as well as unequal set of roots at suitable stages to obtain the above stated results implies the use of above equivalent formulae in the regular (continued-fractions) expansion under the given conditions.
If, however, $\pm 4$, $\pm 2$ or $-1$ is obtained as an additive, the process is much simplified due to the above results.
Thus, when $-4$ is the interpolator, Composition of Equals leads to 4 as the interpolator.
When 4 is the interpolator, Composition of Equals leads to either 1 or 4 as the interpolator according as the greater root is even or odd. In the latter case Composition of Unequals (of the former roots with the latter) leads to unity as the interpolator.
In case of $\pm 2$ or $-1$ as the interpolator, Composition of Equals leads to unity as the interpolator.
In this respect Brahmagupta’s another Lemma is a convenient tool to change $r_{n+1}$ to a suitable $r_{m+1}$ in certain cases. According to it if, $Nx^2 \pm p^2 d = y^2$ has a solution $(x, y)$, then $Nu^2 \pm d = v^2$ has a solution $(u, v)$ where $u = x/p$ and $v = y/p$.
Though the rule is of much wider application, it is of use in this direction when $(p_n, q_n)$ is a solution of the former equation so that $\pm p^2 d = (-1)^n r_{n+1}$ and $(p_m, q_m)$ is a solution of the latter equation so that $\pm d = (-1)^m r_{m+1}$.
After obtaining one value of $(x, y)$, other values of $(x, y)$ are obtained by the Principle of Composition of equal as well as unequal set of roots. Nārāyaṇa writes[^18] "तुल्यातुल्यपदानां भावनायाऽनन्तमूलानि" i.e., "By the Principle of Composition of equal as well as unequal set of roots, (will be obtained) an infinite number of roots."
---
7
VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION
Though the rule is of wider application, here, since the roots are obtained in the form of $(p_n, q_n)$, the rule implies the use of following equivalent formulae in the regular (continued-fractions) expansion.

$$ \left. \begin{aligned} p_{n+tc} &= p_n p_{tc} + Nq_n q_{tc} \\ q_{n+tc} &= q_n p_{tc} + p_n q_{tc} \end{aligned} \right\} \dots (7) $$

$$ \left. \begin{aligned} p_{(s+t)c} &= p_{sc} p_{tc} + Nq_{sc} q_{tc} \\ q_{(s+t)c} &= q_{sc} p_{tc} + p_{sc} q_{tc} \end{aligned} \right\} \dots (7a) $$

the formula being a particular case of (7) when $n=sc$; and

$$ \left. \begin{aligned} p_{2tc} &= p_{tc}^2 + Nq_{tc}^2 \\ q_{2tc} &= 2p_{tc} q_{tc} \end{aligned} \right\} \dots (7b) $$

the formula being a particular case of (7a) when $s=t$.
As regards the importance of the process, I would simply like to quote Selenius[^17], “....*cakravāla* .... anticipated the European methods by more than a thousand years. .... no European performances in the whole field of algebra at a time much later than Bhāskara’s, nay upto our time, equalled the marvellous complexity and ingenuity of *cakravāla*.”

### ILLUSTRATIONS

Consider[^18] $97x^2 + 1 = y^2$ \dots (8)
The different cycles for $\sqrt{97}$ are

| | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $b$ .. | 0 | 9 | 7 | 8 | 3 | 5 | 4 | 5 | 3 | 8 | 7 | 9 |
| $r$ .. | 1 | 16 | 3 | 11 | 8 | 9 | 9 | 8 | 11 | 3 | 16 | 1 |
| $a$ .. | 9 | 1 | 5 | 1 | 1 | 1 | 1 | 1 | 1 | 5 | 1 | 18 |

$*$ \hfill $*$
$c=11$
As 100 (the nearest square to 97) $> 97$, $(p_2, q_2, r_3)$ is obtained initially and the interpolator obtained is positive. The auxiliary equation is,

$$ 97.1^2 + 3 = 10^2 \dots (8a) $$

---
8
PARMANAND SINGH
By the Lemma,

$$ 97 \left( \frac{1.m + 10}{3} \right)^2 + \frac{m^2 - 97}{3} = \left( \frac{10m + 97.1}{3} \right)^2 \dots (8b) $$

By the method of *kuṭṭaka* the solution of

$$ \frac{m+10}{3} = r, \text{ an integer,} \dots (8c) $$

is

$$ m = 3t + 2 \dots (8d) $$

which on putting $t=3$ gives $m=11$ \dots (8e)
Relation (8a), equations (8b), (8c) and solutions (8d), (8e) are same as (3a), (3b), (3c), (3e) and (3g), respectively with $n=3$, $r=s$ and $k=-2$.
This value of $m$ leads from $(p_2, q_2, r_3)$ to $(p_4, q_4, r_5)$, i.e., the modern process is contracted, $(p_3, q_3, r_4)$ is annihilated and convergent of order higher by two is obtained due to relations (5c), (5a) and (5), respectively. Positive interpolator leads to positive $(p_4, q_4)$. Also, since jump is of order two the sign of the interpolator does not change. The value (of $m$) also makes $m^2 - N$ least and transforms (8b) into

$$ 97.7^2 + 8 = 69^2 \dots (9a) $$

By the Lemma,

$$ 97 \left( \frac{7.p + 69}{8} \right)^2 + \frac{p^2 - 97}{8} = \left( \frac{69.p + 97.7}{8} \right)^2 \dots (9b) $$

Solution of the equation,

$$ \frac{7p + 69}{8} = s, \dots (9c) $$

is

$$ p = 5 + 8t \dots (9d) $$

which on putting $t=1$ gives $p=13$ \dots (9e)
Relation (9a), equations (9b), (9c) and solutions (9d), (9e) are same as (3a), (3b), (3c), (3d) and (3g), respectively with $n=5$ and $m=p$.
Here, we observe that $p^2 \sim N = 72$ for $p (= b_6) = 5$ when $t=0$ as well as for $p (= b_6 + r_5) = 13$ when $t=1$. Nārāyaṇa wisely chooses $p=13$ for illustration for this
---
9
VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION
value of $p$ contracts the (modern) process, annihilates $(p_6, q_6, r_6)$ and jumps to $(p_8, q_8, r_7)$ from $(p_4, q_4, r_5)$ whereas the other value of $p$ leads to $(p_6, q_6, r_6)$.
Now (9b) transforms into

$$ 97.20^2 + 9 = 197^2 \dots (10a) $$

Again, by the Lemma,

$$ 97 \left( \frac{20.q + 197}{9} \right)^2 + \frac{q^2 - 97}{9} = \left( \frac{197.q + 97.20}{9} \right)^2 \dots (10b) $$

Solution of

$$ \frac{20q + 197}{9} = c \dots (10c) $$

is

$$ q = 5 + 9t \dots (10d) $$

which on putting $t=1$ gives $q=14$ \dots (10e)
Relation (10a), equations (10b), (10c) and solutions (10d) and (10e) are same as (3a), (3b), (3c), (3d) and (3g), respectively, with $n=7$, $m=q$ and $s=c$.
Here, $q^2 \sim N$ is least for $q (= b_8) = 5$ and not for $q (= b_8 + r_7) = 14$. However, since $\sqrt{97}$ is nearer to $b_8 + r_7$ in comparison to $b_8$, Nārāyaṇa wisely prefers the latter value for the former value of $q$ leads to $(p_7, q_7, r_8)$ from $(p_6, q_6, r_7)$ whereas the latter value contracts the (modern) process, annihilates $(p_7, q_7, r_8)$ and jumps to $(p_8, q_8, r_9)$ from $(p_6, q_6, r_7)$. This value of $q$ transforms (10b) into

$$ 97.53^2 + 11 = 522^2 \dots (11a) $$

By the Lemma,

$$ 97 \left( \frac{53.r + 522}{11} \right)^2 + \frac{r^2 - 99}{11} = \left( \frac{522.r + 97.53}{11} \right)^2 \dots (11b) $$

Solution of

$$ \frac{53r + 522}{11} = d \dots (11c) $$

is

$$ r = 8 + 11t \dots (11d) $$

which on putting $t=0$ gives $r=8$ \dots (11e)
---
10
PARMANAND SINGH
Relation (11a), equations (11b), (11c) and solutions (11d), (11e) are same as (3a), (3b), (3c) and (3d) and (3f), respectively with $n=9$, $m=r$ and $s=d$. As observed earlier, this value of $r$ makes $r^2 - N$ least and leads from $(p_8, q_8, r_9)$ to $(p_9, q_9, r_{10})$. Since the next convergent has been obtained so the sign of the interpolator changes. Now (11b) transforms into $97.86^2 - 3 = 847^2$ \dots (12a)
By the Lemma,

$$ 97 \left( \frac{86.s + 847}{-3} \right)^2 + \frac{s^2 - 97}{-3} = \left( \frac{847.s + 97.86}{-3} \right)^2 \dots (12b) $$

Solution of

$$ \frac{86s + 847}{-3} = h \dots (12c) $$

is

$$ s = 1 + (-3)t \dots (12d) $$

which on putting $t=-3$ gives $s=10$ \dots (12e)
Relation (12a), equations (12b), (12c) and solutions (12d), (12e) are same as (3a), (3b), (3c), (3e) and (3g), respectively with $n=10$, $m=s$, $s=h$ and $k=2$.
This value of $s$ leads to convergent of order higher by two and so negative interpolator leads to negative $(p_{11}, q_{11})$ which are changed into positive $(p_{11}, q_{11})$ for further operations, as stated earlier. Also, since the jump is of order two, the subsequent interpolator $(r_{12})$ has the sign of previous interpolator $(r_{10})$.
Now (12b) transforms into,

$$ 97(569)^2 - 1 = (5604)^2 $$

which is the same as (3a) with $n=12$. As $(-1)$ has been obtained as the interpolator, Composition of Equals leads to the desired result, i.e.,

$$ 97(6377352)^2 + 1 = (62809633)^2 $$

The solution obtained is $Nq_{22}^2 + 1 = p_{22}^2$ and (since $c=11$) implies the use of the formula (7b).
Other solutions of (8) are obtained by the Composition of equal as well as unequal set of roots which implies the use of formulae (7a) and (7b).
***

[^17]: Selenius, C. O., Rationale of the *Cakravāla* process of Jayadeva and Bhāskara II, *Historia Mathematica*, 2 (1975), p. 167-184.

[^18]: *Bijagaṇitāvataṃśa*, Ex. 38, p. 39-40.

VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION 11
Graphically the following picture emerges:

![Fig. 1. Graphical representation of the iterative steps for $97x^2 + 1 = y^2$](media/p11_page.png)

*Fig. 1. Graphical representation of the iterative steps for $97x^2 + 1 = y^2$*

<!-- figure-resolved-page-render: page=11 image=media/p11_page.png -->

<!-- figure-meta: page=11, position=top, type=diagram -->

$\begin{matrix} p_2 = 10 \\ q_2 = 1 \\ (-1)^2 r_3 = 3 \end{matrix} \rightarrow \left| \begin{matrix} (b_4 + r_3) \\ (8 + 3) \end{matrix} \right| \rightarrow \begin{matrix} p_4 = 69 \\ q_4 = 7 \\ (-1)^4 r_5 = 8 \end{matrix} \rightarrow \left| \begin{matrix} b_6 + r_5 \\ (5 + 8) \end{matrix} \right| \rightarrow$
$\begin{matrix} p_6 = 197 \\ q_6 = 20 \\ (-1)^6 r_7 = 9 \end{matrix} \rightarrow \left| \begin{matrix} (b_8 + r_7) \\ (5 + 9) \end{matrix} \right| \rightarrow \begin{matrix} p_8 = 522 \\ q_8 = 53 \\ (-1)^8 r_9 = 11 \end{matrix} \rightarrow \left| \begin{matrix} b_{10} \\ (8) \end{matrix} \right| \rightarrow$
$\begin{matrix} p_9 = 847 \\ q_9 = 86 \\ (-1)^9 r_{10} = -3 \end{matrix} \rightarrow \left| \begin{matrix} b_{11} + r_{10} \\ (7 + 3) \end{matrix} \right| \rightarrow \begin{matrix} -p_{11} = -5604 \\ -q_{11} = -569 \\ (-1)^{11} r_{12} = -1 \end{matrix} \rightarrow \begin{matrix} p_{11} = 6504 \\ q_{11} = 569 \\ (-1)^{11} r_{12} = -1 \end{matrix} \rightarrow$
$\rightarrow \left| \begin{matrix} \text{Composition} \\ \text{of Equals} \end{matrix} \right| \rightarrow \begin{matrix} p_{22} = 62809633 \\ q_{22} = 6377352 \\ (-1)^{22} r_{23} = 1 \end{matrix} \dots \rightarrow \left| \begin{matrix} \text{Composition of} \\ \text{equal as well as} \\ \text{unequal set of} \\ \text{roots} \end{matrix} \right| \rightarrow$
$\rightarrow \text{Further roots.}$
Next, consider[^19] $67x^2 + 1 = y^2$ \dots (13)
Different cycles for $\sqrt{67}$ are,

| | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $b$ .. | 0 | 8 | 7 | 5 | 2 | 7 | 7 | 2 | 5 | 7 | 8 |
| $r$ .. | 1 | 3 | 6 | 7 | 9 | 2 | 9 | 7 | 6 | 3 | 1 |
| $a$ .. | 8 | 5 | 2 | 1 | 1 | 7 | 1 | 1 | 2 | 5 | 16 |
| | | * | | | | | | | | | * |

$c = 10$
As 64 (the nearest square to 67) < 67, ($p_1, q_1, r_2$) is obtained initially and the interpolator obtained is negative. The auxiliary equation is,

$$67.1^2 - 3 = 8^2$$ \dots (13a)
By the Lemma,

$$67 \left( \frac{1.m + 8}{-3} \right)^2 + \frac{m^2 - 67}{-3} = \left( \frac{8m + 67.1}{-3} \right)^2$$ \dots (13b)
12 PARMANAND SINGH
By the method of $kuṭṭaka$ the solution of

$$\frac{m + 8}{-3} = a$$ \dots (13c)
is

$$m = -3t + 1$$ \dots (13d)
which on putting $t = -2$ gives $m = 7$ \dots (13e)
Relation (13a), equations (13b), (13c) and solutions (13d), (13e) are same as (3a), (3b), (3c), (3e) and (3f), respectively with $n=2$, $s=a$ and $k=-2$.
This value of $m$ leads to convergent of order higher by one and negative interpolator leads to negative ($p_2, q_2$) which are changed into positive ($p_2, q_2$) for further operations. Also, since the jump is of order one, the subsequent interpolator ($r_3$) has a sign different from that of the previous interpolator ($r_2$).
Now (13b) transforms into

$$67.5^2 + 6 = 41^2$$ \dots (14a)
By the Lemma,

$$67 \left( \frac{5.p + 41}{6} \right)^2 + \frac{p^2 - 67}{6} = \left( \frac{41.p + 67.5}{6} \right)^2$$ \dots (14b)
Solution of $\frac{5p + 41}{6} = b$ \dots (14c)
is

$$p = 5 + 6t$$ \dots (14d)
which on putting $t=0$ gives $p=5$ \dots (14e)
Relation (14a), equations (14b), (14c) and solutions (14d), (14e) are same as (3a), (3b), (3c), (3d) and (3f), respectively with $n=3$, $m=p$ and $s=b$.
Now (14b) transforms into

$$67.11^2 - 7 = 90^2$$ \dots (15a)
By the Lemma,

$$67 \left( \frac{11.q + 90}{-7} \right)^2 + \frac{q^2 - 67}{-7} = \left( \frac{90q + 67.11}{-7} \right)^2$$ \dots (15b)
Solution of $\frac{11q + 90}{-7} = c$ \dots (15c)
is

$$q = 2 - 7t$$ \dots (15d)
which on putting $t = -1$ gives $q = 9$ \dots (15e)
VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION 13
Relation (15a), equations (15b), (15c) and solutions (15d), (15e) are same as (3a), (3b), (3c), (3d) and (3g), respectively with $n=4$, $m=q$ and $s=c$.
Now (15b) transforms into $67.27^2 - 2 = 221^2$ which is the same as (3a) with $n=6$.
As $(-2)$ has been obtained as the interpolator, Composition of Equals leads to the result, $67(5967)^2 + 1 = (48842)^2$ which is the same as $N q_{10}^2 + 1 = p_{10}^2$ and since $c=10$, implies the use of the formula (6c).
Further roots of (13) are obtained by the Composition of equal as well as unequal set of roots and implies the use of formulae (7a) and (7b).
Graphically the following picture emerges.

![Fig. 2. Graphical representation of the iterative steps for $67x^2 + 1 = y^2$](media/p13_page.png)

*Fig. 2. Graphical representation of the iterative steps for $67x^2 + 1 = y^2$*

<!-- figure-resolved-page-render: page=13 image=media/p13_page.png -->

<!-- figure-meta: page=13, position=middle, type=diagram -->

$\begin{matrix} p_1 = 8 \\ q_1 = 1 \\ (-1)^1 r_2 = -3 \end{matrix} \rightarrow \left| \begin{matrix} b_3 \\ (7) \end{matrix} \right| \rightarrow \begin{matrix} -p_2 = -41 \\ -q_2 = -5 \\ (-1)^2 r_3 = 6 \end{matrix} \rightarrow \begin{matrix} p_2 = 41 \\ q_2 = 5 \\ (-1)^2 r_3 = 6 \end{matrix} \rightarrow \left| \begin{matrix} b_4 \\ (5) \end{matrix} \right| \rightarrow$
$\begin{matrix} p_3 = 90 \\ q_3 = 11 \\ (-1)^3 r_4 = -7 \end{matrix} \rightarrow \left| \begin{matrix} (b_5 + r_4) \\ (2 + 7) \end{matrix} \right| \rightarrow \begin{matrix} -p_5 = -221 \\ -q_5 = -27 \\ (-1)^5 r_6 = -2 \end{matrix} \rightarrow \begin{matrix} p_5 = 221 \\ q_5 = 27 \\ (-1)^5 r_6 = -2 \end{matrix} \rightarrow$
$\left| \begin{matrix} \text{Composition} \\ \text{of Equals} \end{matrix} \right| \rightarrow \begin{matrix} p_{10} = 48842 \\ q_{10} = 5967 \end{matrix} \rightarrow \text{Composition} \rightarrow \text{Other roots.}$
Consider[^20] $61x^2 + 1 = y^2$ (see note 7) \dots (16)
Different cycles for $\sqrt{61}$ are

| | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $b$ .. | 0 | 7 | 5 | 7 | 5 | 4 | 6 | 4 | 5 | 7 | 5 | 7 |
| $r$ .. | 1 | 12 | 3 | 4 | 9 | 5 | 5 | 9 | 4 | 3 | 12 | 1 |
| $a$ .. | 7 | 1 | 4 | 3 | 1 | 2 | 2 | 1 | 3 | 4 | 1 | 14 |
| | | * | | | | | | | | | | * |

$c = 11$
Initially ($p_2, q_2, r_3$) is obtained. The auxiliary equation is

$$61.1^2 + 3 = 8^2$$ \dots (16a)
14 PARMANAND SINGH
By the Lemma,

$$61 \left( \frac{1.m + 8}{3} \right)^2 + \frac{m^2 - 61}{3} = \left( \frac{8.m + 61.1}{3} \right)^2$$ \dots (16b)
Solution of $\frac{m + 8}{3} = a$ \dots (16c)
is

$$m = 1 + 3t$$ \dots (16d)
which on putting $t = 2$ gives $m = 7$ \dots (16e)
Relation (16a), equations (16b), (16c), and solutions (16d), (16e) are same as (3a), (3b), (3c), (3e) and (3f), respectively with $n = 3$, $s = a$ and $k = 2$.
This value of $m$ transforms (16b) into

$$61.5^2 - 4 = 39^2$$ \dots (17a)
which is the same as (3a) with $n = 4$.
Now since $(-4)$ has been obtained as the interpolator, Composition of Equals leads to 4 as the interpolator due to Brahmagupta’s Lemma (Case III) and we get,

$$61.(195)^2 + 4 = (1523)^2$$ \dots (17b)
which is the same as (3a) with $n = 9$ and implies the use of formula (6d) with $m = 3$, $p = 8$ and $k = 2$.
Again Composition of Unequals of (17a) with (17b) leads to $(-1)$ as the interpolator due to Brahmagupta’s Lemma (Case I) and we have

$$61(3805)^2 - 1 = (29718)^2$$ \dots (17c)
which is the same as (3a) with $n = 12$ and implies the use of formula (6b).
Composition of (17c) with itself leads to

$$61(226153980)^2 + 1 = (1766319049)^2$$ \dots (17d)
which is the same as (3a) with $n = 23$ and implies the use of formula (7b).
Other roots of (16) are obtained by the Composition of equal as well as unequal set of roots of (16) and this implies the use of formulae (7a) and (7b).
VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION 15
Graphically the following picture emerges:

![Fig. 3. Graphical representation of the iterative steps for $61x^2 + 1 = y^2$](media/p15_page.png)

*Fig. 3. Graphical representation of the iterative steps for $61x^2 + 1 = y^2$*

<!-- figure-resolved-page-render: page=15 image=media/p15_page.png -->

<!-- figure-meta: page=15, position=top, type=diagram -->

$\begin{matrix} p_2 = 8 \\ q_2 = 1 \\ (-1)^2 r_3 = 3 \end{matrix} \rightarrow \left| \begin{matrix} b_4 \\ (7) \end{matrix} \right| \rightarrow \begin{matrix} p_3 = 39 \\ q_3 = 5 \\ (-1)^3 r_4 = -4 \end{matrix} \rightarrow \left| \begin{matrix} \text{Composition} \\ \text{cf. (6d)} \end{matrix} \right| \rightarrow$
$\begin{matrix} p_8 = 1523 \\ q_8 = 195 \\ (-1)^8 r_9 = 4 \end{matrix} \rightarrow \left| \begin{matrix} \text{Composition} \\ \text{cf. (6b)} \end{matrix} \right| \rightarrow \begin{matrix} p_{11} = 29718 \\ q_{11} = 3805 \\ (-1)^{11} r_{12} = -1 \end{matrix} \rightarrow$
$\begin{matrix} \text{Composition} \\ \text{cf. (7b)} \end{matrix} \rightarrow \begin{matrix} p_{22} = 226153980 \\ q_{22} = 1766319049 \\ (-1)^{22} r_{23} = 1 \end{matrix} \rightarrow \text{Composition} \rightarrow \text{Other roots}$

## NOTES

(1) It so happens because in the former case the relation (2a) with $n=1$, $b_1=0$ and $r_1=1$ gives the value of $a_1$ leading to the above value of ($p_1, q_1$) with negative interpolator and in the latter case $a_2=1$ leads to ($p_2, q_2$) with positive interpolator.
(2) For, from (3c) and (4b)

$$q_{n-1}.m + p_{n-1} = (-1)^{n-1} r_n . s \text{ and}$$

$$q_{n-1}.b_{n+1} + p_{n-1} = (-1)^{n-1} r_n q_n$$

So, by subtraction, $q_{n-1}(m - b_{n+1}) = (-1)^{n-1} r_n(s - q_n)$
or $\frac{m - b_{n+1}}{(-1)^{n-1} r_n} = \frac{s - q_n}{q_{n-1}} = t$, an integer
or $m = b_{n+1} + (-1)^{n-1} r_n t$ which is the same as (3d) or of the form as (3e).
(3) It so happens because $b_{n+1} < \sqrt{N} < b_{n+1} + r_n \dots$ from (4) and (5) and any other value for $m$ from (3d) or (3e) will be either less than $b_{n+1}$ or greater than $b_{n+1} + r_n$. Any one out of these two values for $m$ may make $m^2 - N$ least (numerically), the former making it negative and the latter positive.
(4) For, $b_{n+1} + r_n / 2 < \sqrt{N} < b_{n+1} + r_n$
i.e., $\frac{1}{2} < \frac{\sqrt{N} - b_{n+1}}{r_n} < 1$
But, $\frac{\sqrt{N} - b_{n+1}}{r_n} = \frac{r_{n+1}}{\sqrt{N} + b_{n+1}}$ from (2c)

[^19]: $Bijaganitavatamsa, p. 102-103.$

[^20]: $Bijaganitam, p. 102-104.$

16
PARMANAND SINGH
so, $1 < \frac{\sqrt{N} + b_{n+1}}{r_{n+1}} < 2$ and so $a_{n+1} = 1$ \hfill from (2a).
(5) It so happens because,

$$ \begin{aligned} \frac{(b_{n+1} + r_n)^2 - N}{r_n} &= \frac{r_n^2 + 2b_{n+1}r_n - r_n r_{n+1}}{r_n} && \text{from (2c)} \\ &= r_n + 2b_{n+1} - r_{n+1} \\ &= \frac{N - b_{n+1}^2 + 2b_{n+1}r_{n+1} - r_{n+1}^2}{r_{n+1}} && \text{from (2c)} \\ &= \frac{N - b_{n+2}^2}{r_{n+1}} && \text{from (2b) and as } a_{n+1} = 1 \\ &= r_{n+2} && \text{from (2c).} \end{aligned} $$

(6) It so happens[^21] because,

$$ \begin{aligned} \frac{N + b_{n+1}b_{n+2}}{r_{n+1}} &= \frac{N - r_n r_{n+1} + b_{n+1}b_{n+2} + r_n r_{n+1}}{r_{n+1}} \\ &= \frac{b_{n+1}^2 + b_{n+1}b_{n+2} + r_n r_{n+1}}{r_{n+1}} && \text{from (2c)} \\ &= \frac{b_{n+1}a_{n+1}r_{n+1} + r_n r_{n+1}}{r_{n+1}} && \text{from (2b)} \\ &= b_{n+1} + r_n \quad \text{as } a_{n+1} = 1 \\ \text{and } \frac{b_{n+1} + b_{n+2}}{r_{n+1}} &= 1 && \text{from (2c) and as } a_{n+1} = 1 \end{aligned} $$

(7) The same problem was proposed by Fermat in 1657 and solved by Euler in 1732.

### ACKNOWLEDGEMENT

The author expresses his sincere gratitude to Dr. K. S. Shukla, Retd. Professor, Lucknow University for his kind guidance and help.

### REFERENCES

[^1]: Śukla, K. S., Ācārya Jayadeva, the Mathematician, *Gaṇita*, 5(1), 1954, p. 1-20.

[^2]: (*Bhāskarīya*) *Bījagaṇitam*, R. 70-82.

[^3]: *Bījagaṇitāvataṃśa*, i, R. 70-80.  

*Gaṇita Kaumudī*, x, R. 1-11.

[^4]: Datta, B. B. and Singh, A. N., *History of Hindu Mathematics*, Motilal Banarsidas, Vol. 2, 1938, p. 141-181.

[^5]: Shukla, K. S., Ibid.

[^6]: Srinivasiengar, C. N., *The History of Ancient Indian Mathematics*, The World Press Pvt. Ltd.,

---
VARGA-PRAKṚTI—THE CAKRAVĀLA METHOD OF ITS SOLUTION
17
Calcutta, p. 110-134.

[^7]: Selenius, C. O., Rationale of the *Cakravāla* process of Jayadeva and Bhāskara II, *Historia Mathematica*, 2 (1975), p. 167-184.

[^8]: Barnard, S. and Child, J. M., *Higher Algebra*, Macmillan and Co. Ltd., London, 1952, p. 530-531.

[^9]: Shukla, K. S., Ibid., i, R. 77.

[^10]: *Bījagaṇitāvataṃśa*, x, R. 8.

[^11]: *Bījagaṇitāvataṃśa*, i, R. 77-78.  

*Gaṇita Kaumudī*, x, R. 8c-9.

[^12]: *Bījagaṇitāvataṃśa*, i, R. 79.  

*Gaṇita Kaumudī*, x, R. 10.

[^13]: *Bījagaṇitāvataṃśa*, p. 39.  

*Gaṇita Kaumudī*, p. 237.

[^14]: *Brāhmasphuṭa Siddhānta*, xviii, R. 64-5.

[^15]: Barnard, S. and Child, J. M., Ibid., p. 536.

[^16]: *Bījagaṇitāvataṃśa*, x, R. 76b.  

*Gaṇita Kaumudī*, i, R. 7c-d.

[^17]: Selenius, C. O., Ibid.

[^18]: *Bījagaṇitāvataṃśa*, Ex. 38, p. 39-40.  

*Gaṇita Kaumudī*, Ex. 2, p. 237-39.

[^19]: *Bījagaṇitant*, p. 102-103.

[^20]: *Bījagaṇitam*, p. 102-104.

[^21]: Barnard, S. and Child, J. M., Ibid., Cf. formulae (C) and (D), p. 535.
