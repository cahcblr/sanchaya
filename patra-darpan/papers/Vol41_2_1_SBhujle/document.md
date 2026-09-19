# Calculations of Tithis: An Extension of Surya Siddhanta Formulation

- Author Display: Sudha Bujhle and M N Vahia
- Year: 2006
- Journal Label: IJHS-41-2006-Issue-2
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol41_2_1_SBhujle.pdf

<!-- source: gemini page-chunk extraction -->

*Indian Journal of History of Science*, 41.2 (2006) 133-150

# CALCULATIONS OF *TITHIS*: AN EXTENSION OF *SŪRYA SIDDHĀNTA* FORMULATION

Sudha Bhujle* and M N Vahia **
(Received 4 October 2004)
*Tithis* are the dates of Lunar Calendar. Sewell and Dikshit[^1] have given a detailed procedure to calculate the *tithis* as used in ancient Indian astronomy. The work is based on the principles defined in *Sūryasiddhānta*[^2] and other seminal ancient works. These calculations rely on tabulated values for some constants. The method of deriving these tables is not clear and no formal process of calculating these constants has been given. In the present paper we evaluate the formulation of the process of calculating the *tithis*. We show that this formulation uses constants which can be calculated using trigonometric functions. Hence we re-formulate the method of calculating *tithis* and derive a self consistent equation of calculating *tithis* that still uses the same basic procedure. Using the data of solar eclipses from NASA website[^6], we calculate the *tithis* from 2,000 BC till 3,000 AD. We show that this method of calculating the constants from trigonometric formulae gives an accurate prediction around 500 AD when the tables were created. Outside this period, the discrepancies due to the Earth’s precession overwhelm the data and by 2,000 BC the discrepancies between calculated *tithis* and occurrence of eclipses can be as much as 7 days. We therefore fit this data with least square method and arrive at the correction factors. We add this empirical linear correction factor to correct for this and derive a method of calculating *tithis* which is accurate and self consistent from 2,000 BC to 3,000 AD. We propose that the method may be accurate to as much as 10,000 BC to 10,000 AD. We then test this formulation against the predicted *tithis* (full Moon) of lunar eclipses and show that the formulation gives accurate *tithis* from at least 2,000 BC to 3,000 AD.
**Key Words:** *Guḍī Pāḍwā* day, *Karaṇa*, Mathematical Formulation of *Tithi*, *Nakṣatra*, *Vāra*, Verification of *tithi* from solar and lunar eclipses dates, *Yoga*.
***

[^1]: Raheja Vihar, Powai, Mumbai, e-mail: sbhujle@vsnl.net

[^2]: Tata Institute of Fundamental Research, Mumbai, e-mail: vahia@tifr.res.in

---
134 INDIAN JOURNAL OF HISTORY OF SCIENCE

## 1. INTRODUCTION

The ancient Indian calendar dates back several thousand years and the relevant literature has been extensively collated in a major commentary called the *Indian Calendar* by Sewell and Dikshit [^1]. The standard method of calculating *tithis* was formalised around 500 AD when the calendar was standardised through a book called *Sūryasiddhānta* [^2]. The methodology adopted in the book is not very clear and is often cryptic. In their seminal work more than a century ago, Sewell and Dikshit [^1] have made a detailed analysis of the various Indian calendars and given a standardised method of calculating all aspects of the Indian calendar. In the present paper, we revisit their calculations of *tithis* in order to ascertain the accuracy of the method. We first list the various terminologies used in translations of *Sūryasiddhānta* and also in *Indian Calendars* to help the readers access the original information more easily. We then discuss the method itself and suggest possible changes in the formulation to make the calculations more versatile.

### 1.1. Some basic concepts in defining the calendar

The Hindu calendar has five (*pañca*) limbs (*aṅga*), concerning five elements of time division. These are *vāra*, *tithi*, *nakṣatra*, *yoga* and *karaṇa*. These are defined as follows:
***Vāra:*** It is the name of the day like Monday (*Somavāra*), Tuesday (*Maṅgalavāra*)etc.
***Tithi:*** The moment of new Moon, or that point of time when the longitudes of Sun and Moon are equal is called ‘*amāvasyā*’. The *tithi* is the time taken by the Moon in increasing its distance from the Sun by 12 degrees. The complete revolution of the Moon (29.5 days) occupies 30 *tithis* for 360 degrees. Since the motions of the Sun and Moon are always varying in speed the length of a *tithi* constantly alters.
***Nakṣatra:*** The time, which the Moon requires to travel over the 27th part of the ecliptic, is called ‘*nakṣatra*’. During the traversal of Moon around the Earth it was noticed that the Moon is close to some of the fixed heavenly bodies (stars). Twenty-seven stars that fall on the path of the Moon identified. In 29.5 days, that is, Moon’s one synodic revolution, Moon travels through 27 stars that were
---
CALCULATIONS OF *TITHIS* 135
said to form the 27 *nakṣatras*. Hence, on an average Moon travels one *nakṣatra* everyday. The star, which is closest to the Moon on its path, is called Moon’s *nakṣatra*.
***Yoga:*** The period of time during which the distance between the Sun and Moon is increased by 13° 20'. This is about 1 day.
***Karaṇa:*** The *karaṇa* is half the *tithi* or during which the difference of the longitudes of Sun and Moon is increased by 6°.
While the first three units are still in use, *karaṇas* and *yogas* are hardly used in day-to-day life.

