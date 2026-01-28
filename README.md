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

<div id="tassrbtjzs" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#tassrbtjzs table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#tassrbtjzs thead, #tassrbtjzs tbody, #tassrbtjzs tfoot, #tassrbtjzs tr, #tassrbtjzs td, #tassrbtjzs th {
  border-style: none;
}
&#10;#tassrbtjzs p {
  margin: 0;
  padding: 0;
}
&#10;#tassrbtjzs .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 3px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 3px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#tassrbtjzs .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#tassrbtjzs .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#tassrbtjzs .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_bottom_border {
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_col_headings {
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#tassrbtjzs .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#tassrbtjzs .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#tassrbtjzs .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#tassrbtjzs .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#tassrbtjzs .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#tassrbtjzs .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#tassrbtjzs .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#tassrbtjzs .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#tassrbtjzs .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#tassrbtjzs .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#tassrbtjzs .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#tassrbtjzs .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#tassrbtjzs .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#tassrbtjzs .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#tassrbtjzs .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#tassrbtjzs .gt_first_summary_row {
  border-top-style: none;
  border-top-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#tassrbtjzs .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#tassrbtjzs .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: none;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: none;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#tassrbtjzs .gt_table_body {
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#tassrbtjzs .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#tassrbtjzs .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#tassrbtjzs .gt_left {
  text-align: left;
}
&#10;#tassrbtjzs .gt_center {
  text-align: center;
}
&#10;#tassrbtjzs .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#tassrbtjzs .gt_font_normal {
  font-weight: normal;
}
&#10;#tassrbtjzs .gt_font_bold {
  font-weight: bold;
}
&#10;#tassrbtjzs .gt_font_italic {
  font-style: italic;
}
&#10;#tassrbtjzs .gt_super {
  font-size: 65%;
}
&#10;#tassrbtjzs .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#tassrbtjzs .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#tassrbtjzs .gt_indent_1 {
  text-indent: 5px;
}
&#10;#tassrbtjzs .gt_indent_2 {
  text-indent: 10px;
}
&#10;#tassrbtjzs .gt_indent_3 {
  text-indent: 15px;
}
&#10;#tassrbtjzs .gt_indent_4 {
  text-indent: 20px;
}
&#10;#tassrbtjzs .gt_indent_5 {
  text-indent: 25px;
}
&#10;#tassrbtjzs .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#tassrbtjzs div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table do-not-create-environment cell"
data-quarto-postprocess="true" data-quarto-disable-processing="false"
data-quarto-bootstrap="false">
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="gt_col_headings">
<th id="a::stub" class="gt_col_heading gt_columns_bottom_border gt_left"
data-quarto-table-cell-role="th" scope="col">Type of platform</th>
<th id="Wave" class="gt_col_heading gt_columns_bottom_border gt_right"
data-quarto-table-cell-role="th" scope="col">Wave</th>
<th id="Number-of-days"
class="gt_col_heading gt_columns_bottom_border gt_right"
data-quarto-table-cell-role="th" scope="col">Number of days</th>
<th id="Number-of-test-kits-ordered"
class="gt_col_heading gt_columns_bottom_border gt_right"
data-quarto-table-cell-role="th" scope="col">Number of test kits
ordered</th>
<th id="Order-rate"
class="gt_col_heading gt_columns_bottom_border gt_right"
data-quarto-table-cell-role="th" scope="col">Order rate</th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr class="gt_group_heading_row">
<td colspan="5" id="Dating app" class="gt_group_heading"
data-quarto-table-cell-role="th" scope="colgroup">Dating app</td>
</tr>
<tr class="gt_row_group_first">
<td id="stub_1_1" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row">Grindr</td>
<td class="gt_row gt_right" headers="Dating app stub_1_1 Wave"><span
class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span> 1</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_1 Number of days">70</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_1 Number of test kits ordered">9</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_1 Order rate">0.13</td>
</tr>
<tr>
<td id="stub_1_2" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row">Jack'd</td>
<td class="gt_row gt_right" headers="Dating app stub_1_2 Wave">2</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_2 Number of days">38</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_2 Number of test kits ordered">126</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_2 Order rate">3.32</td>
</tr>
<tr>
<td id="stub_1_3" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row"><br />
</td>
<td class="gt_row gt_right" headers="Dating app stub_1_3 Wave"><br />
</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_3 Number of days">108</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_3 Number of test kits ordered">135</td>
<td class="gt_row gt_right"
headers="Dating app stub_1_3 Order rate">1.25</td>
</tr>
<tr class="gt_group_heading_row">
<td colspan="5" id="Info site" class="gt_group_heading"
data-quarto-table-cell-role="th" scope="colgroup">Info site</td>
</tr>
<tr class="gt_row_group_first">
<td id="stub_1_4" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row">Google</td>
<td class="gt_row gt_right" headers="Info site stub_1_4 Wave"><span
class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span> 1</td>
<td class="gt_row gt_right"
headers="Info site stub_1_4 Number of days">70</td>
<td class="gt_row gt_right"
headers="Info site stub_1_4 Number of test kits ordered">16</td>
<td class="gt_row gt_right"
headers="Info site stub_1_4 Order rate">0.23</td>
</tr>
<tr>
<td id="stub_1_5" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row">Bing</td>
<td class="gt_row gt_right" headers="Info site stub_1_5 Wave">2</td>
<td class="gt_row gt_right"
headers="Info site stub_1_5 Number of days">38</td>
<td class="gt_row gt_right"
headers="Info site stub_1_5 Number of test kits ordered">0</td>
<td class="gt_row gt_right"
headers="Info site stub_1_5 Order rate">0.00</td>
</tr>
<tr>
<td id="stub_1_6" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row"><br />
</td>
<td class="gt_row gt_right" headers="Info site stub_1_6 Wave"><br />
</td>
<td class="gt_row gt_right"
headers="Info site stub_1_6 Number of days">108</td>
<td class="gt_row gt_right"
headers="Info site stub_1_6 Number of test kits ordered">16</td>
<td class="gt_row gt_right"
headers="Info site stub_1_6 Order rate">0.15</td>
</tr>
<tr class="gt_group_heading_row">
<td colspan="5" id="Social media" class="gt_group_heading"
data-quarto-table-cell-role="th" scope="colgroup">Social media</td>
</tr>
<tr class="gt_row_group_first">
<td id="stub_1_7" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row">Facebook</td>
<td class="gt_row gt_right" headers="Social media stub_1_7 Wave"><span
class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span> 1</td>
<td class="gt_row gt_right"
headers="Social media stub_1_7 Number of days">70</td>
<td class="gt_row gt_right"
headers="Social media stub_1_7 Number of test kits ordered">13</td>
<td class="gt_row gt_right"
headers="Social media stub_1_7 Order rate">0.19</td>
</tr>
<tr>
<td id="stub_1_8" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row">Instagram</td>
<td class="gt_row gt_right" headers="Social media stub_1_8 Wave">2</td>
<td class="gt_row gt_right"
headers="Social media stub_1_8 Number of days">38</td>
<td class="gt_row gt_right"
headers="Social media stub_1_8 Number of test kits ordered">13</td>
<td class="gt_row gt_right"
headers="Social media stub_1_8 Order rate">0.34</td>
</tr>
<tr>
<td id="stub_1_9" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row"><br />
</td>
<td class="gt_row gt_right" headers="Social media stub_1_9 Wave"><br />
</td>
<td class="gt_row gt_right"
headers="Social media stub_1_9 Number of days">108</td>
<td class="gt_row gt_right"
headers="Social media stub_1_9 Number of test kits ordered">26</td>
<td class="gt_row gt_right"
headers="Social media stub_1_9 Order rate">0.24</td>
</tr>
<tr class="gt_group_heading_row">
<td colspan="5" id="Total" class="gt_group_heading"
data-quarto-table-cell-role="th" style="font-weight: bold"
scope="colgroup">Total</td>
</tr>
<tr class="gt_row_group_first">
<td id="stub_1_10" class="gt_row gt_left gt_stub"
data-quarto-table-cell-role="th" scope="row"><br />
</td>
<td class="gt_row gt_right" headers="Total stub_1_10 Wave"><br />
</td>
<td class="gt_row gt_right"
headers="Total stub_1_10 Number of days">108</td>
<td class="gt_row gt_right"
headers="Total stub_1_10 Number of test kits ordered">177</td>
<td class="gt_row gt_right"
headers="Total stub_1_10 Order rate">1.64</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes">
<td colspan="5" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span>
Wave 1a duration was 70 days.</td>
</tr>
</tfoot>
&#10;</table>

