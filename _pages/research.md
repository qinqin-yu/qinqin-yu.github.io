---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
---

{% include base_path %}

<ins>Antigenic evolution in *Neisseria gonorrhoeae*</ins>

In 2020, there were an estimated 82 million new cases of gonorrhea (World Health Organization), a sexually transmitted infection caused by the bacterium *Neisseria gonorrhoeae*. Reinfections are common, due to gonorrhea’s multifaceted ability to evade the host immune system. Increasing incidence and antibiotic resistance have underscored the importance of developing a vaccine against gonorrhea and understanding the basis of its immune evasion.

One of the mechanisms by which *N. gonorrhoeae* evades the host adaptive immune system is through rapid variation of its surface antigens. One of the most abundant, diverse, and immunogenic surface antigens is Opa, a surface-adhesion protein that is encoded by multiple *opa* gene paralogs that undergo phase variation to rapidly switch expression. Standard short-read sequencing platforms (such as Illumina) are unable to capture gene paralogs; as such, we have had only a very limited understanding of *opa* diversity in *N. gonorrhoeae*. However, the development of accurate long-read sequencing technology provides an opportunity to characterize and define the *opa* repertoire and its evolutionary dynamics. I am generating new datasets, developing genomics approaches, and developing new frameworks to characterize and analyze *opa* sequence and antigenic evolution. We expect that the development of approaches to study antigenic diversity and evolution in Opa will be applicable to studying evolution of other antigens in *N. gonorrhoeae* as well as in other bacterial species that use similar immune evasion strategies.


<ins>Equity in wastewater-based epidemiology</ins>

Wastewater-based epidemiology is a promising public health tool that can yield a more representative view of the population of than standard case surveillance. However, almost 20% of the population in the United States is not connected to a sewer, with onsite collection and treatment through septic tanks being the most common alternative. Who is not connected to sewers and what impact does this have for the generalizabilty of wastewater data and analyses? To address these questions, we compiled and analyzed datasets from diverse sources at the national and state levels to shed light on the demographic, geographic, and socioeconomic characteristics of those not connected to sewers. 

We found that certain geographic locations, such as Alaska and the Navajo Nation, certain demographic groups, such as American Indian and Alaska Native, White, non-Hispanic, older populations, and larger households were less connected to sewers than average at the national level. However, zooming into smaller spatial scales revealed heterogeneities that emphaize the importance of a local approach to future equity analyses. Using mathematical modeling, we found that wastewater data can be generalized to neighboring unconnected communities in some situations, particuarly when the rate of interaction between the two communities is high, but that this sensitively depends on the relative population sizes of the two populations and the policy question. 

# PhD Research


Genetic drift is the change in a population’s composition due to the random nature of birth and death events. The strength of genetic drift directly impacts a population’s evolutionary trajectory by modulating the rate of diversity loss and the rate of adaptation.

<ins>Statistical inference of genetic drift from lineage frequenciesa</ins>  

Genetic drift in pathogen transmission occurs due to the randomness of transmission and recovery events. The strength of genetic drift in pathogen transmission impacts disease spread, disease extinction, emergence of new variants, and effectiveness of control measures. However, inferring the strength of genetic drift on a large spatiotemporal scale has been challenging due to the lack of systematic contact tracing data on this scale and measurement noise. 

In collaboration with Joao Ascensao from the Hallatschek lab, I developed a statistical inference approach to infer genetic drift in spreading pathogen populations. Our approach uses a Hidden Markov Model structure to infer the strength of genetic drift and measurement noise from lineage frequency time series data, which can be determined from time series genomic data. With decreasing costs and increasing capacity for genomic sequencing, genomic data is now avaialble at large spatiotemporal scales for pathogens such as SARS-CoV-2, HIV, Ebola, seasonal influenza. 

In collaboration with Takashi Okada, former postdoc in the Hallatschek lab, Erik Volz and Olivia Boyd from Imperial College London, we applied this approach to infer the strength of genetic drift in the transmission of SARS-CoV-2 in England over time and space. We found that the strength of genetic drift is up to 2 orders of magnitude higher than expected from the number of infected individuals. We speculated that superspreading and host population structure contributed to the elevated levels of genetic drift observed. The method that we developed will be most applicable to other systems with large datasets and long periods of sampling, such as the pathogens mentioned above, and also potentially ancient DNA and field studies. 

<ins>Evolution of genetic drift in microbial populations</ins>

Changes in strength of genetic drift in a population are conventionally thought to be due to changes in population size and to occur over long time scales. I expanded our understanding of genetic drift by discovering that in microbial colonies, single mutations can affect the strength of genetic drift over short timescales by altering colony morphology. This result suggests that genetic drift can be an evolvable trait of a population. In other words, mutations can affect not only fitness and mutation rate, but also the strength of genetic drift, and this effect in turn affects the evolutionary trajectory of the population.

In collaboration with Joao Ascensao, a graduate student in the Hallatschek Lab, I extended this study to well-mixed cultures, where we hypothesized that phenotypic stochasticity in single cell traits modulates the offspring number variance, which together with the population size determines the strength of genetic drift. We measured the offspring number variance in strains from the E. coli Long Term Evolution Experiment (LTEE) to assess changes in genetic drift over evolutionary time.

<ins>Interplay of self-organization and evolution in microbial biofilms</ins>

Biofilms are the most common form of microbial life and can be found in environments ranging from the human gut to thermal hot springs. Biofilms form complex spatial structures which are hypothesized to impact evolutionary dynamics.

However, we currently have an incomplete understanding of how complex structures, such as three-dimensional growth, cellular nematic ordering, and extracellular matrix production impact biofilm evolutionary dynamics. In collaboration with Hallatschek lab graduate students Aditya Prasad and Joao Ascensao and the lab of Dr. Na Ji, I developed experimental methods to interrogate the impact of biofilm structure on evolutionary dynamics. I developed a molecular system for inducing and visualizing synthetic mutations in *V. cholerae* biofilms. I also developed imaging and microfluidics techniques for studying the growth and structure of *V. cholerae* biofilms.

