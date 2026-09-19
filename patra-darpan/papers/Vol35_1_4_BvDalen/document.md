# Origin of the Mean Motion Tables of Jai Singh

- Author Display: B V Dalen
- Year: 2000
- Journal Label: IJHS-35-2000-Issue-1
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol35_1_4_BvDalen.pdf

<!-- source: gemini page-chunk extraction -->

*Indian Journal of History of Science, 35(1), 2000, 41-66*

# ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH

BENNO VAN DALEN*
(Received 28 September 1999)
In two articles in this journal the relationship has been studied between the Persian *Zīj-i Muḥammad Shāhī*, completed in Jaipur around 1735 under Sawā'ī Jai Singh, and the astronomical tables of Philippe de La Hire, printed in Paris in 1727. Mercier concluded that Jai Singh's planetary tables were all taken directly from La Hire and do not depend on observations made in India. On the other hand, Sharma maintained that the planetary tables in the *Zīj-i Muḥammad Shāhī* are independent from those of La Hire.
In this article, the methods by which Jai Singh's tables for planetary mean motion were computed will be investigated in detail. First it will be shown that the initial mean positions in the *Zīj-i Muḥammad Shāhī* were calculated from La Hire's mean motion tables by adding the entries for the appropriate numbers of years, months and days and applying a correction for a difference in geographical longitude between Paris and Delhi of $73^\circ 30'$.
Next, the mean motion parameters underlying Jai Singh's tables will be determined by means of recently introduced mathematical techniques and computer programs. It will be shown that the daily mean motions were calculated from particular values found in La Hire's tables. Our recomputations of Jai Singh's tables show only incidental differences of at most a couple of sexagesimal fourths of a degree. We conclude that the mean motion tables in the *Zīj-i Muḥammad Shāhī* were in fact derived from the tables of La Hire, thus confirming Mercier's result.
**Keywords:** Least Number of Errors Criterion (LNEC), mean motion tables, Philippe de La Hire, Sawā'ī Jai Singh, *Tabulae astronomicae Ludovici Magni*, *Zīj-i Muḥammad Shāhī*, *Zīj-i Sulṭānī*.
***
42 INDIAN JOURNAL OF HISTORY OF SCIENCE

## INTRODUCTION

Sawā'ī Jai Singh (or Savāī Jayasiṃha, 1688-1743) was Maharajah of Amber from 1700 to his death.[^1] He founded the city of Jaipur in 1727 and built large astronomical observatories with masonry instruments in Delhi, Jaipur, Ujjain, Mathura, and Benares.
One of the most well-known works produced by Jai Singh's astronomers is a Persian astronomical handbook with tables called the *Zīj-i Jadīd-i Muḥammad Shāhī* (c. 1735), which was named after the Moghul emperor who came to the throne in 1719.[^2] In an article in this journal, Mercier (1984, pp. 157-158; see also Pingree 1987, pp. 323-324) has shown that much of the trigonometrical and spherical-astronomical material in the *Zīj-i Muḥammad Shāhī* was taken over from the *Zīj-i Sulṭānī* of Ulugh Beg (c. 1440). Only the tables dependent on the obliquity of the ecliptic or on geographical latitude were recomputed, for which Jai Singh's newly observed obliquity value $23;28$ and the latitudes of Delhi and Jaipur were used. On the other hand, Mercier (pp. 145-147) asserts that the planetary tables in the *Zīj-i Muḥammad Shāhī* are "identical" with those in the *Tabulae astronomicae Ludovici Magni* of Philippe de la Hire (second edition 1702, reprinted in 1727), apart from the use of the Islamic calendar instead of the Julian and a change of meridian from Paris to Delhi. He therefore concludes that the planetary mean motions in the *Zīj* are not the result of observations made in India. This last aspect is disputed by Sharma (1990 and 1995, pp. 243-250), who unsuccessfully tries to recompute Jai Singh's mean motion tables from those of La Hire and, on the basis of a comparison of the underlying mean motions in an Arabic year, states that the parameters in the two works are "totally different".
The purpose of this article is to establish the precise method by which the mean motion tables in the *Zīj-i Muḥammad Shāhī* were computed. First we will analyse the origin of Jai Singh's epoch values, the initial mean positions for February 20, 1719 (Gregorian). Then we will determine the values for the daily mean motion underlying the tables in the *Zīj* as accurately as possible and investigate the way in which these parameters could have been obtained. We have made use of the manuscript of the *Zīj-i Muḥammad Shāhī* from the Arabic and Persian Research Institute in Tonk (Rajasthan). Because of lack of space, we
***
ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 43
cannot include the complete tables that are analysed in this article. Sharma reproduced Jai Singh's table for the mean motion of Venus in facsimile (1990, p. 38; 1995, p. 237) and transcribed part of his table for the solar mean motion (1995, pp. 239-240). He also included La Hire's table for Saturn (1990, pp. 35-36).[^3]

## EPOCH POSITIONS

The epoch or starting point of the mean motion tables in the *Zīj-i Muḥammad Shāhī* is noon at Delhi on February 20, 1719 (Gregorian). This date corresponds to 1 Rabī' II 1131 Hijra and is the beginning of the Islamic month during which Muḥammad Shāh's predecessor Farrukhsiyar was deposed.[^4] The mean positions at epoch are given to an accuracy of seconds, whereas most other tabular values are given to sexagesimal fourths (the few exceptions to this rule are listed in note 12). In general, all values found in mean motion tables are the result of computations based on a mean position at a certain time (not usually the epoch of the tables) and a value for the daily mean motion reduced from a set of observations. The fact that in the *Zīj-i Muḥammad Shāhī* the accuracy of the epoch values is different from that of the other tabular values, points to two essentially different methods of computation. In particular, it seems possible that Jai Singh's epoch values were derived directly from another set of mean motion tables with values to seconds, whereas his other tabular values were computed on the basis of values of the underlying daily mean motions with at least four sexagesimal fractional digits.
The astronomical tables of La Hire display mean positions for noon at Paris on New Year's Day of the Julian years 0, 100, 200, ..., 1600 and the Gregorian years 1600 and 1700. These are accompanied by values of the mean motion in 1, 2, 3, ..., 19, 20, 40, 60, 80, 100, 200, 300, 400, 500 and 1000 years, in the months January to December, in 1 to 30 days, in 1 to 30 hours, and, for some of the mean motions, in minutes and seconds of an hour. In order to compute from La Hire's tables the mean position of a particular planet on any given Julian or Gregorian date, the mean motions in the periods of time elapsed since the beginning of the current century should be added to the mean position given for the
***
44 INDIAN JOURNAL OF HISTORY OF SCIENCE
beginning of the century. For example, to determine a mean position at the epoch of the *Zīj-i Muḥammad Shāhī* mentioned above, one would take the mean position for the Gregorian year 1700 and add to it the mean motion in 18 years, in the month of January, and in 19 days. Since the values in La Hire's mean motion tables are all displayed to seconds, it is possible that they were the source from which the epoch values in the *Zīj-i Muḥammad Shāhī* were calculated. This possibility will be investigated in greater detail in the following paragraphs.
It can be noted that many Arabic and Persian sets of mean motion tables (including that found in the *Zīj-i Muḥammad Shāhī*) display values for so-called "incomplete" years, months and days rather than for the "incomplete" periods used by La Hire. In such sets one looks up the mean motions with the *current* year, month and day instead of the numbers of years, months and days that have elapsed. Whereas many Islamic mean motion tables give two separate sets of values for the months in an ordinary Julian year and those in a leap year, La Hire simply gives instructions to add an extra day for the months March to December in a leap year.
The addition indicated above for determining a mean position at the epoch of the *Zīj-i Muḥammad Shāhī* from the tables of La Hire yields mean positions at noon in Paris. To obtain the mean positions at noon in Delhi (or any other locality), a correction has to be carried out for the difference in geographical longitude (or, equivalently, for the difference in time between noon at the desired locality and noon at Paris, where noon is to be understood as the time of culmination of the mean sun). For this purpose many Islamic mean motion tables include a column for the "differences between the two longitudes" (*mā bayna al-ṭūlayn*), which displays the corrections to the mean motions as a function of degrees of longitude difference. Since La Hire does not provide such a column, a longitude correction based on his tables must be carried out by converting the longitude difference into time (a difference of $15^\circ$ in eastward direction corresponds to the culmination of the mean sun occurring one hour earlier) and then looking up the mean motion during that time in the tables for hours, minutes and seconds.
To illustrate the above, we will now compute the solar mean longitude at the epoch of the *Zīj-i Muḥammad Shāhī*, noon of February 20, 1719 (Gregorian),
***
ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 45
from the tables of La Hire. For this purpose we need to add the following values from the table for the solar mean motion in the *Tabulae astronomicae* (the superscript '$s$' indicates zodiacal signs);

| Description | Value |
| :--- | ---: |
| Mean position at noon of January 1, 1700 Gregorian | $9^s 10^\circ 52' 27''$ |
| Mean motion in 18 (Julian or Gregorian) years | $11^s 29^\circ 38' 42''$ |
| Mean motion in the month January | $1^s 0^\circ 33' 18''$ |
| Mean motion in 19 days | $18^\circ 43' 38''$ |
| | **+** |
| Mean position at noon of February 20, 1719 Gregorian | $10^s 29^\circ 48' 5''$ |

