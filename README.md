### UD_Spanish-COSER v.1
This repository contains the datasets used as a first attempt to evaluate state-of-the-art POS taggers when dealing with spoken Spanish, as described in the paper by Anonimized. The datasets were also used in the games with a purpose hosted at Anonimized as part of a gamified approach for verifying Part of Speech (PoS) tagging of spoken dialectal Spanish. This was necessary due to the scarcity of linguistic resources available for spoken varieties.

The datasets are in CoNLL-U format and were initially generated using automatic methods. They were then manually corrected for UPOS and FEATS tags, while HEAD, DEP, and DEPS tags were produced automatically. In addition, the UPOS tags for the tutorial dataset used in the gamified approach were double-checked by experts.

To cite or check the results of using these datasets, please refer to the following paper:

Anonimized

Additionally, the models_evaluation.py file in this repository includes code used in the evaluation of the POS taggers, as described in the paper.