## 2. CALCULATION OF *TITHI*

The simplest definition of a *tithi* is that, it is the phase of Moon on a given time of the year (DOY). The Moon has a periodicity of 29.5 days and a year begins with Sunrise at *Guḍī Pāḍwā* (the day after the New Moon day at the beginning of spring; in the year 300 AD, spring began on the *amāvasyā* that heralded the month of Caitra). In its most simple form the *tithi* (DOY) on a
**Table 1: Names of tithis starting with Full Moon**

| Number | Phase | Tithi | Number | Phase | Tithi |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Kṛṣṇa | Pratipadā | 16 | Śukla | Pratipadā |
| 2 | Kṛṣṇa | Dvitīyā | 17 | Śukla | Dvitīyā |
| 3 | Kṛṣṇa | Tṛtīyā | 18 | Śukla | Tṛtīyā |
| 4 | Kṛṣṇa | Caturthī | 19 | Śukla | Caturthī |
| 5 | Kṛṣṇa | Pañcamī | 20 | Śukla | Pañcamī |
| 6 | Kṛṣṇa | Ṣaṣṭhī | 21 | Śukla | Ṣaṣṭhī |
| 7 | Kṛṣṇa | Saptamī | 22 | Śukla | Saptamī |
| 8 | Kṛṣṇa | Aṣṭamī | 23 | Śukla | Aṣṭamī |
| 9 | Kṛṣṇa | Navamī | 24 | Śukla | Navamī |
| 10 | Kṛṣṇa | Daśamī | 25 | Śukla | Daśamī |
| 11 | Kṛṣṇa | Ekādaśī | 26 | Śukla | Ekādaśī |
| 12 | Kṛṣṇa | Dvādaśī | 27 | Śukla | Dvādaśī |
| 13 | Kṛṣṇa | Trayodaśī | 28 | Śukla | Trayodaśī |
| 14 | Kṛṣṇa | Caturdaśī | 29 | Śukla | Caturdaśī |
| 15 | Kṛṣṇa | Amāvasyā | 30 | Śukla | Pūrṇimā |

\* The waning phase (from Full Moon to New Moon) is called *Kṛṣṇa Pakṣa* and the waxing phase (from New Moon to Full Moon) is called *Śukla Pakṣa* and the names to *tithis* are reversed.
---
136 INDIAN JOURNAL OF HISTORY OF SCIENCE
**Table 2: Division of the path of Moon in the Sky**

| Number | Star Names | Number | Star Names |
| :--- | :--- | :--- | :--- |
| 1 | Aśvinī | 15 | Svātī |
| 2 | Bharaṇī | 16 | Viśākhā |
| 3 | Kṛttikā | 17 | Anūrādhā |
| 4 | Rohiṇī | 18 | Jyeṣṭhā |
| 5 | Mṛgaśira | 19 | Mūlā |
| 6 | Ārdrā | 20 | Pūrva Āṣāḍhā |
| 7 | Punarvasu | 21 | Uttara Āṣāḍhā |
| 8 | Puṣyā | 22 | Śravaṇā |
| 9 | Āśleṣā | 23 | Dhaniṣṭā |
| 10 | Maghā | 24 | Śatatārakā |
| 11 | Pūrva Phālgunī | 25 | Pūrva Bhādrapādā |
| 12 | Uttara Phālgunī | 26 | Uttara Bhādrapādā |
| 13 | Hastā | 27 | Revatī |
| 14 | Citrā | | |

specific day of the year, can be calculated as :

$$tithi(DOY) = longitude\ of\ Moon - Longitude\ of\ Sun\ (of\ the\ orbit\ of\ 360^\circ) ..(1)$$

In order to map it with observable parameters, an additional factor is added into this formulation. The 30 *tithis* (from Full Moon to New Moon and back) are given in Table 1.
In order to map this movement in the sky, different paths of the movement of the Moon are divided as per the nearest star or constellation. The names of the 27 regions, called the 27 *nakṣatras* that make this path are given in Table 2. These are used to define a month. The name of a lunar month is given by the location of the Moon on the Full Moon day. Each region is about 13° 20' in the sky.
From the point of view of a calendar, a *tithi* begins on one day and ends on the following day. However, the length of the *tithi* alters quite often since the apparent motions are not linear. The length of a *tithi* may begin and end within the limits of same solar day. On other occasions, the Moon may remain in the same *tithi* for as many as 2 days; occupying the whole of one and parts of the other solar day.
One *tithi* ends at the moment of time when the angular distance between the Sun and Moon becomes an integral multiple of 12°. In other words, a *tithi* ends at the same instant of time for all places on Earth and a *tithi* is not sensitive to the longitude (or latitude) of the region. The moment of Sunrise of course varies with longitude and therefore local time of Moon’s entry into any *tithi* will differ at different places. For the same reason expunction and repetition of *tithis* may differ by a day in different longitudes.
---
CALCULATIONS OF *TITHIS* 137

