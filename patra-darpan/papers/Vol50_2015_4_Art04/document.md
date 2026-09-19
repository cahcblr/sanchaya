# Nilakanthas Value of R-Sine for the Arc of Twenty-four Degrees

- Author Display: Takao Hayashi
- Year: 2015
- Journal Label: IJHS-50-2015-Issue-4
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol50_2015_4_Art04.pdf

<!-- source: gemini page-chunk extraction -->

Indian Journal of History of Science, 50.4 (2015) 602-615 DOI: 10.16943/ijhs/2015/v50i4/48363

# Nīlakaṇṭha’s Value of R-Sine for the Arc of Twenty-four Degrees

**Takao Hayashi***
(Received 20 June 2015; revised 10 August 2015)

### Abstract

In an algorithm in astronomy, Nīlakaṇṭha uses the integral constant 8452 as a divisor in place of $R^2 / R \sin 24^\circ$ without specifying the values of $R$ and $R \sin 24^\circ$ he employed. In this paper I propose to determine their probable values.
**Key words:** Interpolation, Mādhava, Power series, Sine table

## 1. DEFINITIONS

For an arc $x$ measured in *kalā* (minute) in a quarter circle with radius $R$, let $J(x)$ be half of the chord (*jyā*) subtending the arc $2x$, and let $J'(x) = J(90 \cdot 60 - x)$. Let a unit arc be $\alpha = (90 \cdot 60)/n$ for an optionally chosen integer $n$, and $J_i = J(\alpha_i)$, where $\alpha_i = i \cdot \alpha$ ($i = 1, 2, \dots, n$); $J_i$ are the tabulated values of the $n$ R-sines for a circle with radius $R$. Finally, let the sine differences be $K_i = J_i - J_{i-1}$ ($J_0 = 0$).

## 2. PROBLEM

