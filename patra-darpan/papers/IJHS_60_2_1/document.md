# Precise determination of the ascendant in the Lagnaprakaraṇa ‑ V

- Author Display: Aditya Kolachana · K. Mahesh· K. Ramasubramanian
- Year: 2025
- Journal Label: IJHS-60-2025-Issue-2
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/IJHS_60_2_1.pdf

<!-- source: gemini page-chunk extraction -->

<!-- decode-chunk: pages=1-1 source_sha256=91b019395f6be99c68fc03d83a81e84c8849fde09a493b33f5bde7eac7b63f0d -->
# Precise determination of the ascendant in the *Lagnaprakaraṇa* - V

**Aditya Kolachana** $^1$ · **K. Mahesh** $^2$ · **K. Ramasubramanian** $^3$
Received: 23 July 2024 / Accepted: 30 April 2025 / Published online: 22 August 2025  
© Indian National Science Academy 2025

### Abstract

Mādhava’s *Lagnaprakaraṇa* is an important astronomical text which discusses numerous innovative techniques of precisely determining the *udayalagna* or the ascendant. In previous papers, we have explained the significance of various astronomical parameters discussed in the first chapter of this text, and detailed the different methods of precisely determining the ascendant described in its second, third and fifth chapters. In this paper, we present the translation and mathematical analysis of the fourth chapter of the *Lagnaprakaraṇa*, which prescribes a procedure for precisely determining the ascendant, employing concepts such as *samalagna*, *samaśaṅku* and *samadṛggati*.
**Keywords** Ascendant · Lagna · *Lagnaprakaraṇa* · Mādhava · *Samadṛggati* · *Samalagna* · *Samaśaṅku* · *Udayalagna*

## 1 Introduction

In a series of earlier papers, we have discussed various contributions of Mādhava to astronomy, particularly in developing ingenious computational techniques for the precise determination of the *udayalagna*, or the ascendant, in his *Lagnaprakaraṇa*. The first three papers presented techniques for determining astronomical quantities known as *prāṇakalāntara*, *cara* and *kālalagna*,[^1] that are employed to determine the ascendant. These techniques are described in the first thirty verses of the *Lagnaprakaraṇa*, which correspond to its first chapter. Three subsequent papers discussed the various techniques for precisely determining the *udayalagna*, described in verses 31–61 of the *Lagnaprakaraṇa*, corresponding to its second and third chapters.[^2] Yet another paper discussed the method of the computation of the *udayalagna* prescribed in verses 80–87 of the *Lagnaprakaraṇa*, corresponding to its fifth chapter.[^3]
In this paper, we discuss other methods to determine the ascendant described in verses 62–79 of *Lagnaprakaraṇa*. These verses, corresponding to the fourth chapter of the text, describe the procedure of determining the ascendant from the *samalagna*, or the intersection of the ecliptic and the prime vertical, and two associated quantities—*samaśaṅku* and *samadṛggati*. This paper should be read in conjunction with our earlier papers, as various physical and mathematical quantities described therein are employed here as well. In this regard, it may be reiterated that we employ the symbols $\lambda$, $\alpha$, $\delta$, and $z$ to respectively refer to the longitude, right ascension, declination, and zenith distance of a celestial body. The *kālalagna*, the latitude of the observer and the obliquity of the ecliptic are denoted by the symbols $\alpha_e$, $\phi$, and $\epsilon$, respectively. It may also be mentioned that all the figures in this paper depict the celestial sphere for an observer having a northerly latitude $\phi$. In these figures, $N$, $E$, $W$, and $So$ denote the cardinal directions north, east, west, and south, while $P$ and $K$ denote the poles of the celestial equator and the ecliptic, respectively. The symbol $S$ represents the Sun, while $\Gamma$ and $\Omega$ represent the vernal and autumnal equinoctial points, respectively.
---
$\boxtimes$ Aditya Kolachana  
aditya.kolachana@gmail.com
$^1$ IIT Madras, Chennai, India  
$^2$ IIT Kharagpur, Kharagpur, India  
$^3$ IIT Bombay, Mumbai, India  

[^1]: See Kolachana et al. (2018, 2019a), Kolachana (2018), respectively.

[^2]: See Kolachana et al. (2019b, 2020a, 2020b).

[^3]: See Kolachana et al. (2021).
<!-- /decode-chunk -->

<!-- decode-chunk: pages=2-2 source_sha256=22c40e8fa1e317d35087cb197a7b963031329ee7be2c40166629db5f06c2f83a -->
## 2 Outline of the procedure for determining the *udayalagna*

अथवा पूर्वमानीय
    समलग्नं पुनस्ततः ।
तच्छङ्कुदृग्गतिज्याभ्यां
    प्राग्विलग्नं समानयेत् ॥६२॥
athavā pūrvamānīya
    samalagnaṃ punastataḥ |
tacchaṅkudṛggatijyābhyāṃ
    prāgvilagnaṃ samānayet ||62||
Or, having first computed the *samalagna*, from that one should again compute the ascendant (*prāgvilagna*), using the *śaṅku* and *dṛggati* of that [*samalagna*].
The above verse, in the *anuṣṭubh* metre, outlines the procedure employed in the subsequent verses to determine the ascendant. This procedure involves determining the *samalagna* or the intersection of the ecliptic and the prime vertical, and then utilising its *śaṅku* and *dṛggati*, i.e., the *samaśaṅku* and *samadṛggati*, to compute the ascendant. It may be noted that the general procedure for precisely computing the ascendant from the *śaṅku* and *dṛggati* corresponding to any point on the ecliptic has already been dealt with in the third chapter of the *Lagnaprakaraṇa*, and is not discussed again in this chapter.[^4] We explain the procedure of computing the *samalagna*, the *samaśaṅku* and the *samadṛggati* in our discussion of the following verses.

## 3 First method of determining *samalagna*, *samaśaṅku* and *samadṛggati*

The procedure for determining the *samalagna* requires computing the *bhujāprabhā*, *valana*, *paramā bhujā*, etc. The computation of these quantities is first discussed in the next few verses. The *samalagna*, *samaśaṅku* and *samadṛggati* are computed thereafter.

### 3.1 Determining the *bhujāprabhā*

इनस्य शङ्कुं विपरीतदिक्कं
    प्रकल्प्य तस्मात् पुनरक्षनिघ्नात् ।
त्रिज्याहतापक्रमसंस्कृताद्यत्
    लम्बोद्धृतं तत्स्वभुजाप्रभा स्यात् ॥६३॥
inasya śaṅkuṃ viparītadikkaṃ
    prakalpya tasmāt punarakṣanighnāt |
trijyāhatāpakramasaṃskṛtādyat
    lamboddhṛtaṃ tatsvabhujāprabhā syāt||63||
Having considered the gnomon (*śaṅku*) of the Sun (*ina*) in different directions (*viparīta-dik*) [of declination], that [*śaṅku*] multiplied by [the Rsine of] the latitude (*akṣa*) and corrected by the radius (*trijyā*) multiplied [Rsine of] declination (*apakrama*) and divided by [the Rsine of] the co-latitude (*lamba*) would be its own *bhujāprabhā*.
The above verse, in the *upajāti* metre, gives the following relation:

$$\text{bhujāprabhā} = \frac{\text{śaṅku} \times \text{akṣajyā} \pm \text{trijyā} \times \text{apakramajyā}}{\text{lambajyā}},$$

or, with reference to Figs. 1a, b,

$$R \sin SC' = \frac{R \cos ZS \times R \sin \phi \pm |R \times R \sin \delta|}{R \cos \phi}. \tag{1}$$

The above relation can be understood with the help of Figs. 1a, b, which depict the celestial sphere from the west, at an instant when the Sun’s declination is positive and negative, respectively.[^5] In these figures, $PS$ and $ZS$ are respectively the arcs of the meridian and the vertical circle passing through the Sun ($S$). The perpendicular dropped from $S$ onto the horizon would be the *śaṅku*.[^6] $SC'$ is an arc of the great circle passing through the Sun and the north and south cardinal points, and is perpendicular to the prime vertical $ZW$—a great circle passing through the zenith and the east and west cardinal points.[^7]
In Fig. 1a, in the spherical triangle $PZS$, $PS = 90 - \delta$, $PZ = 90 - \phi$ and $P\hat{Z}S = 90 + x$. Applying the cosine rule,[^8] we have

$$\cos(90 - \delta) = \cos ZS \sin \phi + \sin ZS \cos \phi \cos(90 + x),$$

or,

[^4]: For more details on *śaṅku* and *dṛggati*, and the contents of the third chapter, see Kolachana et al. (2020b).

[^5]: *Viparīta-dik* (different directions, i.e., in the current context, both positive and negative declination) in the verse. See the discussion on verses 53–54 in Kolachana et al. (2020b) for more details.

[^6]: See the discussion on verses 53–54 in Kolachana et al. (2020b) for more details on the *śaṅku*.

[^7]: Since the north and south cardinal points are the poles of the prime vertical, all great circles passing through them are perpendicular to it.

[^8]: In previous papers, we have demonstrated how the Indian astronomers would have arrived at various results of spherical trigonometry using planar triangles. Here, for convenience, we directly derive the results using the rules of spherical trigonometry.
<!-- /decode-chunk -->

<!-- decode-chunk: pages=3-3 source_sha256=58ab1337642368c39e43fcfc0f4663d34166534e765b83770fe73de261854e10 -->
$$\sin x = \frac{\cos ZS \sin \phi - \sin \delta}{\sin ZS \cos \phi}. \tag{2}$$

