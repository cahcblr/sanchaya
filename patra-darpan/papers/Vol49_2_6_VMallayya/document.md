# Trigonometric Tables in India

- Author Display: V Madhukar Mallayya
- Year: 2014
- Journal Label: IJHS-49-2014-Issue-2
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol49_2_6_VMallayya.pdf

<!-- source: gemini page-chunk extraction -->

Indian Journal of History of Science, 49.2 (2014) 142-156

# TRIGONOMETRIC TABLES IN INDIA

**V MADHUKAR MALLAYYA***
(Received 15 December 2012; revised 25 February 2014)

### ABSTRACT

From Sanskrit literature we get various types of numerical tables such as arithmetical tables, astronomical tables, data preservation tables, reference tables, ready reckoners, trigonometric tables and difference tables for interpolation. Accuracy in astronomical determinations depends on the accuracy in tabular values. So for construction of accurate tabular values several methods are formulated. Special iterative techniques were designed for refining the values and also to generate finer tables with shorter arc bits from coarser tables with larger arc bits thereby forming some sort of *second generation* tables from known tables. A brief survey on development of trigonometric tables is carried out here from a few select works.
**Key words:** Āryabhaṭa, Vaṭeśvara, Rsines, Versed Rsines, Golasāra, Yuktibhāṣā, Trijyā
---

## 1. INTRODUCTION

Numerical tabulation is an ingenious system of representing simple and complex data elements in a compact manner for easy reference and understanding of facts, or for the purpose of storing information or for interpolation of desired functional values or for ready use in further computational procedures so as to simplify computation process to a considerable extent. Numerical tables are in fact functions. As such, study and analysis of tables point towards study and analysis of functions in a broader sense. Study of tables includes study of their history in all aspects, study of computations for preparation of tables, study of computations using tables, study of information provided by tables and study of methods for construction of tables and for reconstruction of old tables so as to improve and update them if need be. Thus an explorative study on numerical tables can be carried out by looking into various aspects such as i) the why, how and when the system of tabulation evolved and the necessity for tabulating their findings, information or data obtained ii) the period and the purpose of the various types of tables iii) the methodology and motivations involved in their constructions iv) how they were used, validity of the tabular data and how they can be updated or upgraded for current use if possible v) how to make modifications and refinements vi) mode of presentation of various tables in compact form such as in versified forms, value based *vākyas*, numerical forms etc and the usage of different systems of expressing numbers such as the *kaṭapayādi* system, *bhūtasaṅkhyā* system, and Āryabhaṭa’s alphabetic system vii) various aspects involved in computation of tabular values and that of computations using the tabular values viii) construction algorithms ix) analysis of table parameters x) techniques for enhancing accuracy xi) mathematical concepts and formulae developed for the purpose of construction of tables and also for using the tabular values xii) type of tabular data and analysis of the contents xiii) classification of tables and xiv) identification and
[^1]
---

[^1]: * Former Professor and Head, Department of Mathematics, Mar Ivanios College, Trivandrum-695015, Kerala, India [Residence: MELTRA- A23, TC. 25/1974(2), Near Gandhariamman Kovil, Trivandrum - 695001, Kerala, India]. Email: crimstvm@yahoo.com

---
TRIGONOMETRIC TABLES IN INDIA 143
study of so far unexplored manuscripts dealing with numerical tables.
Several arithmetical tables can be had from the Vedic literature. Various astronomical texts provide several types of astronomical tables such as planetary tables for computation of longitudes, latitudes of planets; tables for preparation of *pañcāṅga* elements such as *tithi*, *nakṣatra*, *yoga*; eclipse tables; and several other tables giving shadow lengths, ascensions and ascensional differences, mid-heaven longitudes, daylight lengths, time and so on. Moreover they provide various trigonometric tables and their construction techniques.

## 2. TRIGONOMETRIC TABLES

Construction of trigonometric tables is an important topic for discussion in Indian astronomical works. Accuracy in astronomical determinations depends on accuracy in the functional values and so various methods were developed from time to time (Bag 1969, pp. 79-85). Aiming more accuracy, Indian mathematicians generated finer trigonometric tables with smaller arc bits from coarser tables with larger arc bits and this method deserves special mention. Starting from Āryabhaṭa I (b. 476 AD) to Śaṅkara Varman (b. 1800 AD) several astronomers have dealt with trigonometric tables with different arc bits. Generally 24 tabular values were constructed at arc bits of $225'$ by dividing circumference of a circle into 21600 equal parts called *kalas* ($1'$). The choice of $225'$ is based on observation that $96^{\text{th}}$ part of a circle appears to be straight. Balabhadra’s ($8^{\text{th}}$ cent AD) observation (from a lost work *Pulisasiddhānta*) quoted in the *Al Birūni’s India* (Shukla 1983, p. 74; Edward C Sachau 2009, p. 266) supports it. “If anybody asks the reason of this, he must know that each of these *Kardajāt* is $1/96$ of the circle $= 225$ minutes ($= 3\frac{3}{4}$ degrees). And if we reckon its sine, we find it also to be 225 minutes.” Another remark (Shukla 1983, p. 75; Edward C Sachau 2009, p. 265) supports it further. “Human eye sight reaches to a point distant from the earth and its rotundity the $96^{\text{th}}$ part of 5000 *yojana*, i.e $52$ *yojana* (exactly $52\frac{1}{12}$). Therefore a man does not observe its rotundity, and hence the discrepancy of opinions on the subject.” Our eyes can span $1/96$ of Earth’s circumference and so it appears flat. Another justification can be had from the choice of the value $3438'$ for *trijyā R* by Āryabhaṭa I and from his geometrical method meant for deriving Rsines of half arcs starting from $30^\circ$ up to $3^\circ 45' = 225'$. On reaching $225'$ the chord nearly becomes the arc itself and so taken as the first tabular value. 24 tabular values are computed at arc bits of $225'$ using some prescribed algorithm. The last tabular Rsine is that corresponding to the quadrantal arc which is obviously $R$. Different values for $R$ like $60'$, $120'$, $3270'$, $3438'$ and refinements of $3438'$ were used by different astronomers. Āryabhaṭa I logically arrived at the value $3438'$ for $R$. Since the circumference of a circle of diameter 20000 is nearly 62832 (Shukla and Sarma 1976, verse ii. 10, p. 45), the diameter corresponding to circumference $21600'$ will be $\frac{21600 \times 20000}{62832}$ so that $R \approx 3438'$. Later astronomers made further refinement to this value some of which are shown in the Table 1.
The value thus gradually approaches 1 radian. Evolution of latent concept of radian from Āryabhaṭa’s basic considerations up to Mādhava’s power series concept is worth exploring.
Denote the $i^{\text{th}}$ tabular Rsine, Rcosine and Rversine by $J_i = R \sin(ih)$, $K_i = R \cos(ih)$ and $V_i = R - R \sin((l-i)h) = R - J_{l-i}$ for $i = 0, 1, 2, \dots, l$ where $J_0 = 0, l = 3 \times 2^m, m = 0, 1, 2, \dots$ and $h = \frac{5400'}{l}$. Also denote tabular Rsine differences
---
144 INDIAN JOURNAL OF HISTORY OF SCIENCE
Table 1: Āryabhaṭa’s $R$ and some refinements

| Āryabhaṭa I | Govindasvāmin | Vaṭeśvara | Mādhava |
| :--- | :--- | :--- | :--- |
| $R = 3438'$ | $R = 3437' 44'' 19'''$ | $R = \sqrt{11818047' 35''} = (3437' 44'' 19.43''')$ | $R = 3437' 44'' 48'''$ |
| $= 57^\circ 18'$ | $= 57^\circ 17' 44.316''$ | $= 3437' 44'' = 57^\circ 17' 44.322''$ | $= 57^\circ 17' 44.8''$ |

$J_{i+1} - J_i$ by $\Delta J_i$ for $i = 0, 1, 2, \dots, l-1$. Generally for $l = 24$, $m = 3$ and $h = 225'$. $l$ values are computed at arc bits of $h'$. Rsine of a third part of quadrantal arc is $J_{l/3} = R \sin 30^\circ = \frac{R}{2}$ and that of whole is $J_l = R \sin 90^\circ = R$.

### 2.1. Āryabhaṭa I (b. 476 AD)

