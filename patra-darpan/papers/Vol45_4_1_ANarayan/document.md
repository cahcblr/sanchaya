# Dating the Surya Siddhanta using Computational Simulation of Proper Motions and Ecliptic Variations

- Author Display: Anil Narayan
- Year: 2010
- Journal Label: IJHS-45-2010-Issue-4
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol45_4_1_ANarayan.pdf

<!-- source: gemini page-chunk extraction -->

Indian Journal of History of Science, 45.4 (2010) 455-476

# DATING THE *SŪRYA SIDDHĀNTA* USING COMPUTATIONAL SIMULATION OF PROPER MOTIONS AND ECLIPTIC VARIATIONS

ANIL NARAYANAN*
(Received 23 March 2010)
A computational study was undertaken to determine the approximate epoch of the *Sūrya Siddhānta*, an ancient Indian work on astronomy. It is attested on the basis of longitude variation data that the text has been updated several times in the past. The last update was taken up in about 580 AD. The computer simulation involved stellar proper motion, ecliptic-obliquity variation, ecliptic-node-location variation and ecliptic-sink variation for latitudinal data were also obtained and compared which suggest a match for the time frame 7300-7800 BC. The range of values for ecliptic obliquity and ecliptic node location in this timeframe correlated well with standard empirical formulae in current usage.
**Key words:** Axial-precession, Computational simulation, Ecliptic-node, Ecliptic-obliquity, Ecliptic-sink, *Nakṣatra*, Planetary-precession, Steller-proper-motion, *Sūrya Siddhānta*.

## 1. INTRODUCTION

The first hints of Indian astronomical principles reached Europe in the late 17th century curiously enough not from India but from Thailand where there existed a flourishing Hindu state. The obscure manuscripts brought back by the French embassy from Siam eventually made their way into the hands of the famous Italian astronomer John Dominic Cassini, who was able to decipher them correctly. The calculation techniques and data presented in the scripts created a great sensation at that time. As a consequence several prominent European scholars took keen interest in Indian astronomy including the likes of Euler, Laplace and Playfair. The apex of interest was reached in 1787 with the publication of a
---
456 INDIAN JOURNAL OF HISTORY OF SCIENCE
treatise[^1] on the subject by Frenchman Jean Sylvain Bailly who, in the opinion of some, showered an excessive amount of praise on Indian achievements in that field. This led to a general demand for a full and balanced investigation and by the middle and late 19th century many Indian astronomical treatises had been translated into English including *Jyotiṣa Vedāṅga*[^2] (Weber), *Sūrya Siddhānta*[^3] (Burgess) and *Pañca Siddhāntikā*[^4] (Thibaut).
The word *Siddhānta* in Sanskrit means ‘treatise’ and it usually has the author’s name prefixed to it. Ancient Indian lore speaks of eighteen such works on astronomy, many of which have since been lost:

| | | |
| :--- | :--- | :--- |
| *Sūrya Siddhānta* | *Brahma Siddhānta* | *Soma Siddhānta* |
| *Vyāsa Siddhānta* | *Vasiṣṭha Siddhānta* | *Atri Siddhānta* |
| *Parāśara Siddhānta* | *Kāśyapa Siddhānta* | *Nārada Siddhānta* |
| *Garga Siddhānta* | *Marīci Siddhānta* | *Manu Siddhānta* |
| *Aṅgiras Siddhānta* | *Lomaśa Siddhānta* | *Puliśa Siddhānta* |
| *Cyavana Siddhānta* | *Yavana Siddhānta* | *Bhṛgu Siddhānta* |

The first three, Sūrya, Brahma and Soma, are the oldest and indeed so old that their authors are represented as divinities: Sūrya (Sun), Brahma (Creator God) and Soma (Moon). While it is generally supposed that the *Sūrya Siddhānta* is the oldest, some consider the *Brahma Siddhānta* to be so. However, of all the *Siddhāntas* it is the *Sūrya* that has always drawn the greatest respect and reverence and in which each topic is treated more fully than any other.
In this article we will focus on the *Sūrya Siddhānta* and attempt to establish a rough epoch for it from the star data found therein. Surprisingly, hardly any such attempts seem to have been made in recent times; the last one being 150 years ago during the colonial era. This last attempt was marred by several problems including untenable assumptions, inaccurate data, and lack of computing power.

## 2. THE *SŪRYA SIDDHĀNTA*

As mentioned, of all the *Siddhāntas* it is the *Sūrya* that has the best known, the most referred and the most esteemed. Like many classical Indian works, the *Sūrya Siddhānta* is a poem in the Sanskrit language. It has 14 chapters in all and contains exactly 500 verses. The Sanskrit metrical style used is the one called ‘*śloka*’.
Not a trivial work by any means the text covers cosmology, planetary motion, eclipses, conjunctions, star positions, risings/settings, mathematics,
---
DATING THE *SŪRYA SIDDHĀNTA* 457
geography, instrumentation and model-making. Great care has been taken to present detailed data and computation techniques in as compact a form as possible. The *Sūrya Siddhānta* is not a conventional textbook in the sense that it is too succinct and somewhat cryptic for a rank beginner. It is rather meant as a concise aid to instruction for the experienced teacher.
For the modern astronomer, the most tantalizing features in the *Sūrya Siddhānta* are the great cosmological cycles spanning billions of years, including in it an astonishingly accurate value for the Earth’s precessional motion. Who created these cycles and when – these are questions that appear exceedingly difficult to answer even approximately. A noteworthy point here, one that seems to have gone quite unnoticed, concerns the contribution of later Indian astronomers, or rather the lack of it. None of the later great Indian astronomers, Āryabhaṭṭa ($475$ AD), Brahmagupta ($600$ AD), etc can claim to have added anything of significance to the basic structure and framework of Indian astronomy. The great cycles are obviously the creation of a much older era of the Indian civilization; one which had access to vast resources of accurate observational data spanning hundreds if not thousands of years. As a vivid example of this, consider the fact that the *Sūrya Siddhānta* gives the movement of the sun’s slow-point (*maṇḍa*) as being $0.11$ seconds per year eastwards. While this value may not be an accurate one by modern standards, no one will contest the fact that the very awareness of this fine movement, including its correct direction, is clearly indicative of a significantly advanced level of astronomy.

