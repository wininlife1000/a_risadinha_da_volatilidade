# a_risadinha_da_volatilidade

Chapter 4: Variance Swaps

-volatility sensitivity
-volatility and variance swaps
-replicating volatility swaps
-...out of option in BSM
-vanilla options 1/K**2 weights pay out logarithmically
-proof that logarithmic contract S^*=S^0 is future variance

$options are sensitive to VIX and price K
$trading volatility is superior when traded with variance swaps
$how to replicate variance swaps
$how to value swaps
$error in replication causes

Chapter 5: Profit & Loss of Hedged Options

-BSM Equation-> S*phi(d_1)-K_pv*phi(d_2);d_1_2=ln(S/K_pv)+-0.5*v**2;K_pv=e**(-r*t)*K
-P&L -> profit and loss over time

$Call options and stock can make riskless the portfolio
$BSM = Black Scholes Merton
$BSM options formula should be memorized
$Volatility Based P&L is powerful

Chapter 6: The Effect of Discrete Hedging on Profit and Loss

-replication errors from discrete rebalancing

$hedging perfectly continuously
$finite rebalancing strategy
$more hedges, more model perfection to variance
$the cause of transaction costs


Chapter 7: Effect of Transaction Costs on Profit and Loss

-effectiveness of transactions
-analytical approximating transactions

$transactions make long positions worthless and short positions worthmore
$accuracy and other considerations
$effective volatility of hedged options

Chapter 8: The Smile

-consequences of smile for trading
-most popilar and liquid options are ATM options with delta~=0.5 -> delta~=delta_ATM-J/sqrt(2*pi*vega**2);What's J?

$violating BSM, IV's vary with strike expiry
$bond deined by yield
$the smile is easy, function of delta
$standards key is IV  in [+25% of call,-25% of put]
$smile, term structure, surface, skew

Chapter 9: No-Arbitrage Bound on the Smile

-no arbitrage bounds of smile

$constraints on options
$merton inequalities
$inequalities for slope of smile: butterfly,C(K-dK)-2C(K)+C(K+dK)>=0


Chapter 10: A Survey of Smile Models

-problems  caused by the smile
-valuing exotic options
-hedging vanilla options

$overview of smile-consistent models
$local volatility models, stochastic volatility models, jump diffusion
$presence of smile=>incorrect

Chapter 11: Implied Distributions & Static Replication

-implied distributions from stateful security
-Breeden-Litzenberger
-static replication of fixed expiry implied distributions
-BSM risk neutral distribution.



$euro price calculation of IV dist.
$butterfly spreads beget implied density
$exotic ~= portfolio zero coupon bond, a forward, euro-option portfolio



Chapter 12:

$dynanmic replication expenses
$weak static replication better
$weights depend on model
$portfolio unwound with option
$there is no unique static hedge

1. replicate security
2. BSM impractical
3. IV hedging strict; future Real Vol. is "flighty"
4. BSM unrealistic
5. strong replication of euro options

-weak static replication
-insights to barrier options
-another approach  : static replication up and out call
-Phi((log(B/S)+0.5*T*sigma**2)/(sigma*sqrt(T))) - alpha * Phi((log(S/B)+0.5*T*sigma**2)/(sigma*sqrt(T))) = 0


Chapter 13:


Chapter 14:


Chapter 15:

-Dupire's Equation: p(S,t,K,T)=e**(r*(T-r*t))*der(der(C'(K)))/der(der(K**2))
-Binomial Derivation
-Formal Dupire
-Local vs. Implied

$Dupire Equation sigma(K,T) ~= local volatility from T,K
$infinity spread, calendar spread
$one calculates local from implied

Chapter 16:


