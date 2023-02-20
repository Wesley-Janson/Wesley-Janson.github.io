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

## Journal Publications

<a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/jmcb.12968" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><strong><span style="text-decoration: underline;">Out of Bounds: Do SPF Respondents Have Anchored Inflation Expectations?</span></strong></a> (forthcoming, with <a href="https://carolabinder.sites.haverford.edu/" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Carola Binder</span></a> and <a href="https://www.clevelandfed.org/research/economists/verbrugge-randal-j" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Randal J. Verbrugge</span></a>) *Journal of Money Credit & Banking*

## Policy Papers

<a href="https://www.clevelandfed.org/publications/economic-commentary/2020/ec-202027-forward-guidance-during-the-pandemic" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><strong><span style="text-decoration: underline;">Forward Guidance during the Pandemic: Has It Changed the Public’s Expectations?</span></strong></a> (2020, with <a href="https://sites.google.com/site/chengchengjia" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Chengcheng Jia</span></a>) *Federal Reserve Bank of Cleveland Economic Commentary*

<a href="https://www.clevelandfed.org/publications/economic-commentary/2020/ec-202015-info-effect-monetary-policy" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><strong><span style="text-decoration: underline;">The Information Effect of Monetary Policy: Self-Defeating or Optimal?</span></strong></a> (2020, with <a href="https://sites.google.com/site/chengchengjia" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Chengcheng Jia</span></a>) *Federal Reserve Bank of Cleveland Economic Commentary*

<a href="https://www.clevelandfed.org/publications/economic-commentary/2020/ec-202006-cpi-pcepi-inflation-differential" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><strong><span style="text-decoration: underline;">The CPI–PCEPI Inflation Differential: Causes and Prospects</span></strong></a> (2020, with <a href="https://carolabinder.sites.haverford.edu/" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Carola Binder</span></a> and <a href="https://www.clevelandfed.org/research/economists/verbrugge-randal-j" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Randal J. Verbrugge</span></a>) *Federal Reserve Bank of Cleveland Economic Commentary*

<a href="https://cla.umn.edu/heller-hurwicz/news/policy-brief-risk-taking-public-pension-funds" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><strong><span style="text-decoration: underline;">Risk-taking by Public Pension Funds.</span></strong></a> (2018, with <a href="https://navegastrategies.com/about/" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Kurt Winkelmann</span></a>, <a href="https://sites.google.com/a/umn.edu/jordan-pandolfo/" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Jordan Pandolfo</span></a>, and <a href="https://economics.wustl.edu/people/matthew-murphy" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Matthew Murphy</span></a>) *Heller-Hurwicz Economics Institute Policy Brief*

## Works In Progress

<a href="https://www.clevelandfed.org/publications/working-paper/2021/wp-2022r-late-payment-fees-nonpayment-in-rental-markets" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><strong><span style="text-decoration: underline;">Late Payment Fees and Nonpayment in Rental Markets, and Implications for Inflation Measurement: Theoretical Considerations and Evidence</span></strong></a> (Under Review, with <a href="https://www.clevelandfed.org/research/economists/verbrugge-randal-j" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Randal J. Verbrugge</span></a>) <br>
**Abstract:** Statistical agencies track rental expenditures for use in the national accounts and in consumer price indexes (CPIs). As such, statistical agencies should include late payment fees and nonpayment in rent. In the US context, late payment fees are excluded from the CPI. Ostensibly, nonpayment of rent is included in the US CPI; but its treatment is deficient, and we demonstrate that small variations in nonpayment could lead to large swings in shelter inflation, and might have played a role in the 2009 measured shelter inflation collapse. They didn’t: while the national nonpayment incidence is 2-3 percent, in the 1 million plus rent observations in BLS rent microdata from 2000-2016, no nonpayment is recorded. A back-of-the-envelope calculation suggests that, assuming nonpayment undermeasurement continued after 2016, CPI shelter inflation may have been overestimated by about 1 percentage point per month (annualized) in 2020. Late fees and nonpayment are difficult to measure in real time. We offer implementation suggestions that are consistent with CPI procedures.

**Improving Inference via Data-Based Identification of Unobserved Variables and Unusual Data Points** (In Progress, with <a href="https://www.clevelandfed.org/research/economists/verbrugge-randal-j" data-sf-ec-immutable="" data-sf-marked="" target="_blank" rel="noopener"><span style="text-decoration: underline;">Randal J. Verbrugge</span></a>) <br>
**Abstract:** Omitted variable bias is well-known problem that, if the variable is not present in a data set, seems impossible to discover. But two other problems are equally damaging and underappreciated: most classical estimators are highly fragile (their asymptotic distributions diverge with modest contamination) and have low breakdown points (the estimate can be totally spoiled by a miniscule percentage of unusual data). None of these threats disappears asymptotically; none is easy to detect in large, multivariate data; all of them compromise inference. Herein we show how, in some cases, one may use the data at hand (only) to detect the presence of an omitted variable: by locating sets of points that appear to come from a different data-generating mechanism. Their detection can lead to deep insights into the data-generating mechanism. We provide some salient examples.
