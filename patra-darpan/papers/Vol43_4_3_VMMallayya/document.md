# Interpolation of Sines by Successive Approximation Method

- Author Display: V Madhukar Mallayya
- Year: 2008
- Journal Label: IJHS-43-2008-Issue-4
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol43_4_3_VMMallayya.pdf

<!-- source: gemini page-chunk extraction -->

Indian Journal of History of Science, 43.4 (2008) 553-568

# INTERPOLATION OF SINES BY SUCCESSIVE APPROXIMATION METHOD

**V. MADHUKAR MALLAYYA***
(Received 8 October 2007; revised 26 Septembr 2008)
Twelfth century astronomer Bhāskarācārya has given in his astronomical treatise *Siddhānta-Śiromaṇi* a rule for computing intermediary functional difference that is needed for interpolating desired functional value. While discussing this rule, Muniśvara of 17th century has given, in his commentary *Marīci* on the *Siddhānta-Śiromaṇi*, a detailed exposition of the method along with an iterative procedure for successively refining the functional difference using tabular differences. The advantage of this procedure is that a better estimate of the true difference applicable at the given intervening argument can be churned out; using which the desired functional value can be interpolated with greater degree of accuracy. In this paper these two methods are analyzed and viewed through modern perspective and the convergence of Muniśvara’s iterative procedure established in modern terms. A sample result obtained using Muniśvara’s method is compared with that obtained using Bhāskara’s method and also with the corresponding modern value.
**Key words:** *Apacaya*, Āryabhaṭa, Bhāskara, Interpolation, *Jyā*, *Jyotpatti*, *Koṭijyā*, Muniśvara, *Sphuṭam*, *Śeṣāṃśa*, *Utkramajyā*.

## 1. INTRODUCTION

Indian astronomers and mathematicians are found to have made remarkable contributions to the field of Trigonometry and theory of Interpolation. The concept of *jyā* (Rsine) is seen to have evolved from their various astronomical needs. Because of its vast utility, the concept continued to attract the attention of Indian astronomers and mathematicians ever since its introduction in astronomical computations. Introduction of the terminology *jyā* for Rsine by Āryabhaṭa I (499 A.D) along with his methods for computation[^1] may be said to have paved way for scientific treatment of the concept. This branch developed further in due course of time and gradually came to be known by the name *jyotpatti* (*jyā* + *utpatti*, the source of Rsines). Computation of sine tables for interpolation of desired sine values corresponding to intervening arguments, which are needed for astronomical computations and postulation of corrections (*saṃskāra*), formed an important topic for discussion in most of the standard treatises on astronomy and mathematics in India[^2]. Several methods for construction of tabular sines and sine differences along with several techniques for interpolation can be had from various astronomical and mathematical works using which desired intermediary functional values can be computed with desired degree of accuracy. Inverse interpolation techniques for determination of desired intervening argument corresponding to given functional value are also found stated and discussed in several works. Great concern of Indian astronomers for attaining more and more accuracy in the results of their computations motivated them to make deeper studies in this area. The continuous efforts put forth by them using their clear analytic and inquisitive mind not only succeeded in making substantial advancements in their computational skills but also resulted in making significant strides in the discipline by floating several important mathematical concepts and techniques to meet their needs.

## 2. TERMINOLOGY AND NOTATIONS

(i) Corresponding to an arc of a circle of radius $R$ subtending an angle $\theta$ at the centre, the Indian sine known as *kramajyā* or *jyā* is given by $jy\bar{a} (R\theta) = R \sin \theta$ and the Indian cosine called *koṭijyā* is given by $ko\d{t}ijy\bar{a} (R\theta) = R \cos \theta$. Another function which is the versed sine termed *utkramajyā* is given by $R - R \cos \theta$. In fig.1, consider the circular arc $BOW = 2s$ with mid point $O$ subtending an angle $2\theta$ at the centre $K$. Then the arc $BO$ will be equal to $s$ and will subtend an angle $\theta$ at $K$. The half chord $BJ$ is the $kramajy\bar{a}$ or $jy\bar{a}$ of $s$ and the upright $KJ$ on it is the $ko\d{t}ijy\bar{a}$ of $s$. The arrow-like protruding part $JO$ is the $utkramajy\bar{a}$ of $s$. Since $\angle BKO = \theta$ , $jy\bar{a} (s) = BJ = R \sin \theta$, $ko\d{t}ijy\bar{a} (s) = KJ = R \cos \theta$, and $utkramajy\bar{a} (s) = JO = KO - KJ = R - R \cos \theta$.

![Fig. 1](media/p03_page.png)

*Fig. 1*

<!-- figure-resolved-page-render: page=3 image=media/p03_page.png -->

