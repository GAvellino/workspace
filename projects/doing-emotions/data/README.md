# Data

This directory is reserved for research data used by the *Doing Emotions* computational workflow.

The datasets and lexical resources used by the project are not distributed through this repository. Researchers who wish to run the workflow must obtain the required resources independently from their official sources and place the relevant files in `data/raw/`.

Files stored in `data/raw/` are excluded from version control.

## GoEmotions

The project uses the GoEmotions corpus introduced by Demszky et al. (2020), a corpus of Reddit comments annotated for 27 emotion categories plus Neutral.

GoEmotions must be obtained independently from its official distribution.

Reference:

> Demszky, D., Movshovitz-Attias, D., Ko, J., Cowen, A., Nemade, G., & Ravi, S. (2020). GoEmotions: A Dataset of Fine-Grained Emotions. Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics.

Official project:
https://github.com/google-research/google-research/tree/master/goemotions

## NRC Valence, Arousal, and Dominance Lexicon v2

The project uses the NRC Valence, Arousal, and Dominance Lexicon v2 developed by Saif M. Mohammad at the National Research Council Canada.

The lexicon must be obtained independently from its official project page and must not be redistributed through this repository.

Reference:

> Mohammad, S. M. (2025). NRC VAD Lexicon v2: Norms for Valence, Arousal, and Dominance for over 55k English Terms.

Official project:
http://saifmohammad.com/WebPages/nrc-vad.html

Users of the lexicon are responsible for complying with the terms of use published by the National Research Council Canada.

## Reproducibility

The workflow documentation will specify the expected resource versions and local file locations required to reproduce the analysis.

Research data remain separate from the code repository so that the original distribution conditions, attribution requirements, and provenance of each resource are preserved.