</div>

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

<div id="elxaejwjsw" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#elxaejwjsw table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#elxaejwjsw thead, #elxaejwjsw tbody, #elxaejwjsw tfoot, #elxaejwjsw tr, #elxaejwjsw td, #elxaejwjsw th {
  border-style: none;
}
&#10;#elxaejwjsw p {
  margin: 0;
  padding: 0;
}
&#10;#elxaejwjsw .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #000000;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#elxaejwjsw .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#elxaejwjsw .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#elxaejwjsw .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: bold;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#elxaejwjsw .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: bold;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#elxaejwjsw .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#elxaejwjsw .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#elxaejwjsw .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#elxaejwjsw .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#elxaejwjsw .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: bold;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#elxaejwjsw .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: bold;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#elxaejwjsw .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#elxaejwjsw .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#elxaejwjsw .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#elxaejwjsw .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#elxaejwjsw .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#elxaejwjsw .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#elxaejwjsw .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#elxaejwjsw .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#elxaejwjsw .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#elxaejwjsw .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#elxaejwjsw .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#elxaejwjsw .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#elxaejwjsw .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#elxaejwjsw .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#elxaejwjsw .gt_left {
  text-align: left;
}
&#10;#elxaejwjsw .gt_center {
  text-align: center;
}
&#10;#elxaejwjsw .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#elxaejwjsw .gt_font_normal {
  font-weight: normal;
}
&#10;#elxaejwjsw .gt_font_bold {
  font-weight: bold;
}
&#10;#elxaejwjsw .gt_font_italic {
  font-style: italic;
}
&#10;#elxaejwjsw .gt_super {
  font-size: 65%;
}
&#10;#elxaejwjsw .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#elxaejwjsw .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#elxaejwjsw .gt_indent_1 {
  text-indent: 5px;
}
&#10;#elxaejwjsw .gt_indent_2 {
  text-indent: 10px;
}
&#10;#elxaejwjsw .gt_indent_3 {
  text-indent: 15px;
}
&#10;#elxaejwjsw .gt_indent_4 {
  text-indent: 20px;
}
&#10;#elxaejwjsw .gt_indent_5 {
  text-indent: 25px;
}
&#10;#elxaejwjsw .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#elxaejwjsw div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

| Predicted Test Kit Order Rates |  |  |
|----|----|----|
| Estimates derived from Poisson Regression |  |  |
| Platform Name | Wave | Predicted Order Rate (kits/day) |
| Social media |  |  |
| Facebook | 1 | 0.186 |
| Instagram | 2 | 0.342 |
| Dating app |  |  |
| Grindr | 1 | 0.129 |
| Jack'D | 2 | 3.316 |
| Info site |  |  |
| Google | 1 | 0.229 |
| Bing | 2 | 0.000 |

</div>