<!-- figure-meta: page=3, position=top, type=diagram -->

(ii) Denote the tabular arc bit by $h$. ($h = 10^\circ$ as used by Bhāskarācārya in the *Siddhānta-Śiromaṇi*). Then the tabular arcs are of angular measure $kh$ for $k = 0, 1, 2, 3, \dots, l$ where $l = \frac{90^\circ}{h}$.
(iii) Denote the tabular Rsines by $J_k = R \sin kh$ for $k = 0, 1, 2, 3, \dots, l$ and the tabular Rsine differences by $\Delta J_k = J_{k+1} - J_k = R \sin(k+1)h - R \sin kh$ for $k = 0, 1, 2, 3, \dots, l-1$.
(iv) Denote the tabular interval containing the argument $\alpha$ (whose functional value is desired) by $(\alpha_b, \alpha_a)$ where $\alpha_b$ and $\alpha_a$ are the tabular arguments just before and just after $\alpha$. If $\alpha_b = kh$ then $\alpha_a = (k + 1)h$ and so the tabular interval containing this $\alpha$ is $[kh, (k + 1)h]$. Denote the tabular interval $[jh, (j + 1)h]$ by $I_{j+1}$ in short for $j = 0, 1, 2, \dots, l - 1$
(v) Denote the tabular Rsine differences just before (i.e., *gata*, foregoing) and just after (i.e., *bhogya*, ensuing) the desired by $d_b$ and $d_a$ respectively.
If $\alpha \in I_{k+1}$, then $d_b = \Delta J_{k-1}$ and $d_a = \Delta J_k$.
(vi) Denote the rectified or refined Rsine difference applicable in the interior of a tabular interval by $d$ and the $r^{\text{th}}$ approximation to it by $d^{(r)}$ for $r = 1, 2, 3, \dots$. In particular denote the Rsine difference applicable at the desired intervening argument $\alpha$ by $d_\alpha$.
(vii) If the intervening argument $\alpha$ (whose *kramajyā* or *utkramajyā* is desired) leaves a quotient $q$ and a remainder $\rho$ when divided by the arc bit $h$, then $\alpha = qh + \rho$, where $0 < \rho < h$. Then $\alpha \in I_{q+1}$ and the tabular arc just before $\alpha$ is $qh$. The corresponding residual angular arc is $\rho$. If $\rho = \theta h$, then obviously $0 < \theta < 1$.

## 3. BHĀSKARA’S RULE FOR REFINING THE FUNCTIONAL DIFFERENCE

Bhāskara’s rule for refining the functional difference needed for the interpolation of a desired functional value using given tabular values at arc bits of $10^\circ$ runs as follows[^3]:
याताइष्ययोः खण्डकयोर्विशेषः शेषशंशनिघ्नो नखहृत् तदूनाम् /
युतं गतैष्यैक्यदलं स्फुटं स्यात् क्रमोत्क्रमज्याकरणेऽत्र भाग्यम् //
This may be translated as follows:
'Divide the product of the residual arc’s degrees (*śeṣāṃśa*) and the difference between the foregoing and ensuing tabular differences by twenty (*nakha*). This subtracted from or added to half the sum of foregoing and ensuing tabular differences will be the refined (*sphuṭam*) ensuing difference for finding Rsine or versed Rsine (*kramajyā* or *utkramajyā*) respectively’.
The refined (corrected) difference $d$ applicable in the interior of the tabular interval containing the desired argument $\alpha$ is thus given by

$$d = \begin{cases} \frac{1}{2}(d_b + d_a) - (d_b - d_a) \frac{\rho}{20} & \text{for } kramajy\bar{a} \\ \frac{1}{2}(d_b + d_a) + (d_b - d_a) \frac{\rho}{20} & \text{for } utkramajy\bar{a}, \end{cases}$$

Taking the value of $d$ corresponding to the *kramajyā*, the desired Rsine is equal to the *tabular Rsine just before* $+ \frac{\rho}{h}d$. Bhāskara’s rule for rectified difference has its roots running into the works of seventh century astronomer Brahmagupta[^4].
The tabular functional values and differences at $10^\circ$ argumental bits with $R = 120^\circ$ given by Bhāskara are displayed in the following table:
**Table 1. Rsine differences and Rsines in degrees with $h = 10^\circ$ and $R = 120^\circ$**

| $k$ | Angular arc, $kh$ | Rsine difference, $J_k - J_{k-1} = \Delta J_{k-1}$ | $R \sin kh = J_k$ |
| :--- | :--- | :--- | :--- |
| 0 | 0 | ** | 0 |
| 1 | 10 | 21 | 21 |
| 2 | 20 | 20 | 41 |
| 3 | 30 | 19 | 60 |
| 4 | 40 | 17 | 77 |
| 5 | 50 | 15 | 92 |
| 6 | 60 | 12 | 104 |
| 7 | 70 | 9 | 113 |
| 8 | 80 | 5 | 118 |
| 9 | 90 | 2 | 120 |

