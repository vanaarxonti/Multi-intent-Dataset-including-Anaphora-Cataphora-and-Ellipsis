# A Multi-intent-Dataset-including-Anaphora-Cataphora-and-Ellipsis for Intent Classification


## Frequently Asked Questions (FAQs)

## 1. Where does this dataset originate from?

The primary data of the present dataset originate from the following dataset, which functioned as the primary source of our Dataset.

- **Source Intent Classification Dataset:**
  - Original Dataset: CLINC150
  - Original Paper : [An Evaluation Dataset for Intent Classification and Out-of-Scope Prediction](https://www.aclweb.org/anthology/D19-1131)
  -License: [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/)

## 2. Why did you choose this source for your dataset?

For the development of our dataset, we selected the CLINC150 dataset because it is an IC dataset, offering a wide range of single intent utterances of different domains and intents that closely resemble human-system interactions. We utilize the full version of CLINC150 dataset and focus solely on in-scope examples, excluding the out-of-scope samples. Therefore, our dataset has been created based on the subset of the full dataset consisting of 22,500 in-scope utterances. 

## 3. How does your dataset handle multi-intent queries?

Our dataset, an expansion of the original CLINC150 dataset, incorporates multi-intent utterances containing the linguistic phenomena of Anaphora, Cataphora and Ellipsis. It is designed to handle multi-intent scenarios, encompassing double-intent and single-intent utterances. Thus, the dataset includes double-intent utterances with Anaphora, Cataphora & Ellipsis, double-intent utterances without these linguistic phenomena using structures as “Not only- but also, besides, furthermore, moreover” to produce more natural utterances, and single intent utterances. Furthermore, as the primary data were originated from CLINC150, the original utterances dataset were enriched with the aforementioned linguistic phenomena, occurring in double-intent utterances mannually; we prefer to call them utterances, rather than sentences, because we view them as acts of speech. However, the challenges encountered in incorporating thephenomena of cataphora, anaphora, and ellipsis necessitated the modification of some of the initial utterances of the CLINC150 dataset, rather than adopted the straightforward conjunction of two utterances, we adhered to the rules governing anaphora, cataphora and ellipsis.







