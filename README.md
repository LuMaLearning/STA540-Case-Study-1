# STA540 Case 1
Luxman Maheswaran

## Study Overview

Various platforms have been used to target individuals at risk of
infections. It is not clear which platform is more effective at reaching
out to promote Human Immunodeficiency Virus (HIV) self-testing. The
following work attempts to reproduce the findings of Stafylis et. al. in
their paper, *Relative Effectiveness of Social Media, Dating Apps, and
Information Search Sites in Promoting HIV Self-testing: Observational
Cohort Study*.

## Objectives

The primary objective of this study is to compare the effectiveness of
different web platforms in promoting self-testing of HIV among men who
have sex with men (MSM). The three main platforms are social media,
dating appslications, and informational sites. This study will also
examine associations in participants’ social media use, attitudes on HIV
testing, perceptions of sexual risk behavior, medical mistrust, and
stigma impact HIV testing and PrEP uptake.

### Primary Analysis

The primary analysis will look at order rate as an outcome. The order
rate is defined by the number of tests ordered divided by the duration
of the period or wave. The order rate for each site was calculated in
<a href="#tbl-primary" class="quarto-xref">Table 2</a>. There are two
sites for each platform.

In addition, a Poisson model was used to model site specific rates.

$$ log(o_{ij}) =log(t_i)+ \alpha+\beta_i+\gamma_{ij}+\beta*\gamma_{ij}  $$
where $o_{ij}$ is the order rate for a site, $t_i$ is the log duration
or offset $\beta_i$ is the wave effect $\gamma_{j}$ is the site effect
$\beta*\gamma_{ij}$ is the interaction effect

### Secondary Analysis

## Inclusion Criteria

Individuals must meet all of the inclusion criteria in order to be
eligible to participate in the study. Individuals participating in the
study must:

1.  Have clicked on one of the study-specific advertisements posted on
    the platforms/ websites described in this protocol;
2.  Have been biologically born male (cis-gender man), per participant
    self-report;
3.  Report condomless anal intercourse and more than one male sex
    partner in the 90 days prior to the date of the screening
    questionnaire;
4.  Be between the ages of 18-30 years old, inclusive;
5.  Self-identify as Latino and/or Black/African American;
6.  Not currently on PrEP and haven’t taken PrEP in the last six months
    prior to the date of the screening questionnaire (per participant
    self-report);
7.  Have not tested for HIV in the last 3 months prior to the date of
    the screening questionnaire (per participant self-report);
8.  Have a Facebook account (for identity validation to reduce duplicate
    attempts at enrollment); and
9.  Be willing to provide contact information (phone number, email) to
    the study team.

## Exclusion Criteria

Individuals must meet all of the inclusion criteria in order to be
eligible to participate in the study. Individuals participating in the
study must: 1. Have clicked on one of the study-specific advertisements
posted on the platforms/ websites described in this protocol; 2. Have
been biologically born male (cis-gender man), per participant
self-report; 3. Report condomless anal intercourse and more than one
male sex partner in the 90 days prior to the date of the screening
questionnaire; 4. Be between the ages of 18-30 years old, inclusive; 5.
Self-identify as Latino and/or Black/African American; 6. Not currently
on PrEP and haven’t taken PrEP in the last six months prior to the date
of the screening questionnaire (per participant self-report); 7. Have
not tested for HIV in the last 3 months prior to the date of the
screening questionnaire (per participant self-report); 8. Have a
Facebook account (for identity validation to reduce duplicate attempts
at enrollment); and 9. Be willing to provide contact information (phone
number, email) to the study team.

## Table 1

After applying the inclusion and exclusion criteria listed above, there
are still a few participants who do not have a primary outcome that need
to be excluded. The resulting data has 254 participants. Replicating
<a href="#tbl-table1" class="quarto-xref">Table 1</a> leads to the
following results.

The table closely matches the original paper’s, with a few minor
differences. The quartile for age, other ethnicity, and few differences
in reasons for not gettting HIV testing are slightly off.

<div id="tbl-table1">

Table 1: Table 1