## 4. CORROBORATION OF BHĀSKARA’S FORMULA IN MODERN TERMS

If $H = \frac{\pi h}{180}$, then $\cos (h \text{ degrees}) = \cos (H \text{ radians}) = 1 - \frac{H^2}{2!} + \frac{H^4}{4!} - \dots$
Therefore $1 - \cos (h \text{ degrees}) = \frac{H^2}{2!} - \frac{H^4}{4!} + \dots$,
$\approx \frac{H^2}{2}$, up to the order of $H^2$.
Similarly, $\sin (h \text{ degrees}) = H - \frac{H^3}{3!} + \frac{H^5}{5!} - \dots$,
$\approx H$, up to the order of $H^2$.
Now, $\Delta J_{q-1} = J_q - J_{q-1}$
$= R \sin qh - R \sin (q - 1)h$
$= R [\sin qh - \sin qh \cosh + \cos qh \sinh]$
$= R(1 - \cosh) \sin qh + R(\sinh) \cos qh$
Substitute the values of $1 - \cosh$ and $\sinh$ to get
$\Delta J_{q-1} \approx R \frac{H^2}{2} \sin qh + RH \cos qh$.
<<<CONTINUE>>>

[^1]: Āryabhaṭa, *Āryabhaṭīya*, Critically edited with Introduction, English Translation, Notes, Comments and Indexes by K. S. Shukla in collaboration with K. V. Sarma, Indian National Science Academy, New Delhi 1976, verses i.12 and ii.9 – 12 pp. 29-30, 44-54. Also see Parmeshwar Jha, *Āryabhaṭa I and His Contributions to Mathematics*, Bihar Research Society, Patna 1988, pp.248-277.

[^2]: A.K.Bag, ‘Sine Tables in Ancient India’, *IJHS*, 4.1-2 (1969) 79-85.

[^3]: Bhāskarācārya, *Siddhānta Śiromaṇi* Part II, edited by Kedar Datta Joshi, The Banaras Hindu University, Varanasi 1964, verse 16 of the *Spaṣṭādhikāra* section in the *Grahagaṇitādhyāya*.

[^4]: Brahmagupta, *Khaṇḍakhādyaka*, Translated into English by P.C.Sengupta, University of Calcutta, Calcutta 1934, ix.8 p.141. For details see R.C Gupta, ‘Second Order Interpolation in Indian Mathematics up to the Fifteenth Century’, *IJHS*, 4.1-2(1969) 86-98.

558 INDIAN JOURNAL OF HISTORY OF SCIENCE
In the same manner we can establish that $\Delta J_q \approx -R \frac{H^2}{2} \sin qh + RH \cos qh$
Hence $\frac{\Delta J_{q-1} + \Delta J_q}{2} \approx RH \cos qh$ and $\Delta J_{q-1} - \Delta J_q \approx RH^2 \sin qh$
Now if $P = \frac{\pi\rho}{180}$, then
$\cos(\rho \text{ degrees}) = \cos(P \text{ radians})$
$= 1 - \frac{P^2}{2!} + \frac{P^4}{4!} + \dots \approx 1 - \frac{P^2}{2}$, up to the order of $P^2$,
and $\sin(\rho \text{ degrees}) = \sin(P \text{ radians})$
$= P - \frac{P^3}{3!} + \dots \approx P$, up to the order of $P^2$.
Hence the desired Rsine is given by
$R \sin \alpha = R \sin (qh + \rho)$, $0 < \rho < h$
$= R \sin qh(\cos \rho) + R \cos qh(\sin \rho)$
$\approx \left( 1 - \frac{P^2}{2} \right) R \sin qh + P(R \cos qh)$
$= R \sin qh + P(R \cos qh) - \frac{P^2}{2} R \sin qh$
$= R \sin qh + \frac{P}{H}(RH \cos qh) - \frac{P^2}{H^2} \left( \frac{RH^2 \sin qh}{2} \right)$
$= J_q + \frac{P}{H} \left( \frac{\Delta J_{q-1} + \Delta J_q}{2} \right) - \frac{P^2}{H^2} \left( \frac{\Delta J_{q-1} - \Delta J_q}{2} \right)$
559 INTERPOLATION OF SINES
$= J_q + \frac{\rho}{h} \left[ \left( \frac{\Delta J_{q-1} + \Delta J_q}{2} \right) - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - \Delta J_q}{2} \right) \right]$,
since $\frac{P}{H} = \frac{\rho}{h}$
$= J_q + \frac{\rho}{h} \left[ m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - \Delta J_q}{2} \right) \right]$,
where $m = \left( \frac{\Delta J_{q-1} + \Delta J_q}{2} \right)$
$= J_q + \frac{\rho}{h} d$, where $d = m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - \Delta J_q}{2} \right)$
as stated by Bhāskara II.

