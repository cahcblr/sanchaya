# Methods of Interpolation in Indian Astronomy

- Author Display: Nidhi Handa and Padmavati Taneja
- Year: 2014
- Journal Label: IJHS-49-2014-Issue-3
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol49_3_3_NHanda.pdf

<!-- source: gemini page-chunk extraction -->

Indian Journal of History of Science, 49.3 (2014) 251-259

# METHODS OF INTERPOLATION IN INDIAN ASTRONOMY

NIDHI HANDA AND PADMAVATI TANEJA*
(Received 01 May 2012; revised 05 September 2014)

### Abstract

Āryabhaṭa I (476 AD), Brahmagupta (598 AD), Bhāskara II (1114 AD) and others have discussed methods of interpolation for evaluating values of trigonometric functions. However Brahmagupta is credited for using second-difference interpolation formula to evaluate various values of Hindu trigonometric functions. The main purpose of this paper is to present a brief account of the work done on interpolation by Brahmagupta in his astronomical work *Khaṇḍakhādyaka*. Further we give a remark on its probable impact on other cultural areas.
**Key words:** *Bhogyakhaṇḍa*, *Gatakhaṇḍa*, *Jyā*, *Sphuṭabhogyakhaṇḍa*, *Vikalā*
---
*Department of Mathematics, Gurukula Kangri Vishwavidyalaya, Haridwar - 249404, Email: nidhi_6744@yahoo.co

## 1. INTRODUCTION

Construction of tabular R-sines and difference and interpolated functional values corresponding to intervening values of the argument, for their use in various astronomical determination, have been found to be common in India from very early centuries of AD (Chatterjee, 1970). The Indian astronomer Āryabhaṭa I (476 AD) used the first order finite difference to calculate tabular sine-differences. From his composition *Āryabhaṭīya* II, we obtain a rule for finding tabular sine-differences equivalent to the relation (Gupta, 1969)

$$\Delta^2 \sin x = -k \sin x$$

Later mathematicians and astronomers used more proficient methods in search of more and more accurate result.
In seventh century AD, Brahmagupta made use of second difference interpolation for calculation of correct *Bhogyakhaṇḍa* probably for the first time in the history of mathematics (Chatterjee, 1970). He made remarkable achievements in the field of mathematics and astronomy which proved as guidance for several succeeding astronomers and mathematicians. In this paper an attempt has been made to bring out to light the improved rule of interpolation by using second difference given by Brahmagupta in his astronomical treatise *Khaṇḍakhādyaka* and its further elucidation by later mathematicians as Bhāskarācārya and Govindasvāmi.

## 2. ĀRYABHAṬA’S USE OF INTERPOLATION FORMULA

From the classical age of Indian mathematics Āryabhaṭa was the first in the line of great mathematicians and astronomers (Wikipedia). He is credited for discovering the sine-function and for giving the table of sine-differences (Ramasubramanian, 2010). Āryabhaṭa’s table of sine is a table of the first differences of the values of trigonometric sine expressed in arc minute. In his composition *Āryabhaṭīya*, he gave a method for computation of R sines geometrically, which yielded a table of 24 R Sine-differences at intervals of 225 (Joseph, 2009).
From his *Āryabhaṭīya* we found the following verse enunciating the method of linear proportion for obtaining tabular sine-difference (Sharma & Shukla, 1976; Singh, 2010)
प्रथमाच्चापज्यार्धाधैरूनं खंडितं द्वितीयार्धम् ।
तत्प्रथमज्यार्धांशैस्तैस्तै रूनानि शेषाणि ॥
(Gaṇitapāda 12)
The first R sine divided by it gives the quotient (q). Now to obtain the second sine first sine is added to the same (i.e. the first sine) and diminished by the quotient. Similarly other Sines are obtained by successively subtracting the sum of the entire quotient from the first sine and adding the result successively to the last of the already obtained Sines.
In modern notations
The first $jy\bar{a}^* = jy\bar{a} \text{ } 225 = 225$ (as 8th part of $30^\circ = 3\frac{3}{4}^\circ = 225$)
Or $d_1 = R \sin \theta = R\theta = 225$

