\|---------------------------------------------------------------------------------------------------------------------\|

#### **Project Title:** Shape, Duration, and Location: UFO Sightings in the United States from 1950 to 2019

#### **Author:** Kyle Langille

\|---------------------------------------------------------------------------------------------------------------------\|

### Project Overview

This is an independent study project for ACENET's Microcredential in Advanced Computing program.

This project analyzes reported UFO sightings from 1950 to 2019 in the United States (US). This analysis will be threefold:

- Determine the most commonly reported shapes of UFOs (disk, sphere, etc.)
- Explore the geographical distribution of reported sightings to determine sighting density “hotspots”
- Explore the reported durations of UFO sightings to determine typical or outlier durations

As UFO disclosures are becoming more common in the public record and open discussions of UFO sightings are thereby progressively becoming less “taboo,” it is important to have an understanding of the historical record of previously reported UFO events.

### Data

The data for this project is sourced from the following dataset, sourced from sightings reported to NUFORC.org, which have been scraped by Thaddeus Segura. Mr. Segura compiled and cleaned this dataset and has hosted it on KAGGLE.org at the following URL: https://www.kaggle.com/datasets/thaddeussegura/ufo-sightings?resource=download

Although the dataset includes data from outside the US, such entries are sparse and the dataset as a whole maintains a strong US focus. The dataset contains reported sightings dating back to 1899, though the data from these earlier time periods are often incomplete, and as such I will focus my analysis starting in 1950 as entries from this year onwards are much more consistent.

Columns of importance for this analysis are:

- Shape
  - For determining most commonly reported UFO shape
- Duration
  - For determining most commonly reported sighting duration as well as outlier durations
  - As the dataset includes varying measures of duration (seconds, minutes, etc.), effort will be taken in the "sanitization" stage of the project to standardize the duration for cohesive analysis
- State
  - For determining geographic sighting density "hotspots"