Āryabhaṭa I’s geometrical method (Shukla and Sarma 1976, vs ii. 11, p. 45) provides two formulae $J_{l-i} = \sqrt{R^2 - J_i^2}$ and $J_{i/2} = \frac{1}{2}\sqrt{J_i^2 + V_i^2}$ with which we can compute $l$ tabular values (Agathe 2006, pp. 60-64) at arc bits of $h'$ or compute the first Rsine $J_1 = R \sin h'$ needed for constructing $l$ tabular values using another algorithm. Geometrical method gives the following algorithm for finding $l = 3 \times 2^m$ values ($m = 0, 1, \dots$):
**Step 1.** $J_k = \frac{R}{2}, J_l = R = 3438', k = \frac{l}{3}, l = 3 \times 2^m$, $m = 0, 1, 2, \dots$ ($m = 3$ for $l = 24$).
**Step 2.** Get $J_{l-i} = \sqrt{R^2 - J_i^2}, V_i = R - J_{l-i}$, $J_{i/2} = \frac{1}{2}\sqrt{J_i^2 + V_i^2}; i = k, \frac{l}{2}, l - \frac{k}{2}, \frac{k}{2}, l - \frac{k}{4}, \frac{1}{2}(l - \frac{k}{2}) \dots$
**Step 3.** Also go to Step 2 with $i = l, \frac{l}{2}, \frac{l}{4}, \dots, l - \frac{l}{4} \dots$
24 tabular Rsines are thus obtained as per the following scheme (Table 2)
The following algorithm gives Āryabhaṭa’s values (Shukla and Sarma 1976, p. 51, vs. ii. 12).
**Step 1:** $R = 3438', J_k = \frac{R}{2}, J_l = R, k = \frac{l}{3}$, $l = 3 \times 2^m, m = 0, 1, 2, \dots$ ($m = 3$ for $l = 24$).
**Step 2:** For $i = k, \frac{k}{2}, \frac{k}{4}, \dots, \frac{k}{2^{m-1}}$, compute $J_{l-i} = \sqrt{R^2 - J_i^2}, V_i = R - J_{l-i}, J_{i/2} = \frac{1}{2}\sqrt{J_i^2 + V_i^2}$
**Step 3:** With $J_1 = J_{\frac{k}{2^m}}$ find $\Delta J_i = J_1 - \frac{J_1 + J_2 + \dots + J_i}{J_1}, J_{i+1} = J_i + \Delta J_i$, $i = 1, 2, 3, \dots, l-1$ [One version says: $\Delta J_i = \Delta J_{i-1} - \frac{\Delta J_0 + \Delta J_1 + \dots + \Delta J_{i-1}}{J_1}$, $\Delta J_0 = J_1$ (i.e.; $\Delta J_i = \Delta J_{i-1} - \frac{J_i}{J_1}, J_{i+1} = J_i + \Delta J_i$) and another: $\Delta J_i = \Delta J_{i-1} - \frac{J_i}{J_1} (\Delta J_0 - \Delta J_1)$, $i = 2, \dots, l-1, \Delta J_0 = J_1, \Delta J_1 = J_1 - \frac{J_1}{J_1}, J_2 = J_1 + \Delta J_1$]
Table 3 shows Āryabhaṭa’s Rsine differences (Shukla and Sarma 1976, p. 29, verse i. 12), Rsines obtained from it or by geometrical method along with actual values $\sin \theta \times (10800/\pi)$.
---
TRIGONOMETRIC TABLES IN INDIA 145
Table 2: Āryabhaṭa’s computation scheme ($l = 24$)

| $i$ | $J_i$ | $i$ | $J_i$ |
| :--- | :--- | :--- | :--- |
| 0 | $J_0 = 0$ | $24 = l$ | $J_l = R$, known |
| $1 = \frac{k}{2^3}$ | Step 3 on $J_2$ | $23 = l - \frac{k}{2^3}$ | Step 2 on $J_1$ |
| $2 = \frac{k}{2^2}$ | Step 3 on $J_4$ | $22 = l - \frac{k}{2^2}$ | Step 2 on $J_2$ |
| $3 = \frac{l}{2^3}$ | Step 3 on $J_6$ (with $k=l$) | $21 = l - \frac{l}{2^3}$ | Step 2 on $J_3$ (with $k=l$) |
| $4 = \frac{k}{2}$ | Step 3 on $J_8$ | $20 = l - \frac{k}{2}$ | Step 2 on $J_4$ |
| $5 = \frac{1}{2^2}(l - \frac{k}{2})$ | Step 3 on $J_{10}$ | $19 = l - \frac{1}{2^2}(l - \frac{k}{2})$ | Step 2 on $J_5$ |
| $6 = \frac{l}{2^2}$ | Step 3 on $J_{12}$ (with $k=l$) | $18 = l - \frac{l}{2^2}$ | Step 2 on $J_6$ (with $k=l$) |
| $7 = \frac{1}{2}(l - \frac{1}{2}(l - \frac{k}{2}))$ | Step 3 on $J_{14}$ | $17 = l - \frac{1}{2}(l - \frac{1}{2}(l - \frac{k}{2}))$ | Step 2 on $J_7$ |
| $8 = k = l/3$ | $J_k = R/2$, known | $16 = l - k$ | Step 2 on $J_8$ |
| $9 = \frac{1}{2}(l - \frac{l}{2^2})$ | Step 3 on $J_{18}$ (with $k=l$) | $15 = l - \frac{1}{2}(l - \frac{l}{2^2})$ | Step 2 on $J_9$ (with $k=l$) |
| $10 = \frac{1}{2}(l - \frac{k}{2})$ | Step 3 on $J_{20}$ | $14 = l - \frac{1}{2}(l - \frac{k}{2})$ | Step 2 on $J_{10}$ |
| $11 = \frac{1}{2}(l - \frac{k}{2^2})$ | Step 3 on $J_{22}$ | $13 = l - \frac{1}{2}(l - \frac{k}{2^2})$ | Step 2 on $J_{11}$ |
| $12 = l/2$ | Step 3 on $J_{24}$ (with $k=l$) | | |

### 2.2. Sūryasiddhānta

The *Sūryasiddhānta* has given a method for construction of tabular Rsines and Rversines along with their values (Phanindralal 2000, pp. 58-59, vs. ii. 15-16; 22c-d; 17-22a-b; 23-27):
**Step 1:** With $J_1 = 225'$ compute $J_{i+1} = J_i + J_1 - \frac{J_1}{J_1} - \frac{J_2}{J_1} - \dots - \frac{J_i}{J_1}$ for $i = 1, 2, \dots, 23$
**Step 2:** With $R = 3438'$ compute $V_i = R - J_{24-i}$ for $i = 1, 2, 3, \dots, 24$.
Rsines are 225, 449, 671; 890, 1105, 1315; 1520, 1719; 1910, 2093; 2267, 2431; 2585, 2728; 2859, 2978; 3084, 3177; 3256, 3321; 3372, 3409; 3431, 3438 and Rversines are 7, 29, 66, 117, 182, 261, 354, 460, 579, 710, 853, 1007, 1171, 1345, 1528, 1719, 1918, 2123, 2333, 2548, 2767, 2989, 3213, 3438.
---
146 INDIAN JOURNAL OF HISTORY OF SCIENCE
Table 3: Āryabhaṭa’s tabular values