### 2.1. Mathematical formulation of *tithi* calculations

Lunation is the time taken by the Moon to complete one revolution around the Earth. The 360° angular path of the Moon in the sky is divided into 10,000 parts and 1 part, the finest possible resolution amounts 2.16 arc min (2.16'). The time between two conjunctions is a synodic lunar month. The smallest unit of measure of a *tithi* is 1/10,000th part of an apparent sidereal revolution of the Moon.
When the angular difference between the Sun and Moon is less than ± 2.16' (measured eastward angle), the Sun and Moon are said to be in conjunction. This moment of time is said to be the *amāvasyā* moment or new Moon. To travel 21,600' of arc, (360°) Moon takes 29.53 (solar) days or 42,480 minutes. So, to travel 2.16' of arc it takes 4.25 minutes. The Moon remains in this position for approximately 4.25 minutes. This interval defines the accuracy of all astronomical observations in ancient Indian calendar. Since *amāvasyā* (new Moon) lasts for the movement of the Moon from -2.16' to + 2.16' around the Sun, it lasts for 8.50 minutes only, according to this formulation.

#### 2.1.1. Primary calculations - Calculation of *tithi* index 'a' :

As stated earlier, a lunation, i.e. rotation by 360° is divided into 30 *tithis*. 1/30th of a lunation represents the time duration of a *tithi* or the angular movement of 12°. Since the lunation is divided into 10,000 parts about 333 (10,000/30) parts go to one *tithi*, 667 parts to 2 *tithis* and so on. Lunation parts are called *tithi* indices. The *tithi* index '*a*' shows the position of the Moon in its orbit with respect to the position of the Sun at conjunction. For example, 0 or 10,000 *tithi* index is the distance travelled from one new Moon to return back to the same relative position, and a *tithi* index of 5000 implies that the Moon has travelled from new Moon to full Moon. The value $t = 40$ shows that the Moon has recently ($40 \times 29.53 \times 24 \times 60 / 10,000 = 170$ minutes ago) passed the point or moment of conjunction. Hence if we know the *tithi* index '*a*' we can find out the *tithi* of a given day. Therefore, Equation (1) can be written as:

$$a = (DOY - DOY\ of\ Guḍī\ Pāḍwā) \times 338.63 .....(2)$$

The constant 338.63 arises from the fact that the Moon travels 10,000 parts in 29.5 days, or 338.63 parts in a day. It implicitly assumes that the mo-
<<<CONTINUE>>>

138 INDIAN JOURNAL OF HISTORY OF SCIENCE
ment after $\textit{amāvasyā}$ was at Sunrise on the $\textit{Guḍi Pāḍwā}$ day, that is, the sunrise on $\textit{Guḍi Pāḍwā}$ day occurred 8.5 minutes after $\textit{amāvasyā}$. Clearly, this is not a good approximation and various corrections need to be made. $\textit{Guḍi Pāḍwā}$ day is defined as the first moment after New Moon after the Spring $^{*}$.

### 2.1.2. Correction factors

The first correction comes from the fact that the exact moment of New Moon need not have occurred 8.5 minutes before Sunrise. Then the initial value of ‘$a$’ is non-zero. For example, in the year 300 AD, the value of ‘$a$’ on $\textit{Guḍi Pāḍwā}$ day was 182 i.e. the Moon was 182 units ahead of the Sun at sunrise at Ujjain which was the central point for all calculations. That is, the $\textit{amāvasyā}$ had occurred 773 minutes (12.9 hours) before the sunrise (for more details see page 57 of Sewell and Dikshit [^1]). Hence we add the first correction term to equation (2) and compute the value of ‘$a$’ in the following manner :

$$a_{calculated} = a + a_{Gu\text{ḍ}i P\text{ā}\text{ḍ}w\text{ā}} \text{ \dots\dots (3)}$$

$a_{calculated}$ is a number that tells how may lunation parts have been completed or lagging behind on the day in question.
The calculation of $\textit{tithi}$ is further complicated than this since all the objects involved, the Moon, the Sun and the Earth have some movements. The correction for all this involves 2 additional parameters over $a_{calculated}$ - namely, ‘$b$’ and ‘$c$’. We discuss these below.
While movement of the Moon is measured with respect to the Sun, the movement of the Sun itself (with respect to the background stars) is, in reality, a measure of the movement of the Earth with respect to the Sun. The Moon travels much faster than the Earth in the sky. Hence the absolute angular distance of Moon and Sun or their distance from one another increases continuously for the first half of the month and decreases during the second half of the month till another conjunction occurs. For measurements, all angles are calculated due east starting with 0 at conjunction and 5,000 parts at the maximum separation to 10,000 parts at the next conjunction, when the counter is re-set. Note that while the Moon completes 1 revolution in 10,000 parts, in the sky, the Sun itself has moved an additional $30^\circ$ (to complete $360^\circ$ in 12 months). Hence to calculate the correct $\textit{tithi}$ two corrections to the first number are added.
***
[*] In the year 500 AD, spring is defined as the period when the Sun enters Aries. Since then, the precession of the Earth’s axis means that this is no longer true.
139 CALCULATIONS OF $\textit{TITHIS}$
Hence a total of 3 terms have to be evaluated to determine the $\textit{tithi}$. The first number is simply the calculation of the Moon’s movement assuming the Sun to be stationary, the $\textit{tithi}$ index (term ‘$a$’) as discussed above. To this, an additional correction (term ‘$b$’) is added to correct for the rotation of the Earth. A third correction (term ‘$c$’) takes into account the revolution of the Earth. While in the original calculations, the term ‘$a$’ is calculated based on formula given in equation (3), the corrections for ‘$b$’ and ‘$c$’ are directly read out from a Table. The values of ‘$b$’ and ‘$c$’ are tabulated by Sewell and Dikshit and its method is not specified. However we fit the trigonometric sine curve to the values of ‘$b$’ and ‘$c$’ when drawn against angle (lunation parts) as a parameter.
Since the relevant motions are not uniform, a given object (Moon, Earth or Sun) is sometimes behind and sometimes in front of its mean or average place. These distances are said to be ‘in defect’ ($\textit{uṇa}$) or ‘in excess’ ($\textit{adhik}$) depending on whether the object is behind, or in front of the expected location from the calculations of ‘$a$’. The parameter ‘$a$’, corresponds to mean expected location and is also called ‘location of the centre’ and the correction over this is called ‘equation of correction from centre’ in lunar motion. This value sometimes needs to be added and sometimes to be subtracted from the mean longitude. In the method adopted in (1), the sign element is eliminated and the correction tables are prepared so that the sum to be worked out is always be one of addition. That is, the correct $\textit{tithi}$ is derived as

$$a_{calculated} = a + C \text{ \dots\dots (4)}$$

where C is the correction term that is derived empirically and tabulated. The value of the term C is the term of the equation of correction of the centre.
The true value of ‘$a$’ which gives the correct $\textit{tithi}$, that is difference between the longitudes of Moon and Sun. We therefore get

$$a_{true} = \text{true longitude of the Moon} - \text{true longitude of the Sun} + C \text{ \dots (5a)}$$

or

$$a_{true} = a_{calculated} + b + c \text{ \dots\dots (5b)}$$

140 INDIAN JOURNAL OF HISTORY OF SCIENCE
To get the true longitude of the Moon from the mean longitude, we must apply the equation of the centre to the mean longitude. The increase in mean longitude of Sun and Moon, i.e., eastward distance of Moon from the Sun, Sun’s mean anomaly (constant ‘$c$’) and Moon’s mean anomaly (constant ‘$b$’) are given in Table 3. As per the conventional definition, the variable ‘$b$’ is moon’s mean anomaly, defined as the difference between the longitude of moon and it’s perigee. The constant ‘$c$’ is Sun’s mean anomaly, namely the difference between the longitude of Sun and it’s perigee. The mean values of these three constants, namely the eastward Moon (quantity ‘$a$’), is calculated as the angular travel by the moon in 1 lunar month (given by 10000/29.53), the mean anomaly of the Moon (quantity ‘$b$’ given by 1000/27.5546) and the Sun’s mean anomaly (quantity ‘$c$’ given by 1000/365.256) are given in Table 3. The quantities $b$ and $c$ can also be interpreted the correction of the co-movement of the Moon with respect to the Earth (quantity $b$, for Earth’s rotation) and Earth with respect to the Sun (quantity $c$, for Earth’s revolution).
Table 3: Daily drifts of the Sun from the moon and the mean anomaly in this movement.

| No. of days | Eastward dist. Of Moon from sun | Moon's mean anomaly | Sun's mean anomaly |
| :--- | :--- | :--- | :--- |
| | (a) Parts of $\textit{tithi}$ index | (b) Parts of $\textit{tithi}$ index | (c) Parts of $\textit{tithi}$ index |
| 1 | 338.6319 | 36.2916 | 2.7378 |

In order to determine the relative angular displacement of the Moon from the Sun, the quantity ($b+c$) must be $\textit{added}$ to the eastward displacement of the Moon that can be calculated as given in equation (4). Since these quantities are small, their evaluation is done by dividing 1 lunar month by 1,000 parts as compared to the division by 10,000 in evaluating ‘$a$’. In Sewell and Dikshit [^1] the values of ‘$b$’ and ‘$c$’ are evaluated in parts of $\textit{tithi}$ index per day. Their method of calculations is not given and they are said to have been derived as best fit values over a long period of empirical studies. In Fig. 1, we have plotted the values of ‘$b$’ and ‘$c$’ as given in Tables VI and VII of Sewell and Dikshit [^1].
Since both ‘$b$’ and ‘$c$’ are trigonometric we can calculate them by the equations given below :
CALCULATIONS OF $\textit{TITHIS}$ 141

![Fig. 1. Variation of ‘b’ and ‘c’ over 1 lunar month (divided into 1000 parts)](media/p09_page.png)

*Fig. 1. Variation of ‘b’ and ‘c’ over 1 lunar month (divided into 1000 parts)*

<!-- figure-resolved-page-render: page=9 image=media/p09_page.png -->

<!-- figure-meta: page=9, position=top, type=graph -->

Table 4: Commonly used names of Lunar Months

| Sr. No. | Name of lunar month | Sr. No. | Name of lunar month |
| :--- | :--- | :--- | :--- |
| 1 | Caitra | 7 | Āśvinī |
| 2 | Vaiśākha | 8 | Kṛttikā |
| 3 | Jyeṣṭhā | 9 | Mṛgaśira |
| 4 | Āṣāḍhā | 10 | Pauṣa |
| 5 | Śrāvaṇā | 11 | Maghā |
| 6 | Bhādrapada | 12 | Phālguṇa |

$$b = C_1 \sin(a_{calculated}) + C_2, \text{ where } C_1=140, C_2=140 \text{ \dots\dots (6a)}$$

and

$$b = C_3 \sin(a_{calculated}) + C_4, \text{ where } C_3=-60, C_4=60 \text{ \dots\dots (6b)}$$

The constants $C_1$ to $C_4$ are dependant on the period and speed of the objects concerned and can, in principle, be calculated from basic astronomy. However, we have used empirical values of $C_1$ to $C_4$ based on the amplitudes of the functions plotted in Fig. 1. We therefore derive the formula based on $\textit{Sūrya siddhānta}$ formulation as,

$$a_{calculated} = a_{Gu\text{ḍ}i P\text{ā}\text{ḍ}w\text{ā}} + (DOY - 29.5 * \text{months till Gu\text{ḍ}i P\text{ā}\text{ḍ}w\text{ā}}) \times 338.63 \text{ \dots\dots (7)}$$

142 INDIAN JOURNAL OF HISTORY OF SCIENCE
This can be simplified to the equation for $a_{true}$ as

$$a_{true} = Tithi (DOY) = a_{calculated} + C_1 \sin(a_{calculated}) + C_2 + C_3 \sin(a_{calculated}) + C_4 + \dots \text{ (8)}$$

From one full Moon to the next it takes 29.5 days. These many days correspond to one lunar month. Names of the lunar months are given in Table 4. Twelve lunar months correspond to one lunar year and one lunar year is equivalent to 354 days.
Earth takes 365.24 days to go around the Sun. So the lunar year is shorter by about 11 days. To map lunar year to solar year a luni-solar calendar has been used for several centuries (see e.g. Bag [^3]).
To define the exact day of the beginning of the so-called spring month of $\textit{Caitra}$ the following procedure is used. In most of India luni-solar $\textit{Caitrādi}$ year commences with $\textit{śukla pakṣa pratipada}$ or 1 day of the Caitra month. According to luni-solar calendar, one extra month is added at a regular interval. This month is called ‘$\textit{adhikamāsa}$’ or intercalated month. Intercalations occur in the $3^{rd}$, $5^{th}$, $8^{th}$, $11^{th}$, $14^{th}$, $16^{th}$ and $19^{th}$ year of a cycle of 19 years is called the Metonic Cycle and is Greek in origin. It arises from the fact that 19 Solar months ($19 \times 364.2422 = 6939.602$ days) and 235 Lunar Months ($235 \times 29.53059 = 6939.689$ days) are nearly identical and are used for re-setting the complete calendar. This is the method adopted by Sewell and Dikshit [^1]. The original Indian practice was to define 5 year periods with two intercalated months (See e.g. Abhyankar [^4]). While we continue with the Metonic cycle as done by Sewell and Dikshit, since the true period of lunar orbit precession is 18.6 years rather than 19 years, the 5 year method gives a more accurate method of corrections. We simply note in the passing that Chandra Hari [^5] has suggested that 19 year cycle was also in use in India as far back as 2400 BC.
It is clear from equation(3) that the entire calculation depends critically on the mapping of $\textit{Guḍi Pāḍwā}$ on the solar year. We therefore discuss the calculation of the DOY of $\textit{Guḍi Pāḍwā}$ below.

### 2.1.3. Calculation of $\textit{Guḍi Pāḍwā}$ day

The initialisation of the calendar was done on the first day of the month of $\textit{Caitra}$ at Ujjain (lat $23^\circ 9' \text{ N}$, $75^\circ 43' \text{ E}$) of the year 399. This day is called $\textit{Guḍi Pāḍwā}$.

[^1]: Robert Sewell and S B Dikshit, $\textit{Indian Calendar}$, 1986

[^3]: A. K. Bag, "Luni-solar Calendar, Kali Ahargaṇa and Julian Days", $\textit{IJHS}$, 38.1 (2003) 17-38.

[^4]: K D Abhyankar, "5-year yuga in Vedāṅga Jyotiṣa", $\textit{IJHS}$, 39.2 (2004) 227-230.

[^5]: K Chandra Hari, "P. V. Holay's Interpretation of the ṚK - Jyotiṣa verses on 19-year yuga", $\textit{IJHS}$, 39.2 (2004) 157-176.

CALCULATIONS OF *TITHIS* | 143
There after, all *Guḍī Pāḍwā* days are calculated based from this day, with a quasi periodicity of 354 days with re-normalisation done when an additional month is added every few years as discussed above. In some cases, this may imply that the month of *Caitra* that is supposed to herald the beginning of spring may come earlier or later than the actual beginning of the season of spring.
The years with intercalated month have 383-385 days and normal year has 353 - 355 days. All calculations are based on *Guḍī Pāḍwā* as the first day of the year. The *Guḍī Pāḍwā* day itself is the day after new Moon day of the month *Caitra*. The lunar year is $354 (29.5 \times 12)$ days and hence the *Guḍī Pāḍwā* is earlier by 11 days every year, if no corrections are made. In order to synchronize with the solar year therefore an additional month “*adhikāmāsa*” is added every $3^{\text{rd}}$, $5^{\text{th}}$, $8^{\text{th}}$, $11^{\text{th}}$, $14^{\text{th}}$, $16^{\text{th}}$ and $19^{\text{th}}$ year. In Fig. 2 we have plotted the

![Fig. 2. Plot of the Day of Guḍī Pāḍwā compared to previous year’s Guḍī Pāḍwā day as a function of years for one 19 year cycle. Year 1 is 400 AD. The number near each point corresponds to the year number in the sequence. Note that the difference is about -11 days corresponding to the difference between the length of lunar and solar year. During the months of adhika māsa (i.e. years with intercalary months, namely $3^{\text{rd}}$, $5^{\text{th}}$, $8^{\text{th}}$, $11^{\text{th}}$, $14^{\text{th}}$, $16^{\text{th}}$ and $19^{\text{th}}$ year) the difference changes from - 11 days to +18 days. A precession cycle of 19 years ensures that the pattern is repeated every 19 years and hence only one cycle is shown.](media/p11_page.png)

*Fig. 2. Plot of the Day of Guḍī Pāḍwā compared to previous year’s Guḍī Pāḍwā day as a function of years for one 19 year cycle. Year 1 is 400 AD. The number near each point corresponds to the year number in the sequence. Note that the difference is about -11 days corresponding to the difference between the length of lunar and solar year. During the months of adhika māsa (i.e. years with intercalary months, namely $3^{\text{rd}}$, $5^{\text{th}}$, $8^{\text{th}}$, $11^{\text{th}}$, $14^{\text{th}}$, $16^{\text{th}}$ and $19^{\text{th}}$ year) the difference changes from - 11 days to +18 days. A precession cycle of 19 years ensures that the pattern is repeated every 19 years and hence only one cycle is shown.*

<!-- figure-resolved-page-render: page=11 image=media/p11_page.png -->

<!-- figure-meta: page=11, position=middle, type=graph -->

144 | INDIAN JOURNAL OF HISTORY OF SCIENCE
**Table 5: Approximate values of $a_{Guḍī Pāḍwā}$ as a function of n**

| Value of n (equation 8) | Value of $a_{Guḍī Pāḍwā}$ | Value of n (equation 8) | Value of $a_{Guḍī Pāḍwā}$ |
| :--- | :--- | :--- | :--- |
| 0 | 74 | 10 | 9985 |
| 1 | 9950 | 11 | 20 |
| 2 | 9825 | 12 | 9896 |
| 3 | 9860 | 13 | 9771 |
| 4 | 9736 | 14 | 9806 |
| 5 | 9770 | 15 | 20 |
| 6 | 9985 | 16 | 55 |
| 7 | 199 | 17 | 269 |
| 8 | 234 | 18 | 145 |
| 9 | 109 | | |

DOY of *Guḍī Pāḍwā* given in (1) for one cycle of 19 years. As can be seen from the figure the difference of *Guḍī Pāḍwā* day from previous year is about -11 days in normal years and about + 18 days for years with the *Adhikamāsa*.
In order to calculate the *Guḍī Pāḍwā* day in any given year ($y$), we follow the following procedure:

$$n = \text{integer equivalent of } [\text{remainder } (\text{abs}(y-399)/19)] \dots\dots(9)$$

Note that the remainder $n$ is an integer *number* between 0 and 18. The number 399 corresponds to the year of normalization. If $n = 0, 3, 5, 8, 11, 14 \text{ or } 16$ then
$Guḍī Pāḍwā \text{ day} = Guḍī Pāḍwā \text{ day in 399 } (DOY = 54) + 18 \text{ days} \dots\dots(10\text{a})$
else
$Guḍī Pāḍwā \text{ day} = Guḍī Pāḍwā \text{ day in 399 } -$
$11 \text{ day} \times (\text{from the year with last adhikamāsa}) \dots\dots(10\text{a})$
Since this drift is entirely due to the precession of Lunar orbit around the earth, we assume that it is not dependent on the precession of the earth’s orbit around the Sun.
It should be noted that while we have used the 19-year cycle to get the *Guḍī Pāḍwā* date of any required year, the periodicity is not exact. The value of ‘$a_{Guḍī Pāḍwā}$’ (Equation 7) does not return exactly to the same value after 19
CALCULATIONS OF *TITHIS* | 145
year cycle. Hence for accurate calculations, the round off with years should not be used and the integer number of days from *Guḍī Pāḍwā* in 399 should be calculated. However, for 1 day accuracy, the approximations used here are acceptable.
In Table 5 we have given the value of $a_{Guḍī Pāḍwā}$ for 19 years from the year 1753. It should be noted that the Moon travels 338.63 *tithi* indexes in 1 day. Also, for all the parameter values in Table 5 with the values less than 338.63 or greater than 9661.37 (10,000 - 338.63), the error introduced by slightly different correct values of $a_{Guḍī Pāḍwā}$ for a specific year will not be significant and will be less than the error of 1 day introduced by longitude insensitivity of calculations.
In one day the eastward distance of Moon from Sun was found to be 338.63. Number of days between the *Guḍī Pāḍwā* day and the solar eclipse day under consideration was found and the value of ‘$a$’ for these many days was calculated.
**Example :** For the year 1937 *Guḍī Pāḍwā* was on March 11th. To calculate the *tithi* of December 2nd 1937 (solar eclipse day), one has to find the difference between March 11 th and December 2nd, i.e., 266 days. Then the *tithi* index of the day was calculated as follows in line with equation (3).

$$a_{calc} = 338.63 \times 266 + \text{'a' on Guḍī Pāḍwā of 1937AD (from equation 9)}$$

$$= 90075.58 + 145 = 90220.58$$

The counter is initialised to 0 once $t = 10000$. Accordingly, the correct value of *tithi* index of the day is 220. According to *tithi* index value it is a *śukla Pakṣa Pratipadā*.

### 2.1.4. Final formulation

To summarise, in order to calculate the *tithi* on any day ($d_y$) of any Solar year ($y$) the following steps must be performed :
a) Calculate the day of *Guḍī Pāḍwā* as given by equation (10a) or (10b) as per the parameter $n$ defined in equation (9).
b) Now calculate the number of days from the *Guḍī Pāḍwā* for $d_y$ by subtraction.
c) To determine the value of a *Guḍī Pāḍwā* use Table 5. Using the appropriate value of $a_{Guḍī Pāḍwā}$ compute equation (7) to get the value of $a_{(calculated)}$ using the values of $C_1$ to $C_4$ from equations (6a) and (6b).
146 | INDIAN JOURNAL OF HISTORY OF SCIENCE