<div class="cell-output-display">

| **Characteristic** | **Value** |
|:---|:--:|
| **Age in years, median (IQR)** |  |
| Median (Q1-Q3) | 25.0 (21.0-27.0) |
| **Ethnicity** |  |
| Hispanic/Latinx | 66 (26%) |
| Non-Hispanic | 188 (74%) |
| **Race** |  |
| American Indian or Alaskan Native | 1 (0.4%) |
| Black or African American | 196 (77%) |
| Multiracial | 11 (4.3%) |
| Other | 18 (7.1%) |
| White | 28 (11%) |
| **History of PrEP uptake** |  |
| In the past 6 months | 22 (8.7%) |
| Never taken PrEP | 232 (91%) |
| **Number of male sex partners in the past 90 days, median (IQR)** |  |
| Median (Q1-Q3) | 4.0 (3.0-6.0) |
| **Condom use** |  |
| Never | 36 (14%) |
| Sometimes | 108 (43%) |
| About half the time | 37 (15%) |
| Most of the time | 68 (27%) |
| Always | 5 (2.0%) |
| **Condomless receptive anal sex in the past 90 days** | 210 (83%) |
| **Ever tested for HIV during lifetime** | 191 (75%) |
| **Months since last HIV test** | 11 (6-21) |
| **If not tested for HIV** | 63 (25%) |
| **Main reasons cited for not getting tested** |  |
| Afraid of testing HIV-positive | 25 (39%) |
| Did not want to think about HIV/HIV-positive | 9 (14%) |
| Dislike for needles | 5 (7.8%) |
| Other reasons | 4 (6.3%) |
| Unable to trust that the results will be confidential | 3 (4.7%) |
| Unaware of where to get tested | 7 (11%) |
| Unlikely to be exposed to HIV | 8 (13%) |
| Worried about names being reported if positive | 3 (4.7%) |

</div>

</div>

## Primary Outcome

The original paper uses Table 2 to summarize their primary outcome
across different sites. The
<a href="#tbl-primary" class="quarto-xref">Table 2</a> below has
identical information with the exception of 1 Google order. The paper
had mentioned that there were no orders in Wave 3, however, in the
dataset, there is one order under Yahoo (Wave 3). Mislabeled data could
explain the discrepancy.

As expected, since the tables closely match, the same conclusions from
the primary analysis of the original paper still hold. Dating apps
performed the best followed by social media and info sites.

<div id="tbl-primary">

Table 2: Table 2

<div class="cell-output-display">

</div>

</div>

### Poisson Regression

The Poisson model specified above leads to the following cell-specific
rates in the table below. These rate closely match the order rates in
<a href="#tbl-primary" class="quarto-xref">Table 2</a>, indicating good
model fit.

The paper also did pair-wise testing within wave by platform with a
Hochberg correction. Performing the same analysis shows that none of the
Wave 1 platforms were significantly different at a 5% significance
level. In Wave 2, each platform was statistically significant at the
same 5% level.

When checking the model for overdispersion, the residual deviance is
approximately equal to the residual degrees of freedom, which means that
there is no significant over/underdispersion.

## Secondary Outcomes

Overall, the secondary analysis conclusions match the original paper’s
assertions. The resulting p-values are very similar, if not the same.
The only significant (5% level) difference found between those that did
and did not order a test kit was opinions on HIV stigma. Substance abuse
was high among all participants (see
<a href="#tbl-a" class="quarto-xref">Table 3</a>). Even though medical
mistrust was high among participants, it did not seem to impact test kit
ordering (see <a href="#tbl-f" class="quarto-xref">Table 4</a>).

#### a. Tobacco, alcohol, prescription medications, and other substance use

<div id="tbl-a">

Table 3

<div class="cell-output-display">