| $i$ | Arc $ih'$ | $\Delta J'_i$ | $J'_i$ | Modern value $\sin \theta \times (10800/\pi)$ | $i$ | Arc $ih'$ | $\Delta J'_i$ | $J'_i$ | Modern value $\sin \theta \times (10800/\pi)$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 0 | | 0 | $0'$ | 12 | 2700 | | 2431 | $2430' 51'' 14''' 35.6''''$ |
| | | 225 | | | | | 154 | | |
| 1 | 225 | | 225 | $224' 50'' 21''' 49.6''''$ | 13 | 2925 | | 2585 | $2584' 38'' 05''' 32.0''''$ |
| | | 224 | | | | | 143 | | |
| 2 | 450 | | 449 | $448' 42'' 57''' 35.1''''$ | 14 | 3150 | | 2728 | $2727' 20'' 52''' 22.9''''$ |
| | | 222 | | | | | 131 | | |
| 3 | 675 | | 671 | $670' 40'' 16''' 02.9''''$ | 15 | 3375 | | 2859 | $2858' 22'' 55''' 06.5''''$ |
| | | 219 | | | | | 119 | | |
| 4 | 900 | | 890 | $889' 45'' 15''' 36.7''''$ | 16 | 3600 | | 2978 | $2977' 10'' 33''' 43.6''''$ |
| | | 215 | | | | | 106 | | |
| 5 | 1125 | | 1105 | $1105' 01'' 38''' 56.5''''$ | 17 | 3825 | | 3084 | $3083' 13'' 16''' 56.1''''$ |
| | | 210 | | | | | 93 | | |
| 6 | 1350 | | 1315 | $1315' 34'' 07''' 26.5''''$ | 18 | 4050 | | 3177 | $3176' 03'' 49''' 58.0''''$ |
| | | 205 | | | | | 79 | | |
| 7 | 1575 | | 1520 | $1520' 28'' 35''' 27.6''''$ | 19 | 4275 | | 3256 | $3255' 18'' 21''' 34.9''''$ |
| | | 199 | | | | | 65 | | |
| 8 | 1800 | | 1719 | $1718' 52'' 24''' 11.2''''$ | 20 | 4500 | | 3321 | $3320' 36'' 30''' 12.3''''$ |
| | | 191 | | | | | 51 | | |
| 9 | 2025 | | 1910 | $1909' 54'' 35''' 11.3''''$ | 21 | 4725 | | 3372 | $3371' 41'' 29''' 09.0''''$ |
| | | 183 | | | | | 37 | | |
| 10 | 2250 | | 2093 | $2092' 46'' 03''' 29.5''''$ | 22 | 4950 | | 3409 | $3408' 20'' 10''' 56.0''''$ |
| | | 174 | | | | | 22 | | |
| 11 | 2475 | | 2267 | $2266' 39'' 50''' 12.5''''$ | 23 | 5175 | | 3431 | $3430' 23'' 10''' 38.9''''$ |
| | | 164 | | | | | 7 | | |
| | | | | | 24 | 5400 | | 3438 | $3437' 44'' 48''' 22.5''''$ |

### 2.3. Varāha Mihira ($6^{\text{th}}$ cent AD)

Varāha Mihira’s method (Thibaut and Dvivedi 1997, p. 22, vs. iv. 2-5) is based on repeated application of $J_{i/2} = \frac{1}{2}\sqrt{J_i^2 + V_i^2}$ or $J_{i/2} = \sqrt{\frac{R}{2}V_i}$ starting from Rsines of $30^\circ$, $45^\circ$ and $60^\circ$. Rsines for every increase of $225'$ (Thibaut and Dvivedi 1997, vs. iv. 6-15) with $R = 120'$ are $7' 51''$, $15' 40''$, $23' 25''$, $31' 4''$, $38' 34''$, $45' 56''$, $53' 5''$, $60'$, $66' 40''$, $73' 3''$, $79' 7''$, $84' 51''$, $90' 13''$, $95' 12''$, $99' 46''$, $103' 55''$, $107' 37''$, $110' 52''$, $113' 37''$, $115' 55''$, $117' 42''$, $118' 59''$, $119' 44''$, $120'$ and Rsine differences are $7' 51''$, $7' 49''$, $7' 45''$, $7' 39''$, $7' 30''$, $7' 22''$, $7' 9''$, $6' 55''$, $6' 40''$, $6' 23''$, $6' 4''$, $5' 44''$, $5' 22''$, $4' 59''$, $4' 34''$, $4' 9''$, $3' 42''$, $3' 15''$, $2' 45''$, $2' 18''$, $1' 47''$, $1' 17''$, $0' 45''$, $0' 16''$.

### 2.4. Brahmagupta ($7^{\text{th}}$ cent AD)

Two methods are given in the *Brahmasphuṭa siddhānta* (Sharma, 1996, IV. pp. 1349–1358, vs xxi.17-23) of which one is geometrical. The other based on formulae: $F_1$: $J_{i/2} = \frac{1}{2}\sqrt{J_i^2 + V_i^2}$ (or $J_{i/2} = \sqrt{\frac{D \times V_i}{4}}, D = 2R$), $V_i = R - J_{l-i} = R - \sqrt{R^2 - J_i^2}$ and $F_2$: $J_{l-i} = \sqrt{R^2 - J_i^2}$ is given by:
<<<CONTINUE>>>

TRIGONOMETRIC TABLES IN INDIA 147
Step 1: Apply $F_1$ and $F_2$ for $i = k, \frac{k}{2}, \frac{k}{4}, \dots, \frac{k}{2^{m-1}}$
Step 2: Repeat the same on $J_n$ for every even $n$ starting from $J_k = \frac{R}{2}, R = 3270', k = \frac{l}{3}, l = 3 \times 2^m, m = 0, 1, 2, \dots$ ($m = 3$ for standard 24 tabular values so that $k = 8$)
Step 3: With $J_i = R$ apply the same procedure for $i = l, \frac{l}{2}, \frac{l}{4}, \dots, \frac{l}{2^{m-1}}$.
Brahmagupta’s standard table with $R = 3270'$ (Sharma, 1996, II. pp. 140–141, vs ii.1-9) gives Rsines: $214', 427', 638', 846', 1051', 1251', 1446', 1635', 1817', 1991', 2156', 2312', 2459', 2594', 2719', 2832', 2933', 3021', 3096', 3159', 3207', 3242', 3263', 3270'$ and Rversines: $7', 28', 63', 111', 174', 249', 337', 438', 551', 676', 811', 985', 1114', 1299', 1453', 1635', 1824', 2019', 2219', 2424', 2632', 2843', 3056', 3270'$. Brahmagupta’s shorter table in degrees at bits of $15^\circ$ with $R = 150$ (Sengupta 1934, I. iii. 6) gives Rsines: 39, 75, 106, 130, 145, 150; with first differences: 39, 36, 31, 24, 15 and 5; and second differences: $-3, -5, -7, -9$, and $-10$.

## 2.5. Govindasvāmin (800-850 AD)

Govindasvāmin’s commentary on the *Mahābhāskarīya* of Bhāskara I gives certain rules for computing accurate values and applies corrections to Āryabhaṭa’s Rsine differences: $-9'37''$, $-7'30''$, $-2'42''$, $+4'57''$, $+16'22''$, $+32'26''$, $-5'34''$, $-36'12''$, $+2'09''$, $-8'33''$, $-7'02''$, $+12'10''$, $-13'11''$, $-17'14''$, $+2'02''$, $-12'22''$, $+2'42''$, $-9'28''$, $+14'31''$, $+18'08''$, $+4'59''$, $-21'19''$, $+3'00''$, $+21'37''$ (Kuppanna Sastri, 1957, pp.200-201). Table 4 shows corrected values $J'_i$ with modern values.

## 2.6. Vaṭeśvara (b. 880 AD)

Instead of equating $24^{\text{th}}$ part (i.e $\frac{1}{96}$) of quadrantal arc to its chord, Vaṭeśvara equated a fourth part of the $24^{\text{th}}$ part to the chord. He divided quadrantal arc into 96 equal bits of angular measure $56'.5''$. Being much smaller than the $24^{\text{th}}$ part, it is more qualified to be considered straight and so first tabular sine can be more accurately equated to the angular measure of the first tabular arc. Construction of table of 96 Rsines and versed Rsines is a special feature of the *Vaṭeśvara siddhānta* (Shukla 1986, pp.81–92, Part I ch.ii. vs i.2–51). He used $R^2 = 11818047' 35''$ and $R = 3437'44''$. Following algorithm for $l = 96$ gives Vaṭeśvara’s values (Mallayya, 2008b).
Step 1: Divide quadrantal arc into $l$ bits of size $h = \frac{5400'}{l}$. Take $J_0 = 0, J_1 = h, \Delta J_0 = J_1$.
Step 2: With $R^2 = 11818047'35''$ compute $K_1 = \sqrt{R^2 - J_1^2}, V_1 = R - K_1, \rho = \frac{R}{2V_1}$
Step 3: For $i = 1, 2 \dots, l - 1$, compute $\Delta^2 J_{i-1} = -\frac{J_i}{\rho}$ and $\Delta J_i = \Delta J_{i-1} + \Delta^2 J_{i-1}$
Step 4: For $i = 1, 2 \dots, l - 1$, compute $J_{i+1} = J_i + \Delta J_i, K_{i+1} = \sqrt{R^2 - J_{i+1}^2}$ and $V_{i+1} = R - K_{i+1}$
Vaṭeśvara’s 96 Rsines along with modern values and versed Rsines are given in Table 5.

## 2.7. Āryabhaṭa II (c.950 AD)

Rsines by Āryabhaṭa II (Sudhakara Dvivedi 1995, p. 55, verses iii. 4-8) are 225, 449, 671, 890, 1105, 1315; 1520, 1719; 1910, 2093; 2267, 2431; 2585, 2728; 2859, 2977; 3084, 3177; 3256, 3321; 3371, 3409; 3431, 3438. Rversines are 7, 29, 66, 117, 182, 261, 354, 461, 579, 710, 853, 1007, 1171, 1345, 1528, 1719, 1918, 2123, 2333, 2548, 2767, 2989, 3213, 3438. His Method is:
Step 1: $R = 3438', J_k = \frac{R}{2}, J_l = R, J_{1/2} = 2431'$,
148 INDIAN JOURNAL OF HISTORY OF SCIENCE
Table 4: Govindasvāmin’s corrected values and modern values

| $i$ | Arc $ih'$ | $\Delta J'_i$ | $J'_i$ | Modern value $\sin \theta \times (10800/\pi)$ | $i$ | Arc $ih'$ | $\Delta J'_i$ | $J'_i$ | Modern value $\sin \theta \times (10800/\pi)$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 0 | | 0 | 0 | 12 | 2700 | | $2430'50''54'''$ | $2430'51''14'''35.6''''$ |
| | | $224'50''23'''$ | | | | | $153'46''49'''$ | | |
| 1 | 225 | | $224'50''23'''$ | $224'50''21'''49.6''''$ | 13 | 2925 | | $2584'37''43'''$ | $2584'38''05'''32.0''''$ |
| | | $223'52''30'''$ | | | | | $142'42''46'''$ | | |
| 2 | 450 | | $448'42''53'''$ | $448'42''57'''35.1''''$ | 14 | 3150 | | $2727'20''29'''$ | $2727'20''52'''22.9''''$ |
| | | $221'57''18'''$ | | | | | $131'02''02'''$ | | |
| 3 | 675 | | $670'40''11'''$ | $670'40''16'''02.9''''$ | 15 | 3375 | | $2858'22''31'''$ | $2858'22''55'''06.5''''$ |
| | | $219'04''57'''$ | | | | | $118'47''38'''$ | | |
| 4 | 900 | | $889'45''08'''$ | $889'45''15'''36.7''''$ | 16 | 3600 | | $2977'10''09'''$ | $2977'10''33'''43.6''''$ |
| | | $215'16''22'''$ | | | | | $106'02''42'''$ | | |
| 5 | 1125 | | $1105'01''30'''$ | $1105'01''38'''56.5''''$ | 17 | 3825 | | $3083'12''51'''$ | $3083'13''16'''56.1''''$ |
| | | $210'32''26'''$ | | | | | $92'50''32'''$ | | |
| 6 | 1350 | | $1315'33''56'''$ | $1315'34''07'''26.5''''$ | 18 | 4050 | | $3176'03''23'''$ | $3176'03''49'''58.0''''$ |
| | | $204'54''26'''$ | | | | | $79'14''31'''$ | | |
| 7 | 1575 | | $1520'28''22'''$ | $1520'28''35'''27.6''''$ | 19 | 4275 | | $3255'17''54'''$ | $3255'18''21'''34.9''''$ |
| | | $198'23''48'''$ | | | | | $65'18''08'''$ | | |
| 8 | 1800 | | $1718'52''10'''$ | $1718'52''24'''11.2''''$ | 20 | 4500 | | $3320'36''02'''$ | $3320'36''30'''12.3''''$ |
| | | $191'02''09'''$ | | | | | $51'04''59'''$ | | |
| 9 | 2025 | | $1909'54''19'''$ | $1909'54''35'''11.3''''$ | 21 | 4725 | | $3371'41''01'''$ | $3371'41''29'''09.0''''$ |
| | | $182'51''27'''$ | | | | | $36'38''41'''$ | | |
| 10 | 2250 | | $2092'45''46'''$ | $2092'46''03'''29.5''''$ | 22 | 4950 | | $3408'19''42'''$ | $3408'20''10'''56.0''''$ |
| | | $173'52''58'''$ | | | | | $22'03''00'''$ | | |
| 11 | 2475 | | $2266'38''44'''$ | $2266'39''50'''12.5''''$ | 23 | 5175 | | $3430'22''42'''$ | $3430'23''10'''38.9''''$ |
| | | $164'12''10'''$ | | | | | $7'21''37'''$ | | |
| | | | | | 24 | 5400 | | $3437'44''19'''$ | $3437'44''48'''22.5''''$ |

Table 5: Vaṭeśvara’s 96 tabular values

| $i$ | Arc, $ih$ | Rsine, $J_i$ | Modern value $\sin \theta \times (10800/\pi)$ | Versed Rsines $V_i$ | $i$ | Arc, $ih$ | Rsine, $J_i$ | Modern value $\sin \theta \times (10800/\pi)$ | Versed Rsines $V_i$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | $56'15''$ | $56'15''$ | $56'14''50'''57.9''''$ | $0'27''$ | 49 | $2756'15''$ | $2470'18''$ | $2470'18''05'''53.4''''$ | $1046'59''$ |
| 2 | $112'30''$ | $112'29''$ | $112'28''47'''43.0''''$ | $1'50''$ | 50 | $2812'30''$ | $2509'05''$ | $2509'05''16'''17.6''''$ | $1087'43''$ |
| 3 | $168'45''$ | $168'41''$ | $168'40''56'''03.6''''$ | $4'8''$ | 51 | $2868'45''$ | $2547'12''$ | $2547'12''08'''25.1''''$ | $1129'5''$ |
| 4 | $225'0''$ | $224'50''$ | $224'50''21'''49.6''''$ | $7'21''$ | 52 | $2925'0''$ | $2584'38''$ | $2584'38''05'''32.0''''$ | $1171'5''$ |
| 5 | $281'15''$ | $280'56''$ | $280'56''10'''53.5''''$ | $11'30''$ | 53 | $2981'15''$ | $2621'22''$ | $2621'22''31'''33.4''''$ | $1213'40''$ |
| 6 | $337'30''$ | $336'57''$ | $336'57''29'''11.3''''$ | $16'33''$ | 54 | $3037'30''$ | $2657'25''$ | $2657'24''51'''05.0''''$ | $1256'51''$ |
| 7 | $393'45''$ | $392'53''$ | $392'53''22'''43.3''''$ | $22'31''$ | 55 | $3093'45''$ | $2692'44''$ | $2692'44''29'''22.4''''$ | $1300'38''$ |
| 8 | $450'0''$ | $448'42''$ | $448'42''57'''35.1''''$ | $29'24''$ | 56 | $3150'0''$ | $2727'21''$ | $2727'20''52'''22.9''''$ | $1344'58''$ |
| 9 | $506'15''$ | $504'25''$ | $504'25''19'''58.4''''$ | $37'12''$ | 57 | $3206'15''$ | $2761'13''$ | $2761'13''26'''45.1''''$ | $1389'52''$ |
| 10 | $562'30''$ | $559'59''$ | $559'59''36'''11.7''''$ | $45'55''$ | 58 | $3262'30''$ | $2794'21''$ | $2794'21''39'''50.6''''$ | $1435'20''$ |
| 11 | $618'45''$ | $615'24''$ | $615'24''52'''41.5''''$ | $55'32''$ | 59 | $3318'45''$ | $2826'45''$ | $2826'44''59'''41.5''''$ | $1481'19''$ |
| 12 | $675'0''$ | $670'40''$ | $670'40''16'''02.9''''$ | $66'3''$ | 60 | $3375'0''$ | $2858'23''$ | $2858'22''55'''06.5''''$ | $1527'50''$ |
| 13 | $731'15''$ | $725'44''$ | $725'44''53'''00.4''''$ | $77'29''$ | 61 | $3431'15''$ | $2889'15''$ | $2889'14''55'''35.8''''$ | $1574'51''$ |
| 14 | $787'30''$ | $780'37''$ | $780'37''50'''29.0''''$ | $89'48''$ | 62 | $3487'30''$ | $2919'20''$ | $2919'20''31'''24.4''''$ | $1622'22''$ |
| 15 | $843'45''$ | $835'18''$ | $835'18''15'''35.0''''$ | $10'31''$ | 63 | $3543'45''$ | $2948'39''$ | $2948'39''13'''32.0''''$ | $1670'23''$ |

Contd...
TRIGONOMETRIC TABLES IN INDIA 149

| $i$ | Arc, $ih$ | Rsine, $J_i$ | Modern value $\sin \theta \times (10800/\pi)$ | Versed Rsines $V_i$ | $i$ | Arc, $ih$ | Rsine, $J_i$ | Modern value $\sin \theta \times (10800/\pi)$ | Versed Rsines $V_i$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 16 | $900'0''$ | $889'45''$ | $889'45''15'''36.7''''$ | $117'8''$ | 64 | $3600'0''$ | $2977'10''$ | $2977'10''33'''43.6''''$ | $1718'52''$ |
| 17 | $956'15''$ | $943'58''$ | $943'52''11'''55.4''''$ | $132'8''$ | 65 | $3656'15''$ | $3004'53''$ | $3004'54''04'''29.8''''$ | $1767'49''$ |
| 18 | $1012'30''$ | $997'55''$ | $997'55''30'''45.8''''$ | $148'1''$ | 66 | $3712'30''$ | $3031'49''$ | $3031'49''19'''07.4''''$ | $1817'12''$ |
| 19 | $1068'45''$ | $1051'37''$ | $1051'37''01'''37.8''''$ | $164'47''$ | 67 | $3768'45''$ | $3057'55''$ | $3057'55''51'''39.4''''$ | $1867'1''$ |
| 20 | $1125'0''$ | $1105'1''$ | $1105'01''38'''56.5''''$ | $182'26''$ | 68 | $3825'0''$ | $3083'13''$ | $3083'13''16'''56.1''''$ | $1917'16''$ |
| 21 | $1181'15''$ | $1158'8''$ | $1158'08''31'''13.2''''$ | $200'57''$ | 69 | $3881'15''$ | $3107'41''$ | $3107'41''10'''35.0''''$ | $1967'55''$ |
| 22 | $1237'30''$ | $1210'56''$ | $1210'56''47'''16.4''''$ | $220'20''$ | 70 | $3937'30''$ | $3131'19''$ | $3131'19''09'''01.3''''$ | $2018'57''$ |
| 23 | $1293'45''$ | $1263'25''$ | $1263'25''36'''12.4''''$ | $240'35''$ | 71 | $3993'45''$ | $3154'6''$ | $3154'06''49'''28.4''''$ | $2070'23''$ |
| 24 | $1350'0''$ | $1315'34''$ | $1315'34''07'''26.5''''$ | $261'41''$ | 72 | $4050'0''$ | $3176'3''$ | $3176'03''49'''58.0''''$ | $2122'10''$ |
| 25 | $1406'15''$ | $1367'21''$ | $1367'21''30'''43.3''''$ | $283'38''$ | 73 | $4106'15''$ | $3197'9''$ | $3197'09''49'''20.8''''$ | $2174'19''$ |
| 26 | $1462'30''$ | $1418'47''$ | $1418'46''56'''07.9''''$ | $306'25''$ | 74 | $4162'30''$ | $3217'24''$ | $3217'24''27'''16.7''''$ | $2226'48''$ |
| 27 | $1518'45''$ | $1469'49''$ | $1469'49''34'''06.6''''$ | $330'3''$ | 75 | $4218'45''$ | $3236'47''$ | $3236'47''24'''15.0''''$ | $2279'36''$ |
| 28 | $1575'0''$ | $1520'28''$ | $1520'28''35'''27.6''''$ | $354'31''$ | 76 | $4275'0''$ | $3255'18''$ | $3255'18''21'''34.9''''$ | $2332'43''$ |
| 29 | $1631'15''$ | $1570'43''$ | $1570'43''11'''21.8''''$ | $379'49''$ | 77 | $4331'15''$ | $3272'57''$ | $3272'57''01'''25.5''''$ | $2386'7''$ |
| 30 | $1687'30''$ | $1620'32''$ | $1620'32''33'''23.7''''$ | $405'55''$ | 78 | $4387'30''$ | $3289'43''$ | $3289'43''06'''46.6''''$ | $2439'49''$ |
| 31 | $1743'45''$ | $1669'55''$ | $1669'55''53'''32.2''''$ | $432'51''$ | 79 | $4443'45''$ | $3305'36''$ | $3305'36''21'''28.4''''$ | $2493'46''$ |
| 32 | $1800'0''$ | $1718'52''$ | $1718'52''24'''11.2''''$ | $460'34''$ | 80 | $4500'0''$ | $3320'36''$ | $3320'36''30'''12.3''''$ | $2547'59''$ |
| 33 | $1856'15''$ | $1767'21''$ | $1767'21''18'''10.5''''$ | $489'5''$ | 81 | $4556'15''$ | $3334'43''$ | $3334'43''18'''30.6''''$ | $2602'26''$ |
| 34 | $1912'30''$ | $1815'22''$ | $1815'21''48'''46.4''''$ | $518'24''$ | 82 | $4612'30''$ | $3347'56''$ | $3347'56''32'''47.2''''$ | $2657'6''$ |
| 35 | $1968'45''$ | $1862'53''$ | $1862'53''09'''42.7''''$ | $548'29''$ | 83 | $4668'45''$ | $3360'15''$ | $3360'16''00'''17.6''''$ | $2711'59''$ |
| 36 | $2025'0''$ | $1909'54''$ | $1909'54''35'''11.3''''$ | $579'21''$ | 84 | $4725'0''$ | $3371'41''$ | $3371'41''29'''09.0''''$ | $2767'4''$ |
| 37 | $2081'15''$ | $1956'25''$ | $1956'25''19'''52.8''''$ | $610'59''$ | 85 | $4781'15''$ | $3382'12''$ | $3382'12''48'''20.8''''$ | $2822'19''$ |
| 38 | $2137'30''$ | $2002'24''$ | $2002'24''38'''57.4''''$ | $643'23''$ | 86 | $4837'30''$ | $3391'49''$ | $3391'49''47'''44.6''''$ | $2877'45''$ |
| 39 | $2193'45$ | $2047'52''$ | $2047'51''48'''05.8''''$ | $676'31''$ | 87 | $4893'45''$ | $3400'32''$ | $3400'32''18'''04.2''''$ | $2933'19''$ |
| 40 | $2250'0''$ | $2092'46''$ | $2092'46''03'''29.5''''$ | $710'23''$ | 88 | $4950'0''$ | $3408'20''$ | $3408'20''10'''56.0''''$ | $2989'1''$ |
| 41 | $2306'15''$ | $2137'06''$ | $2137'06''41'''51.8''''$ | $745'0''$ | 89 | $5006'15''$ | $3415'13''$ | $3415'13''18'''49.2''''$ | $3044'51''$ |
| 42 | $2362'30''$ | $2180'53''$ | $2180'53''00'''28.2''''$ | $780'19''$ | 90 | $5062'30''$ | $3421'11''$ | $3421'11''35'''05.4''''$ | $3100'47''$ |
| 43 | $2418'45''$ | $2224'4''$ | $2224'04''17'''07.6''''$ | $816'22''$ | 91 | $5118'45''$ | $3426'14''$ | $3426'14''53'''59.4''''$ | $3156'48''$ |
| 44 | $2475'0''$ | $2266'39''$ | $2266'39''50'''12.5''''$ | $853'6''$ | 92 | $5175'0''$ | $3430'23''$ | $3430'23''10'''38.9''''$ | $3212'54''$ |
| 45 | $2531'15''$ | $2308'39''$ | $2308'38''58'''39.7''''$ | $890'32''$ | 93 | $5231'15''$ | $3433'36''$ | $3433'36''21'''04.5''''$ | $3269'3''$ |
| 46 | $2587'30''$ | $2350'01''$ | $2350'01''02'''01.42''''$ | $928'39''$ | 94 | $5287'30''$ | $3435'54''$ | $3435'54''22'''10.2''''$ | $3325'15''$ |
| 47 | $2643'45''$ | $2390'45''$ | $2390'45''20'''25.3''''$ | $967'26''$ | 95 | $5343'45''$ | $3437'17''$ | $3437'17''11'''42.8''''$ | $3381'29''$ |
| 48 | $2700'0''$ | $2430'51''$ | $2430'51''14'''35.6''''$ | $1006'53''$ | 96 | $5400'0''$ | $3437'44''$ | $3437'44''48'''22.5''''$ | $3437'44''$ |

$l = 3 \times 2^m, m = 0, 1, 2 \dots$ ($m=3, k = 8$ for $l = 24$)
Step 2: Compute $J_{\left(\frac{l \pm i}{2}\right)} = \sqrt{\frac{R \pm J_i}{2}}$ for $i = k, k_1, k_2, k_3$ where $k_n = \frac{l \pm k_{n-1}}{2}, k_0 = k$
Step 3: Proceed as in Step 2 for $i = l_1, l_2$ where $l_n = \frac{l \pm l_{n-1}}{2}, n = 2, 3; l_1 = \frac{l}{2}$. The scheme is shown in Table 6.

## 2.8. Bhāskara II (b.1114 AD)

Bhāskara II gives several methods in the *Siddhāntaśiromaṇi* (Joshi 1988, *Chedyakādhikara* 2-6, *Jyotpattivāsana*) including those by Brahmagupta, Āryabhaṭa II along with some new methods.

### a) Methods based on the following formulae:

1) $J_{\frac{p-q}{2}} = \frac{1}{2} \sqrt{(J_p - J_q)^2 + (K_p - K_q)^2}$ where $K_i = J_{l-i} = \sqrt{R^2 - J_i^2}$. Given $J_l = R$ and $J_k = R/2$,
150 INDIAN JOURNAL OF HISTORY OF SCIENCE
all tabular values can be computed. (for tables of 24 values, $l = 3 \times 2^m = 24, m = 3; k = \frac{l}{3} = 8$)
2) $J_{\frac{i}{2}} = \frac{1}{2} \sqrt{J_i^2 + V_i^2}$ where $V_i = R - K_i = R - \sqrt{R^2 - J_i^2} = J_{l - \frac{l-i}{2}}$.
3) $K_i = R - \frac{2}{R} J_{\frac{i}{2}}^2, J_{l-i} = K_i$ Not all values can be found. But square roots are not involved.
4) $J_{i \pm 1} = \left( J_i - \frac{J_i}{467} \right) \pm \frac{100}{1529} K_i, i = 1, 2, 3, \dots, 24; J_1 = 225 - \frac{1}{7}'$, arc bit being $225'$.
5) Tabular Rsines for every degree increase of arc are given by $J_{(i \pm 1)^\circ} = \left( J_i - \frac{J_i}{6567} \right) \pm \frac{10}{573} K_i, i = 1, 2, \dots, 89$ where $J_1 = 60'$

### b) Method based on refining tabular differences - Munīśvara’s iterative procedure for extracting finer (‘second generation’) tables from known coarser tables

The *Siddhāntaśiromaṇi* (Joshi 1964, *Grahagaṇitādhyāya*, *Spaṣṭādhikāra*, vs 16) gives a method for refining functional differences for interpolating using a table at arc bits of $10^\circ$.

$$d = \frac{1}{2} \left[ (d_b + d_a) - (d_b - d_a) \frac{\rho}{20} \right] \text{ for } kramajyā$$

$$d = \frac{1}{2} \left[ (d_b + d_a) + (d_b - d_a) \frac{\rho}{20} \right] \text{ for } utkramajyā$$

where $d$ is the refined difference applicable in the interior of the interval $(qh, qh + h)$ containing the desired argument $\alpha = qh + \rho, 0 < \rho < h$ where $d_b = \Delta J_{q-1}$ and $d_a = \Delta J_q$ are the tabular differences just before and after that interval. Earlier it was used by Brahmagupta (Sengupta 1934, p.141, ix.8). Taking the value of $d$ for *kramajyā*, the desired Rsine = the tabular Rsine just before $+ \frac{\rho}{h} d$.
Bhāskara’s tabular values for every increase of $h = 10^\circ$ of arc with $R = 120^\circ$ (Joshi 1964, *Spaṣṭādhikāra*, verse 13) are displayed in Table 7.
Using this table, $R\sin(qh + \rho) = J_q + \frac{\rho}{h} d$ can be computed. The refined difference $d$ is given by $d = m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - \Delta J_q}{2} \right)$ where $m = \left( \frac{\Delta J_{q-1} + \Delta J_q}{2} \right)$. Commentator Munīśvara
Table 6: Scheme for finding tabular values by Āryabhaṭa II

| | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $J_0 = 0$ | $J_{24} = R$ | Known | $J_6$ | $J_{18}$ | Step 3 on $J_{12}$ |
| $J_1$ | $J_{23}$ | Step 2 on $J_{22}$ | $J_7$ | $J_{17}$ | Step 2 on $J_{10}$ |
| $J_2$ | $J_{22}$ | Step 2 on $J_{20}$ | $J_8$ | $J_{16}$ | $J_8 = \frac{R}{2}$ known, Step 2 on $J_8$ |
| $J_3$ | $J_{21}$ | Step 3 on $J_{18}$ | $J_9$ | $J_{15}$ | Step 3 on $J_6$ |
| $J_4$ | $J_{20}$ | Step 2 on $J_{16}$ | $J_{10}$ | $J_{14}$ | Step 2 on $J_4$ |
| $J_5$ | $J_{19}$ | Step 2 on $J_{14}$ | $J_{11}$ | $J_{13}$ | Step 2 on $J_2$ |
| $\dots \rightarrow$ | $\dots \rightarrow$ | $\dots \dots \uparrow$ | $J_{12}$ | $\dots$ | known, 2431 or compute using $J_{\left(\frac{l \pm 0}{2}\right)} = \sqrt{\frac{R \pm J_0}{2}}$ |

TRIGONOMETRIC TABLES IN INDIA 151
Table 7: *Siddhāntaśiromaṇi* tabular values

| $i$ | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Arc $ih$ | 0 | $10$ | $20$ | $30$ | $40$ | $50$ | $60$ | $70$ | $80$ | $90$ |
| Rsine diff $\Delta J_i$ | | 21 | 20 | 19 | 17 | 15 | 12 | 9 | 5 | 2 |
| $J_i = R\sin(ih)$ | 0 | 21 | 41 | 60 | 77 | 92 | 104 | 113 | 118 | 120 |

(1653 AD) gives an iterative procedure for further refining the difference $d$ (Mallayya 2008a).
Step 1: Divide the arc $\alpha$ by $h$ ($h = 10^\circ$) and note the quotient $q$ and remainder $\rho$
Step 2: Note the tabular Rsines $J_q$ and $J_{q+1}$, tabular Rsine differences $\Delta J_{q-1}$ and $\Delta J_q$ and compute the mean Rsine difference $m = \frac{\Delta J_{q-1} + \Delta J_q}{2}$
Step 3: With, $d^{(0)} = \Delta J_q$, compute $d^{(r+1)} = m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - d^{(r)}}{2} \right)$ for $r = 0, 1, 2, \dots$
Step 4: Stop when $d$ attains desired level of stability. (When $r = 0$ we get Bhāskara’s value)
Step 5: Compute the desired Rsine using $R\sin \alpha = J_q + \theta d$ where $\theta = \frac{\rho}{h}$.
Using this on Table 7, a refined Rsine table (Table 8) is extracted for every $1^\circ$ increase of arc (Joshi 1964, p.140, *Spaṣṭādhikāra*, vs. 16).

## 2.9. Nīlakaṇṭha Somayāji (1444-1545 AD)

### a) Tantrasaṅgraha: 

Citing Mādhava (1340-1425AD) Nīlakaṇṭha gives the following methods on computation of Rsines, versed Rsines and Rsine differences (Sarma 1977, verses ii. 2-21).
I) Step 1: First Rsine difference is $\Delta J_0 = J_1 - J_0 = J_1$.
Step 2: For $i = 1, 2, \dots, l - 1$; ($l = 24$) compute $\Delta J_i = \Delta J_{i-1} - \frac{J_i}{233 \frac{1}{2}}$ and $J_{i+1} = J_i + \Delta J_i$ or,
Table 8: *Siddhāntaśiromaṇi* - Marīci refined tabular values

| $ih$ | $1^\circ$ | $2^\circ$ | $3^\circ$ | $4^\circ$ | $5^\circ$ | $6^\circ$ | $7^\circ$ | $8^\circ$ | $9^\circ$ | $10^\circ$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $J_i$ | 2;5;40 | 4;11;16 | 6;17;10 | 8;22;14 | 10;27;30 | 12;33;36 | 14;37;2 | 16;42;2 | 18;46;20 | 20;50;36 |
| $ih$ | $11^\circ$ | $12^\circ$ | $13^\circ$ | $14^\circ$ | $15^\circ$ | $16^\circ$ | $17^\circ$ | $18^\circ$ | $19^\circ$ | $20^\circ$ |
| $J_i$ | 22;53;50 | 24;56;56 | 26;59;38 | 29;1;50 | 31;3;30 | 33;4;56 | 35;6;5;4 | 37;4;56 | 39;04;06 | 41;02;32 |
| $ih$ | $21^\circ$ | $22^\circ$ | $23^\circ$ | $24^\circ$ | $25^\circ$ | $26^\circ$ | $27^\circ$ | $28^\circ$ | $29^\circ$ | $30^\circ$ |
| $J_i$ | 43;0;16 | 44;57;12 | 46;53;18 | 48;48;30 | 50;42;52 | 52;36;16 | 54;30;40 | 56;20;16 | 58;10;20 | 60;00;00 |
| $ih$ | $31^\circ$ | $32^\circ$ | $33^\circ$ | $34^\circ$ | $35^\circ$ | $36^\circ$ | $37^\circ$ | $38^\circ$ | $39^\circ$ | $40^\circ$ |
| $J_i$ | 61;48;16 | 63;25;24 | 65;21;24 | 67;06;12 | 68;49;24 | 70;32;02 | 72;13;44 | 73;52;46 | 75;31;06 | 77;08;04 |
| $ih$ | $41^\circ$ | $42^\circ$ | $43^\circ$ | $44^\circ$ | $45^\circ$ | $46^\circ$ | $47^\circ$ | $48^\circ$ | $49^\circ$ | $50^\circ$ |
| $J_i$ | 79;23;30 | 80;17;44 | 81;50;22 | 82;20;32 | 84;50;50 | 86;19;34 | 87;45;44 | 89;10;38 | 90;33;54 | 91;55;30 |
| $ih$ | $51^\circ$ | $52^\circ$ | $53^\circ$ | $54^\circ$ | $55^\circ$ | $56^\circ$ | $57^\circ$ | $58^\circ$ | $59^\circ$ | $60^\circ$ |
| $J_i$ | 93;15;26 | 94;33;40 | 95;50;10 | 97;04;54 | 98;17;52 | 99;29;04 | 100;38;26 | 101;46;56 | 102;51;36 | 103;55;23 |
| $ih$ | $61^\circ$ | $62^\circ$ | $63^\circ$ | $64^\circ$ | $65^\circ$ | $66^\circ$ | $67^\circ$ | $68^\circ$ | $69^\circ$ | $70^\circ$ |
| $J_i$ | 104;57;16 | 105;57;14 | 106;55;10 | 107;51;20 | 108;45;26 | 109;37;32 | 110;27;38 | 111;14;26 | 112;01;46 | 112;45;48 |
| $ih$ | $71^\circ$ | $72^\circ$ | $73^\circ$ | $74^\circ$ | $75^\circ$ | $76^\circ$ | $77^\circ$ | $78^\circ$ | $79^\circ$ | $80^\circ$ |
| $J_i$ | 113;27;44 | 114;05;36 | 114;45;26 | 115;21;06 | 115;14;40 | 116;26;08 | 116;55;28 | 117;22;40 | 117;47;42 | 118;10;38 |
| $ih$ | $81^\circ$ | $82^\circ$ | $83^\circ$ | $84^\circ$ | $85^\circ$ | $86^\circ$ | $87^\circ$ | $88^\circ$ | $89^\circ$ | $90^\circ$ |
| $J_i$ | 118;31;22 | 118;49;56 | 119;06;22 | 119;20;34 | 119;32;18 | 119;42;28 | 119;50;08 | 119;55;36 | 119;58;54 | 120;00;00 |

152 INDIAN JOURNAL OF HISTORY OF SCIENCE
compute $J_{i+1} = J_i + J_1 - \left\{ \frac{J_1 + J_2 + J_3 + ... + J_i}{233 \frac{1}{2}} \right\};$
$\Delta J_i = J_1 - \left\{ \frac{J_1 + J_2 + J_3 + ... + J_i}{233 \frac{1}{2}} \right\}$
II) Step 1: With $d = \frac{21600 \times 113}{355}, R = \frac{d}{2}$ and $J_l = R$ find $J_{l-1} = \sqrt{R^2 - J_l^2}$ and $M = 2 (R - J_{l-1})$
Step 2: Compute $\Delta J_{i-1} - \Delta J_i = \left( \frac{M}{R} \right) J_i$ and $J_{i+1} = \Delta J_{i-1} + \left( 1 - \frac{M}{R} \right) J_i$ or in other terms $J_{i+1} = 2J_i - \left( \frac{M}{R} \right) J_i - J_{i-1}$ or $J_{i+1} = \left( \frac{2J_{l-1} \times J_i}{R} \right) - J_{i-1}$ for $i = 1, 2, \dots, l - 1$ ($l = 24$).

### b) Golasāra:

In this (Sarma 1970, pp. 17-19, verse iii. 6-14) Nīlakaṇṭha gives a method to construct accurate tabular Rsines and versed Rsines (Mallayya, 2004) starting from an arc of angular measure $\theta = 30^\circ$. Denoting $S_i = R \sin \left( \frac{\theta}{2^i} \right)$, $v_i = R \text{ versin} \left( \frac{\theta}{2^i} \right)$, $k_i = R \cos \left( \frac{\theta}{2^i} \right)$, $i = 0, 1, 2, \dots, m$ ($m = 0, 1, 2, \dots$ for $l = 3 \times 2^m$ tabular values) then Nīlakaṇṭha’s procedure is:
Step 1: Starting from $S_0 = \frac{R}{2} (= R \sin 30^\circ)$ determine $S_i$ for $i = 1, 2, 3 \dots m$ using the geometric method based on the formula $S_i = \frac{1}{2} \sqrt{S_{i-1}^2 + v_{i-1}^2}$ where $v_{i-1} = R - k_{i-1}$ and $k_{i-1} = \sqrt{R^2 - S_{i-1}^2}$.
Step 2: Take $R = \frac{21600 \times 113}{2 \times 355}$ and with $J_1 = R \sinh = S_m, J_l = R \sinh = R$ as first and last Rsines, find $J_{l-1} = \sqrt{R^2 - J_l^2}, K_{l-1} = \sqrt{R^2 - J_{l-1}^2}$ and $V_{l-1} = R - K_{l-1}$.
Step 3: Using $J_l$ and $J_{l-1}$ compute $\Delta J_{l-1} = J_l - J_{l-1}$ and $\lambda = 2 \left( \frac{\Delta J_{l-1}}{R} \right)$.
Step 4: Compute $\Delta J_{l-i} = \lambda \times J_{l-(i-1)} + \Delta J_{l-(i-1)}$, $J_{l-i} = J_{l-(i-1)} - \Delta J_{l-i}, K_{l-i} = \sqrt{R^2 - J_{l-i}^2}$ and $V_{l-i} = R - K_{l-i}$, for $i = 2, 3, 4, \dots, l - 2$.
Step 1 generates the first tabular Rsine for construction of tables of lengths $l$. It also provides all tabular values directly (same as Āryabhaṭa I’s geometrical scheme). Tabular Rsines shown in Table 9.

## 2.10. Jyeṣṭhadeva (1500-1608 AD)

The *Yuktibhāṣā* (Ramavarma 1948, ch. vii.) gives several methods for determination of tabular Rsine differences, Rsines, Rversines, and Rcosines.
I) One method is the geometrical method of Āryabhaṭa I using which $J_1, J_2, J_4, J_5, J_7, J_{10}, J_{11}, J_{13}, J_{14}, J_{16}, J_{17}, J_{19}, J_{20}, J_{22}, J_{23}$ are derived starting from $J_8 = \frac{R}{2}$ and the remaining $J_3, J_6, J_9, J_{12}, J_{15}, J_{18}, J_{21}$ are derived starting from $J_{24} = R$.
II) Another method is by adding the tabular differences. With $\Delta J_0 = J_1$, compute $J_i = \Delta J_0 + \Delta J_1 + \Delta J_2 + \dots + \Delta J_{i-1}; V_i = \Delta J_{l-1} + \Delta J_{l-2} + \dots + \Delta J_{l-i}$ and $K_i = R - V_i$; for $i = 1, 2, 3, \dots, l$ ($l = 24$). Āryabhaṭa’s tabular differences are to be used for the computation.
TRIGONOMETRIC TABLES IN INDIA 153
Table 9: Tabular Rsines using Golasāra method

| $i$ | arc | Rsines $J_i$ | Modern Rsine $\sin \theta \times (10800/\pi)$ | $i$ | arc | Rsines $J_i$ | Modern Rsine $\sin \theta \times (10800/\pi)$ |
|---|---|---|---|---|---|---|---|
| 1 | $225'$ | $224' 50'' 21.76'''$ | $224' 50'' 21.83'''$ | 13 | $2925'$ | $2584' 38'' 04.59'''$ | $2584' 38'' 05.53'''$ |
| 2 | $450'$ | $448' 42'' 57.27'''$ | $448' 42'' 57.58'''$ | 14 | $3150'$ | $2727' 20'' 51.44'''$ | $2727' 20'' 52.38'''$ |
| 3 | $675'$ | $670' 40'' 15.66'''$ | $670' 40'' 16.04'''$ | 15 | $3375'$ | $2858' 22'' 54.16'''$ | $2858' 22'' 55.11'''$ |
| 4 | $900'$ | $889' 45'' 15.15'''$ | $889' 45'' 15.61'''$ | 16 | $3600'$ | $2977' 10'' 32.77'''$ | $2977' 10'' 33.73'''$ |
| 5 | $1125'$ | $1105' 01'' 38.42'''$ | $1105' 01'' 38.94'''$ | 17 | $3825'$ | $3083' 13'' 15.97'''$ | $3083' 13'' 16.94'''$ |
| 6 | $1350'$ | $1315' 34'' 06.85'''$ | $1315' 34'' 07.44'''$ | 18 | $4050'$ | $3176' 03'' 48.99'''$ | $3176' 03'' 49.97'''$ |
| 7 | $1575'$ | $1520' 28'' 34.79'''$ | $1520' 28'' 35.46'''$ | 19 | $4275'$ | $3255' 18'' 20.59'''$ | $3255' 18'' 21.58'''$ |
| 8 | $1800'$ | $1718' 52'' 23.45'''$ | $1718' 52'' 24.19'''$ | 20 | $4500'$ | $3320' 36'' 29.20'''$ | $3320' 36'' 30.20'''$ |
| 9 | $2025'$ | $1909' 54'' 34.41'''$ | $1909' 54'' 35.19'''$ | 21 | $4725'$ | $3371' 41'' 28.13'''$ | $3371' 41'' 29.15'''$ |
| 10 | $2250'$ | $2092' 46'' 02.66'''$ | $2092' 46'' 03.49'''$ | 22 | $4950'$ | $3408' 20'' 9.90'''$ | $3408' 20'' 10.93'''$ |
| 11 | $2475'$ | $2266' 39'' 49.34'''$ | $2266' 39'' 50.21'''$ | 23 | $5175'$ | $3430' 23'' 09.60'''$ | $3430' 23'' 10.65'''$ |
| 12 | $2700'$ | $2430' 51'' 13.69'''$ | $2430' 51'' 14.60'''$ | 24 | $5400'$ | $3437' 44'' 47.32'''$ | $3437' 44'' 48.37'''$ |

