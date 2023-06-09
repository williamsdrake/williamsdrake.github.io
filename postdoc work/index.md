---
title: Current Research
nav:
  order: 1
  tooltip: Current Research
---

# <i class="fas fa-flask"></i>Core Research Areas

{% include section.html %}
## <i class="fas fa-bacteria"></i> Probing host‑microbe interactions in the oral mucosa 
{% include section.html %}
### Antigen-specific T cell responses at the oral barrier
{% capture text %}
Broadly, we are interested in the delicate interplay between host cells and microbes in barrier tissue. Relatively little is known how host cells respond to specific bacterial antigen and non-specific bacterial stimuli at the oral barrier.
We are generating the following tools in order to understand how antigen-specific responses to oral microbes contributes to disease pathogenesis:
- transgenic and retrogenic mice expressing a T cell receptor that recognizes *Aggregatibacter actinomycetemcomitans (Aa)*
- MHC tetramers that identify *Aa*-specific T cells

We will use these tools to:
- understand antigen-specific T cell response to oral pathogens in the oral mucosa
- study the role of oral pathogens in peripheral disease

Additionally, we will utilize the tool development pipeline to study the role of commensal microbes in oral mucosal homeostasis and disease. 
{% endcapture %}

{%
  include feature.html
  image="images/research_tcell.png"
  link=""
  headline=""
  text=text
%}

{% include section.html %}
### Improved identification of disease-associated oral microbes
{% capture text %}
Microbe relative abundance shifts do not necessarily indicate a causal role in disease pathogenesis. However, antibody response to microbes may better identify microbes that confer protection and/or microbes that enhance disease pathogenesis. 

Thus, we are applying culture-independent flow-cytometry-based oral microbe cell sorting and 16S/ITS sequencing to characterize the anti-microbiota IgA/IgG repertoire in severe human periodontitis
{% endcapture %}

{%
  include feature.html
  image="images/research_igg.png"
  link=""
  headline=""
  text=text
%}

### Related publications

{% include list.html data="citations" component="citation" filters="stage: pd, project: hostmicro" %}

{% include section.html %}

## <i class="fas fa-laptop-medical"></i> Molecular architecture and deep immunophenotyping of the oral barrier 
{% capture text %}
We employ a systems biology approach to better understand homeostasis at the oral barrier, and importantly, how homeostasis is disrupted in inflammatory disease (periodontitis).
We are actively working to expand our understanding of processes that govern disease using a combination of next generation single cell and histology approaches, including: 
 - spatial transcriptomics
 - spatial proteomics
 - multi-modal single cell sequencing 
{% endcapture %}

{%
  include feature.html
  image="images/research_omics.png"
  link=""
  headline=""
  text=text
%}

### Related publications

{% include list.html data="citations" component="citation" filters="stage: pd, project: atlas" %}




{% include section.html %}
## <i class="fas fa-syringe"></i> Mucosal immunity in mendelian disease
{% capture text %}
The Moutsopoulos Lab sees several cohorts of patients that have single gene mutations which lead to severe oral disease. Using single cell sequencing, we are assessing how experimental treatment influences cell composition and gene expression in:
- patients with a gain-of-function mutation in *Stat1*, which causes chronic mucocutaneous candidiasis and severe oral ulcers
- patients with leukocyte adhesion deficiency 1 (LAD1), which causes severe gingival immunopathology leading to early-life tooth loss
{% endcapture %}

{%
  include feature.html
  image="images/benchBed.png"
  link=""
  headline=""
  text=text
%}