In spherical triangle $ZSC'$, we have $Z\hat{C}'S = 90$ and $C'\hat{Z}S = x$. Applying the sine rule, we have

$$\sin SC' = \sin ZS \sin x.$$

Substituting for $\sin x$ from (2), we have

$$\sin SC' = \frac{\cos ZS \sin \phi - \sin \delta}{\cos \phi}. \tag{3}$$

Similarly, in Fig. 1b, from the spherical triangles $PZS$ (here, $PS = 90 + \delta$) and $ZSC'$, we obtain

$$\sin SC' = \frac{\cos ZS \sin \phi + \sin \delta}{\cos \phi}. \tag{4}$$

Thus, from (3) and (4), we obtain (1).[^9]

### 3.2 Determining the *valana*

सत्रिभद्युमणिबाह्वपक्रमे-  
     णार्धविस्तृतिहतेन संस्कृतात् ।  
अक्षदृग्गतिवधादवाप्यते  
     लम्बकेन वलनं विवस्वतः ॥६४॥
satribhadyumaṇibāhvapakrame-  
     ṇārdhavistṛtihatena saṃskṛtāt |  
akṣadṛggativadhādavāpyate  
     lambakena valanaṃ vivasvataḥ ||64||
The *valana* of the Sun (*vivasvat*) is obtained from the division of the product of [the Rsine of] the latitude (*akṣa*) and the *dṛggati*—which is corrected by the product of [the Rsine of] the declination (*apakrama*) of the longitude of the Sun (*dyumaṇi*) plus three signs (*satribha*) and the semi-diameter (*vistṛti*)—by [the Rsine of] the co-latitude (*lamba*).
The above verse, in the *rathoddhatā* metre, gives the following relation:

$$\text{\textit{valana}} = [\text{\textit{dṛggati}} \times \text{\textit{akṣajyā}} \pm \text{\textit{ardhavistṛti}} \times \text{\textit{satribhadyumaṇibāhvapakramajyā}}] \div \text{\textit{lambajyā}},$$

or, with reference to Figs. 2a, b,

$$R \sin S'C = \frac{R \cos ZS' \times R \sin \phi \pm |R \times R \sin \delta'|}{R \cos \phi}. \tag{5}$$

The above relation can be understood with the help of Figs. 2a, b, which depict the celestial sphere from the east, at the same instant as Figs. 1a, b, when the Sun’s declination is positive and negative, respectively. In Figs. 2a, b, $S'$ represents a point whose longitude is $90^\circ$ greater than the Sun ($S$) shown in Figs. 1a, b. That is

$$\lambda_{s'} = \lambda + 90, \tag{6}$$

where $\lambda$ and $\lambda_{s'}$ are the longitudes of $S$ and $S'$, respectively. Let $\delta'$ be the declination of $S'$. Further, $PS'$ and $ZS'$ are arcs of the meridian and the vertical circle passing through $S'$.[^10] $S'C$ is an arc of the great circle passing through $S'$ and the north and south cardinal points, and is perpendicular to the prime vertical $ZE$.[^11]
Now, in Fig. 2a, in the spherical triangle $PZS'$, $PS' = 90 + \delta'$, $PZ = 90 - \phi$ and $P\hat{Z}S' = 90 + y$. Applying the cosine rule, we have

$$\cos(90 + \delta') = \cos ZS' \sin \phi + \sin ZS' \cos \phi \cos(90 + y),$$

or,

$$\sin y = \frac{\cos ZS' \sin \phi + \sin \delta'}{\sin ZS' \cos \phi}. \tag{7}$$

In spherical triangle $ZS'C$, we have $Z\hat{C}S' = 90$ and $C\hat{Z}S' = y$. Applying the sine rule, we have

$$\sin S'C = \sin ZS' \sin y.$$

Substituting for $\sin y$ from (7), we have

$$\sin S'C = \frac{\cos ZS' \sin \phi + \sin \delta'}{\cos \phi}. \tag{8}$$

Similarly, in Fig. 2b, from the spherical triangles $PZS'$ (here, $PS' = 90 - \delta'$) and $ZS'C$, we obtain

$$\sin S'C' = \frac{\cos ZS' \sin \phi - \sin \delta'}{\cos \phi}. \tag{9}$$

Thus, from (8) and (9), we obtain (5).[^12]

[^9]: The measure of the *śaṅku* or $R \cos ZS$ is obtained from (1) in Kolachana et al. (2020b).

[^10]: Here, the *dṛggati* is to be understood as the perpendicular dropped from $S'$ onto the horizon, where, $\lambda_{s'} = \lambda + 90$. However, in the third chapter of the *Lagnaprakaraṇa*, the *dṛggati* is defined as the perpendicular dropped onto the horizon from a point $S'$ such that $\lambda_{s'} = \lambda - 90$. As any two points $180^\circ$ apart on the ecliptic would be symmetric with respect to the horizon, the measures of the perpendiculars dropped from these points onto the horizon would remain the same. See the discussion on verses 55–56 in Kolachana et al. (2020b) for more details on *dṛggati*.

[^11]: See footnote 7.

[^12]: The measure of the *dṛggati* or $R \cos ZS'$ is obtained from (4) in Kolachana et al. (2020b).
<!-- /decode-chunk -->

<!-- decode-chunk: pages=4-4 source_sha256=d21dc7879264df3411dbd5510935d19cb47602ae162db684efa19e2e9c723e9e -->
<!-- figure-resolved-page-render-hidden: image=media/p04_page.png caption="Fig. 1. Schematic representation of the celestial sphere from the west. (a) Sun with northern declination. (b) Sun with southern declination." -->

<!-- figure-meta: page=4, position=top-left, type=diagram -->

![Fig. 2. Schematic representation of the celestial sphere from the east at the same instant as Fig. 1. (a) $S'$, a point $90^\circ$ ahead of the Sun, having southern declination. (b) $S'$, a point $90^\circ$ ahead of the Sun, having northern declination.](media/p04_page.png)

*Fig. 2. Schematic representation of the celestial sphere from the east at the same instant as Fig. 1. (a) $S'$, a point $90^\circ$ ahead of the Sun, having southern declination. (b) $S'$, a point $90^\circ$ ahead of the Sun, having northern declination.*

<!-- figure-resolved-page-render: page=4 image=media/p04_page.png -->

<!-- figure-meta: page=4, position=top-right, type=diagram -->

### 3.3 Determining the *paramā bhujā*, *bhuja* and *koṭi*

वलनबाहुभयोरनयोर्द्वयोः
     कृतिसमासपदं परमा भुजा ।
त्रिभगुणौ भुजभावलनाहतौ
     परभुजाविहृतौ भुजकोटिके ॥६५॥
*valanabāhubhayoranayordvayoḥ*
   *kṛtisamāsapadaṃ paramā bhujā* |
*tribhaguṇau bhujabhāvalanāhatau*
   *parabhujāvihṛtau bhujakoṭike* ||65||
The square root of the sum of the squares of these two, *valana* and *bhujāprabhā* (*bāhubhā*), is the *paramā bhujā*. The *bhujāprabhā* (*bhujabhā*) and the *valana* multiplied by the radius (*tribhaguṇa*) and divided by
<!-- /decode-chunk -->

<!-- decode-chunk: pages=5-5 source_sha256=6ce027a681b08891525bd29be91b3807e410a320011495c0de8d42e80b821871 -->
the *paramā bhujā* (*parabhujā*) would be the *bhuja* and the *koṭi*, [respectively].
The above verse, in the *drutavilambita* metre, gives the following relations:

$$\mathit{paramābhujā} = \sqrt{(\mathit{bhujāprabhā})^2 + (\mathit{valana})^2},$$

or,

$$R \sin B = R \sin B' = \sqrt{(R \sin SC')^2 + (R \sin S'C)^2}, \tag{10}$$

and,

$$\mathit{bhuja} = \frac{\mathit{bhujāprabhā} \times \mathit{tribhaguṇa}}{\mathit{paramābhujā}},$$

$$\mathit{koṭi} = \frac{\mathit{valana} \times \mathit{tribhaguṇa}}{\mathit{paramābhujā}}$$

or,

$$R \sin SB' = \frac{R \sin SC' \times R}{R \sin B}, \tag{11}$$

$$R \sin S'B = \frac{R \sin S'C \times R}{R \sin B}. \tag{12}$$

In Figs. 1a, b, let $B'$ be the point of intersection of the ecliptic and the prime vertical. Applying the sine rule in the spherical triangle $SC'B'$, where $S\hat{C}'B' = 90$,[^13] and $\hat{B}' = \hat{B}$,[^14] we obtain

$$\sin SB' = \frac{\sin SC'}{\sin B'} = \frac{\sin SC'}{\sin B}, \tag{13}$$

which is equivalent to (11). Similarly, (12) can be obtained from the spherical triangle $S'CB$ in Figs. 2a, b.
Now, noting that the arc $S'B = 90 - SB'$,[^15] we have:

$$(R \sin SB')^2 + (R \sin S'B)^2 = (R \sin SB')^2 + (R \cos SB')^2, \tag{14}$$

and, from (11) and (12), we have:

$$\begin{aligned}
(R \sin SB')^2 &+ (R \sin S'B)^2 \\
&= \left(\frac{R \sin SC' \times R}{R \sin B}\right)^2 + \left(\frac{R \sin S'C \times R}{R \sin B}\right)^2.
\end{aligned} \tag{15}$$

Thus, from (14) and (15), we obtain

$$(R \sin B)^2 = (R \sin SC')^2 + (R \sin S'C)^2,$$

which is equivalent to (10).

### 3.4 Determining the *samalagna* from the *bhuja* and the *koṭi*

