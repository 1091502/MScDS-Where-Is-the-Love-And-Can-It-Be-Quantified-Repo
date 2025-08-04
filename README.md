
**Last updated:** Monday, August 4th, 2025

## Overview

This repository contains the research materials for the Master's thesis:  
*"Where Is the Love?" (And Can It Be Quantified?): A Network-Topic Discourse Analysis of Romance in Popular Music*

## Contents

/MSc-Dissertation/
├── Love Song Analysis Script.ipynb
├── BERTopic_Script.ipynb
├── processed_love_song_dataset_FINAL.csv
└── README.md

- **`Love Song Analysis Script.ipynb`**  
  Contains Python code to run the main analyses used in the study, including lyric preprocessing, topic modelling (LDA), generational segmentation, and a network analysis of songwriting credits.

- **`BERTopic_Script.ipynb`**  
  Alternative topic modelling (BERTopic) used for comparison. This was written and executed in Google Colab.

- **`processed_love_song_dataset_FINAL.csv`**  
  The core dataset containing preprocessed lyrical and metadata used in the analysis.

---

## Reproducibility

- The code notebooks provide a full processing pipeline.
- The topic modelling scripts include reproducibility measures such as fixed random seeds.

- Researchers can reproduce the study:
  1. Similarly by legally obtaining lyrics and preprocessing them as shown in the notebook.
  2. & Exactly by running the notebooks on the provided dataset.


---

## Basic Usage

1. **Load the Data**  
   - Use the included CSV file with preprocessed lyrics, metadata, and credits.  
   - Adjust file paths as needed for your environment.

2. **Run the Analysis**  
   - Execute the notebook cells in sequence to perform the full analysis pipeline.  
   - This includes topic modelling by generation and co-credit network construction.  
   - Visualisations will appear inline or be saved as HTML files.

3. **Optional**  
   - Run `BERTopic_Script.ipynb` for additional topic modelling output.

 More detailed explanations are included in comments throughout the notebooks.

---

## Dataset Description & Licensing

The dataset includes:

| Column             | Description                                  | Source & Licensing                     |
|--------------------|----------------------------------------------|----------------------------------------|
| Song_Title         | Title of the song                            | last.fm API (non-commercial use only)  |
| Artist             | Artist or band name                          | last.fm API(non-commercial use only)   |
| Processed_Tokens   | Lemmatised, anonymised lyric tokens          | lyrics.ovh (preprocessed; fair use)    |
| Release Year       | Song release year                            | MusicBrainz (open source)              |
| Standardised Genre | Genre (standardised form)                    | Wikipedia (CC BY-SA 4.0)               |
| Writers            | Songwriting credits                          | Wikipedia (CC BY-SA 4.0)               |
| Producers          | Production credits                           | Wikipedia (CC BY-SA 4.0)               |

> • Lyrics were pulled via the lyrics.ovh API and preprocessed to ensure non-reconstructability and fair use.  
> • Wikipedia-sourced content is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). - information falls under fair use. 
> • last.fm API terms: Non-commercial use only ([link](https://www.last.fm/api/tos)).
> • MusicBrainz is a community-maintained open source encyclopaedia of music information.

---

## Terms of Use

- The dataset is provided for personal and academic use only.
- Lyrics are non-reconstructable.
- Redistribution or commercial use is prohibited without explicit permission.
- Use of this dataset implies acceptance of these terms.

---

## AI Assistance Acknowledgment

Sections of the analysis code were developed with support from OpenAI's ChatGPT (GPT-4).  
AI contributions included code drafting, debugging, and explanatory guidance. All final implementation choices and interpretations are my own.

---

## Citation (placeholder until after marking) 

If you use this code or dataset in your research, please cite the original thesis or include the following note:

> Code and dataset adapted from: [Author's Name] (2025), Where Is the Love? (And Can It Be Quantified?):A Network-Topic Discourse Analysis of Romance in Popular Music, Master's Thesis, University of Oxford.
(Currently anonymised for marking purposes, to be altered once marked)