The sum $10^s 29^\circ 48' 5''$ is only $12' 4''$ larger than the epoch value of Jai Singh's solar mean motion table. As a working hypothesis, we will now assume that the epoch positions in the *Zīj-i Muḥammad Shāhī* were computed from the tables of La Hire. Under that assumption, the difference of $12' 4''$ found above must be due to a correction for the longitude difference between Paris and Delhi. We will thus proceed by determining the underlying longitude difference, which Mercier (1984, p. 146) found to be $73^\circ 30'$.[^5] Since the amount of the correction is proportional to the daily (or hourly) mean motion concerned, the largest corrections will be found for the mean motions in longitude of the Moon, Mercury, Venus, and the Sun, in that order. Since all epoch values in the *Zīj-i Muḥammad Shāhī* are given to seconds, this also implies that the most accurate determination of the longitude difference is possible from the differences between Jai Singh's epoch values for the above four mean motions and the corresponding mean positions at his epoch computed from the *Tabulae astronomicae*.
As an example, we will now compute the longitude difference on the basis of the lunar mean longitude. La Hire's lunar mean position at noon in Paris on February 20, 1719 Gregorian, computed similarly to the solar mean position above, is $11^s 13^\circ 58' 31''$, which is $2^\circ 41' 25''$ larger than the value found in the *Zīj-i Muḥammad Shāhī*. This difference can be seen to be the mean lunar motion in longitude in precisely 4 hours and 54 minutes, since La Hire's tables give a motion of $2^\circ 11' 46''$ for 4 hours and a motion of $29' 39''$ for 54 minutes. The same turns out to be true for the differences between Jai Singh's epoch values for Mercury, Venus, and the Sun and the corresponding values computed from the tables of La Hire:[^6]
***
[^*] Institut für Geschichte der Naturwissenschaften, Postfach 111 932 (FB 13), 60054 Frankfurt am Main, Germany.
[^1] For the sources of the biographical information here presented and for additional information concerning life and works of Jai Singh, the reader is referred to the bibliography below.
[^2] According to Pingree (1976, p. 63), the *Zīj-i Muḥammad Shāhī* was most probably written by Abū al-Khayr Khayr Allāh Khān. However, for the sake of convenience we will refer to Jai Singh as the author of the work.
[^3] In particular for the solar apogee, the values given by Sharma differ from those we found in the manuscript of the *Zīj-i Muḥammad Shāhī* kept in Tonk.
[^4] Farrukhsiyar was deposed on March 1, 1719 (Gregorian), while Muḥammad Shāh came to power only on September 28 of that same year. In the seven intervening months, two puppet emperors sat on the throne. As Elphinstone (reference provided in Mercier 1984, note 8) indicates, these two emperors were left out from the official list of kings of the Moghul empire, so that the reign of Muḥammad Shāh was considered to have begun with the deposition of Farrukhsiyar. This explains how the epoch date of *Zīj-i Muḥammad Shāhī* can be connected to the accession of Muḥammad Shāh in spite of the time difference. Note that in traditional Persian calendars the beginning of the year was usually determined by the time of the vernal equinox. Also Akbar, Moghul emperor from 1556 to 1602, is known to have used a calendar based on the vernal equinox (David Pingree, personal communication). However, the vernal equinox of the year 1719 fell on 1 Jumāda I 1131 Hijra, so that it cannot explain the epoch date of the *Zīj-i Muḥammad Shāhī*.
[^5] Mercier's Table I contains a mistake in the line for the longitude of Venus: the epoch position at $t_L$ is $41;52,0$ instead of $41;52,10$. As a result, the calculated position at $t_J$ becomes $346;43,12.2$ and the derived change in meridian $73;32$. The misprint in the motion of the node of Venus in 30 Hijra years (correct is $0;22,21,15,13$) was already noted by Mercier himself in his review of Sharma 1995 in *Isis* 88 (1997), p. 151.
[^6] We will use the standard notation for sexagesimal numbers, e.g., $2;41,25$ stands for $2 + \frac{41}{60} + \frac{25}{3600}$ or $2^\circ 41' 25''$. Note that the values for the mean motion of Mercury and Venus in 54 minutes are given to sexagesimal thirds because they were obtained by dividing values from the respective tables for hours by 60.
<<<CONTINUE>>>

46 INDIAN JOURNAL OF HISTORY OF SCIENCE

| Planet | Computed difference La Hire-Jai Singh | La Hire's motion in 4 hours | La Hire's motion in 54 minutes | Confidence level (time) |
| :--- | :--- | :--- | :--- | :--- |
| Moon | 2;41,25 | 2;11,46 | 0;29,39 | 0.9 seconds |
| Mercury | 0;50, 8 | 0;40,56 | 0; 9,12,27 | 2.9 seconds |
| Venus | 0;19,38 | 0;16, 2 | 0; 3,36,21 | 7.5 seconds |
| Sun | 0;12, 4 | 0; 9,51 | 0; 2,13 | 12.2 seconds |

If we add the motions in 4 hours and in 54 minutes and round the result to seconds, we obtain in each case precisely the difference between Jai Singh’s epoch value and the position computed from La Hire’s mean motion tables (i.e., the assumed longitude correction) given in the second column of the above table. This shows that Jai Singh’s epoch values were in fact computed from the tables of La Hire with a correction for a longitude difference of $4^h 54^m$ or $73^\circ 30'$.
One may ask how accurate the above determination of the longitude difference is. In fact, differences sufficiently close to $4^h 54^m$ will lead to the same corrections when these are rounded to seconds. The fifth column in the above table shows how many time seconds the longitude difference may be different from $4^h 54^m$ before the rounded correction changes by one second. We note that even if the longitude difference differs by only one second from $4^h 54^m$, the correction for the moon will not any more be equal to what we have found it to be. We therefore conclude that the longitude correction applied by Jai Singh was for precisely $4^h 54^m$ or $73^\circ 30'$. As was already noted by Mercier (1984, pp. 146-150), these values are in full agreement with the longitude difference between Paris and Delhi as found at various other places in the *Zīj-i Muḥammad Shāhī*, although they correspond better to the modern longitude difference between Paris and Jaipur.[^7]
We can now complete our recomputation of the solar mean position at epoch in the *Zīj-i Muḥammad Shāhī* by subtracting from the value found above the longitude correction for $73^\circ 30'$, i.e., the mean motion in 4 hours and 54 minutes:
---
ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 47
Mean position at noon of February 20, 1719 Gregorian  
for the meridian of Paris: $10^s 29^\circ 48' 5''$
Correction for difference in longitude between Paris  
and Delhi:  
Mean motion in 4 hours: $9' 51''$  
Mean motion in 54 minutes: $2' 13''$  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ——————  
Mean position at noon of February 20, 1719 Gregorian  
for the meridian of Delhi: $10^s 29^\circ 36' 1''$
In agreement with our analysis above, the result is identical with Jai Singh's solar mean position at epoch.
Following the same computational scheme we recomputed the epoch values for all twenty mean motion tables in the *Zīj-i Muḥammad Shāhī*. For fourteen tables the recomputed epoch value equalled that in the *Zīj*; in one case (the motion of the aphelium of Venus) it was two seconds larger than the value given by Jai Singh and in five cases (aphelium and node of Saturn and Mars, node of Mercury) it was one second smaller. Since all six non-matches occur for aphelia and nodes of planets, the mean motions concerned are significantly smaller than one second per day. This implies that incorrect or omitted longitude corrections could not account for the differences. We suspect that the cause of the differences is possibly a scribal error for the aphelium of Venus and a misreading in the other five cases.[^8]

## THE UNDERLYING DAILY MEAN MOTIONS