## 3. THE *NAKṢATRA* SYSTEM

Chapter 8 of the *Sūrya Siddhānta* is devoted entirely for stellar data and that will be the focus of this current investigation. The stars mentioned therein are divided into two groups – the *nakṣatra* and non-*nakṣatra*. The *nakṣatra*, which are 28 in number, can be thought of as minor constellations close to or on the ecliptic. They are similar to the zodiacal constellations, only much smaller, with each *nakṣatra* containing typically 1 to 5 stars. The non-*nakṣatra* group is a small set containing just 7 individual stars that are mostly well away from the ecliptic. They are noted for their brilliance or are otherwise special in some way. In the current investigation we consider only the *nakṣatra* stars.
Each *nakṣatra* constellation spans about 13 degrees on the ecliptic and the significance of this will be immediately apparent to anyone familiar with the daily motion of our closest neighbor in space. The Moon moves about 13 degrees
---
458 INDIAN JOURNAL OF HISTORY OF SCIENCE
each day against the background of the fixed stars, making a full circle in about 28 days. Thus the Moon spends about a day in a *nakṣatra*. In Indian mythology the *nakṣatras* are the 28 wives of the Moon with each of whom he spends a day. This has been since ancient times the Indian method of keeping track of daily time — the *tithi*, or lunar-day.
A primary star, sometimes called junction-star, is defined for each *nakṣatra* constellation. Star’s data (position and brightness) is given in the *Sūrya Siddhānta*. One would expect the brightest star in a *nakṣatra* to be
**Table 1**

| No. | *Nakṣatra* | Junction Star | SS Bright | SS Long. | SS Lat. | Modern Long. | Modern Lat. |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Aśvinī | β-Arietis | 3 | $8^{\circ}$ | $10^{\circ}$ | $34^{\circ}$ | $8.5^{\circ}$ |
| 2 | Bharaṇī | 35-Arietis | 5 | $20^{\circ}$ | $12^{\circ}$ | $46.9^{\circ}$ | $11.3^{\circ}$ |
| 3 | Kṛttikā (Pleiades) | Merope | 3 | $37^{\circ} 30^{\prime}$ | $5^{\circ}$ | $59.7^{\circ}$ | $3.96^{\circ}$ |
| 4 | Rohiṇī | Aldebaran | 2 | $49^{\circ} 30^{\prime}$ | $-5^{\circ}$ | $69.8^{\circ}$ | $-5.5^{\circ}$ |
| 5 | Mṛgaśīrṣā | - | 5 | $63^{\circ}$ | $-10^{\circ}$ | - | - |
| 6 | Ārdrā | - | 3 | $67^{\circ} 20^{\prime}$ | $-9^{\circ}$ | - | - |
| 7 | Punarvasu | Pollux | 1 | $93^{\circ}$ | $6^{\circ}$ | $113.2^{\circ}$ | $6.7^{\circ}$ |
| 8 | Puṣya | δ-Cancri | 5 | $106^{\circ}$ | $0^{\circ}$ | $128.7^{\circ}$ | $0.1^{\circ}$ |
| 9 | Āśleṣā | - | 3 | $109^{\circ}$ | $-7^{\circ}$ | - | - |
| 10 | Maghā | Regulus | 2 | $129^{\circ}$ | $0^{\circ}$ | $149.8^{\circ}$ | $0.5^{\circ}$ |
| 11 | P. Phālguṇī | - | 2 | $144^{\circ}$ | $12^{\circ}$ | - | - |
| 12 | U. Phālguṇī | Denebola | 2 | $155^{\circ}$ | $13^{\circ}$ | $171.6^{\circ}$ | $12.3^{\circ}$ |
| 13 | Hasta | δ-Corvi | 2 | $170^{\circ}$ | $-11^{\circ}$ | $193.4^{\circ}$ | $-12.2^{\circ}$ |
| 14 | Citrā | Spica | 1 | $180^{\circ}$ | $-2^{\circ}$ | $203.8^{\circ}$ | $-2.1^{\circ}$ |
| 15 | Svāti | Arcturus | 1 | $199^{\circ}$ | $37^{\circ}$ | $204.2^{\circ}$ | $30.7^{\circ}$ |
| 16 | Viśākhā | - | 3 | $213^{\circ}$ | $-1^{\circ} 30^{\prime}$ | - | - |
| 17 | Anūrādhā | - | 3 | $224^{\circ}$ | $-3^{\circ}$ | - | - |
| 18 | Jyeṣṭhā | Antares | 1 | $229^{\circ}$ | $-4^{\circ}$ | $249.8^{\circ}$ | $-4.6^{\circ}$ |
| 19 | Mūla | - | 3 | $241^{\circ}$ | $-9^{\circ}$ | - | - |
| 20 | P. Āṣāḍhā | - | 5 | $254^{\circ}$ | $-5^{\circ} 30^{\prime}$ | - | - |
| 21 | U. Āṣāḍhā | - | 5 | $260^{\circ}$ | $-5^{\circ}$ | - | - |
| 22 | Abhijit | Vega | 1 | $266^{\circ} 40^{\prime}$ | $60^{\circ}$ | $285.32^{\circ}$ | $61.7^{\circ}$ |
| 23 | Śravaṇā | Altair | 2 | $280^{\circ}$ | $30^{\circ}$ | $301.8^{\circ}$ | $29.3^{\circ}$ |
| 24 | Śraviṣṭhā | β-Delphini | 2 | $290^{\circ}$ | $36^{\circ}$ | $316.3^{\circ}$ | $31.9^{\circ}$ |
| 25 | Śatabhiṣaj | - | 4 | $320^{\circ}$ | $-0^{\circ} 30^{\prime}$ | - | - |
| 26 | P. Bhādrapada | - | 4 | $326^{\circ}$ | $24^{\circ}$ | - | - |
| 27 | U. Bhādrapada | - | 4 | $337^{\circ}$ | $26^{\circ}$ | - | - |
| 28 | Revatī | - | 4 | $359^{\circ} 50^{\prime}$ | $0^{\circ}$ | - | - |

