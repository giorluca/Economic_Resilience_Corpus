# Economic-Resilience-Corpus-ERC
<p align="justify">
‘Economic Resilience Corpus’ (ERC) is a collection of 307 English research papers on the concept of economic resilience published between 2019 and June 2024, written by 304 authors. The textual genre distribution is 100% academic, thus the communication typology is expert-to-expert. The data source for our corpus is CORE (Knoth et al., 2023), a comprehensive bibliographic database of the world’s scholarly literature and the world’s largest collection of full text open access research papers.
Each entry in the corpus contains a unique numerical identifier, the COREid, the title, the full text, the author(s), the year of publication, the abstract, the DOI (Digital Object Identifier), the language, the publisher and the title-text pair together.
</p>

![image](https://github.com/user-attachments/assets/bde1c15c-b9c6-4972-b69f-d0de3a36253c)

![image](https://github.com/user-attachments/assets/31ed0ae3-bfaf-483e-a083-60dfde46d46c)

_Data Preprocessing_
<p align="justify">
We make sure that the corpus contains no missing entries in both the title and text field. Then we drop 7 duplicate entries by title. We also append the titles to the beginning of the texts, separating them by two newline characters (‘\n’) in order to have all relevant textual data in the same string. Furthermore, we remove stopwords (e.g., ‘and’, ‘or’, ‘of’), as non-informative, functional and very common words which carry minimal semantic relevance can obscure potential interesting and meaningful patterns in content analysis3. Finally, for enhanced compatibility with the textual analysis toolkit, we export each preprocessed title-text pair in separate plain text format (.txt) files. 
</p>
