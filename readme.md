# How does insect richness in Connecticut correlate with temperature and precipitation over time?

## Project Statement: 
Insects, particularly beetles (Coleoptera), butterflies (Lepidoptera), and bees (Apidae), are important pollinators and predators, contributing to food security
and ecosystem stability. Populations have declined over recent decades, thus we seek to assess the relationship between climate changes and insect species richness.

## Hypothesis:
Changes in temperature and precipitation over the past 50 years have significantly influenced the distribution and population density of Nymphalidae species in Connecticut.

## File Manifest
* 01_Precipitation_data.ipynb
  * download, clean, and summarize NOAA precipitation data
* 02_temperature_data.ipynb
  * download, clean, and summarize NOAA temperature data
* 03_ypm_insect_downloading_cleaning.ipynb
  * download, clean, and summarize Peabody insect data via GBIF
* 04_climate_insects_analyses_figures.ipynb
  * join climate and insect data, analyze relationships, make plots
* 05_insect_spatial_analysis.ipynb
  * map US-level insect data patterns
* noaa_precip_yearly_ct.csv
  * summarized yearly precipitation data for CT
  * output from 01_Precipitation_data.ipynb
  * input to 04_climate_insects_analyses_figures.ipynb
* temp_data.csv
  * all temperature data for CT
  * input to 02_temperature_data.ipynb
* temp_summary.csv
  * summarized yearly temperature data for CT
  * output from 02_temperature_data.ipynb
  * input to 04_climate_insects_analyses_figures.ipynb
* ypm_ent_taxo_summaries_20250424.csv
  * summarized US-wide insect data
  * output from 03_ypm_insect_downloading_cleaning.ipynb
  * input to 05_insect_spatial_analysis.ipynb
* ypm_ct_ent_taxo_summaries_20250418.csv
  * datasheet with number of species for all insects (total_richness), Lepidoptera (butterflies), Coleoptera (beetles), Nymphalidae (brush footed butterflies), Papilionidae (swallowtail butterflies), Apidae (bees), and Noctuidae (owlet moths) from 1900-2024.
  * output from 04_climate_insects_analyses_figures.ipynb
* CT_insect_climate_data.csv
  * joined climate and insect data for each year in CT
  * output from 04_climate_insects_analyses_figures.ipynb

## Original Datasets: 
YPM Insects: https://www.gbif.org/dataset/96404cc2-f762-11e1-a439-00145eb45e9a/activity \
NOAA: https://www.ncei.noaa.gov/cdo-web/datasets \
US Census Data (for state boundaries): https://github.com/envirodatascience/ENVS-617-Class-Data/raw/main/tl_2020_us_state.zip \

## Other Links: 
Link to Presentation slides: https://docs.google.com/presentation/d/1MQ6CyFeu4wIqnG13GZFW3jJMG89N_2ru/edit?usp=sharing&ouid=112633141429842355591&rtpof=true&sd=true \
Link to Google Doc (group project notes): https://docs.google.com/document/d/1qb_u7YNPmGLWlOS4u_9a4-hSig6mMN954YvEJOMVJAU/edit?usp=sharing
