# On the Computation of Daily-motion in Ancient Indian Astronomy

- Author Display: Anil Narayanan
- Year: 2019
- Journal Label: IJHS-54-2019-Issue-4
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol54_4_2019__Art02.pdf

<!-- source: gemini page-chunk extraction -->

IJHS | VOL 54.4 | DECEMBER 2019 ARTICLES

# On the Computation of Daily-motion in Ancient Indian Astronomy

**Anil Narayanan***
Former Scientist, Indian Space Research Organization, 9106 Colgrove Ct, Lorton, VA 22079
(Received 21 November 2018; revised 29 August 2019)

### Abstract

The computation of the true daily-motion of a heavenly body is an important precursory step in several calculations in Indian astronomy, like those for eclipses, planetary conjunctions, longitude corrections, etc. In this article we examine all aspects of the daily-motion calculation as given in the *Sūryasiddhānta*, an ancient Indian text of astronomy. It is observed that these algorithms are based on the standard Indian planetary model. In the standard model, the true longitude of a planet is determined by the combined effects of the *manda* and *śīghra* epicycles. In an analogous manner, the daily-motion of a planet is seen to be the sum of its *manda* and *śīghra* components. Computed results based on the daily-motion algorithms, when compared with actuality, were found to be considerably accurate.
**Key words:** Daily-motion, Epicycle, Heliocentric, *Manda*, *Śīghra*, *Sūryasiddhānta*.

## 1 Introduction

The true daily-motion of a planet is employed in several computations in Indian astronomy, and its calculation illustrates, among other things, the advanced nature of the Indian science. As far as we can tell, no other ancient civilization, including the Greek and the Arab, has shown interest in computing the daily-motion of a planet as a stand-alone calculation. Thus, the conception and computation of the daily-motion as a distinct entity appears to be unique to Indian Astronomy. Uniqueness aside, three other features of this Indian computation are apt to draw our attention — first, the sheer brevity or conciseness of the calculation; second, the considerable accuracy of the computed result; third, and most interesting, the curious presence of heliocentric features in the computation.
Though the Indian planetary model is essentially geocentric, some of its core features have intimations of heliocentricity. For example, consider the planetary mean motions, which form the very core of any astronomical system. Yet another heliocentric feature can be found in the 4-step procedure for calculation of planetary longitudes. The computation of the third or penultimate step results in the heliocentric longitude of the planet, with the fourth and final step merely converting the heliocentric longitude to geocentric. These examples serve to illustrate the curious undercurrent of heliocentricity in the avowedly geocentric Indian planetary model. In this present article, we will see that the daily-motion algorithm adds yet another heliocentric feather in the cap for Indian astronomy.
There are two definitions of daily-motion for a heavenly body: (1) the mean daily-motion, and, (2) the true daily-motion. The mean daily-motion is simply the average daily-motion of the planet taken over a sufficiently long period of time, which, for all practical purposes, is a constant. The true daily-motion, on the other hand, varies considerably from day to day. It is the arc traversed by the planet in the heavens on any particular day, as seen from the earth. The magnitude of this true daily-motion oscillates about the mean daily-motion, sometimes being less that it and at other times being greater.
Besides being an interesting parameter in itself, the true daily-motion is also an essential ingredient in several other computations in Indian astronomy, like those for eclipses, planetary conjunctions, rising and setting of planets, time of meridian crossing and determination of a correction factor for the true longitude.
While the daily-motion formulae have been mentioned in several books and articles, there appear to have been few attempts at a rigorous analysis of the complete algorithm. The Indian text we will mainly refer is the *Sūryasiddhānta* (Burgess 1858), the oldest and most revered of all Indian works on astronomy. Like most Indian texts, the *Sūryasiddhānta* is at places somewhat terse and succinct. Data and computation techniques are presented in as compact a form as possible, with no explanatory notes whatsoever. Rather than being a conventional textbook, it is more a concise aid to instruction for the experienced teacher. The original text is estimated to be older than 3000 BCE (Brennand 1896; Narayanan 2010, 2011).
In this article, we will first analyze the complete set of daily-motion algorithms, and follow it up with some sample computations based on these algorithms and compare the results with actuality. We begin by taking a brief look at the Indian planetary model.

## 2 Overview of the Indian planetary model

The Indian planetary model employs the epicycle for its basis. In this respect, it is similar to the Greek, Islamic and early European models. The Indian epicycle, however, differs from the rest in a curious way. While the other epicycles are of constant size, the radius of the Indian epicycle changes with motion. That is, the epicycle expands and contracts as it moves on the deferent circle. Thus, it is sometimes called the pulsating Indian epicycle.
Figure 1 shows a schematic of the basic Indian epicycle model. The earth ($E$) is located at the center of the larger circle, the deferent. The smaller circle, called the epicycle, moves on the deferent in a CCW (counter-clockwise) manner, at an angular rate that equals the planet’s mean motion. The mean planet is situated at the center of the epicycle at $C$. The actual planet ($P$) revolves around the epicycle in one of two ways —CW (clock-wise) for the *manda* model and CCW for the *śīghra* model (Figure 1 depicts the *manda* model). The angular rate of motion of the actual planet on the epicycle equals the relative rate of motion between the mean planet and the apsis (apogee for the *manda* and conjunction for the *śīghra* models respectively).

![Figure 1 The Indian epicycle model.](media/p02_page.png)

*Figure 1 The Indian epicycle model.*

<!-- figure-resolved-page-render: page=2 image=media/p02_page.png -->

<!-- figure-meta: page=2, position=middle, type=diagram -->