दिग्भेदसाम्यादिह बाहुकोट्योः  
     स्वर्णं भुजाचापमिने प्रकुर्यात् ।  
कोटिस्तु याम्या यदि तत्र योज्यं  
     भानाञ्च षट्कं समलग्नसिद्ध्यै ॥६६॥  
स्वर्णं भुजाकोटिदिगैक्यभेदात्  
     त्रिभान्विते भास्वति कोटिचापम् ।  
कुर्यात्तदा वा समलग्नकं स्यात्  
     सौम्ये भुजे तत्तु भषट्कयुक्तम् ॥६७॥  
> *digbhedasāmyādiha bāhukoṭyoḥ*  
> *svarṇaṃ bhujācāpamine prakuryāt |*  
> *koṭistu yāmyā yadi tatra yojyaṃ*  
> *bhānāñca ṣaṭkaṃ samalagnasiddhyai ||66||*  
> *svarṇaṃ bhujākoṭidigaikyabhedāt*  
> *tribhānvite bhāsvati koṭicāpam |*  
> *kuryāttadā vā samalagnakaṃ syāt*  
> *saumye bhuje tattu bhaṣaṭkayuktam ||67||*  
Here, one should apply the sine inverse (*cāpa*) of the *bhuja* (*bhujā*) to [the longitude of] the Sun (*ina*), positively or negatively, depending on the difference and sameness in the directions of *bhuja* (*bāhu*) and *koṭi* [with respect to the prime vertical]. If the *koṭi* is southern, six signs should be added there to obtain the *samalagna*.
Or, one should apply the sine inverse (*cāpa*) of the *koṭi* to [the longitude of] the Sun (*bhāsvat*) along with three signs, positively or negatively, depending on the sameness and difference in the directions of the *bhuja* (*bhujā*) and the *koṭi* [with respect to the prime vertical]. If the *bhuja* is northern, that has to be increased by six signs. Then [the result] would be the *samalagna*.
The above two verses give the procedure for determining the *samalagna*, or the eastern intersection of the ecliptic and prime vertical, from the quantities *bhuja* and *koṭi* computed in the previous verse. Verse 66, in the *indravajrā* metre, gives the following relations to determine the longitude ($\lambda_b$) of the *samalagna* from the longitude ($\lambda$) of the Sun and the *bhuja*:

[^13]: As noted earlier, all great circles passing through the Sun and the north and south cardinal points are perpendicular to the prime vertical.

[^14]: The angle between the prime vertical and the ecliptic at $B'$, in Figs. 1a, b, will be equal to the angle between them at their other intersection at $B$, in Figs. 2a, b, respectively.

[^15]: $B'B = 180$ and, by definition, $SS' = 90$. Thus, $SB' + S'B = 90$.
<!-- /decode-chunk -->

<!-- decode-chunk: pages=6-10 source_sha256=6b1d8450991a77ec9dd4ae981cc7e2fb667a042cd160891832f8c4abbe798cb4 -->
$$\begin{aligned}
\textit{samalagna} &= ina + c\bar{a}pa(bhuja) \\
&\quad [\textit{bhuja southern, koṭi northern}] \\
\textit{samalagna} &= ina - c\bar{a}pa(bhuja) \\
&\quad [\textit{bhuja and koṭi northern}] \\
\textit{samalagna} &= ina + c\bar{a}pa(bhuja) + bh\bar{a}n\bar{a}\d{m}\ \d{s}a\d{t}ka \\
&\quad [\textit{bhuja northern, koṭi southern}] \\
\textit{samalagna} &= ina - c\bar{a}pa(bhuja) + bh\bar{a}n\bar{a}\d{m}\ \d{s}a\d{t}ka \\
&\quad [\textit{bhuja and koṭi southern}]
\end{aligned}$$

or, with reference to Fig. 3,

$$\lambda_b = \lambda + R\sin^{-1}(bhuja) \tag{16}$$