$$d_2 = R \sin \theta + R \sin \theta - \frac{R \sin \theta}{R \sin \theta}$$

$$= d_1 + 225 - q_1 \quad (\text{where } q_1 = \frac{225}{225})$$

$$= 225 + 225 - \frac{225}{225}$$

$$= 449$$

$$d_3 = d_2 + 225 - (q_1 + q)$$

Hence $d_n = d_{n-1} + 225 - (q_1 + q_2 + \dots + q_n)$
$n = 1, 2, \dots 24$
It can be summarized as $d_n = d_{n-1} + d_1 - q_t$
(* Here $Jy\bar{a}$ is the radius multiplied by modern sine)
From *Sūryasiddhanta* (c. 400 AD), an earlier text than *Āryabhaṭīya*, we also find the same formula along with a list of 24 R sines (Chatterjee, 1970; Sharma & Shukla, 1976; Srinivasiengar, 1967). Hence it is a matter of contemplation that whether Āryabhaṭa himself constructed his table of sine or borrowed its idea from *Sūryasiddhānta*.
Āryabhaṭa constructed his table of Sines taking $r \text{ (radius)} = 3438$
(As circumference of a circle $= 360^\circ = 360 \times 60 = 21600 \text{ minute}$)

$$\text{Radius of a circle} = \frac{21600}{2\pi} = \frac{21600}{2(3.14)} = 3438'$$

His table shows only the Sines of multiple of $3\frac{3}{4}^\circ$. For finding the Sines of other angles between $0^\circ$ and $90^\circ$ he made use of the method of interpolation i.e. by applying the method of proportion to the difference (Singh, 2010). His Sine table is as follows (Mallaya, 2000 and Singh, 2010):

### Table 1. Sine Table

| No. | Angle | Āryabhaṭa’s *Jyā* Or Hindu Sine | Modern $3438 \times (\sin \theta)$ |
| :--- | :--- | :--- | :--- |
| 1. | $3^\circ 45$ | 225 | 224.85 |
| 2. | $7^\circ 20$ | 449 | 448.95 |
| 3. | $11^\circ 15$ | 671 | 670.72 |
| 4. | $15^\circ 0$ | 890 | 889.82 |
| 5. | $18^\circ 45$ | 1105 | 1105.01 |
| 6. | $22^\circ 30$ | 1315 | 1315.05 |
| 7. | $26^\circ 15$ | 1520 | 1520.58 |
| 8. | $30^\circ 0$ | 1719 | 1719.00 |
| 9. | $33^\circ 45$ | 1910 | 1910.05 |
| 10. | $37^\circ 30$ | 2093 | 2092.09 |
| 11. | $41^\circ 15$ | 2267 | 2266.08 |
| 12. | $45^\circ 0$ | 2431 | 2431.01 |
| 13. | $48^\circ 45$ | 2585 | 2584.08 |
| 14. | $52^\circ 30$ | 2728 | 2727.55 |
| 15. | $56^\circ 15$ | 2859 | 2858.55 |

Contd...

| No. | Angle | Āryabhaṭa’s *Jyā* Or Hindu Sine | Modern $3438 \times (\sin \theta)$ |
| :--- | :--- | :--- | :--- |
| 16. | $60^\circ 0$ | 2978 | 2977.04 |
| 17. | $63^\circ 45$ | 3084 | 3083.45 |
| 18. | $67^\circ 30$ | 3177 | 3176.06 |
| 19. | $71^\circ 15$ | 3256 | 3255.75 |
| 20. | $75^\circ 0$ | 3321 | 3320.85 |
| 21. | $78^\circ 45$ | 3372 | 3371.95 |
| 22. | $82^\circ 30$ | 3409 | 3408.75 |
| 23. | $86^\circ 15$ | 3431 | 3430.85 |
| 24. | $90^\circ 0$ | 3438 | 3438 |

Hence it is clear that Āryabhaṭa made use of the interpolation formula for finding the sine values and after him another eminent scholar Brahmagupta extended his interpolation formula up to second difference interpolation formula.

## 3. BRAHMAGUPTA’S INTERPOLATION FORMULA