<div id="mbqirsobrh" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#mbqirsobrh table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#mbqirsobrh thead, #mbqirsobrh tbody, #mbqirsobrh tfoot, #mbqirsobrh tr, #mbqirsobrh td, #mbqirsobrh th {
  border-style: none;
}
&#10;#mbqirsobrh p {
  margin: 0;
  padding: 0;
}
&#10;#mbqirsobrh .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#mbqirsobrh .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#mbqirsobrh .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#mbqirsobrh .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#mbqirsobrh .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#mbqirsobrh .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#mbqirsobrh .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#mbqirsobrh .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#mbqirsobrh .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#mbqirsobrh .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#mbqirsobrh .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#mbqirsobrh .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#mbqirsobrh .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#mbqirsobrh .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#mbqirsobrh .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#mbqirsobrh .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#mbqirsobrh .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#mbqirsobrh .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#mbqirsobrh .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#mbqirsobrh .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#mbqirsobrh .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#mbqirsobrh .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#mbqirsobrh .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#mbqirsobrh .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#mbqirsobrh .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#mbqirsobrh .gt_left {
  text-align: left;
}
&#10;#mbqirsobrh .gt_center {
  text-align: center;
}
&#10;#mbqirsobrh .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#mbqirsobrh .gt_font_normal {
  font-weight: normal;
}
&#10;#mbqirsobrh .gt_font_bold {
  font-weight: bold;
}
&#10;#mbqirsobrh .gt_font_italic {
  font-style: italic;
}
&#10;#mbqirsobrh .gt_super {
  font-size: 65%;
}
&#10;#mbqirsobrh .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#mbqirsobrh .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#mbqirsobrh .gt_indent_1 {
  text-indent: 5px;
}
&#10;#mbqirsobrh .gt_indent_2 {
  text-indent: 10px;
}
&#10;#mbqirsobrh .gt_indent_3 {
  text-indent: 15px;
}
&#10;#mbqirsobrh .gt_indent_4 {
  text-indent: 20px;
}
&#10;#mbqirsobrh .gt_indent_5 {
  text-indent: 25px;
}
&#10;#mbqirsobrh .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#mbqirsobrh div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

| Contrast           | Ratio | Std. Error | DF  | null | Z-score | P-Value |
|--------------------|-------|------------|-----|------|---------|---------|
| 2                  |       |            |     |      |         |         |
| Bing / Instagram   | 0.00  | 0.00       | Inf | 1    | 0.00    | 1.00    |
| Bing / Jack'd      | 0.00  | 0.00       | Inf | 1    | 0.00    | 1.00    |
| Instagram / Jack'd | 0.10  | 0.03       | Inf | 1    | −7.80   | 0.00    |
| 1                  |       |            |     |      |         |         |
| Facebook / Google  | 0.81  | 0.30       | Inf | 1    | −0.56   | 0.58    |
| Facebook / Grindr  | 1.44  | 0.63       | Inf | 1    | 0.85    | 0.58    |
| Google / Grindr    | 1.78  | 0.74       | Inf | 1    | 1.38    | 0.50    |

</div>

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

