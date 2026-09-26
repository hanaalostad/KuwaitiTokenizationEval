# Kuwaiti Arabic Tokenization Evaluation

This repository contains the source code and scripts used to create and prepare the Kuwaiti Arabic (KA) translations used in the study:

**Evaluating LLM Tokenization Efficiency on Kuwaiti Dialect, MSA and Other Arabic Dialects**

The study evaluates tokenization efficiency for Kuwaiti Arabic (KA), Modern Standard Arabic (MSA), and other Arabic dialects using semantically aligned sentences.

## Data Sources

### MADAR Corpus-6

The study uses **MADAR Corpus-6** as the source of the parallel MSA and Arabic dialect sentences.

MADAR Corpus-6 is available from the original provider under its research-use license:

https://camel.abudhabi.nyu.edu/madar-parallel-corpus/

MADAR data are **not redistributed in this repository**.

The KA translations created from MADAR are also **not redistributed in this repository**.

Users who wish to reproduce the dataset construction should obtain MADAR Corpus-6 directly from the original provider and comply with its applicable license terms.

## Kuwaiti Arabic Translation and Preparation

This repository provides the source code and scripts used to create and prepare the KA translations from the MADAR MSA sentences.

The KA dataset used in the study was produced through machine-assisted translation followed by native-speaker review and post-editing.

The provided scripts support reproduction of the dataset preparation process after the user has independently obtained the required MADAR data.

## Kuwaiti Stance Dataset

The Kuwaiti Arabic stance dataset used in the downstream evaluation is openly available from the Q8Stance repository:

https://github.com/hanaalostad/Q8Stance

## Data Availability Summary

| Resource | Availability |
|---|---|
| MADAR Corpus-6 | Available from the original provider under its applicable research-use license |
| MADAR source sentences | Not redistributed in this repository |
| KA translations derived from MADAR | Not redistributed in this repository |
| KA translation and preparation scripts | Available in this repository |
| Kuwaiti stance dataset | Publicly available through the Q8Stance repository |

## Reproducibility

To reproduce the KA dataset preparation:

1. Obtain MADAR Corpus-6 directly from the original provider.
2. Follow the applicable MADAR license and usage conditions.
3. Use the scripts provided in this repository to create and prepare the KA translations.
4. Apply the review and quality-assurance procedure described in the associated paper.

Because the original MADAR sentences and their KA translations are not redistributed here, users must provide their own authorized copy of MADAR Corpus-6 when running the scripts.

## License

The license of this repository applies only to the source code and scripts provided here.

It does **not** grant any rights to MADAR Corpus-6 or to other third-party datasets used in the study. Users are responsible for complying with the licenses and terms of the original data providers.

## Citation

If you use the code or methodology from this repository, please cite the associated paper:

> H. Alostad and Y. Almutairi, *Evaluating LLM Tokenization Efficiency on Kuwaiti Dialect, MSA and Other Arabic Dialects*.
        
