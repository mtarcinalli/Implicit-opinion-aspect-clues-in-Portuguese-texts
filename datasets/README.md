

Each file in this directory presents sentences and aspects related to a different domain (camera, hotel, book and smartphone).

The files are in csv format, using tab as a separator. Where:

- The first column indicates the sentence number

- The second introduces the word.

- The third is the classification obtained by the POS-tagger (spaCy using the pt_core_news_lg model)

- The fourth column the aspect indicator in IOB format (short for inside, outside, beginning), where:
    - B-asp: beginning of an aspect
    - I-asp: inside of an aspect
    - O: outside of an aspect



Sentence #	Word	POS	Tag
Sentence: 1	Vale	VERB	O
	a	DET	O
	pena	NOUN	O
	cada	DET	B-asp
	centavo	NOUN	I-asp
	investido	VERB	I-asp
	nesta	ADP	O
	máquina	NOUN	B-asp
	.	PUNCT	O
Sentence: 2	O	PRON	O
	que	PRON	O
	gostei	VERB	O
	:	PUNCT	O
	Excelente	ADJ	O
	qualidade	NOUN	O
	da	ADP	O
	imagem	NOUN	O
	;	PUNCT	O
	Bonita	PROPN	O
	;	PUNCT	O
	Fácil	PROPN	O
	manuseio	NOUN	B-asp
	.	PUNCT	O