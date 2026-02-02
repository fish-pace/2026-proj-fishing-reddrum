# 2026-proj-fishing-reddrum

## Project Name

Red Drum habitat: Fish distribution and investigation into environmental drivers using PACE

## Project Details

**One-line Description:** Use PACE data to infer drivers of red drum habitat

**Goal:** Map red drum tag data with PACE variables, calculate statistics and time series

**Slack Channel:** **proj-fishdrum**

**Pitch Slide:** [Project 5 Fishery productivity, marine animal habitat: their distribution and their drivers](https://docs.google.com/presentation/d/12q0pR__0EPRSHUYNb3KnKEOb08HT4t3K/edit?slide=id.g3b8a1a82a8e_0_195#slide=id.g3b8a1a82a8e_0_195)

**Final presentation:** [Red Drum habitat: Fish distribution and investigation into environmental drivers using PACE (PDF)](https://drive.google.com/file/d/1pQ2yQgXNpXvhm95677x-1XGrc1-goB1M/view)

## Collaborators

| Name                | Role                |
|---------------------|---------------------|
| Ted Chia       | Temperature, GitHub |
| Retno Septiani       | PACE Level 2, matchups for statistics |
| Ayeshmantha Andagala       | PACE Level 3       |
| Jeniffer De Maligaya      | Time Series, Statistics    |
| Ron Vogel       | Documentarian        |

## Folder Structure

* `contributor_folders` 
  + **Retno:** Code for 1) PACE Level 2 monthly AOP and BGC maps indicating red drum locations, 2) matchup red drum locations with AOP and BGC data and output spreadsheet for statistical calculations
  + **Ayeshmantha:** Code for PACE Level 3 weekly and monthly chlorophyll maps indicating red drum locations
  + **Ted:** Code for MODIS-Aqua Level 3 monthly temperature maps indicating red drum locations
* `final_notebooks`
  + Final notebooks of Ted and Ayeshmantha
* `data`
  + We did not make the red drum data public due to the source researcher not having published the data yet.

## Datasets

* Fish data: We used Red Drum acoustic tag data. The data are weekly averaged pings at the acoustic receivers for 12 individual red drum fish. The primary location of the receivers is Chesapeake Bay. For questions about the data, contact [Wilmelie.Cruz@noaa.gov](Wilmelie.Cruz@noaa.gov).

* PACE Data:
  * Level 2: granules averaged within 5-day window around given week of red drum detections
    + AOP: Aparent Visible Wavelength
    + BGC: Chlorophyll, Phytoplankton Carbon, Particulate Organic Carbon
  * Level 3: Chlorophyll, 4km, 8-day and monthly

* MODIS-Aqua Data:
  * Level 3: Temperature, 4km, monthly

## Workflow/Roadmap

* See Methods slides in final presentation

## Results/Findings

**See final presentation for additional detail**

* In summer, red drum cluster in the north where chlor-a is high
  + Perhaps due to food availability
* In fall, chlorophyll decreases and red drum detections spread out spatially 
  + Perhaps due to lower food availability and colder temperature 
* In winter, red drum decrease in detections
  + Perhaps due to migration out of the bay or mortality (natural, catch, or by-catch)
* BUT, the red drum detections have higher correlation with POC than Chlor-a which may suggest that POC has higher influence in the red drum habitat preference.

## Emerging Hypotheses

* Do red drum move seasonally within Chesapeake Bay based on food availability, as suggested by temporal and spatial patterns in Chlor-a and POC at the detection locations?
* AVW may be a good discriminator of red drum location:
  + Detections cluster around 550 nm.
  + Detections occur in regions of higher AVW (>500 nm) regardless of season, even though Chlor-a and POC vary seasonally at these detection locations.

