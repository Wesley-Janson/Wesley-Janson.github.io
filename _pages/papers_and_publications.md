---
layout: archive
title: "Papers and Publications"
permalink: /papers_and_publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Selected Publications

**[Out of Bounds: Do SPF Respondents Have Anchored Inflation Expectations?](https://onlinelibrary.wiley.com/doi/abs/10.1111/jmcb.12968)** (forthcoming, with [Carola Binder](https://carolabinder.sites.haverford.edu/) and [Randal J. Verbrugge](https://www.clevelandfed.org/research/economists/verbrugge-randal-j)) *Journal of Money Credit & Banking*

**[Forward Guidance during the Pandemic: Has It Changed the Public’s Expectations?](https://www.clevelandfed.org/publications/economic-commentary/2020/ec-202027-forward-guidance-during-the-pandemic)** (2020, with [Chengcheng Jia](https://sites.google.com/site/chengchengjia)) *Federal Reserve Bank of Cleveland Economic Commentary*

**[The Information Effect of Monetary Policy: Self-Defeating or Optimal?](https://www.clevelandfed.org/publications/economic-commentary/2020/ec-202015-info-effect-monetary-policy)** (2020, with [Chengcheng Jia](https://sites.google.com/site/chengchengjia)) *Federal Reserve Bank of Cleveland Economic Commentary*

**[The CPI–PCEPI Inflation Differential: Causes and Prospects](https://www.clevelandfed.org/publications/economic-commentary/2020/ec-202006-cpi-pcepi-inflation-differential)** (2020, with [Carola Binder](https://carolabinder.sites.haverford.edu/) and [Randal J. Verbrugge](https://www.clevelandfed.org/research/economists/verbrugge-randal-j)) *Federal Reserve Bank of Cleveland Economic Commentary*

**[Risk-taking by Public Pension Funds.](https://cla.umn.edu/heller-hurwicz/news/policy-brief-risk-taking-public-pension-funds)** (2018, with [Kurt Winkelmann](https://navegastrategies.com/about/), [Jordan Pandolfo](https://sites.google.com/a/umn.edu/jordan-pandolfo/), and [Matthew Murphy](https://economics.wustl.edu/people/matthew-murphy)) *Heller-Hurwicz Economics Institute Policy Brief*

## Work In Progress

**[Late Payment Fees and Nonpayment in Rental Markets, and Implications for Inflation Measurement: Theoretical Considerations and Evidence](https://www.clevelandfed.org/publications/working-paper/2021/wp-2022r-late-payment-fees-nonpayment-in-rental-markets)** (Under Review, with [Randal J. Verbrugge](https://www.clevelandfed.org/research/economists/verbrugge-randal-j)) <br>
**Abstract:** Statistical agencies track rental expenditures for use in the national accounts and in consumer price indexes (CPIs). As such, statistical agencies should include late payment fees and nonpayment in rent. In the US context, late payment fees are excluded from the CPI. Ostensibly, nonpayment of rent is included in the US CPI; but its treatment is deficient, and we demonstrate that small variations in nonpayment could lead to large swings in shelter inflation, and might have played a role in the 2009 measured shelter inflation collapse. They didn’t: while the national nonpayment incidence is 2-3 percent, in the 1 million plus rent observations in BLS rent microdata from 2000-2016, no nonpayment is recorded. A back-of-the-envelope calculation suggests that, assuming nonpayment undermeasurement continued after 2016, CPI shelter inflation may have been overestimated by about 1 percentage point per month (annualized) in 2020. Late fees and nonpayment are difficult to measure in real time. We offer implementation suggestions that are consistent with CPI procedures.

**Improving Inference via Data-Based Identification of Unobserved Variables and Unusual Data Points** (In Progress, with [Randal J. Verbrugge](https://www.clevelandfed.org/research/economists/verbrugge-randal-j)) <br>
**Abstract:** Omitted variable bias is well-known problem that, if the variable is not present in a data set, seems impossible to discover. But two other problems are equally damaging and underappreciated: most classical estimators are highly fragile (their asymptotic distributions diverge with modest contamination) and have low breakdown points (the estimate can be totally spoiled by a miniscule percentage of unusual data). None of these threats disappears asymptotically; none is easy to detect in large, multivariate data; all of them compromise inference. Herein we show how, in some cases, one may use the data at hand (only) to detect the presence of an omitted variable: by locating sets of points that appear to come from a different data-generating mechanism. Their detection can lead to deep insights into the data-generating mechanism. We provide some salient examples.