<!-- figure-resolved-page-render-hidden: image=media/p14_page.png caption="Fig. 3. Difference between calculated tithi and New Moon days determined from Solar Eclipse. The best fit line is difference in days = -0.003 $\\times$ year +0.6994. The reduced $\\chi^2$ is 0.9401. Note that the year is in AD." -->

<!-- figure-meta: page=14, position=top, type=graph -->

![Fig. 4. Difference between calculated tithi and New Moon days determined from Solar Eclipse. The best fit line is y = 0.0041 $\times$ year -7.6017. The reduced $\chi^2$ is 0.9156.](media/p14_page.png)

*Fig. 4. Difference between calculated tithi and New Moon days determined from Solar Eclipse. The best fit line is y = 0.0041 $\times$ year -7.6017. The reduced $\chi^2$ is 0.9156.*

<!-- figure-resolved-page-render: page=14 image=media/p14_page.png -->

<!-- figure-meta: page=14, position=middle, type=graph -->

d) Compute equation (8) using the parameters from earlier steps to get $a_{true}$ to arrive at the *tithi* for the $d_y$.
Since the corrections introduced by ‘$b$’ and ‘$c$’ are less than 338.63, as a first approximation, these can be ignored for average daily *tithis*. However, since the sum of maximum error of $b$ and $c$ is 400, these calculations can intro-
CALCULATIONS OF *TITHIS* | 147
duce an error of 1 day. In addition, the approximations used in Table 5 when added for maximum error, the error can go up to 2 days.
Note that these calculations will have an inaccuracy of 1 day due to usage of Table 5. To calculate the *tithi* with an accuracy of better than 1 day, it is necessary that the DOY is computed from DOY 54 (*Guḍī Pāḍwā* day) in 399 and performing the above calculations ignoring the round off with years. However, this procedure will introduce an additional error due to the precession of the Earth’s axis with a period of about 25,800 years. We correct for this in the formulation below.