III) The method based on ‘jīve paraspara nyāya’ is as follows:
Step 1: $J_1$ is the first Rsine, $K_0 = R$, and $K_1 = \sqrt{R^2 - J_1^2}$ the first Rcosine.
Step 2: Compute $J_i = \frac{J_{i-1} \times K_1 + K_{i-1} \times J_1}{R}$ and $K_i = \sqrt{R^2 - J_i^2}$; for $i = 2, 3, 4 \dots, l; (l = 24)$.
IV) Another method for computing the tabular values without using the value of $R$ is:
Step 1: $J_1, J_2$ are known (or $J_2$ can be derived without using $R$ from $J_2 = J_1 + \Delta J_1$).
Step 2: Compute $J_{i+1} = \frac{J_i^2 - J_1^2}{J_{i-1}}$ for $i = 2, 3, \dots, l - 1$.
V) The following method is to determine tabular values with desired degree of accuracy.
Step 1: $J_0 = 0, V_0 = 0, K_0 = R$.
Step 2: Compute $J_i = J_{i-1} + \left( \frac{h}{R} \right) K_{i-\frac{1}{2}}$; $V_i = V_{i-1} + \left( \frac{h}{R} \right) J_{i-\frac{1}{2}}$; and $K_i = K_{i-1} - \left( \frac{h}{R} \right) J_{i-\frac{1}{2}}$ for $i = 1, 1\frac{1}{2}, 2, 2\frac{1}{2}, \dots, l - \frac{1}{2}, l$.
This gives $2l$ tabular values are at arc bits of $\frac{h}{2}$, of which $l$ tabular values at arc bits of $h'$. For $l = 24$, we get 48 values for every increase of $112 \frac{1}{2}'$.