$$[S\text{ southern, } S'\text{ northern}]$$

$$\lambda_b = \lambda - R\sin^{-1}(bhuja) \tag{17}$$

$$[S\text{ and } S'\text{ northern}]$$

$$\lambda_b = \lambda + R\sin^{-1}(bhuja) + 180 \tag{18}$$

$$[S\text{ northern, } S'\text{ southern}]$$

$$\lambda_b = \lambda - R\sin^{-1}(bhuja) + 180. \tag{19}$$

$$[S\text{ and } S'\text{ southern}]$$

Verse 67, in the *upajāti* metre, gives the following relations to determine the longitude of the *samalagna* using the *koṭi*:

$$\begin{aligned}
\textit{samalagna} &= bh\bar{a}svat + tribha + c\bar{a}pa(ko\d{t}i) \\
&\quad [\textit{bhuja and koṭi southern}] \\
\textit{samalagna} &= bh\bar{a}svat + tribha - c\bar{a}pa(ko\d{t}i) \\
&\quad [\textit{bhuja southern, koṭi northern}] \\
\textit{samalagna} &= bh\bar{a}svat + tribha + c\bar{a}pa(ko\d{t}i) + bha\d{s}a\d{t}ka \\
&\quad [\textit{bhuja and koṭi northern}] \\
\textit{samalagna} &= bh\bar{a}svat + tribha - c\bar{a}pa(ko\d{t}i) + bha\d{s}a\d{t}ka \\
&\quad [\textit{bhuja northern, koṭi southern}]
\end{aligned}$$

or, with reference to Fig. 3,

$$\lambda_b = \lambda + 90 + R\sin^{-1}(ko\d{t}i) \tag{20}$$

$$[S\text{ and } S'\text{ southern}]$$

$$\lambda_b = \lambda + 90 - R\sin^{-1}(ko\d{t}i) \tag{21}$$

$$[S\text{ southern, } S'\text{ northern}]$$

$$\lambda_b = \lambda + 90 + R\sin^{-1}(ko\d{t}i) + 180 \tag{22}$$

$$[S\text{ and } S'\text{ northern}]$$

$$\lambda_b = \lambda + 90 - R\sin^{-1}(ko\d{t}i) + 180. \tag{23}$$

$$[S\text{ northern, } S'\text{ southern}]$$

The above expressions are conditional with respect to the orientation of the *bhuja* and the *koṭi*, or equivalently, $S$ and $S'$,[^16] with respect to the prime vertical. The *bhuja* and the *koṭi*, as is evident from (11) and (12), are nothing but the Rsines of the smallest ecliptic arcs from $S$ and $S'$, respectively, to the prime vertical. Recalling, from (6), that $\lambda_{s'} = \lambda + 90$, the rationale of the above expressions can be understood with the help of Fig. 3, which depicts the four possible mutual orientations of $S$ and $S'$ with respect to the prime vertical.
In Fig. 3a, $S$ and $S'$ are on opposite sides of the prime vertical, with $S$ to the south and $S'$ to the north. In this case, the longitude ($\lambda_b$) of the *samalagna* ($B$) is evidently

$$\begin{aligned}
\lambda_b &= \Gamma B = \Gamma S + SB \\
&= \lambda + R\sin^{-1}(bhuja),
\end{aligned} \tag{24}$$

or,

$$\begin{aligned}
\lambda_b &= \Gamma B = \Gamma S' - BS' \\
&= \lambda + 90 - R\sin^{-1}(ko\d{t}i).
\end{aligned} \tag{25}$$

Thus, we obtain (16) and (21), respectively.
In Fig. 3b, $S$ and $S'$ are both to the north of the prime vertical. In this case, the longitude of the *samalagna* can be obtained as

$$\begin{aligned}
\lambda_b &= \Gamma B = \Gamma S - BS \\
&= \lambda - R\sin^{-1}(bhuja),
\end{aligned} \tag{26}$$

or,

$$\begin{aligned}
\lambda_b &= \Gamma B = \Gamma S' + S'B' + B'B \\
&= \lambda + 90 + R\sin^{-1}(ko\d{t}i) + 180.
\end{aligned} \tag{27}$$

Thus, we obtain (17) and (22), respectively.
In Fig. 3c, $S$ and $S'$ are to the north and south of the prime vertical, respectively. In this case, the longitude of the *samalagna* is given by

$$\begin{aligned}
\lambda_b &= \Gamma B = \Gamma S + SB' + B'B \\
&= \lambda + R\sin^{-1}(bhuja) + 180,
\end{aligned} \tag{28}$$

or,

$$\begin{aligned}
\lambda_b &= \Gamma B = \Gamma S' - B'S' + BB' \\
&= \lambda + 90 - R\sin^{-1}(ko\d{t}i) + 180.
\end{aligned} \tag{29}$$

Thus, we obtain (18) and (23), respectively.
Finally, in Fig. 3d, $S$ and $S'$ are both to the south of the prime vertical. In this case, the longitude of the *samalagna* is evidently

$$\begin{aligned}
\lambda_b &= \Gamma B = \Gamma S - B'S + B'B \\
&= \lambda - R\sin^{-1}(bhuja) + 180,
\end{aligned} \tag{30}$$

or,

$$\begin{aligned}
\lambda_b &= \Gamma B = \Gamma S' + S'B \\
&= \lambda + 90 + R\sin^{-1}(ko\d{t}i).
\end{aligned} \tag{31}$$

Thus, we obtain (19) and (20), respectively.

![Fig. 3. Determining the samalagna from the bhuja and the koṭi](media/p07_page.png)

*Fig. 3. Determining the samalagna from the bhuja and the koṭi*

<!-- figure-resolved-page-render: page=7 image=media/p07_page.png reason=no-extracted-figure -->

<!-- figure-meta: page=7, position=top, type=diagram -->

### 3.5 Determining the samaśaṅku and samaprabhā

समलग्नभुजाजीवा  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;परमक्रान्तिताडिता ।  
अक्षाप्ता समशङ्कुः स्यात्  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;तत्कोटिश्च समप्रभा ॥६८॥
samalagnabhujājīvā  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;paramakrāntitāḍitā |  
akṣāptā samaśaṅkuḥ syāt  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;tatkoṭiśca samaprabhā ||68||
The Rsine of the longitude of the *samalagna* multiplied by [the Rsine of] the maximum declination (*paramakrānti*) and divided by [the Rsine of] the latitude would be the *samaśaṅku*. The Rcosine of that would be the *samaprabhā*.
The above verse, in the *anuṣṭubh* metre, gives the following relations:

$$sama\acute{s}a\dot{n}ku = \frac{samalagnabhuj\bar{a}j\bar{\imath}v\bar{a} \times paramakr\bar{a}ntijy\bar{a}}{ak\d{s}ajy\bar{a}}$$

or,

$$R\sin BE = \frac{R\sin \Gamma B \times R\sin \epsilon}{R\sin \phi}, \tag{32}$$

and

$$samaprabh\bar{a} = R\cos BE. \tag{33}$$

The *samaśaṅku* is the perpendicular dropped from the *samalagna* onto the plane of the horizon. Thus, it corresponds to the Rsine of the arc $BE$ in Figs. 2a, b, or the semi-chord $BX$ depicted in Fig. 4, which gives a perspective of Fig. 2b from the south ($So$).
The measure of this perpendicular can be derived from the spherical triangle $\Gamma BE$, where $\Gamma B = \textit{samalagna}$ (derived in the previous verse), $\Gamma\hat{E}B = \phi$,[^17] and $B\hat{\Gamma}E = \epsilon$. Applying the sine rule in this triangle, we obtain

$$\sin BE = \frac{\sin \Gamma B \times \sin \epsilon}{\sin \phi},$$

which is equivalent to (32). The corresponding cosine, $OX = R\cos BE$ in Fig. 4, is stated to be the *samaprabhā*.

![Fig. 4. Visualising the samaśaṅku](media/p08_page.png)

*Fig. 4. Visualising the samaśaṅku*

<!-- figure-resolved-page-render: page=8 image=media/p08_page.png reason=no-extracted-figure -->

<!-- figure-meta: page=8, position=top, type=diagram -->

### 3.6 Determining the samadṛggati

त्रिज्यान्त्यबाह्वोः कृतिभेदमूलं  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;कोटिस्तदभ्यस्तसमप्रभायाः ।  
त्रिजीवयाप्ता समदृग्गतिस्स्यात्  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;एषात्र दृक्क्षेपविपर्ययाशा ॥६९॥
trijyāntyabāhvoḥ kṛtibhedamūlaṃ  
&nbsp;&nbsp;koṭistadabhyastasamaprabhāyāḥ |  
trijīvayāptā samadṛggatissyāt  
&nbsp;&nbsp;eṣātra dṛkkṣepaviparyayāśā ||69||
The squareroot of the difference of the squares of the radius (*trijyā*) and the *paramā bhujā* (*antyabāhu*) is the *koṭi*. The quotient obtained from the division of the product of that [*koṭi*] and the *samaprabhā* by the radius (*trijīvā*) would be the *samadṛggati*. This here will be opposite in direction (*āśā*) to the *dṛkkṣepa*.
The above verse, in the *upajāti* metre, gives the following relations:

$$ko\d{t}i = \sqrt{(trijy\bar{a})^2 - (param\bar{a}\ bhuj\bar{a})^2},$$

or,

$$R\cos B = \sqrt{R^2 - (R\sin B)^2}, \tag{34}$$

and,

$$samad\d{r}ggati = \frac{ko\d{t}i \times samaprabh\bar{a}}{trij\bar{\imath}v\bar{a}},$$

or,

$$R\cos ZG = \frac{R\cos B \times R\cos BE}{R}. \tag{35}$$

The term *antyabāhu* in the verse is a synonym for *paramā bhujā* ($R\sin B$), defined in verse 65 as (10). The *koṭi* described in this verse refers to the corresponding cosine ($R\cos B$), and (34) simply states the well known identity involving the sine and cosine of an arc. It may be noted that the *koṭi* of (34) is distinct from that of (12).
The *samadṛggati* in (35) refers to the measure of the perpendicular dropped onto the horizon from a point on the ecliptic which is $90^\circ$ behind the *samalagna* ($B$). Let this point be $G$ in Fig. 4. Thus, the *samadṛggati* will be the measure of the Rsine of the arc $GG'$. However, since $GG' = 90 - ZG$, we have the

$$samad\d{r}ggati = R\sin GG' = R\cos ZG.$$

Now, in the spherical triangle $ZGB$, we have $GB = 90$ (by definition), $ZB = 90 - BE$ and, from (34), $\cos B = ko\d{t}i$. Employing the cosine rule, we have

$$\cos ZG = \sin ZB \cos B = \cos BE \cos B,$$

which is equivalent to (35).
The last quarter of the verse states that the *samadṛggati* is opposite in direction to the *dṛkkṣepa*. This statement can be understood with the help of Fig. 5, which depicts the positions of the ecliptic points corresponding to the *samalagna* ($B$), *samadṛggati* ($G$) and the *dṛkkṣepa* ($D$) as the *kālalagna* cycles through the four quadrants over the course of the day.
Figures 5a, b depict the situation when the *kālalagna* is in the first and the second quadrants, respectively. In these two cases, the rising ecliptic point ($L$), i.e., the *udayalagna*, lies to the north of the east cardinal point, and the setting ecliptic point ($L'$), i.e., the *astalagna*, lies to the south of the west cardinal point. Thus, the *dṛkkṣepalagna* ($D$), which is equidistant between the rising the setting ecliptic points,[^18] lies in the eastern hemisphere. On the other hand, the eastern intersection ($B$) of the ecliptic and the prime vertical, i.e., the *samalagna*, lies above the horizon, and the western intersection ($B'$) lies below the horizon. Thus, the ecliptic point corresponding to the *samadṛggati* ($G$), which is equidistant between $B$ and $B'$, lies in the western hemisphere.[^19]
Figures 5c, d depict the situation when the *kālalagna* is in the third and the fourth quadrants, respectively. In these two cases, the rising ecliptic point ($L$) lies to the south of the east cardinal point, and the setting ecliptic point ($L'$) lies to the north of the west cardinal point. Thus, the *dṛkkṣepalagna* ($D$) lies in the western hemisphere. On the other hand, the eastern intersection ($B$) of the ecliptic and the prime vertical lies below the horizon, and the western intersection ($B'$) lies above the horizon. Thus, the *samadṛggati* lies in the eastern hemisphere.
Hence, it is observed that the ecliptic points corresponding to the *samadṛggati* and the *dṛkkṣepalagna* always lie in opposite hemispheres. This is the purport of the last quarter of the verse.

## 4 Alternative method of determining the samalagna, samaśaṅku and samadṛggati

### 4.1 Outline of the procedure for determining the samalagna

गोलायनान्त्यबाहुभ्याम्  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;अथवा पूर्वमानयेत् ।  
विषुवच्चलनं तेन  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;समलग्नं समानयेत् ॥७०॥
golāyanāntyabāhubhyām  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;athavā pūrvamānayet |  
viṣuvaccalanaṃ tena  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;samalagnaṃ samānayet ||70||
Or, one should first compute the *viṣuvaccalana* using the *golāntyabāhu* and *ayanāntyabāhu*. [Thereafter], one should compute the *samalagna* by that.
The above verse, in the *anuṣṭubh* metre, outlines the procedure of computing the *samalagna*, discussed over the next six verses. This verse states that the *samalagna* can be determined from the *viṣuvaccalana*, which is the measure of the shorter arc ($< 180^\circ$) of the ecliptic between the vernal equinox and the prime vertical. The *viṣuvaccalana* in turn is to be computed from the *golāntyabāhu* and the *ayanāntyabāhu*, also referred to in the following verses as *viṣuvadbhujā* and the *ayanāntabāhu*, respectively. Once the *samalagna* has been computed in this manner, the remaining verses state the procedure for computing the *samaśaṅku*, *samadṛggati*, etc.

### 4.2 Determining the viṣuvadbhujā and ayanāntabāhu

अक्षाहता कालविलग्नदोर्ज्या  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;त्रिज्याविभक्ता विषुवद्भुजा स्यात् ।  
कोटीगुणात् कालविलग्ननीतात्  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;अक्षाहताद्व्यासदलेन लब्धम् ॥७१॥  
अन्त्यद्युजीवागुणिता त्रिमौर्व्या  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;भक्ता धनर्णं मृगकर्कटाद्योः ।  
त्रिज्याहृतेऽन्त्यापमलम्बघाते  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;कुर्यात्तदा स्यादयनान्तबाहुः ॥७२॥
akṣāhatā kālavilagnadorjyā  
trijyāvibhaktā viṣuvadbhujā syāt |  
koṭīguṇāt kālavilagnanītāt  
akṣāhatādvyāsadalena labdham ||71||  
antyadyujīvāguṇitā trimaurvyā  
bhaktā dhanarṇaṃ mṛgakarkaṭādyoḥ |  
trijyāhṛte’ntyāpamalambaghāte  
kuryāttadā syādayanāntabāhuḥ ||72||

![Fig. 5. The dṛkkṣepa (D) and the samadṛggati (G) lie in opposite hemispheres](media/p10_page.png)

*Fig. 5. The dṛkkṣepa (D) and the samadṛggati (G) lie in opposite hemispheres*

<!-- figure-resolved-page-render: page=10 image=media/p10_page.png reason=no-extracted-figure -->

<!-- figure-meta: page=10, position=top, type=diagram -->

The Rsine of the *kālalagna* (*kālavilagna*) multiplied by [the Rsine of] the latitude (*akṣa*) and divided by the radius (*trijyā*) would be the *viṣuvadbhujā*. One should apply the quotient obtained from the division of the product of the Rcosine computed from the *kālalagna* (*kālavilagna*) and [the Rsine of] the latitude (*akṣa*) by the semi-diameter (*vyāsadala*), which is multiplied by the last day-radius (*antyadyujīvā*) and divided by the radius (*trimaurvī*), positively [when the *kālalagna* is] in [the six signs] Capricorn (*mṛga*) etc., and negatively [when the *kālalagna* is] in [the six signs] Cancer (*karkaṭa*) etc., to the product of [the Rsine of] the maximum declination (*antyāpama*) and [the Rsine of] the co-latitude (*lamba*) divided by the radius (*trijyā*). Then [the result] would be the *ayanāntabāhu*.
The above verses, in the *indravajrā* metre, give the following relations:

$$vi\d{s}uvadbhuj\bar{a} = \left| \frac{k\bar{a}lavilagnadorjy\bar{a} \times ak\d{s}ajy\bar{a}}{trijy\bar{a}} \right|,$$

or, with reference to Figs. 1a, b,

$$R\sin \Gamma F = R\sin \Omega F' = \left| \frac{R\sin \alpha_e \times R\sin \phi}{R} \right|, \tag{36}$$

and,

[^16]: From (11) and (12), it is evident that the *bhuja* and the *koṭi* are the Rsines of the ecliptic arcs $SB'$ and $S'B$, respectively. As $B$ and $B'$ represent the intersections of the prime vertical and the ecliptic, the northern and southern orientation of the aforementioned arcs, and their Rsines, with respect to the prime vertical, is equivalent to the orientation of $S$ and $S'$ with respect to the prime vertical. See Fig. 3 and our discussion below.

[^17]: This is the angle between the celestial equator and the prime vertical. This can be visualised with the help of Fig. 2b, where the angle between the prime vertical and the celestial equator is equal to the arc $ZT = PN = \phi$, as the arcs $NZ = PT = 90$.

[^18]: It may be recalled from (14) in Kolachana et al. (2019b) that the *udayalagna* and the *dṛkkṣepalagna* are $90^\circ$ apart on the ecliptic. It may also be recalled that the perpendicular dropped onto the horizon from the *dṛkkṣepalagna* is known as the *dṛkkṣepakoṭikā* or the *paraśaṅku*. The zenith distance of the *dṛkkṣepalagna* is known as the *dṛkkṣepajyā*.

[^19]: It may be recalled from our discussion above that the *samalagna* and the ecliptic point corresponding to the *samadṛggati* are $90^\circ$ apart on the ecliptic.
<!-- /decode-chunk -->

<!-- decode-chunk: pages=11-15 source_sha256=b359b0132a5b298954d525bb4f27dc499f08127aa18f9cf6476010c825dadfc0 -->
or, again with reference to Figs. 1a, b,

$$
ayanāntabāhu = \frac{antyāpamajyā \times lambajyā}{trijyā} \pm \frac{\left| \frac{kālavilagnakoṭīguṇa \times akṣajyā}{vyāsadala} \times antyadyujīvā \right|}{trimaurvī},

$$

$$
R \sin HJ = R \sin H' J' = \frac{R \sin \epsilon \times R \cos \phi}{R} \pm \frac{\left| \frac{R \cos \alpha_e \times R \sin \phi}{R} \times R \cos \epsilon \right|}{R}. \tag{37}

$$
The verse further states that the second term in (37) is to be applied positively when the *kālalagna* is in the fourth and the first quadrants (*mṛgādi*), and negatively when it is in the second and the third quadrants (*karkaṭādi*).
In Fig. 2b, the ecliptic points $\Gamma$ and $H$ correspond to the vernal equinox and the summer solstice, respectively. $\Gamma F$ is an arc of the great circle passing through the equinoxes and the north and south cardinal points, which is perpendicular to the prime vertical $ZE$ at $F$.[^20] Similarly, $HJ$ is an arc of the great circle passing through the solstices and the north and south cardinal points, perpendicular to the prime vertical at $J$.
Now, in spherical triangle $F\Gamma E$, $\Gamma E = \alpha_e$,[^21] $\hat{F} = 90$, and $\hat{E} = \phi$.[^22] Applying the sine rule, we obtain the magnitude of

$$
\sin \Gamma F = |\sin \alpha_e \times \sin \phi|, \tag{38}

$$
which is equivalent to (36).
In spherical triangle $PHN$, $PN = \phi$, $PH = 90 - \epsilon$,[^23] and $\hat{P} = \alpha_e$.[^24] Applying the cosine rule, we have

$$
\cos HN = \sin \epsilon \cos \phi + \cos \epsilon \sin \phi \cos \alpha_e.

$$
As $HJ = 90 - HN$, we have

$$
\sin HJ = \sin \epsilon \cos \phi \pm |\cos \epsilon \sin \phi \cos \alpha_e|, \tag{39}

$$
which is equivalent to (37). It may be noted that both $\epsilon$ and $\phi$ lie in the range $0^\circ$ to $90^\circ$. Therefore, the sine and cosine of these two quantities will always be positive. However, $\alpha_e$ can vary from $0^\circ$ to $360^\circ$. Thus, in the above expression, $\cos \alpha_e$ will be positive in first and fourth quadrants, and negative in the second and third quadrants. Hence, the verse states that the second term in (39) should be applied positively and negatively in the six signs from *mṛga* ($270^\circ$ to $90^\circ$) and *karkaṭa* ($90^\circ$ to $270^\circ$), respectively.
The given expressions can also be derived with the help of Fig. 1a. In this figure, the ecliptic points $\Omega$ and $H'$ correspond to the autumnal equinox and the winter solstice, respectively. $\Omega F'$ is an arc of the great circle passing through the equinoxes and the north and south cardinal points, which is perpendicular to the prime vertical $ZW$ at $F'$. Similarly, $H' J'$ is an arc of the great circle passing through the solstices and the north and south cardinal points, perpendicular to the prime vertical at $J'$. In spherical triangle $F'\Omega W$, $\Omega W = 360 - \alpha_e$,[^25] $\hat{F}' = 90$, and $\hat{W} = \phi$.[^26] Applying the sine rule, we obtain the magnitude of

$$
\sin \Omega F' = |\sin \alpha_e \times \sin \phi|, \tag{40}

$$
which is equivalent to (36).
In spherical triangle $PH' N$, $PN = \phi$, $PH' = 90 - \epsilon$,[^27] and $\hat{P} = 360 - \alpha_e$.[^28] Applying the cosine rule, we have

$$
\cos H' N = \sin \epsilon \cos \phi + \cos \epsilon \sin \phi \cos \alpha_e.

$$
As $H' J' = 90 - H' N$, we have

$$
\sin H' J' = \sin \epsilon \cos \phi \pm |\cos \epsilon \sin \phi \cos \alpha_e|, \tag{41}

$$
which is equivalent to (37).

## 4.3 Determining the paramā bhujā

तद्वर्गगयुुक्तााद्विषुुवद्भुजााु याःः
     वर्गाात् पदंंवाा परमाा भुुजााप्ताा ।[^29]
समााख्यवृृत्ताापमवृृत्तयोोस्साा
     पराान्तराालोोद्भवशिञ्जिनीी स्याात् ॥७३॥
*tadvargayuktādviṣuvadbhujāyāḥ*
   *vargāt padaṃ vā paramā bhujāptā |*
*samākhyavṛttāpamavṛttayossā*
   *parāntarālodbhavaśiñjinī syāt ||73||*
Or, the *paramā bhujā* is the square root obtained from the square of the *viṣuvadbhujā* which has been added by the square of that [*ayanāntabāhu*]. That would be the Rsine arising from the maximum separation of the prime vertical (*samākhyavṛtta*) and the ecliptic (*apamavṛtta*).
The above verse, in the *upajāti* metre, gives another relation for the *paramā bhujā*, earlier discussed in verse 65:

$$
paramābhujā = \sqrt{(viṣuvadbhuja)^2 + (ayanāntabāhu)^2},

$$
or, with reference to Figs. 1a, b,

$$
\begin{aligned}
R \sin B = R \sin B' &= \sqrt{(R \sin \Gamma F)^2 + (R \sin HJ)^2} \\
&= \sqrt{(R \sin \Omega F')^2 + (R \sin H'J')^2}.
\end{aligned} \tag{42}

$$
In Fig. 2b, in spherical triangles $B \Gamma F$ and $BHJ$, where $\hat{F} = \hat{J} = 90$, it is evident that

$$
\sin \Gamma B = \frac{\sin \Gamma F}{\sin B}, \text{ and, } \sin BH = \frac{\sin HJ}{\sin B}.

$$
Noting that the arc $\Gamma H = \Gamma B + BH = 90$, as $H$ is the solstitial point, we have

$$
(\sin \Gamma B)^2 + (\sin BH)^2 = \left( \frac{\sin \Gamma F}{\sin B} \right)^2 + \left( \frac{\sin HJ}{\sin B} \right)^2,

$$
or,

$$
\sin B = \sqrt{(\sin \Gamma F)^2 + (\sin HJ)^2},

$$
which is equivalent to (42). The two terms on the right in the above expression, corresponding to the *viṣuvadbhujā* and the *ayanāntabāhu*, are obtained from (36) and (37), respectively, where from we also obtain the second expression in (42):[^30]

$$
\sin B = \sin B' = \sqrt{(\sin \Omega F')^2 + (\sin H'J')^2},

$$
corresponding to Fig. 1a.
The second half of the verse states that the *paramā bhujā* is the Rsine which corresponds to the maximum separation between the prime vertical and the ecliptic. This can be understood with the help of Fig. 6, which is the same as Fig. 4, but is rotated about its axis, and depicts the celestial sphere from the perspective of the plane of the prime vertical, for ease of visualisation. The maximum separation between any two great circles on a celestial sphere occurs $90^\circ$ from their point of intersection. In Fig. 6, the prime vertical and the ecliptic intersect at $B$, and given $BG = BG'' = 90$, their maximum separation is denoted by the line segment $GA = R \sin GG'' = R \sin B$. In this text, this quantity has been appropriately termed as the *paramā bhujā*, or the maximum *bhujā*, with its measure given by (10), (42) and (60).

## 4.4 Determining the viṣuvaccalana

विषुुवद्भुजतु स्त्रिगुुणााभिहताात्
     अमुुयााप्तधनुुर्वििषुुवच्चलनम् ।
भगणाार्धधवि शुद्धिरमुुष्य भवेेत्
     अयनाान्तभुुजेेसति कर्कििमुुखेे॥७४॥
अथवाा मृृगकर्ककटकाादिवशाात्
     अयनाान्तभुुजाा त्रिगुुणेेन हताात् ।
परयाा भुुजयााप्तधनुःः क्रमशःः
     त्रिभहीीनयुुतंंविषुुवच्चलनम् ॥७५॥
*viṣuvadbhujatastriguṇābhihatāt*
*amuyāptadhanurviṣuvaccalanam |*
*bhagaṇārdhaviśuddhiramuṣya bhavet*
*ayanāntabhuje sati karkimukhe ||74||*
*athavā mṛgakarkaṭakādivaśāt*
*ayanāntabhujā triguṇena hatāt |*
*parayā bhujayāptadhanuḥ kramaśaḥ*
*tribhahīnayutaṃ viṣuvaccalanam ||75||*
The arc (*dhanuḥ*) of the quotient obtained from the division of the product of the *viṣuvadbhujā* (*viṣuvadbhuja*) and the radius (*triguṇa*) by this [*paramā bhujā*] is the *viṣuvaccalana*. One should subtract this [arc] from half a revolution (*bhagaṇārdha*) if the *ayanāntabāhu* (*ayanāntabhuja*) is [within six signs] beginning with Cancer (*karki*).
Or, depending on [whether the *ayanāntabāhu* is within six signs] beginning with Capricorn (*mṛga*) or Cancer (*karkaṭaka*), the arc of the quotient obtained from the division of the product of the *ayanāntabāhu* (*ayanāntabhujā*) and the radius (*triguṇa*) by the *paramā bhujā* (*parā bhujā*), subtracted from or added to three signs, respectively, would be the *viṣuvaccalana*.
The above two verses, in the *toṭaka* metre, give two different procedures for determining the *viṣuvaccalana*, which is the shortest arc ($\Gamma B_{min}$) along the ecliptic between the vernal equinox ($\Gamma$) and the *samalagna* ($B$).[^31] Verse 74 gives the following relations:
*viṣuvaccalana*
$= dhanuṣ \left( \frac{viṣuvadbhuja \times triguṇa}{paramābhujā} \right)$
[*ayanāntabāhu in mṛgādi*]
*viṣuvaccalana*
$= bhagaṇārdha - dhanuṣ \left( \frac{viṣuvadbhuja \times triguṇa}{paramābhujā} \right)$
[*ayanāntabāhu in karkaṭādi*]
or,

$$
\Gamma B_{min} = R \sin^{-1} \left( \frac{R \sin \Gamma F \times R}{R \sin B} \right) \tag{43}

$$
$[270 < \alpha_e < 90]$

$$
\Gamma B_{min} = 180 - R \sin^{-1} \left( \frac{R \sin \Gamma F \times R}{R \sin B} \right). \tag{44}

$$
$[90 < \alpha_e < 270]$
Verse 75 presents the following alternative procedure for determining the *viṣuvaccalana*:
*viṣuvaccalana*
$= tribha - dhanuṣ \left( \frac{ayanāntabāhu \times triguṇa}{paramābhujā} \right)$
[*ayanāntabāhu in mṛgādi*]
*viṣuvaccalana*
$= tribha + dhanuṣ \left( \frac{ayanāntabāhu \times triguṇa}{paramābhujā} \right)$
[*ayanāntabāhu in karkaṭādi*]
or,

$$
\Gamma B_{min} = 90 - R \sin^{-1} \left( \frac{R \sin HJ \times R}{R \sin B} \right) \tag{45}

$$
$[270 < \alpha_e < 90]$

$$
\Gamma B_{min} = 90 + R \sin^{-1} \left( \frac{R \sin HJ \times R}{R \sin B} \right). \tag{46}

$$
$[90 < \alpha_e < 270]$
All the above relations for the computation of the *viṣuvaccalana* are conditional upon the presence of *ayanāntabāhu* in *mṛgādi* ($270^\circ$ to $90^\circ$) or *karkaṭādi* ($90^\circ$ to $270^\circ$). As we have noted in our discussion of verse 72, the second term in the expression for the *ayanāntabāhu* in (37) is applied positively or negatively depending upon whether the *kālalagna* is in the first and fourth quadrants, or the second and third quadrants, respectively. Thus, the given relations are to be understood to be conditional upon the quadrant in which the *kālalagna* is present.

![Fig. 6. Visualising the paramā bhujā](media/p13_page.png)

*Fig. 6. Visualising the paramā bhujā*

<!-- figure-resolved-page-render: page=13 image=media/p13_page.png -->

<!-- figure-meta: page=13, position=top, type=diagram -->

In Fig. 2b, in the spherical triangle $\Gamma FB$, we have $\hat{F} = 90$.[^32] Now, applying the sine rule, we obtain

$$
\Gamma B_{min} = \Gamma B = \sin^{-1} \left( \frac{\sin \Gamma F}{\sin B} \right), \tag{47}

$$
which is equivalent to (43). It may be noted that in this figure, the *kālalagna* ($\Gamma E = \alpha_e$) is in the first quadrant, i.e., $0 < \alpha_e < 90$.
The measure of the *viṣuvaccalana* when the *kālalagna* is in other quadrants can be understood with the help of Fig. 7. This figure depicts four instances when the *kālalagna* is in four different quadrants. Fig. 7a depicts the *kālalagna* in the first quadrant, like Fig. 2b.
In Fig. 7b, the *kālalagna* is in the second quadrant and the magnitude of the arc $B'\Gamma$ (in the west) is equal to (47). Here, the shortest arc between $\Gamma$ and $B$ is above the horizon and is given by

$$
\begin{aligned}
\Gamma B_{min} = \Gamma B &= B' B - B' \Gamma \\
&= 180 - \sin^{-1} \left( \frac{\sin \Gamma F}{\sin B} \right),
\end{aligned} \tag{48}

$$
which is equivalent to (44).
In Fig. 7c, the *kālalagna* is in the third quadrant and the magnitude of the arc $\Gamma B'$ (in the west) is equal to (47). Here, the shortest arc between $\Gamma$ and $B$ is below the horizon and is given by

$$
\begin{aligned}
\Gamma B_{min} = B\Gamma &= BB' - \Gamma B' \\
&= 180 - \sin^{-1} \left( \frac{\sin \Gamma F}{\sin B} \right),
\end{aligned} \tag{49}

$$
which is equivalent to (44).
Finally, in Fig. 7d, the *kālalagna* is in the fourth quadrant and the magnitude of the arc $B\Gamma$ (in the east) is equal to (47). This is the shortest arc between $\Gamma$ and $B$, and thus

$$
\Gamma B_{min} = B\Gamma = \sin^{-1} \left( \frac{\sin \Gamma F}{\sin B} \right), \tag{50}

$$
which is equivalent to (43).
The second set of relations given by (45) and (46) can be derived in a similar way. Here, again, the conditions regarding the presence of *ayanāntabāhu* in *mṛgādi* and *karkaṭādi* are to be understood to pertain to the *kālalagna*.
In Fig. 2b, in the spherical triangle $BHJ$, we have $\hat{J} = 90$.[^33] Applying the sine rule, we obtain

$$
BH = \sin^{-1} \left( \frac{\sin HJ}{\sin B} \right). \tag{51}

$$
Now, noting that $H$ is the solstitial point, and thus $\Gamma H = 90$, we have

$$
\begin{aligned}
\Gamma B_{min} = \Gamma B &= \Gamma H - BH \\
&= 90 - \sin^{-1} \left( \frac{\sin HJ}{\sin B} \right),
\end{aligned} \tag{52}

$$
which is equivalent to (45). It may be noted that in this figure, the *kālalagna* ($\Gamma E = \alpha_e$) is in the first quadrant, i.e., $0 < \alpha_e < 90$.
The measure of the *viṣuvaccalana* when the *kālalagna* is in other quadrants can be understood with the help of Fig. 7. As already noted, Fig. 7a depicts the *kālalagna* in the first quadrant, like Fig. 2b.
In Fig. 7b, the *kālalagna* is in the second quadrant and the magnitude of the arc $HB$ (in the east) is equal to (51). Here, the shortest arc between $\Gamma$ and $B$ is above the horizon and is given by

$$
\begin{aligned}
\Gamma B_{min} = \Gamma B &= \Gamma H + HB \\
&= 90 + \sin^{-1} \left( \frac{\sin HJ}{\sin B} \right),
\end{aligned} \tag{53}

$$
which is equivalent to (46).
In Fig. 7c, the *kālalagna* is in the third quadrant and the magnitude of the arc $BH'$ (in the east) is equal to (51). Here, the shortest arc between $\Gamma$ and $B$ is below the horizon and is given by

$$
\begin{aligned}
\Gamma B_{min} = B\Gamma &= BH' + H'\Gamma \\
&= 90 + \sin^{-1} \left( \frac{\sin HJ}{\sin B} \right),
\end{aligned} \tag{54}

$$
which is equivalent to (46).
Finally, in Fig. 7d, the *kālalagna* is in the fourth quadrant and the magnitude of the arc $H'B$ (in the east) is equal to (51). Here, the shortest arc between $\Gamma$ and $B$ is given

$$
\begin{aligned}
\Gamma B_{min} = B\Gamma &= H'\Gamma - H'B \\
&= 90 - \sin^{-1} \left( \frac{\sin HJ}{\sin B} \right),
\end{aligned} \tag{55}

$$
which is equivalent to (45).

## 4.5 Determining the samalagna

तदेेव समलग्नंंस्याात्
     मेेषाादौौ कााललग्नकेे ।
तुुलाादौौ तद्वि शुद्धस्य
     चक्रस्य समलग्नताा ॥७६॥
*tadeva samalagnaṃ syāt*
   *meṣādau kālalagnake |*
*tulādau tadviśuddhasya*
   *cakrasya samalagnatā ||76||*
That [*viṣuvaccalana*] itself would be *samalagna* when the *kālalagna* is in [the six signs] Aries (*meṣa*) etc. That [*viṣuvaccalana*] subtracted from a circle (*cakra*) would be the *samalagna* when the *kālalagna* is in [the six signs] Libra (*tula*) etc.
The above verse, in the *anuṣṭubh* metre, gives the following rules for determining the *samalagna* from the *viṣuvaccalana*:
*samalagna* = *viṣuvaccalana*
[*kālalagna in meṣādi*]
*samalagna* = *cakra* $-$ *viṣuvaccalana*
[*kālalagna in tulādi*]
or,

$$
\lambda_b = \Gamma B_{min} \quad [0 < \alpha_e < 180] \tag{56}

$$

$$
\lambda_b = 360 - \Gamma B_{min} \quad [180 < \alpha_e < 360]. \tag{57}

$$
The above relations for the *samalagna* are conditional upon the *kālalagna* being *meṣādi* ($0^\circ$ to $180^\circ$) or *tulādi* ($180^\circ$ to $360^\circ$). The validity of these relations can be readily seen from Fig. 7, which depicts the *kālalagna* in four different quadrants. In Figs. 7a, b, the *kālalagna* is in the first and second quadrants, and it can be seen that the longitude of the *samalagna*, is given by

$$
\lambda_b = \Gamma B = \Gamma B_{min}, \tag{58}

$$
where $\Gamma B_{min}$ is determined using the appropriate expressions from (43)–(46). When the *kālalagna* is in the first quadrant, $\Gamma B_{min}$ is to be computed using (43) or (45), and when the *kālalagna* is in the second quadrant, $\Gamma B_{min}$ is to be computed using (44) or (46).
When the *kālalagna* is in the third and fourth quadrants, as depicted in Figs. 7c, d, it can be seen that the longitude of the *samalagna* is given by

$$
\lambda_b = \Gamma B = 360 - B\Gamma = 360 - \Gamma B_{min}, \tag{59}

$$
where $\Gamma B_{min}$ is determined using the appropriate expressions from (43)–(46). When the *kālalagna* is in the third quadrant, $\Gamma B_{min}$ is to be computed using (44) or (46), and when the *kālalagna* is in the fourth quadrant, $\Gamma B_{min}$ is to be computed using (43) or (45).

![Fig. 7. Visualising the viṣuvaccalana when kālalagna is in different quadrants](media/p15_page.png)

*Fig. 7. Visualising the viṣuvaccalana when kālalagna is in different quadrants*

<!-- figure-resolved-page-render: page=15 image=media/p15_page.png -->

<!-- figure-meta: page=15, position=top, type=diagram -->

## 4.6 Determining the paramā bhujā

कााललग्नभुुजोोत्पन्न-
     क्राान्तिदृक्क्षेेपजीीवयोःः ।
वर्गगसंंयोोगमूूलंंवाा
     कथिताा परमाा भुुजाा ॥७७॥
*kālalagnabhujotpanna-*
      *krāntidṛkkṣepajīvayoḥ |*
*vargasaṃyogamūlaṃ vā*
      *kathitā paramā bhujā ||77||*
***

[^20]: See footnote 7.

[^21]: This is the *kālalagna*. See Kolachana et al. (2019a).

[^22]: See footnote 17.

[^23]: As $H$ is the solstitial point, we have $\Gamma H = \Gamma I = 90$. Thus, $HI = H \hat{\Gamma} I = \epsilon$ and $PH = 90 - \epsilon$.

[^24]: We have $EP \hat{I} = EI = \Gamma I - \Gamma E = 90 - \alpha_e$. Also, $EP \hat{N} = 90$ as $E$ is the pole of the observer’s meridian. Thus, $HP \hat{N} = EP \hat{N} - EP \hat{I} = \alpha_e$.

[^25]: $\Omega W = 180 - \Omega E = 180 - (\Gamma E - 180) = 360 - \alpha_e$.

[^26]: See footnote 17.

[^27]: As $H'$ is the solstitial point, we have $\Omega H' = \Omega I' = 90$. Thus, $H' I' = H' \hat{\Omega} I' = \epsilon$ and $PH' = 90 - \epsilon$.

[^28]: We have $W P \hat{I}' = WI' = \Omega I' - \Omega W = 90 - (360 - \alpha_e) = \alpha_e - 270$. Also, $W P \hat{N} = 90$ as $W$ is the pole of the observer’s meridian. Thus, $H' P \hat{N} = W P \hat{N} - W P \hat{I}' = 360 - \alpha_e$.

[^29]: अत्र परमाा भुुजाा इति व्यस्तेेपदेेग्रााह्येे। अन्यथाा छन्दोोवि च्छित्तिःः स्याात्। यद्यपि आप्ताा इत्यनेने विभज्यााप्ताा इति अर्थःः साामाान्यतोो गृह्यतेृ े तथााप्यत्र लब्धाा इति अर्थःः एव इष्टःः।

[^30]: Note that the angle between the ecliptic and prime vertical will be equal at their two points of intersection at $B$ and $B'$.

[^31]: Note that the *samalagna* is the eastern intersection of the ecliptic and the prime vertical.

[^32]: Recall that the arc $\Gamma F$ is part of the great circle passing through the equinoxes and the north and south cardinal points, which is perpendicular to the prime vertical.

[^33]: Recall that the arc $HJ$ is part of the great circle passing through the solstices and the north and south cardinal points, which is perpendicular to the prime vertical.
<!-- /decode-chunk -->

<!-- decode-chunk: pages=16-18 source_sha256=5da7d8e9a718b1e06b903dc91db57220fed3a566496a0db2665747eccd5a6f05 -->
*kālalagnabhujotpanna-*<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*krāntidṛkkṣepajīvayoḥ |*<br/>
*vargasaṃyogamūlaṃ vā*<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*kathitā paramā bhujā ||77||*
Or, the square root of the sum of squares of the Rsines of the *kālalagnabhujotpannakrānti* and the *dṛkkṣepa*, is stated to be the *paramā bhujā*.
The above verse, in the *anuṣṭubh* metre, gives the following relation:

$$\textit{paramā bhujā} = \sqrt{(\textit{kālalagnabhujotpannakrāntijīvā})^2 + (\textit{dṛkkṣepajīvā})^2},$$

or,

$$R \sin B = \sqrt{(R \sin \alpha_e \sin \epsilon)^2 + (R \sin z_d)^2}. \tag{60}$$

The term *kālalagnabhujotpannakrāntijīvā* in the verse is an interesting and fairly long compound which involves a few familiar terms such as *kālalagna*, *krānti* and *jīvā*. The phrase *krāntijīvā* refers to the Rsine of the *krānti* or declination, the standard relation for which is $R \sin \lambda \sin \epsilon$. The expression *kālalagnabhujotpannakrāntijīvā* is to be understood as the Rsine of the ‘declination’ obtained from the *kālalagna*, or $R \sin \alpha_e \sin \epsilon$.[^34]
The relation given in the above verse can be understood with the help of Fig. 8. This figure depicts the celestial sphere from the perspective of the eastern horizon, and shows the *dṛkkṣepalagna* ($D$) or the nonagesimal and the *samalagna* ($B$). In the spherical triangle $\Gamma B E$, we have $\Gamma E = \alpha_e$, $B \hat{\Gamma} E = \epsilon$ and $\Gamma \hat{B} E = 180 - \Gamma \hat{B} Z = 180 - B$. Using the sine rule, we obtain:

$$\sin B E = \frac{\sin \alpha_e \sin \epsilon}{\sin B}. \tag{61}$$

In the spherical triangle $ZDB$, the zenith distance of the *dṛkkṣepalagna* is $ZD = z_d$, $Z\hat{D}B = 90$,[^35] and the arc $ZB = 90 - BE$. Applying the sine rule, we obtain:

$$\cos B E = \sin ZB = \frac{\sin z_d}{\sin B}. \tag{62}$$

Squaring and summing (61) and (62), we obtain

$$\sin B = \sqrt{(\sin \alpha_e \sin \epsilon)^2 + (\sin z_d)^2},$$

which is the same as (60).

### 4.7 Determining the *samaśaṅku* and the *samaprabhā*

काललग्नभुजाक्रान्ति-<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;दृक्क्षेपौ त्रिज्यया हतौ ।<br/>
परया भुजया भक्तौ<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;समशङ्कुप्रभे क्रमात् ॥७८॥
*kālalagnabhujākrānti-*<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*dṛkkṣepau trijyayā hatau |*<br/>
*parayā bhujayā bhaktau*<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*samaśaṅkuprabhe kramāt ||78||*
[The Rsines of] the *kālalagnabhujākrānti* and the *dṛkkṣepa* [separately] multiplied by the radius (*trijyā*) and divided by the *paramā bhujā* (*parā bhujā*) would be the *samaśaṅku* and *samaprabhā*, respectively.
The above verse, in the *anuṣṭubh* metre, gives the following relations:

$$\textit{samaśaṅku} = \frac{\textit{kālalagnabhujākrāntijyā} \times \textit{trijyā}}{\textit{paramābhujā}},$$

$$\textit{samaprabhā} = \frac{\textit{dṛkkṣepajyā} \times \textit{trijyā}}{\textit{paramābhujā}},$$

or,[^36]

$$R \sin BE = \frac{R \sin \alpha_e \sin \epsilon \times R}{R \sin B}, \tag{63}$$

$$R \cos BE = \frac{R \sin z_d \times R}{R \sin B}. \tag{64}$$

The above two relations are identical to (61) and (62), which we have derived in our discussion of the previous verse. It may be recalled[^37] that the *samaśaṅku* is the perpendicular dropped from the *samalagna* onto the plane of the horizon, corresponding to the line segment $BX = R \sin BE$ in Fig. 4, while the *samaprabhā* is the corresponding cosine $OX = R \cos BE$.
---

![Fig. 8. Schematic representation of spherical triangles necessary for computing paramā bhujā, samaśaṅku, samaprabhā and samadṛggati](media/p17_page.png)

*Fig. 8. Schematic representation of spherical triangles necessary for computing paramā bhujā, samaśaṅku, samaprabhā and samadṛggati*

<!-- figure-resolved-page-render: page=17 image=media/p17_page.png reason=no-extracted-figure -->

<!-- figure-meta: page=17, position=top, type=diagram -->

### 4.8 Determining the *samadṛggati*

दृक्क्षेपसमभावर्ग-<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;विश्लेषस्य पदं भवेत् ।<br/>
समदृग्गतिरत्रैषा<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;दृक्क्षेपविपरीतदिक् ॥७९॥
*dṛkkṣepasamabhāvarga-*<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*viśleṣasya padaṃ bhavet |*<br/>
*samadṛggatiratraiṣā*<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*dṛkkṣepaviparītadik ||79||*
The square root of the difference of the squares of [the Rsine of] the *dṛkkṣepa* and the *samaprabhā* (*samabhā*) would be the *samadṛggati*. This here will be opposite in direction to the *dṛkkṣepa*.
The above verse, in the *anuṣṭubh* metre, gives the following relation:

$$\textit{samadṛggati} = \sqrt{(\textit{dṛkkṣepajyā})^2 - (\textit{samaprabhā})^2}$$

or, with reference to Figs. 4 and 8,

$$R \cos ZG = \sqrt{|(R \sin z_d)^2 - (R \cos BE)^2|}. \tag{65}$$

Substituting for $R \sin z_d$ from (64), the RHS of (65) reduces to

$$R \cos ZG = \frac{R \cos B \times R \cos BE}{R},$$

which is the same expression for the *samadṛggati* given in verse 69, stated in (35). The derivation of this expression has been addressed in our discussion there.
The verse further states that the *samadṛggati* is opposite in direction to the *dṛkkṣepa*. A similar assertion has been made earlier in verse 69, and its significance and validity have been addressed in our discussion there.

## 5 Discussion

In a previous paper,[^38] we have detailed the contents of the third chapter of the *Lagnaprakaraṇa*, which discusses the procedure for computing the ascendant using the *śaṅku* and *dṛggati* corresponding to any ecliptic point. In this paper, we have elaborated upon the contents of verses 62–79 of the *Lagnaprakaraṇa*, corresponding to its fourth chapter, which describes the procedure for computing the *samaśaṅku* and *samadṛggati*, which are the *śaṅku* and *dṛggati* corresponding to the *samalagna* or the intersection of the ecliptic and the prime vertical. The fourth chapter provides two methods for determining the *samalagna*, *samaśaṅku* and *samadṛggati*, but does not explicitly discuss the method for determining the ascendant from the same. However, by substituting the longitude of the Sun for the longitude of the *samalagna*, the procedures given in the third chapter for determining the ascendant are applicable here as well.
The fourth chapter of the *Lagnaprakaraṇa* is once again a testament to Mādhava's genius. Adopting a fresh approach, he expertly conceptualizes several parameters such as the *bhujāprabhā*, *valana*, *paramā bhujā*, *viṣuvadbhujā*, *ayanāntabāhu*, *viṣuvaccalana*, etc., which assist in the elegant and precise determination of the *samalagna*, *samaśaṅku* and *samadṛggati*. The remarkable visualisation of these complex concepts, and their presentation in the form of charming verses, reveals an extraordinary intuition and intellect in both the scientific and artistic domains. We have attempted to showcase some of brilliance involved here through detailed diagrams, derivations and discussion. On the basis of this study, in our opinion, the fourth chapter of the *Lagnaprakaraṇa* further justifies the moniker *golavid* bestowed upon Mādhava by the scholars of the Kerala school.
**Acknowledgements** We would like to place on record our sincere gratitude to the Ministry of Education, Government of India, for the generous support extended to carry out research activities on Indian science and technology by way of initiating the Science and Heritage Initiative (SandHI) at IIT Bombay and the Centre for Indian Knowledge Systems at IIT Madras. We pay our obeisance to the late Prof. K. V. Sarma, who saved the *Lagnaprakaraṇa* for future generations by painstakingly copying the crumbling manuscripts of the text. We are also extremely grateful to the Prof. K. V. Sarma Research Foundation, Chennai, for preserving and sharing the copies of these manuscripts, which has enabled us to study this interesting and important work. Finally, we would also like to thank the Indian Council of Historical Research (ICHR) for supporting our study of the *Lagnaprakaraṇa*.

## References

Kolachana, A., Mahesh, K., & Ramasubramanian, K. (2018). Mādhava's multi-pronged approach for obtaining the *prāṇakalāntara*. *Indian Journal of History of Science*, 53(1), 1–15.
Kolachana, A., et al. (2018). Determination of ascensional difference in the *Lagnaprakaraṇa*. *Indian Journal of History of Science*, 53(3), 302–316.
Kolachana, A., Mahesh, K., & Ramasubramanian, K. (2019). Determination of *kālalagna* in the *Lagnaprakaraṇa*. *Indian Journal of History of Science*, 54(1), 1–12.
Kolachana, A., Mahesh, K., & Ramasubramanian, K. (2019). Precise determination of the ascendant in the *Lagnaprakaraṇa*-I. *Indian Journal of History of Science*, 54(3), 304–316.
Kolachana, A., Mahesh, K., & Ramasubramanian, K. (2020). Precise determination of the ascendant in the *Lagnaprakaraṇa*-II. *Indian Journal of History of Science*, 55(1), 1–25.
Kolachana, A., Mahesh, K., & Ramasubramanian, K. (2020). Precise determination of the ascendant in the *Lagnaprakaraṇa*-III. *Indian Journal of History of Science*, 55(2), 99–112.
Kolachana, A., Mahesh, K., & Ramasubramanian, K. (2021). Precise determination of the ascendant in the *Lagnaprakaraṇa*-IV. *Indian Journal of History of Science*, 56(1), 1–13.
Mādhava. “Lagnaprakaraṇa”. Manuscript 414B, ff. 53–84. Kerala University Oriental Research Institute and Manuscripts Library, Thiruvananthapuram.
Mādhava. “Lagnaprakaraṇa”. KVS Manuscript No. 37a. Prof. K. V. Sarma Research Foundation, Chennai.
Mādhava. “Lagnaprakaraṇa”. KVS Manuscript No. 37b. Prof. K. V. Sarma Research Foundation, Chennai.
Yelluru, N., & Kolachana, A. (2023). Geometry of *prāṇakalāntara* in the *Lagnaprakaraṇa*. *Indian Journal of History of Science*, 58(3), 171–180.
Springer Nature or its licensor (e.g. a society or other partner) holds exclusive rights to this article under a publishing agreement with the author(s) or other rightsholder(s); author self-archiving of the accepted manuscript version of this article is solely governed by the terms of such publishing agreement and applicable law.

[^34]: Similar usage has been observed earlier in verses 39 and 45. See Kolachana et al. (2020a). Also see the next verse, i.e., verse 78.

[^35]: The vertical circle passing through the *dṛkkṣepalagna* also passes through the pole of the ecliptic, and is thus perpendicular to the ecliptic. See our discussion on verse 36 in (Kolachana et al. 2019b, pp. 310–311).

[^36]: The expression *kālalagnabhujākrānti* is to be understood to mean $R \sin \alpha_e \sin \epsilon$. This is similar to the expression *kālalagnabhujotpannakrāntijīvā* employed in the previous verse. See our discussion there.

[^37]: See our discussion of verse 68.

[^38]: See Kolachana et al. (2020b).
<!-- /decode-chunk -->
