# [TITLE]

## About

This is the official repository for the research paper *"[TITLE]"*. The work addresses automated methods of detectin usability problems. Systematic literature review is conducted on the topic, revealing different research areas, approaches, usage of artificial intelligence and participants in research publications from years 2014 - 2024.

### Paper citation

Not published yet.

### Contents

* [Data](#data)
* [Scripts](#scripts)
* [Extended results](#extended-results)
* [Authors](#authors)
* [License](#license)

## Data

[Final dataset](./data/dataset.csv) of publication sources contains 132 research publications, bibliographic data and relevant extracted data fields:
- *key:* unique identifier
- *title*
- *author*
- *year*
- *type:* either journalArticle, conferencePaper or preprint
- *volume*
- *issue*
- *pages*
- *journal:* journal or conference
- *journalShort:* abbreviation of the conference
- *publisher*
- *doi*
- *url*
- *abstract*
- *keywords*
- *citedBy:* number of citation on Google Scholar
- *quality:* journal quartile or conference rank
- *area:* tagged research area
- *subArea:* tagged research subArea
- *approach:* tagged automation approaches used in the publication
- *AI:* tagged AI usages used in the publication
- *AIsub:* tagged AI subcategory
- *data:* tagged data sources utilized in the publication
- *participants:* whether the approach utilizes participants

Lietrature/tool review publications as well as interviews or survey publications are available [in the data directory as well](./data/reviews.csv).


## Scripts

See below for guidelines on configuring the virtual environment used for data analysis, an explanation of key scripts found in the file structure and resulting files.

### Environment

All of the scripts located in the analysis folder are written using Python (version 3.12.1) and other external libraries installed using pip (version 23.2.1). Scripts were executed using jupyter notebooks in VS Code. A [requirements file](./analysis/requirements.txt) is provided for installing dependencies. After installing Python, the below commands can be used in the analysis directory to install the environment:

```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

On macOS devices, this process could be slightly different:

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

This will create your virtual environment and install the dependencies. After the installation, notebooks could be executed in any available IDE (IDEs such as VS Code, in which the environment could be even installed automatically) or using the built-in web environment using this command in the command line (while having activated the virtual environment using .venv\Scripts\activate or source .venv/bin/activate):

```
jupyter notebook
```

### Files

Following files are present in the [analysis directory](./analysis):
- [analysis.ipynb](./analysis/analysis.ipynb)
- [tests.ipynb](./analysis/tests.ipynb)


## Extended results



## Authors

### General contact 

Email: 
**[EMAIL]**


**Eduard Kuric**\
He is a researcher and lecturer at [Faculty of Informatics and Information Technologies](https://www.fiit.stuba.sk/), [Slovak University of Technology in Bratislava](https://www.stuba.sk/). His research interests include human-computer interaction analysis, user modeling, personalized web-based systems, and machine learning. Eduard is also the head of the UX Research Department and the founder of [UXtweak](https://www.uxtweak.com/).
- [LinkedIn](https://www.linkedin.com/in/eduard-kuric-b7141280/)
- [Google Scholar](https://scholar.google.com/citations?user=MwjpNoAAAAAJ&hl=en&oi=ao)
- Email: eduard.kuric([AT])stuba.sk

**Peter Demcak**\
Researcher with background in software engineering, whose current topics of interest involve user behavior, human-computer interaction, UX research methods and design practices, and machine learning. Currently occupies the position of a scientific and user experience researcher at [UXtweak](https://www.uxtweak.com/), with focus on research that supports work of UX professionals.

- Email: peter.demcak([AT])uxtweak.com

**Matus Krajcovic**\
User experience researcher at [UXtweak](https://www.uxtweak.com/) and computer science student at [Faculty of Informatics and Information Technologies](https://www.fiit.stuba.sk/), [Slovak University of Technology in Bratislava](https://www.stuba.sk/). Currently focuses on data analysis and research in machine learning use in the field of human-computer interaction.
- [LinkedIn](https://linkedin.com/in/matus-krajcovic)
- Email: matus.krajcovic([AT])uxtweak.com


## License
This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

[![Creative Commons License](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)