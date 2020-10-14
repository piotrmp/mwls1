# MWLS1

MWLS1 (*Multi-Word Lexical Simplification dataset 1*) is a dataset for lexical simplification (making text easier to understand by replacing some words), in which both the replaced and replacing fragments can consist of multiple words (up to 3). It was gathered by asking [Amazon Mechanical Turk](https://www.mturk.com/) crowd workers to provide alternatives for specified fragments that are simpler, yet preserve the overall meaning and fluency of the sentences. 

For example, one of the sentences in the dataset (*CASE_1433*) reads *For the fortified city is solitary, a **habitation deserted** and forsaken, like the wilderness.* The replaced fragment, highlighted in bold, has been simplified by crowd workers as *home left*, *residence abandoned*, *home forgotten*, *house empty* and *place empty*.

The dataset was created as a part of the study described in the article *[Multi-Word Lexical Simplification](https://www.aclweb.org/anthology/TODO.pdf)* presented at the [COLING 2020](https://coling2020.org/) conference in Barcelona. If you need any more information consult [the paper](https://www.aclweb.org/anthology/TODO.pdf) or contact its authors! 

## Data format

File ```MWLS1.tsv``` contains 1462 sentences with 7059 simplifications that make up the dataset. 

## Licence

The dataset is released under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) licence.
