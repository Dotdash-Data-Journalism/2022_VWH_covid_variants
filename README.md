# COVID-19 Variant Proportions Tracker

This repository contains the code & data that powers two [Datawrapper](https://www.datawrapper.de/) charts on the prevalence of COVID-19 variants in the US for [Verywell Health](https://www.verywellhealth.com/covid-variants-timeline-6741198). CSVs for each chart are in the `visualizations` folder and the YAML file `cdc_covid19_variant_runner.yml` in the `.github/workflows` file updates the [CDC variant data](https://covid.cdc.gov/covid-data-tracker/#variant-proportions) via the [Socrata API](https://data.cdc.gov/Laboratory-Surveillance/SARS-CoV-2-Variant-Proportions/jr58-6ysp) every Saturday via the [Datawrapper API](https://developer.datawrapper.de/reference/introduction).