| **Characteristic** | **No**<br>N = 77 | **Yes**<br>N = 177 | **p-value** |
|:---|:--:|:--:|:--:|
| **alcohol** |  |  | 0.3 |
| None | 16 (21%) | 52 (29%) |  |
| Problem Use | 21 (27%) | 46 (26%) |  |
| High Risk Substance Use | 40 (52%) | 79 (45%) |  |
| **cannabis** |  |  | 0.10 |
| None | 32 (42%) | 89 (50%) |  |
| Problem Use | 12 (16%) | 37 (21%) |  |
| High Risk Substance Use | 33 (43%) | 51 (29%) |  |
| **stimulants** |  |  | 0.3 |
| None | 69 (90%) | 165 (93%) |  |
| Problem Use/High Risk Substance Use | 8 (10%) | 12 (6.8%) |  |
| **opioids** |  |  | \>0.9 |
| None | 75 (97%) | 173 (98%) |  |
| Problem Use/High Risk Substance Use | 2 (2.6%) | 4 (2.3%) |  |
| **sedatives** |  |  | 0.8 |
| None | 72 (94%) | 168 (95%) |  |
| Problem Use/High Risk Substance Use | 5 (6.5%) | 9 (5.1%) |  |
| **prescription stimulants** |  |  | 0.7 |
| None | 74 (96%) | 172 (97%) |  |
| Problem Use/High Risk Substance Use | 3 (3.9%) | 5 (2.8%) |  |

</div>

</div>

#### b. Stage of Health Behavior Change

| **Characteristic**         | **No**<br>N = 77 | **Yes**<br>N = 177 | **p-value** |
|:---------------------------|:----------------:|:------------------:|:-----------:|
| **Health Behavior Change** |                  |                    |    0.21     |
| Precontemplation           |     2 (2.6%)     |      7 (4.0%)      |             |
| Contemplation              |     8 (10%)      |      32 (18%)      |             |
| Determination              |     49 (64%)     |      86 (49%)      |             |
| Action                     |     12 (16%)     |      40 (23%)      |             |
| Maintenance                |     6 (7.8%)     |     12 (6.8%)      |             |

#### c. Attitudes toward human immunodeficiency virus (HIV) testing

| **Characteristic** | **No**<br>N = 77 | **Yes**<br>N = 177 | **p-value** |
|:---|:--:|:--:|:--:|
| **Getting tested for HIV helps people feel better** |  |  | 0.16 |
| Agree | 70 (91%) | 169 (95%) |  |
| Disagree | 7 (9.1%) | 8 (4.5%) |  |
| **Getting tested for HIV helps people from getting HIV** |  |  | 0.72 |
| Agree | 62 (82%) | 148 (84%) |  |
| Disagree | 14 (18%) | 29 (16%) |  |
| Unknown | 1 | 0 |  |
| **People in my life would leave if I had HIV** |  |  | 0.049 |
| Agree | 37 (48%) | 60 (34%) |  |
| Disagree | 40 (52%) | 115 (66%) |  |
| Unknown | 0 | 2 |  |
| **People who tested positive for HIV should hide it from others** |  |  | 0.82 |
| Agree | 9 (12%) | 18 (10%) |  |
| Disagree | 68 (88%) | 159 (90%) |  |
| **I would rather not know if I have HIV** |  |  | 0.46 |
| Agree | 15 (19%) | 27 (15%) |  |
| Disagree | 62 (81%) | 150 (85%) |  |

#### d. Attitudes toward human immunodeficiency virus (HIV) treatment

| **Characteristic** | **No** N = 77 | **Yes** N = 177 | **p-value** |
|:---|:--:|:--:|:--:|
| **I am less threatened by the idea of being HIV positive than I used to be** | 3.84 (2.16) | 4.09 (1.98) | 0.41 |
| **I am less worried about HIV infection than I used to be** | 3.52 (1.84) | 3.78 (1.99) | 0.34 |
| **I think HIV/AIDS is less of a problem than it used to be** | 3.62 (2.11) | 3.86 (2.11) | 0.45 |
| **I think HIV/AIDS is a less serious threat than it used to be because of new HIV/AIDS treatments** | 3.79 (2.11) | 4.19 (2.03) | 0.21 |
| **I am much less concerned about becoming HIV positive myself because of new HIV/AIDS treatments** | 2.98 (1.89) | 3.37 (2.04) | 0.27 |
| **I think that condom use during sex is less necessary now that new HIV/AIDS treatments are available** | 2.23 (1.53) | 2.41 (1.77) | 0.88 |
| **I think that someone who is HIV positive now needs to care less about condom use** | 2.49 (2.08) | 1.92 (1.66) | 0.059 |
| **I think that the need for condom use is less than it used to be, because you can always start new treatments** | 2.46 (2.02) | 2.50 (1.86) | 0.76 |
| **I think that someone who is HIV positive and uses new HIV/AIDS treatments can be cured** | 3.64 (2.16) | 3.25 (1.95) | 0.21 |
| **I think that new HIV/AIDS treatments can eradicate the virus from your body** | 3.80 (2.08) | 3.09 (1.94) | 0.031 |

