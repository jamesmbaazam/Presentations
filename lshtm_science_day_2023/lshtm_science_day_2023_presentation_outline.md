# Tooling outbreak response analytics (the _Epiverse_ Initiative by data org)

## Introduction

- Rapid analytics to support outbreak response decision-making is enhanced by ready, stable, and reliable software.
- There's lots of R packages for outbreak analytics but mostly lacking visibility, coherence, and continuity
- Need for initiatives to champion development of coherent, reproducible, and reliable software for epidemiological modelling, particularly, outbreak response decision-making
  
## Epiverse TRACE initiative

Aims to:

- support existing efforts (WHO's goData, harmonizing social contact matrices, etc)
- develop new ones (finalsize, epiparameter, episoap, etc); recall recent showcase
- provide an ecosystem 
  
## Epiverse (cont'd)

- Epiverse TRACE is organized/managed internally with so-called pillars/themes.
- Pillar 2 (real-time analysis):
  - Existing tools: EpiNow2, epinowcast, EpiEstim, epidemia, etc.

### An example: \{*bpmodels*}

- Originally developed by Seb Funk (LSHTM)
- Simulates branching processes for answering questions around:
  - Sizes and lengths of clusters 
  - Population-level transmissibility and individual heterogeneities in transmission (superspreading)
  - Useful during early phase of an epidemic
  - Example applications during COVID-19:
    - Projecting COVID-19 cases in Africa: Pearson et al, 2020.
    - R0 and superspreading of COVID-19 in China: Abbott et all, 2020.
  - **Current work**: improving docs, refactoring, stabilizing, etc. 

#### Ways to contribute to {bpmodels}

- Use cases
- Vignettes
- User experience
- Code base
- Language translations??
- Next steps: submission to CRAN, plan for major release, etc

## Ways to contact/contribute to Epiverse

- Website: <https://data.org/initiatives/epiverse>
- Github org: <https://github.com/epiverse-trace>
- Pitcher: <https://github.com/epiverse-trace/pitcher/discussions>

## Conclusion

- To response quickly to outbreaks, we need ready tools
- Epiverse seeks to contribute to this effort by proving a collaborative system that supports and initiates creations of needed tools
- {bpmodels} is an example of an existing package being improved and maintained in readiness.
- Ask how you can contribute to Epiverse TRACE
- Questions?? 
