# Ois Curve

Overnight index swaps OIS curves became the market standard for discounting collateralized cashflows. The reason often given for using the OIS rate as the discount rate is that it is derived from the fed funds rate and the fed funds rate is the interest rate usually paid on collateral. As such the fed funds rate and OIS rate are the relevant funding rates for collateralized transactions.

n the past, a classic yield curve, such as 3 month LIBOR was used for both discounting cashflows and projecting forward rates. However, this classic viewpoint is too simplistic. It does not take into account the relative credit risk between lending money forward over a short period of time at interbank rates, versus the risk involved in short-term funding of those loans.

Prior to the 2007 financial crisis, market practitioners considered the swap curve as a proxy for the risk-free curve and used it for discounting cashflows. LIBOR is the short-term borrowing rate of AA-rated financial institutions, but still is not risk-free. Specifically, in stressed market conditions as the 2007 financial crisis, TED-which is the spread between three month US LIBOR and three month US treasury rate-increased dramatically; in October 2008, it reached over 450 basis points. Besides that, the 2007 financial crisis triggered high basis spreads for swaps characterized by different underlying rate tenors. As a result, the swap curve data can not be regarded as risk free anymore.

Market practitioners started to use a new valuation methodology referred to as dual curve discounting, OIS discounting or CSA discounting. OIS curves became the market standard for discounting collateralized cashflows. This curve represents the market expectations of the Federal Reserve daily target for the overnight lending rate.

The reason often given for using the OIS rate as the discount rate is that it is derived from the fed funds rate and the fed funds rate is the interest rate usually paid on collateral. As such the fed funds rate and OIS rate are the relevant funding rates for collateralized transactions. Many banks now consider that overnight indexed swap OIS rates should be used for discounting when collateralized portfolios are valued and that LIBOR should be used for discounting when portfolios are not collateralized.

The most liquid instruments that can be used to build OIS curve are Fed Fund Futures and OIS swaps that pay at the daily compounded Fed Fund rate. However, Fed Fund Futures are currently only liquid up to two years and OIS swaps up to ten years. Beyond ten years, the most liquid instruments are Fed Fund versus 3M LIBOR basis swaps, which are liquid up to thirty years.

The problem is that to price these basis swaps one needs both the OIS curve, to project the Fed Fund rate, and the LIBOR curve, to project the LIBOR rate. In the past one could have generated the LIBOR curve data separately, by using the single curve for both forward projection and discounting.

However, in the modern market LIBOR swaps are quoted using OIS discounting. This means that in order to generate a forward LIBOR curve from LIBOR swap quotes one must first have the OIS curve already constructed so that one knows how to discount the cashflows. So neither the OIS curve nor the Libor curve can be built without the other. The two curves must be generated simultaneously.

The central tenet of curve construction under OIS discounting is to bootstrap multiple curves simultaneously. One needs two term structure inputs for curve construction under OIS discounting: a term structure of OIS instruments and a term structure of swaps.

References:

https://finpricing.com/lib/EqAutocallable.html

