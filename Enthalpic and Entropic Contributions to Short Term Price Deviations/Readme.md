__"Does the Stratergy "Fly under the Radar" of Institutional Money Managers?" - Ernie Chan__


__Probably nowhere near correct or rigourous, just got bored__


# Entropy correlated share

# prices

### Information theory based approach for share correlations


## Background on share fluctuations


● Current belief is that instantaneous fluctuations of shares are random
● Analysis of short scale (tick-minute) variations across market data
confirms this
● Share price indicators currently require a lot of information to make
accurate predictions, all over longer time periods, in the t<1min regime
● Current models use by analysts treat fluctuations as a random geometric
brownian walk using piecewise correlations to make predictions1, (e)
● Another assumption is that price deviations of different shares are
random at t>1min
●


1) excluding market specific temporal effects


## Assumptions underlying share price


● Too many social and human factors make reflected price uncorrilated
● Investor decisions are too influenced by human factors
● Objective measures are used in algorithmic trading, their assumptions can be summerised
as:
  ○ Information at time t is uniform.
  ○ Patterns between in small scale is unimportant because a) empirical analysis shows this is random, b)
  computationally infeasible to demonstrate a specific correlation.
  ○ There is no process in a market, therefore “ There is no set of work activities that deterministically or probabilistically
  generates the output data. Financial data are a byproduct or epiphenomenon of human and social
  developments—management decisions, economic policies, and changing perceptions of value and potential future
  payoffs.”
  ○ When there is small scale correlation, it is due to human factors, therefore, despite being correlated, you
  cannot make meaningful, or accurate predictions for time t, in the future. So you are unable to generate a
  machine with stable outputs.
  ○ “The inputs into financial systems (i.e., financial price data) are driven by human and
  societal decisions and, therefore, are random and cannot be stable.”
● https://www.tandfonline.com/doi/full/10.1080/15427560.2012.


## A potential flaw

#### ● We will try to find an exception to the above assumptions, in particular the

#### first. That information to an algorithm or trader (trading entity) at time t uniform

#### across all trading entities.

#### ● To do this we need a system of linked shares.

#### ● A predictable occurrence causes a gap of information between information

#### between a

#### ● We construct a model of a duo-oply of a specific market. Where company a,

#### occupies a% of the market and b occupies (100-a)% of the market.

#### ● Financial inputs lead to proportional growth, in both and b, but otherwise

#### maintain equal proportional market share.


## Entropic, and enthalpic approach to information

#### ● In information theory, there is an associated energy cost to increase your

#### precision in defining your set of microstates.

#### ● Therefore if we can demonstrate a specific energy debt at time t between

#### trading entities for a and b, (A,B), information for one set of trading entities

#### would be greater than the other.

#### ● For instance if net power consumption of A decreases, the energy and

#### information available for B will be greater than A, proportionally to a time delay

#### t’.

#### ● This allows B, to have more information the traded commodity and market.


## Patterns associated with extra information


● As in our criteria, we have constructed a set where the market share, ergo value of a is proportional to b
● Therefore if A has a period of more information about the market, B will be able to act on it. So I predict during this energy
lapse, B have information about a, therefore can more easily predict the state of their shared market.
● I predict that b’s share price will have a time delayed correlation to a


We now need to find a potential situation that fits our constructed set. Information required to construct this will
include:


● Historic market share of a,b
● Definable energy debt of a at defined time t, of t-delay ∈ t’
● If there is a predictable amount energy debt, we can then define t’ as a period of defined correlation.
● We will construct a t’’ where t’ ∈ t’’, where there is energy debt but it is less well defined
● We expect to see correlations between a, b in period t ∈ t’’, where t /∈ t’. The assumption is not necessary to
demonstrate the above but will reinforce the reliability of our theory.
● This does not mean that A, B define the value of a,b, however B, knows more about a, so for instance if a’s value goes up before market
close, B could estimate that the value of their shared market has increased, therefore the perceived value of b is higher.


## Constructing an ideal energy scenario for A,B


Energy loss:


● If we have a t’’ where |A|t∈t’’ | < | A|t /∈ (∀t∩t’’)| there will be an energy loss due to decrease in
size.
● A loss in computation for A
● Another energy expenditure for A

Could this situation occur during market close of a|(b=open for t>>t’)?, this is hard to prove analytically but
we should see empirical data. As this should be a stable, common occurrence, we should have a
consistent value for t-delay. An potential situation:

During extended hours is trading volume for a < a|(a=open), this is easier to show, but this doesn’t
necessarily show the above, the converse is necessary. A decrease in A means less trading volume, given
that the remaining A do not proportionally increase trading volume


## Indicators and causes for energy scenario

Could this situation occur during market close of a|(b=open for t>>t’)?, this is hard to prove
analytically but we should see empirical data. As this should be a stable, common occurrence, we
should have a consistent value for t-delay.

Indicators:


● Consistent t-delay for t ∈ t’

##### ● During t, where, t /∈ (∀t∩t’’) is there correlation between shares for a,b, with an effect of b


caused by a. For example:
○ During extended hours is trading volume for a < a|(a=open), this is easier to show, but
this doesn’t necessarily show the above, the converse is necessary. A decrease in A
means less trading volume, given that the remaining A do not proportionally increase
trading volume.
● Can we find a scenario where there is an energy or information delay, and show correlation
in perceived value, therefore share price. This is not necessarily consistent or predictable


## Constructing the market for a,b


● Where both companies income is based off the same source
● Social and legal and financial influences lead to lack of competition so are stable in market
position.
● From this both a,b are in the same industry and have a joint source of income.
● Most companies achieve profits from selling a product a to consumers, we need a situation
where there is only one customer, so we can rule out individual humans as this will be
based off energy requirements of the customer, rather than trading entities.
● Further a,b cannot have a large customer base so input demand is stable. So value is not
influenced by customer behavior. This is an important assumption as we are trying to define
a trading protocol that does not require much information.
● A, B can be modelled as distinct entities.
● Shareholder decisions do not affect short term patterns.


## Potential situations

#### ● Subsidiaries or dependents, c, of larger organisations, C, in a fixed supply

#### chain. So demand is defined by the next order body. They also need to have

#### their value tied exclusive to body C.

#### ● The defence industry is such, where they work almost exclusively with

#### government contracts. Political influence, joint products and systems, single

#### point of demand implies that they would be heavily correlated.

#### ● Ideally we want to demonstrate that this happens elsewhere to verify the

#### underlying theory however this isn’t essential to construct an algorithm.


## Factors we need to demonstrate and how:

Catagorised by theoretical or actionable significance


Theoretical Actionable


a,b values are proportional: Historic value, market share, proportion of activity
Predictions are defined at a t-delay: Given a suspect incident during t’, that the strongest indicator is consistently share price a at time t-delay ago. Compute correlation from all times in t-delay. Over time
t, would demonstrate that this is not a random event to reinforce the theory but not necessary to produce an accurate prediction. Our underlying theory may be wrong but if we have a consistent
prediction algorithm this hardly matters


A correlation during t’’ Prediction value p is statistically significant


Other energy events influence value a, b


Fluctuations in value a,b are random even during correlated periods. That is, a gives b a time delay but variation in a is random.


