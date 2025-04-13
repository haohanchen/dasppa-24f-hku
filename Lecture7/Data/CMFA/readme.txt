Summary of the repository (v4; 13 January 2024)

The repository contains the Chinese Ministry of Foreign Affairs Press Conferences Corpus (CMFA PressCon) and covers the period between 15 October 2002 and 31 December 2023 (v4). 

CMFA_PressCon_v4.xlsx
	-	The corpus consists of 30 964 question/response dyads stored in an Excel file (UTF8 encoding). Data points are ordered by date. Each dyad is accompanied by the name of the speaker 			holding the press conference as well as the lemmatized versions of both the question and the given response. To facilitate further research, named entities identified in both questions 		and responses (using Flair library) are listed per dyad. See the codebook for further details.

CODEBOOK_CHFA_PressCon_v4
	-	Codebook in PDF format.

CMFA_PressCon_annotated_corpus_questions_v4.RDS
CMFA_PressCon_annotated_corpus_responses_v4.RDS
	-	The main corpus file is accompanied by two corpus datasets with full annotations (CoNLL-U format) of the collected question and answers stored in R’s native RDS files. See Trankit's 			GitHub page for details on the toolkit's modules (https://github.com/nlp-uoregon/trankit).
