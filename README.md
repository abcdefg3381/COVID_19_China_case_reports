# COVID-19 Case Reports in China

This project holds the data curated from daily COVID-19 case reports that are publicly disclosed by local health committees in China outside Hubei Province, starting January 2019.

## A brief description

Chinese prefectural level governments started to report daily confirmed COVID-19 cases online, starting from January 2020. The disclosures may contain the mobility, potential exposure scenario, epidemiological characteristics, and other useful information of individual cases. We organized a group of content coders since early March 2020, kept monitoring the information updates, manually extracted useful information from the public disclosures, and compiled these datasets.

We welcome any form of collaborations with us and non-commercial reuse of our dataset. We highly encourage interested parties to examine the data, report errors in our coding, and help us to keep the data updated.

The detailed data description can be found on [Scientific Data](https://doi.org/10.1038/s41597-021-00844-8).

## File name explanation

* **data_sources.csv:** the URLs to online disclosure venues.

* **dataset EN.csv:** coded information in English.

* **reasons_for_missing_data.csv:** The reasons for missing cases in some prefecturals.

## Suggested citation
Liu, X.F., Xu, XK. & Wu, Y. Mobility, exposure, and epidemiological timelines of COVID-19 infections in China outside Hubei province. Sci Data 8, 54 (2021). https://doi.org/10.1038/s41597-021-00844-8

## Automated information extraction using NLP models
Manual data curation has been costly in the past two years. In fact, these repetitive works can be and should be automated with artificial intelligence. Dr Yuanyuan Sun and her student Mr Zhizheng Wang from Dalian University of Technology collaborated with us and developed a deep-learning based text anaysis framework to extract the information from natural language written texts. Case reports since 2022 are curated with the help of this framework. The code and model are also shared through our repository. 

## Suggested citation
TBA
## License
This project is licensed under the terms of the Creative Commons Attribution 4.0 International (CC BY 4.0) license. View license Deed https://creativecommons.org/licenses/by/4.0/deed.en and Legal Code https://creativecommons.org/licenses/by/4.0/legalcode.
