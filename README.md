# Interest Rate Models

Deck 12 of the [Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series](https://github.com/BrendanJamesLynskey/Wilmott_QF_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/Wilmott_QF_12_Interest_Rate_Models/

A guided tour of chapters 16, 17, 18 and 19 of *Paul Wilmott Introduces Quantitative Finance*
(2nd edition, Wiley, 2007) &mdash; from the stochastic short rate to the bond pricing
equation, the named one-factor models, the HJM framework and the LIBOR market model.

## What's inside

- The stochastic short rate $r_t$, modelled as $dr = u(r,t)\,dt + w(r,t)\,dW$
- The bond pricing equation derived from a two-bond portfolio; the market price of risk $\lambda$
- Risk-neutral vs real-world drift &mdash; pricing under $\mathbb{Q}$, risk under $\mathbb{P}$
- **Vasicek** ($dr = (a-br)dt + \sigma dW$) &mdash; mean-reverting, Gaussian, can go negative
- **Cox&ndash;Ingersoll&ndash;Ross** ($dr = (a-br)dt + \sigma\sqrt{r}dW$) &mdash; non-negative, Feller condition
- **Ho&ndash;Lee** and **Hull&ndash;White** &mdash; time-dependent drift $\theta(t)$ to fit the curve exactly
- The yield-curve fitting trade-off: parameter stability vs. exact repricing
- The **Heath&ndash;Jarrow&ndash;Morton** framework; the no-arbitrage drift condition $\mu = \sigma \int \sigma$
- The **Brace&ndash;Gatarek&ndash;Musiela / LIBOR market model** &mdash; log-normal forward rates, the workhorse of fixed-income desks
- **Interactive short-rate path simulator** &mdash; choose Vasicek / CIR / Ho&ndash;Lee, sweep $r_0$, $a$, $b$, $\sigma$, $T$, $N$, and read off the empirical mean and standard deviation of $r_T$ against the theoretical Vasicek stationary mean

Companion to chapters 16, 17, 18 and 19 of:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
