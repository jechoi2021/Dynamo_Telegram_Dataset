# Dynamo_Telegram_Dataset

This repository briefly describes the Telegram dataset collected and curated as part of the research project DYNAMO.
For a detailed description and analysis, please refer to our paper (currently under review) 
Our dataset can be found here: https://zenodo.org/records/15686121 (DOI https://doi.org/10.5281/zenodo.15686120)

**!! Update !!**
- November 2025: Our dataset paper has been accepted for the IEEE BigData2025 Conference and will appear soon in the proceedings. The link to the paper will be added once the proceedings are published. Until then, you can temporarily access our paper here: [PAPER]().

## Dataset Structure
The dataset is divided into two main collections:

Collection_{actors}:
Provides aggregated statistical metadata for each actor (i.e., channel or group).
Useful for analyzing actor-level behavior and dissemination dynamics.

Collection_{posts}:
Contains curated metadata for individual posts, organized per actor.
Each file corresponds to a specific actor and includes metadata for all posts from that actor.

## Purpose
This dataset enables research on dissemination patterns and behavioral dynamics of Telegram actors, particularly in the context of disinformation.
Due to potential privacy and legal concerns, only anonymized metadata is provided. Content-level data is not included. Instead, keyword and sentiment annotations are provided to support meaningful analysis.

## Anonymization and Identifiers
Actor identifiers (for both channels and groups) are pseudonymized and do not correspond to actual Telegram IDs.
The same is for user identifiers.
Post identifiers are unique within each file and correspond to the original Telegram message ID within that actor.

Filenames in Collection_{posts} match the pseudonymized actor ID in Collection_{actors}.

## Format
All files are provided in CSV format.

Column structure and field descriptions are explained in detail in the accompanying paper.

## Usage Notes
The dataset supports efficient metadata-driven analysis without compromising user privacy.

Please cite our paper when using this dataset in your work.
