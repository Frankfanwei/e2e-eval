E2E NLG Challenge Evaluation Files
==================================

This package contains outputs of participating systems and raw human ratings for the
[E2E NLG Challenge](http://www.macs.hw.ac.uk/InteractionLab/E2E/).


Contents
--------

### Directory structure

The directory structure is the following:

- `participants.tsv` -- "legend" to labels for participating teams 
    (these are used for direcory names and in system labels in the human
    rating files; see below for primary system variants)
- `human_ratings/` -- raw human ratings
- `system_outputs/primary/` -- outputs of primary systems (these were
    used for human ratings)
- `system_outputs/all/` -- outputs of all systems submitted to the
    challenge (including primary)


### System output files

The system output files are TSV files with UTF-8 encoding, containing two tab-separated columns:
* `MR` = the input MR
* `output` = the corresponding system output


### Raw human ratings files

In the human ratings CSV files, these columns are of interest:
- `mr` = the input MR
- `sys1`-`sys5` = system labels
- `ref1`-`ref5` = corresponding system outputs
- `quality1`-`quality5` / `natur1`-`natur5` = corresponding human ratings


### Primary system labels


These are used in the human rating files (they correspond to the labeling used
in the INLG paper):

| label    | affiliation                                      | architecture |
|----------|--------------------------------------------------|--------------|
| adapt    | AdaptCentre                                      | seq2seq      |
| chen     | Harbin Institute of Technology                   | seq2seq      |
| dangnt   | University of Information Technology VNU-HCM     | rule-based   |
| forge1   | Pompeu Fabra University                          | rule-based   |
| forge3   | Pompeu Fabra University                          | templates    |
| gong     | Harbin Institute of Technology                   | seq2seq      |
| harv     | HarvardNLP                                       | seq2seq      |
| nle      | NAVER Labs Europe                                | seq2seq      |
| sheff1   | Sheffield NLP                                    | data-driven  |
| sheff2   | Sheffield NLP                                    | seq2seq      |
| slug     | UC Santa Cruz (Slug2Slug)                        | seq2seq      |
| slug-alt | UC Santa Cruz (Slug2Slug)                        | seq2seq      |
| tgen     | Heriot-Watt University (baseline)                | seq2seq      |
| tnt1     | UC Santa Cruz (TNT-NLG)                          | seq2seq      |
| tnt2     | UC Santa Cruz (TNT-NLG)                          | seq2seq      |
| tr1      | Thomson Reuters NLP                              | seq2seq      |
| tr2      | Thomson Reuters NLP                              | templates    |
| tuda     | UKP TU Darmstadt                                 | templates    |
| zhang    | Xiamen University                                | seq2seq      |
| zhaw1    | Zürcher Hochschule für Angewandte Wissenschaften | data-driven  |
| zhaw2    | Zürcher Hochschule für Angewandte Wissenschaften | data-driven  |