---
DATING THE *SŪRYA SIDDHĀNTA* 459
denoted its junction star and indeed this is often the case, though not always. Table 1 shows the *nakṣatras*, the junction stars and their brightness level according to the *Sūrya Siddhānta* (SS) and the data for longitude and latitude including the modern (J2000) equivalents. The *Sūrya Siddhānta* defines 5 levels of brightness, the brightest being level 1. The P and U initials in *nakṣatra* names stand for ‘*pūrva*’ and ‘*uttara*’, meaning ‘prior’ and ‘latter’ respectively. Note that the coordinates are ecliptical.
The *Sūrya Siddhānta* provides two ways of identifying a junction star – by its brightness and by its position within the *nakṣatra*. Even so, several junction stars, especially the fainter ones, are yet to be clearly identified. These uncertain junction stars have been left out of the current investigation and also out of Table 1. We will consider herein only those junction stars that have been unambiguously identified. The information in this table is our base data for this analysis.

## 4. ALTERATIONS OF THE TEXT OVER TIME

There are many indications that the *Sūrya Siddhānta* has undergone several modifications in the past which in itself is a clue to the great age of the text. An enquiry into these alterations is an indispensable step for us before we attempt to determine the age of the text through its data. In this section we will examine in detail each of these clues.

### 4.1. Indication in the text itself

A very first indication of change is provided in the text itself. In the beginning verses of the first chapter we observe:
> This is the very same original text-book that the Sun of old promulgated:
> Only, by reason of the revolution of the Ages, is here a difference of times
> \- Chap 1, Verse 8.
This is a clear confession that the data in the text has been updated periodically due to ‘the revolution of the ages’, in other words, due to precessional changes. There is also the implication that apart from updates to the data, the text itself has been relatively untouched.

### 4.2. Change of data precision

The opening verse of chapter 8 reads:
---
\* Formerly Scientist, Indian Space Research Organization; Currently Consultant, Washington DC. 10209 Leslie Ct, #201, Burke, VA 22015, USA. e-mail: anilkn_ban@hotmail.com

[^1]: Bailly, J.S., *Traité de l’astronomie indienne et orientale*, 1787

[^2]: Weber, A., *Über den Vedakalender Namens Jyotisham*, Berlin 1862.

[^3]: Burgess, E., *Sūrya Siddhānta - A Text Book of Hindu Astronomy*, 1858.

[^4]: Thibaut G., Dvivedi M.S., *The Pañcasiddhāntikā, Astronomical work of Varāha Mihira*, 1889

460 INDIAN JOURNAL OF HISTORY OF SCIENCE
Now are set forth, the positions of the junction-stars in minutes  
If the share of each be multiplied by ten and increased by the past  
junction-stars -  
The result will be the longitude  
\- Chap 8, Verse 1.
The first line says that longitudes are given in arc-minutes, or $1/60^{\text{th}}$ of a degree. This is well and good as it conforms to the fact that the best precision achievable with the naked eye is about 1 minute of arc. The second line indicates how to calculate the longitude for a star. For example, for the first *nakṣatra* (*Aśvinī*), longitude is given as 48 in the text. We are called upon to multiply this by 10 to get the actual longitude in minutes (i.e. 480 minutes, or 8 degrees). The question naturally arises – if the longitude is 480 minutes then why not indicate this value directly, instead of $48 \times 10$. While appearing to be a convoluted way of presenting data this second line is in fact a subtle way of indicating that a precision of 10 minutes of arc is intended for this longitudinal data.
Now based on the above observation regarding longitudinal precision and also the fact that the unit of measurement is minutes-of-arc, we expect to see several values with fractional degrees in the longitudinal data. However a glance at the $SS$ longitudinal data column of Table 1 throws up a puzzle. Nearly 85% of the data has been rounded off to the nearest degree! This is akin to using yards instead of miles to describe the distance between two cities, but then rounding up the value (in yards) to whole miles anyway. Given the higher-precision unit employed by the text, there appears no plausible reason to assume that the original data was in the lower-precision form that we find it today. Original high precision data was apparently overwritten with values of lower precision at a later era, perhaps due to lack of better instrumentation. A more likely reason for this could be the dawning of awareness that great precision in longitude is a wasted effort since the value changes fairly rapidly (in astronomical terms), the rate of change being one degree in 71 years.
Of the remaining 15% stars for which longitudinal data appears in fractions of a degree, some have a fractional part of 30 arc-minutes, or half a degree. Disregarding these, what remains are 3 *nakṣatras* with fractional values of longitude – *Ārdrā* (67°20′), *Abhijit* (266°40′) and *Revatī* (359°50′). *Abhijit* (*Vega*) is a special case and is discussed in section 4.5 below. Why only *Ārdrā* and *Revatī* should be left out of the rounding process is not easy to see. In any case, we may conclude with reasonable confidence that at some point in the history of the text,
DATING THE *SŪRYA SIDDHĀNTA* 461
older longitudinal data with 10-minute precision was overwritten by data with the lower precision of half-a-degree.