<div id="vluxlzepfe" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#vluxlzepfe table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#vluxlzepfe thead, #vluxlzepfe tbody, #vluxlzepfe tfoot, #vluxlzepfe tr, #vluxlzepfe td, #vluxlzepfe th {
  border-style: none;
}
&#10;#vluxlzepfe p {
  margin: 0;
  padding: 0;
}
&#10;#vluxlzepfe .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#vluxlzepfe .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#vluxlzepfe .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#vluxlzepfe .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#vluxlzepfe .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#vluxlzepfe .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#vluxlzepfe .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#vluxlzepfe .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#vluxlzepfe .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#vluxlzepfe .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#vluxlzepfe .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#vluxlzepfe .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#vluxlzepfe .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#vluxlzepfe .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#vluxlzepfe .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vluxlzepfe .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#vluxlzepfe .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#vluxlzepfe .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#vluxlzepfe .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vluxlzepfe .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#vluxlzepfe .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vluxlzepfe .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#vluxlzepfe .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vluxlzepfe .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#vluxlzepfe .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vluxlzepfe .gt_left {
  text-align: left;
}
&#10;#vluxlzepfe .gt_center {
  text-align: center;
}
&#10;#vluxlzepfe .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#vluxlzepfe .gt_font_normal {
  font-weight: normal;
}
&#10;#vluxlzepfe .gt_font_bold {
  font-weight: bold;
}
&#10;#vluxlzepfe .gt_font_italic {
  font-style: italic;
}
&#10;#vluxlzepfe .gt_super {
  font-size: 65%;
}
&#10;#vluxlzepfe .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#vluxlzepfe .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#vluxlzepfe .gt_indent_1 {
  text-indent: 5px;
}
&#10;#vluxlzepfe .gt_indent_2 {
  text-indent: 10px;
}
&#10;#vluxlzepfe .gt_indent_3 {
  text-indent: 15px;
}
&#10;#vluxlzepfe .gt_indent_4 {
  text-indent: 20px;
}
&#10;#vluxlzepfe .gt_indent_5 {
  text-indent: 25px;
}
&#10;#vluxlzepfe .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#vluxlzepfe div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table do-not-create-environment"
data-quarto-postprocess="true" data-quarto-disable-processing="false"
data-quarto-bootstrap="false">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="gt_col_headings">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left"
data-quarto-table-cell-role="th"
scope="col"><strong>Characteristic</strong></th>
<th id="stat_1"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>No</strong><br>N =
77<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>Yes</strong><br>N =
177<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th"
scope="col"><strong>p-value</strong><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">alcohol</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.3</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    None</td>
<td class="gt_row gt_center" headers="stat_1">16 (21%)</td>
<td class="gt_row gt_center" headers="stat_2">52 (29%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Problem Use</td>
<td class="gt_row gt_center" headers="stat_1">21 (27%)</td>
<td class="gt_row gt_center" headers="stat_2">46 (26%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    High Risk Substance
Use</td>
<td class="gt_row gt_center" headers="stat_1">40 (52%)</td>
<td class="gt_row gt_center" headers="stat_2">79 (45%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">cannabis</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.10</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    None</td>
<td class="gt_row gt_center" headers="stat_1">32 (42%)</td>
<td class="gt_row gt_center" headers="stat_2">89 (50%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Problem Use</td>
<td class="gt_row gt_center" headers="stat_1">12 (16%)</td>
<td class="gt_row gt_center" headers="stat_2">37 (21%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    High Risk Substance
Use</td>
<td class="gt_row gt_center" headers="stat_1">33 (43%)</td>
<td class="gt_row gt_center" headers="stat_2">51 (29%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">stimulants</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.3</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    None</td>
<td class="gt_row gt_center" headers="stat_1">69 (90%)</td>
<td class="gt_row gt_center" headers="stat_2">165 (93%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Problem Use/High Risk
Substance Use</td>
<td class="gt_row gt_center" headers="stat_1">8 (10%)</td>
<td class="gt_row gt_center" headers="stat_2">12 (6.8%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">opioids</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">&gt;0.9</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    None</td>
<td class="gt_row gt_center" headers="stat_1">75 (97%)</td>
<td class="gt_row gt_center" headers="stat_2">173 (98%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Problem Use/High Risk
Substance Use</td>
<td class="gt_row gt_center" headers="stat_1">2 (2.6%)</td>
<td class="gt_row gt_center" headers="stat_2">4 (2.3%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">sedatives</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.8</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    None</td>
<td class="gt_row gt_center" headers="stat_1">72 (94%)</td>
<td class="gt_row gt_center" headers="stat_2">168 (95%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Problem Use/High Risk
Substance Use</td>
<td class="gt_row gt_center" headers="stat_1">5 (6.5%)</td>
<td class="gt_row gt_center" headers="stat_2">9 (5.1%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">prescription stimulants</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.7</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    None</td>
<td class="gt_row gt_center" headers="stat_1">74 (96%)</td>
<td class="gt_row gt_center" headers="stat_2">172 (97%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Problem Use/High Risk
Substance Use</td>
<td class="gt_row gt_center" headers="stat_1">3 (3.9%)</td>
<td class="gt_row gt_center" headers="stat_2">5 (2.8%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span>
n (%)</td>
</tr>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span>
Fisher’s exact test</td>
</tr>
</tfoot>
&#10;</table>

</div>

</div>

</div>

#### b. Stage of Health Behavior Change

<div id="zvstehwlhq" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#zvstehwlhq table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#zvstehwlhq thead, #zvstehwlhq tbody, #zvstehwlhq tfoot, #zvstehwlhq tr, #zvstehwlhq td, #zvstehwlhq th {
  border-style: none;
}
&#10;#zvstehwlhq p {
  margin: 0;
  padding: 0;
}
&#10;#zvstehwlhq .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#zvstehwlhq .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#zvstehwlhq .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#zvstehwlhq .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#zvstehwlhq .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#zvstehwlhq .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#zvstehwlhq .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#zvstehwlhq .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#zvstehwlhq .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#zvstehwlhq .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#zvstehwlhq .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#zvstehwlhq .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#zvstehwlhq .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#zvstehwlhq .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#zvstehwlhq .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#zvstehwlhq .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#zvstehwlhq .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#zvstehwlhq .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#zvstehwlhq .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#zvstehwlhq .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#zvstehwlhq .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#zvstehwlhq .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#zvstehwlhq .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#zvstehwlhq .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#zvstehwlhq .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#zvstehwlhq .gt_left {
  text-align: left;
}
&#10;#zvstehwlhq .gt_center {
  text-align: center;
}
&#10;#zvstehwlhq .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#zvstehwlhq .gt_font_normal {
  font-weight: normal;
}
&#10;#zvstehwlhq .gt_font_bold {
  font-weight: bold;
}
&#10;#zvstehwlhq .gt_font_italic {
  font-style: italic;
}
&#10;#zvstehwlhq .gt_super {
  font-size: 65%;
}
&#10;#zvstehwlhq .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#zvstehwlhq .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#zvstehwlhq .gt_indent_1 {
  text-indent: 5px;
}
&#10;#zvstehwlhq .gt_indent_2 {
  text-indent: 10px;
}
&#10;#zvstehwlhq .gt_indent_3 {
  text-indent: 15px;
}
&#10;#zvstehwlhq .gt_indent_4 {
  text-indent: 20px;
}
&#10;#zvstehwlhq .gt_indent_5 {
  text-indent: 25px;
}
&#10;#zvstehwlhq .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#zvstehwlhq div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table" data-quarto-postprocess="true"
data-quarto-disable-processing="false" data-quarto-bootstrap="false">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="gt_col_headings">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left"
data-quarto-table-cell-role="th"
scope="col"><strong>Characteristic</strong></th>
<th id="stat_1"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>No</strong><br>N =
77<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>Yes</strong><br>N =
177<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th"
scope="col"><strong>p-value</strong><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">Health Behavior Change</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.21</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Precontemplation</td>
<td class="gt_row gt_center" headers="stat_1">2 (2.6%)</td>
<td class="gt_row gt_center" headers="stat_2">7 (4.0%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Contemplation</td>
<td class="gt_row gt_center" headers="stat_1">8 (10%)</td>
<td class="gt_row gt_center" headers="stat_2">32 (18%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Determination</td>
<td class="gt_row gt_center" headers="stat_1">49 (64%)</td>
<td class="gt_row gt_center" headers="stat_2">86 (49%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Action</td>
<td class="gt_row gt_center" headers="stat_1">12 (16%)</td>
<td class="gt_row gt_center" headers="stat_2">40 (23%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Maintenance</td>
<td class="gt_row gt_center" headers="stat_1">6 (7.8%)</td>
<td class="gt_row gt_center" headers="stat_2">12 (6.8%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span>
n (%)</td>
</tr>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span>
Fisher’s exact test</td>
</tr>
</tfoot>
&#10;</table>

</div>

#### c. Attitudes toward human immunodeficiency virus (HIV) testing

<div id="egrbxywtke" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#egrbxywtke table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#egrbxywtke thead, #egrbxywtke tbody, #egrbxywtke tfoot, #egrbxywtke tr, #egrbxywtke td, #egrbxywtke th {
  border-style: none;
}
&#10;#egrbxywtke p {
  margin: 0;
  padding: 0;
}
&#10;#egrbxywtke .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#egrbxywtke .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#egrbxywtke .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#egrbxywtke .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#egrbxywtke .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#egrbxywtke .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#egrbxywtke .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#egrbxywtke .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#egrbxywtke .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#egrbxywtke .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#egrbxywtke .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#egrbxywtke .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#egrbxywtke .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#egrbxywtke .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#egrbxywtke .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#egrbxywtke .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#egrbxywtke .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#egrbxywtke .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#egrbxywtke .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#egrbxywtke .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#egrbxywtke .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#egrbxywtke .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#egrbxywtke .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#egrbxywtke .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#egrbxywtke .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#egrbxywtke .gt_left {
  text-align: left;
}
&#10;#egrbxywtke .gt_center {
  text-align: center;
}
&#10;#egrbxywtke .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#egrbxywtke .gt_font_normal {
  font-weight: normal;
}
&#10;#egrbxywtke .gt_font_bold {
  font-weight: bold;
}
&#10;#egrbxywtke .gt_font_italic {
  font-style: italic;
}
&#10;#egrbxywtke .gt_super {
  font-size: 65%;
}
&#10;#egrbxywtke .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#egrbxywtke .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#egrbxywtke .gt_indent_1 {
  text-indent: 5px;
}
&#10;#egrbxywtke .gt_indent_2 {
  text-indent: 10px;
}
&#10;#egrbxywtke .gt_indent_3 {
  text-indent: 15px;
}
&#10;#egrbxywtke .gt_indent_4 {
  text-indent: 20px;
}
&#10;#egrbxywtke .gt_indent_5 {
  text-indent: 25px;
}
&#10;#egrbxywtke .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#egrbxywtke div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table" data-quarto-postprocess="true"
data-quarto-disable-processing="false" data-quarto-bootstrap="false">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="gt_col_headings">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left"
data-quarto-table-cell-role="th"
scope="col"><strong>Characteristic</strong></th>
<th id="stat_1"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>No</strong><br>N =
77<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>Yes</strong><br>N =
177<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th"
scope="col"><strong>p-value</strong><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">Getting tested for HIV helps people feel
better</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.16</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">70 (91%)</td>
<td class="gt_row gt_center" headers="stat_2">169 (95%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">7 (9.1%)</td>
<td class="gt_row gt_center" headers="stat_2">8 (4.5%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">Getting tested for HIV helps people from
getting HIV</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.72</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">62 (82%)</td>
<td class="gt_row gt_center" headers="stat_2">148 (84%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">14 (18%)</td>
<td class="gt_row gt_center" headers="stat_2">29 (16%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">1</td>
<td class="gt_row gt_center" headers="stat_2">0</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">People in my life would leave if I had
HIV</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.049</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">37 (48%)</td>
<td class="gt_row gt_center" headers="stat_2">60 (34%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">40 (52%)</td>
<td class="gt_row gt_center" headers="stat_2">115 (66%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">0</td>
<td class="gt_row gt_center" headers="stat_2">2</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">People who tested positive for HIV should hide
it from others</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.82</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">9 (12%)</td>
<td class="gt_row gt_center" headers="stat_2">18 (10%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">68 (88%)</td>
<td class="gt_row gt_center" headers="stat_2">159 (90%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
would rather not know if I have HIV</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.46</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">15 (19%)</td>
<td class="gt_row gt_center" headers="stat_2">27 (15%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">62 (81%)</td>
<td class="gt_row gt_center" headers="stat_2">150 (85%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span>
n (%)</td>
</tr>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span>
Fisher’s exact test</td>
</tr>
</tfoot>
&#10;</table>

</div>

#### d. Attitudes toward human immunodeficiency virus (HIV) treatment

<div id="yknryhbarr" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#yknryhbarr table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#yknryhbarr thead, #yknryhbarr tbody, #yknryhbarr tfoot, #yknryhbarr tr, #yknryhbarr td, #yknryhbarr th {
  border-style: none;
}
&#10;#yknryhbarr p {
  margin: 0;
  padding: 0;
}
&#10;#yknryhbarr .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#yknryhbarr .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#yknryhbarr .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#yknryhbarr .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#yknryhbarr .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#yknryhbarr .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#yknryhbarr .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#yknryhbarr .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#yknryhbarr .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#yknryhbarr .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#yknryhbarr .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#yknryhbarr .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#yknryhbarr .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#yknryhbarr .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#yknryhbarr .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yknryhbarr .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#yknryhbarr .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#yknryhbarr .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#yknryhbarr .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yknryhbarr .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#yknryhbarr .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yknryhbarr .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#yknryhbarr .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yknryhbarr .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#yknryhbarr .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yknryhbarr .gt_left {
  text-align: left;
}
&#10;#yknryhbarr .gt_center {
  text-align: center;
}
&#10;#yknryhbarr .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#yknryhbarr .gt_font_normal {
  font-weight: normal;
}
&#10;#yknryhbarr .gt_font_bold {
  font-weight: bold;
}
&#10;#yknryhbarr .gt_font_italic {
  font-style: italic;
}
&#10;#yknryhbarr .gt_super {
  font-size: 65%;
}
&#10;#yknryhbarr .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#yknryhbarr .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#yknryhbarr .gt_indent_1 {
  text-indent: 5px;
}
&#10;#yknryhbarr .gt_indent_2 {
  text-indent: 10px;
}
&#10;#yknryhbarr .gt_indent_3 {
  text-indent: 15px;
}
&#10;#yknryhbarr .gt_indent_4 {
  text-indent: 20px;
}
&#10;#yknryhbarr .gt_indent_5 {
  text-indent: 25px;
}
&#10;#yknryhbarr .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#yknryhbarr div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table" data-quarto-postprocess="true"
data-quarto-disable-processing="false" data-quarto-bootstrap="false">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="gt_col_headings">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left"
data-quarto-table-cell-role="th"
scope="col"><strong>Characteristic</strong></th>
<th id="stat_1"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>No</strong><br />
N = 77<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>Yes</strong><br />
N = 177<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th"
scope="col"><strong>p-value</strong><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
am less threatened by the idea of being HIV positive than I used to
be</td>
<td class="gt_row gt_center" headers="stat_1">3.84 (2.16)</td>
<td class="gt_row gt_center" headers="stat_2">4.09 (1.98)</td>
<td class="gt_row gt_center" headers="p.value">0.41</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
am less worried about HIV infection than I used to be</td>
<td class="gt_row gt_center" headers="stat_1">3.52 (1.84)</td>
<td class="gt_row gt_center" headers="stat_2">3.78 (1.99)</td>
<td class="gt_row gt_center" headers="p.value">0.34</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
think HIV/AIDS is less of a problem than it used to be</td>
<td class="gt_row gt_center" headers="stat_1">3.62 (2.11)</td>
<td class="gt_row gt_center" headers="stat_2">3.86 (2.11)</td>
<td class="gt_row gt_center" headers="p.value">0.45</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
think HIV/AIDS is a less serious threat than it used to be because of
new HIV/AIDS treatments</td>
<td class="gt_row gt_center" headers="stat_1">3.79 (2.11)</td>
<td class="gt_row gt_center" headers="stat_2">4.19 (2.03)</td>
<td class="gt_row gt_center" headers="p.value">0.21</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
am much less concerned about becoming HIV positive myself because of new
HIV/AIDS treatments</td>
<td class="gt_row gt_center" headers="stat_1">2.98 (1.89)</td>
<td class="gt_row gt_center" headers="stat_2">3.37 (2.04)</td>
<td class="gt_row gt_center" headers="p.value">0.27</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
think that condom use during sex is less necessary now that new HIV/AIDS
treatments are available</td>
<td class="gt_row gt_center" headers="stat_1">2.23 (1.53)</td>
<td class="gt_row gt_center" headers="stat_2">2.41 (1.77)</td>
<td class="gt_row gt_center" headers="p.value">0.88</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
think that someone who is HIV positive now needs to care less about
condom use</td>
<td class="gt_row gt_center" headers="stat_1">2.49 (2.08)</td>
<td class="gt_row gt_center" headers="stat_2">1.92 (1.66)</td>
<td class="gt_row gt_center" headers="p.value">0.059</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
think that the need for condom use is less than it used to be, because
you can always start new treatments</td>
<td class="gt_row gt_center" headers="stat_1">2.46 (2.02)</td>
<td class="gt_row gt_center" headers="stat_2">2.50 (1.86)</td>
<td class="gt_row gt_center" headers="p.value">0.76</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
think that someone who is HIV positive and uses new HIV/AIDS treatments
can be cured</td>
<td class="gt_row gt_center" headers="stat_1">3.64 (2.16)</td>
<td class="gt_row gt_center" headers="stat_2">3.25 (1.95)</td>
<td class="gt_row gt_center" headers="p.value">0.21</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
think that new HIV/AIDS treatments can eradicate the virus from your
body</td>
<td class="gt_row gt_center" headers="stat_1">3.80 (2.08)</td>
<td class="gt_row gt_center" headers="stat_2">3.09 (1.94)</td>
<td class="gt_row gt_center" headers="p.value">0.031</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span>
Mean (SD)</td>
</tr>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span>
Wilcoxon rank sum test</td>
</tr>
</tfoot>
&#10;</table>