## 5. MUNIŚVARA'S SUCCESSIVE APPROXIMATION TECHNIQUE

Muniśvara (alias Viśvarūpa) of 1653 AD, in his Sanskrit commentary *Marīci* on the *Siddhānta-Śiromaṇi*, gives a detailed exposition of Bhāskara's rule along with an iterative procedure[^5] for further refining the difference $d$ (with desired degree of accuracy) so as to make it applicable in the interior of the interval containing the argument. Muniśvara also gives the rationale of the procedure and illustrates it numerically. The tabular Rsine differences and Rsines at equal arc bits of $h$ degrees are given and the functional value corresponding to the argument $\alpha$ is desired. If $q$ and $\rho$ denote respectively the quotient and remainder of division of $\alpha$ by the arc bit $h$ then $\alpha = qh + \rho$, where $0 < \rho < h$. Therefore $\alpha$ lies between the tabular arcs $qh$ and $(q+1)h$ so that $I_{q+1} = [qh, (q+1)h]$ is the tabular interval containing $\alpha$. The desired functional value is $R \sin \alpha$ which lies between the tabular values $J_q$ and $J_{q+1}$. These are respectively the tabular Rsines just before and just after the desired or, in other words they are respectively the tabular Rsines at the beginning and end of the interval $I_{q+1}$. The tabular Rsine differences $d_b$ and $d_a$ just before and after the desired are respectively $\Delta J_{q-1} = J_q - J_{q-1}$ and
560 INDIAN JOURNAL OF HISTORY OF SCIENCE
$\Delta J_q = J_{q+1} - J_q$. In the interior of the interval, the tabular Rsine difference $\Delta J_{q-1}$ is found to have been crossed already at $qh$ and $\Delta J_q$ is the forthcoming one which will be attained only after advancing $h$ degrees from $qh$. Since the difference $\Delta J_{q-1}$ has already been crossed at $qh$ and $\Delta J_q$ will be attained only on crossing $(q+1)h$, a rough assumption that the tabular Rsine difference $\Delta J_q$ is the Rsine difference for the interior of the interval of arc bit $h$ will give $\frac{\rho}{h} \Delta J_q$ as an estimate of the Rsine difference for the residual bit $\rho$ using the rule of three. Under this assumption the desired Rsine will be $R \sin \alpha = J_q + \frac{\rho}{h} \Delta J_q$. But the assumption that the *forthcoming* tabular difference $\Delta J_q$ as the Rsine difference for the interior of the interval of length $h$ is not sound. Moreover, the subsequent application of rule of three for finding the difference corresponding to the residual part is not justified because the Rsine differences are not uniform and in fact they are found to be varying in a decreasing order. In the interval $I_{q+1}$ containing the argument $\alpha$, Rsine difference is found to be decreasing from the crossed tabular difference $\Delta J_{q-1}$ to the forthcoming tabular difference $\Delta J_q$. Consequently, neither $\Delta J_{q-1}$ nor $\Delta J_q$ are qualified to be applicable at any point in the interior of this interval. But, having crossed $\Delta J_{q-1}$, if the true value in the interior of length $h$ is $d$ (after taking into account the amount of decrease in the difference) then the value at $\alpha$ (where $\alpha = \alpha_b + \rho$) will be $d_\alpha = \frac{\rho}{h} d$, so that the desired Rsine is $R \sin \alpha = J_q + d_\alpha = J_q + \frac{\rho}{h} d$. Bhāskara's rule is, in fact, an attempt to find an estimate of such a true difference $d$ applicable in the interior of the tabular interval. In order to attain more accuracy Muniśvara arrived at a new version of Bhāskara's formula. Muniśvara's method is capable of successively refining the desired Rsine difference till the desired level of accuracy is attained. Starting from the value obtained from Bhāskara's formula and treating it as the first approximation $d^{(1)}$, the successive approximations $d^{(r+1)}$ for $r = 1, 2, 3$ etc. are computed using the iterative formula

