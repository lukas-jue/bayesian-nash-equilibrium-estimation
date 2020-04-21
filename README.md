# Bayesian Beer Market Estimation: Simulating Nash Equilibrium Market Outcomes with Bayesian Analysis of Choice-Based Conjoint Data

## About the Paper
This research paper was written in summer 2019 within the Master's course *Customer Satisfaction and Consumer Choice*
taught by Prof. Thomas Otter at Goethe University Frankfurt. Read the full paper here: 

[Bayesian Beer Market Estimation: Simulating Nash Equilibrium Market Outcomes with Bayesian Analysis of Choice-Based Conjoint Data](cscc-paper.pdf)

## Summary and Findings

Which beer would Thomas Bayes, the famous philosopher and statistician that first
described Bayes’ Theorem (Bayes 1763) prefer? Though a particular preference by
Bayes for a certain product cannot be inferred and this question remains unanswered
by the present study, modern Bayesian methods provide a sophisticated way to estimate
today’s customers’ individual preferences based on their choices. This paper
uses Bayesian methods applied on choice-based conjoint (CBC) data to simulate Nash
equilibrium market outcomes in the beer market.

Historically, marketing research has heavily relied on Conjoint Analysis as a tool to
measure consumers’ preferences by asking them to choose between different products
that imply trade-offs (Green & Srinivasan 1990). This is a method to derive consumers’
preferences in a more credible way than to ask them which brand or feature they prefer,
since this often yields trivial results such as preferring the cheap vs. the expensive 
good or valuing the better quality good more than the low quality product.
Choice-based conjoint data enables researchers
to calculate counterfactual scenarios, such as what happens to a company’s market
share if a competitor changes its price (Huber et al. 2001). To analyze choice-based
conjoint data, market research has focused on the Multinomial Logit (MNL) Model.
Unfortunately, the MNL model is based on two strong and unrealistic assumptions
(Elrod et al. 1992). First, choices should be independent of irrelevant alternatives
(IIA). This means that consumer’s choices are not influenced by the presence or absence
of another, supposedly irrelevant other choice option. However, numerous examples
have been constructed to easily show that this assumption is often violated, most
famously the blue and red bus example by McFadden (1973). Especially for substitute
products, this assumtion therefore does not hold. Modeling very similar choices with
a traditional MNL model is hence not desirable. The second strong assumption that
is required for MNL estimation is homogeneity in preferences across consumers. This
implies that consumer’s preferences — expressed by the beta coefficients — are identical
for all consumers, which does not hold in reality. Literature has acknowledged those
violations and proposed the heterogeneous MNL, a more flexible model that relaxes
the IIA assumption and allows for differences in preferences by modeling individual
MNL models for every single customer (Steckel & Vanhonacker 1988).

To sum it up, the analytical model implemented in this study addresses
three serious shortcomings of most common methods to conduct a market simulation
and derive profit-maximizing prices. It relaxes the IIA assumption, allows for heterogeneous
individual-level consumer preferences, and infers unobserved budgets. Those
three model specifications are believed to yield more realistic and less biased estimates
(Chandukala et al. 2008, Pachali et al. 2017).
