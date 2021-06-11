# What can we do (and what do we need) to exploit ELTeC corpus. Some examples.

Borja Navarro Colorado | University of Alicante

## Introduction

This [INTELE](http://ixa2.si.ehu.eus/intele/?q=home) webinar shows how to exploit [ELTeC corpus](https://www.distant-reading.net/eltec/) for literary studies with some examples. Except for the last one, these examples are implemented and explained in COLAB notebooks, so you can run them in your machine. They explore the next topics:

- how to open and process ELTeC corpus with Python in COLAB;
- how to extract information annotated in XML;
- how to analyze ELTeC corpus with basic NLP techniques;
- and finally a simple proposal to overcome language barriers. 

## Where is ELTeC corpus?

+ Development version:
   - https://github.com/COST-ELTeC

+ Stable versions:
    - Official: https://zenodo.org/communities/eltec
    - TEIpublisher: https://teipublisher.com/exist/apps/eltec/index.html
    - GAMS: http://glossa.uni-graz.at/context:eltec
    - TextGRID (testing) https://dev.textgridrep.org/browse/3thgt.0

## Extracting information from XML

1. [Extracting author and gender from one collection (ELTeC-SPA)](https://github.com/bncolorado/Processing-ELTeC-corpus/blob/main/COLAB_notebooks/ELTeC_ExtractAuthorTitleGender.ipynb)
2. [Extracting author and gender from two (or more) collection (ELTeC-SPA and ELTeC-ENG)](https://github.com/bncolorado/Processing-ELTeC-corpus/blob/main/COLAB_notebooks/ELTeC_ExtractAuthorGenderFromSeveralCollections.ipynb)
3. [Extracting code switchig](https://github.com/bncolorado/Processing-ELTeC-corpus/blob/main/COLAB_notebooks/ELTeC_CodeSwitching.ipynb)


## Applying basic NLP techniques to analyze ELTeC corpus (with SpaCy)

1. [Analyzing Part of Speech of a novel from ELTeC-SPA with SpaCy.](https://github.com/bncolorado/Processing-ELTeC-corpus/blob/main/COLAB_notebooks/ELTeC_AnalyzingPoS.ipynb)

## Overcomming language barriers

Only an example about how to extract stylometric relations between novels from diverse languages. Unfortunatelly  it is not possible doing it in COLAB.

Inter-lingual representation based on WordNet synsets. Stylometric relations extracted with R package "Stylo".

Some results:

- [ELTeC SPA, ENG and FRA (all synsets).](https://raw.githubusercontent.com/bncolorado/Processing-ELTeC-corpus/8a92da48550e8d23daea81120b82234bba9016dc/images/Exp1_ELTeCSpaEngFra_synset.svg)
- [ELTeC SPA, ENG and FRA (only verb synsets).](https://raw.githubusercontent.com/bncolorado/Processing-ELTeC-corpus/8a92da48550e8d23daea81120b82234bba9016dc/images/Exp2_ELTeCSpaEngFra_SoloVerbos.svg)

