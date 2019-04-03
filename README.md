# bioelmo
BioELMo is a biomedical version of embeddings from language model (ELMo), pre-trained on PubMed abstracts. Pre-training uses 10M recent PubMed abstracts (2.46B tokens in total), and BioELMo achieves an averaged forward and backward perplexity of 31.37 on a held-out test set.

## Download
- [BioELMo weights](https://drive.google.com/file/d/1CHRd5YQrt3ys64WfJkJR1KX72-2CaT4I/view?usp=sharing)
- [options](https://drive.google.com/file/d/19sLZ1NhUtD_bMgTstSRWoVDx6Vm-T8Qt/view?usp=sharing)
- [vocabulary file](https://drive.google.com/file/d/15cXEVoRhUQ9oBnHVFP3nx6GQozczgxgP/view?usp=sharing)

## Usage
Please visit https://github.com/allenai/bilm-tf. Basically, you use BioELMo the same way you use ELMo.

## Interesting Properties
1. BioELMo encodes biomedical entity-type and relational information pretty well, as shown in our paper.
2. BioELMo effectively encodes numbers in biomedical contexts. ![alt text](image/demographic_embeddings.png "demo")

## Probing Experiments
Please visit https://github.com/Andy-jqa/probing_biomed_embeddings for codes of probing experiments described in Probing Biomedical Embeddings from Language Model.

## Citation
Please cite the following paper if you use BioELMo:
```
@inproceedings{jin2019,
  title={Probing Biomedical Embeddings from Language Models},
  author=author={Jin, Qiao and Dhingra, Bhuwan and Cohen, William and Lu, Xinghua},
  booktitle={Proceedings of the 3rd Workshop on Evaluating Vector Space Representations for NLP},
  year={2019}
}
```
