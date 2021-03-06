# Implicit Aspect Clues in Portuguese opinion texts

![NILC - ICMC - C4AI](https://github.com/mtarcinalli/Implicit-opinion-aspect-clues-in-Portuguese-texts/blob/main/logos.png?raw=true)


In this repository we make available the files resulting from the papers: “Learning rules for automatic identification of implicit aspects in Portuguese” [1] and “Implicit opinion aspect clues in Portuguese texts: analysis and categorization” [2].

The data used in the experiments are found in the “datasets” directory. The camera, smartphone and books domains were obtained from the corpus elaborated by Vargas and Pardo [4] with small changes in the implicit annotation to enable the validation of the aspects extraction processes. The hotel domain was obtained from the corpus created by Freitas and Vieira [3], this corpus does not present the annotation of the Implicit Aspect Clues (IACs), a task that we detailed in our paper [2].

In the directory “lexico iacs” there is a xml file containing the mapping of implicit aspect clues for the respective aspects. The file was created based on the IACs found in the datasets. In the table below we present statistics related to the dataset and iacs lexicon.

![Statistics related to the dataset and iacs lexicon](https://github.com/mtarcinalli/Implicit-opinion-aspect-clues-in-Portuguese-texts/blob/main/table1.png?raw=true)

In the directory “tipologia” there is a csv file with the classification of the IACs resulting from our research [2]. In this work, we performed a categorization of the IACs aiming to identify the type of knowledge needed to recognize the related aspect. The table below presents a summary of the categories and subcategories found.

![Summary of the categories and subcategories found](https://github.com/mtarcinalli/Implicit-opinion-aspect-clues-in-Portuguese-texts/blob/main/table2.png?raw=true)

## Citing

[1] Mateus Tarcinalli Machado et al. “Learning rules for automatic identification of implicit aspects in Portuguese”. In:Anais do XIII Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana. SBC. 2021, pp. 82–91.


[2] Mateus Tarcinalli Machado, Thiago AS Pardo, and Evandro Eduardo Seron Ruiz. “Implicit opinion aspect clues in Portuguese texts: analysis and categorization”. In:International Conference on Computational Processing of the Portuguese Language. Springer. forthcoming.

## Bibtex

@inproceedings{machado2021learning,
 title={Learning rules for automatic identification of implicit aspects in Portuguese},
 author={Machado, Mateus Tarcinalli and Pardo, Thiago Alexandre Salgueiro and Ruiz, Evandro Eduardo Seron and Di Felippo, Ariani},
 booktitle={Anais do XIII Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana},
 pages={82--91},
 year={2021},
 organization={SBC}
}

@inproceedings{machado2022implicit,
 title={Implicit opinion aspect clues in Portuguese texts: analysis and categorization},
 author={Machado, Mateus Tarcinalli and Pardo, Thiago AS and Ruiz, Evandro Eduardo Seron},
 booktitle={International Conference on Computational Processing of the Portuguese Language},
 year={2022},
 organization={Springer}
}


## Other references

[3] L. A. d. Freitas and R. Vieira. “Exploring Resources for Sentiment Analysis in Portuguese Lan-guage”. In:2015 Brazilian Conference on Intelligent Systems (BRACIS). Nov. 2015, pp. 152–156.


[4] Francielle Alves Vargas and Thiago Alexandre Salgueiro Pardo. “Clustering and hierarchical organization of opinion aspects: a corpus study”. In:Proceedings of the 14th Corpus Linguistics Meeting. 2017, pp. 342–351.