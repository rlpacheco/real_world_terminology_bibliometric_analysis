# Real_world_terminology_bibliometric_analysis

All codes and files for the article: 

**Accelerated rate of published studies with uninformative “real-world” terminology in title and abstracts: a bibliometric analysis of the entire Medline database**

**Authors**: Rafael Leite Pacheco, Ana Luiza Cabrera Martimbianco, Carolina de Oliveira Cruz Latorraca, Rachel Riera

**Affiliation**: Centre of Health Technology Assessment, Hospital Sírio-Libanês

**Contact for feedbacks and corrections**: rleitepacheco@hotmail.com

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

csv files: you will find 15 csv files. **Do not open** them on Excel or any standard csv reader because of rounding settings that will distort the number of extracted references. It is better to read them direct from Stata of other statistical software.

For replication, we suggest you to place all files in your working directory.

Files (matchted with ordering from **Table 1**)

1) PubMed_Timeline_Results_by_Year_all_190322
2) PubMed_Timeline_Results_by_Year_RWE_title_190322
3) PubMed_Timeline_Results_by_Year_RWE_190322
4) PubMed_Timeline_Results_by_Year_rando_title_190322
5) PubMed_Timeline_Results_by_Year_rando_title_abst_190322
6) PubMed_Timeline_Results_by_Year_ct_190322
7) PubMed_Timeline_Results_by_Year_ct_narrow_190322
8) PubMed_Timeline_Results_by_Year_rw_t_covid_i_190322
9) PubMed_Timeline_Results_by_Year_rw_ta_covid_i_190322
10) PubMed_Timeline_Results_by_Year_rw_t_covid_p_190322
11) PubMed_Timeline_Results_by_Year_rw_ta_covid_p_190322
12) PubMed_Timeline_Results_by_Year_rando_t_covid_i_190322
13) PubMed_Timeline_Results_by_Year_rando_ta_covid_i_190322
14) PubMed_Timeline_Results_by_Year_rando_t_covid_p_190322
15) PubMed_Timeline_Results_by_Year_rando_ta_covid_p_190322

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Detailed conducted searchers (**Table 1**)

Searches date 19 March 2022

1) Totals search (hits 33,834,201) output file: PubMed_Timeline_Results_by_Year_all_190322

("1500"[Date - Publication] : "3000"[Date - Publication])

2) Real-world title (hits 14,994) output file: PubMed_Timeline_Results_by_Year_RWE_title_190322

"real world"[Title] OR "real-world"[Title]

3) Real-world title and abstract (hits 60,384) output file: PubMed_Timeline_Results_by_Year_RWE_190322

"real world"[Title/Abstract] OR "real-world"[Title/Abstract]

4) Randomized title (hits 239,779) output file: PubMed_Timeline_Results_by_Year_rando_title_190322

"randomized"[Title] OR "randomised"[Title]

5) Randomized title and abstract (hits 718,496) output file: PubMed_Timeline_Results_by_Year_rando_title_abst_190322

"randomized"[Title/Abstract] OR "randomised"[Title/Abstract]

6) Broad therapy filter (hits 5,995,181) output file: PubMed_Timeline_Results_by_Year_ct_190322

((clinical[Title/Abstract] AND trial[Title/Abstract]) OR clinical trials as topic[MeSH Terms] OR clinical trial[Publication Type] OR random*[Title/Abstract] OR random allocation[MeSH Terms] OR therapeutic use[MeSH Subheading])

7) Narrow therapy filter (hits 622,863) output file: PubMed_Timeline_Results_by_Year_ct_narrow_190322
(randomized controlled trial[Publication Type] OR (randomized[Title/Abstract] AND controlled[Title/Abstract] AND trial[Title/Abstract]))

8) Covid-19 therapy related (LitCTreatment) (hits 108,972) output file: not extracted

