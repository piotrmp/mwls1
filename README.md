# MWLS1

MWLS1 (*Multi-Word Lexical Simplification dataset 1*) is a dataset for lexical simplification (making text easier to understand by replacing some words), in which both the replaced and replacing fragments can consist of multiple words (up to 3). It was gathered by asking [Amazon Mechanical Turk](https://www.mturk.com/) crowd workers to provide alternatives for specified fragments that are simpler, yet preserve the overall meaning and fluency of the sentences. 

For example, one of the sentences in the dataset (*CASE_1433*) reads *For the fortified city is solitary, a **habitation deserted** and forsaken, like the wilderness.* The replaced fragment, highlighted in bold, has been simplified by crowd workers as *home left*, *residence abandoned*, *home forgotten*, *house empty* and *place empty*.

The dataset was created as a part of the study described in the article *[Multi-Word Lexical Simplification](https://github.com/piotrmp/mwls1/blob/main/Multi-Word_Lexical_Simplification_Coling2020.pdf)* presented at the [COLING 2020](https://coling2020.org/) conference in Barcelona. If you need any more information consult [the paper](https://github.com/piotrmp/mwls1/blob/main/Multi-Word_Lexical_Simplification_Coling2020.pdf) or contact its authors! 

## Data format

File ```MWLS1.tsv``` contains 1462 sentences with 7059 simplifications that make up the dataset. It has the following tab-separated columns:
* *Id*: unique sentence indentifier,
* *Group* indicates the length of the replaced text (1-3 words) and the source corpus:
  * *BIBLIE*: World English Bible translation from a [parallel corpus](http://christos-c.com/bible/),
  * *BIOMED*: Text of biomedical publications gathered in the [CRAFT corpus](http://bionlp-corpora.sourceforge.net/CRAFT/),
  * *EUROPARL*: English text from the European Parliament proceedings compiled as the [Europarl corpus](https://www.statmt.org/europarl/).
* *Prefix*: the part of the sentence before the replaced fragment,
* *Replaced*: the replaced fragment,
* *Suffix*: the part of the sentence after the replaced fragment,
* *NoAnswers*: number of replacements provided by the workers (1-5)
* *Answers*: the replacements.

## Licence

The dataset is released under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) licence.

## Citation

Przybyła, P. and Shardlow, M., 2020, December. Multi-Word Lexical Simplification. In Proceedings of the 28th International Conference on Computational Linguistics.


    @inproceedings{plainifier,
        title = "Multi-Word Lexical Simplification",
        author = {Przyby{\l}a, Piotr and Shardlow, Matthew}",
        booktitle = "Proceedings of the 28th International Conference on Computational Linguistics",
        month = dec,
        year = "2020",
        address = "Barcelona, Spain",
        publisher = "Association for Computational Linguistics",
    }