</div>

#### e. Human immunodeficiency virus (HIV)-related stigma among study participants

<div id="yssjrjdish" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#yssjrjdish table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#yssjrjdish thead, #yssjrjdish tbody, #yssjrjdish tfoot, #yssjrjdish tr, #yssjrjdish td, #yssjrjdish th {
  border-style: none;
}
&#10;#yssjrjdish p {
  margin: 0;
  padding: 0;
}
&#10;#yssjrjdish .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#yssjrjdish .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#yssjrjdish .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#yssjrjdish .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#yssjrjdish .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#yssjrjdish .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#yssjrjdish .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#yssjrjdish .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#yssjrjdish .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#yssjrjdish .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#yssjrjdish .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#yssjrjdish .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#yssjrjdish .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#yssjrjdish .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#yssjrjdish .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yssjrjdish .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#yssjrjdish .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#yssjrjdish .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#yssjrjdish .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yssjrjdish .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#yssjrjdish .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yssjrjdish .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#yssjrjdish .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yssjrjdish .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#yssjrjdish .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#yssjrjdish .gt_left {
  text-align: left;
}
&#10;#yssjrjdish .gt_center {
  text-align: center;
}
&#10;#yssjrjdish .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#yssjrjdish .gt_font_normal {
  font-weight: normal;
}
&#10;#yssjrjdish .gt_font_bold {
  font-weight: bold;
}
&#10;#yssjrjdish .gt_font_italic {
  font-style: italic;
}
&#10;#yssjrjdish .gt_super {
  font-size: 65%;
}
&#10;#yssjrjdish .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#yssjrjdish .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#yssjrjdish .gt_indent_1 {
  text-indent: 5px;
}
&#10;#yssjrjdish .gt_indent_2 {
  text-indent: 10px;
}
&#10;#yssjrjdish .gt_indent_3 {
  text-indent: 15px;
}
&#10;#yssjrjdish .gt_indent_4 {
  text-indent: 20px;
}
&#10;#yssjrjdish .gt_indent_5 {
  text-indent: 25px;
}
&#10;#yssjrjdish .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#yssjrjdish div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table" data-quarto-postprocess="true"
data-quarto-disable-processing="false" data-quarto-bootstrap="false">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="gt_col_headings">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left"
data-quarto-table-cell-role="th"
scope="col"><strong>Characteristic</strong></th>
<th id="stat_1"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>No</strong><br>N =
77<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>Yes</strong><br>N =
177<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th"
scope="col"><strong>p-value</strong><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
feel afraid of people living with HIV/AIDS</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.56</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">7 (9.1%)</td>
<td class="gt_row gt_center" headers="stat_2">11 (6.2%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">2 (2.6%)</td>
<td class="gt_row gt_center" headers="stat_2">9 (5.1%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Somewhat agree</td>
<td class="gt_row gt_center" headers="stat_1">9 (12%)</td>
<td class="gt_row gt_center" headers="stat_2">21 (12%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Neither agree nor
disagree</td>
<td class="gt_row gt_center" headers="stat_1">9 (12%)</td>
<td class="gt_row gt_center" headers="stat_2">20 (11%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Somewhat disagree</td>
<td class="gt_row gt_center" headers="stat_1">6 (7.8%)</td>
<td class="gt_row gt_center" headers="stat_2">11 (6.2%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">17 (22%)</td>
<td class="gt_row gt_center" headers="stat_2">33 (19%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">27 (35%)</td>
<td class="gt_row gt_center" headers="stat_2">72 (41%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
could not be friends with someone who has HIV/AIDS</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.040</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">4 (5.2%)</td>
<td class="gt_row gt_center" headers="stat_2">1 (0.6%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">0 (0%)</td>
<td class="gt_row gt_center" headers="stat_2">1 (0.6%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Somewhat agree</td>
<td class="gt_row gt_center" headers="stat_1">1 (1.3%)</td>
<td class="gt_row gt_center" headers="stat_2">3 (1.7%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Neither agree nor
disagree</td>
<td class="gt_row gt_center" headers="stat_1">6 (7.8%)</td>
<td class="gt_row gt_center" headers="stat_2">9 (5.1%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Somewhat disagree</td>
<td class="gt_row gt_center" headers="stat_1">1 (1.3%)</td>
<td class="gt_row gt_center" headers="stat_2">7 (4.0%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">19 (25%)</td>
<td class="gt_row gt_center" headers="stat_2">27 (15%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">46 (60%)</td>
<td class="gt_row gt_center" headers="stat_2">129 (73%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">People who get HIV/AIDS through sex or drug
use got what they deserve</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.39</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">0 (0%)</td>
<td class="gt_row gt_center" headers="stat_2">2 (1.1%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">1 (1.3%)</td>
<td class="gt_row gt_center" headers="stat_2">2 (1.1%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Somewhat agree</td>
<td class="gt_row gt_center" headers="stat_1">2 (2.6%)</td>
<td class="gt_row gt_center" headers="stat_2">4 (2.3%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Neither agree nor
disagree</td>
<td class="gt_row gt_center" headers="stat_1">7 (9.1%)</td>
<td class="gt_row gt_center" headers="stat_2">8 (4.5%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Somewhat disagree</td>
<td class="gt_row gt_center" headers="stat_1">2 (2.6%)</td>
<td class="gt_row gt_center" headers="stat_2">6 (3.4%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">12 (16%)</td>
<td class="gt_row gt_center" headers="stat_2">24 (14%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">53 (69%)</td>
<td class="gt_row gt_center" headers="stat_2">131 (74%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label" style="font-weight: bold">I
feel anger toward people with HIV/AIDS</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.25</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">0 (0%)</td>
<td class="gt_row gt_center" headers="stat_2">1 (0.6%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">0 (0%)</td>
<td class="gt_row gt_center" headers="stat_2">0 (0%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Somewhat agree</td>
<td class="gt_row gt_center" headers="stat_1">0 (0%)</td>
<td class="gt_row gt_center" headers="stat_2">0 (0%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Neither agree nor
disagree</td>
<td class="gt_row gt_center" headers="stat_1">5 (6.5%)</td>
<td class="gt_row gt_center" headers="stat_2">11 (6.2%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Somewhat disagree</td>
<td class="gt_row gt_center" headers="stat_1">0 (0%)</td>
<td class="gt_row gt_center" headers="stat_2">3 (1.7%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">16 (21%)</td>
<td class="gt_row gt_center" headers="stat_2">20 (11%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">56 (73%)</td>
<td class="gt_row gt_center" headers="stat_2">142 (80%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span>
n (%)</td>
</tr>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span>
Wilcoxon rank sum test</td>
</tr>
</tfoot>
&#10;</table>

</div>

#### f. Medical mistrust

<div id="tbl-f">

Table 4

<div class="cell-output-display">

<div id="kkjueawyoq" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#kkjueawyoq table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#kkjueawyoq thead, #kkjueawyoq tbody, #kkjueawyoq tfoot, #kkjueawyoq tr, #kkjueawyoq td, #kkjueawyoq th {
  border-style: none;
}
&#10;#kkjueawyoq p {
  margin: 0;
  padding: 0;
}
&#10;#kkjueawyoq .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#kkjueawyoq .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#kkjueawyoq .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#kkjueawyoq .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#kkjueawyoq .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#kkjueawyoq .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#kkjueawyoq .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#kkjueawyoq .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#kkjueawyoq .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#kkjueawyoq .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#kkjueawyoq .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#kkjueawyoq .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#kkjueawyoq .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#kkjueawyoq .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#kkjueawyoq .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#kkjueawyoq .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#kkjueawyoq .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#kkjueawyoq .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#kkjueawyoq .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#kkjueawyoq .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#kkjueawyoq .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#kkjueawyoq .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#kkjueawyoq .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#kkjueawyoq .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#kkjueawyoq .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#kkjueawyoq .gt_left {
  text-align: left;
}
&#10;#kkjueawyoq .gt_center {
  text-align: center;
}
&#10;#kkjueawyoq .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#kkjueawyoq .gt_font_normal {
  font-weight: normal;
}
&#10;#kkjueawyoq .gt_font_bold {
  font-weight: bold;
}
&#10;#kkjueawyoq .gt_font_italic {
  font-style: italic;
}
&#10;#kkjueawyoq .gt_super {
  font-size: 65%;
}
&#10;#kkjueawyoq .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#kkjueawyoq .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#kkjueawyoq .gt_indent_1 {
  text-indent: 5px;
}
&#10;#kkjueawyoq .gt_indent_2 {
  text-indent: 10px;
}
&#10;#kkjueawyoq .gt_indent_3 {
  text-indent: 15px;
}
&#10;#kkjueawyoq .gt_indent_4 {
  text-indent: 20px;
}
&#10;#kkjueawyoq .gt_indent_5 {
  text-indent: 25px;
}
&#10;#kkjueawyoq .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#kkjueawyoq div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table do-not-create-environment"
data-quarto-postprocess="true" data-quarto-disable-processing="false"
data-quarto-bootstrap="false">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="gt_col_headings">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left"
data-quarto-table-cell-role="th"
scope="col"><strong>Characteristic</strong></th>
<th id="stat_1"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>No</strong><br>N =
77<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th" scope="col"><strong>Yes</strong><br>N =
177<span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value"
class="gt_col_heading gt_columns_bottom_border gt_center"
data-quarto-table-cell-role="th"
scope="col"><strong>p-value</strong><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">You’d better be cautious when dealing with
health care organizations</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.81</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">17 (22%)</td>
<td class="gt_row gt_center" headers="stat_2">37 (21%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">32 (42%)</td>
<td class="gt_row gt_center" headers="stat_2">67 (38%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">14 (18%)</td>
<td class="gt_row gt_center" headers="stat_2">42 (24%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">13 (17%)</td>
<td class="gt_row gt_center" headers="stat_2">31 (18%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">1</td>
<td class="gt_row gt_center" headers="stat_2">0</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">Patients have sometimes been deceived or
misled by health care organizations</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.38</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">11 (14%)</td>
<td class="gt_row gt_center" headers="stat_2">32 (18%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">34 (44%)</td>
<td class="gt_row gt_center" headers="stat_2">84 (48%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">22 (29%)</td>
<td class="gt_row gt_center" headers="stat_2">33 (19%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">10 (13%)</td>
<td class="gt_row gt_center" headers="stat_2">27 (15%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">0</td>
<td class="gt_row gt_center" headers="stat_2">1</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">When health care organizations make mistakes
they usually cover it up</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.026</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">10 (13%)</td>
<td class="gt_row gt_center" headers="stat_2">29 (17%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">29 (38%)</td>
<td class="gt_row gt_center" headers="stat_2">84 (48%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">30 (39%)</td>
<td class="gt_row gt_center" headers="stat_2">36 (21%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">7 (9.2%)</td>
<td class="gt_row gt_center" headers="stat_2">25 (14%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">1</td>
<td class="gt_row gt_center" headers="stat_2">3</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">Health care organizations have sometimes done
harmful experiments on patients without their knowledge</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.55</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">14 (18%)</td>
<td class="gt_row gt_center" headers="stat_2">30 (17%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">25 (32%)</td>
<td class="gt_row gt_center" headers="stat_2">73 (41%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">26 (34%)</td>
<td class="gt_row gt_center" headers="stat_2">52 (30%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">12 (16%)</td>
<td class="gt_row gt_center" headers="stat_2">21 (12%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">0</td>
<td class="gt_row gt_center" headers="stat_2">1</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">Health care organizations don’t always keep
your information totally private</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.66</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">11 (14%)</td>
<td class="gt_row gt_center" headers="stat_2">37 (21%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">29 (38%)</td>
<td class="gt_row gt_center" headers="stat_2">64 (37%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">23 (30%)</td>
<td class="gt_row gt_center" headers="stat_2">47 (27%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">13 (17%)</td>
<td class="gt_row gt_center" headers="stat_2">27 (15%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">1</td>
<td class="gt_row gt_center" headers="stat_2">2</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">Sometimes I wonder if health care
organizations really know what they are doing</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.90</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">9 (12%)</td>
<td class="gt_row gt_center" headers="stat_2">23 (13%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">28 (36%)</td>
<td class="gt_row gt_center" headers="stat_2">66 (38%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">30 (39%)</td>
<td class="gt_row gt_center" headers="stat_2">60 (34%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">10 (13%)</td>
<td class="gt_row gt_center" headers="stat_2">27 (15%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">0</td>
<td class="gt_row gt_center" headers="stat_2">1</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label"
style="font-weight: bold">Mistakes are common in health care
organizations</td>
<td class="gt_row gt_center" headers="stat_1"><br />
</td>
<td class="gt_row gt_center" headers="stat_2"><br />
</td>
<td class="gt_row gt_center" headers="p.value">0.93</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly agree</td>
<td class="gt_row gt_center" headers="stat_1">8 (11%)</td>
<td class="gt_row gt_center" headers="stat_2">21 (12%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Agree</td>
<td class="gt_row gt_center" headers="stat_1">36 (48%)</td>
<td class="gt_row gt_center" headers="stat_2">89 (51%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Disagree</td>
<td class="gt_row gt_center" headers="stat_1">23 (31%)</td>
<td class="gt_row gt_center" headers="stat_2">47 (27%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Strongly disagree</td>
<td class="gt_row gt_center" headers="stat_1">8 (11%)</td>
<td class="gt_row gt_center" headers="stat_2">19 (11%)</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
<tr>
<td class="gt_row gt_left" headers="label">    Unknown</td>
<td class="gt_row gt_center" headers="stat_1">2</td>
<td class="gt_row gt_center" headers="stat_2">1</td>
<td class="gt_row gt_center" headers="p.value"><br />
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span>
n (%)</td>
</tr>
<tr class="gt_footnotes">
<td colspan="4" class="gt_footnote"><span class="gt_footnote_marks"
style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span>
Fisher’s exact test</td>
</tr>
</tfoot>
&#10;</table>

</div>

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
