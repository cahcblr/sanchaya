# On Mathematical Complexity of Sriyantra

- Author Display: Vladislav-Veniamin Pustynski
- Year: 2014
- Journal Label: IJHS-49-2014-Issue-3
- Source Url: https://insa.nic.in/(S(eh1ucortlbqqezipwgliy3mn))/writereaddata/UpLoadedFiles/IJHS/Vol49_3_5_Pustynski.pdf

<!-- source: gemini page-chunk extraction -->

Indian Journal of History of Science, 49.3 (2014) 268-277

# ON MATHEMATICAL COMPLEXITY OF ŚRĪYANTRA

**VLADISLAV-VENIAMIN PUSTYNSKI***
(Received 13 August 2013)

### Abstract

*Śrīyantra* is an ancient geometrical construction based on interlocking triangles. As other ancient *yantras*, it is of large importance for meditation. Empirical methods widely used for *Śrīyantra* construction are adequate only for small shapes drawn with wide lines. High accuracy required for large shapes may be achieved using the mathematical solution based on geometrical properties of *Śrīyantra*. In this work we show how accurate parameters of *Śrīyantra* may be obtained algebraically. We study uniqueness of the solution and discuss mathematical and computational complexity of the problem.
**Key words:** Algebraic fractions, Non-linear equations, Numerical solutions, *Śrīyantra*
---

## 1. INTRODUCTION