## 2.11. Mādhava’s Power Series Method for Rsines, Rversines and Rcosines

Mādhava prescribes the following procedure using power series coefficients. Nīlakaṇṭha in his *Āryabhaṭīyabhāṣya* (Sambasiva Sastry 1930, I. p.113) as well as Śaṅkara in the *Yuktidīpikā* (Sarma 1977, p.117) cites Mādhava’s enunciation for computation of desired Rsines and versed Rsines. According to this enunciation, if $s$ is any arc (preferably small for greater accuracy, and for computation of tabular values take $s = jh$ for $j = 1, 2, \dots, l$), then $\text{jīvā}(s)$

$$= s - \frac{s^3}{c_q^2} \left[ M_1 - \frac{s^2}{c_q^2} \left\{ M_2 - \frac{s^2}{c_q^2} \left( M_3 - \frac{s^2}{c_q^2} [ M_4 - \frac{s^2}{c_q^2} M_5 ] \right) \right\} \right]$$

where $c_q$ is the quadrantal arc of measure $5400'$, and $M_k$ denote the Mādhava numbers in minutes (*kalā*), seconds (*vikalā*) and sub seconds (*tatpara*) written in descending order. 24 main Rsines
154 INDIAN JOURNAL OF HISTORY OF SCIENCE
obtained are listed in a set of verses attributed to Mādhava (Sambasiva Sastry 1930, I. p.55; Ramavarma 1948, p.198; Nayar 1956, p.191). Mādhava’s procedure is given below in two stages.
Stage I (To compute the decreasing sequence of Mādhava numbers $M_k$)
Step 1: With $R = \frac{12375888}{60 \times 60}$, and quadrantal arc $c_q = 5400'$ compute $\lambda^2 = \frac{c_q^2}{R^2}$
Step 2: Taking $M_0 = c_q$, compute the Mādhava numbers $M_k$ successively using

