# GA Capstone Research Topics

#### Preliminary research for my GA DAI Capstone Project, exploring possible topics and relevant datasets

---
## Table of Contents:
- .gitignore - feel free to gitIgnore this! I won't mind.
- README.md - you are here! Hi!
- data_dictionary.txt - relevant data labels
- eda_linguistics.ipynb - jupyter notebook EDA of linguistic data
- eda_space.ipynb - jupyter notebook EDA of space topic
---
## Notes:

### Linguistics: 
- some uncommon/non ASCII characters have to be dealt with
- will have to scrape from UNESCO for # of speakers and status (cannot find in glottolog yet but I KNOW it's there)
- data for revitalization (unsure if I can find it)
- [Grambank](https://grambank.clld.org/)
- [Glottolog](https://github.com/glottolog/glottolog/tree/master)
- [CLDF](https://cldf.clld.org/) - Cross-Linguistic Data Formats
- glotto has huge data set compared to gram, but lots of missing countries & dates of doco missing


languages=pd.read_csv(filepath_or_buffer='.\data\glottolog_cldf\cldf\languages.csv')
#profile=ProfileReport(languages, title='languages.csv Profiling Report')
languages.head()