## 4.3. Longitude updates

Next we look at the longitudinal data in detail. Longitudinal data is affected by axial precession which, as mentioned, results in fairly rapid changes to the star’s position – nearly one degree every 71 years. We therefore expect to see a sizable difference between the longitudinal data in the *Sūrya Siddhānta* and its modern equivalent. This difference is a measure of the time elapsed between the last update to the *Sūrya Siddhānta* and 2000 AD. We observe from Table 1 that for several junction stars, though not all, an approximate difference of about 20 degrees exists between the two. From this we may infer that the last update to the longitudinal data was made $20 \times 71 (=1420)$ years ago, or about 580 AD.
An important question regarding this last update to the longitudinal data is this — was the update done using values from actual observation or was it done by simply adding to all longitudes a fixed value, the so-called precessional increment? As noted, a few stars do show a difference in longitude in excess of 20 degrees though the excess amount is not high enough to rule out observational error. A glance at the longitudes of Spica (*Citrā*) and Arcturus (*Svātī*) however settles the matter instantly. Modern longitudes of these stars are very close (203.84° and 204.23° respectively). The *Sūrya Siddhānta* depicts them as 19 degrees apart! Even for 580 AD this is way beyond what can be considered an observational error margin. Thus we may conclude that the last longitudinal update, which occurred about 580 AD, was not done using actual observational data but simply by adding a fixed increment to all *nakṣatra* longitudes.

## 4.4. Latitude updates

Moving on to latitudinal data, we make an intriguing discovery – in the *Sūrya Siddhānta* longitudes and latitudes are specified in different units! While longitudinal values are given in minutes-of-arc, for greater accuracy needless to say, those for latitudes are given in degrees with a precision of half-a-degree. This appears to indicate that latitudinal data was considered less significant than the longitudinal, which turns out to be a saving grace, as we will see shortly.
462 INDIAN JOURNAL OF HISTORY OF SCIENCE
Latitudinal data, unlike the longitudinal, is unaffected by axial precession. But it can change due to two other reasons: (1) Planetary precession and (2) Proper motion of the star. Both these changes are exceedingly slow, requiring several thousand years to show any perceptible change to the naked eye. Here then is the main difficulty in using the *Sūrya Siddhānta*’s latitudinal data to determine its age – we are working with a variable that changes very slowly and to compound matters the data we have is of low precision. Half a degree in latitude this way or that translates to several thousand years this way or that. The one exception to this imbroglio would be if the star had an exceeding fast proper motion, and here we have a savior in Arcturus (*Svātī*). This star has one of the fastest proper motions in the sky (more than 2 seconds per year). Comparing the *Sūrya Siddhānta* latitudinal data for Arcturus with its modern value is an eye opener. There is a difference of more than 6 degrees! Here is then another hint of the great age of this text. But let us be cautious - all of the 6 degrees has not been caused by proper motion alone; some of it, as we’ll see later, is due to planetary precession as well. Thus, after examining the latitudinal data, we conclude that updates of star latitudes have not been done at least for several thousand years and most likely this is due to its lower status as compared to the longitudinal data, which has turned out to be advantageous as it can help us determine the epoch of the text or, at a minimum, the era of the last update to the latitudes.

## 4.5. Nakṣatra list revised

Lastly, we will briefly discuss in passing a well known modification to the *Sūrya Siddhānta* in the very distant past. This early amendment changed the very foundation of the *nakṣatra* system. The 28-*nakṣatra* scheme was changed to 27. Most scholars are of the opinion that this change was made mainly to facilitate easy calculation[^3], [^5]. 360 degrees contain 21600 minutes. Dividing this latter number by 28 gives a fractional quantity while dividing by 27 produces a nice round 800. Whatever the reason, one *nakṣatra* had to be discarded and the straw fell on Vega (*Abhijit*), most likely due to the fact that at 60° north it is the furthest *nakṣatra* from the ecliptic. After removing Vega, there was the need to ‘adjust’ the other *nakṣatras* - from covering 12.86 degrees on the ecliptic to the newer $13 \frac{1}{3}$ degrees of arc each. We can today see the after-affects of this change. Several junction stars have been pushed to the very edge of their *nakṣatra* and one *nakṣatra* is without a junction-star. While this is an interesting topic we will not continue further on this, apart from recognizing that a fundamental change was made to the system and Vega (*Abhijit*) was discarded from the *nakṣatra* set.
DATING THE *SŪRYA SIDDHĀNTA* 463

## 5. THE ANALYSIS SCHEME

Having examined these modifications over time to the *Sūrya Siddhānta*, we are faced with the manifest conclusion that its longitudinal data may have been updated several times and therefore that data may not serve our purpose of determining the age of the text. Furthermore, the latitudinal data appears to be untouched, at least for several thousand years and therefore it appears promising to our quest.
Latitudinal data, as we saw, is influenced by planetary precession (or ecliptic obliquity) as well as the proper motion of the star. We could therefore consider an analysis scheme where we move back in time by applying the proper motion in reverse to each star and simultaneously making time-related ecliptical changes using well known formulae[^6] and then check to see if we get a match with the latitudes given in the *Sūrya Siddhānta* at some point in time. However this approach has the following difficulties:
1. **Accuracy of numerical formulas:** The astronomical formulae we will use are empirical in nature. They are accurate only for limited ranges of time. For periods that cover thousands of years their accuracy is suspect.
2. **Limits of current knowledge:** The Solar System is a conglomeration of several objects which exert varying influences on the Earth’s orbit. There may be long term phenomena and variations that are as yet unknown. Also the empirical formulae do not consider the motion of the Solar system itself.
To get around these limitations we will try a brute-force method. We will use the power of the computer to examine every possible combination of the variables, down to a fine level of granularity and filter out the results using the expected conditions.
The quantities which will vary are the following:
1. Time (which includes proper motion)
2. Ecliptic Obliquity
3. Ecliptic Node location
4. Vertical motion of the ecliptic
The following figure 1 shows a schematic of these variations. More details are provided in the next section.
464 INDIAN JOURNAL OF HISTORY OF SCIENCE