#### e. Human immunodeficiency virus (HIV)-related stigma among study participants

| **Characteristic** | **No**<br>N = 77 | **Yes**<br>N = 177 | **p-value** |
|:---|:--:|:--:|:--:|
| **I feel afraid of people living with HIV/AIDS** |  |  | 0.56 |
| Strongly agree | 7 (9.1%) | 11 (6.2%) |  |
| Agree | 2 (2.6%) | 9 (5.1%) |  |
| Somewhat agree | 9 (12%) | 21 (12%) |  |
| Neither agree nor disagree | 9 (12%) | 20 (11%) |  |
| Somewhat disagree | 6 (7.8%) | 11 (6.2%) |  |
| Disagree | 17 (22%) | 33 (19%) |  |
| Strongly disagree | 27 (35%) | 72 (41%) |  |
| **I could not be friends with someone who has HIV/AIDS** |  |  | 0.040 |
| Strongly agree | 4 (5.2%) | 1 (0.6%) |  |
| Agree | 0 (0%) | 1 (0.6%) |  |
| Somewhat agree | 1 (1.3%) | 3 (1.7%) |  |
| Neither agree nor disagree | 6 (7.8%) | 9 (5.1%) |  |
| Somewhat disagree | 1 (1.3%) | 7 (4.0%) |  |
| Disagree | 19 (25%) | 27 (15%) |  |
| Strongly disagree | 46 (60%) | 129 (73%) |  |
| **People who get HIV/AIDS through sex or drug use got what they deserve** |  |  | 0.39 |
| Strongly agree | 0 (0%) | 2 (1.1%) |  |
| Agree | 1 (1.3%) | 2 (1.1%) |  |
| Somewhat agree | 2 (2.6%) | 4 (2.3%) |  |
| Neither agree nor disagree | 7 (9.1%) | 8 (4.5%) |  |
| Somewhat disagree | 2 (2.6%) | 6 (3.4%) |  |
| Disagree | 12 (16%) | 24 (14%) |  |
| Strongly disagree | 53 (69%) | 131 (74%) |  |
| **I feel anger toward people with HIV/AIDS** |  |  | 0.25 |
| Strongly agree | 0 (0%) | 1 (0.6%) |  |
| Agree | 0 (0%) | 0 (0%) |  |
| Somewhat agree | 0 (0%) | 0 (0%) |  |
| Neither agree nor disagree | 5 (6.5%) | 11 (6.2%) |  |
| Somewhat disagree | 0 (0%) | 3 (1.7%) |  |
| Disagree | 16 (21%) | 20 (11%) |  |
| Strongly disagree | 56 (73%) | 142 (80%) |  |

#### f. Medical mistrust

<div id="tbl-f">

Table 4

<div class="cell-output-display">