## 3. Verification of the *tithi* using solar eclipse dates

In order to check the accuracy of the formulation given above, we calculated the *tithis* of the days on which Solar eclipses were observed. NASA website $^6$ gives a list of solar and lunar eclipses from 2000 BC to 4000 AD using current ephemeris. In the first step, we calculated the *tithi* corresponding to the dates of solar eclipse given there. We tolerated an error of $\pm 1$ day in view of the approximations discussed earlier. That is, if our calculated *tithi* was *Caturdaśī*, *Amāvasyā* or *Pratipadā*, we considered the calculations to be accurate. Apart from the approximations, the error of 1 day can also arise due to the fact that we calculate the average *tithi* as seen at Ujjain on that day while it is very likely that the *tithi* index itself did reach 0 sometime during the day, since we have taken all eclipses in the data base and not restricted to those seen from Ujjain. We find that our calculated *tithis* can be substantially different from the expected *tithi* when the calculations are extended into past or future.
The error arises due to the fact that the year is not synchronised to the length of the day. The short term error in the calculations is due to the 19 year precession of the Moon around the Earth which was discussed while discussing the calculation of *Guḍī Pāḍwā* above. The long term deviation occurs due to the fact that the year is not 365.24 days but has fractions that go to third and fourth decimal places. This error builds up into a significant (linear) error over a few hundred years. We empirically correct for both these below.
We verified our calculations with more than 100 solar eclipse dates from 2000 BC to 3000 AD taken from (ref. 6 and 7). However a systematic increase in the deviation from the central value was noticed both for AD and