The *manda* epicycle scheme, as shown in Figure 1, starts off at time $T_0$, at bottom right in the Figure with the actual planet ($P$) being farthest away from the earth. The planet at this point is said to be at its apogee ($A$). As seen from the earth, the direction of the mean-planet ($C$) here coincides with the actual planet ($P$). Sometime later, at time $T_1$, the epicycle has moved CCW on the deferent by an angle $\theta$ (the anomaly), and its center is now at $C_1$. In that same time interval, the actual planet has moved CW on the epicycle, by the same angle, to $P_1$. At this new location, the actual planet, as seen from the earth, no longer coincides with the mean-planet. The longitude of the actual planet is now the mean-planet’s longitude minus the correction angle ($\alpha$), which can be found by simple geometry. In this manner, the true *manda*-corrected longitude of the planet may be determined for any time.
Note that there is an added complication in the Indian model which we have omitted in the above description. As mentioned earlier, the radius of the Indian epicycle is not constant but varies as a function of $\theta$. The interested reader can look up Narayanan (2011) for details on how this additional feature is handled. This completes the basic Indian epicycle model. For the Sun and the Moon, whose orbits are centered on the earth, the *manda* epicycle model yields longitudes with remarkable accuracy, far more accurate than the Greek, Islamic or European models (Narayanan 2011, 2013). However, for the five visible planets, whose motion is centered on the Sun, the *manda* model by itself would not have obviously provided accurate results. Both the Indians and the Greeks took divergent paths to resolve the issue. While the Greeks resorted to various mechanical devices like cranks and off-center designs, the Indians employed the simpler idea of a second epicycle.
It appears that the ancient Indians perceived two other factors, apart from the mean motion, that influences the progress of a planet in its orbit: (1) a decelerating entity, called the *manda*, and, (2) an accelerating entity, called the *śīghra*. In Sanskrit, the words *manda* and *śīghra* mean slow and fast respectively. The *manda* and *śīghra* can be conceived to be two entities that reside at specific points in the orbit of a planet. The motion of the planet at any instant is therefore the result of the combined influence of these two entities, the magnitude of influence depending upon the nearness of the planet to either entity. An additional twist is that the *manda* and *śīghra* entities are themselves in motion. In mathematical form, the effect of these two entities on the planet’s mean motion can be expressed as two epicycles — the *manda* epicycle and the *śīghra* epicycle. Thus, to calculate the true longitude of a planet at any instant, one would first apply the *manda* correction to the mean-planet, followed by a *śīghra* correction applied to the result of the *manda* operation.
Verses 34–38 in chapter-II of the *Sūryasiddhānta* provide the dimensions of the *manda* and *śīghra* epicycles of various heavenly bodies and it is interesting to make a comparison of the physical dimensions of the two types of epicycles, *manda* and *śīghra*. Figure 2a shows the relative sizes of the *manda* epicycle for various heavenly bodies. It can be seen from the figure that the *manda* epicycles are relatively small when compared to the deferent circle. Figure 2b shows a similar illustration for the *śīghra* epicycles. Here it can be observed that *śīghra* epicycles are much larger than the *manda*. Note that the Sun and the Moon have only *manda* epicycles.
One other item to consider is the effect of epicycle pulsation — the phenomenon which increases and decreases the epicycle radius. To what degree are the *manda* and *śīghra* epicycle dimensions altered by pulsation? Table 1 shows the pulsation parameters of the *manda* and *śīghra* epicycles for each planet. In Indian astronomy, the size of the epicycle is usually specified in terms of its circumference ($C$) rather than the radius ($r$). The circumference of the deferent is assumed to be 360 degrees and the epicycle circumference is specified as a fraction of that in degrees. It can be seen from the max. and min. columns of Table 1 that the magnitude of pulsation for both *manda* and *śīghra* epicycles is quite small, very fine in fact. Doubtless, the ancient Indians had good reasons for crafting such fine control of the epicycle size. Today, with our as yet incomplete analysis of Indian astronomy, we can only marvel and conjecture about their reasons for doing so.
In modern astronomical terms, the *manda* correction is related to the correction for the equation-of-center of a planet’s orbit. Thus, the *manda* location for all the planets coincides with the aphelion of those planets, while for the Sun and the Moon it equates to the apogee of their orbits (Narayanan 2012). The equation-of-center is in turn dependent on the eccentricity of the orbit. Thus, we may expect the size of the *manda* epicycle to reflect the relative magnitude of eccentricity of the planetary orbit. This surmise is borne out in Figure 3a which shows the orbital eccentricity and relative sizes of the *manda* epicycle for the Sun, Moon and the five planets. For the inner planets Mercury and Venus, the numerical comparison of eccentricity to epicycle-size is not as good as that of the outer planets, though the trend is matched. This is expected, since the orbit of these two inner planets does not enclose the earth. For a discussion on the *manda* of the inner planets refer to the article mentioned above (Narayanan 2012).
The *śīghra* correction, on the other hand, is related to the conversion of heliocentric coordinates to geocentric. Thus, we may expect the *śīghra* epicycle dimension to depend upon the ratio of orbital radii of the planet in question and the earth. This conjecture is borne out admirably in Figure 3b which shows the ratio of the mean orbital radii of the five planets and the relative sizes of their *śīghra* epicycles. Note that the ratio of orbital radii for the two sets of planets, inner and outer, is reversed. The reason, though not complex, is beyond the scope of the current article.

<!-- figure-resolved-page-render-hidden: image=media/p04_page.png caption="Figure 2: (a) Relative sizes of manda epicycles. (b) Relative sizes of śīghra epicycles." -->

<!-- figure-meta: page=4, position=top, type=graph -->

![Figure 3: (a) Correlating planetary orbital eccentricity with manda epicycles. (b) Correlating planetary orbital radii with śīghra epicycles.](media/p04_page.png)

*Figure 3: (a) Correlating planetary orbital eccentricity with manda epicycles. (b) Correlating planetary orbital radii with śīghra epicycles.*