| **Characteristic** | **No**<br>N = 77 | **Yes**<br>N = 177 | **p-value** |
|:---|:--:|:--:|:--:|
| **You’d better be cautious when dealing with health care organizations** |  |  | 0.81 |
| Strongly agree | 17 (22%) | 37 (21%) |  |
| Agree | 32 (42%) | 67 (38%) |  |
| Disagree | 14 (18%) | 42 (24%) |  |
| Strongly disagree | 13 (17%) | 31 (18%) |  |
| Unknown | 1 | 0 |  |
| **Patients have sometimes been deceived or misled by health care organizations** |  |  | 0.38 |
| Strongly agree | 11 (14%) | 32 (18%) |  |
| Agree | 34 (44%) | 84 (48%) |  |
| Disagree | 22 (29%) | 33 (19%) |  |
| Strongly disagree | 10 (13%) | 27 (15%) |  |
| Unknown | 0 | 1 |  |
| **When health care organizations make mistakes they usually cover it up** |  |  | 0.026 |
| Strongly agree | 10 (13%) | 29 (17%) |  |
| Agree | 29 (38%) | 84 (48%) |  |
| Disagree | 30 (39%) | 36 (21%) |  |
| Strongly disagree | 7 (9.2%) | 25 (14%) |  |
| Unknown | 1 | 3 |  |
| **Health care organizations have sometimes done harmful experiments on patients without their knowledge** |  |  | 0.55 |
| Strongly agree | 14 (18%) | 30 (17%) |  |
| Agree | 25 (32%) | 73 (41%) |  |
| Disagree | 26 (34%) | 52 (30%) |  |
| Strongly disagree | 12 (16%) | 21 (12%) |  |
| Unknown | 0 | 1 |  |
| **Health care organizations don’t always keep your information totally private** |  |  | 0.66 |
| Strongly agree | 11 (14%) | 37 (21%) |  |
| Agree | 29 (38%) | 64 (37%) |  |
| Disagree | 23 (30%) | 47 (27%) |  |
| Strongly disagree | 13 (17%) | 27 (15%) |  |
| Unknown | 1 | 2 |  |
| **Sometimes I wonder if health care organizations really know what they are doing** |  |  | 0.90 |
| Strongly agree | 9 (12%) | 23 (13%) |  |
| Agree | 28 (36%) | 66 (38%) |  |
| Disagree | 30 (39%) | 60 (34%) |  |
| Strongly disagree | 10 (13%) | 27 (15%) |  |
| Unknown | 0 | 1 |  |
| **Mistakes are common in health care organizations** |  |  | 0.93 |
| Strongly agree | 8 (11%) | 21 (12%) |  |
| Agree | 36 (48%) | 89 (51%) |  |
| Disagree | 23 (31%) | 47 (27%) |  |
| Strongly disagree | 8 (11%) | 19 (11%) |  |
| Unknown | 2 | 1 |  |

</div>

</div>

## Reflection

Overall, the study was for the most part able to be replicated. There
were a few minor deviances, but none that would alter the study’s
conclusions or even magnitude of significance levels. Overall, it would
be beneficial if they provided public code to double check if there are
any differences in procedures. They also used SAS, which may have
different defaults, that could lead to minor difference in Poisson model
calculation.

## References

1.  Stafylis C, Vavala G, Wang Q, McLeman B, Lemley SM, Young SD, Xie H,
    Matthews AG, Oden N, Revoredo L, Shmueli-Blumberg D, Hichborn EG,
    McKelle E, Moran LM, Jacobs P, Marsch LA, Klausner JD. Relative
    Effectiveness of Social Media, Dating Apps, and Information Search
    Sites in Promoting HIV Self-testing: Observational Cohort Study.
    JMIR Form Res. 2022 Sep 23;6(9):e35648. doi: 10.2196/35648. PMID:
    36149729; PMCID: PMC9591705.

2.  National Institute on Drug Abuse. (2025, April 9). *NIDA-CTN-0083:
    Using social media to deliver HIV self-testing kits and link to
    online PrEP services*. NIDA Data Share.
    https://datashare.nida.nih.gov/study/nida-ctn-0083

3.  Lenth, R., & Piaskowski, J. (2025). *emmeans: Estimated marginal
    means, aka least-squares means* (R package version 2.0.1).
    https://rvlenth.github.io/emmeans/
    :contentReference<span index="0">oaicite:0</span>

4.  OpenAI. (2026). *ChatGPT* (GPT-5.2) \[Large language model\].
    https://chat.openai.com. Used for table formatting code