We now proceed with an analysis of the remaining mean motion values given in the *Zīj-i Muḥammad Shāhī*. Jai Singh tabulates mean positions for the thirty Arabic years following his epoch, i.e., for the 1st Rabī‘ II of the so-called *extended years* 1132, 1133, 1134, ..., 1161 Hijra. In his 30-year cycle, the epoch year and the 3rd, 5th, 8th, 11th, 14th, 16th, 19th, 22nd, 24th, and 27th year after the epoch year are leap years of 355 days (instead of the ordinary 354). Thus Jai Singh's cycle does not run parallel with one of the cycles commonly used by medieval Muslim astronomers. In addition to the mean positions for a
---
48 INDIAN JOURNAL OF HISTORY OF SCIENCE
complete cycle, the *Zīj-i Muḥammad Shāhī* tabulates the mean motion in 30, 60, 90, ..., 300, 600, 900, and 1200 so-called *collected years*;[^9] for current months from Rabī‘ II of the following year,[^10] and for current days from 1 to 61.[^11] In the remainder of this article we will occasionally refer to the tables for extended and collected years, months, and days as the "sub-tables" of a mean motion table.
Because the tabular values in most of the mean motion tables in the *Zīj-i Muḥammad Shāhī* are displayed to sexagesimal fourths,[^12] it is impossible that they were derived from the *Tabulae astronomicae* in the same way as the epoch values (as was noted above, La Hire’s values are given to seconds only). We will therefore determine the underlying parameters of Jai Singh’s mean motion tables directly from the tabular values without presupposing a relationship with any other tables. For this purpose we will make use of a recently introduced mathematical technique called the Least Number of Errors Criterion (LNEC). Descriptions of two slightly different forms of the LNEC can be found in Van Dalen 1993, Chapter 2.5, pp. 60-63 and in Mielgo 1996. The computer programs for DOS PC with which the analyses below were carried out can be obtained through the author’s webpage (http://www.rz. uni-frankfurt.de/~dalen).
In brief, the LNEC determines the parameter underlying an astronomical table in such a way that the number of errors in the table (i.e., the number of differences between the table and a recomputation based on the parameter value found) is minimized. This can be done by calculating for any given tabular value the interval of parameter values for which that tabular value is correctly recomputed. By taking the intersection of all intervals thus obtained we find the range of parameter values for which all tabular values are correctly recomputed. If this intersection is empty, we instead use the range of parameter values for which the number of errors is as small as possible. As Mielgo indicated, this range can for instance be obtained by leaving out any intervals which do not intersect with the majority of intervals obtained. In each case we will assume that the historical parameter used for the computation of the table lies within the range of values for which the number of errors in the table is minimized.
---
ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 49
The LNEC works particularly well for tables that have generally very few errors. Since calculations of mean motions can largely be performed by repeated additions of the mean motion per day or in certain other periods (cf. below), the probability of a computational error in mean motion tables tends to be smaller than in trigonometrically computed tables. On the other hand, an error in an intermediate calculation can easily propagate through a whole mean motion table.
To illustrate the principle of the LNEC, we will determine the range of values of the daily mean motion of Saturn for which Jai Singh’s mean motion of this planet in 30 Islamic years (10631 days) is correctly recomputed. The motion concerned is given in the *Zīj-i Muḥammad Shāhī* as $11^s 26^\circ 3' 37'' 2''' 54^{\text{iv}}$, and we may assume that this number was obtained by rounding to sexagesimal fourths the result of a multiplication of Jai Singh’s daily mean motion of Saturn by 10631.[^13] In case "modern" rounding were correctly applied, this result lay between $11^s 26^\circ 3' 37'' 2''' 53 \frac{1}{2}^{\text{iv}}$ and $11^s 26^\circ 3' 37'' 2''' 54 \frac{1}{2}^{\text{iv}}$; in the case of truncation, it lay between $11^s 26^\circ 3' 37'' 2''' 54^{\text{iv}}$ and $11^s 26^\circ 3' 37'' 2''' 55^{\text{iv}}$. A range within which the underlying daily mean motion of Saturn must lie can now be found by dividing the lower and upper bounds above by the number of days involved, 10631. For instance, under the assumption that modern rounding was used, we find that the daily mean motion must lie between $0;2,0,34,24,39,26,52^\circ$ and $0;2,0,34,24,39,27,12^\circ$. By intersecting this interval with intervals obtained in a similar way from other tabular values, the range within which Jai Singh’s value for the daily mean motion of Saturn must lie can be further narrowed down.
Note that for the faster mean motions and longer periods we have to take into account the number of rotations (multiples of $12^s$ or $360^\circ$) that the planet has completed. These are not indicated in the *Zīj-i Muḥammad Shāhī* (as in most Islamic astronomical handbooks) and therefore need to be added separately to the tabular values.
When we analysed the mean motion tables of Jai Singh, we found that not all sub-tables were computed by multiplying an accurate value of the daily mean motion by the relevant numbers of days. For various tables it could be shown that the computations were performed by adding rounded intermediate results, instead of calculating an accurate multiple of the daily mean motion in each case.
---
50 INDIAN JOURNAL OF HISTORY OF SCIENCE
**Table 1. Example of constant (left column) and non-constant (right column) tabular differences in mean motion tables of the types found in the *Zīj-i Muḥammad Shāhī***

| Extended years | | | Extended years | | |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **year** | **position** | **difference** | **year** | **position** | **difference** |
| 1 | $10^s 29^\circ 36, 1$ | - | 1 | $10^s 29^\circ 36, 1$ | - |
| 2 | $10^s 19^\circ 30, 18$ | $11^s 19^\circ 54, 17$ | 2 | $10^s 19^\circ 30, 18$ | $11^s 19^\circ 54, 17$ |
| 3 | $10^s \phantom{1} 8^\circ 25, 26$ | $11^s 18^\circ 55, \phantom{1} 8$ | 3 | $10^s \phantom{1} 8^\circ 25, 26$ | $11^s 18^\circ 55, \phantom{1} 8$ |
| 4 | $9^s 27^\circ 20, 34$ | $11^s 18^\circ 55, \phantom{1} 8$ | 4 | $9^s 27^\circ 20, 35$ | $11^s 18^\circ 55, \phantom{1} 9$ |
| 5 | $9^s 17^\circ 14, 51$ | $11^s 19^\circ 54, 17$ | 5 | $9^s 17^\circ 14, 51$ | $11^s 19^\circ 54, 16$ |
| 6 | $9^s \phantom{1} 6^\circ \phantom{1} 9, 59$ | $11^s 18^\circ 55, \phantom{1} 8$ | 6 | $9^s \phantom{1} 6^\circ 10, \phantom{1} 0$ | $11^s 18^\circ 55, \phantom{1} 9$ |
| 7 | $8^s 26^\circ \phantom{1} 4, 16$ | $11^s 19^\circ 54, 17$ | 7 | $8^s 26^\circ \phantom{1} 4, 17$ | $11^s 19^\circ 54, 17$ |
| 8 | $8^s 14^\circ 59, 24$ | $11^s 18^\circ 55, \phantom{1} 8$ | 8 | $8^s 14^\circ 59, 25$ | $11^s 18^\circ 55, \phantom{1} 8$ |
| 9 | $8^s \phantom{1} 3^\circ 54, 32$ | $11^s 18^\circ 55, \phantom{1} 8$ | 9 | $8^s \phantom{1} 3^\circ 54, 33$ | $11^s 18^\circ 55, \phantom{1} 8$ |
| 10 | $7^s 23^\circ 48, 49$ | $11^s 19^\circ 54, 17$ | 10 | $7^s 23^\circ 48, 50$ | $11^s 19^\circ 54, 17$ |
| 11 | $7^s 12^\circ 43, 57$ | $11^s 18^\circ 55, \phantom{1} 8$ | 11 | $7^s 12^\circ 43, 59$ | $11^s 18^\circ 55, \phantom{1} 9$ |
| 12 | $7^s \phantom{1} 1^\circ 39, \phantom{1} 5$ | $11^s 18^\circ 55, \phantom{1} 8$ | 12 | $7^s \phantom{1} 1^\circ 39, \phantom{1} 7$ | $11^s 18^\circ 55, \phantom{1} 8$ |
| 13 | $6^s 21^\circ 33, 22$ | $11^s 19^\circ 54, 17$ | 13 | $6^s 21^\circ 33, 24$ | $11^s 19^\circ 54, 17$ |
| 14 | $6^s 10^\circ 28, 30$ | $11^s 18^\circ 55, \phantom{1} 8$ | 14 | $6^s 10^\circ 28, 32$ | $11^s 18^\circ 55, \phantom{1} 8$ |
| 15 | $5^s 29^\circ 23, 38$ | $11^s 18^\circ 55, \phantom{1} 8$ | 15 | $5^s 29^\circ 23, 41$ | $11^s 18^\circ 55, \phantom{1} 9$ |
| 16 | $5^s 19^\circ 17, 55$ | $11^s 19^\circ 54, 17$ | 16 | $5^s 19^\circ 17, 57$ | $11^s 19^\circ 54, 16$ |
| 17 | $5^s \phantom{1} 8^\circ 13, \phantom{1} 3$ | $11^s 18^\circ 55, \phantom{1} 8$ | 17 | $5^s \phantom{1} 8^\circ 13, \phantom{1} 6$ | $11^s 18^\circ 55, \phantom{1} 9$ |
| 18 | $4^s 28^\circ \phantom{1} 7, 20$ | $11^s 19^\circ 54, 17$ | 18 | $4^s 28^\circ \phantom{1} 7, 23$ | $11^s 19^\circ 54, 17$ |
| 19 | $4^s 17^\circ \phantom{1} 2, 28$ | $11^s 18^\circ 55, \phantom{1} 8$ | 19 | $4^s 17^\circ \phantom{1} 2, 31$ | $11^s 18^\circ 55, \phantom{1} 8$ |
| 20 | $4^s \phantom{1} 5^\circ 57, 36$ | $11^s 18^\circ 55, \phantom{1} 8$ | 20 | $4^s \phantom{1} 5^\circ 57, 39$ | $11^s 18^\circ 55, \phantom{1} 8$ |
| 21 | $3^s 25^\circ 51, 53$ | $11^s 19^\circ 54, 17$ | 21 | $3^s 25^\circ 51, 56$ | $11^s 19^\circ 54, 17$ |
| $\vdots$ | $\vdots$ | $\vdots$ | $\vdots$ | $\vdots$ | $\vdots$ |
| Collected years | | | Collected years | | |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **years** | **motion** | **difference** | **years** | **motion** | **difference** |
| 30 | $1^s \phantom{1} 8^\circ 24, 53$ | $1^s \phantom{1} 8^\circ 24, 53$ | 30 | $1^s \phantom{1} 8^\circ 24, 53$ | $1^s \phantom{1} 8^\circ 24, 53$ |
| 60 | $2^s 16^\circ 49, 46$ | $1^s \phantom{1} 8^\circ 24, 53$ | 60 | $2^s 16^\circ 49, 46$ | $1^s \phantom{1} 8^\circ 24, 53$ |
| 90 | $3^s 25^\circ 14, 38$ | $1^s \phantom{1} 8^\circ 24, 53$ | 90 | $3^s 25^\circ 14, 39$ | $1^s \phantom{1} 8^\circ 24, 53$ |
| 120 | $5^s \phantom{1} 3^\circ 39, 31$ | $1^s \phantom{1} 8^\circ 24, 53$ | 120 | $5^s \phantom{1} 3^\circ 39, 31$ | $1^s \phantom{1} 8^\circ 24, 52$ |
| 150 | $6^s 12^\circ \phantom{1} 4, 24$ | $1^s \phantom{1} 8^\circ 24, 53$ | 150 | $6^s 12^\circ \phantom{1} 4, 24$ | $1^s \phantom{1} 8^\circ 24, 53$ |
| 180 | $7^s 20^\circ 29, 17$ | $1^s \phantom{1} 8^\circ 24, 53$ | 180 | $7^s 20^\circ 29, 17$ | $1^s \phantom{1} 8^\circ 24, 53$ |
| 210 | $8^s 28^\circ 54, 10$ | $1^s \phantom{1} 8^\circ 24, 53$ | 210 | $8^s 28^\circ 54, 10$ | $1^s \phantom{1} 8^\circ 24, 53$ |
| 240 | $10^s \phantom{1} 7^\circ 19, \phantom{1} 3$ | $1^s \phantom{1} 8^\circ 24, 53$ | 240 | $10^s \phantom{1} 7^\circ 19, \phantom{1} 3$ | $1^s \phantom{1} 8^\circ 24, 53$ |
| 270 | $11^s 15^\circ 43, 55$ | $1^s \phantom{1} 8^\circ 24, 53$ | 270 | $11^s 15^\circ 43, 56$ | $1^s \phantom{1} 8^\circ 24, 53$ |
| 300 | $0^s 24^\circ \phantom{1} 8, 48$ | $1^s \phantom{1} 8^\circ 24, 53$ | 300 | $0^s 24^\circ \phantom{1} 8, 48$ | $1^s \phantom{1} 8^\circ 24, 52$ |
| 600 | $1^s 18^\circ 17, 37$ | $0^s 24^\circ \phantom{1} 8, 48$ | 600 | $1^s 18^\circ 17, 37$ | $0^s 24^\circ \phantom{1} 8, 49$ |
| 900 | $2^s 12^\circ 26, 25$ | $0^s 24^\circ \phantom{1} 8, 48$ | 900 | $2^s 12^\circ 26, 25$ | $0^s 24^\circ \phantom{1} 8, 48$ |
| 1200 | $3^s \phantom{1} 6^\circ 35, 13$ | $0^s 24^\circ \phantom{1} 8, 48$ | 1200 | $3^s \phantom{1} 6^\circ 35, 13$ | $0^s 24^\circ \phantom{1} 8, 48$ |

***

[^7]: In the Sanskrit translation of La Hire's *Tabulae astronomicae* by Kevalarāma, a correction is applied for a difference in geographical longitude between Paris and Jaipur of $4^h 49^m$, i.e. $72^\circ 15'$ (Pingree, to appear). Note that this value is consistent with the difference $73^\circ 30'$ between Paris and Delhi found above and the longitude $1^\circ 15'$ west of Delhi assigned to Jaipur by Jai Singh (cf. Mercier 1984, p.150).

[^8]: Because the motions of the aphelia and nodes of the planets amount to much less than a second per day, the same tabular value will be found for series of days if the motions are expressed in seconds. In such cases La Hire entered every value only once and left the remaining entries blank. As far as we know, he did not make it completely clear which value should be taken if none is found opposite the requested number of days. For our recomputation we have always taken the tabular value *above* the line for 19 days in cases where no value is given on that line. If we had always taken the tabular value *nearest* to the line for 19 days (so also possibly *below* it), the five differences of one minute mentioned above would have disappeared, but three new ones would have been introduced.

[^9]: This range of years is precisely the same as that in the *Sulṭānī Zīj* of Ulugh Beg, but besides this there are no similarities between the two sets of tables: both the tabulated quantities and the underlying parameters are clearly different.

[^10]: Since the tables are for "current" months, the first values (for Rabī‘ II) are always equal to zero, indicating that for a date in the first month of the year no mean motion from the table for months needs to be added to the mean position at the beginning of the year. The leap day is apparently inserted at the end of the last month of the year, Rabī‘ I, which thus receives 31 days in a leap year. However, in the manuscript of the Arabic and Persian Research Institute in Tonk, interlinear values facilitate insertion of the leap day at the end of Dhu'l-Ḥijja as in the common Hijra calendar.

[^11]: Similarly to the months, the mean motion for the first day is zero in all cases. By shifting the sexagesimal point, the values for days can also be used for the Indian sexagesimal subdivisions of a day called *ghaṛī* and *pal*.

[^12]: Only the sub-table for extended years of the table for the mean solar longitude and that for collected years of the table for the motion of the solar apogee display values to five sexagesimal fractional digits. In the table for the mean longitude of Jupiter the fourths' position contains zeros only, because the underlying daily mean motion happens to be an integer number of sexagesimal thirds. In the sub-tables for extended and collected years of the table for the motion of Jupiter's aphelium, the fourths' position contains either 0 or 30, apparently the result of intermediate rounding. For all mean motions, the values in the second half of the table for days (and in some cases the whole table) are given to sexagesimal thirds instead of to fourths.

[^13]: Whether this multiplication was effectively carried out as a multiplication or as a repeated addition of mean motions in larger periods such as Arabic ordinary and leap years, does not make a difference for the operation of the LNEC.

ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 51
For instance, the tables for months may be computed on the basis of rounded values for the motions in 29 and in 30 days; the tables for extended years were often computed on the basis of rounded values for 354 and for 355 days; and about half of the tables for collected years consist of plain multiples of the motion in 30 Arabic years. The use of rounded values for intermediate results can be easily recognized from the tabular differences of a mean motion table. If rounding to the number of digits of the table was performed at an intermediate stage of the calculation, the resulting tabular differences will be constant (i.e., they are all the same or, in the case of the tables for months and extended years, they assume only two different values for the two underlying periods). If no intermediate rounding was performed, the tabular differences will usually have two values differing by only one in the final digit (examples of constant and non-constant tabular differences for two types of sub-tables can be found in Table 1).
The probability that a mean motion table which was not computed on the basis of rounded intermediate results does have constant tabular differences is in fact very small.[^14] Since more than half of the mean motion tables in the $Z\bar{i}j\text{-}i\ Mu\d{h}ammad\ Sh\bar{a}h\bar{i}$ have constant tabular differences in at least one or two of the sub-tables, we may assume that Jai Singh often rounded his intermediate results to the number of sexagesimal digits of his tables. Note that in all such cases we have determined the underlying daily mean motion from the rounded intermediate result only, rather than finding the parameter values for which all tabular values are correctly recomputed (i.e., using the LNEC). For instance, if the collected years have constant tabular differences, we have calculated the daily mean motion from the motion in 30 Arabic years. Below, an overview will be given of the various methods of computation that we have been able to recognize in Jai Singh's mean motion tables.
The third column of Table 2 presents our estimates of the daily mean motions underlying the tables of Jai Singh with an indication of their accuracy. An entry of the form $\mu \pm \nu$ indicates that the value of the daily mean motion used for the computation of the table concerned can be assumed to lie between $\mu-\nu$ and $\mu+\nu$. Note that the leading zeros of $\nu$ have been omitted, but that the final sexagesimal digit of $\nu$ always corresponds to the final digit of the estimate $\mu$. For instance, an entry $0;59,8,20,0 \pm 1,30$ indicates that we expect the parameter
52 INDIAN JOURNAL OF HISTORY OF SCIENCE
Table 2. Estimates of the motion parameters used by Jai Singh

| planet | motion | daily mean motion (in degrees) used by Jai Singh | daily mean motion multiplied by 365 | corresponding value of La Hire |
| :--- | :--- | :--- | :--- | :--- |
| Sun | longitude | $0;59, 8,19,46,50,57,27,27 \pm 10$ | $359;45,40,19,59,59,32$ | $359;17, 1 / 3 \text{ years}$ |
| | apogee | $0; 0, 0,10, 6,34,34,34 \pm 4$ | $0; 1, 1,30, 0,20$ | $0; 2, 3 / 2 \text{ years}$ |
| Moon | longitude | $13;10,35, 1,22,11,28,38,30 \pm 17$ | $129;23, 3,19,59,49$ | $28; 9,10 / 3 \text{ years}$ |
| | apogee | $0; 6,41, 4,29,35,20,29, 4 \pm 10$ | $40;39,52,19,59,59,37$ | $121;59,37 / 3 \text{ years}$ |
| | node | $-0; 3,10,38,18, 4,54,55, 4 \pm 10$ | $-19;19,42,59,59,54$ | $-19;19,43 / 1 \text{ year}$ |
| Saturn | longitude | $0; 2, 0,34,24,39,27,12, 2 \pm 30$ | $12;13,29,20, 0,28$ | $36;40,28 / 3 \text{ years}$ |
| | aphelium | $0; 0, 0,13,28,46, 1,38, 9 \pm 17$ | $0; 1,21,59,59,59,57$ | $0; 1,22 / 1 \text{ year}$ |
| | node | $0; 0, 0,11,45,12,19,44, 2 \pm 30$ | $0; 1,11,30, 0, 3$ | $0; 2,23 / 2 \text{ years}$ |
| Jupiter | longitude | $0; 4,59,16$ | $30;20,32,20$ | $91; 1,37 / 3 \text{ years}$ |
| | aphelium | $0; 0, 0,15,30,25,23,51 \pm 10$ | $0; 1,34,20, 4$ | $0; 4,43 / 3 \text{ years}$ |
| | node | $0; 0, 0, 2,19, 4,13,58 \pm 10$ | $0; 0,14, 6, 0,45$ | $0; 2,21 / 10 \text{ years}$ |
| Mars | longitude | $0;31,26,39,13,58,18,25 \pm 10$ | $191;17, 8,39,59,42$ | $213;51,26 / 3 \text{ years}$ |
| | aphelium | $0; 0, 0,10,57,32, 3,26 \pm 10$ | $0; 1, 6,40, 0,53$ | $0; 3,20 / 3 \text{ years}$ |
| | node | $0; 0, 0, 6, 4,55,53, 8 \pm 10$ | $0; 0,36,59,59,58$ | $0; 0,37 / 1 \text{ year}$ |
| Venus | longitude | $1;36, 7,49,32, 3,17,25 \pm 10$ | $224;47,36,20, 0,57$ | $314;22,49 / 3 \text{ years}$ |
| | aphelium | $0; 0, 0,14,10,11,30,25,29 \pm 15$ | $0; 1,26,12, 0, 5$ | $0; 7,11 / 5 \text{ years}$ |
| | node | $0; 0, 0, 7,34,11,30,28 \pm 10$ | $0; 0,46, 3, 0,20$ | --- |
| Mercury | longitude | $4; 5,32,35,20,32,52,52 \pm 10$ | $53;43,15, 0, 2$ | $53;43,15 / 1 \text{ year}$ |
| | aphelium | $0; 0, 0,16,14,27,56,40,51 \pm 23$ | $0; 1,38,47,59,59,48$ | $0; 8,14 / 5 \text{ years}$ |
| | node | $0; 0, 0,14, 0,39,27, 7,45 \pm 17$ | $0; 1,25,14, 0, 2$ | $1;25,14 / 60 \text{ years}$ |

ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 53
concerned to lie between $0;59,8,18,30$ and $0;59,8,21,30$. The estimate of the daily mean motion of Saturn found above from the single tabular value $T(30^y)$ for 30 Arabic years would be expressed as $T(30^y)/10631 \pm 0;0,0,0,0,30/10631$.[^15]
As becomes clear from Table 2, we can in each case determine the underlying daily mean motion with an uncertainty of less than 10 in the seventh sexagesimal fractional digit. Whereas this accuracy has little meaning in an astronomical sense, we will see below that it helps us in investigating the relationship between Jai Singh's parameter values and those of La Hire and even in determining the precise way in which Jai Singh obtained his parameters. Using the values of the daily mean motions given in Table 2 and taking into consideration the particular methods of computation discussed below, we find that the errors in Jai Singh's mean motion tables generally amount to at most a sexagesimal fourth. Some very large errors that occur in most of the tables can be seen to be due to scribal errors or copying mistakes in the manuscript that we have used. In the least accurate table, that for the mean motion in longitude of Mercury, the 24 errors in the sub-table for extended years (which we have not been able to explain) range from $-4$ to $+1$ sexagesimal fourths (see Table 5 below).[^16]
Summarizing, we found that the following computational techniques have been used in the twenty mean motion tables in the $Z\bar{i}j\text{-}i\ Mu\d{h}ammad\ Sh\bar{a}h\bar{i}$:
1.  Accurate computation on the basis of *un-rounded* values for the daily mean motions (or, equivalently, for the mean motions in the periods underlying the respective sub-tables, namely, 29 and 30 days for the table for months, 354 and 355 days for the table for extended years, and 10631 days (30 Arabic years) for the table for collected years).
2.  Computation on the basis of *rounded* values for the mean motions in the periods underlying the various sub-tables. Thus we found that in at least eight of the twenty mean motion tables the table for extended years was computed on the basis of rounded mean motion values for 354 and for 355 days. As a result of the rounding, in five of these tables the difference between the mean positions at the beginning of the years 31 and 1 is not equal to the mean motion in 30 years displayed in the table for collected years. In one more case in which the rounding was used, the value for the year 31 was modified in order to avoid such a disagreement (but resulting in an anomaly
54 INDIAN JOURNAL OF HISTORY OF SCIENCE
within the table for extended years.) Furthermore, in ten tables the sub-table for collected years was based on a rounded value for 30 Arabic years. In all these cases the rounding of the underlying parameters could be recognized from the constant tabular differences of the sub-tables (cf. above).
3.  In a number of cases the tables for months and days were computed with a heavily rounded value of the daily mean motion which is not compatible with the values used for the tables for extended and collected years.
4.  In general it can be seen that the results of the mean motion computations were rounded to the number of digits of the tabular values in the "modern" way, i.e., sexagesimal digits 30 and higher were rounded upwards, digits 29 and lower were discarded. However, for the values in a couple of tables "truncation" appears to have been used, i.e., the sexagesimal fifths and below were simply discarded.
5.  Some of the tables for extended years and for months have highly irregular error patterns, which we have not been able to explain. However, also in these tables the errors are never larger than four sexagesimal fourths (cf. Table 5).
A typical example for the variety of computational techniques used by Jai Singh is his table for the motion of the Ascending Node of Mars. A complete reconstruction of this table (including the derivation of the underlying value of the daily mean motion) will be given at the end of this article.

## ORIGIN OF JAI SINGH'S VALUES FOR THE DAILY MEAN MOTIONS

In order to investigate the relationship between the values for the daily mean motions in the $Z\bar{i}j\text{-}i\ Mu\d{h}ammad\ Sh\bar{a}h\bar{i}$ and those in the $Tabulae\ astronomicae$, it would be possible to analyse the tables of La Hire in the same way as those of Jai Singh and then compare the results. However, our estimates of Jai Singh's parameters are so accurate that we can verify a more general hypothesis concerning their origin, namely that they were derived from some other set of tables by taking for each type of mean motion one particular tabular value and dividing that by the corresponding (integer) number of days. According to this hypothesis, we expect that certain multiples of the parameters found from Jai Singh's tables
ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 55
are close to round numbers, i.e., numbers with only a limited number of non-zero sexagesimal fractional digits such as we find them in tables.
Table 3 shows a selection of multiples of the value of Saturn's daily mean motion in longitude that we derived from the $Z\bar{i}j\text{-}i\ Mu\d{h}ammad\ Sh\bar{a}h\bar{i}$. Besides multiples from 1 to 30, those for the lengths of ordinary and leap years as well as average year lengths in some common calendars have been included. As can be seen from the table, the daily mean motion of Saturn multiplied by 365 is close to $12;13,29,20$, i.e., an integer number of seconds divided by 3. Consequently, the daily mean motion of Saturn multiplied by 1095 is close to an integer number of seconds, namely $36;40,28$. No other multiples are even approximately similarly close to a round number.
It turns out that this situation is typical for all mean motion parameters used by Jai Singh. The fourth column of Table 2 contains the 365-folds of the derived daily mean motions in the third column (multiples of $360^{\circ}$ have been omitted). Except for the aphelium and node of Jupiter, all these 365-folds are close to a round number. We conclude that Jai Singh derived his parameters by dividing mean motion values for certain integer numbers of ordinary (i.e. non-leap) Julian years or Persian years by the corresponding multiples of 365.
Since most of the 365-folds are close to an integer number of seconds or to an integer number of seconds divided by 2 or 3, it is very probable that the mean motion values on which Jai Singh based his parameters were given to seconds. Under this assumption, the fifth column of Table 2 shows the mean motion values from which the parameters were derived. These turn out to be identical with values found in the $Tabulae\ astronomicae$ of La Hire, except for the node of Venus, for which La Hire gives a motion of $0;15,22^{\circ}$ in 20 Julian years, whereas Jai Singh used $0;15,21^{\circ}$. We therefore conclude that Jai Singh determined his values for the daily mean motions of the sun, moon, and planets by dividing mean motion values for certain numbers of Julian years from the $Tabulae\ astronomicae$ by the appropriate multiples of 365.[^6]
***

[^6]: Mercier's Table I contains a mistake in the line for the longitude of Venus: the epoch position at $t_L$ is $41;52,0$ instead of $41;52,10$. As a result, the calculated position at $t_J$ becomes $346;43,12.2$ and the derived change in meridian $73;32$. The misprint in the motion of the node of Venus in 30 Hijra years (correct is $0;22,21,15,13$) was already noted by Mercier himself in his review of Sharma 1995 in *Isis* 88 (1997), p. 151.

[^14]: In the case of the type of mean motion tables in the $Z\bar{i}j\text{-}i\ Mu\d{h}ammad\ Sh\bar{a}h\bar{i}$, the probability that the table for extended years has constant tabular differences is around 4.1%, whereas that for the table for collected years is 2.5%, and that for the table for months approximately 13.2%. Statisticians who are interested in the concept of randomness in connection with (deterministically computed) astronomical parameters and tables are referred to Van Dalen 1993, Section 1.2.4, pp. 15-19. The above probabilities are based on the assumption that the underlying values for the daily mean motion have a uniform distribution on a certain relevant interval.

[^15]: This is the estimate obtained under the assumption that modern rounding was used. It is not the same as the entry for the longitude of Saturn in Table 2, because the sub-table for collected years of Saturn's mean motion table does not have constant tabular differences and hence we applied the LNEC to determine a more accurate estimate.

[^16]: The errors of up to $1\ \frac{1}{2}$ degrees that can be seen in Sharma's recomputation of Jai Singh's table for the mean longitude of Venus (1990, p. 40; 1995, p. 248) are due to an erroneous method of computation (cf. E.S. Kennedy's review of Sharma 1990 in *Mathematical Reviews* 1991m:01013 and R.P. Mercier's review of Sharma 1995 in *Isis* 88 (1997), pp. 150-151). Sharma calculated the motion in 20 Arabic years from La Hire's value for 20 Julian years by multiplying by $354;22/365;15$ (1990, p. 37; 1995, p. 247), but then distributed the result over what should have been 20 Arabic years using the intercalation scheme of the Julian calendar. Thus the values $T(n)$ ($n = 1, 2, 3, \dots, 19$) in the fourth column of his Tables 3 and 11-4 (except $T(19)$, which does not seem to belong to this column at all) were effectively computed by the formula $T(n) = T(0) + \text{Trunc}(n . 365\ \frac{1}{4}) . (T(20) + 31 . 360 - T(0)) / 7305$.

56 INDIAN JOURNAL OF HISTORY OF SCIENCE
**Table 3. Multiples of Jai Singh's value for Saturn's daily mean motion**

| multiplier | multiple |
| :--- | :--- |
| 1 | $0; 2, 0,34,24,39,27,12, 2$ |
| 2 | $0; 4, 1, 8,49,18,54,24, 4$ |
| 3 | $0; 6, 1,43,13,58,21,36, 6$ |
| 4 | $0; 8, 2,17,38,37,48,48, 8$ |
| 5 | $0;10, 2,52, 3,17,16, 0,10$ |
| 6 | $0;12, 3,26,27,56,43,12,12$ |
| 7 | $0;14, 4, 0,52,36,10,24,14$ |
| 8 | $0;16, 4,35,17,15,37,36,16$ |
| 9 | $0;18, 5, 9,41,55, 4,48,18$ |
| 10 | $0;20, 5,44, 6,34,32, 0,20$ |
| 11 | $0;22, 6,18,31,13,59,12,22$ |
| 12 | $0;24, 6,52,55,53,26,24,24$ |
| 13 | $0;26, 7,27,20,32,53,36,26$ |
| 14 | $0;28, 8, 1,45,12,20,48,28$ |
| 15 | $0;30, 8,36, 9,51,48, 0,30$ |
| 16 | $0;32, 9,10,34,31,15,12,32$ |
| 17 | $0;34, 9,44,59,10,42,24,34$ |
| 18 | $0;36,10,19,23,50, 9,36,36$ |
| 19 | $0;38,10,53,48,29,36,48,38$ |
| 20 | $0;40,11,28,13, 9, 4, 0,40$ |
| 21 | $0;42,12, 2,37,48,31,12,42$ |
| 22 | $0;44,12,37, 2,27,58,24,44$ |
| 23 | $0;46,13,11,27, 7,25,36,46$ |
| 24 | $0;48,13,45,51,46,52,48,48$ |
| 25 | $0;50,14,20,16,26,20, 0,50$ |
| 26 | $0;52,14,54,41, 5,47,12,52$ |
| 27 | $0;54,15,29, 5,45,14,24,54$ |
| 28 | $0;56,16, 3,30,24,41,36,56$ |
| 29 | $0;58,16,37,55, 4, 8,48,58$ |
| 30 | $1; 0,17,12,19,43,36, 1, 0$ |
| 354 | $11;51,23, 1,28,46,28,59,48$ |
| 354;22 | $11;52, 7,14, 5,48,56,58,13$ |
| 355 | $11;53,23,35,53,25,56,11,50$ |
| 360 | $12; 3,26,27,56,43,12,12, 0$ |
| 365 | $12;13,29,20, 0, 0,28,12,10$ |
| 365;15 | $12;13,59,28,36,10,20, 0,11$ |
| 366 | $12;15,29,54,24,39,55,24,12$ |
| 1095 | $36;40,28, 0, 0, 1,24,36,30$ |
| 1461 | $48;55,57,54,24,41,20, 0,42$ |
| 10631 | $356; 3,37, 2,54,28,29, 6,22$ |

---
ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 57
It can be noted that Jai Singh was not completely systematic in the way in which he made use of mean motion values from the *Tabulae astronomicae*. It seems that he used La Hire's values for 2 years for the solar apogee and the node of Saturn, his values for 10, 20 or 60 years for the node of Jupiter, the aphelium of Venus, and the aphelium and node of Mercury, and his values for 3 years in the remaining 13 cases (in 4 of these cases he might also have used La Hire's value for 1 year, because the value for 3 years is exactly three times that for 1 year). Where Jai Singh made use of values for more than 3 years, he seems to have ignored the leap days in the Julian calendar and still performed the necessary divisions by a multiple of 365. Since this only occurs for the slow motions of the aphelia and nodes of the five planets, the resulting errors were relatively small. We do not know why Jai Singh used La Hire's mean motion values for 2 or 3, and occasionally for 10, 20 or 60 years to derive his own mean motion parameters. From a modern point of view, a more appropriate method would have been, for instance, to take the values for 1000 years and divide them by 365,250.

