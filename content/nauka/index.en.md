---
title: "Science"
date: "2026-10-25"
summary: "Academic publications, scientific research, and open-source data science tools - from psychometrics and social science methodology to multi-omics and a Nature-family publication."
showTableOfContents: true
---

{{< katex >}}

{{< lead >}}
In science and data analytics, what drives me most is the thrill of discovery - that feeling when, with the right analytical approach, one can cleanly isolate the hidden signal from apparent noise that no one had noticed before. Everyone can see raw data, but only rigorous methodology unveils what lies beneath.
{{< /lead >}}

Equally fascinating to me is the very mechanism of scientific progress. It is a globally unique process where researchers build directly upon each other's achievements, rigorously test hypotheses, and collectively push the boundaries of knowledge. Every solid analysis - whether it opens new horizons or prevents others from repeating mistakes - becomes a lasting building block for the community.

I find the greatest satisfaction in tackling problems with real-world gravity that can truly help people. The publications to my name are a source of deep pride: tangible proof that curiosity backed by methodological discipline delivers concrete, verifiable results.

Below, you will find my academic articles and research projects.

## Research & Publication Timeline

{{< timeline >}}
{{< timelineItem icon="graduation-cap" header="2008" badge="Studies & Psychometrics" subheader="The KWS Questionnaire and Master's Thesis Publication" md=true >}}
- **Doroszewicz, K., Sijko, K. (2008).** [Social Influence Questionnaire in Close Relationships (KWS)]. *Psychologia Jakości Życia*, 7(1-2), pp. 19-45. (In Polish).
- **Sijko, K. (2008).** [How Do Couples Play? Dynamics of Social Influence in Close Relationships]. *Psychologia Jakości Życia*, 7(1-2), pp. 139-157. (In Polish).

> The KWS questionnaire, which I co-developed, and a publication based on my master's thesis at SWPS University. I look back on this milestone with immense fondness: to this day, I still periodically receive emails from researchers and students requesting permission to adopt the KWS scale in new studies. I always gladly say yes, and it is truly heartwarming to see an early student project continue to live on in academic research.
{{< /timelineItem >}}
{{< timelineItem icon="lightbulb" header="2010-2014" badge="SWPS Era" subheader="Social Research Methodology & Jena Collaboration" md=true >}}
- **Brzezińska, A. I., Rycielski, P., Sijko, K. (2010).** [Methodological Challenges. Needs Diagnosis and Support Evaluation Among Individuals with Disabilities]. Warsaw: Scholar Scientific Publishing. (In Polish).
- **Pavlova, M. K., Silbereisen, R. K., Sijko, K. (2014).** *Social participation in Poland: Links to emotional well-being and risky alcohol consumption*. Social Indicators Research (Springer), 117(1), pp. 29-43.

> My first academic book publication dedicated to social science methodology: emphasizing the paramount importance of precise problem definition and what constitutes rigorous empirical design. The chapter spotlighting overlooked research vulnerabilities anticipated the psychology replication crisis (which unfolded in earnest between 2011-2015) - skepticism towards pure representativeness dogmas, critique of thoughtless threshold-chasing ($\alpha = 0.05$), and exposing the illusory nature of random sampling in hard-to-reach populations.
> 
> Collaboration with the University of Jena produced my first English peer-reviewed paper in *Social Indicators Research*. We observed an unexpected relationship between engagement in social participation / local NGOs and alcohol consumption patterns among Polish adults.
{{< /timelineItem >}}
{{< timelineItem icon="file-lines" header="2012-2014" badge="IBE Era" subheader="National Coordination of ICILS & Gaming Module in SUEK" md=true >}}
- **Sijko, K. (Ed.) (2014).** [Computer and Information Literacy of Youth in Poland. National Report from the ICILS 2013 Study]. Warsaw: Educational Research Institute (IBE). (In Polish).
- **SUEK Longitudinal Study (2012-2015):** Original research module dedicated to video gaming in the nationwide study *School Determinants of Educational Effectiveness*.

> At IBE, I served as the National Research Coordinator for the international IEA ICILS assessment. This multi-year study was carried out across schools in numerous countries using laptops and interactive scenario-based tasks to measure digital literacy. We established Poland's first standardized baseline for searching, verifying, and evaluating digital information - skills that, in today's generative AI era, are more vital than ever.
> 
> Simultaneously, I designed an original module on video gaming within the large-scale longitudinal SUEK study. While it didn't produce formal academic monographs, it sparked widely read popular science pieces (including in *Gazeta Wyborcza*), helping demystify common misconceptions surrounding gaming.
{{< /timelineItem >}}
{{< timelineItem icon="star" header="2017-2023" badge="Children's Memorial Health Institute & TT Science" subheader="The EPISTOP Trial and Multi-omic Discovery in Nature Communications (2023)" md=true >}}
- **Huschner, F., Głowacka-Walas, J., Kwiatkowski, D. J., [...], Sijko, K., [...], Jóźwiak, S., & Kotulska, K. (2023).** *Molecular EPISTOP, a comprehensive multi-omic analysis of blood from Tuberous Sclerosis Complex infants age birth to two years*. Nature Communications, 14, art. 7654. DOI: [10.1038/s41467-023-43187-y](https://doi.org/10.1038/s41467-023-43187-y)

> The data stemmed from the landmark EPISTOP clinical trial (described inter alia in Annals of Neurology, 2021), coordinated by the Children's Memorial Health Institute in Warsaw, evaluating preventive antiepileptic therapy in infants with Tuberous Sclerosis Complex (TSC). My team at Transition Technologies Science spearheaded the complex multi-omic analytics, processing over 33 TB of raw transcriptomic, proteomic, and metabolomic data.
> 
> In high-dimensional biological data ($p \gg n$), an uncompromising approach to false discovery rate (FDR) control, nested cross-validation, and robust biomarker selection was essential. The multivariate classifiers we developed accurately predicted epileptogenesis months prior to clinical seizure onset and characterized the molecular mechanisms of early preventive treatment. This project represented years of intensive work at the intersection of molecular biology and data engineering; having our work published in a Nature-family journal remains one of my most cherished career milestones.
{{< /timelineItem >}}
{{< /timeline >}}

## Open Source for Science

To me, research and code are inseparable. Scientific findings must be reproducible, and analytical toolsets openly accessible to the community - hence my work has often involved contributions to open-source projects.

Within the open pharmaverse ecosystem - an R package automating the transformation and standardization of raw clinical study data into the CDISC SDTM standard:
{{< github repo="pharmaverse/sdtm.oak" showThumbnail=false >}}

An interactive R/Shiny platform I co-developed for multidimensional exploration and visualization of multi-omic data (transcriptomics, proteomics, metabolomics):
{{< github repo="JagGlo/playOmics" showThumbnail=false >}}

An open-source R package and microservice developed at Transition Technologies Science for reproducible, auditable, and secure patient randomization - an engine deployed as the randomization module in, among others, the Medical Research Agency's (ABM) eCRF platform supporting dozens of clinical trials:
{{< github repo="ttscience/unbiased" showThumbnail=false >}}

An early project from my time at SWPS University conceived specifically for non-researchers: the curious mayor, village head, or investigative journalist - a web GUI for R enabling sound data analysis without needing a statistician on call:
{{< github repo="pich/WebiR" showThumbnail=false >}}

> [!TIP]
> For citation metrics, full co-author lists, and complete bibliographies, visit my [Google Scholar](https://scholar.google.com/citations?view_op=search_authors&mauthors=Kamil+Sijko) profile and [ORCID (0000-0002-2203-1065)](https://orcid.org/0000-0002-2203-1065).