![Fig. 1. Physical View of the Analysis Scheme](media/p10_page.png)

*Fig. 1. Physical View of the Analysis Scheme*

<!-- figure-resolved-page-render: page=10 image=media/p10_page.png -->

<!-- figure-meta: page=10, position=middle, type=diagram -->

## 6. THE COMPUTING SCHEME

As mentioned, our basic approach will be to apply the proper motion in reverse to each junction star, going backwards in time. To this basic scheme we will add further complexity in terms of varying the ecliptic’s inclination, node location and sink variation. Fig. 2 depicts pictorially the computing scheme. Details are as follows.

### 6.1 The Time Loop (T-loop)

This is the outermost loop in the computation – the time or T-loop. Starting from the year 2000 AD, we go backwards in time in steps of 50 years. For a typical star’s proper motion of, say, 0.05 arc seconds per year, a 50-year timeframe translates to 2.5 arc seconds of movement which is granular enough for our purpose.

[^3]: Burgess, E., *Sūrya Siddhānta - A Text Book of Hindu Astronomy*, 1858.

[^5]: Kaye, G.R., *Hindu Astronomy, Ancient Science of the Hindus*, Cosmo Publications, New Delhi, 1981.

[^6]: Meeus, J, *Astronomical Algorithms*, Willmann-Bell Inc, 2000.

DATING THE SŪRYA SIDDHĀNTA 465

![Fig. 2. The Computing Scheme](media/p11_page.png)

*Fig. 2. The Computing Scheme*

<!-- figure-resolved-page-render: page=11 image=media/p11_page.png -->

<!-- figure-meta: page=11, position=top, type=diagram -->

Fig. 2. The Computing Scheme
Modern star data (location and proper motion) is usually found in Equatorial Coordinates (right ascension, declination). However as the Sūrya Siddhānta data is all in Ecliptical Coordinates (longitude, latitude) we will convert everything to that system. After applying a star’s proper motion, PM, in arc-seconds/year for time-period t years to the J2000 coordinates ($\text{RA}_{\text{J2000}}$, $\text{Dec}_{\text{J2000}}$), the resultant Equatorial values are converted to Ecliptic Coordinates ($\text{Long}_t, \text{Lat}_t$) using standard conversion formulae[^6]. These steps are given as follows:

$$\text{RA}_t = \text{RA}_{\text{J2000}} - \text{PM} * t / 3600 \dots (1)$$

$$\text{Dec}_t = \text{Dec}_{\text{J2000}} - \text{PM} * t / 3600 \dots (2)$$

$$\text{Long}_t, \text{Lat}_t = \text{Transform1} (\text{RA}_t, \text{Dec}_t) \dots (3)$$

All further computation is carried out in Ecliptic Coordinates. The next 3 steps will transform the resultant Ecliptic Coordinates for various ecliptic variations at time t years (counting backwards from 2000 AD).

## 6.2 The Ecliptic-Node-Location sub-loop (N-loop)

It is well known that the plane of the ecliptic is not fixed but has a see-saw movement around the ecliptic nodes $n_1$ and $n_2$ (refer Fig. 1). Also, these
---
466 INDIAN JOURNAL OF HISTORY OF SCIENCE
nodes themselves are not fixed, but have a movement along the ecliptic (N in Fig. 1). So next we simulate this node movement along the ecliptic. A change of node location changes only the longitudinal position value of a star. Latitude remains unchanged. The second loop (inside the time loop) is thus the ‘node loop’ or N-loop. Herein we will vary the node location of the ecliptic from 0 to 180 degrees in steps of $1/60^{\text{th}}$ degree or 1 minute. The resultant Longitudinal Coordinate, $\text{Long\_N}_t$ is obtained as follows:

$$\text{Long\_N}_t = \text{Long}_t + \Delta N \dots (4)$$

where $\Delta N$ denotes the change in node location, measured in degrees from the J2000 system origin (O).
It may be noted that we vary N from 0°–180°, and not 0°–360°. This is because there are 2 nodes. When one node traverses 0° to 180°, the other node simultaneously covers 180° to 360°. In the next section we discuss varying the ecliptic inclination for both positive and negative angles. An ecliptic inclination of say 1° and $\Delta N = 120^{\circ}$ turns out to have the same spatial orientation as an ecliptic inclination of -1° and $\Delta N = (120^{\circ} + 180^{\circ})$. Thus varying the node location from 0° to 360° simply gives the same result twice; a situation we avoid by varying N from 0°–180° only.

## 6.3 The Ecliptic Inclination sub-loop ($\phi$-loop)

As mentioned, the ecliptic has a see-saw motion around a line of nodes. This is primarily caused by planetary precession. The next variation we simulate is this movement of the ecliptic. This motion currently has a magnitude of about 47 arc-seconds per century[^6]. We will vary the inclination of the ecliptic up to 3 degrees positive and negative in steps of 1 arc second, which should provide a sufficient level of granularity and time span. This happens inside the N-loop, and is called the ‘Ecliptic Inclination loop’ or $\phi$-loop. Note that unlike the N-variation, the $\phi$-variation results in changes to both Longitude and Latitude. The transform is similar to (3) with the difference that here the obliquity, $\phi$, is supplied as a variable parameter as well.