148 INDIAN JOURNAL OF HISTORY OF SCIENCE
BC dates (Figs. 3,4). This deviation can occur due to the difference in number of days in one year.
We analysed the data between 2000 BC and 3000 AD with least square fit. The corrections thus obtained were incorporated in our program and the correct value of *tithi* was obtained.
As the figures above show, long term corrections are linear. Hence in order to determine the correct *tithi*, the DOY of *Guḍī Pādwā* should be recalculated as per equations given below.
From 2000 BC to 1582 AD

$$Difference\ in\ days = -0.003 \times year + 0.6994 \dots\dots (11a)$$

From 1583 AD to 3000 AD

$$Difference\ in\ days = 0.0041 \times year - 7.6017 \dots\dots (11b)$$

The change over from (11a) to (11b) is done in the year 1582 since that is the year when the Julian year was change to Gregorian year. As seen from the value of $\chi^2$ the best-fit equations are equation (11a) and (11b) and we use this formulation to extend the calculations to determine the *tithi* over an extended period from 2,000 BC to 3,000 AD.
The formulation was checked for the Eclipses from 3000 to 4000 AD tabulated in equ. (6).
The present formulation has taken into account all possible sources of accumulated errors due to various approximations. Hence it should be possible to extend the calculations from 10,000 BC to 10,000 AD. However, since we have no independent ways of confirming this, we only mention this here.