*Śrīyantra*, also known as *Śrīcakra*, is an ancient sacred diagram widely used in Tāntric meditation practices, as well as a decorative element and an architectural form (Kulaichev & Ramendic, 1989). The central region of *Śrīyantra* represents a network of nine interlocking primary triangles inscribed into a circle. The five triangles pointing down represent *Śakti*, the female principle, and the four triangles pointing up represent *Śiva*, the male principle. The central point of the figure, *Bindu*, is common for all the triangles, it unifies both principles (Huet, 2002; Rao, 1998). Intersection points of the triangles generate secondary triangles, 43 of which (arranged in four nested complexes of 14, 10, 10, 8 triangles respectively plus the central triangle) are traditionally colored. The complex of triangles is encircled with an 8-petalled lotus, surrounded by another circle and a 16-petalled lotus. The outer lotus lies inside a triplet of concentric circles. The whole figure is placed into a square formed by three lines and provided with four gateways, see Fig. 1. Three main types of *Śrīyantra* are known: the plain shape, the spherical shape and the stepped shape. A good overview of the spiritual meaning of *Śrīyantra* and its components is given in (Rao, 1998). We note that traditional literature does not contain constraints necessary and sufficient to define a unique representation of *Śrīyantra*. It was shown in (Huet, 2002; Rao, 1998) that an unlimited number of figures satisfy the general specifications that may be found in classical literature.
Rao (1998) expressed algebraically correlations between parameters of *Śrīyantra* and specified 20 possible constraints to these parameters. He also found numerical solutions for a number of combinations of these constraints, both for spherical and plane shapes. The problem of mathematical complexity of *Śrīyantra* was studied by Kulaichev (1984). He analyzed one of possible plain *Śrīyantra* forms (corresponding to the 6th set of constraints in (Rao, 1998, Table 1), namely the variant with 10 vertices of the primary triangles lying on the circumscribing circle. This form is illustrated in Fig. 1 taken from (Kulaichev, 1984). The method of drawing *Śrīyantra* was presented as a four-step iterative process. Kulaichev found that the problem may be reduced to a system of four algebraic non-linear equations
---
\* Tallinn University of Technology, Department of Physics, Ehitajate tee 5, Tallinn 19086, Estonia; Email: vlad.pustynski@gmail.com
ON MATHEMATICAL COMPLEXITY OF *ŚRĪYANTRA* 269
<!-- figure-resolved-page-render-hidden: image=media/p02_page.png caption="Fig. 1. Plain Śrīyantra with 10 vertices lying on the circumscribing circle." -->
<!-- figure-meta: page=2, position=top, type=diagram -->
with up to sixteenth power of variables. He found a numerical solution (his results coincided with the solution of Rao) and raised the question of uniqueness of this solution. Following Kulaichev, the system of four equations may be reduced to a polynomial of a single variable with a power not higher than 12544. Kulaichev concludes that the problem of uniqueness far exceeded the capacities of computers of that time. His conclusions of an extreme geometrical and computational complexity of *Śrīyantra* were widely cited (see for instance Tularam 2012 and The Hindu News, Nov. 25, 1984).
In this work we discuss in more detail some of Kulaichev’s conclusions. We deduce all equations necessary to construct *Śrīyantra* and formulate these equations in terms of coordinates of the significant points. We demonstrate that iterative procedures may be replaced by analytical solutions in the first two steps. The systems of equations on the third and the forth step are quite unwieldy for analytical solution and should be solved using approximative root-finding methods. Therefore, all parameters of *Śrīyantra* may be found by a two-step iterative procedure. We study the equations numerically (and, where possible, analytically) and conclude that each of the steps has only one significant root. This means that only one *Śrīyantra* may be constructed with the restrictions adopted in (Kulaichev 1984). We prove that convergence of iterative processes is relatively fast; this fact simplifies the procedure of finding the solution algebraically or graphically. The deduced set of equations may be used with some modifications to solve other possible forms of *Śrīyantra*.

## 2. CONSTRUCTION STEPS AND ANALYSIS

To construct *Śrīyantra*, we follow the four-steps procedure described in (Kulaichev 1984). In each step we derive necessary equations and analyze them. We draw *Śrīyantra* step by step inside a circle with a unit radius. Only the right half of the circle is shown in the figures for more clarity. Points below the horizontal line of symmetry are labeled with primed letters.

![Fig. 2. The first step. The intersection point B’ of the segments βζ’ and Dη’ lies on the segment D’α’.](media/p02_page.png)

<!-- figure-resolved-page-render: page=2 image=media/p02_page.png -->
<!-- figure-meta: page=2, position=bottom, type=diagram -->
270 INDIAN JOURNAL OF HISTORY OF SCIENCE

### 2.1 First step

On this step the two largest of the nine primary triangles and the primary triangle with the lowermost horizontal base is drawn. We arbitrarily choose $y$-coordinate of the point $D$, i.e. the value $D_y$ ($0 < D_y < 1$), see Fig. 2. This value should be refined on the forth step. We draw symmetrical congruent triangles $D\alpha V'$ and $D'\alpha'V$, they will be the largest primary triangles.
Let’s calculate $x$-coordinates of the points $\alpha$ and $\beta$ together with their counterparts ($\alpha'$ and $\beta'$). We will need these coordinates later. It is obvious that $\alpha_x = \alpha'_x = \sqrt{1 - D_y^2}$. From the triangles $D'\alpha'V$ and $D\beta V$ it is also obvious that

$$\frac{\alpha'_x}{\beta_x} = \frac{1+D_y}{1-D_y}, \text{ so } \beta_x = \sqrt{\frac{(1-D_y)^3}{1+D_y}}.$$

We shall find now the point $\zeta'$. The segment $\zeta'\eta'$ should be horizontal and the segments $D\eta'$, $\beta\zeta'$ should intersect in the point $B'$ lying on the segment $D'\alpha'$. From the triangles $D\beta\zeta'$ and $D'\beta'\zeta'$ we find $\frac{\beta_x}{D_y-\zeta'_y} = \frac{B'_x}{D_y+\zeta'_y}$ (we take into account that $y$-coordinates below $x$-axis are negative), from the triangles $D\eta'\zeta'$ and $DD'B'$ we find $\frac{\eta'_x}{D_y-\zeta'_y} = \frac{B'_x}{2D_y}$. Since the point $\eta'$ lies on the circumscribing circle and $\zeta'\eta'$ is horizontal, $\eta'_x = \sqrt{1-\zeta'^2_y}$. These tree equations may be combined into a single equation

$$\beta_x(D_y + \zeta'_y) = -2D_y\sqrt{1-\zeta'^2_y} \quad \dots (1)$$

where $\beta_x$ depends only on $D_y$. Therefore, the formula (1) represents an equation for $\zeta'_y$ in terms of $D_y$. When squared, it becomes a quadratic equation and may be solved analytically. After some transformations, the following formula for the negative root may be obtained:

$$\zeta'_y = -D_y \frac{(1-D_y)^3+2(1+D_y)\sqrt{(1-D_y)^4+4D_y^2}}{(1-D_y)^3+4(1+D_y)D_y^2}. \quad \dots (2)$$

The second root differs by the negative sign before 2 in numerator and is positive for every $D_y$; this is obvious since $\sqrt{(1-D_y)^4+4D_y^2} > (1-D_y)^2 > (1-D_y)^3$. A positive value of $\zeta'_y$ is meaningless for *Śrīyantra*.

### 2.2 Second step

On the second step we draw the primary triangle with the uppermost horizontal base. An arbitrary point $A'$ is chosen on the segment $OD'$ ($0 < -A'_y < D_y$). Its $y$-coordinate $A'_y$ is the parameter to be refined on the third step. This point is used for a construction similar to one drawn on the first step, see Fig. 3: the point $\delta$ of intersection of $A'\epsilon$ and $\beta'\gamma$ should lie on the segment $D\alpha$, and $\gamma\epsilon$ should be horizontal.

![Fig. 3. The second step. The intersection point δ of the segments β′γ and A′ε lies on the segment Dα.](media/p03_page.png)

<!-- figure-resolved-page-render: page=3 image=media/p03_page.png -->
<!-- figure-meta: page=3, position=bottom, type=diagram -->
From the triangles $D'\beta'\gamma$ and $D\beta\gamma$ we find that $\frac{\beta_x}{\gamma_y+D_y} = \frac{\delta_x}{\gamma_y-D_y}$ (using the fact that $D'_y = -D_y$),
ON MATHEMATICAL COMPLEXITY OF *ŚRĪYANTRA* 271
from the triangles $A'\epsilon\gamma$ and $A'D\delta$ we get $\frac{\epsilon_x}{\gamma_y-A'_y} = \frac{\delta_x}{D_y-A'_y}$. Since the point $\epsilon$ lies on the circumscribing circle and $\gamma\epsilon$ is horizontal, $\epsilon_x = \sqrt{1-\gamma_y^2}$. These tree equations may be combined into a single equation

$$\beta_x (\gamma_y - A'_y) (D_y - A'_y) = (\gamma_y + D_y) (D_y - A'_y) \sqrt{1 - \gamma_y^2}, \quad \dots (3)$$

where $\beta_x$ depends only on $D_y$. Therefore the formula (3) represents an equation for $\gamma_y$ expressed in terms of $D_y$ and $A'_y$. When squared, it becomes a quartic equation with respect to $\gamma_y$:

$$a\gamma_y^4 + b\gamma_y^3 + c\gamma_y^2 + d\gamma_y + e = 0 \quad \dots (4)$$

where $a, b, c, d$ and $e$ are the following functions of $D_y$ and $A'_y$:

$$a = \beta_x^2 + (D_y - A'_y)^2,$$

$$b = 2 \left[ D_y(D_y - A'_y)^2 - \beta_x^2 (A'_y + D_y) \right],$$

$$c = \beta_x^2 \left[ (A'_y + D_y)^2 + 2A'_y D_y \right] - (D_y - A'_y)^2 (1 - \beta_x^2),$$

$$d = -2D_y \left[ \beta_x^2 (A'_y + D_y) A'_y + (D_y - A'_y)^2 \right],$$

$$e = D_y^2 \left[ \beta_x^2 A'_y^2 - (D_y - A'_y)^2 \right]. \quad \dots (5)$$

Since quartic equations may be solved analytically, the second step of *Śrīyantra* also has an analytical solution. However, quartic equations may have up to four real roots, and the question of the number of roots of Eq. (4) in the range ($-D_y, 0$) should be studied. It may be more simple to return to Eq. (3) and to express $A'_y$ as a function of $\gamma_y$:

$$A'_y = \frac{D_y (\gamma_y + D_y) \sqrt{1 - \gamma_y^2} - \beta_x \gamma_y (D_y - A'_y)}{(\gamma_y + D_y) \sqrt{1 - \gamma_y^2} - \beta_x (D_y - A'_y)}. \quad \dots (6)$$

Eq. (6) was studied numerically. $A'_y$ versus $\gamma_y$ was plotted in the range ($D_y, 1$) for different values of $D_y$ (we used a dense grid of 10 000 points for $\gamma_y$). It was found that the function $A'_y = f(\gamma_y)$ has similar appearance for all values of $D_y$. Its behavior is the following: $D_y = f(D_y)$; when $\gamma_y$ increases, $f$

![Fig. 4. Function A′y = f (γy) for three different values of the parameter Dy.](media/p04_page.png)

<!-- figure-resolved-page-render: page=4 image=media/p04_page.png -->
<!-- figure-meta: page=4, position=top, type=graph -->
decreases to zero and becomes negative; at some point it becomes smaller than $-D_y$. When the denominator of Eq. (6) approaches zero, $f$ approaches $-\infty$ from the left and to $+\infty$ from the right. With further growth of $\gamma_y$, $f$ drops to unity: $f(1) = 1$. For $\gamma_y > 1$ only complex values of $A'_y$ exist. Fig. 4 illustrates the behavior of the function $A'_y = f(\gamma_y)$ for three different values of the parameter $D_y$. It is seen that $A'_y$ is a one-to-one function of $\gamma_y$, and this is true for each value of $D_y$. Therefore the opposite is also true: there is only one positive value of $\gamma_y$ that corresponds to each negative value of $A'_y$. This fact proves the uniqueness of the positive root of Eq. (4). Of course, this equation has also at least one negative root (and sometimes may have two or three negative roots), but negative roots are meaningless for *Śrīyantra*.
Thus it has been proven that the first two steps have unique analytical solutions. However, since analytical solution of quartic equations requires many operations, one may prefer to solve the second step numerically, as it is frequently done in practice with quartic equations. In this case we recommend to solve directly Eq. (3) as it is relatively simple.

### 2.3 Third step

The third step is based on intersection points obtained on the first and the second steps.
272 INDIAN JOURNAL OF HISTORY OF SCIENCE
<!-- figure-resolved-page-render-hidden: image=media/p05_page.png caption="Fig. 5. The third step. Points λ, ρ, θ′, ϕ′ lie on intersections of three segments." -->
<!-- figure-meta: page=5, position=top, type=diagram -->

![Fig. 6. The forth step. The central circle is inscribed into the triangle A′χω.](media/p05_page.png)

<!-- figure-resolved-page-render: page=5 image=media/p05_page.png -->
<!-- figure-meta: page=5, position=middle, type=diagram -->
We complete the two primary triangles that we started in the first two steps and add two inner primary triangles (see Fig. 5). On this step the parameter $A'_y$ (chosen freely on the 2nd step) becomes fixed by the value of the parameter $D_y$, i.e. it becomes a function of $D_y$.
On this step it is convenient to find coordinates of intersection points of segments using equations of lines corresponding to these segments. Let’s start with the point $\theta'$ lying in the intersection of the segments $V'\alpha$ and $D\eta'$. The equation of the line $V'\alpha$ is $y = \frac{1+D_y}{\alpha_x}x - 1$ and the equation of the line $D\eta'$ is $y = -\frac{D_y-\zeta'_y}{\eta'_x}x + D_y$. The point $\theta'$ belongs to both lines, so we get its coordinates solving the system of the two equations. The result is:

$$\theta_x = \frac{(1+D_y)\alpha_x\eta'_x}{(1+D_y)\eta'_x + (D_y-\zeta'_y)\alpha_x}, \quad \theta_y = \frac{(1+D_y)^2\eta'_x}{(1+D_y)\eta'_x + (D_y-\zeta'_y)\alpha_x} - 1 \quad \dots (7)$$

Other intersections are found in a similar way. $\lambda$ lies in the intersection of the segments $V\alpha'$ and $A'\epsilon$, so from the equations of these two lines we get

$$\lambda_x = \frac{(1-A'_y)\alpha_x\epsilon_x}{(1+D_y)\epsilon_x + (\gamma_y-A'_y)\alpha_x}, \quad \lambda_y = \frac{(\gamma_y-A'_y)(1-A'_y)\alpha_x}{(1+D_y)\epsilon_x + (\gamma_y-A'_y)\alpha_x} + A'_y \quad \dots (8)$$

Next we find the point $\xi'$ where the horizontal line crossing the point $A'$ touches the segment $\zeta'v$:

$$\xi'_x = \frac{A'_y - \zeta'_y}{D_y - \zeta'_y}\beta_x, \quad \xi'_y = A'_y \quad \dots (9)$$

The point $\rho$ is the intersection point of $A'\epsilon$ and $\mu\zeta'$ (we use the fact that $\mu_y = \lambda_y$):

$$\varrho_x = \frac{(\lambda_y-A'_y)\epsilon_x\xi'_x}{(\gamma_y-A'_y)\xi'_x + (\lambda_y-A'_y)\epsilon_x}, \quad \varrho_y = \frac{(\gamma_y-A'_y)(\lambda_y-A'_y)\xi'_x}{(\gamma_y-A'_y)\xi'_x + (\lambda_y-A'_y)\epsilon_x} + A'_y$$

These equations may be simplified using Eq. (8):
<<<CONTINUE>>>

ON MATHEMATICAL COMPLEXITY OF ŚRĪYANTRA 273

$$\varrho_x = \frac{\xi'_x \lambda_x}{\xi'_x + \lambda_x}, \quad \varrho_y = \frac{(\lambda_y - A'_y)\xi'_x}{\xi'_x + \lambda_x} + A'_y \dots(10)$$

The point $\varrho$ defines the point $\tau$ on the horizontal segment passing through $\varrho$ and touching the segment $\lambda\kappa'$ (i.e. on the segment $\sigma\tau$):

$$\tau_x = \frac{\gamma_y - \varrho_y}{\gamma_y + D_y} \beta_x, \quad \tau_y = \varrho_y. \dots(11)$$

The final and the key point of this construction is $\phi'$. We may look for two points: the point $\phi'_1$ where the segment $D\eta'$ intersects with the horizontal segment $A'\zeta'$, and the point $\phi'_2$ where the segment $\iota'\tau$ intersects with $A'\zeta'$. The line equations give:

$$\phi'_{1x} = \frac{D_y - A'_y}{D_y - \zeta'_y} \eta'_x, \quad \phi'_{2x} = \frac{\varrho_y - A'_y}{\varrho_y - \iota'_y} \tau_x, \quad \phi'_{1y} = \phi'_{2y} = A'_y. \dots(12)$$

If the point $A'$ is arbitrary, $\phi'_1$ and $\phi'_2$ do not coincide in the general case. But in accurately drawn Śrīyantra they coincide in a single point $\phi'$. Thus $A'_y$ should be chosen in a way that the condition $\phi'_{1x} = \phi'_{2x}$ is satisfied, i.e.

$$\frac{D_y - A'_y}{D_y - \zeta'_y} \eta'_x - \frac{\varrho_y - A'_y}{\varrho_y - \iota'_y} \tau_x = 0 \dots(13)$$

The Eqs. ($7 - 11, 13$) together with the equations $\alpha_x = \sqrt{1 - D_y^2}; \beta_x = \sqrt{\frac{(1 - D_y)^3}{1 + D_y}}; \varepsilon_x = \sqrt{1 - \gamma_y^2}; \eta'_x = \sqrt{1 - \zeta'^2_y}$ form a system. Theoretically it is possible to reduce this system to a singe relation between the parameters $D_y$ and $A'_y$. Unfortunately, such a relation would be very unwieldy and it would be impossible to find $A'_y$ as an analytical function of $D_y$.
However, the above-mentioned system of equations may be analyzed numerically. We performed this analysis sequentially substituting coordinates from the earlier equations into the Eq. (13) and studying numerically the trend of the difference $\phi_{1x} - \phi_{2x}$ as a function of $A'_y$. We plotted this difference against $A'_y$ using a dense grid of $A'_y$ values (the range of $A'_y$ was divided into 10 000 points). It was found that $\phi'_{1x} - \phi'_{2x}$ is a uniformly decreasing function for all values of $D_y$. In Fig. 7 this function is plotted for three values of $D_y$ (the trends are increasing since $-A'_y$ values are depicted for convenience in the $x$-axis). There is no sign of local extrema on the graphs, and, considering the high density of the grid, there is evidently no chance that local extrema could have been missed. Thus we may conclude that the third step has a unique solution. Further study shows that $\phi_{1x} - \phi_{2x}$ has an infinite discontinuity at the point $-1$: $\lim_{A'_y \to -1^-} = +\infty$ and $\lim_{A'_y \to -1^+} = -\infty$. A second root is present in the domain $A'_y < -1$, more roots may appear in the domain $A'_y > 0$; however, these roots are meaningless for Śrīyantra.

![Fig. 7. Difference $\phi_{1x} - \phi_{2x}$ as a function of $A_y$ for three different values of $D_y$. All graphs are plotted in the range $(0 - D_y)$.](media/p06_page.png)

<!-- figure-resolved-page-render: page=6 image=media/p06_page.png -->
<!-- figure-meta: page=6, position=middle, type=graph -->
Since the formulae used in this step are quite simple by their nature (algebraic fractions), it takes very little computational time to find the root of Eq. (13) even with the simplest numerical methods (i.e. with the secant method). It is important since this root is used as an intermediate result on the forth step and should be calculated many times while seeking for $D_y$, see Section 2.4. To conclude this section, we give the formulae for the points $\nu$ and $\kappa'$ (these points are vertices of two primary triangles, see Fig. 5):
274 INDIAN JOURNAL OF HISTORY OF SCIENCE

$$v_x = \frac{\lambda_y - \zeta'_y}{D_y - \zeta'_y} \beta_x, \quad v_y = \lambda_y;$$

$$\kappa'_x = \frac{\gamma_y - \theta'_y}{\gamma_y + D_y} \beta_x, \quad \kappa'_y = \theta'_y \dots(14)$$

### 2.4 Forth step

On the forth step the ninth (i.e. the smallest) of the primary triangles is drawn, and the construction of Śrīyantra is completed. On this step the value of the parameter $D_y$ (chosen freely on the first step) becomes fixed, and the whole construction finally becomes rigid.
First we will need the point $\chi$, that is the intersection point of the segments $D\eta'$ and $A'\varepsilon$. Using the equations of the corresponding lines, we find from the condition of their intersection:

$$\chi_x = \frac{(D_y - A'_y)\varepsilon_x \eta'_x}{(\gamma_y - A'_y)\eta'_x + (D_y - \zeta'_y)\varepsilon_x}$$

$$\chi_y = \frac{(D_y - A'_y)(\gamma_y - A'_y)\eta'_x}{(\gamma_y - A'_y)\eta'_x + (D_y - \zeta'_y)\varepsilon_x} + A'_y \dots(15)$$

Next we find a point $\psi$ where the segment $\omega\chi$ touches the segment $\mu\zeta'$. (Please note that the point $\psi$ is not the intersection point of the segments $\iota'\tau$ and $\mu\xi'$, although in the final construction $\chi$ will lie very close to this point). The coordinates of $\psi$ are:

$$\psi_x = \frac{\lambda_y - \chi_y}{\lambda_y - A'_y} \xi'_x, \quad \psi_y = \chi_y. \dots(16)$$

The final detail of the construction is the circle inscribed into the innermost triangle $\omega\chi A'$: this circle should be concentric with the circumscribing circle of Śrīyantra. Let's formulate this condition algebraically. The radius of the innermost circle is $R = \chi_y$. The distance from the central point to the segment $A'\varepsilon$ should be the same. The well-known formula for the distance from a point to a line gives $R = \frac{A'_y \varepsilon_x}{\sqrt{(\gamma_y - A'_y)^2 + \varepsilon_x^2}}$, so we finally get:

$$\chi_y + \frac{A'_y \varepsilon_x}{\sqrt{(\gamma_y - A'_y)^2 + \varepsilon_x^2}} = 0 \dots(17)$$

The condition (17) is satisfied only for a specific value of $D_y$. Since it is impossible to find $A'_y$ analytically on the third step, we are obliged to rely again on numerical methods and to solve Eq. (17) iteratively. At each step of the iteration it is necessary to repeat the steps 1–3.

![Fig. 8. Difference $\chi_y - R$ as a function of $D_y$.](media/p07_page.png)

<!-- figure-resolved-page-render: page=7 image=media/p07_page.png -->
<!-- figure-meta: page=7, position=middle, type=graph -->
Since our task is not only to obtain the solution of Śrīyantra, but also to study uniqueness of this solution, we investigated Eq. (17) numerically. The left-hand side of Eq. (17) was plotted as a function of $D_y$ in the range (0, 1) (a dense grid of 10 000 values of $D_y$ was used). The resulting trend is represented in Fig. 8. Numerical analysis shows that the trend has a singularity at the point $D_y = 0$. This point corresponds to the degenerate case, when the segments $D\alpha$ and $D'\alpha'$ (and consequently the whole construction) merge together. Of course this point is meaningless for the actual Śrīyantra. It may be concluded from Fig. 8 that Eq. (17) has a single root in the range $0.25 < D_y < 0.30$. This proves that Śrīyantra with restrictions set in (4) has a unique solution.

### 2.5 Results

Eq. (17) was solved numerically. Table 1 contains coordinates of all points shown in Fig. 6 (with exception of symmetrical points $D'$, $\alpha'$ and $\beta'$). The values of $\gamma_y, \zeta'_y, A'_y$ and $D_y$ (i.e. the parameters calculated on the steps 1 – 4) are put in bold. 15 figures are given for each coordinate, at least 14 of them are significant. Our
ON MATHEMATICAL COMPLEXITY OF ŚRĪYANTRA 275
results coincide with the results by (Rao 1998) (where 6 significant figures are given) and are slightly more accurate then the values in (Kulachev 1984) (where 12 figures are given, the first 10 of them are correct). As it has been demonstrated, Śrīyantra does not have alternative solutions.
Table 1. Coordinates $x$ and $y$ of points in Fig. 6

| Point | $x$ | $y$ |
| :--- | :--- | :--- |
| $D$ | 0 | **0.279461220861835** |
| $A'$ | 0 | **-0.101410465950899** |
| $B'$ | 0.270779392705488 | -0.279461220861835 |
| $\alpha$ | 0.960156979891524 | 0.279461220861835 |
| $\beta$ | 0.540720052152901 | 0.279461220861835 |
| $\gamma$ | 0 | **0.793459849383596** |
| $\delta$ | 0.259039898580079 | 0.279461220861835 |
| $\varepsilon$ | 0.608622598509258 | 0.793459849383596 |
| $\zeta'$ | 0 | **-0.840120291819195** |
| $\eta'$ | 0.542400124699129 | -0.840120291819195 |
| $\Theta'$ | 0.376680058433962 | -0.498053404254090 |
| $\iota'$ | 0 | -0.498053404254090 |
| $\kappa$ | 0.650883958969493 | -0.498053404254090 |
| $\lambda$ | 0.392957431667828 | 0.476362922107536 |
| $\mu$ | 0 | 0.476362922107536 |
| $\nu$ | 0.635816922689476 | 0.476362922107536 |
| $\xi'$ | 0.356771892930644 | -0.101410465950899 |
| $\tilde{n}$ | 0.186995709167944 | 0.173533168477376 |
| $\sigma$ | 0 | 0.173533168477376 |
| $\tau$ | 0.312424461152494 | 0.173533168477376 |
| $\phi'$ | 0.184519704980561 | -0.101410465950899 |
| $\chi$ | 0.107759961187845 | 0.057031219725571 |
| $\psi$ | 0.258935022478938 | 0.057031219725571 |
| $\omega$ | 0 | 0.476362922107536 |

It is interesting to note that the intersection point of the segments $\mu\xi'$ and $\iota'\tau$ is very close to the point $\psi$. It’s $x$-coordinate is only $\approx 4.0 \times 10^{-4}$ smaller than $\psi_x$ and its $y$-coordinate is only $\approx 6.5 \times 10^{-4}$ larger than $\psi_y$. Since this point lies to the upper left of $\psi$, the segments $D'\psi$ and $\iota'\tau$ also intersect within close proximity to $\psi$, and two additional tiny triangles are formed.
All calculations were performed with the aid of Asymptote Vector Graphics Language-based software by SOURCEFORGE, which was also used to construct Śrīyantra in vector format. Although a two-step iteration was required, an ordinary PC was able to find the solution and to build the plot within seconds.

## 3. DISCUSSION

It was found that all parameters of Śrīyantra with the constraints adopted in (Kulaichev, 1984) and in (Rao, 1998) may be found via a two-step iteration procedure. The first two steps have analytical solutions. Analytical and numerical analysis shows that each of the four steps has a unique root. Therefore we conclude that there is only one set of parameters satisfying the adopted constraints. Unfortunately, purely analytical solution of the final two steps is probably impossible since the corresponding equations are too unwieldy.
As it was mentioned in Section 1, the analyzed variant is only one of many possible representations of Śrīyantra. However we consider this variant to be important by two reasons.
1) First, in this variant ten vertices of four primary triangles belong to the circumscribing circle, while in other representations the number of such vertices is only six, and only two primary triangles are in contact with the circle. This feature makes the figure visually more complex. Kulaichev (1984) hypothesizes that this form is the basic representation of Śrīyantra, other forms being its simplifications. If we reject the above-mentioned constraint without adding other restrictions, Śrīyantra will not be a rigid figure anymore, and it will be possible to continuously deform it; so its drawing will be simplified to a large extent. Kulaichev notices that although simplified figures are more common, most of them are not so old as the studied variant, the earliest representations of which may be dated not later than 17 century AD.
276 INDIAN JOURNAL OF HISTORY OF SCIENCE
2) Most of the variants studied by (Rao, 1998) are defined by 5 constraints (see the next paragraph). The variant we studied is apparently based only on 4 constraints. The reason is that there is an additional “superconstraint” in this variant, namely, the two largest primary triangles are congruent, so $D_y = - D'_y$. This feature gives more symmetry to the figure and makes its geometry more restricted in comparison with other forms.
Although other Śrīyantra variants are possible, some of our results may be directly applied to other representations. For instance, the analytical solutions of the first and the seconds steps remain unchanged for each variant with congruent primary triangles $D\alpha V'$ and $D'\alpha'V$ and the points $\varepsilon, \eta'$ lying on the circumscribing circle. Most of the derived equations may remain unaltered even if some constraints are replaced with other ones: these equations are algebraic manifestations of line intersections and they keep until the corresponding lines intersect. Of course, if some equations are altered, a new solution of the whole figure should be found and the problem of uniqueness of that solution should be studied again. If additional free parameters are introduced, more steps should be added to the procedure of solution. Rao (1998) uses five parameters $b, c, d, e, g$; they are related to our parameters $\gamma_y, \zeta'_y, A'_y$ and $D_y$ in the following way: $b = - (D_y + \zeta'_y), c = -D'_y, d = D_y, e = \gamma_y - D_y$ and $g = - A'_y$. If we cancel the restriction that the triangles $D\alpha V'$ and $D'\alpha'V$ are congruent, the equality $D_y = - D'_y$ will vanish and a fifth free parameter will appear. Canceling one restriction would imply a need to introduce another restriction to keep Śrīyantra rigid.
It is relatively easy to solve and analyze Śrīyantra equations numerically since they have a sufficiently simple form of algebraic fractions. The simplest numerical algorithms (bisection method and secant method) are adequate to find approximate roots with a high degree of accuracy. Even massive calculations required to make Fig. 8 were performed on an ordinary PC in less than ten seconds.
It remains questionable, though, if it was possible to find an accurate solution of Śrīyantra in pre-computer era. Algebraic solution of Śrīyantra does not require a lot of mathematical knowledge. In principle, it is enough to be able to calculate fractions, square roots and to know some approximative root-finding method. Theoretically, a more or less accurate solution could have been found centuries ago: methods of finding quadratic roots were known to Indian mathematicians at least from the times of Śulba-Śūtras, and Brahmagupta was the first who gave an explicit method to solve quadratic equations (Colebrooke, 1817). Approximative calculations were also known since ancient times. However, technically the procedure of finding the solution probably was too complicated for ancient mathematicians, since the total amount of calculations is really large. Nevertheless we would like to stress that computer is not required to get a sufficiently accurate result. Using for computations only a pocket calculator, we were able to get the parameters of Śrīyantra in several days with an accuracy better than 0.01%. It may be explained by the fact that discrepancies in intersection points grow slowly when parameters diverge from their exact values. Fig. 7 shows that discrepancy in the point $\phi'$ grows $\sim 2$ times slower than $A'_y$, and Fig. 8 shows that discrepancy between $\chi_y$ and $R$ grows only by about $0.01 \div 0.02$ when $D_y$ differs by 0.1 from its exact value. Such a slow growth of discrepancy leads to quick convergence of root-finding iterative procedures. Of course, it also helps to find the solution geometrically, adjusting the drawing manually step-by-step and fixing the best result with the aid of algebraic proportions between the parameters of the best fit. Therefore, obviously
ON MATHEMATICAL COMPLEXITY OF ŚRĪYANTRA 277
Śrīyantra may be drawn with sufficient accuracy by manual iterations in reasonable time.

## REFERENCES & BIBLIOGRAPHY

Algebra, with arithmetic and mensuration, from the Sanscrit of Brahmegupta and Bhascara,” translation by Henry Thomas Colebrooke. London 1817, pp. 346-347.
Huet G. Sri Yantra Geometry. *Theoretical Computer Science*, 281 (2002) 609-628.
Kulaichev, A.P. Śrīyantra and its Mathematical Properties. *IJHS*, 19.3 (1984) 279-292.
Kulaichev, A.P. and Ramendic, D.M. Śrīyantra – the Ancient Instrument to Control the Psychophysiological State of Man. *IJHS*, 24.3 (1989) 137-149.
Rao, C.S. Śrīyantra – A Study of Spherical and Plane Forms. *IJHS*, 33.3 (1998) 203-227.
Śri yantra – an enigma, The Hidnu News, November 25 (1984).
Tularam, G.A. Investigating the Development of Arithmetic and Algebra in Vedic India: Tribute to Swami Dayananda Saraswati. *International Journal of Mathematics, Game Theory and Algebra*, 20.2 (2012) 163-187.