Brahmagupta (598 AD) was a great mathematical prodigy born in Bhinmal city in the state of Rajasthan of Northwest India. He was the son of Jiṣṇugupta. His achievements and contributions glorified the Indian mathematics and astronomy. He made use of mathematics and algebra in predicting astronomical events. (Wikipedia).
His two principle works are *Brāhmasphuṭa Siddhānta* and *Khaṇḍakhādyaka*. *Khaṇḍakhādyaka* is an expository book on astronomy, which consists of mainly two parts *Pūrvakhaṇḍakhādyaka* and *Uttarakhaṇḍakhādyaka*. In the *Uttarakhaṇḍakhādyaka* part of his book he had discussed many innovative ideas for the calculation of *natakāla*, *mandaparidhi* and *śīghraparidhi*, which are especially useful for the calculation of an eclipse. His description of the motions of the planets and stars were based mainly on mathematical calculation to a degree that had not been achieved by earlier astronomers. But the most glorious innovation was that he calculated correct *Bhogyakhaṇḍa* by the method of interpolation, using the second difference – for the first time in the history of mathematics (Chatterjee, 1970).

### 3.1 Interpolation formula for equal intervals

In his astronomical treatise *Khaṇḍakhādyaka* he had given the table of Sines and interpolation formula for finding the values of Sines at different intervals. From *Uttarakhaṇḍakhādyaka*, we get the improved rule of interpolation by using the second difference.
In *Uttarakhaṇḍakhādyaka*, he termed the correct tabular difference by the name *Sphuṭabhogyakhaṇḍa* and also gave the methods of finding it for calculating *Jyā*, *Utkramajyā*, *Krānti* and *Mandaphala*. To evaluate *Sphuṭabhogyakhaṇḍa*, he multiplied the *Vikala* by half the difference of the *Gatakhaṇḍā* (GK) and the *Bhogyakhaṇḍa* (BK) and divides the product by 900. Now this result is either added or subtracted from half the sum of GK and BK accordingly as this half sum is less or greater than the BK. In each case we get the required *Sphuṭabhogyakhaṇḍa* (Chatterjee, 1970). [Here *Vikala* is the remainder left after subtracting as many tabular differences of *Jyās* etc. as possible]
To explain this procedure following example is taken from Varuna’s commentary.
Find Jyā 2 signs $28^\circ 57' 44''$
$2 \text{ signs } 28^\circ 57' 44'' = 5 \times 900' + 837' 44''$
Hence we see that five differences or *khaṇḍās* 39, 36, 31, 24, 15 have been passed. The next *Khaṇḍā* 5 is *Bhogyakhaṇḍa*, 15 is *Gatakhaṇḍa* (refer Table 2) and $837' 44''$ is *Vikala* (Chatterjee, 1970).