$$d^{(r+1)} = \frac{1}{2}(d_b + d_a) - \frac{\rho}{2h}(d_b - d^{(r)})$$ till the value becomes stable up to the desired subdivision of degrees (where each subunit is a sixtieth part of the
561 INTERPOLATION OF SINES
preceding one like $1' = $ a sixtieth part of $1^\circ, 1'' = $ a sixtieth part of $1'$ and so on). The stabilized value so obtained is taken as the true difference $d$.
Since the tabular Rsine difference $\Delta J_{q-1}$ has been crossed at $qh$ and the tabular difference $\Delta J_q$ is attained only on crossing $(q+1)h$, the natural choice for the difference within the interval $I_{q+1}$ would be the mean $m = \frac{\Delta J_{q-1} + \Delta J_q}{2} = \frac{d_b + d_a}{2}$. But the Rsine differences are found to be in decreasing order. Hence the amount of decrease (*apacaya*) in the interval from $qh$ has to be deducted from this mean value to get a rectified value. If the decrease in the Rsine difference for $h$ degrees in the interval $I_{q+1}$ is $\delta$ and if the first approximation to it is $\delta^{(1)}$ then $\delta^{(1)} = m - \Delta J_q = m - d^{(0)}$, where $d^{(0)} = d_a = \Delta J_q$.
Since $m = \left( \frac{\Delta J_{q-1} + \Delta J_q}{2} \right)$, it follows that
$\delta^{(1)} = \frac{\Delta J_{q-1} + \Delta J_q}{2} - \Delta J_q$
$= \frac{\Delta J_{q-1} - \Delta J_q}{2} = \frac{\Delta J_{q-1} - d^{(0)}}{2}$
Now, by the rule of three, the decrease across $\rho$ degrees is $\frac{\rho}{h} \delta^{(1)} = \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - d^{(0)}}{2} \right)$ so that the first approximation to the rectified difference is $d^{(1)} = m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - d^{(0)}}{2} \right)$. This is exactly Bhāskara's formula for Rsine.
Replacing the $d^{(0)}$ on the right side of the above formula by $d^{(1)}$ the second approximation $d^{(2)} = m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - d^{(1)}}{2} \right)$ will be obtained.
562 INDIAN JOURNAL OF HISTORY OF SCIENCE
Proceeding like this, the third approximation $d^{(3)}$, fourth approximation $d^{(4)}$ and so on may be obtained. In general the $r^{th}$ approximation is given by
$d^{(r)} = m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - d^{(r-1)}}{2} \right)$. The process is to be continued till two successive approximations, say $d^{(M+1)}$ and $d^{(M)}$ (for some positive integer $M$) become equal up to the desired subdivision of degrees (or up to the desired number of decimal places). Then the criterion $|d^{(n+1)} - d^{(n)}| < \varepsilon$ will be satisfied $\forall n \geq M$ where the positive quantity $\varepsilon$ can be chosen as small as we please so as to get the desired degree of accuracy in the result. The stabilized value thus obtained is taken as the true difference $d$ for computing the desired Rsine.

## 6. CONVERGENCE OF MUNIŚVARA'S ITERATIVE PROCEDURE

Muniśvara's iterative formula $d^{(r+1)} = m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - d^{(r)}}{2} \right)$ can be expressed in the form $d^{(r+1)} = m - \frac{\theta}{2} \Delta J_{q-1} + \frac{\theta}{2} d^{(r)}$, where $\theta = \frac{\rho}{h}$, $0 < \theta < 1$.
Replace $r$ by $r-1$ to get $d^{(r)} = m - \frac{\theta}{2} \Delta J_{q-1} + \frac{\theta}{2} d^{(r-1)}$. Subtract this from $d^{(r+1)}$ to get $d^{(r+1)} - d^{(r)} = \frac{\theta}{2} \{ d^{(r)} - d^{(r-1)} \}$.
Replace $r$ successively by $n, n-1, n-2, \dots, 2, 1$ to get the following $n$ equations

$$d^{(n+1)} - d^{(n)} = \frac{\theta}{2} \{ d^{(n)} - d^{(n-1)} \}$$

$$d^{(n)} - d^{(n-1)} = \frac{\theta}{2} \{ d^{(n-1)} - d^{(n-2)} \}$$

[^5]: Op.cit. No.3, pp.133-140. Also see R.C. Gupta, 'Muniśvara's Modification of Brahmagupta's Rule for Second Order Interpolation', *IJHS*, 14.1(1979) 66-72.

INTERPOLATION OF SINES 563

$$d^{(n-1)} - d^{(n-2)} = \frac{\theta}{2} \left\{ d^{(n-2)} - d^{(n-3)} \right\}$$

............................
............................

$$d^{(2)} - d^{(1)} = \frac{\theta}{2} \left\{ d^{(1)} - d^{(0)} \right\}$$

Take their product and cancel out the common factors on either side to obtain

$$d^{(n+1)} - d^{(n)} = \left( \frac{\theta}{2} \right)^n \left\{ d^{(1)} - d^{(0)} \right\}$$