<!-- figure-resolved-page-render: page=4 image=media/p04_page.png -->

<!-- figure-meta: page=4, position=middle, type=graph -->

Table 1 Maximum and minimum pulsating circumferences for *manda* and *śīghra* epicycles.

| Planet | *manda* epicycle | *manda* epicycle | *śīghra* epicycle | *śīghra* epicycle |
| :--- | :--- | :--- | :--- | :--- |
| | **max. deg** | **min. deg** | **max. deg** | **min. deg.** |
| Sun | 14 | 13.66 | – | – |
| Moon | 32 | 31.66 | – | – |
| Mercury | 30 | 28 | 133 | 132 |
| Venus | 12 | 11 | 262 | 260 |
| Mars | 75 | 72 | 235 | 232 |
| Jupiter | 33 | 32 | 72 | 70 |
| Saturn | 49 | 48 | 40 | 39 |

Having covered the background of the Indian planetary system, we now move on to the 4-step procedure for determining the true longitude of a planet. As a preliminary step, the mean longitude ($L_m$) of the planet is determined at the required date-time. Next, the *śīghra* epicycle is applied to this mean longitude and the *śīghra* correction obtained. Half of this correction is applied to the mean to get the first corrected longitude $L_1$. Next, a similar operation is carried out for the *manda* epicycle. The *manda* correction is obtained and half of it applied to $L_1$ to produce longitude $L_2$. In the 3rd step, once again the *manda* correction is found, but this time the full correction is applied to the mean longitude $L_m$, which gives us longitude $L_3$. In the 4th and final step, the *śīghra* correction is obtained and applied in full to $L_3$ to produce $L_4$, which yields the true longitude of the planet. The procedure may be summarized as follows:
*   **Step-1:** Use $L_m$ as mean; find *śīghra* correction; apply half to $L_m$; get $L_1$
*   **Step-2:** Use $L_1$ as mean; find *manda* correction; apply half to $L_1$; get $L_2$
*   **Step-3:** Use $L_2$ as mean; find *manda* correction; apply full to $L_m$; get $L_3$
*   **Step-4:** Use $L_3$ as mean; find *śīghra* correction; apply full to $L_3$; get $L_4$ (true longitude)
Examining the 4-step process in detail, we observe that steps 1 and 2 effectively reset the mean longitude in a certain manner. Steps 3 and 4 then apply the full *manda* and *śīghra* corrections in tandem to this corrected mean longitude. In other words, the 4-step procedure is essentially a 2-step process comprising the *manda* and *śīghra* corrections being applied to a modified mean longitude. One remarkable output of the 4-step process is $L_3$, the longitude obtained after the 3rd step in the process. For the outer planets (Mars, Jupiter and Saturn), $L_3$ turns out to be equal to the heliocentric longitude of these planets (Burgess, 1858; Narayanan, 2012). The 4th and final step simply converts this heliocentric longitude to geocentric.
Having covered the Indian planetary model in brief, we now proceed to the main topic of this paper, namely, the calculation of the true daily-motion of a planet. Of course, using the 4-step procedure outlined above, one can always calculate the true longitude of a planet on two consecutive days, and take the difference, which will be the true daily-motion at that point in time. Indian astronomy, however, provides a shorter algorithm to determine the same, and that is what we are about to examine.

## 3 Calculation of the true daily-motion

The calculation of the true daily-motion of a planet involves the determination of its two components, namely—the *manda* daily-motion, and the *śīghra* daily-motion. The true daily-motion is then simply the sum of these ancillary daily motions. Let us examine these component daily-motions in detail.

### 3.1 Daily motion due to the *manda*

The *manda* daily-motion is derived from the dynamics of the *manda* epicycle. Figure 4a shows a schematic for the *manda* daily-motion calculation. Say, at time $T_1$ the mean planet (or epicycle) is located at $C_1$ and the actual planet...
<<<CONTINUE>>>

[^1]: DOI: 10.16943/ijhs/2019/v54i4/49768

[^2]: Email: anilkn_ban@hotmail.com

at $P_1$. Subsequently, after a time interval of one day, at time $T_2$, the mean planet has moved to $C_2$ and the actual planet is now at $P_2$. Note that due to the pulsation effect the epicycle radius $r_2$ at time $T_2$ will be smaller than $r_1$, the epicycle radius at $T_1$. That is, $C_1P_1 > C_2P_2$.
Then, the daily-motion of the planet due to the $manda$ can be expressed as $L_2 - L_1$, where $L_1$ and $L_2$ are the actual longitudes of the planet at time $T_1$ and $T_2$ respectively.
Referring to the figure, $L_1$ and $L_2$ can be written as:

$$L_1 = \theta_1 - \alpha_1 \qquad (1)$$

$$L_2 = \theta_2 - \alpha_2 \qquad (2)$$

...where $\theta_1$ and $\theta_2$ are the anomalies measured from the apogee $A_0$ at times $T_1$ and $T_2$, and $\alpha_1$ and $\alpha_2$ are the respective $manda$ corrections.
The $manda$ daily-motion ($\Delta_M$) can therefore be expressed as:

$$\Delta_M = L_2 - L_1 = (\theta_2 - \theta_1) - (\alpha_2 - \alpha_1) \qquad (3)$$

Since $\theta_2 - \theta_1$ is the $manda$ mean daily-motion ($\Delta_{Mmean}$) of the planet, (3) becomes:

$$\Delta_M = \Delta_{Mmean} - (\alpha_2 - \alpha_1) \qquad (4)$$

Now, $\alpha_1$ and $\alpha_2$ may be expressed as: $\alpha_1 = \frac{A_1}{R}$ and $\alpha_2 = \frac{A_2}{R}$, where $A_1$ and $A_2$ are the arcs $C_1e$ and $C_2o$ and $R$ is the radius of the deferent.
Thus, (4) becomes:

$$\Delta_M = \Delta_{Mmean} - \frac{(A_2 - A_1)}{R} \qquad (5)$$

Assuming the epicycle radius and the pulsation to be small in relation to the deferent, the following approximations can be made:

$$r_1 = C_1P_1 = C_2P_2 = r_2 = r$$

$$A_1 = C_1e = mp_1 = r \times \sin \theta_1$$

$$A_2 = C_2o = np_2 = r \times \sin \theta_2$$

Substituting the above into (5), we obtain:

$$\Delta_M = \Delta_{Mmean} - (\sin \theta_2 - \sin \theta_1) \times \frac{r}{R} \qquad (6)$$

Multiplying and dividing the last term in (6) by $\Delta_{Mmean} = (\theta_2 - \theta_1)$ we get:

$$\Delta_M = \Delta_{Mmean} - \Delta_{Mmean} r \frac{(\sin \theta_2 - \sin \theta_1)}{(\theta_2 - \theta_1)} \times \frac{1}{R} \qquad (7)$$

As mentioned, in Indian astronomy the epicycle size is usually specified by its circumference $C$, which is given as a fraction of the deferent circumference (assumed to be 360 degrees). That is, $\frac{r}{R} = \frac{C}{360}$, where $C$ is the epicycle circumference in degrees and $r$ and $R$ are the radii of the epicycle and deferent respectively.
Thus:

$$r = C \times \frac{R}{360}$$

Substituting the above in (7) we obtain:

$$\Delta_M = \Delta_{Mmean} - \Delta_{Mmean} \times C \times \frac{(\sin \theta_2 - \sin \theta_1)}{(\theta_2 - \theta_1) \times 360} \qquad (8)$$

The above equation is essentially the expression given in the *Sūryasiddhānta* for the daily-motion of a planet due to its *manda* (Chapter II, verses 48, 49), but adapted for usage with the Indian R-sine table.
For example, say $\theta_2$ and $\theta_1$ are 30 and 15 degrees respectively. Then, a modern computation of the expression $\frac{\sin(\theta_2) - \sin(\theta_1)}{(\theta_2 - \theta_1)}$, using regular sines, yields $\frac{(0.5 - 0.2588)}{(30 - 15)} \times \frac{180}{\pi} = 0.921$. The *Sūryasiddhānta* equivalent of this computation using R-sines is as follows: $\frac{(1719 - 890)}{(4 \times 225)} = 0.921$, where R-sine (30) = 1719, R-sine (15) = 890. The angle increments in each row of the R-sine table by 3.75 degrees or 225 minutes, and there are 4 such divisions of 225 minutes between 30 and 15 degrees, that is, $(30 - 15) = 15$ degrees = 900 minutes = $4 \times 225$.
Note that two assumptions were made in the analysis: (1) epicycle size is relatively small compared to the deferent, and, (2) pulsation is small. It can be observed from Figure 2a and Table 1 that both these assumptions are reasonable for the $manda$ scheme.
There is one other observation with regard to the $manda$ daily-motion. In the 4-step process described earlier, the $manda$ daily-motion represents the daily-rate-of-change of $L_3$, the longitude obtained after the 3rd step. Since $L_3$ for the outer planets is equal to the heliocentric longitude of the planet, the $manda$ daily-motion must equal the heliocentric daily-motion of these planets. If so, we have come upon a physical meaning for the $manda$ daily-motion.

## 3.2 Daily motion due to the śīghra

The *śīghra* daily-motion algorithm is derived from the dynamics of the *śīghra* epicycle and is similar to the *manda* calculation. There are, however, two major differences

<!-- figure-resolved-page-render-hidden: image=media/p07_page.png caption="Fig. 4. Schematic for analysis of manda daily-motion." -->

<!-- figure-meta: page=7, position=top, type=diagram -->

![Fig. 4. Schematic for analysis of śīghra daily-motion.](media/p07_page.png)

*Fig. 4. Schematic for analysis of śīghra daily-motion.*

<!-- figure-resolved-page-render: page=7 image=media/p07_page.png -->

<!-- figure-meta: page=7, position=top, type=diagram -->

**Figure 4**
between the two. Firstly, the *śīghra* epicycles are much larger than those of the *manda* and so some approximations made during the *manda* analysis will not be valid for the *śīghra*. Secondly, while the movement of the *manda* entity for all heavenly bodies (except the Moon) is extremely slow, the *śīghra* has an exceedingly rapid motion. In fact, the *śīghra* motion in all cases is faster than the mean motion of the planet itself.
Figure 4b shows a schematic for the *śīghra* daily-motion calculation. At time $T_1$ the mean planet is located at $C_1$, the actual planet at $P_1$ and the *śīghra* at $S_1$. The correction factor is $\alpha_1$ and planet's longitude $L_1$. Subsequently, after a time interval of one day, at time $T_2$, the mean planet has moved to $C_2$, the *śīghra* to $S_2$ and the actual planet to $P_2$. The correction factor is now $\alpha_2$ and longitude $L_2$. This schematic, though similar to the *manda* instance, is different in an important way; the anomaly $\theta$ is now measured from a moving reference ($S$) instead of a static one (the apogee). Also, since the *śīghra* moves faster than the mean planet, the arc $S_1S_2$ will always be greater than the arc $C_1C_2$. However, note that in Figure 4b, the arc $S_1S_2$ is shown smaller than $C_1C_2$ due to space constraint. Apart from being a representation of the *śīghra* daily-motion, the schematic shown in Figure 4b has also another interpretation. It depicts the 4th and final step of the 4-step process, namely, the application of the final *śīghra* correction to obtain the true longitude. The mean longitudes, i.e. longitudes of $C_1$ and $C_2$, are those obtained after the 3rd step in the calculation and the difference of the final longitudes ($L_2 - L_1$) is the actual daily-motion of the planet. Now if ($L_2 - L_1$) amounts to the true daily-motion, that raises the question of what constitutes the *śīghra* daily-motion? The answer is that the *śīghra* daily-motion ($\Delta_S$) is the daily-motion or daily-rate-of-change of the correction factor $\alpha$. That is:

