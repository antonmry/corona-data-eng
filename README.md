### Context

[Coronadatascraper](https://github.com/lazd/coronadatascraper) project exists to scrape, de-duplicate, and cross-check county-level data on the COVID-19 coronavirus pandemic.

Every piece of data produced includes the URL where the data was sourced from as well as a rating of the source's technical quality (completeness, machine readability, best practices -- not accuracy)..

- Website: [Corona Data Scraper](http://blog.lazd.net/coronadatascraper/#home). Download data and view sources
- GitHub: [Corona Data Scraper](https://github.com/lazd/coronadatascraper). Help write scrapping rules. See Readme
- Google Doc: [COVID-19 Community Data Collection](https://docs.google.com/spreadsheets/d/1T2cSvWvUvurnOuNFj2AMPGLpuR2yVs3-jdd_urfWU4c/edit#gid=0). Help us acquire valid, official data sources on all levels: County, State, Country
- Slack: [SARS-CoV-2:COVID-19](https://join.slack.com/t/sars-cov-2covid-19/shared_invite/zt-cr6ln0ph-6eDATfSUNDtFK3mlQxqYKw). First [Join](https://join.slack.com/t/sars-cov-2covid-19/shared_invite/zt-cr6ln0ph-6eDATfSUNDtFK3mlQxqYKw), then go to the Slack

### How it works?

The COVID-19 dataset is upgraded periodically and uploaded to Kaggle using Databricks notebooks:

- [Databricks coronadatascraper Notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5083922891908052/469897532896452/2904401718056930/latest.html): install `coronadatascraper` and download the COVID-19 dataset.
- [Databricks Kaggle Notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5083922891908052/2568995183456180/2904401718056930/latest.html): upload the COVID-19 dataset to [Kaggle](https://www.kaggle.com/).
- [Kaggle Dataset](https://www.kaggle.com/antonmry/covid19): updated and versioned.
- [Github Project](https://github.com/antonmry/corona-data-eng)

### Content

- [Metadata for Coronavirus Data Scraper](https://github.com/CoronaVirusDataTeam/docs/blob/master/metadata.md)
- [Document output data format](https://github.com/lazd/coronadatascraper/issues/49)

### Acknowledgements

- [CSSEGISandData](https://github.com/CSSEGISandData/COVID-19/issues/558)
- [coronadatascraper](https://github.com/lazd/coronadatascraper)