Nīlakaṇṭha prescribes an algorithm for calculating the *dṛkkṣepa* (zenith distance of the nonagesimal) in two verses of his two works, *Tantrasaṃgraha* and *Candracchāyāgaṇita* [TS 3.104cd-106ab = CC 9-10]; in the algorithm he uses the integral number 8452 as a divisor (cf. [Ramasubramanian et al. (2011), pp.242-45). He cites the same verses in his commentary on the fourth chapter of the *Āryabhaṭīya* [NAB4, p.118, line 23 to p.119, line 2] and explains how to derive the algorithm, mentioning that the integer 8452 has been obtained by reducing a multiplier $J(1440)$, where $1440'$ or $24^\circ$ is the sun’s maximum declination, and a divisor $R^2$ that occur in the process of derivation to a single number by means of a ‘shortcut’ (*laghu-tantra*). In his commentary on the second chapter of the *Āryabhaṭīya* [NAB2, p.53, lines 19-22] Nīlakaṇṭha cites the ‘shortcut’ given in two verses from Govinda-svāmin’s commentary on the *Mahābhāskarīya* [GMB 1.23, p.33], which teaches that the calculation, $\frac{a \times b}{c}$, can be replaced by another, $\frac{a \times b'}{c'}$, where $c' = \frac{c \times b'}{b}$ when $b'$ is an optionally determined number (*mati*) or $b' = \frac{b \times c'}{c}$ when $c'$ is optionally determined. This calculation, either for $c'$ or for $b'$, is carried out in the form of *trairāśika* (so-called rule of three). In the former case, for example, the verbal formulation (*vācoyukti*) of the *trairāśika* is: ‘If $c$ is obtained from $b$, then what is obtained from $b'$?’, which may be expressed in modern notation as $b : c = b' : x$, and the result is $c'$. In the present case, after formulating the *trairāśika* with $b' = 1$, Nīlakaṇṭha says that the result is 8452. Expressed in modern notation,

$$J(1440) : R^2 = 1 : x \to x = \frac{R^2}{J(1440)} = 8452$$

***
*Professor Emeritus, Doshisha University, Kyoto, Japan. Email: ganaka@kyoto.zaq.ne.jp
---
NĪLAKAṆṬHA’S VALUE OF R-SINE FOR THE ARC OF TWENTY-FOUR DEGREES 603
He, however, does not refer to the values of $R$ and $J(1440)$ he used here.
Bhāskara II assigns 1397 for $R \sin 24^\circ$ in his *Golādhyāya* [GA, *spaṣṭādhikāra* 12c]. This value, 1397, can be obtained from his $J_i$ [GG 2.3-4], which except $J_{16} = 2977$ are exactly the same as Āryabhaṭa’s, by means of linear interpolation (see §4a below). However, from this value with Āryabhaṭa’s $R = 3438$, we obtain $R^2/J(1440) = 8460; 52, 23, \dots$, which is greater than 8452 by nearly 9 *kalās*. We, therefore, have to seek for other pair of values for Nīlakaṇṭha’s $R$ and $J(1440)$.
Nīlakaṇṭha himself prescribes two recursion methods for constructing tables of $J_i$ ([TS 2.3cd-10ab]; see Appendix A) and one method for interpolation [TS 2.17-20]. It may, therefore, be natural to assume that he himself obtained $J(1440)$ by using his own $J_i$ tables with the interpolation. But the Kerala tables of $J_i$, including Nīlakaṇṭha’s, are variations of Āryabhaṭa’s table in the sense that they use $R = 3438$ or revised ones and $n = 24$. Moreover, as the arc of 1440 *kalās* has a special significance in Indian astronomy, there is also the possibility that the value of $J(1440)$ used by Nīlakaṇṭha had already been obtained by his predecessors. Hence, it is worthwhile to see if 8452 can be obtained by means of an appropriate interpolation from other tables with $R = 3438$ or with similar values. I shall examine which combination of $J_i$ tables and methods of interpolation can produce the number 8452.
The $J_i$ tables used here for calculation are:
a. Āryabhaṭa’s table reconstructed from his table of $K_i$ [AB 1.12 (1.10 in earlier editions); see Hayashi (1997), p.402, Table 1]. This table has been adopted in the *Sūryasiddhānta*, one of the most influential astronomical works, and by Bhāskara II, one of the most influential astronomers.
b. Āryabhaṭa’s reconstructed table with minor corrections [$J_i^*$ in Hayashi (1997), p.402, Table 1].
c. Āryabhaṭa’s table corrected by Govindasvāmin [GMB 4.22, p.200; cf. Gupta (1971), pp.53-54 and Table 1; cf. also Mallayya (2014), p.148, Table 4].
d. Mādhava’s table cited by Nīlakaṇṭha and by Śaṅkara [see Appendix B].
e. Nīlakaṇṭha’s table reconstructed from his first recursion method [TS 2.3cd-6ab; see Appendix A1].
f. Nīlakaṇṭha’s table reconstructed from his second recursion method [TS 2.6cd-10ab; see Appendix A2].
The methods of interpolation examined here are:
1. Linear interpolation.
2. Nīlakaṇṭha’s interpolation which utilizes the sum and difference formulas for $J(x)$ and $J'(x)$ [TS 2.17-20].
3. Mādhava’s second order interpolation (cited in [TS 2.10cd-13] and in [NAB2, p.55, lines 1-7]).
4. Brahmagupta’s second order interpolation [BSS 25.17 = KhKh II, 1.4; adopted in GG 2.16].
5. Govindasvāmin’s second order interpolation [GMB 4.22, pp.201-02; cf. Gupta (1969), pp.91-92].
Besides these interpolations, I shall examine the two formulas that directly produce $J(x)$ for any arc $x$, namely,
6. Bhāskara I’s rational approximation formula, and
7. Mādhava’s power series expansion.
The former [MB 7.17-18], or one of its equivalents, has been adopted by other
---
604 INDIAN JOURNAL OF HISTORY OF SCIENCE
astronomers beginning with Brahmagupta [BSS 14.23-24]. The latter has been cited by Śaṅkara Vāriyar [YD 2.440-41 $\approx$ 2.451-52; KK on L 199, p.390]. As A. K. Bag points out [Bag (1976), pp.54-56; cf. Ramasubramanian et al. (2011), p.63], Mādhava’s table of $J_i$ with the two sexagesimal places, *vikalā* and *tatparā*, can be obtained by means of this power series (see Appendix B).
Finally, I shall also examine the value of $J(1440)$ given by Vaṭeśvara, a follower of Āryabhaṭa, who however uses a $J_i$ table with $n = 96$ instead of $n = 24$.
For the dates of the astronomers and of their works consult general works on the history of mathematics and astronomy in India.

## 3. REQUIREMENTS

The nearest integer to $R^2/J(1440)$ is 8452 when and only when the quotient of the division of $R^2$ by $J(1440)$ lies between 8451;30 and 8452;30, that is,

$$8451;30 \le \frac{R^2}{J(1440)} < 8452;30,$$

which can be rewritten as

$$\frac{R^2}{8452;30} < J(1440) \le \frac{R^2}{8451;30}.$$

**3a and 3b.** Since $R = 3438$, we have $R^2 = 11819844$ and
$R^2/8452;30 = 1398; 23, 3, 46, \dots$
$R^2/8451;30 = 1398; 32, 59, 26, \dots$
Hence follows the requirement:
$1398; 23, 3, 46, \dots < J(1440) \le 1398; 32, 59, 26, \dots$
**3c.** Since $R = 3437; 44, 19$, we have $R^2 = 11818046; 45, 29, 58, 1$ and
$R^2/8452;30 = 1398; 10, 18, 19, \dots$
$R^2/8451;30 = 1398; 20, 13, 52, \dots$
Hence follows the requirement:
$1398; 10, 18, 19, \dots < J(1440) \le 1398; 20, 13, 52, \dots$
**3d.** Since $R = 3437; 44, 48$, we have $R^2 = 11818102; 8, 39, 2, 24$ and
$R^2/8452;30 = 1398; 10, 41, 54, \dots$
$R^2/8451;30 = 1398; 20, 37, 28, \dots$
Hence follows the requirement:
$1398; 10, 41, 54, \dots < J(1440) \le 1398; 20, 37, 28, \dots$
**3e.** Since $R = 3437; 28$, we have $R^2 = 11816177; 5; 4$ and
$R^2/8452;30 = 1397; 57, 2, 0, \dots$
$R^2/8451;30 = 1398; 6, 57, 28, \dots$
Hence follows the requirement:
$1397; 57, 2, 0, \dots < J(1440) \le 1398; 6, 57, 28, \dots$
**3f.** Since $R = 3437; 44, 47$, we have $R^2 = 11818100; 14, 3, 32, 49$ and
$R^2/8452;30 = 1398; 10, 41, 5, \dots$
$R^2/8451;30 = 1398; 20, 36, 39, \dots$
Hence follows the requirement:
$1398; 10, 41, 5, \dots < J(1440) \le 1398; 20, 36, 39, \dots$
In each of 3a ~ 3f, the possible range for $J(1440)$ has the width of about 10 *vikalās*.

## 4. LINEAR INTERPOLATION

When $0 < \epsilon \le \alpha/2$,

$$J(\alpha_i \pm \epsilon) = J_i \pm \frac{(J_{i+1} - J_i)\epsilon}{\alpha} = J_i \pm \frac{\epsilon}{\alpha} \cdot K_{i+1}.$$

For $n = 24$ we have $\alpha = 225, 1440 = \alpha_6 + 90$, and

$$J(1440) = J_6 + \frac{2}{5} \cdot (J_7 - J_6) = J_6 + \frac{2}{5} \cdot K_7.$$

---
NĪLAKAṆṬHA’S VALUE OF R-SINE FOR THE ARC OF TWENTY-FOUR DEGREES 605
**4a.** Since $J_6 = 1315$ and $J_7 = 1520$, we have $J(1440) \approx 1397$, which does not fulfill the requirement (see 3a above).
**4b.** Since $J_6 = 1316$ and $J_7 = 1521$, we have $J(1440) \approx 1398$, which does not fulfill the requirement (3a).
**4c.** Since $J_6 = 1315; 33, 56$ and $J_7 = 1520; 28, 22$, we have $J(1440) \approx 1397; 31, 42$, which does not meet the requirement (3c).
**4d.** Since $J_6 = 1315; 34, 7$ and $J_7 = 1520; 28, 35$, we have $J(1440) \approx 1397; 31, 54$, which does not fulfill the requirement (3d).
**4e.** Since $J_6 = 1315; 32$ and $J_7 = 1520; 26$, we have $J(1440) \approx 1397; 30$, which does not fulfill the requirement (3e).
**4f.** Since $J_6 = 1315; 34, 7$ and $J_7 = 1520; 28, 35$, we have $J(1440) \approx 1397; 31, 54$, which does not fulfill the requirement (3f).

## 5. NĪLAKAṆṬHA’S INTERPOLATION

When $0 < \epsilon \le \alpha/2$,

$$J(\alpha_i + \epsilon) = \frac{J_i \cdot J'(\epsilon) \pm J'_i \cdot J(\epsilon)}{R},$$

$$J'(\alpha_i + \epsilon) = \frac{J'_i \cdot J'(\epsilon) \mp J_i \cdot J(\epsilon)}{R},$$

where

$$J(\epsilon) = \epsilon - \frac{\epsilon^3}{6R^2},$$

as $\epsilon$ is small enough, and

$$J'(\epsilon) = \sqrt{R^2 - J(\epsilon)^2}.$$

The last relationship is mentioned in TS 2.14ab.
For our case,

$$J(1440) = J(\alpha_6 + 90) = \frac{J_6 \cdot J'(90) + J'_6 \cdot J(90)}{R}$$

where

$$J(90) = \frac{540R^2 - 729000}{6R^2}, \quad J'(90) = \sqrt{R^2 - J(90)^2}.$$

**5a.** Since $R = 3438, J_6 = 1315$, and $J'_6 = J_{18} = 3177$, we have $J(90) \approx 89; 59, 23, J'(90) \approx 3436; 49, 19$, and $J(1440) \approx 1397; 42, 26$, which does not meet the requirement (3a).
**5b.** Since $R = 3438, J_6 = 1316$, and $J'_6 = J_{18} = 3176$, we have $J(90) \approx 89; 59, 23, J'(90) \approx 3436; 49, 19$, and $J(1440) \approx 1398; 40, 51$, which does not meet the requirement (3b).
**5c.** Since $R = 3437; 44, 19, J_6 = 1315; 33, 56$, and $J'_6 = J_{18} = 3176; 3, 23$, we have $J(90) \approx 89; 59, 22, 59, J'(90) \approx 3436; 33, 42, 48$, and $J(1440) \approx 1398; 15, 18$, which meets the requirement (3c): $R^2/J(1440) = 8451; 59, 48, \dots \approx 8452$.
**5d.** Since $R = 3437; 44, 48, J_6 = 1315; 34, 7$, and $J'_6 = J_{18} = 3176; 3, 50$, we have $J(90) \approx 89; 59, 22, 59, J'(90) \approx 3436; 34, 7, 7$, and $J(1440) \approx 1398; 15, 39$, which meets the requirement (3d): $R^2/J(1440) = 8452; 0; 4, \dots \approx 8452$.
**5e.** Since $R = 3437; 28, J_6 = 1315; 32$, and $J'_6 = J_{18} = 3175; 53$, we have $J(90) \approx 89; 59, 23, J'(90) \approx 3436; 17, 18$, and $J(1440) = 1398; 6, 48, 32, \dots \approx 1398; 7$, which does not meet the requirement (3e). The result of the calculation up to the second sexagesimal place, 1398;6,48, meets the requirement but the second place is not valid in this case (see Appendix A1).
**5f.** Since $R = 3437; 44, 47, J_6 = 1315; 34, 7$, and $J'_6 = J_{18} = 3176; 3, 49$, we have $J(90) = 89; 59, 22, 59, J'(90) = 3436; 34, 6, 5$, and $J(1440) \approx 1398; 15, 27$, which meets the requirement (3f): $R^2/J(1440) = 8452; 1, 11, \dots \approx 8452$.

## 6. MĀDHAVA’S SECOND ORDER INTERPOLATION

When $0 < \epsilon \le \alpha/2$, let $D = 13751/(2\epsilon)$. Then

$$J(\alpha_i \pm \epsilon) = J_i \pm \frac{2}{D} \cdot \left(J'_i \mp \frac{J_i}{D}\right)$$

$$J'(\alpha_i \pm \epsilon) = J'_i \mp \frac{2}{D} \cdot \left(J_i \pm \frac{J'_i}{D}\right).$$

---
606 INDIAN JOURNAL OF HISTORY OF SCIENCE
For our case, $\epsilon = 90, D = 13751/180$ and

$$J(1440) = J_6 + \frac{2}{D} \cdot \left(J'_6 - \frac{J_6}{D}\right).$$

The number 13751 in $D$ is the nearest integer to $4R$ with Mādhava’s $R$:

$$4R = 4 \cdot 3437; 44, 48 = 13750; 59, 12 \approx 13751.$$

It seems that the dividend and the divisor of the right-hand side of $D = 2R/\epsilon$ have been doubled so that the dividend, which will turn out to be a divisor in the above calculation, might become an integer, which would make the calculation easier.
For Govindasvāmin’s $R$ reconstructed from [GMB 4.22] also (see [Mallayya (2014), p.148, Table 4]), we have

$$4R = 4 \cdot 3437; 44, 19 = 13750; 57, 16 \approx 13751.$$

Also for Nīlakaṇṭha’s $R$ reconstructed from [TS 2.6cd-10ab] (see Appendix A2), we have

$$4R = 4 \cdot 3437; 44, 47 = 13750; 59, 8 \approx 13751.$$

But, for Nīlakaṇṭha’s another $R$ reconstructed from [TS 2.3cd-6ab] (see Appendix A1), we have

$$4R = 4 \cdot 3437; 28 = 13749; 52 \approx 13750.$$

On the other hand, for Āryabhaṭa’s $R = 3438$, we have $D = 6876/\epsilon$.
**6a.** Since $R = 3438, J_6 = 1315$, and $J'_6 = J_{18} = 3177$, we have $D = 6876/90$ and $J(1440) \approx 1397; 43, 1$, which does not fulfill the requirement (3a).
**6b.** Since $R = 3438, J_6 = 1316$, and $J'_6 = J_{18} = 3176$, we have $D = 6876/90$ and $J(1440) \approx 1398; 41, 26$, which does not fulfill the requirement (3b).
**6c.** Since $R = 3437; 44, 19, J_6 = 1315; 33, 56$, and $J'_6 = J_{18} = 3176; 3; 23$, we have $D = 13751/180$, and $J(1440) \approx 1398; 15, 49$, which meets the requirement (3c).
**6d.** Since $R = 3437; 44, 48, J_6 = 1315; 34, 7$, and $J'_6 = J_{18} = 3176; 3, 50$, we have $D = 13751/180$ and $J(1440) \approx 1398; 16, 1$, which fulfills the requirement (3d).
**6e.** Since $R = 3437; 28, J_6 = 1315; 32$, and $J'_6 = J_{18} = 3175; 53$, we have $D = 13750/180$ and $J(1440) \approx 1398; 14$, which does not fulfill the requirement (3e).
**6f.** Since $R = 3437; 44, 47, J_6 = 1315; 34, 7$, and $J'_6 = J_{18} = 3176; 3, 49$, we have $D = 13751/180$ and $J(1440) \approx 1398; 16, 0$, which fulfills the requirement (3f).

## 7. BRAHMAGUPTA’S SECOND ORDER INTERPOLATION

When $0 < \epsilon < \alpha$,

$$J(\alpha_i + \epsilon) = J_i + \frac{\epsilon}{\alpha} \cdot \frac{K_i + K_{i+1}}{2} - \left(\frac{\epsilon}{\alpha}\right)^2 \cdot \frac{K_i - K_{i+1}}{2}.$$

For our case,

$$J(1440) = J_6 + \frac{K_6 + K_7}{5} - \frac{2(K_6 - K_7)}{25}.$$

**7a.** Since $J_6 = 1315, K_6 = 210$, and $K_7 = 205$, we have $J(1440) \approx 1397; 36$, which does not fulfill the requirement (3a).
**7b.** Since $J_6 = 1316, K_6 = 211$, and $K_7 = 205$, we have $J(1440) \approx 1398; 43, 12$, which does not fulfill the requirement (3b).
**7c.** Since $J_6 = 1315; 33; 56, K_6 = 210; 32; 26$, and $K_7 = 204; 54, 26$, we have $J(1440) \approx 1398; 12, 16$, which meets the requirement (3c).
**7d.** Since $J_6 = 1315; 34, 7, K_6 = 210; 32, 29$, and $K_7 = 204; 54, 28$, we have $J(1440) \approx 1398; 12, 28$, which fulfills the requirement (3d).
**7e.** Since $J_6 = 1315; 32, K_6 = 210; 32$, and $K_7 = 204; 54$, we have $J(1440) \approx 1398; 10$, which does not fulfill the requirement (3e).

607 NĪLAKAṆṬHA’S VALUE OF R-SINE FOR THE ARC OF TWENTY-FOUR DEGREES
7f. Since $J_6 = 1315; 34, 7, K_6 = 210; 32, 29$, and $K_7 = 204; 54, 28$, we have $J(1440) \approx 1398; 12, 28$, which fulfills the requirement (3f).

## 8. GOVINDASVĀMIN’S SECOND ORDER INTERPOLATION

When $0 < \varepsilon < \alpha$,

$$J(\alpha_i + \varepsilon) = J_i + \frac{\varepsilon}{\alpha} \cdot K_{i+1} + E,$$

where

$$E = \frac{1}{4} \cdot \frac{3\varepsilon(\alpha - \varepsilon)}{\alpha^2} \cdot (K_i - K_{i+1}) \text{ (for } i = 1 \text{ to } 7),$$

$$E = \frac{1}{6} \cdot \frac{3\varepsilon(\alpha - \varepsilon)}{\alpha^2} \cdot (K_i - K_{i+1}) \text{ (for } i = 8 \text{ to } 15),$$

$$E = \frac{1}{47 - 2i} \cdot \frac{\alpha - \varepsilon}{\alpha} \cdot \frac{\varepsilon}{\alpha} \cdot K_{i+1} \text{ (for } i = 16 \text{ to } 23).$$

For our case ($i = 6$),

$$J(1440) = J_6 + \frac{2}{5} \cdot K_7 + \frac{9}{50} \cdot (K_6 - K_7)$$

The results of the calculations, none of which meets the requirements, are shown in Table 2.

## 9. BHĀSKARA I’S RATIONAL APPROXIMATION

When the arc $\theta$ is measured in degree,

$$R \sin \theta = \frac{R\theta(180 - \theta)}{[40500 - \theta(180 - \theta)] / 4}.$$

For $x$ measured in $kalā$, we have

$$J(x) = \frac{R \cdot \frac{x}{60} (180 - \frac{x}{60})}{[40500 - \frac{x}{60} (180 - \frac{x}{60})] / 4}.$$

For our case,

$$J(1440) = \frac{416}{1021} \cdot R.$$

The results of the calculations, none of which meets the requirements, are shown in Table 2.

## 10. MĀDHAVA’S POWER SERIES EXPANSION

For $n \ge 2$,

$$J(x) = x - x \cdot \frac{x^2}{(2^2 + 2)R^2} + x \cdot \frac{x^2}{(2^2 + 2)R^2} \cdot \frac{x^2}{(4^2 + 4)R^2} - \dots$$

$$+ (-1)^{n-1} x \cdot \frac{x^{2n-2}}{(2^2 + 2)(4^2 + 4) \dots \{(2n - 2)^2 + (2n - 2)\} R^{2n-2}}$$

For this formula see Appendix B. Table 1 shows $J(1440)$ obtained by means of this formula for $n = 2, 3, 4, 5$, and 100. The underlined values meet the requirements. Interestingly, with Govindasvāmin’s $R = 3437; 44, 19$, Mādhava’s $R = 3437; 44, 48$ and Nīlakaṇṭha’s $R = 3437; 44, 47$, calculation up to the third term is enough for obtaining $J(1440)$ that fulfills the requirements. The same power series with Mādhava’s coefficients (see Appendix B) produces the same value, $J(1440) = 1398; 15, 27, 17, 3$, as has been obtained for $n$ greater than 4 with Mādhava’s $R$.
Table 1: $J(1440)$ by Mādhava’s power series

| $n$ | a,b. Ārya $R = 3438$ | c. Govinda $3437;44,19$ | d. Mādhava $3437;44,48$ | e. Nīla-A1 $3437;28$ | f. Nīla-A2 $3437;44,47$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2 | 1397;53,45,12,27 | 1397;53,22,09,24 | 1397;53,22,51,57 | 1397;52,58,10, 12 | 1397;53,22,50,39 |
| 3 | 1398;15,54,46,26 | <u>1398;15,22,07,48</u> | <u>1398;15,32,49,29</u> | 1398;15,08,33,38 | <u>1398;15,32,48,11</u> |
| 4 | 1398;15,49,13,09 | <u>1398;15,26,34,30</u> | <u>1398;15,27,16,12</u> | 1398;15,03,00,08 | <u>1398;15,27,14,54</u> |
| 5 | 1398;15,49,14,00 | <u>1398;15,26,35,22</u> | <u>1398;15,27,17,03</u> | 1398;15,03,01,00 | <u>1398;15,27,15,46</u> |
| 100 | 1398;15,49,14,00 | <u>1398;15,26,35,22</u> | <u>1398;15,27,17,03</u> | 1398;15,03,01,00 | <u>1398;15,27,15,46</u> |

608 INDIAN JOURNAL OF HISTORY OF SCIENCE
Table 2: Data and the values obtained by calculation

| | a. Ārya | b. corr. Ārya | c. Govinda | d. Mādhava | e. Nīla-A1 | f. Nīla-A2 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $R$ | 3438 | 3438 | 3437;44,19 | 3437;44,48 | 3437;28 | 3437;44,47 |
| $J_6$ | 1315 | 1316 | 1315;33,56 | 1315;34,07 | 1315;32 | 1315;34,07 |
| $J_7$ | 1520 | 1521 | 1520;28,22 | 1520;28,35 | 1520;26 | 1520;28,35 |
| $K_6$ | 210 | 211 | 210;32,26 | 210;32,29 | 210;32 | 210;32,29 |
| $K_7$ | 205 | 205 | 203;54.26 | 204;54,28 | 204;54 | 204;54,28 |
| $J'_6 (= J_{18})$ | 3177 | 3176 | 3176;03,23 | 3176;03,50 | 3175;53 | 3176;03,49 |
| **$J(1440)$** | | | | | | |
| Lower limit (§3) $^{*1}$ | 1398;23,... | 1398;23,... | 1398;10,... | 1398;10,... | 1397;57,... | 1398;10,... |
| Upper limit (§3) $^{*2}$ | 1398;32,... | 1398;32,... | 1398;20,... | 1398;20,... | 1398;06,... | 1398;20,... |
| Linear Int. (§4) | 1397;00 | 1398;00 | 1397;31,42 | 1397;31,54 | 1397;30 | 1397;31,54 |
| Nīlakaṇṭha’s Int. (§5) | 1397;42 | 1398;41 | <u>1398;15,18</u> | <u>1398;15,39</u> | 1398;07 | <u>1398;15,27</u> |
| Mādhava’s Int. (§6) | 1397;43 | 1398;41 | 1398; 15,49 | 1398,16,01 | 1398;14 | <u>1398; 16,00</u> |
| Brahma’s Int. (§7) | 1397;36 | 1398;43 | <u>1398; 12,16</u> | <u>1398; 12,28</u> | 1398;10 | <u>1398; 12,28</u> |
| Govinda’s Int. (§8) | 1399;54 | 1401;29 | 1400;58,33 | 1400;57,50 | 1400;46 | 1400;47,50 |
| Bhāskara’s App. (§9) | 1400;47 | 1400;47 | 1400;41,06 | 1400;41,17 | 1400;34 | 1400;41,16 |
| Mādhava’s P.S. (§10) $^{*3}$ | 1398;16 | 1398;16 | <u>1398; 15,32</u> | <u>1398; 15,32</u> | 1398; 15 | <u>1398;15,32</u> |
| Mādhava’s P.S. (§10) $^{*4}$ | 1398;16 | 1398;16 | <u>1398;15,26</u> | <u>1398;15,27</u> | 1398;15 | <u>1398;15,27</u> |
| Mādhava’s P.S. (§10) $^{*5}$ | | | | <u>1398;15,27</u> | | |

$^{*1}$ $R^2/8452;30$. $^{*2}$ $R^2/8451;30$. $^{*3}$ Calculated up to the 3rd term. $^{*4}$ Calculated up to the 4th term. $^{*5}$ With Mādhava’s coefficients.

## 11. VAṬEŚVARA’S VALUE OF $J(1440)$

At the beginning of the second chapter of his *Siddhānta*, Vaṭeśvara gives a $J_i$ table [VS 2.1.2-27a] and a versed sine table [VS 2.1.27-49] up to $vikalā$ with $R = 3437; 44$ and $n = 96$. And in the next verse [VS 2.1.50] he states that $R^2 = 11818047; 35$ and $J(1440) = 1398; 13$. Interestingly, these values produce 8452: $R^2/J(1440) = 11818047; 35/1398; 13 = 8452; 13, 44, \dots$
His value of $R$ is a variation of Āryabhaṭa’s value 3438. That is, from $21600/(2R) = 62832/20000$ we have $R = (216 \cdot 10^6)/62832 = 3437; 44, 19, 26, 4, \dots \approx 3437; 44$. His value of $R^2$ can be obtained either from $3437; 44, 19, 26^2 = 11818047; 35, 9, \dots$ or from $\{(216 \cdot 10^6)/62832\}^2 = (46656 \cdot 10^{12})/3947860224 = 11818047; 35; 18; \dots$ As has been pointed out by Shukla [see his note on VS 2.1.61 (part 2, p.170)], $J(1440) = 1398; 13$ can be obtained from Vaṭeśvara’s $J_i$ table with $n = 96$ by means of the linear interpolation modified for that table [VS 2.1.61]:

$$J(\theta) = J_i + \frac{(J_{i+1} - J_i)r}{15},$$

where $\theta$ is expressed in degree and $i$ and $r$ are respectively the quotient and the remainder of the division, $96\theta/90$ or $16\theta/15$. When $\theta = 24$, we have $i = 25$ and $r = 9$. In Vaṭeśvara’s $J_i$ table, $J_{25} = 1367; 21$ and $J_{26} = 1418; 47$ [Mallayya (2014), p.149]. Hence follows: $J(1440) = 1367; 21 + \{(1418; 47 - 1367; 21) \cdot 9\}/15 = 1367; 21 + 30; 51, 36 = 1398; 12, 36 \approx 1398; 13$.

## 12. CONCLUSION

Table 2 shows the data and the results of calculation of the six cases (a, b, c, d, e, f) treated in §4-§10 above. The sixteen values underlined fulfill the requirements. Among these, the most probable candidate for the value of $J(1440)$ used by Nīlakaṇṭha for deriving 8452 is 1398;15,27 or 1398,15 (see also Appendix C) obtained from his second table of $J_i$ by means of his own interpolation (5f), but 8452 can be produced also
609 NĪLAKAṆṬHA’S VALUE OF R-SINE FOR THE ARC OF TWENTY-FOUR DEGREES
by 1398;16,1 or 1398;16 obtained from Mādhava’s $J_i$ with $R = 3437; 44, 48$ (6d) and 1398;16,0 or 1398;16 obtained from Nīlakaṇṭha’s own $J_i$ with $R = 3437; 44, 47$ (6f), both by means of Mādhava’s second order interpolation; and by 1398;15,32 or 1398;16 and 1398;15,27 or 1398;15 obtained either for $R = 3437; 44; 48$ or for $3437;44,47$ by means of Mādhava’s power series (10d and 10f); the latter value is also obtained by means of Mādhava’s power series with his five coefficients (10d). The same two values, 1398;15 and 1398;16, can also be obtained from Govindasvāmin’s $J_i$ with $R = 3437; 44; 19$ either by Mādhava’s interpolation (6c), or by Nīlakaṇṭha’s interpolation (5c), or by Mādhava’s power series (10c). The number 8452 can also be yielded by Vaṭeśvara’s $J(1440) = 1398;13$, which has been obtained from his $J_i$ table with $n = 96$ and $R = 3437; 44$ by means of the linear interpolation.
Brahmagupta’s second order interpolation too produces 8452 from Govindasvāmin’s $J_i$ with $R = 3437; 44, 19$ (7c), from Mādhava’s $J_i$ with $R = 3437; 44, 48$ (7d), and from Nīlakaṇṭha’s $J_i$ with $R = 3437; 44, 47$ (7f), but it is unlikely that the Kerala astronomers who had their own methods of interpolation ventured to use Brahmagupta’s even if they knew it.

# APPENDICES

## A. Reconstruction of Nīlakaṇṭha’s table of $J_i$

For constructing an R-sine table or a table of $J_i$, Nīlakaṇṭha prescribes, in addition to the traditional diagrammatical method [GS 3.6-9ab], two recursion methods, both of which are based on the principle that the second order sine difference is proportionate to the sine, a principle stated in the *Āryabhaṭīya* [AB 2.12], that is,

$$K_i - K_{i+1} = (K_1 - K_2) \frac{J_i}{J_1},$$

which in turn is based on the relationship,

$$\frac{K_i - K_{i+1}}{J_i} = \left( \frac{a}{R} \right)^2,$$

where $a$ is the ‘whole chord’ (*samasta-jyā*) subtending one unit arc ($\alpha$) [Hayashi (1997)]. The only difference between the two methods lies in the accuracy of the coefficients for (i.e., divisors of) $J_i$ in the formulas for $K_{i+1}$, that is, 233;30 in method 1 and 233;31,38,13 in method 2.

### A1. Method 1 [TS 2.3cd-6ab]

$$J_1 = K_1 = 224; 50, \quad K_{i+1} = K_i - \frac{J_i}{233;30},$$

$$J_{i+1} = K_1 + K_2 + \dots + K_{i+1}.$$

If we calculate $K_i$ and $J_i$ according to this method, rounding off the third sexagesimal place of the quotient of the division by 233;30 to the nearest *tatparā* at each step, we obtain the two columns designated A1 of Table 3. As the initial value ($J_1 = K_1$) has the figures down to the first sexagesimal place (*vikalā*) only, other $K_i$ and $J_i$ are also valid up to that place.

### A2. Method 2 [TS 2.6cd-10ab]

$$2R = \frac{21600.113}{355}, \quad J_{23} = J'_{1} = \sqrt{J_{24}^2 - J_1^2},$$

$$K_i - K_{i+1} = \frac{2(J_{24} - J_{23})J_i}{R}.$$

Nīlakaṇṭha gives the last equation in his *Golasāra* aslo [GS 13cd-14ab] after rewriting it with $J_{24} - J_{23} = K_{24}$. He cites the same verse in his commentary on the second chapter of the *Āryabhaṭīya* [NAB2, p.53, lines 12-13] and proves it in the lines that follow. Cf. [Hayashi et al. (1997), pp.108-11]. For a modern proof of the same equation see [Ramasubramanian et al. (2011), pp.62-63].
From the first equation we have $J_{24} = R = 3437; 44, 47, 19, \dots$ By means of Mādhava’s power series (see §10 above) we have $J_1 = K_1 = 224; 50;$
610 INDIAN JOURNAL OF HISTORY OF SCIENCE
21; 50; from the second equation $J_{23} \approx 3430; 23; 9; 35$; and therefore

$$\frac{R}{2(J_{24} - J_{23})} = \frac{3437;44,47,19}{14;43,15,28} = 233;31,38,13, \dots$$

By substituting the reciprocal of this value in the third equation, we have

$$K_{i+1} = K_i - \frac{J_i}{233;31,38,13}.$$

If we calculate $K_i$ and $J_i$ according to this method, rounding off the fourth sexagesimal place of the quotient of the division by 233;31,38,13 at each step, we obtain the two columns designated A2 of Table 3. These $J_i$, except $J_{15}$ and $J_{23}$, are the same as those obtained by means of the diagrammatical method [GS3.6-9ab] with $C/d = 355/113$ [GS 3.12ab] after the third sexagesimal places are rounded off. See [Mallayya (2014), p.153, Table 9], which has 2858;22,54.16 ($\approx 2858; 22, 54$) for $J_{15}$ and 3430;23,09.60 ($\approx 3430; 23, 10$) for $J_{23}$.
Table 3: Nīlakaṇṭha’s $J_i$ tables reconstructed

| $i$ | A1 (acc. to TS 2.3cd-6ab) $K_i$ | A1 (acc. to TS 2.3cd-6ab) $^{*1} J_i$ | A2 (acc. to TS 2.6cd-10ab) $K_i$ | A2 (acc. to TS 2.6cd-10ab) $J_i$ |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 224 ; 50 | 224 ; 50 | 224 ; 50,21,50 | 224 ; 50,21,50 |
| 2 | 223 ; 52,14 | 448 ; 42,14 | 223 ; 52,35,46 | 448 ; 42,57,36 |
| 3 | 221 ; 56,56 | 670 ; 39,10 | 221 ; 57,18,28 | 670 ; 40,16,04 |
| 4 | 219 ; 04,36 | 889 ; 43,46 | 219 ; 04,59,34 | 889 ; 45,15,38 |
| 5 | 215 ; 15,59 | 1104 ; 59,45 | 215 ; 16,23,20 | 1105 ; 01,38,58 |
| 6 | 210 ; 32,03 | 1315 ; 31,48 | 210 ; 32,28,30 | 1315 ; 34,07,28 |
| 7 | 204 ; 54,01 | 1520 ; 25,49 | 204 ; 54,28,01 | 1520 ; 28,35,29 |
| 8 | 198 ; 23,20 | 1718 ; 49,09 | 198 ; 23,48,43 | 1718 ; 52,24,12 |
| 9 | 191 ; 01,40 | 1909 ; 50,49 | 191 ; 02,10,59 | 1909 ; 54,35,11 |
| 10 | 182 ; 50,55 | 2092 ; 41,44 | 182 ; 51,28,17 | 2092 ; 46,03,28 |
| 11 | 173 ; 53,11 | 2266 ; 34,55 | 173 ; 53,46,41 | 2266 ; 39,50,09 |
| 12 | 164 ; 10,46 | 2430 ; 45,41 | 164 ; 11,24,20 | 2430 ; 51,14,29 |
| 13 | 153 ; 46,10 | 2584 ; 31,51 | 153 ; 46,50.53 | 2584 ; 38,05,22 |
| 14 | 142 ; 42,03 | 2727 ; 13,54 | 142 ; 42,46,47 | 2727 ; 20,52,09 |
| 15 | 131 ; 01,16 | 2858 ; 15,10 | 131 ; 02,02,39 | 2858 ; 22,54,48 |
| 16 | 118 ; 46,49 | 2977 ; 01,59 | 118 ; 47,38,32 | 2977 ; 10,33,20 |
| 17 | 106 ; 01,50 | 3083 ; 03,49 | 106 ; 02,43,07 | 3083 ; 13,16,27 |
| 18 | 92 ; 49,37 | 3175 ; 53,26 | 92 ; 50,32,56 | 3176 ; 03,49,23 |
| 19 | 79 ; 13,32 | 3255 ; 06,58 | 79 ; 14,31,30 | 3255 ; 18,20,53 |
| 20 | 65 ; 17,06 | 3320 ; 24,04 | 65 ; 18,08,30 | 3320 ; 36,29,23 |
| 21 | 51 ; 03,54 | 3371 ; 27,58 | 51 ; 04,58,49 | 3371 ; 41,28,12 |
| 22 | 36 ; 37,34 | 3408 ; 05,32 | 36 ; 38,41,39 | 3408 ; 20,09,51 |
| 23 | 22 ; 01,50 | 3430 ; 07,22 | 22 ; 02,59,34 | $^{*2}$3430 ; 23,09,25 |
| 24 | 7 ; 20,26 | 3437 ; 27,48 | 7 ; 21,37,34 | $^{*2}$3437 ; 44,46,59 |

$^{*1}$ [Ramasubramanian et al. (2011), p.64] lists $J_i$ of A1 up to *vikalā* (first sexagesimal place). Those values can be obtained from these by rounding off the second sexagesimal place (*tatparā*) except for $J_{12}, J_{17}, J_{19}, J_{21}, J_{22}$, and $J_{24}$; their values for these $J_i$ differ by one *vikalā* from the values in this list after the second sexagesimal place is rounded off.
$^{*2}$ These values for $J_{23}$ and $J_{24}$ are less than those used in the calculation of the divisor, 233;31,38,13, of $J_i$ (see Appendix A2) by 0;0,0,10 and 0;0,0,20, respectively.
611 NĪLAKAṆṬHA’S VALUE OF R-SINE FOR THE ARC OF TWENTY-FOUR DEGREES
Table 4: Possible derivations of Mādhava’s $J_i$

| $i$ | Mādhava’s (in 6 verses) $J_i$ | B1 (by power series) $J_i$ | B2 (with coefficients) $J_i$ | B3 (by sine difference) $K_i$ | B3 (by sine difference) $J_i$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 0224; 50,22 | 224; 50,21,49,36 | 224; 50,21,49,36 | 224; 50,21,50 | 224; 50,21,50 |
| 2 | 0448; 42,58 | 448; 42,57,35,05 | 448; 42,57,35,05 | 223; 52,35,46 | 448; 42,57,36 |
| 3 | 0670; 40,16 | 670; 40,16,02,49 | 670; 40,16,02,49 | 221; 57,18,28 | 670; 40,16,04 |
| 4 | 0889; 45,15 | *889; 45,15,36,34 | *889; 45,15,36,31 | 219; 04,59,34 | *889; 45,15,38 |
| 5 | 1105; 01,39 | 1105; 01,38,56,06 | 1105; 01,38,56,19 | 215; 16,23,20 | 1105; 01,38,58 |
| 6 | 1315; 34,07 | 1315; 34,07,26,06 | 1315; 34,07,26,06 | 210; 32,28,30 | 1315; 34,07,28 |
| 7 | 1520; 28,35 | 1520; 28,35,26,48 | 1520; 28,35,27,01 | 204; 54,28,01 | 1520; 28,35,29 |
| 8 | 1718; 52,24 | 1718; 52,24,10,17 | 1718; 52,24,10,17 | 198; 23,48,43 | 1718; 52,24,12 |
| 9 | 1909; 54,35 | 1909; 54,35,10,06 | 1909; 54,35,09,53 | 191; 02,10,59 | 1909; 54,35,11 |
| 10 | 2092; 46,03 | 2092; 46,03,27,25 | 2092; 46,03,27,38 | 182; 51,28,17 | 2092; 46,03,28 |
| 11 | 2266; 39,50 | 2266; 39,50,09,44 | 2266; 39,50,09,57 | 173; 53,46,41 | 2266; 39,50,09 |
| 12 | 2430; 51,15 | 2430; 51,14,31,59 | 2430; 51,14,32,12 | 164; 11,24,21 | 2430; 51,14,30 |
| 13 | 2584; 38,06 | *2584; 38,05,27,36 | *2584; 38,05,27,48 | 153; 46,50,54 | *2584; 38,05,24 |
| 14 | 2727; 20,52 | 2727; 20,52,17,45 | 2727; 20,52,17,32 | 142; 42,46,48 | 2727; 20,52,12 |
| 15 | 2858; 22,55 | 2858; 22,54,59,54 | 2858; 22,54,59,54 | 131; 02,02,40 | 2858; 22,54,52 |
| 16 | 2977; 10,34 | 2977; 10,33,36,00 | 2977; 10,33,36,00 | 118; 47,38,33 | *2977; 10,33,25 |
| 17 | 3083; 13,17 | 3083; 13,16,47,03 | 3083; 13,16,46,50 | 106; 02,43,08 | 3083; 13,16,33 |
| 18 | 3176; 03,50 | 3176; 03,49,47,03 | 3176; 03,49,47,29 | 92; 50,32,57 | 3176; 03,49,30 |
| 19 | 3255; 18,22 | *3255; 18,21,22,36 | *3255; 18,21,22,49 | 79; 14,31,31 | *3255; 18,21,01 |
| 20 | 3320; 36,30 | 3320; 36,29,58,12 | 3320; 36,29,58,50 | 65; 18,08,31 | 3320; 36,29,32 |
| 21 | 3371; 41,29 | 3371; 41,28,53,06 | 3371; 41,28,53,58 | 51; 04,58,50 | *3371; 41,28,22 |
| 22 | 3408; 20,11 | 3408; 20,10,38,12 | 3408; 20,10,39,30 | 36; 38,41,40 | *3408; 20,10,02 |
| 23 | 3430; 23,11 | *3430; 23,10,18,46 | *3430; 23,10,20,29 | 22; 02,59,35 | *3430; 23,09,37 |
| 24 | 3437; 44,48 | 3437; 44,48,00,43 | 3437; 44,48,00,04 | 7; 21,37,35 | *3437; 44,47,12 |

## B. Derivation of Mādhava’s table of $J_i$

Mādhava’s versified table of $J_i$ (see the second column of Table 4) is cited by Nīlakaṇṭha in his commentary on the *Āryabhaṭīya* [NAB2, p.55, lines 10-22] and by Śaṅkara Vāriyar in his prose commentary on the *Tantrasaṅgraha* [TS 2.6cd-10ab; cf. Ramasubramanian et al. (2011), p.63]. The values given in the six verses agree fairly well, though not perfectly, with those obtained by means of Mādhava’s power series for $J(x)$.
Śaṅkara in his metrical commentary *Yuktidīpikā* on the *Tantrasaṅgraha* [YD 2.440-41 $\approx$ 2.451-52] and in his prose commentary on the *Līlavatī* [KK on L 199, p.390] anonymously quotes Mādhava’s rule for $J(x)$ for any arc $x$ expressed in $kalā$, which may be expressed in modern notation as follows.
Let $f_i$ ($i \ge 2$) be dened as

$$f_i = \frac{x^2}{\{(2i - 2)^2 + (2i - 2)\}R^2}.$$

Put $x$ and $f_i$ vertically one below the other — column (1) in the next diagram; starting from the top, multiply the upper into the lower in succession — (2); and, starting from the bottom, subtract the lower from the upper in succession; the result is $J(x)$ — (3).

612 INDIAN JOURNAL OF HISTORY OF SCIENCE

| (1) | (2) |
| :-: | :-: |
| $x$ | $x$ |
| $f_2$ | $x f_2$ |
| $f_3$ | $x f_2 f_3$ |
| $\vdots$ | $\vdots$ |
| $f_{n-1}$ | $x f_2 f_3 \dots f_{n-1}$ |
| $f_n$ | $x f_2 f_3 \dots f_{n-1} f_n$ |

(3) $J(x) = x - (x f_2 - (x f_2 f_3 - \dots - (x f_2 f_3 \dots f_{n-1} - x f_2 f_3 \dots f_n)))$.
This (3) may be rewritten as

$$J(x) = x - x \cdot \frac{x^2}{(2^2 + 2)R^2} + x \cdot \frac{x^2}{(2^2 + 2)R^2} \cdot \frac{x^2}{(4^2 + 4)R^2} - \dots$$

$$+ (-1)^{n-1} x \cdot \frac{x^{2n-2}}{(2^2 + 2)(4^2 + 4) \dots \{(2n-2)^2 + (2n-2)\} R^{2n-2}}$$

In passing, this is equivalent to:

$$\sin \theta = \theta - \frac{\theta^3}{3!} + \frac{\theta^5}{5!} - \dots + (-1)^{n-1} \frac{\theta^{2n-1}}{(2n-1)!}$$

Now, if we put $y = x/5400$, the above formula with the first six terms of the right-hand side can be rewritten as

$$J(x) = x - a_1 y^3 + a_2 y^5 - a_3 y^7 + a_4 y^9 - a_5 y^{11},$$

where, for Mādhava’s $R = 3437; 44, 48$,

$$a_1 = \frac{5400^3}{3! R^2} = 2220; 39, 40, \quad a_2 = \frac{5400^5}{5! R^4} = 273; 57, 47,$$

$$a_3 = \frac{5400^7}{7! R^6} = 16; 5, 41, \quad a_4 = \frac{5400^9}{9! R^8} = 0; 33, 6,$$

$$a_5 = \frac{5400^{11}}{11! R^{10}} = 0; 0, 44.$$

A quarter verse that reads these five coefficients in the Kaṭapayādi notation is quoted by Nīlakaṇṭha [NAB2.17cd, p.113, line 7] and by Śaṅkara [YD 2.437a, p.117]. Cf. [Gupta (1976); Gold and Pingree (1991); Pingree (2003), pp.49-51].
The third column of Table 4 (B1) shows the results of the calculations by the power series with Mādhava’s $R = 3437; 44, 48$ and $n = 7$. The four asterisked values differ from Mādhava’s by one *tatparā* when their third sexagesimal places are rounded off. The fourth column (B2) shows the values obtained by Mādhava series with Mādhava’s coefficients up to the sixth term. Here also, the same four $J_i$, asterisked, differ from Mādhava’s by one *tatparā*.
For comparison, I also put in the same table the values of $K_i$ and $J_i$ obtained by means of the recursive formula for the sine differences as in Appendix A2 above. Here I use, instead of 355/113 used by Nīlakaṇṭha in the first of the three equations, Mādhava’s ratio of the circumference to the diameter, $C/d = 2827433388233/(9 \cdot 10^{11})$, cited by Nīlakaṇṭha [NAB2, p.42] and by Śaṅkara [KK, p.377]. From this we obtain $J_{24} = R = 3437; 44, 48, 22, \dots$; by means of Mādhava’s power series $J_1 = K_1 = 224; 50, 21, 50, \dots$ as above; from the second equation $J_{23} \approx 3430; 23, 10, 38$; and therefore,

$$\frac{R}{2(J_{24} - J_{23})} = \frac{3437; 44, 48, 22}{14; 43, 15, 28} = 233; 31, 38, 17 \dots$$

Finally from the third equation, we have

$$K_{i+1} = K_i - \frac{J_i}{233; 31, 38, 17}.$$

As in Appendix A2, if we calculate $K_i$ and $J_i$ according to this method, rounding off the fourth sexagesimal place of the quotient of the division by 233;31,38,17 at each step, we obtain the two columns designated B3 of Table 4. The eight asterisked values differ from Mādhava’s by one *tatparā* when their third sexagesimal places are rounded off.
***
NĪLAKAṆṬHA’S VALUE OF R-SINE FOR THE ARC OF TWENTY-FOUR DEGREES 613
Of course, Mādhava could have used the diagrammatical procedure alluded to in the *Āryabhaṭīya* [AB 2.11] etc. (cf. [Hayashi (1997), p.403]) and it would have brought him more accurate values. But every step of that procedure involves square-root computation as the procedure consists of the two formulas:

$$J_{24-i} = \sqrt{R^2 - J_i^2} \text{ and } J_{\frac{i}{2}} = \frac{\sqrt{J_i^2 + (R - J_{24-i})^2}}{2}.$$

It is therefore very cumbersome especially with numbers expressed partly in decimal and partly in sexagesimal notation. This may have been the reason why he, as well as others, avoided this procedure.

### C. Confirmation

The anonymous referee of this paper rightly pointed out that I had missed the following three cases: (1) Vaṭeśvara’s value of $J(1440)$, (2) ‘similar approximations’ that occur in Nīlakaṇṭha’s auto-commentary on the CC (8452 on p.8 and 1398 on p.16), and (3) Govindasvāmin’s interpolation. ‘8452’ of case (2) does not provide new information; case (3) has been included in later versions of the draft; and (1) was newly incorporated as §11. But more important is ‘1398 on p.16’ of case (2), which leads us to the confirmation of a candidate for $J(1440)$.
It occurs in an *Anuṣṭubh* verse of Nīlakaṇṭha, which he cites in his own commentary on CC 19-21. The verse in the published edition reads:
> ‘सौरिः शक्यं (2715) दधौ लोके (1398)
> संस्कारो लग्नवत् किल ।
> अपमज्याध्रुवविष्कम्भदलज्ये क्रमशोऽन्तिमे ॥’
The editor admits numerical values (expressed in the Kaṭapayādi notation) only in the first *pāda*. Here he seems to be confused: he first divides it into three parts, *sauriḥ* (27), *śakyam* (15), and *dadhau loke* (1398), and then combines the first two numbers into one (2715), so that the first *pāda* signifies the two numbers, 2715 and 1398. Certainly two numbers are expected in this verse because it is introduced by the words, ‘The maximum declination is stated as *bhāpakramaḥ* (‘declination 24 $^\circ$’) [in AB 1.8a]. ... Its complementary arc is sixty-six degrees. Their <half> chords have been obtained and read <in verse by us as follows>.’ Now, 1398 may be an approximation to $J(24^\circ)$, but 2715 cannot be an approximation to $J(66^\circ)$. Nor can I find any meaning (or role) of it. So, I propose to read one number each in the first and the second *pādas*, both in eight digits, as follows (I emended *śakyam*, which does not make sense in this context, to *śalyam*, which does not change the numerical meaning).
> सौरिः शल्यं दधौ लोके (७२५१८९३१)
> संस्कारो लग्नवत्किल (७१२३०४१३) ।
> अपमज्याध्रुवविष्कम्भदलज्ये क्रमशोऽन्तिमे ॥
Saturn put distress upon the world (72518931); purification at an auspicious moment <is necessary> indeed (71230413). <These are> respectively the chord of the declination and the chord of the semi-diameter of the diurnal <circle of the sun>, both being final.
In other words, 1398;15,27 and 3140;32,17 are respectively the half chords (*J*’s or Rsines) of the sun’s maximum declination ($24^\circ$ or 1440 *kalās*) and its complementary arc ($66^\circ$ or 3960 *kalās*):

$$J(1440) = 1398; 15, 27,$$

$$J(3960) = 3140; 32, 17.$$

Remarkably, by this reading, the first *pāda* of the cited verse turns out to have given exactly the same value of $J(1440)$ that we have already obtained by means of Mādhava’s power series both from Mādhava’s $R = 3437; 44, 48$ and from Nīlakaṇṭha’s $R = 3437; 44, 47$ (see Table 1), and also by means of Nīlakaṇṭha’s interpolation (see
***
614 INDIAN JOURNAL OF HISTORY OF SCIENCE
5f and Table 2) from his second table of $J_i$ with $R = 3437; 44, 47$ (Appendix A2).
The above interpretation of the cited verse is confirmed with regard to the second *pāda* also; nearly the same values of $J(3960)$ are obtained in the same manner. By Mādhava’s power series (see §10) we have $J(3960) = 3140; 32, 16, 26, 36 \approx 3140; 32, 16$ from Mādhava’s $R$ and $3140; 32, 15, 59, 49 \approx 3140; 32, 16$ from Nīlakaṇṭha’s $R$, when $n \ge 7$ (when $n = 5$, Nīlakaṇṭha’s $R$ happens to produce $3140; 32, 17, 27, 18 \approx 3140; 32, 17$). The same approximation is obtained by Nīlakaṇṭha’s interpolation (see § 5), too:

$$J(3960) = J'(1440) = \frac{J'_6 \cdot J'(90) - J_6 \cdot J(90)}{R}$$

$$= 3140; 32, 15, 38, \dots \approx 3140; 32, 16.$$

Of course, the Pythagorean theorem could also be used to produce $J(3960)$ as the arc 3960 is complementary to 1440:

$$J(3960) = \sqrt{R^2 - J(1440)^2}.$$

Thus, we have $3140;32,15,45, \dots \approx 3140;32,16$ from Mādhava’s $R$ and $3140; 32, 15, 14, \dots \approx 3140; 32, 15$ from Nīlakaṇṭha’s.

### ACKNOWLEDGMENT

I am grateful to the anonymous referee whose valuable comments helped me improve this paper (see Appendix C).

### BIBLIOGRAPHY

#### 1. Primary sources

*Āryabhaṭīya* of Āryabhaṭa (Abbrev: AB) ed. with the commentary of Bhāskara I and Someśvara, Indian National Science Academy, New Delhi, 1976.
*Āryabhaṭīyabhāṣya* of Nīlakaṇṭha, *Gaṇitapāda* (Abbrev: NAB2) ed. by K. S. Śāstrī, Trivandrum Sanskrit Series 101, University of Trivandrum, Trivandrum, 1930.
*Āryabhaṭīyabhāṣya* of Nīlakaṇṭha, *Golapāda* (Abbrev: NAB4) ed. by S. K. Pillai, Trivandrum Sanskrit Series 185, University of Trivandrum, Trivandrum, 1957.
*Brāhmasphuṭasiddhānta* of Brahmagupta (Abbrev: BSS) ed. by S. Dvivedin, Medical Hall Press, Benares, 1902.
*Candracchāyāgaṇita* of Nīlakaṇṭha (Abbrev: CC) ed. with an English translation by K.V. Sarma, Panjab University Indological Series 6, Panjab University, Hoshiarpur, 1976.
*Golādhyaya* of Bhāskara II (Abbrev: GA) ed. by M. Dh. Chaturvedi in: *Siddhāntaśiromaṇi* of Bhāskarācārya, Library Rare Text Publication Series 5, Sampurnanand Sanskrit University, Varanasi, 1981.
*Golāsara* of Nīlakaṇṭha (Abbrev: GS) ed. by K. V. Sarma, Vishveshvaranand Indological Series 47, Vishveshvaranand Institute, Hoshiarpur, 1970.
*Grahagaṇitādhāya* of Bhāskara II (Abbrev: GG) ed. by M. Dh. Chaturvedi in: *Siddhāntaśiromaṇi* of Bhāskarācārya, Library Rare Text Publication Series 5, Sampurnanand Sanskrit University, Varanasi, 1981.
*Khaṇḍakhādyaka* of Brahmagupta (Abbrev: KhKh) ed. with Utpala’s commentary and an English translation by B. Chatterjee, 2 vols., World Press, Calcutta, 1970.
*Kriyākramakarī* of Śaṅkara Vāriyar and Nārāyaṇa (Abbrev: KK). See *Līlāvatī* of Bhāskara II below.
*Līlāvatī* of Bhāskara II (Abbrev: L) ed. with the *Kriyākramakarī* of Śaṅkara and Nārāyaṇa by K. V. Sarma, Vishveshvaranand Indological Series 66, Vishveshvaranand Institute, Hoshiarpur, 1975.
*Mahābhāskarīya* of Bhāskara I (Abbrev: MB) ed. with the commentary *Bhāṣya* of Govindasvāmin and the super commentary *Siddhāntadīpikā* of Parameśva by T. S. Kuppanna Sastri, Madras Government Oriental Series 130, Government Oriental Manuscripts Library, Madras, 1957.
*Mahābhāskarīyabhāṣya* of Govindasvāmin (Abbrev: GMB). See *Mahābhāskarīya* of Bhāskara I above.
*Tantrasaṅgraha* of Nīlakaṇṭha (Abbrev: TS) ed. with the *Yuktidīpika* and *Laghuvivṛti* of Śaṅkara Vāriyar by K. V. Sarma, Punjab University, Hoshiarpur, 1977.
*Vaṭeśvarasiddhānta* of Vaṭeśvara (Abbrev: VS) ed. with an English translation and notes by K. S. Shukla, 2 parts, Indian National Science Academy, New Delhi, 1985-86.
*Yuktidīpikā* of Śaṅkara Vāriyar (Abbrev: YD). See *Tantrasaṅgraha* of Nīlakaṇṭha above.
***
NĪLAKAṆṬHA’S VALUE OF R-SINE FOR THE ARC OF TWENTY-FOUR DEGREES 615

#### 2. Secondary sources

Bag, A. K. Mādhava’s Sine and Cosine Series, *Indian Journal of History of Science* 11(1976): 54-57.
Gold, D. and D. Pingree. A Hitherto Unknown Sanskrit Work concerning Mādhava’s Derivation of the Power Series for Sine and Cosine, *Historia Scientiarum* 42(1991): 49-65.
Gupta, R.C. Second Order Interpolation in Indian Mathematics up to the Fifteenth Century, *Indian Journal of History of Science* 4(1969): 86-98.
Gupta, R.C. Fractional Parts of Āryabhaṭa’s Sines and Certain Rules Found in Govindasvāmin’s Bhāṣya on the *Mahābhāskarīya*, *Indian Journal of History of Science* 6(1971): 51-59.
Gupta, R.C. Mādhava’s Power Series Computation of the Sine, *Gaṇita* 27(1976): 19-24.
Hayashi, T. Āryabhaṭa’s Rule and Table for Sine Differences, *Historia Mathematica* 24(1997): 396-406.
Hayashi, T., T. Kusuba, and M. Yano. *Studies in Indian Mathematics: Series, Pi and Trigonometry*, in Japanese, Koseisha Koseikaku, Tokyo, 1997.
Knudsen, T. Versified Sine Tables in Jñānarāja’s *Siddhāntasundara*, *Indian Journal of History of Science* 49(2014): 127-41.
Mallayya, V. M. Trigonometric Tables in India, *Indian Journal of History of Science* 49(2014): 142-56.
Pingree, D. The Logic of Non-Western Science: Mathematical Discoveries in Medieval India, *Dædalus* (Journal of the American Academy of Arts & Sciences) Fall/2003 (2003): 45-53.
Ramasubramanian, K. and M. S. Sriram. *Tantrasaṅgraha of Nīlakaṇṭha Somayājī*, Springer, London etc., 2011.