$$\Delta_S = \alpha_2 - \alpha_1 \qquad (9)$$

As earlier, $\alpha_1 = \frac{A_1}{R}$ and $\alpha_2 = \frac{A_2}{R}$, where $A_1$ and $A_2$ are the arcs $C_1e$ and $C_2o$ and $R$ is the radius of the deferent.
Thus (9) becomes:

$$\Delta_S = \frac{(A_2 - A_1)}{R} \qquad (10)$$

The *śīghra* pulsations being small, like those of the $manda$, we can once again make the following approximation: $r_1 = C_1P_1 = C_2P_2 = r_2 = r$.
In addition, the *Sūryasiddhānta* appears to make one other approximation that is related to the hypotenuse, namely, $H_1 = EP_1 = EP_2 = H_2 = H$, the hypotenuse. The assumption here is that the daily rate of motion of the planet on the epicycle being small, the change of hypotenuse length from one day to the next is small enough to be neglected. Since the largest daily mean motion of any planet is only 4 degrees per day (for Mercury), this assumption may be considered passable.
Then, the arcs $A_1$ and $A_2$ may be closely approximated as:

$$A_1 = C_1e = (r \times \sin \theta_1) \frac{R}{H}$$

$$A_2 = C_2o = (r \sin \theta_2) \frac{R}{H}$$

Substituting the above into (10) we obtain:

$$\Delta_S = (\sin \theta_2 - \sin \theta_1) \frac{r}{H} \qquad (11)$$

Referring to Figure 4b, the anomalies $\theta_1$ and $\theta_2$ may be written as follows:
$\theta_1 = L_{C1} - L_{S1}$ (difference of longitudes of $C_1$ and $S_1$)
$\theta_2 = L_{C2} - L_{S2}$ (difference of longitudes of $C_2$ and $S_2$)
Thus,

$$\theta_2 - \theta_1 = (L_{C2} - L_{C1}) - (L_{S2} - L_{S1}) \qquad (12)$$

Now, $L_{C1}$ and $L_{C2}$ are the resultant longitudes after the 3rd step (the $manda$ correction step) in the 4-step process. That is, $(L_{C2} - L_{C1})$ constitutes the $manda$ daily-motion. Also, $(L_{S2} - L_{S1})$ is the *śīghra* mean daily-motion ($\Delta_{Smean}$).
Incorporating these changes, (12) can be expressed as:

$$\theta_2 - \theta_1 = \Delta_M - \Delta_{Smean} \qquad (13)$$

Multiplying and dividing (11) by (13), we obtain:

$$\frac{(\sin \theta_2 - \sin \theta_1)}{(\theta_2 - \theta_1)} \times \frac{r \times (\Delta_M - \Delta_{Smean})}{H} \qquad (14)$$

For small anomaly changes, the rate of change of $\sin \theta$ is $\cos \theta$. Thus (14) can be written as:

$$\Delta_S = \frac{\cos \theta \times r \times (\Delta_M - \Delta_{Smean})}{H} \qquad (15)$$

Making another approximation, namely $H - R = r \times \cos \theta$ and substituting in (15) we obtain:

$$\Delta_S = \frac{(\Delta_M - \Delta_{Smean}) \times (H - R)}{H} \qquad (16)$$

Eqn. 16 is the concise expression given in the *Sūryasiddhānta* for the daily-motion of a planet due to its *śīghra* (Chapter II, verses 50, 51). $H$ is referred to as the last hypotenuse in the text, indicating the hypotenuse employed in the final *śīghra* step in the 4-step process discussed earlier.

## 3.3 The total daily motion

As mentioned, Figure 4b portrays not only the *śīghra* daily-motion but also the 4th and final step in the computation of true longitude of a planet. Thus, the difference of longitude of the planet at times $T_2$ and $T_1$ represents the actual (total) daily motion ($\Delta$).
That is,

$$\Delta = L_{P2} - L_{P1} \qquad (17)$$

Since $L_{P2} = L_{C2} - \alpha_2$ and $L_{P1} = L_{C1} - \alpha_1$, we obtain:

$$\Delta = (L_{C2} - L_{C1}) - (\alpha_2 - \alpha_1) \qquad (18)$$

As seen earlier, the first term in brackets on the right side is the daily-motion due to the $manda$ while the second term is that due to the *śīghra*. Generalizing, we have:

$$\Delta = \Delta_M + \Delta_S \qquad (19)$$

Eqn. 19 is the expression given in the *Sūryasiddhānta* for the true daily-motion of a planet in its simple and elegant form (Chapter II, verse 51). We will employ it for computation of the daily-motion in the next section.

# 4 Computational results

Using the expressions derived above, we will now calculate the $manda$, *śīghra* and true daily motions for various heavenly bodies and compare the results with expected or actual values. We will determine the actual longitude of a planet using well-known empirical formulae in current use (Meeus 2000). To obtain the actual daily-motion of a planet we find its actual longitude from the empirical formulae on two consecutive days, and take the difference.
The test date-range for each heavenly body is shown in Table 2. The time-range of the test dates for each body was chosen to be its orbital period or greater. All test dates employed here, except for the Sun, are around the 2000 CE timeframe. For the Sun, the test dates were chosen in the 4700 BCE timeframe. The Indian epicycle model for the
**Table 2** Test Date Ranges.