## RECONSTRUCTION OF JAI SINGH'S TABLE FOR THE ASCENDING NODE OF MARS

In conclusion of our analysis, we will now present a complete reconstruction of the table in the $Zīj\text{-}i\ Muḥammad\ Shāhī$ for the motion of the ascending node of Mars. This table is a typical example for the variety of computational techniques used by Jai Singh and nicely illustrates the way in which he derived his mean motion parameters from the *Tabulae astronomicae* of Philippe de La Hire. Table 4 shows the tables for extended years, collected years and months with the errors according to two methods of computation which will be explained below:
I. an accurate computation on the basis of the underlying daily motion $0;0,6,4,55,53$
II. a computation on the basis of the particular computational techniques that can be recognized from the table.
---
58 INDIAN JOURNAL OF HISTORY OF SCIENCE
**Table 4. Recomputation of Jai Singh's table for the motion of the Ascending Node of Mars. Error I: differences between the table and an accurate computation based on a daily motion of $0;0,6,4,55,53^\circ$. Error II: differences between the table and a recomputation involving rounded values for ordinary and leap years and for 30 years**

| Extended years | | | | Collected years | | | |
| :--- | :--- | :---: | :---: | :--- | :--- | :---: | :---: |
| year | position | error I | error II | years | motion | error I | error II |
| 1 | $1^s 17;36,29$ | | | 30 | $0;17,57,39,46$ | | |
| 2 | $1^s 17;37, 4,59,11$ | | | 60 | $0;35,55,19,32$ | +1 | |
| 3 | $1^s 17;37,40,52,17$ | +1 | | 90 | $0;53,52,59,18$ | +1 | |
| 4 | $1^s 17;38,16,45,23$ | +1 | | 120 | $1;11,50,39, 4$ | +2 | |
| 5 | $1^s 17;38,52,44,34$ | +1 | | 150 | $1;29,48,18,50$ | +2 | |
| 6 | $1^s 17;39,28,37,40$ | +2 | | 180 | $1;47,45,58,36$ | +2 | |
| 7 | $1^s 17;40, 4,36,51$ | +2 | | 210 | $2; 5,43,38,22$ | +3 | |
| 8 | $1^s 17;40,40,29,57$ | +2 | | 240 | $2;23,41,18, 8$ | +3 | |
| 9 | $1^s 17;41,16,23, 3$ | +3 | | 270 | $2;41,38,57,54$ | +4 | |
| 10 | $1^s 17;41,52,22,14$ | +3 | | 300 | $2;59,36,37,40$ | +4 | |
| 11 | $1^s 17;42,28,15,20$ | +3 | | 600 | $5;59,13,15,20$ | +8 | |
| 12 | $1^s 17;43, 4, 8,26$ | +3 | | 900 | $8;58,49,53, 0$ | +12 | |
| 13 | $1^s 17;43,40, 7,36$ | +3 | -1 | 1200 | $11;58,26,30,40$ | +16 | |
| 14 | $1^s 17;44,16, 0,43$ | +4 | | | | | |
| 15 | $1^s 17;44,51,53,49$ | +4 | | **Months** | | | |
| 16 | $1^s 17;45,27,53, 0$ | +5 | | month | motion | error I/II | |
| 17 | $1^s 17;46, 3,46, 6$ | +5 | | $Rabi\text{ʿ}\ II$ | $0; 0, 0, 0, 0$ | | |
| 18 | $1^s 17;46,39,45,17$ | +5 | | $Jum\text{ā}d\text{ā}\ I$ | $0; 0, 2,56,23$ | | |
| 19 | $1^s 17;47,15,38,23$ | +6 | | $Jum\text{ā}d\text{ā}\ II$ | $0; 0, 5,58,51$ | | |
| 20 | $1^s 17;47,51,31,29$ | +6 | | $Rajab$ | $0; 0, 8,55,14$ | | |
| 21 | $1^s 17;48,27,30,40$ | +6 | | $Sha\text{ʿ}b\text{ā}n$ | $0; 0,11,57,42$ | | |
| 22 | $1^s 17;49, 3,23,46$ | +7 | | $Rama\text{ḍā}n$ | $0; 0,14,54, 5$ | | |
| 23 | $1^s 17;49,39,16,52$ | +7 | | $Shaww\text{ā}l$ | $0; 0,17,56,33$ | | |
| 24 | $1^s 17;50,15,16, 3$ | +7 | | $Dhu'l\text{-}qa\text{ʿ}da$ | $0; 0,20,52,56$ | | |
| 25 | $1^s 17;50,51, 9, 9$ | +8 | | $Dhu'l\text{-}ḥijja$ | $0; 0,23,55,24$ | | |
| 26 | $1^s 17;51,27, 8,20$ | +8 | | $Muḥarram$ | $0; 0,26,51,47$ | | |
| 27 | $1^s 17;52, 3, 1,26$ | +8 | | $Safar$ | $0; 0,29,54,14$ | -1 | |
| 28 | $1^s 17;52,38,54,32$ | +8 | | $Rabi\text{ʿ}\ I$ | $0; 0,32,50,38$ | | |
| 29 | $1^s 17;53,14,53,43$ | +9 | | ordinary year | $0; 0,35,53, 5$ | -1 | |
| 30 | $1^s 17;53,50,46,49$ | +9 | | leap year | $0; 0,35,59,10$ | -1 | |
| 31 | $1^s 17;54,26,39,55$ | +9 | | | | | |