$$= \left( \frac{\theta}{2} \right)^n \left\{ m - \frac{\theta}{2} \Delta J_{q-1} + \frac{\theta}{2} d^{(0)} - d^{(0)} \right\} \text{ since } d^{(1)} = m - \frac{\theta}{2} \Delta J_{q-1} + \frac{\theta}{2} d^{(0)}$$

$$= \left( \frac{\theta}{2} \right)^n \left\{ \frac{\Delta J_{q-1} + \Delta J_q}{2} - \frac{\theta}{2} \Delta J_{q-1} + \frac{\theta}{2} \Delta J_q - \Delta J_q \right\}$$

$$= \left( \frac{\theta}{2} \right)^n \frac{1}{2} (\theta - 1) \{ J_{q+1} - 2J_q + J_{q-1} \} \text{ since } \Delta J_k = J_{k+1} - J_k$$

$$= \left( \frac{\theta}{2} \right)^n \frac{1}{2} (\theta - 1) \{ R \sin (q+1)h - 2R \sin qh + R \sin (q-1)h \}$$

$$= \left( \frac{\theta}{2} \right)^n \frac{1}{2} (\theta - 1) R [ \{ \sin (q+1)h + \sin (q-1)h \} - 2 \sin qh ]$$

$$= \left( \frac{\theta}{2} \right)^n \frac{1}{2} (\theta - 1) R [ 2 \sin qh \cos h - 2 \sin qh ]$$

564 INDIAN JOURNAL OF HISTORY OF SCIENCE

$$= \left( \frac{\theta}{2} \right)^n (1 - \theta) R \sin qh (1 - \cos h)$$

$$= \left( \frac{\theta}{2} \right)^n (1 - \theta) R \sin qh \cdot 2 \sin^2 \left( \frac{h}{2} \right)$$

$$\rightarrow 0 \text{ as } n \rightarrow \infty \text{ since } 0 < \theta < 1.$$

Hence corresponding to a pre-assigned positive quantity $\varepsilon$ however small it may be, there exists some positive integer $M$ such that $|d^{(n+1)} - d^{(n)}| < \varepsilon, \forall n \geq M$, since $\left( \frac{\theta}{2} \right)^n \rightarrow 0$ as $n \rightarrow \infty$. This establishes the convergence of the procedure. Thus it follows that for some positive integer $M$, the $M^{\text{th}}$ and $(M+1)^{\text{th}}$ approximations will be equal up to the desired number of decimal places and the procedure will terminate with $r = M$.

## 7. THE ALGORITHM

The following algorithm is based on Munīśvara’s iterative method to compute $R \sin \alpha$ for any given argument $\alpha$ using tabular values at equal arc bits of $h^0$
**Step I:** Divide the angular arc $\alpha$ by $h$ (Here $h=10^{\circ}$) and note the quotient $q$ and remainder $\rho$ where $0 < \rho < h$.
**Step II:** Note the preceeding and forthcoming tabular Rsines $J_q$ and $J_{q+1}$ as well as the preceeding and forthcoming tabular Rsine differences $\Delta J_{q-1}$ and $\Delta J_q$
**Step III:** Compute the mean Rsine difference $m = \frac{\Delta J_{q-1} + \Delta J_q}{2}$
**Step IV:** To begin with take $d^{(0)} = \Delta J_q$
**Step V:** Compute the successive approximations $d^{(r+1)}$ using the iterative formula $d^{(r+1)} = m - \frac{\rho}{h} \left( \frac{\Delta J_{q-1} - d^{(r)}}{2} \right)$ for $r = 0, 1, 2, 3, \ldots$
INTERPOLATION OF SINES 565
**Step VI:** For each $r$ examine whether two successive values say $d^{(r+1)}$ and $d^{(r)}$ have become stable up to the desired subdivision of degrees (or up to desired number of decimal places). For this examine whether the criterion $| d^{(r+1)} - d^{(r)} | < \varepsilon$ is satisfied where the small positive quantity $\varepsilon$ is to be chosen so as to attain the desired degree of accuracy in the result. If it is satisfied then terminate the process and take the stabilized value as the value of the refined difference $d$. If not, go to Step V and continue the process of approximating.
(The process when terminated with $r = 0$ will give Bhāskara’s value).
**Step VII:** Using the stabilized value $d$ compute the desired Rsine by applying the formula $R \sin \alpha = J_q + \theta d$ where $\theta = \frac{\rho}{h}$.

## 8. NUMERICAL EVALUATION