| Body | Start-date | End date | Total days |
| :--- | :--- | :--- | :--- |
| Sun | Oct 13, -4699 | Oct 17, -4698 | 370 |
| Moon | Jan 4, 2000 | Feb 7, 2001 | 400 |
| Mercury | Jan 17, 2000 | Feb 19, 2001 | 400 |
| Venus | June 12, 2000 | Mar 8, 2003 | 1000 |
| Mars | Jan 17, 2000 | Jul 8, 2005 | 2000 |
| Jupiter | Jan 17, 2000 | Sep 24, 2013 | 5000 |
| Saturn | Jan 17, 2000 | Nov 23, 2032 | 12000 |

Sun is interesting in that it becomes progressively more accurate as we go back in time (Narayanan, 2011). Peak accuracy is reached around 4500–5500 BCE. With that in mind, the Sun's test data was set in that timeframe.
Let us first examine the results for the $manda$ daily-motion.

## 4.1 Results for manda daily-motion

We have seen that the $manda$ daily-motion reflects the daily-motion of $L_3$, the longitude obtained after the 3rd step in the 4-step process. Figures 5a and 5b show the calculated $manda$ and $L_3$ daily-motions for the inner planets, Mercury and Venus, for periods of 400 and 500 days respectively. It can be seen that while the $manda$ daily motion varies smoothly, the $L_3$ daily-motion has some fluctuations, especially for Mercury. Even so, the $manda$ daily-motion curve appears to be a fair approximation of the $L_3$ curve for these planets. The closeness of match of the two curves is an indication of the goodness of approximations that were made in the analysis. The $manda$ epicycle for Venus being very small, the approximations made there have a less deleterious effect than those for Mercury whose $manda$ epicycle is much larger.
As mentioned, the longitude $L_3$ in the case of the outer planets is the actual heliocentric longitude of the planet. Thus, for the outer planets, the $L_3$ daily-rate-of-change is the daily-motion of the heliocentric longitude of the planet. In other words, the $manda$ daily-motion for the outer planets represents the heliocentric daily-motion of these planets. Figures 5c, 5d and 5e show the calculated $manda$ daily-motion and the actual heliocentric daily-motions of the outer planets Mars, Jupiter and Saturn. It can be seen from the Figures that there is a very good match between the two curves.
The Sun and the Moon have only $manda$ epicycles. Thus, their $manda$ daily-motions are also their true daily-motions. We will discuss these results under section 4.3 further below.

## 4.2 Results for śīghra daily-motion

The *śīghra* daily-motion, as described in section 3.2, is a measure of the daily-rate-of-change (or daily motion) of the $L_4$ correction in the 4-step process. Figures 6a to 6e show a comparison of the modern value of *śīghra* daily-motion and the daily-motion of the $L_4$ correction for the five visible planets. For Mercury, Jupiter and Saturn there is excellent agreement between the two curves. Venus and Mars are a little off, though still in good agreement. These latter two planets, as seen from Figure 2b, possess the largest *śīghra* epicycles and thus the greater inaccuracy is a measure of the error that has crept in due to the approximations made in the analysis. At the present time there appears no discernible physical meaning that can be attributed to the *śīghra* daily-motion, apart from the connection to the 4-step process.

## 4.3 Results for true daily-motion

For computational purposes we have taken the true daily-motion to be the sum of the $manda$ and *śīghra* daily motions. The true daily-motion was calculated for the five visible planets for various intervals ranging from 400 days to 2000 days and the results are depicted in Figures 7a – 7e. The actual daily-motion is also shown for comparison. In addition, the $manda$ and *śīghra* daily-motions are presented as well for reference purposes. A few things stand out in these Figures. The variation in magnitude of the $manda$ daily-motion appears small when compared to the *śīghra* variation. Another observation is that while the *śīghra* daily-motion occasionally becomes negative (retrograde), the $manda$ daily-motion is always positive (prograde). It can be seen in these figures that the calculated

![Fig. 5.  (a) Manda and $L_3$ daily-motions for Mercury. (b) Manda and $L_3$ daily-motions for Venus. (c) Manda and actual heliocentric daily-motions for mars. (d) Manda and actual heliocentric daily-motions for Jupiter. (e) Manda and actual heliocentric daily-motions for Saturn.](media/p10_page.png)

*Fig. 5.  (a) Manda and $L_3$ daily-motions for Mercury. (b) Manda and $L_3$ daily-motions for Venus. (c) Manda and actual heliocentric daily-motions for mars. (d) Manda and actual heliocentric daily-motions for Jupiter. (e) Manda and actual heliocentric daily-motions for Saturn.*

<!-- figure-resolved-page-render: page=10 image=media/p10_page.png -->

<!-- figure-meta: page=10, position=middle, type=graph -->

**Figure 5**

IJHS | VOL 54.4 | DECEMBER 2019 ARTICLES

![Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Mercury.](figure-6a-placeholder)

*Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Mercury.*

<!-- figure-unresolved: figure=6a page_meta=missing chunk_pages=11-15 -->

![Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Venus.](figure-6b-placeholder)

*Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Venus.*

<!-- figure-unresolved: figure=6b page_meta=missing chunk_pages=11-15 -->

![Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Mars.](figure-6c-placeholder)

*Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Mars.*

<!-- figure-unresolved: figure=6c page_meta=missing chunk_pages=11-15 -->

![Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Jupiter.](figure-6d-placeholder)

*Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Jupiter.*

<!-- figure-unresolved: figure=6d page_meta=missing chunk_pages=11-15 -->

![Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Saturn.](media/p11_page.png)

*Fig. 6. Modern value of the śīghra and $L_4$ correction daily-motions for Saturn.*

<!-- figure-resolved-page-render: page=11 image=media/p11_page.png -->