## 4. TESTING OF DATA FOR LUNAR ECLIPSE

We have tested the calculated *tithi* dates based on equation (7) against the calculation of Lunar eclipse data which was not used in deriving the parameters here, as well as Solar eclipse till 4000 AD. The figures given below show the lunar eclipse data fit.
In Fig. 5 we have plotted sample calculations of the *tithi* on the day on which a lunar eclipse was calculated using modern ephemeris $^3$ for different years on which data are available. As can be seen from the figure, for the same values of the various constants our calculated dates of lunar eclipse agree with the observed date of lunar eclipse validating the formulation given here.
CALCULATIONS OF *TITHIS* 149

![Fig.5. Difference between calculated and expected values of *tithis* (*pūrṇima*) on days of lunar eclipse from 2000 BC to 3000 BC](media/p17_page.png)

*Fig.5. Difference between calculated and expected values of *tithis* (*pūrṇima*) on days of lunar eclipse from 2000 BC to 3000 BC*

<!-- figure-resolved-page-render: page=17 image=media/p17_page.png -->

<!-- figure-meta: page=17, position=top, type=graph -->

## 5. DISCUSSION AND CONCLUSION

We have analysed the method employed to calculate the *tithis* on any given solar day from Ujjain (lat $23^\circ\ 9'\text{ N}$, $75^\circ\ 43'\text{ E}$). We show that the formulation is amenable to simpler mathematical compression. We have extended the formulation of *Sūryasiddhānta* to get a more versatile formula to calculate *tithis*. The formulation given here makes the following improvements:
a) Analyses the astronomical reasons for the corrections and give a formulation of look up table for second order corrections introduced by non-synchronised manner of all the periods and movements involved,
b) discusses and corrects for 19 year lunar cycle and long term error build up,
c) gives empirical formula to calculate the *Guḍī Pādwā* day and *tithi* index on the day of *Guḍī Pādwā*,
d) corrects for long-term deviation in the formulation due to the precession using the data of solar eclipses based on modem ephemeris.
We have then checked the formulation by fitting the data to lunar eclipses and shown that the formulation given here calculates the new moon days for lunar eclipse to within an error of 1 day in most cases. We propose that can be used to accurately
150 INDIAN JOURNAL OF HISTORY OF SCIENCE
calculate the *tithi* (within 1 day error) from 10,000 BC to 10,000 AD. We therefore suggest that the formulation given here is more versatile and can be used for extended periods.

### ACKNOWLEDGEMENT

The authors are very grateful to Prof Mohan Apte whose encouragement, clarification and careful reading of the manuscript ensured that we avoided a lot of serious errors and also helped clarify our concepts. We also wish to thank Dr. Jamkhedkar for his encouragement and support.

### REFERENCES

1. Robert Sewell and S B Dikshit, *Indian Calendar*, 1986
2. *Sūryasiddhānta*, 524, (see e.g. English translation by Burgess Rev. Ebenenezer, Motilal Banarasidas, 1860 and 1989 (Sanskrit version published by Chaukhamba Surabharati Prakashan, Varanasi)
3. A. K. Bag, "Luni-solar Calendar, Kali Ahargaṇa and Julian Days", *IJHS*, 38.1 (2003) 17-38.
4. K D Abhyankar, "5-year yuga in Vedāṅga Jyotiṣa", *IJHS*, 39.2 (2004) 227-230.
5. K Chandra Hari, "P. V. Holay's Interpretation of the ṚK - Jyotiṣa verses on 19-year yuga", *IJHS*, 39.2 (2004) 157-176.
6. NASA Website http://sunearth.gsfc.nasa.gov/eclipse/eclipse.html
7. C Marriot, SkyMap Pro, version 8.0.