---
ORIGIN OF THE MEAN MOTION TABLES OF JAI SINGH 59
Jai Singh started by computing his epoch value, the position of the ascending node of Mars on February 20, 1719 (Gregorian) from the tables of La Hire. For this purpose he added the appropriate tabular values for the beginning of the century and for the completed years, months, and days as shown below (cf. the earlier example for the solar mean longitude). Note that in this case it is not necessary to actually carry out the correction for the difference in geographical longitude between Paris and Delhi, because the daily motion (approximately 6''), and hence the correction, is significantly smaller than the accuracy of La Hire's tabular values (1''). For the motion in 19 days we have taken the value found for 20 days (2'), rather than that for 10 days (1', cf. note 8).

| | |
| :--- | ---: |
| Position at noon of January 1, 1700 Gregorian: | $1^s 17^\circ 25'20''$ |
| Motion in 18 (Julian or Gregorian) years: | $0^\circ 11' 4''$ |
| Motion in the month January: | $0^\circ 0' 3''$ |
| Motion in 19 days: | $0^\circ 0' 2''$ |
| | --- |
| Position at noon of February 20, 1719 Gregorian | |
| for the meridian of Paris or Delhi: | $1^s 17^\circ 36'29''$ |

Next Jai Singh took from La Hire's tables the motion of the ascending node of Mars in 3 Julian years, $0^\circ 1'51''$. He divided this value by 1095 and rounded the result to sexagesimal sixths to obtain as his value for the daily motion $0;0,6,4,55,53$.[^17]
In order to compute the table for *extended years*, Jai Singh multiplied the daily motion by 354 for an ordinary Hijra year and by 355 for a leap year and rounded the results to four sexagesimal fractional places, the accuracy of his table. Thus he obtained $0;0,35,53,6$ (exactly: $0;0,35,53,5,42,42$) for the motion in an ordinary year and $0;0,35,59,11$ (exactly: $0;0,35,59,10,38,35$) for the motion in a leap year. Following his intercalation scheme, he successively added these numbers to the epoch value and obtained a table with "constant" tabular differences (i.e., in this case, two different values for the tabular differences, one for every ordinary year and one for every leap year). In this way, the difference between the values for the years 31 and 1 became $19 \times 0;0,35,53,6 + 11 \times 0;0,35,59,11 = 0;17,57,39,55$. By comparing this with the result of a multiplica-
---
60 INDIAN JOURNAL OF HISTORY OF SCIENCE
**Table 5. Recomputation of the sub-table for extended years of Jai Singh's table for the mean motion in longitude of Mercury (assumed daily mean motion: $4;5,32,35,20,32,53^\circ$)**

| year | mean position | error | year | mean position | error |
| :--- | :--- | :---: | :--- | :--- | :---: |
| 1 | $203;22,21, 0, 0$ | | 17 | $7;12, 0,51,46$ | -1 |
| 2 | $216;10,10, 6,34$ | -1 | 18 | $19;59,49,58,19$ | -3 |
| 3 | $224;52,26,37,45$ | -4 | 19 | $28;42, 6,29,35$ | -1 |
| 4 | $233;34,43, 9, 2$ | -1 | 20 | $37;24,23, 0,49$ | -1 |
| 5 | $246;22,32,15,35$ | -2 | 21 | $50;12,12, 7,24$ | -1 |
| 6 | $255; 4,48,46,51$ | | 22 | $58;54,28,38,35$ | -4 |
| 7 | $267;52,37,53,24$ | -2 | 23 | $67;36,45, 9,51$ | -2 |
| 8 | $276;34,54,24,39$ | -1 | 24 | $80;24,34,16,24$ | -3 |
| 9 | $285;17,10,55,53$ | -1 | 25 | $89; 6,50,47,40$ | -1 |
| 10 | $298; 5, 0, 2,26$ | -2 | 26 | $101;54,39,54,13$ | -3 |
| 11 | $306;47,16,33,42$ | | 27 | $110;36,56,25,29$ | -1 |
| 12 | $315;29,33, 4,55$ | -1 | 28 | $119;19,12,56,44$ | |
| 13 | $328;17,22,11,28$ | -3 | 29 | $132; 7, 2, 3,17$ | -1 |
| 14 | $336;59,38,42,44$ | -1 | 30 | $140;49,18,34,32$ | |
| 15 | $345;41,55,13,58$ | -1 | 31 | $149;31,35, 5,46$ | |
| 16 | $358;29,44,20,31$ | -2 | | | |

tion of the accurate value of the daily motion by the number of days in 30 Arabic years ($10631 \times 0;0,6,4,55,53 = 0;17,57,39,45,35,43$), Jai Singh probably realised that his value for the year 31 was too large by 9 sexagesimal fourths, but he did not adjust it. Note that the single error for this reconstruction ($36^{\text{iv}}$ instead of $37^{\text{iv}}$ for the year 13) can be explained as a scribal error.
Jai Singh computed the table for *collected years* by simply taking multiples of $0;17,57,39,46$, i.e. the accurate value for the motion in 30 Arabic years rounded to the number of digits of the table. Since therefore the basic parameter of the table for collected years is the motion in 30 years, we have used the tabular value for 30 years rather than that for 300 or 1200 years to obtain the estimate presented in Table 2.
The table for *months* is generally accurate, except for three of the last four values, which are one fourth too small. These include the values for an ordinary

[^17]: That the exact quotient $0;0,0,6,4,55,53,25,28,46,\dots$ was rounded to sexagesimal sixths is made plausible by the fact that our analysis of Jai Singh's mean motion parameters yield an interval $0;0,0,6,4,55,53,8 \pm 10$ of possible values for the daily motion of the ascending node of Mars (cf. Table 2). However, it should be mentioned that not all of the parameters used by Jai Singh can be precisely reconstructed in this way. It seems that in many cases the division of a value from La Hire's tables by the appropriate multiple of 365 was broken off at some point or the final digits were guessed to yield an approximate value only.

<<<CONTINUE>>>

Hijra year and a leap year, which, therefore, do not agree with the values underlying the table for extended years. Note that the error in the value for Ṣafar (14 fourths instead of 15) could be explained as a scribal error.
Also the table for days, not displayed here, is generally accurate. Only the values for 11 days (0;0,1,0), 21 days (0;0,2,1), and 33 days (0;0,3,14) are one third too small. A larger error in the value for 61 days (0;0,6,0 should have been 0;0,6,5) can be explained as a scribal mistake.
As an example of a table which can be less exactly reconstructed, Table 5 displays part of Jai Singh’s table for the mean motion in longitude of Mercury, along with the differences from an accurate computation on the basis of the daily mean motion listed in Table 2.

## CONCLUSION

We have shown that the astronomers of Jai Singh depended completely on the *Tabulae astronomicae* of Philippe de la Hire for computing the planetary mean motion tables in the *Zīj-i Muḥammad Shāhī*. Thus we have confirmed the conclusions of Mercier in his article “The Astronomical Tables of Rajah Jai Singh Sawā’ī,” which appeared in this journal in 1984. We have been able to determine the precise method by which the mean motion tables in the *Zīj-i Muḥammad Shāhī* were computed. The epoch values were found by adding the appropriate values for centuries, years, months and days found in La Hire’s tables. The daily mean motions were obtained by taking one particular mean motion value from La Hire’s tables, mostly that for 3 Julian years, but incidentally the value for 2, 5, 10 or 60 years, and dividing it by the corresponding number of days. Finally, we have uncovered various details of the methods by which the astronomers of Jai Singh computed their mean motion tables, in particular the use of rounded values for the motion in the periods underlying the tables.

## ACKNOWLEDGEMENTS

The research laid down in this article has been conducted with financial support of the Alexander von Humboldt Foundation (Bonn, Germany), the Japan
Society for the Promotion of Science (JSPS), and the Dibner Institute (Cambridge, Massachusetts). I am grateful to Professor S. M. Razaullah Ansari for suggesting to me to carry out a mathematical analysis of Jai Singh’s mean motion tables and for providing me with copies of manuscripts of the *Zīj-i Muḥammad Shāhī*. I benefited very much from discussions with Professors David Pingree and Raymond Mercier and Dr. Kim Plofker.

## NOTES AND REFERENCES

1. For the sources of the biographical information here presented and for additional information concerning life and works of Jai Singh, the reader is referred to the bibliography below.
2. According to Pingree (1976, p. 63), the *Zīj-i Muḥammad Shāhī* was most probably written by Abū al-Khayr Khayr Allāh Khān. However, for the sake of convenience we will refer to Jai Singh as the author of the work.
3. In particular for the solar apogee, the values given by Sharma differ from those we found in the manuscript of the *Zīj-i Muḥammad Shāhī* kept in Tonk.
4. Farrukhsiyar was deposed on March 1, 1719 (Gregorian), while Muḥammad Shāh came to power only on September 28 of that same year. In the seven intervening months, two puppet emperors sat on the throne. As Elphinstone (reference provided in Mercier 1984, note 8) indicates, these two emperors were left out from the official list of kings of the Moghul empire, so that the reign of Muḥammad Shāh was considered to have begun with the deposition of Farrukhsiyar. This explains how the epoch date of *Zīj-i Muḥammad Shāhī* can be connected to the accession of Muḥammad Shāh in spite of the time difference. Note that in traditional Persian calendars the beginning of the year was usually determined by the time of the vernal equinox. Also Akbar, Moghul emperor from 1556 to 1602, is known to have used a calendar based on the vernal equinox (David Pingree, personal communication). However, the vernal equinox of the year 1719 fell on 1 Jumāda I 1131 Hijra, so that it cannot explain the epoch date of the *Zīj-i Muḥammad Shāhī*.
5. Mercier’s Table I contains a mistake in the line for the longitude of Venus: the epoch position at $t_{\text{L}}$ is 41;52,0 instead of 41;52,10. As a result, the calculated position at $t_{\text{J}}$ becomes 346;43,12.2 and the derived change in meridian 73;32. The misprint in the motion of the node of Venus in 30 Hijra years (correct is 0;22,21,15,13) was already noted by Mercier himself in his review of Sharma 1995 in *Isis* 88 (1997), p. 151.
6. We will use the standard notation for sexagesimal numbers, e.g., 2;41,25 stands for $$2 + \frac{41}{60} + \frac{25}{3600}$$ or 2°41'25". Note that the values for the mean motion of Mercury and Venus in 54 minutes are given to sexagesimal thirds because they were obtained by dividing values from the respective tables for hours by 60.
7. In the Sanskrit translation of La Hire’s *Tabulae astronomicae* by Kevalarāma, a correction is applied for a difference in geographical longitude between Paris and Jaipur of $4^{\text{h}}49^{\text{m}}$, i.e. 72°15' (Pingree, to appear). Note that this value is consistent with the difference 73°30' between Paris and Delhi found above and the longitude 1°15' west of Delhi assigned to Jaipur by Jai Singh (cf. Mercier 1984, p.150).
8. Because the motions of the aphelia and nodes of the planets amount to much less than a second per day, the same tabular value will be found for series of days if the motions are expressed in seconds. In such cases La Hire entered every value only once and left the remaining entries blank. As far as we know, he did not make it completely clear which value should be taken if none is found opposite the requested number of days. For our recomputation we have always taken the tabular value *above* the line for 19 days in cases where no value is given on that line. If we had always taken the tabular value *nearest* to the line for 19 days (so also possibly *below* it), the five differences of one minute mentioned above would have disappeared, but three new ones would have been introduced.
9. This range of years is precisely the same as that in the *Sultānī Zīj* of Ulugh Beg, but besides this there are no similarities between the two sets of tables: both the tabulated quantities and the underlying parameters are clearly different.
10. Since the tables are for “current” months, the first values (for Rabi‘ II) are always equal to zero, indicating that for a date in the first month of the year no mean motion from the table for months needs to be added to the mean position at the beginning of the year. The leap day is apparently inserted at the end of the last month of the year, Rabi‘ I, which thus receives 31 days in a leap year. However, in the manuscript of the Arabic and Persian Research Institute in Tonk, interlinear values facilitate insertion of the leap day at the end of Dhu’l-Ḥijja as in the common Hijra calendar.
11. Similarly to the months, the mean motion for the first day is zero in all cases. By shifting the sexagesimal point, the values for days can also be used for the Indian sexagesimal subdivisions of a day called *ghaṛī* and *pal*.
12. Only the sub-table for extended years of the table for the mean solar longitude and that for collected years of the table for the motion of the solar apogee display values to five sexagesimal fractional digits. In the table for the mean longitude of Jupiter the fourths’ position contains zeros only, because the underlying daily mean motion happens to be an integer number of sexagesimal thirds. In the sub-tables for extended and collected years of the table for the motion of Jupiter’s aphelium, the fourths’ position contains either 0 or 30, apparently the result of intermediate rounding. For all mean motions, the values in the second half of the table for days (and in some cases the whole table) are given to sexagesimal thirds instead of to fourths.
13. Whether this multiplication was effectively carried out as a multiplication or as a repeated addition of mean motions in larger periods such as Arabic ordinary and leap years, does not make a difference for the operation of the LNEC.
14. In the case of the type of mean motion tables in the *Zīj-i Muḥammad Shāhī*, the probability that the table for extended years has constant tabular differences is around 4.1%, whereas that for the table for collected years is 2.5%, and that for the table for months approximately 13.2%. Statisticians who are interested in the concept of randomness in connection with (deterministically computed) astronomical parameters and tables are referred to Van Dalen 1993, Section 1.2.4, pp. 15-19. The above probabilities are based on the assumption that the underlying values for the daily mean motion have a uniform distribution on a certain relevant interval.
15. This is the estimate obtained under the assumption that modern rounding was used. It is not the same as the entry for the longitude of Saturn in Table 2, because the sub-table for collected years of Saturn’s mean motion table does not have constant tabular differences and hence we applied the LNEC to determine a more accurate estimate.
16. The errors of up to $1 \frac{1}{2}$ degrees that can be seen in Sharma’s recomputation of Jai Singh’s table for the mean longitude of Venus (1990, p.40; 1995, p. 248) are due to an erroneous method of computation (cf. E.S. Kennedy’s review of Sharma 1990 in *Mathematical Reviews* 1991m:01013 and R.P. Mercier’s review of Sharma 1995 in *Isis* 88 (1997), pp. 150-151). Sharma calculated the motion in 20 Arabic years from La Hire’s value for 20 Julian years by multiplying by $354;22/365;15$ (1990, p.37; 1995, p. 247), but then distributed the result over what should have been 20 Arabic years using the intercalation scheme of the Julian calendar. Thus the values $T(n)$ ($n = 1, 2, 3, \dots, 19$) in the fourth column of his Tables 3 and 11-4 (except $T(19)$, which does not seem to belong to this column at all) were effectively computed by the formula

$$T(n) = T(0) + \text{Trunc } (n . 365 \frac{1}{4} ). (T(20) + 31 . 360 - T(0)/7305,$$

where $T(0) = 346;23,34$ is Jai Singh’s epoch value, $\text{Trunc } (x)$ denotes truncation of the fractional part of $x$, $T(20) = 181;31,54°$ equals $T(0)$ plus the motion in 20 Arabic years computed from La Hire’s value for 20 Julian years, 31 is the number of rotations completed by Venus in 20 Julian years, and 7305 is the number of days in that period. Naturally there is no way in which the result could ever be close to Jai Singh’s table.
17. That the exact quotient 0;0,0,6,4,55,53,25,28,46,... was rounded to sexagesimal sixths is made plausible by the fact that our analysis of Jai Singh’s mean motion parameters yield an interval 0;0,0,6,4,55,53,8 $\pm 10$ of possible values for the daily motion of the ascending node of Mars (cf. Table 2). However, it should be mentioned that not all of the parameters used by Jai Singh can be precisely reconstructed in this way. It seems that in many cases the division of a value from La Hire’s tables by the appropriate multiple of 365 was broken off at some point or the final digits were guessed to yield an approximate value only.

## BIBLIOGRAPHY

Virendra Svarup Bhatnagar. *Life and Times of Jai Singh (1688-1743)*, Delhi (Impex India) 1974.
Benno van Dalen. *Ancient and Mediaeval Astronomical Tables: Mathematical Structure and Parameter Values* (doctoral thesis), University of Utrecht, 1993.
Philippe de La Hire. *Tabularum astronomicarum Ludovici magni* (2nd ed.), Paris 1702 (repr. 1727).
Raymond P. Mercier. “The Astronomical Tables of Rajah Jai Singh Sawā’ī”. *Indian Journal of History of Science* 19 (1984), pp. 143-171.
Honorino Mielgo. “A Method of Analysis for Mean Motion Astronomical Tables”. *From Baghdad to Barcelona* (eds. Josep Casulleras and Julio Samso), Barcelona (Instituto Millás Vallicrosa) 1996, vol. 1, pp. 159-179.
David Pingree. *Census of the Exact Sciences in Sanskrit*, Series A, Vol. 3, Memoirs of the American Philosophical Society 111, Philadelphia 1976 (repr. in 1992).
David Pingree. “Indian and Islamic Astronomy at Jayasiṃha’s Court.” From *Deferent to Equant* (eds. David A. King and George A. Saliba), New York (The New York Academy of Sciences) 1987, pp. 313-328.

66 INDIAN JOURNAL OF HISTORY OF SCIENCE
David Pingree. “Philippe de La Hire at the Court of Jayasiṃha.” To appear in *History of Oriental Astronomy, Proceedings of the Joint Discussion 17, held at the XXIIIrd IAU General Assembly, Aug, 25-26, 1997* (ed. S.M. Razaullah Ansari), Dordrecht (Kluwer Academic Publisher).
Virendra Nath Sharma. “Zīj-i Muḥammad Shāhī and the Tables of de La Hire”. *Indian Journal of History of Science* 25 (1990), pp. 34-44.
Virendra Nath Sharma. *Sawai Jai Singh and his Astronomy*, Delhi (Motilal Banarsidass) 1995.