$$M_k = M_{k-1} \left[ \frac{\lambda^2}{(2k)^2 + (2k)} \right],$$

or using $M_k = M_{k-1} \left[ \frac{c_q^2}{[(2k)^2 + (2k)] R^2} \right]$ for $k = 1, 2, 3, \dots, m$.
Table 10: Tabular values by power series method with Mādhava’s values and modern values

| $j$ | Arc $jh$ | Mādhava’s Rsines | Computed Rsines | Modern Rsines $\sin \theta \times (10800/\pi)$ | Rversnes | Rcosines |
|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 0 | 0 | 3437; 44; 48 |
| 1 | 225 | 224; 50; 22 | 224; 50; 22 | 224; 50; 21.83 | 7; 21; 38 | 3430; 23; 10 |
| 2 | 450 | 448; 42; 58 | 448; 42; 58 | 448; 42; 57.58 | 29; 24; 37 | 3408; 20; 11 |
| 3 | 675 | 670; 40; 16 | 670; 40; 16 | 670; 40; 16.04 | 66; 03; 19 | 3371; 41; 29 |
| 4 | 900 | 889; 45; 15 | 889; 45; 15.6 | 889; 45; 15.61 | 117; 8; 18 | 3320; 36; 30 |
| 5 | 1125 | 1105; 01; 39 | 1105; 01; 39 | 1105; 01; 38.94 | 182; 26; 27 | 3255; 18; 21 |
| 6 | 1350 | 1315; 34; 07 | 1315; 34; 07 | 1315; 34; 07.44 | 261; 40; 58 | 3176; 3; 50 |
| 7 | 1575 | 1520; 28; 35 | 1520; 28; 35 | 1520; 28; 35.46 | 354; 31; 31 | 3083; 13; 17 |
| 8 | 1800 | 1718; 52; 24 | 1718; 52; 24 | 1718; 52; 24.19 | 460; 34; 15 | 2977; 10; 33 |
| 9 | 2025 | 1909; 54; 35 | 1909; 54; 35 | 1909; 54; 35.19 | 579; 21; 53 | 2858; 22; 55 |
| 10 | 2250 | 2092; 46; 03 | 2092; 46; 03 | 2092; 46; 03.49 | 710; 23; 56 | 2727; 20; 52 |
| 11 | 2475 | 2266; 39; 50 | 2266; 39; 50 | 2266; 39; 50.21 | 853; 6; 43 | 2584; 38; 5 |
| 12 | 2700 | 2430; 51; 15 | 2430; 51; 15 | 2430; 51; 14.60 | 1006; 53; 34 | 2430; 51; 14 |
| 13 | 2925 | 2584; 38; 06 | 2584; 38; 06 | 2584; 38; 05.53 | 1171; 4; 58 | 2266; 39; 50 |
| 14 | 3150 | 2727; 20; 52 | 2727; 20; 52 | 2727; 20; 52.38 | 1344; 58; 45 | 2092; 46; 3 |
| 15 | 3375 | 2858; 22; 55 | 2858; 22; 55 | 2858; 22; 55.11 | 1527; 50; 13 | 1909; 54; 35 |
| 16 | 3600 | 2977; 10; 34 | 2977; 10; 34 | 2977; 10; 33.73 | 1718; 52; 24 | 1718; 52; 24 |
| 17 | 3825 | 3083; 13; 17 | 3083; 13; 17 | 3083; 13; 16.94 | 1917; 16; 13 | 1520; 28; 35 |
| 18 | 4050 | 3176; 03; 50 | 3176; 03; 50 | 3176; 03; 49.97 | 2122; 10; 41 | 1315; 34; 7 |
| 19 | 4275 | 3255; 18; 22 | 3255; 18; 22 | 3255; 18; 21.58 | 2332; 43; 9 | 1105; 1; 39 |
| 20 | 4500 | 3320; 36; 30 | 3320; 36; 30 | 3320; 36; 30.20 | 2547; 59; 33 | 889; 45; 15 |
| 21 | 4725 | 3371; 41; 29 | 3371; 41; 29 | 3371; 41; 29.15 | 2767; 4; 32 | 670; 40; 16 |
| 22 | 4950 | 3408; 20; 11 | 3408; 20; 11 | 3408; 20; 10.93 | 2989; 1; 51 | 448; 42; 57 |
| 23 | 5175 | 3430; 23; 11 | 3430; 23; 10.2 | 3430; 23; 10.65 | 3212; 54; 26 | 224; 50; 22 |
| 24 | 5400 | 3437; 44; 48 | 3437; 44; 48 | 3437; 44; 48.37 | 3437; 44; 48 | 0; 0; 0 |