$$\text{Long}_\phi, \text{Lat}_\phi = \text{Transform2} (\text{Long\_N}_t, \text{Lat}_t, \phi) \dots (5)$$

The resultant Ecliptic Coordinates ($\text{Long}_\phi, \text{Lat}_\phi$) are the star coordinates after applying the current iteration’s value of Ecliptic Node location and Ecliptic Obliquity. There is one other variation of the Ecliptic that we must consider in this
---
DATING THE SŪRYA SIDDHĀNTA 467
computational simulation. This variation is not usually taken into account when calculating for several hundred or even couple thousand years, but must be considered for longer periods involving several thousand years. That is discussed next.

## 6.4 The Sink Loop (S-loop)

This loop was introduced at a later stage during this research because not enough matches could be obtained by the assumption that the ecliptic nodes were moving only in the ecliptic plane. The fourth and final loop, inside the $\phi$-loop, is the ‘sink’ or S-loop, where the nodes are (also) moving in the vertical plane, up and down. Here we introduce a ‘vertical’ or sinking/rising motion to the ecliptic plane up to 1 degree, in steps of $1/60^{\text{th}}$ of a degree.

$$\text{Lat}_s = \text{Lat}_\phi + \Delta S \dots (6)$$

$\text{Lat}_s$ is the value obtained by adding the iteration’s sink value ($\Delta S$) to the Latitude obtained after the $\phi$-loop. We do not bother calculating the Longitude at this step since we won’t be using that. The $\text{Lat}_s$ is then the final value in the looping. Each star’s value for this variable is checked against its latitudinal constraints which are detailed in the next section.

## 6.5 Filter Constraints

A computational scheme will usually produce an enormous amount of information, including combinations which are doubtful or even impossible. To weed out the impossible or unlikely combinations we introduce constraints on the results. The constraints we use here are shown in Table 2 and are quite straightforward. They are simply the Latitude data found in the Sūrya Siddhānta for each star with a cushion of ±0.5°. The cushion value was chosen keeping in mind the Sūrya Siddhānta’s latitudinal precision of half-a-degree. The one exception to this rule is for $\delta$-Corvi (Hasta). The minimum latitude for that star had to be moved down another 0.5° to enable a match to be found.
A variable set was considered ‘matched’ only if it passed all the above constraints simultaneously.

## 6.6 Coding Language

The code for the simulation was developed and run on a computer running Windows XP. Initially the code was written in Java. However the time taken for
---
468 INDIAN JOURNAL OF HISTORY OF SCIENCE
Table 2

| No. | Nakṣatra | Modern | Less than | Greater than |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Aśvinī | $\beta$-Arietis | 10.5° | 9.5° |
| 2 | Bharaṇī | 35-Arietis | 12.5° | 11.5° |
| 3 | Kṛttikā | Merope | 5.5° | 4.5° |
| 4 | Rohiṇī | Aldebaran | -4.5° | -5.5° |
| 5 | Punarvasu | Pollux | 6.5° | 5.5° |
| 6 | Puṣya | $\delta$-Cancri | 0.5° | -0.5° |
| 7 | Maghā | Regulus | 0.5° | -0.5° |
| 8 | U. Phālgunī | Denebola | 13.5° | 12.5° |
| 9 | Hasta | $\delta$-Corvi | -10.5° | -12.0° |
| 10 | Citrā | Spica | -1.5° | -2.5° |
| 11 | Svātī | Arcturus | 37.5° | 36.5° |
| 12 | Jyeṣṭhā | Antares | -3.5° | -4.5° |
| 13 | Abhijit | Vega | 60.5° | 59.5° |
| 14 | Śravaṇā | Altair | 30.5° | 29.5° |
| 15 | Śraviṣṭhā | $\beta$-Delphini | 36.5° | 35.5° |

more granular variations was found to be of the order of several hours and so found unacceptable. The code was rewritten in C++ whereby an acceptable performance was obtained.

# 7. RESULTS

It was observed that for the constraints specified, a match could not be obtained for two stars – Vega (Abhijit) and $\beta$-Delphini (Śraviṣṭhā). For variable combinations where favorable matches were found for other stars, these two were found to be more than 2 degrees off the expected latitude. For the remaining nakṣatra stars several matches were obtained in the timeframe 7300-7800 BC.
Fig. 3 shows the Ecliptic Obliquity ($\phi$) v/s Time for the simulation. It can be seen that favorable matches were obtained for values of $\phi$ in the neighborhood of 1.3°.
Similarly Fig. 4 shows the results for Ecliptic Node location (N) v/s Time. It is seen that favorable matches were obtained for a narrow band around -52 and -53 degrees for N.
Results of Sink values for favorable matches have not been graphed because a very narrow range for it was obtained for all matching combinations. This range is +0.58° to +0.6°.
---
DATING THE SŪRYA SIDDHĀNTA 469

<!-- figure-resolved-page-render-hidden: image=media/p15_page.png caption="Fig. 3. Ecliptic Obliquity (φ) v/s Time for favorable matches obtained" -->

<!-- figure-meta: page=15, position=top, type=graph -->

Fig. 3. Ecliptic Obliquity ($\phi$) v/s Time for favorable matches obtained

![Fig. 4. Ecliptic Node Location (N) v/s Time for favorable matches obtained](media/p15_page.png)

*Fig. 4. Ecliptic Node Location (N) v/s Time for favorable matches obtained*

<!-- figure-resolved-page-render: page=15 image=media/p15_page.png -->