<!-- figure-meta: page=11, position=middle, type=graph -->

**Figure 6**
415
***
ARTICLES IJHS | VOL 54.4 | DECEMBER 2019
true daily-motion is quite close to actuality, especially for the two outermost planets.
We shall discuss these points further in section 6.
The Sun, as mentioned earlier, has only the *manda* epicycle. Thus, its *manda* daily-motion is also its true daily motion. This calculated true daily-motion is plotted in Figure 7f along with the actual daily-motion for a period of 370 days. It can be seen that there is a very close match between the two curves.
Like the Sun, the Moon also has only one epicycle (the *manda*). However, there is an added complication in the calculation of lunar daily motion. Among the heavenly bodies the Moon is somewhat of an anomaly in that its motion is strongly influenced by two bodies, the Earth and the Sun. Therefore, its expression for daily-motion must contain a sun-related component too. However, we note that the *manda* daily-motion expression, as given in (8), has no Sun-related parameters. Thus, it is to be expected that the calculated result for the Moon’s daily-motion will not match actuality. This is indeed proved so in Figure 7g which shows a large discrepancy between the Moon’s actual and calculated daily motions, over a period of 400 days.
Figure 7h shows a similar graph, but this time with a Sun-correction applied to the *manda* daily-motion expression. From this figure we observe that the calculated daily-motion results are now greatly improved. The Sun-correction for the Moon’s daily-motion is described in section 5.1 below and discussed further in section 6. Now that we have examined the complete daily-motion algorithm as given in the *Sūryasiddhānta*, we are in a position to briefly review the works of some other Indian astronomers with regard to the daily-motion algorithm. Note that this is not an exhaustive study of all existing Indian works but only a representative survey to get a gist of the daily-motion algorithm in these other works.

## 5 The daily-motion algorithm in other ancient works

As mentioned, apart from the *Sūryasiddhānta*, several other Indian texts also indicate algorithms for calculating daily-motion. Of them Manjula observes a special mention.

### 5.1 Manjula (932 CE)

Manjula’s *Laghumānasa* (Shukla, 1990) has two verses that describe the *manda* and *śīghra* daily-motions respectively and one other verse that describes a second-correction for the Moon alone. Manjula’s Sun-related correction ($Z$) for the Moon’s daily-motion appears to be as follows:

$$Z = \Delta M_{mean} \times C \times \cos(\theta_{apo} - \theta_{sun}) \times \cos(\theta - \theta_{sun}) \times 360$$

where,
$\theta_{apo}$ = longitude of the lunar Apogee
$\theta_{sun}$ = longitude of the Sun
$\theta$ = longitude of the Moon
Applying this to (8), the full (Sun-corrected) equation for the Moon’s daily-motion becomes:

$$\Delta_M = \Delta M_{mean} - (\Delta M_{mean} \times C \times \cos(\theta) \times 360)(Z)$$

This expression was used to compute the Moon’s true daily-motion, as shown in Figure 7h.

### 5.2 Nīlakaṇṭha (1500 CE)

Nīlakaṇṭha’s *Tantrasaṅgraha* (Ramasubramanian and Sriram, 2011) contains a couple of verses dealing with the daily-motion.
> Let the product of the *koṭiphala* and the daily motion of the *kendra* be divided by the square root of the square of the *bāhuphala* of the Moon subtracted from the square of the *trijyā* (radius). The quantity thus obtained has to be subtracted from the (mean) daily motion if beginning from *makara* and is to be added to the daily motion if beginning from *karkaṭaka*. This will be a far more accurate value of the instantaneous velocity of the Moon, for the Sun also (Chapter–II, Verse 23).
For the Sun and the Moon, Nīlakaṇṭha gives above what we now understand to be the *manda* daily-motion per (8), though in a different form.
The longitude of the planet found for tomorrow is subtracted from the longitude of the planet today.
416
***
IJHS | VOL 54.4 | DECEMBER 2019 ARTICLES

![Fig. 7. Calculated and actual daily-motion for Mercury.](figure-7a-placeholder)

*Fig. 7. Calculated and actual daily-motion for Mercury.*

<!-- figure-unresolved: figure=7a page_meta=missing chunk_pages=11-15 -->

![Fig. 7. Calculated and actual daily-motion for Venus.](figure-7b-placeholder)

*Fig. 7. Calculated and actual daily-motion for Venus.*

<!-- figure-unresolved: figure=7b page_meta=missing chunk_pages=11-15 -->

![Fig. 7. Calculated and actual daily-motion for Mars.](figure-7c-placeholder)

*Fig. 7. Calculated and actual daily-motion for Mars.*

<!-- figure-unresolved: figure=7c page_meta=missing chunk_pages=11-15 -->

![Fig. 7. Calculated and actual daily-motion for Jupiter.](figure-7d-placeholder)

*Fig. 7. Calculated and actual daily-motion for Jupiter.*

<!-- figure-unresolved: figure=7d page_meta=missing chunk_pages=11-15 -->

![Fig. 7. Calculated and actual daily-motion for Saturn.](figure-7e-placeholder)

*Fig. 7. Calculated and actual daily-motion for Saturn.*

<!-- figure-unresolved: figure=7e page_meta=missing chunk_pages=11-15 -->

![Fig. 7. Calculated and actual daily-motion for the Sun.](media/p13_page.png)

*Fig. 7. Calculated and actual daily-motion for the Sun.*

<!-- figure-resolved-page-render: page=13 image=media/p13_page.png -->

<!-- figure-meta: page=13, position=middle, type=graph -->

**Figure 7**
417
***
ARTICLES IJHS | VOL 54.4 | DECEMBER 2019

![Fig. 7. Calculated and actual daily-motion for the Moon (without Sun Correction).](figure-7g-placeholder)