Using the given set of tabular values and using a computer program based on Munīśvara’s algorithm, the functional values corresponding to desired arguments can be obtained and compared with those obtained by using Bhāskara’s method and these values may be compared with corresponding modern values.
To evaluate the functional value $R \sin 24^{\circ}$, the angular arc is $\alpha = 24^{\circ}$. From the given set of tabular values $h = 10^{\circ}$ so that $q = 2$ and $\varepsilon = 4$.
Preceeding and forthcoming tabular Rsines are $J_q = 41$ and $J_{q+1} = 60$; preceeding and forthcoming tabular Rsine differences are $\Delta J_{q-1} = 20$ and $\Delta J_q = 19$.
Taking $\varepsilon = 0.0000005$, the ten successive approximations obtained are given in Table 2.
Munīśvara’s rectified Rsine difference is $d = 19^{\circ}22'29''59'''$
The desired functional value by Munīśvara’s method is $R \sin 24^{\circ} = 48.74999998463999870000 = 48^{\circ}44'59''59'''59^{iv}48^v03^{vi}21^{vii}49^{viii}36^{ix}37^x$ in degrees, minutes, seconds and subunits.
The Desired Rsine by Bhāskara’s method is $R \sin 24^{\circ} = 48.7199999999999890000$.
566 INDIAN JOURNAL OF HISTORY OF SCIENCE
**Table 2. Successive approximations for $d$ in degrees, min, sec, and subunits**

| r | $d^{(r)}$ in decimal form | $d^{(r)}$ in deg, min, sec and subunits |
| :--- | :--- | :--- |
| 0 | 19.000000000000000 | $19^{\circ}00'00''00'''00^{iv}00^v00^{vi}00^{vii}00^{viii}00^{ix}00^x$ |
| 1 | 19.300000000000007 | $19^{\circ}18'00''00'''00^{iv}00^v00^{vi}00^{vii}00^{viii}07^{ix}09^x$ |
| 2 | 19.359999999999994 | $19^{\circ}21'35''59'''59^{iv}59^v59^{vi}59^{vii}59^{viii}54^{ix}16^x$ |
| 3 | 19.371999999999999 | $19^{\circ}22'19''11'''59^{iv}59^v59^{vi}59^{vii}59^{viii}58^{ix}51^x$ |
| 4 | 19.374400000000014 | $19^{\circ}22'27''50'''24^{iv}00^v00^{vi}00^{vii}00^{viii}14^{ix}05^x$ |
| 5 | 19.374880000000010 | $19^{\circ}22'29''34'''48^{iv}00^v00^{vi}00^{vii}00^{viii}09^{ix}58^x$ |
| 6 | 19.374976000000002 | $19^{\circ}22'29''54'''48^{iv}57^{v}36^{vi}00^{vii}00^{viii}01^{ix}59^x$ |
| 7 | 19.374995200000008 | $19^{\circ}22'29''58'''57^{iv}47^{v}31^{vi}12^{vii}00^{viii}07^{ix}33^x$ |
| 8 | 19.374999039999987 | $19^{\circ}22'29''59'''47^{iv}33^{v}30^{vi}14^{vii}23^{viii}47^{ix}11^x$ |
| 9 | 19.374999807999983 | $19^{\circ}22'29''59'''57^{iv}30^{v}42^{vi}02^{vii}52^{viii}31^{ix}07^x$ |
| 10 | 19.374999961600004 | $19^{\circ}22'29''59'''59^{iv}30^{v}08^{vi}24^{vii}34^{viii}37^{ix}23^x$ |

(The value corresponding to $r = 0$ is the Bhāskara’s value for $d$).
Value of $\sin 24^{\circ}$ by Bhāskara’s method $= 0.40599999999999997200$
Value of $\sin 24^{\circ}$ by Munīśvara’s method $= 0.40624999987200000000$
Modern value of $\sin 24^{\circ} = 0.40673664307580020775$
Thus for $\alpha = 24^{\circ}$
Munīśvara’s Sine - Bhāskara’s Sine $= 0.000249999872000028$
Modern Sine - Munīśvara’s Sine $= 0.00048664320380020775$
Modern Sine - Bhāskara’s Sine $= 0.00073664307580023575$
The numerical output provided here gives the successive approximations as well as the value of $R \sin \alpha$ for $\alpha = 24^{\circ}$ computed using the method given by Munīśvara. Corresponding to $\varepsilon = 0.0000005$, the ten approximations obtained here closely resemble the Munīśvara’s values. Munīśvara’s functional value is found to be closer to the corresponding modern value than Bhāskara’s value. Errors in these functional values are also estimated. Further improvement may be made by using more accurate tabular values and also by reducing the value of $\varepsilon$.

## 9. A NOTE ON THE APPROXIMATIONS GIVEN BY MUNĪŚVARA

Ten successive approximations to $d$ corresponding to $24^{\circ}$ given in the *Marīci* with stability in the last two values up to the subunit corresponding
INTERPOLATION OF SINES 567
**Table 3. The *Marīci* and the computed Approximations for $d$ in degrees, min, sec, and subunits**