<!-- figure-meta: page=15, position=bottom, type=graph -->

Fig. 4. Ecliptic Node Location (N) v/s Time for favorable matches obtained

[^6]: Meeus, J, *Astronomical Algorithms*, Willmann-Bell Inc, 2000

470 INDIAN JOURNAL OF HISTORY OF SCIENCE
How do these results appear physically? Fig 5 shows a schematic view of what these results look like on the ecliptic plane. An average value in the matched range has been chosen for each variable. The figure shows the current position of the ecliptic plane (J2000) and the computed position of the ecliptic for the period around 7500 BC at which favorable matches were obtained. The ecliptic node location (N) is shown to be $53^\circ$ in the eastwards direction. Both nodes have ‘sunk’ by $0.6^\circ$ and the ecliptic angle is $1.3^\circ$ in relation to the J2000 position. $N_s$ is the node location value after sink-correction has been applied, as explained later. This value is about $26^\circ$.

![Fig. 5. Physical View of the Simulation Results](media/p16_page.png)

*Fig. 5. Physical View of the Simulation Results*

<!-- figure-resolved-page-render: page=16 image=media/p16_page.png -->

<!-- figure-meta: page=16, position=middle, type=diagram -->

J : Ecliptic Plane (J2000)
O : Ecliptic Origin (J2000)
$n_{J2000}$ : Ecliptic node (J2000)
BC : Ecliptic Plane (7500 BC)
$n_{bc}$ : Ecliptic node (7500 BC)
N : $53^\circ$
$N_s$ : $26^\circ$
$\phi$ : $1.3^\circ$
S : $0.6^\circ$
**Fig. 5.** Physical View of the Simulation Results
It would be useful to see how the latitudinal errors decrease with time during the simulation until it drops below the match-threshold that we look for. Fig. 6 shows such a variation of the sum of Latitudinal errors with time for a set
---
DATING THE *SŪRYA SIDDHĀNTA* 471
of average values in the matched range, namely $N=53^\circ$, $\phi =1.3^\circ$ and $S=0.6^\circ$. The sum of Latitudinal errors is the absolute difference between the final Latitude obtained in each time-loop, $Lat_s$, and the Latitude given in the *Sūrya Siddhānta*, $Lat_{ss}$, summed over all stars under consideration.

$$\text{Sum of Errors} = \sum |Lat_s - Lat_{ss}| \dots (7)$$

It can be seen that the sum of errors decreases as we move back in time reaching a minimum around 8000 BC. The solid line is for all stars while the dashed one is for all stars without Arcturus (Svātī). This figure shows clearly the strong influence of the rapidly-moving Arcturus on the results. In the next section we will study these results and measure how they fare when matched with our current knowledge of ecliptic motion.

![Fig. 6. Variation of the Sum of Latitudinal Errors v/s Time](media/p17_page.png)

*Fig. 6. Variation of the Sum of Latitudinal Errors v/s Time*

<!-- figure-resolved-page-render: page=17 image=media/p17_page.png -->

<!-- figure-meta: page=17, position=middle, type=graph -->

**Fig. 6.** Variation of the Sum of Latitudinal Errors v/s Time

## 8. DISCUSSION

Let us now examine how these results stand up against well known empirical formulae for Ecliptic Obliquity and Node-Location variation.
Fig. 7 shows the variation of Ecliptic-Obliquity with time. The solid line represents the well known empirical formula for the obliquity (J2000 Reference) from Meeus[^6], reproduced below for convenience:
---
472 INDIAN JOURNAL OF HISTORY OF SCIENCE

![Fig. 7. Comparison of Empirical and Computational results for Ecliptic Obliquity](media/p18_page.png)

*Fig. 7. Comparison of Empirical and Computational results for Ecliptic Obliquity*

<!-- figure-resolved-page-render: page=18 image=media/p18_page.png -->

<!-- figure-meta: page=18, position=top, type=graph -->

**Fig. 7.** Comparison of Empirical and Computational results for Ecliptic Obliquity

$$\eta = 47''.0029t - 0''.03302t^2 + 0''.000060t^3 \dots(8)$$

where $\eta$ is the ecliptic obliquity and $t$ is time in centuries. The dots in Fig. 7 represent favorable computational matches obtained for the *nakṣatra* stars in the current investigation. It is heartening to see that there is an excellent match between them. Both values are in the region of $1.3^\circ$ for the 7300-7800 BC timeframe.
Similarly Fig. 8 shows the variation of Ecliptic-Node-Location with time. The solid line, as earlier, depicts the empirical formula (J2000 Reference) from Meeus[^6] reproduced below for convenience:

$$\Pi = 174^\circ.876384 - 869''.8089t + 0''.03536t^2 \dots(9)$$

where $\Pi$ is the ecliptic node location with respect to the J2000 location and $t$ is time in centuries. A little explanation is required to interpret and correlate this figure in terms of the earlier results we obtained. Note that the empirical formula uses the opposite node as compared to that produced by the computational results. Therefore we have to add $180^\circ$ to the computational result value for $N$ to get the equivalent for the empirical (i.e. $180^\circ + 53^\circ$).
---
DATING THE *SŪRYA SIDDHĀNTA* 473

![Fig. 8. Comparison of Empirical and Computational results for Ecliptic Node Location](media/p19_page.png)

*Fig. 8. Comparison of Empirical and Computational results for Ecliptic Node Location*

<!-- figure-resolved-page-render: page=19 image=media/p19_page.png -->

<!-- figure-meta: page=19, position=top, type=graph -->