$$\text{Sphuṭabhogyakhaṇḍa} = \frac{15+5}{2} \pm \frac{\left( \frac{15-5}{2} \right) (837' 44'')}{900}$$

$$= 10 \pm \frac{837' 44''}{180}$$

Hence the required *jyā* can be calculated as follows:

$$\text{The required Jyā} = \frac{\text{Vikala (Sphuṭabhogyakhaṇḍa)}}{900} + \text{Khaṇḍas passed}$$

$$= \frac{(837' 44'') \left( 10 \pm \frac{837' 44''}{180} \right)}{900} + 39 + 36 + 31 + 24 + 15$$

$$= \frac{(837.73) \left( 10 \pm \frac{837.73}{180} \right)}{900} + 145 \quad (\text{as } 44'' = 0.73 \text{ min})$$

$$= 4.976 + 145 = 149.976$$

From *Uttarakhaṇḍakhādyaka* (UKK) we obtain the following śloka also which describes the Brahmagupta’s interpolation rule for equal intervals (Gupta, 1969 and Sharma, 1189).
गतभोग्य खण्डकान्तरदलविकलवधात्
शतेर्नवाभिराप्त्या ।
तद्युतिदल युतोण भोग्यादधिकां भोग्यम् ॥
UKK IX.8
Multiply half the difference of the tabular difference ($d_t$) and the difference to be passed over ($d_{t+1}$) by the residual arc ($\theta$ in minutes) and divide by 900 minutes ($h$). The result is added to or subtracted from half the sum (of $d_t$ and $d_{t+1}$) according to whether this half sum is less than or greater than the tabular difference to be crossed. Hence obtained result is the true functional difference to be crossed (Rao, 1994)
UKK 8
In modern notations it can be shown as:

$$d = \frac{1}{2}(d_t + d_{t+1}) \pm \frac{1}{2}(d_t - d_{t+1}) \frac{\theta}{h} \quad \dots(1)$$

accordingly as $d_t < d_{t+1}$ or $d_t > d_{t+1} \quad \dots(2)$
keeping $\theta = nh$ and using (1) in (2), and we get

$$f(x+nh) = f(x) + \frac{n}{2} \{\Delta f(x-h) + \Delta f(x)\} + \frac{n^2}{2} \Delta^2 f(x-h)$$

This formula is similar to the Newton-Stirling formula up to the second difference term (Gupta, 1979).
For table of Sines, we get the following śloka from his manuscript *Khaṇḍakhādyaka* (Chatterjee, 1970).
त्रिंशत् सन्नवरसेन्दुजिन (तिथि) विषयगृहाद्धं पापाना
अर्द्धज्या खण्डानि ज्या भुक्तैक्यं सभोग्यफलम् ॥
KK I.3
Thirty increased severally by 9, 6, 1 and 24, 15 and 5 are the tabular differences of Sines at intervals of half a sine. For any arc the ‘sine’ is the sum of the parts passed over increased by the proportional part of the tabular difference to be passed over.
It can be expressed in tabular form as follows

### Table 2. Brahmagupta’s table of Sines

| S. No. | Angle (in degrees) | Sine | Sine-differences: First Difference | Sine-differences: Second Difference |
| :--- | :--- | :--- | :--- | :--- |
| 1. | 0 | 0 | | |
| 2. | 15 | 39 | 39 | -3 |
| 3. | 30 | 75 | 36 | -5 |
| 4. | 45 | 106 | 31 | -7 |
| 5. | 60 | 130 | 24 | -9 |
| 6. | 75 | 145 | 15 | -10 |
| 7. | 90 | 150 | 5 | |

Using above table we can find the value of R sin 57° with the help of following procedure:
$57^\circ = 3420 \text{ min} = 900 \times 3 + 720$
$h = 15^\circ = 15 \times 60 = 900 \text{ min}$
From table it is clear that three of the tabular differences are considered as passed over: the last one being 31 ($d_t$) and the one to be passed over is 24 ($d_{t+1}$) and we see that $d_t > d_{t+1}$
Hence from equation (1) true tabular difference is

$$d = \frac{24+31}{2} - \frac{720}{900} \times \left( \frac{31-24}{2} \right)$$

Hence

$$\text{R sin } 57^\circ = 106 + \frac{720}{900} \left[ \frac{24+31}{2} - \frac{720}{900} \times \left( \frac{31-24}{2} \right) \right]$$

$$= 106 + \frac{720}{900} \left[ \frac{55}{2} - \frac{28}{10} \right]$$

$$= 106 + \frac{8}{10} [24.7] = 106 + 19.7 = 125.76$$

Similarly we can also find the value of R sin 67° by using the same procedure:
$67^\circ = 4020 \text{ min} = 900 \times 4 + 420$
Here 24 is ($d_t$) and 15 is ($d_{t+1}$) and we see that $d_t > d_{t+1}$
Hence from equation (1) true tabular difference is

$$d = \frac{15+24}{2} - \frac{420}{900} \times \left( \frac{24-15}{2} \right)$$

Hence

$$\text{R sin } 67^\circ = 130 + \frac{420}{900} \left[ \frac{15+24}{2} - \frac{420}{900} \times \left( \frac{24-15}{2} \right) \right]$$

$$= 130 + \frac{7}{5} [17.4] = 130 + \frac{121.8}{15} = 138.12$$

Its modern value is 138.08, which is very nearer to the value as has been calculated by Brahmagupta’s Interpolation formula.
From Table (1) we have the value of

$$\text{R sin } 56^\circ 15' = 2859$$

$$\text{and R sin } 60^\circ 0' = 2978$$

Hence we see the difference in the two given intervals is
$3^\circ 45'$ or $225' = 119$ for $1 = 119$

$$\text{For } 1' = \frac{119}{225}$$

$$\text{or } 45' = \frac{119}{225} \times 45' = 23.26$$

Thus $\text{R sin } 57^\circ = \text{Rsin } 56^\circ 15 + 45$
$= 2859 + 23.26 = 2882 \text{ (appr.)}$
where $R = 3438$ hence 3438
$\text{Sin } 57^\circ = 2882 \quad \text{Sin } 57^\circ = 0.8373$
if we consider $R = 150$ then we have the value of R Sin 57° as
$\text{R sin } 57^\circ = 150 \times 0.8373 = 125.74 \text{ (appr.)}$
Similarly the value of R sin 67° (for $R = 3438$) by using Āryabhaṭa’s table is
$\text{R sin } 67^\circ 30 = 3177$
$\text{R sin } 71^\circ 15 = 3256$
The difference in the two given intervals is $225 = 79$

$$1' = \frac{79}{225}$$

$$30' = \frac{79}{225} \times 30' = 10.53$$

256 INDIAN JOURNAL OF HISTORY OF SCIENCE
$R \sin 67^\circ = 3177 - 10.53 = 3166.47$ (when $R = 3438$)
$\sin 67^\circ = 0.9210$
when $R = 150$ then
$R \sin 67^\circ = 138.15$ (appr.)
Now we evaluate these values by modern methods [Mallayya, 2000]
$\sin 57^\circ = 0.8387$ (appr.)
when $R = 150$ then
$R \sin 57^\circ = 150 \times 0.8387 = 125.8$ (appr.)
$\sin 67^\circ = 0.9205$ (appr.)
when $R = 150$ then
$R \sin 67^\circ = 150 \times 0.9205 = 138.08$ (appr.)
Other values are listed in the table 3.
On comparing the different values of $R \sin \theta$ we obtain the following table which represents the different values of $R \sin \theta$ at different intervals as calculated by two different methods, first by using Āryabhaṭa’s table and second by using Brahmagupta’s Interpolation formula. Moreover these values are then compared with the values of $R \sin \theta$ calculated by modern methods and we see that the variations are a little.
Comparing Āryabhaṭa’s $R \sin \theta$ values and Brahmagupta’s $R \sin \theta$ values with modern values of $R \sin \theta$, we found that there is striking similarity between the results obtained by different methods.
**Table 3**

| S. No. | Arc $\theta$ (deg.) | Value of $R \sin \theta$ as Calculated from Āryabhaṭa’s table $R = 150$ | Value of $R \sin \theta$ as calculated by using Brahmagupta’s Interpolation formula $R = 150$ | Value of $R \sin \theta$ as calculated by modern methods $R = 150$ |
| :--- | :--- | :--- | :--- | :--- |
| 1. | 37° | 90.25 | 90.08 | 90.272 |
| 2. | 47° | 109.64 | 109.61 | 109.703 |
| 3. | 57° | 125.74 | 125.76 | 125.8 |
| 4. | 67° | 138.15 | 138.12 | 138.08 |
| 5. | 77° | 146.08 | 146.24 | 146.26 |
| 6. | 87° | 149.77 | 149.80 | 149.79 |

### 3.2 Interpolation formula for unequal intervals

From his manuscript *Khaṇḍakhādyaka* we also find the use of interpolation formula in finding any intermediate value when the given data is at unequal intervals. He also made use of it in computing the *gatiphala* (change in the equation) correspond to any given *gati* (change in anomaly) when the tabulated values of the *gatiphala* (गतिफल) are at unequal intervals (Gupta, 1969).
From this astronomical treatise we obtain the relevant couplet for finding the true functional difference to be passed over
> भुक्त गति फलांश गुणा भोग्य गतिर्भुक्त गति हृता लब्धम् ।
> भुक्तः गतेः फल भागास्तद् भोग्य फलान्तराधे हतम् ।।
> विकलं भोग्य गति हृतं लब्धेनोनाधिकं फलैक्यार्धम् ।
> भोग्य फलानधिकोनं तद् भोग्य फलं स्फुटं भवति ।।
> (*Khaṇḍa Khādyaka*, IX, 12-13, etc.)
On dividing the product of last *gatiphala* ($D_p$) (in degrees) and current *gati* ($h_{p+1}$) by the last *gati* ($h_p$); we obtain the “adjusted” last *gatiphala* ($d_p$). Multiply half the difference of the “adjusted” last *gatiphala* and the current *gatiphala* by the residual arc and divide by the current *gati*. The new result is added or subtracted from half the sum of the “adjusted” last *gatiphala* and the current *gatiphala* accordingly whether this half sum is less or more than the current *gatiphala*. The final result is the true current *gatiphala* ($D_t$) i.e. true functional difference to be passed cover (Gupta, 1969[^1]).

[^1]: Note: The OCR text and printed page indicate "19692", which appears to be a citation typo for 1969 or a specific reference index.

METHODS OF INTERPOLATION IN INDIAN ASTRONOMY 257
In modern notation it can be shown as:

$$d_p = D_p \left( \frac{h_{p+1}}{h_p} \right)$$

or

$$D_t = \frac{1}{2}(d_p + d_{p+1}) \pm \frac{1}{2}(d_p - d_{p+1}) \frac{\theta}{h_{p+1}}$$

addition or subtraction can be taken accordingly as $\frac{1}{2}(d_p + d_{p+1})$ is less or greater than $d_{p+1}$ i.e. accordingly as $d_p$ is less or greater than $d_{p+1}$.
To obtain desired result

$$f(x + \theta) = f(x) + \frac{\theta}{h_{p+1}} D_t$$

where $x = a_p = h_1 + h_2 + \dots$
$f(x) = D_1 + D_2 + \dots + D_p$
In particular case when the intervals are equal i.e. $h_p = h_{p+1}$
We will have $d_p = D_p$
Then the rule will takes the form of its earlier rule that is for equal intervals.
Muniśvara in seventeenth century AD attempted to modify Brahmagupta’s Interpolation formula in order to obtain more accurate results. It has been lucidly explained by R. C. Gupta (1979).

## 4. BHĀSKARA II FORM OF INTERPOLATION FORMULA

Bhāskara II (b. 1114 AD), a renowned mathematician of twelfth century, is well known for his compositions *Līlāvatī*, *Bījagaṇita* and *Siddhānta-Śiromaṇi*. He had computed the interpolation formula for finding the tabular difference which is same as had been computed by Brahmagupta, only he used $h = 10^\circ$ instead of $h = 15^\circ (= 900')$ (Gupta, 1969).
Bhāskara II gave the following relevant couplet in the *Grahagaṇita* part of his *Siddhānta-Śiromaṇi*,
> यातैष्योः खण्डयोर्विशेषः
> शेषांश निघ्नो नखहृत् तदूनम् ।
> युतं गतैष्यैक्य दलं स्फुटं स्यात्
> क्रमोत्क्रमज्याकरणेऽत्र भोग्यम् ।।१६।।
> (*Siddhānta-Śiromaṇi* II (*Spaṣṭādhikāra*), 16)
> (Shastri, 1957)
The difference of the tabular difference passed over and tabular difference to be passed over is multiplied by the residual arc $\theta$ and divided by 20. In case of sine this result is subtracted from half the sum of tabular difference passed over ($D_p$) and tabular difference to be passed over ($D_{p+1}$) and in case of versed sine this result is added to the sum of $D_p$ and $D_{p+1}$. Here $D_p$ is the tabular difference passed over and $D_{p+1}$ is the tabular difference to be passed over.
That is $D_t = \frac{1}{2}(D_p + D_{p+1}) \pm \frac{1}{2}(D_p \sim D_{p+1}) \frac{\theta}{10}$
For computing sine and versed sine we have to take the negative and positive sign respectively.
The tabular differences at the end and beginning of the current intervals are $(D_{p+1})$ and $\frac{1}{2}(D_p + D_{p+1})$ respectively. Then the correction will be (Gupta, 1969).

$$= - \left\{ \frac{1}{2}(D_p + D_{p+1}) \sim D_{p+1} \right\} \frac{\theta}{10} = \frac{\theta}{20}(D_p - D_{p+1})$$

Combining it with $\frac{1}{2}(D_p + D_{p+1})$ we get the required $D_t$.
As tabular difference (*apacaya*) for sine and increase (*upacaya*) in case of versed sine, thus we have to add or subtract the correction term (Gupta, 1969).
258 INDIAN JOURNAL OF HISTORY OF SCIENCE
Hence

$$D_t = \frac{1}{2}(D_p + D_{p+1}) \pm \frac{\theta}{20}(D_p \sim D_{p+1})$$

is the required expression for the ‘true’ *Bhogyakhaṇḍa* $D_t$.

## 5. GOVINDASVĀMI’S RULES FOR INTERPOLATION

Govindasvāmi (c. 800-850) was an astronomer of Kerala whose most famous treatise was a commentary on the *Mahābhāskarīya* of Bhāskara I (Mallayya, 2008). Bhāskara I wrote the *Mahābhāskarīya* in about 600 AD and in 830 AD Govindasvāmi wrote commentary on it by the name *Bhāṣya*. One of the most interesting aspects of the commentary however is Govindasvāmi’s construction of the sine-table. Indian mathematicians and astronomers constructed sine-table with great precision. In his commentary *Bhāṣya* he enunciated a set of particular rules of making second order interpolation to compute the intermediary functional values. Different formulas had been laid down for different argument intervals. The relevant text from his commentary is as follows:
> गच्छद्यात गुणान्तराहत वपुर्यातेष्यदिग्श्वासनेच्छे—
> दाभ्यास समूह कार्मुक कृति प्राप्तात्, त्रिभिस्ताडितात् ।
> वेदैः षड्भिरवाप्तमन्त्य गुणजे राश्योः क्रमात्, अन्त्यभे
> गन्तव्याहत वर्तमान गुणज्याप्तमेकादिभिः ।।
> अन्त्यादनुत्क्रमतः क्रमेण विषमः विशेषैः क्षिपेद्
> भङ्क्त्वाप्तं, यदि मौर्विका विधिरयं मख्याः क्रमात्
> वर्तते ।
> शोध्यं व्युत्क्रमतस्तथाकृत-फलं .......
> (Govindasvāmi’s commentary on *Mahābhāskarīya*)
> (Shastri, 1957)
For first and second term, multiply the difference of the last and the current sine-difference i.e. $(D_p - D_{p+1})$ by the two parts of the elemental arc $h$ (made by any intermediary point on it). Now multiply it by three and divide by the square of the elemental arc (Gupta, 1969).
Now for the first term divide the so obtained result by four and by six for the second term.
According to these rules, we have
(Suppose first quadrant has 24 equal divisions)
First term

$$E = \frac{1}{4} \frac{3\theta(h-\theta)}{h^2}(D_p - D_{p+1}) \text{ when } p = 1 \text{ to } 7$$

For second term

$$E = \frac{1}{6} \frac{3\theta(h-\theta)}{h^2}(D_p - D_{p+1}) \text{ when } p = 8 \text{ to } 15$$

For the third term, multiply the linearly proportional part of the current sine-difference by remaining part of the elemental arc. Hence
Third term

$$E = \left( \frac{h-\theta}{h} \right) \frac{\theta}{h} D_{p+1} \left( \frac{1}{47 - 2p} \right) \text{ when } p = 16 \text{ to } 23$$

On dividing the so obtained result by the odd numbers 1, 3, 5 etc. accordingly as the current sine difference is first, second, third when counted from the end in the reversed order.
The final result thus obtained is added to one portion of the current sine-difference to obtain the *Bhogyaphala* (true sine-difference)

$$R \sin(x + \theta) - R \sin x = \frac{\theta}{h} D_{p+1} + E$$

By the ordinary first order linear interpolation we obtain $\frac{\theta}{h} D_{p+1}$, and $E$ is the term got by second order interpolation.
These are the rules of computing sine-difference for direct sines. Apply the rules in the reversed order in case of versed sine and the above corrections are to be subtracted from the respective differences (got by linear interpolation).
METHODS OF INTERPOLATION IN INDIAN ASTRONOMY 259
Using $\Delta$ as the finite difference operation and $h^{th}$ step-length, the rule for the second *rāśi* (30 to 60) may be put as:

$$f(x + nh) = f(x) + n \Delta f(x) + \frac{n(n-1)}{2} \{ \Delta f(x) - \Delta f(x - h) \}$$

It is the modern form of Govindasvāmi’s rule and is a particular form of the general Newton-Gauss interpolation formula to the second-order (Rao, 1994). It is equivalent to that of Brahmagupta’s interpolation rule for equal knots.

## 6. CONCLUSION

Indian mathematicians carried out a constant search at least from the time of Āryabhaṭa I (b. 476 AD); for accurate method of interpolation especially in respect of sine-values for intermediate angles. Moreover for the accurate computation of the motion of celestial bodies requires more sophisticated interpolation technique than just first order. Hence Brahmagupta (b. 598 AD) used a second difference interpolation formula, which was rediscovered nearly a thousand years later and termed as Newton-Stirling formula.
Hence we can see that the work of Āryabhaṭa and Brahmagupta on interpolation technique proved as fertile soil for further exploration. Preceding mathematicians like Bhāskara II, Govindasvāmi, Mādhava worked on it and further Newton, Gauss, Gregory and Bessel etc. extended this up to $n^{th}$ difference term, which is used in many advanced astronomical researches. Scientists became able to acquire immense information and knowledge about solar and lunar eclipses and movement of stars by using this interpolation technique. In present scenario it is still being searched out.

### ACKNOWLEDGMENT

We are especially thankful to Prof. S.L. Singh and Prof. R.C. Gupta for their valuable support in preparing this paper

### BIBLIOGRAPHY

Aryabhaṭa, From Wikipedia, the free encyclopedia. http://en.wikipedia.org/wiki/Aryabhata.
Brahmagupta, From Wikipedia, the free encyclopedia. http://wikipedia.org/wiki/Birhmagupta.
Brahmagupta. http://www.answers.com/topic, 2010.
Chatterjee, Bina. (Ed. and Tr.) *The Khaṇḍakhādyaka of Brahmagupta*, Pub. Delhi, 1970.
Gupta, R.C. Second Order Interpolation in Indian Mathematics Up To The Fifteenth Century, *IJHS*, 4.1 & 2(1969):86-98
Gupta, R.C. Muniśvara’s Modification of Brahmagupta’s Rule for Second order Interpolation, *IJHS* 14 (1979):66-72
Joseph, G.G. *A Passage To Infinity, Medieval Indian Mathematics from Kerala and Its Impact*, SAGE Publications India Pvt. Ltd., New Delhi, 2009.
Mallayya, V. Madhukar. An Interesting Algorithm for Computation of Sine Tables from the *Golasāra* of Nīlakaṇṭha *Gaṇita Bhāratī*, 26.1-4 (2000):40-55.
Mallayya, V. Madhukar. Vateśvara’s Trigonometric Tables and the Method, *Gaṇita Bhāratī*, 30 (2008):61-79
Ramasubramanian, K. The Origin and Growth of Mathematics in India, R. C. Gupta Award Lecture, 21 Oct 2010.
Rao, S.B. *Indian Mathematics and Astronomy*, Jnana Deep Publications, Bangalore, 1994.
Sastri, T.S. Kuppana. (Editor), *Mahābhāskarīya*, with the *Bhāṣya* of Govindasvāmi and super-commentary *Siddhāntadīpikā* of Parmeśvara, Govt. Oriental MSS Library, Madras, 1957, P. XLXII
Sharma, K.V. and Shukla, K.S. *Āryabhaṭīya of Āryabhaṭa*, Critical Edition and Translation with Notes, INSA, New Delhi, 1976
Sharma, R.S. (Ed.), *Brāhmasphuṭa-siddhānta*, Delhi, Vol.4, ch. XVIII (on *Kuṭṭaka*), 1189.
Singh, S.L., Solving the equation $Nx^2+1 = Y^2$, Paper presented at ‘National Meet on History of Mathematical Sciences’, Delhi, 2010.
Srinivasiengar, C.N. *The History of Ancient Indian Mathematics*, The World Press Pvt. Ltd., Calcutta, 1967.