TRIGONOMETRIC TABLES IN INDIA 155
Stage II (To compute Rsines): For each arc $s = jh$ (where $j = 2, 3, 4, \dots, l$),
Step 1: Compute $\rho = \frac{s}{c_q}, \rho^2$ and $\rho^3$
Step 2: Taking the last Mādhava number $M_m$ as $d_m$ compute successively the product $p_{m-i} = \rho^2 d_{m-(i-1)}$ and the difference $d_{m-i} = M_{m-i} - p_{m-i}$ for $i = 1, 2, 3, \dots, m - 1$.
Step 3: Compute the final product $p_0 = \rho^3 d_1$ and final difference $d_0 = s - p_0$. Then $J = d_0$
Mādhava numbers (Sambasiva Sastry 1930, I. p.113: Sarma 1977, p.117) are 2220, 39, 40 ; 273, 57, 47; 16, 05, 41; 0, 33, 06 ; 0, 0, 44 and Mādhava’s tabular Rsines (Sambasiva Sastry 1930, p.55; Ramavarma 1948, p.198; Nayar 1956, p.191) are 224,50,22; 448,42,58; 670,40,16; 889,45,15; 1105,1,39; 1315,34,7; 1520,28,35; 1718,52,24; 1909,54,35; 2092,46,3; 2266,39,50; 2430,51,15; 2584,38,6; 2727,20,52; 2858,22,55; 2977,10,34; 3083,13,17; 3176,3,50; 3255,18,22; 3320,36,30; 3371, 41, 29; 3408,20,11; 3430,23,11; 3437, 44, 48.
Similarly for computation of versed Rsines and Rcosines if $s = jh$ are the arcs then *śara*($s$)