**Fig. 8.** Comparison of Empirical and Computational results for Ecliptic Node Location
The solid circles in Fig. 8 represent raw results for the node location. It can be seen that there is quite a bit of mismatch between the raw computed results and the empirical curve, an average error of about $35^\circ$. Fig. 8 also shows, using unfilled circles, the results after sink-correction is applied. Sink correction details are shown on upper right. Using standard formulae[^7], applying sink of $0.6^\circ$ for an ecliptic inclination of $1.33^\circ$ produces a longitudinal movement of about $27^\circ$. This is the sink-correction amount to be subtracted from the node location values in the raw results. The sink-corrected value is shown pictorially in Fig 5 as $N_s$. This correction reduces the Node-Location error to about $8^\circ$.
In physical terms, it would be interesting to think about what constitutes the ‘sink’ movement of the ecliptic. From this computational study, all we have obtained is that applying a vertical movement of $-0.6^\circ$ to the ecliptic gives an excellent match with the data found in the *Sūrya Siddhānta*. It is additionally heartening to note that there is very little variation in this value for all the stars under consideration, the said variation being $0.58^\circ - 0.6^\circ$. Whether the ‘sink’ constitutes a vertical movement of the Solar System itself is a point to consider.
---
474 INDIAN JOURNAL OF HISTORY OF SCIENCE
Lastly it is to be noted that there are indications in the *Sūrya Siddhānta* that appear to conflict with these results. At two places in the book is mentioned that the obliquity of the Earth’s axis of rotation is 24 degrees:
> The sine of the greatest declination is 1397
> By this multiply any sine and divide by radius ,etc
> — Chap 2, Verse 28.
> The sun during his northern and southern progress revolves directly over a $15^{\text{th}}$ part of the Earth’s circumference; etc…
> — Chap 12, Verse 68.
The standard radius in the Indian astronomical system is 3438. What is implied in the first verse is that dividing 1397 by this value will yield the sine of the greatest declination, which turns out to be $24^\circ$. Again, from the second verse, we note that a fifteenth part of $360^\circ$ is $24^\circ$. Now while this second verse may be taken in a lighter spirit as a general indication of the obliquity, the first verse cannot be considered likewise. It is a clear statement that the greatest declination was 24 degrees exactly.
Fig 9 shows the variation of the obliquity of the earth’s axis going backwards in time using an empirical relation[^6]. It can be seen that the obliquity was 24

![Fig. 9. Variation of the Earth’s Axis’ Inclination v/s Time](media/p20_page.png)

*Fig. 9. Variation of the Earth’s Axis’ Inclination v/s Time*

<!-- figure-resolved-page-render: page=20 image=media/p20_page.png -->

<!-- figure-meta: page=20, position=bottom, type=graph -->

**Fig. 9.** Variation of the Earth’s Axis’ Inclination v/s Time

[^6]: Meeus, J, *Astronomical Algorithms*, Willmann-Bell Inc, 2000

[^7]: Smart, W.M., *Textbook on Spherical Astronomy*, Cambridge University, Sixth Ed, 1977

DATING THE *SŪRYA SIDDHĀNTA* 475
degrees at about 3000 BC. Allowing for an error of 10 minutes of arc will take this value back to about 5000 BC which is still quite a bit away from our computational result of 7500 BC, at which date the obliquity was a little less than $24\frac{1}{4}$ degrees. We are left to conjecture whether the empirical relation for the Earth’s obliquity that we used can really be extended as far back as 7500 BC. The other possibility, one that may not be too far fetched, is that perhaps the obliquity value was updated in the *Sūrya-Siddhānta* around 3000 BC – one of many changes this ancient text has seen.

## 16. CONCLUSIONS

Conclusions that may be drawn from this review of the *Sūrya Siddhānta*’s stellar data and computational simulation of its *nakṣatra* latitudinal data are as follows:
1. The *Sūrya Siddhānta* has been updated several times in the past. The last update took place in the vicinity of 580 AD when *nakṣatra* data appears to have been updated by adding a fixed precessional increment to all longitudes. Latitudinal data, which was deemed of lesser significance, has been untouched, at least for several thousand years.
2. Longitudinal data was originally present with a precision of 10 minutes-of-arc. This high-precision data was subsequently overwritten at a later date by data with the lower precision of half-a-degree.
3. Using computer simulation of *nakṣatra* latitudinal data by varying ecliptic-obliquity, ecliptic-node-location and ecliptic-sink together with proper motion, a match for the *Sūrya Siddhānta* latitudinal data was obtained in the timeframe 7300-7800 BC.
4. Computational results for ecliptic-obliquity was seen to match exceptionally well with the well-known empirical formula in current use.
5. The raw computational results for ecliptic-node-location were quite off the mark when compared with the empirical formula in current use. However the error was substantially reduced when sink correction was applied.
A major assumption made in this investigation is that star proper motion is fairly constant over several thousands of years. The results may be adversely affected if this were found untrue for the star set under consideration.
476 INDIAN JOURNAL OF HISTORY OF SCIENCE

## REFERENCES

1. Bailly, J.S., *Traité de l’astronomie indienne et orientale*, 1787
2. Weber, A., *Über den Vedakalender Namens Jyotisham*, Berlin 1862.
3. Burgess, E., *Sūrya Siddhānta - A Text Book of Hindu Astronomy*, 1858.
4. Thibaut G., Dvivedi M.S., *The Pañcasiddhāntikā, Astronomical work of Varāha Mihira*, 1889
5. Kaye, G.R., *Hindu Astronomy, Ancient Science of the Hindus*, Cosmo Publications, New Delhi, 1981
6. Meeus, J, *Astronomical Algorithms*, Willmann-Bell Inc, 2000
7. Smart, W.M., *Textbook on Spherical Astronomy*, Cambridge University, Sixth Ed, 1977