| r | The Marīci approximations | Computed approximations |
| :--- | :--- | :--- |
| 1 | $19^{\circ}18'$ | $19^{\circ}18'$ |
| 2 | $19^{\circ}21'36''$ | $19^{\circ}21'36''$ |
| 3 | $19^{\circ}22'22''12'''$ | $19^{\circ}22'19''12'''$ |
| 4 | $19^{\circ}22'28''26'''24^{iv}$ | $19^{\circ}22'27''50'''24^{iv}$ |
| 5 | $19^{\circ}22'29''41'''16^{iv}47^v$ | $19^{\circ}22'29''34'''4^{iv}48^v$ |
| 6 | $19^{\circ}22'29''56'''15^{iv}21^{v}36^{vi}$ | $19^{\circ}22'59''54'''48^{v}57^{vi}36^{vii}$ |
| 7 | $19^{\circ}22'29''59'''15^{iv}4^{v}19^{vi}12^{vii}$ | $19^{\circ}22'29''58'''57^{iv}47^{v}31^{vi}12^{vii}$ |
| 8 | $19^{\circ}22'29''59'''51^{iv}0^{v}51^{vi}50^{vii}24^{viii}$ | $19^{\circ}22'29''59'''47^{iv}33^{v}30^{vi}14^{vii}24^{viii}$ |
| 9 | $19^{\circ}22'29''59'''58^{iv}12^{v}10^{vi}22^{vii}4^{viii}48^{ix}$ | $19^{\circ}22'29''59'''57^{iv}30^{v}42^{vi}02^{vii}52^{viii}31^{ix}$ |
| 10 | $19^{\circ}22'29''59'''59^{iv}38^{v}20^{vi}34^{vii}14^{viii}57^{ix}36^{x}$ | $19^{\circ}22'29''59'''59^{iv}30^{v}8^{vi}24^{vii}34^{viii}37^{ix}23^{x}$ |

to the sixtieth part of a second are displayed in Table-3 along with the corresponding computed values.
On comparing the two sets of values some minor differences can be seen in the *Marīci* values from the third approximation onwards. A small error of $3''$ is found to have occurred somehow in the third approximation for $d$ given in the *Marīci* and is seen to have spread out in all the succeeding approximations. However the last *Marīci* value and the corresponding computed value are found to be same up to the fourth subdivision of a degree. At the end of the iterative procedure the refined value (stable up to third subdivision of a degree) is seen to be $19^{\circ}22'29''59'''$.
While the computed functional value in degrees and ten subunits is $48^{\circ}44'59''59'''59^{iv}48^v3^{vi}21^{vii}49^{viii}36^{ix}37^x$, the corresponding *Marīci* value is $48^{\circ}44'59''59'''51^{iv}20^{v}13^{vi}45^{vii}59^{viii}2^{ix}24^x$. The *Marīci* value and the computed value are same only up to third subdivision of a degree and is equal to $48^{\circ}44'59''59'''$.
Likewise applying the formula for $d$ corresponding to the *utkramajyā*, the rectified difference for versed Rsines can be determined using which the desired versed Rsine (and hence Rcosine) can be interpolated.

568 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; INDIAN JOURNAL OF HISTORY OF SCIENCE

## REFERENCES

1. Āryabhaṭa, *Āryabhaṭīya*, Critically edited with Introduction, English Translation, Notes, Comments and Indexes by K. S. Shukla in collaboration with K. V. Sarma, Indian National Science Academy, New Delhi 1976, verses i.12 and ii.9 – 12 pp. 29-30, 44-54. Also see Parmeshwar Jha, *Āryabhaṭa I and His Contributions to Mathematics*, Bihar Research Society, Patna 1988, pp.248-277.
2. A.K.Bag, ‘Sine Tables in Ancient India’, *IJHS*, 4.1-2 (1969) 79-85.
3. Bhāskarācārya, *Siddhānta Śiromaṇi* Part II, edited by Kedar Datta Joshi, The Banaras Hindu University, Varanasi 1964, verse.16 of the *Spaṣṭādhikāra* section in the *Grahagaṇitādhyāya*.
4. Brahmagupta, *Khaṇḍakhādyaka*, Translated into English by P.C.Sengupta, University of Calcutta, Calcutta 1934, ix.8 p.141. For details see R.C Gupta, ‘Second Order Interpolation in Indian Mathematics up to the Fifteenth Century’, *IJHS*, 4.1-2(1969) 86-98.
5. *Op.cit.* No.3, pp.133-140. Also see R.C Gupta, ‘Munīśvara’s Modification of Brahmagupta’s Rule for Second Order Interpolation’, *IJHS*, 14.1(1979) 66-72.