$$= \frac{s^2}{c_q} \left[ M'_1 - \frac{s^2}{c_q^2} \left\{ M'_2 - \frac{s^2}{c_q^2} \left( M'_3 - \frac{s^2}{c_q^2} \left[ M'_4 - \frac{s^2}{c_q^2} \left( M'_5 - \frac{s^2}{c_q^2} M'_6 \right) \right] \right) \right\} \right]$$

where $c_q = 5400'$ and $M'_k$ are the Mādhava numbers for Rversines (in *kalās*, *vikalās*, and *tatparas*) placed one below the other. $M'_k$ are 4241,9,0; 872,3,5; 71,43,24; 3,9,37; 0,5,12; 0,0,6 (Sarma 1977, p.118, vs 438; Ramavarma 1948, p.188, 195; Nayar, 1956, p.192, vs vi.15). Table 10 shows 24 tabular values from power series method along with Mādhava’s values and modern values.

# 3. CONCLUDING REMARKS

The above presentation just peeps into some trigonometric tables and their construction methods from a very few select treatises such as *Āryabhaṭīya* of Āryabhaṭa I and *bhāṣya* of Nīlakaṇṭha Somayāji, *Sūryasiddhānta*, *Pañcasidhāntikā* of Varāha Mihira, *Khaṇḍakhādyaka* and *Brahmasphuṭasiddhānta* of Brahmagupta, *Mahābhāskarīya bhāṣya* of Govindasvāmin, *Vaṭeśvara Siddhānta* of Vaṭeśvara, *Mahāsiddhānta* of Āryabhaṭa II, *Siddhāntaśiromaṇi* of Bhāskarchārya and *Marīci* of Munīśvara, *Tantrasaṅgraha* and *Golasāra* of Nīlakaṇṭha Somayāji, *Yuktibhāṣā* of Jyeṣṭhadeva and *Karaṇapaddhati* of Putumana Somayāji. The concept and method of extraction of a second generation refined table with shorter interval of differencing from a known coarser table deserves special attention. From the vast store of manuscripts on trigonometric tables only a small percentage has been edited and explored so far and several original manuscripts are still lying in various repositories (Sarma KV, 2002). Development of trigonometric tables in India can be fully traced by carrying out explorative studies on the contents of the large mass of such manuscripts also.

# BIBLIOGRAPHY

Agathe Keller, *Expounding the Mathematical Seed*, Vol I, Birkhauser Verlag, (2006).
Bag A. K, “Sine Tables in Ancient India”, *IJHS*, INSA, N. Delhi, (1969), 4.1-2 79-85.
Edward C Sachau, *Alberūni’s India*, I, Rupa.Co, New Delhi, 2009.
Joshi Kedar Datta (Ed.), *Siddhāntaśiromaṇi* of Bhāskarāchārya, *Golādhyāya*, with own commentary *Vāsanābhāṣya* and the Commentary *Marīci* of Munīśvara, Motilal Banarsidass, Delhi, 1988.
Joshi Kedar Datta (Ed.), *Siddhāntaśiromaṇi* of Bhāskarāchārya, Part II, Banaras Hindu University, Varanasi, 1964.
Kuppanna Sastri T.S (Ed.), *Mahābhāskarīya* of Bhāskarāchārya with the *bhāṣya* of Govindasvāmin and the super commentary *Siddhāntadīpikā* of Parameśvara, Govt Oriental Mss Library, Madras, 1957.
156 INDIAN JOURNAL OF HISTORY OF SCIENCE
a) Mallayya Madhukar V, “Interpolation of Sines by Successive Approximation Method”, *IJHS*, INSA, N. Delhi, 43.4 (2008) 553-568.
b) Mallayya Madhukar V, “Vaṭeśvara’s Trigonometric Tables and the Method", *Gaṇita Bhāratī*, Bulletin of Indian Society for History of Mathematics, Delhi, 30(1) (2008) 61-79.
Mallayya Madhukar V, “An Interesting Algorithm for Computation of Sine Tables from the Golasāra of Nīlakaṇṭha”,*Gaṇita Bhāratī*, Bulletin of ISHM, Delhi, 26 (2004) 40-55.
Nayar S.K (Ed.), *Karaṇapaddhati* of Putumana Somayāji, Govt Oriental Mss Library, Madras, 1956.
Phanindralal Gangooly (Ed.), *The Sūryasiddhānta*, A Text Book of Hindu Astronomy, Translated with Notes and Appendix by E. Burgess, Motilal Banarsidass, Delhi, 2000.
Ramavarma Maru Thampuran and Akhileshvara Aiyer (Ed.), *Yuktibhāṣā* of Jyeṣṭhadeva, Mangalodayam, Trichur, 1948.
Sambasiva Sastry K (Ed.), *Āryabhaṭīya* of Āryabhaṭa, Edited with *bhāṣya* of Nīlakaṇṭha, Part I, Trivandrum Sanskrit Series No.101, Trivandrum, 1930.
Sarma K. V (Ed.), *Tantrasaṅgraha* of Nīlakaṇṭha Somayāji, Critically Edited with *Yuktidīpikā* and *Laghuvivṛti* of Śaṅkara, VVBI, Hoshiarpur, 1977.
Sarma K.V (Ed.), *Golasāra* of Nīlakaṇṭha Somayāji, Vishveshvaranand Institute, Hoshiarpur, 1970.
Sengupta P. C, *Khaṇḍakhādyaka* of Brahmagupta (Translated into English), University of Calcutta, 1934.
Sharma Rama Swarup (Ed.), *Brahmasphuṭasiddhānta* of Brahmagupta, Edited with *Vāsanā*, *Vijñāna*, and Hindi Commentaries, Vol. II; IV, IIASR, Delhi,1996.
Shukla K. S (Ed.), *Vaṭeśvara Siddhānta and Gola*, Critically Edited with English Translation and Commentary, INSA, New Delhi, Part I 1986.
Shukla K.S (Revised), Datta Bibhutibhushan and Singh A.N, “Hindu Trigonometry”, *IJHS*, INSA, New Delhi, (1983), 18.1, p.74.
Shukla K.S in collaboration with Sarma K.V (Ed.), *Āryabhaṭīya* by Āryabhaṭa, Critically edited with Introduction, English Translation, Notes, Comments and Indexes, INSA, N. Delhi, 1976.
Sudhakar Dvivedi (Ed.) *Pañcasidhāntikā* of Varāha Mihira, Text with an Original commentary in Sanskrit and an English Translation and Introduction by Thibaut G, Chowkhamba, Varanasi, 1997.
Sudhakara Dvivedi (Ed.) *Mahāsiddhānta* of Āryabhaṭa, Edited with his own commentary, Choukhamba, Delhi, 1995.
Sarma K.V, *Science Texts in Sanskrit in the Manuscripts Repositories of Kerala and Tamilnadu*, Rashtriya Sanskrit Sansthan, Delhi, 2002.
