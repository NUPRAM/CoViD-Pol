# CoViD-Pol
Collections on Vaccination Discourse by Politicians

## Content

We made available the following output from our annotation system:


### Covid-Pol Corpus V.2.0 (2025)

- **Covid-Pol_Corpus_v2.0.csv**: The final corpus in Brazilian Portuguese with stance, sentiment, and relevance annotations after considering the majority of annotators, also indicating the tweet ID and date of the post.
  - `relevant`: The value `False` indicates that the tweet, even though it contains the keywords used in the search, is not related to COVID-19 vaccines. `True` indicates that it is related to COVID-19 vaccines.
  - `final_stance`: Stance column, contanining three categories: favorable, unfavorable, and unclear towards COVID-19 vaccines.
  - `final_sentiment`: Three categories: positive, negative, and unclear. Sentiment was annotated considering the overall sentiment expressed in the text, not in relation to COVID-19 vaccines.
  - `final_children`: Indicates if the tweet is related to vaccination in children. `false` indicates no relation, and `true` indicates that the tweet is about children's vaccination.

- **Codebook v.2.0 (2025)**: We also provide the codebook with information on the dataset building process, classification rules, and some additional content.

- **NLP4DH (2025) Presentation Slides and Article**: Additionally, we include the slides of the NLP4DH presentation (May 3-4, 2025) and the Accepted article on the subfolder `NLP4DH (2025)`.


### Covid-Pol Corpus V.1.0 (2023)



- **Covid-Pol_Corpus_v1.0.csv**: The final corpus in Brazilian Portuguese with stance and relevance annotations after considering the majority of annotators, also indicating the tweet ID and date of the post.

  - `post_vaccine`: For the post_vaccine column, the value 0 indicates that the tweet, even though it contains the keywords used in the search, is not related to Covid-19 Vaccines. 1 indicate that it is related to Covid-19 vaccines.
  - `final_stance`: For the positions_vac column, 1 indicates a tweets that is favourable towards Covid-19 vaccines, 2 indicates that it is neutral towards these vaccines and 3 indicates the unfavourable tweets.

- **Codebook v.1.0 (2023)**: We also provide the codebook with informations on the dataset building process, classification rules and some additional content for this first version of the corpus.

- **STIL (2023) Presentation Slides and Article**: Additionally, we include the slides of the NLP4DH presentation (October, 2023) and the Accepted article on the subfolder `STIL (2023)`.








## Related Articles

1. **Barberia, L., Schmalz, P., Roman, N. T., Lombard, B., & Sousa, T. C. M. (2025)**  
   *It's about What and How you say it: A Corpus with Stance and Sentiment Annotation for COVID-19 Vaccines Posts on X/Twitter by Brazilian Political Elites.*  
   In Proceedings of the 5th International Conference on Natural Language Processing for Digital Humanities (NLP4DH 2025).  
   Available at: [https://aclanthology.org/2025.nlp4dh-1.32/](https://aclanthology.org/2025.nlp4dh-1.32/)

2. **Barberia, L. G., Schmalz, P. H. S., & Roman, N. T. (2023)**  
   *When Tweets Get Viral - A Deep Learning Approach for Stance Analysis of Covid-19 Vaccines Tweets by Brazilian Political Elites.*  
   In: Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana (STIL), 14., 2023, Belo Horizonte/MG.  
   Anais [...]. Porto Alegre: Sociedade Brasileira de Computação, 2023. p. 104-114.  
   DOI: [https://doi.org/10.5753/stil.2023.233961](https://doi.org/10.5753/stil.2023.233961)

---

## Acknowledgments and Partnerships

This research project was made possible by grant support from the José Luiz Egydio Setúbal Foundation (JLES). In addition, the authors acknowledge support from the Center for Artificial Intelligence of the University of São Paulo (C4AI - [http://c4ai.inova.usp.br/](http://c4ai.inova.usp.br/)) and its supporting grants from the São Paulo Research Foundation (FAPESP grant #2019/07665-4) and the IBM Corporation. The project was also supported by the Ministry of Science, Technology and Innovation, with resources of Law N. 8.248, of October 23, 1991, within the scope of PPI-SOFTEX, coordinated by Softex and published as Residence in TIC 13, DOU 01245.010222/2022-44.

---

## License

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a  
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/  
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png  
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