*Fig. 7. Calculated and actual daily-motion for the Moon (without Sun Correction).*

<!-- figure-unresolved: figure=7g page_meta=missing chunk_pages=11-15 -->

![Fig. 7. Calculated and actual daily-motion for the Moon (with Sun Correction).](media/p14_page.png)

*Fig. 7. Calculated and actual daily-motion for the Moon (with Sun Correction).*

<!-- figure-resolved-page-render: page=14 image=media/p14_page.png -->

<!-- figure-meta: page=14, position=top, type=graph -->

**Figure 7**
The result (if positive) is the retrograde daily motion of the planet; if otherwise, the result gives the direct daily motion of the planet (Chapter–II, Verse 29)
For the planets, Nīlakaṇṭha above dispenses with the need for a separate algorithm to calculate the daily-motion. He advocates finding the actual planetary position for two consecutive days and taking the difference.

## 6 Discussion

It was noted earlier that other than at peak retrograde points, the calculated daily-motion is in general a smooth curve. In the actual daily-motion data there are sometimes sharp fluctuations which are not captured very well by the calculated daily-motion curve; the calculated curve passes through these fluctuations smoothly. It may be that the calculated daily-motion is not intended to be of extreme accuracy but something in the nature of a median true daily-motion. As mentioned, the calculated daily-motion result is used in a number of other computations. It appears that a close-enough approximation of the actual daily-motion may have been considered good enough by the ancient Indian astronomers. However, this is only a conjecture, and we await further research to throw more light on the matter.
One of the remarkable things in the Indian planetary model is that for the outer planets the longitude produced at the 3rd step ($L_3$) is the actual heliocentric longitude of the planet. In this paper we have seen that $\Delta_M$, which represents the daily-motion of ($L_3$), matches the actual heliocentric daily-motion of these outer planets. This adds to the list of heliocentric features in the Indian planetary model.
The Indian epicycle model for the Sun predicts its longitude with reasonable accuracy. From the results of this study it is seen that the daily-motion expression for the Sun also predicts the actual daily-motion with remarkable precision. The Moon, unlike the planets, is strongly influenced by two objects instead of just one. Its daily-motion is the result of the combined influence of the Earth and the Sun. Thus, in the algorithm for calculation of the Moon’s daily-motion, one would expect to find some Sun-related parameters as well. However, per our current understanding of the *Sūryasiddhānta*, there appears to be no such Sun-specific factors in the text. On the other hand, the Sun-related correction of the Moon’s daily-motion provided by Manjula seems to fit into the *Sūryasiddhānta*’s basic formula perfectly, with the combination providing fairly accurate values of the lunar daily-motion, as seen in Figure 7h.
The works of later Indian astronomers appear to contain daily-motion algorithms that are very similar to those given in the *Sūryasiddhānta*, though there also appear to be some discrepancies. A detailed study comparing these
418
***
IJHS | VOL 54.4 | DECEMBER 2019 ARTICLES
algorithms is called for to sort out the matter.

## 7 Conclusion

Some conclusions that may be drawn from this study on the daily-motion of planets in Indian astronomy are as follows:
*   The distinct, stand-alone calculation of daily-motion of a heavenly body is unique to Indian astronomy. The calculation algorithms are based on the standard Indian planetary model.
*   Computed values of the true daily-motion which we have to be the sum of *manda* and *śīghra* motion were found to be considerably accurate for all the planets.
*   The *manda* daily-motion of a planet corresponds to the daily-motion of $L_3$, the longitude obtained after the 3rd step in the 4-step process. For the outer planets, the *manda* daily-motion equals their actual heliocentric daily-motion.
*   The *śīghra* daily-motion of a planet corresponds to the daily-motion of the longitude correction factor in the 4th and final step of the 4-step process.
*   For the Sun, the daily-motion model predicts the actual daily-motion with good accuracy.
*   For the Moon, the standard daily-motion formula, along with a Sun-related correction, results in fairly accurate values of its daily-motion.

### Acknowledgement

The author would like to thank the reviewers for their valuable comments and recommended suggestions which have added value to the paper.

### Bibliography

[1] Brennand W. *Hindu Astronomy*, reprinted, Caxton Publications, Delhi, 1988.
[2] Burgess E. *Sūryasiddhānta – A Text Book of Hindu Astronomy*, 1858.
[3] Chatterjee B. *Siṣyadhivṛddhida Tantra* of Lalla, Translation and Mathematical Notes, Indian National Science Academy, Delhi, 1981.
[4] Chatterjee B. *The Khaṇḍakhādyaka* of Brahmagupta, Indian National Science Academy, 1970.
[5] Meeus J. *Astronomical Algorithms*, Willmann-Bell Inc., 2000.
[6] Narayanan A. Dating the *Sūryasiddhānta* using Computational Simulation of Proper motions and Ecliptic variations. *Indian Journal of History of Science*, 45.4 (2010): 455–476.
[7] Narayanan A. The Lunar Model in Ancient Indian Astronomy, *Indian Journal of History of Science*, 48.3 (2013): 349–381.
[8] Narayanan A. The *manda* Puzzle in Indian Astronomy, *Indian Journal of History of Science*, 47.3(2012): 317–343.
[9] Narayanan A. The Pulsating Indian Epicycle of the Sun. *Indian Journal of History of Science*, 46.3 (2011): 411–425.
[10] Ramasubramanian K. and Sriram, M. S. *Tantrasaṅgraha* of Nīlakanṭha Somayājī, Hindustan Book Agency, New Delhi, 2011.
[11] Sengupta P. C. *The Khandakhadyaka*, University of Calcutta, 1934.
[12] Shukla K. S. *A Critical Study of the Laghumanasa* of Manjula, Indian National Science Academy, 1990.
419