("COVID-19" OR "COVID-19"[MeSH Terms] OR "COVID-19 Vaccines" OR "COVID-19 Vaccines"[MeSH Terms] OR "COVID-19 serotherapy" OR "COVID-19 serotherapy"[Supplementary Concept] OR "COVID-19 Nucleic Acid Testing" OR "covid-19 nucleic acid testing"[MeSH Terms] OR "COVID-19 Serological Testing" OR "covid-19 serological testing"[MeSH Terms] OR "COVID-19 Testing" OR "covid-19 testing"[MeSH Terms] OR "SARS-CoV-2" OR "sars-cov-2"[MeSH Terms] OR "Severe Acute Respiratory Syndrome Coronavirus 2" OR "NCOV" OR "2019 NCOV" OR (("coronavirus"[MeSH Terms] OR "coronavirus" OR "COV") AND 2019/11/01[PDAT] : 3000/12/31[PDAT])) AND ("therapeutics"[MeSH Terms] OR "therapeutics"[All Fields] OR "treatments"[All Fields] OR "therapy"[MeSH Subheading] OR "therapy"[All Fields] OR "treatment"[All Fields] OR "treatment s"[All Fields] OR "treat*"[All Fields] OR ("clinical trial"[Publication Type] OR "clinical trials as topic"[MeSH Terms] OR "clinical trials"[All Fields]) OR ("clinical trial"[Publication Type] OR "clinical trials as topic"[MeSH Terms] OR "clinical trial"[All Fields]) OR ("randomized controlled trial"[Publication Type] OR "randomized controlled trials as topic"[MeSH Terms] OR "randomized controlled trial"[All Fields] OR "randomised controlled trial"[All Fields]) OR ("randomized controlled trial"[Publication Type] OR "randomized controlled trials as topic"[MeSH Terms] OR "randomized controlled trials"[All Fields] OR "randomised controlled trials"[All Fields]) OR ("therapeutics"[MeSH Terms] OR "therapeutics"[All Fields] OR "therapies"[All Fields] OR "therapy"[MeSH Subheading] OR "therapy"[All Fields] OR "therapy s"[All Fields] OR "therapys"[All Fields]) OR ("therapeutical"[All Fields] OR "therapeutically"[All Fields] OR "therapeuticals"[All Fields] OR "therapeutics"[MeSH Terms] OR "therapeutics"[All Fields] OR "therapeutic"[All Fields]))

9) Covid-19 prevention related (LitCPrevention) (hits 115,659) output file: not extracted

("COVID-19" OR "COVID-19"[MeSH Terms] OR "COVID-19 Vaccines" OR "COVID-19 Vaccines"[MeSH Terms] OR "COVID-19 serotherapy" OR "COVID-19 serotherapy"[Supplementary Concept] OR "COVID-19 Nucleic Acid Testing" OR "covid-19 nucleic acid testing"[MeSH Terms] OR "COVID-19 Serological Testing" OR "covid-19 serological testing"[MeSH Terms] OR "COVID-19 Testing" OR "covid-19 testing"[MeSH Terms] OR "SARS-CoV-2" OR "sars-cov-2"[MeSH Terms] OR "Severe Acute Respiratory Syndrome Coronavirus 2" OR "NCOV" OR "2019 NCOV" OR (("coronavirus"[MeSH Terms] OR "coronavirus" OR "COV") AND 2019/11/01[PDAT] : 3000/12/31[PDAT])) AND ("transmission*"[All Fields] OR "prevent*"[All Fields] OR "intervent*"[All Fields] OR ("prognosis"[MeSH Terms] OR "prognosis"[All Fields] OR "prognoses"[All Fields]) OR "treatment outcome"[All Fields] OR "prevention and control"[MeSH Subheading] OR ("therapeutical"[All Fields] OR "therapeutically"[All Fields] OR "therapeuticals"[All Fields] OR "therapeutics"[MeSH Terms] OR "therapeutics"[All Fields] OR "therapeutic"[All Fields]) OR "therapeutic*"[All Fields])
