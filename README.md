# Citation-Driven Improvements in Information Retrieval: A TREC COVID Exploration

The primary objective of our research is to explore ways to enhance information retrieval systems using 
citation analysis and that leads us to our central research question, driving this study: whether 
augmenting the corpus with citations could lead to an improvement in the retrieval score obtained 
through the OKAPI BM25 system. 

# Reasearch Question
Can enriching the corpus with citations improve the baseline score of Information Retrieval?

# Evaluation 
TREC_EVAL evaluation framework has been used.
From this tool, we get the result parameters, such as
·        ndcg@20 
·        MAP 
·        p@20
·        Bpref

# Findings
•	Citations consistently enhance bpref, indicating added context improves retrieval systems identification and ranking.
•	MAP, p@20 scores vary across citation contexts. Some improve precision; broader contexts may challenge performance.
•	Adding a lower boundary in normalization harms retrieval. Top-performing corpus lacks it. Duplicating citations compromises the quality.
•	Incorporating citations boosts system performance, particularly NDCG20, with optimal window size and normalization.

# Future Work: 
•	Fine-tuning models
•	Exploring different normalization techniques
•	Improving Scalability and Efficiency
•	Incorporating advanced Machine Language techniques


