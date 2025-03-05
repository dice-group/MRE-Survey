# Multilingual Relation Extraction - A Survey
## Repository Information  

This repository contains files related to our systematic survey about Multilingual RE.  

- **Details of all papers:** [Google Spreadsheet](https://docs.google.com/spreadsheets/d/1MCPoM9nsN1VgvdvzjvgRW8OwoUaCkOGQxb_g4RzGN34/edit?gid=1771987299#gid=1771987299)  
- **Colab Notebook:** [Google Colab](https://colab.research.google.com/drive/1Aqyj45rwOKANbbjfGQC9kQtKpzYxJ_Fv#scrollTo=y0DSORGEPk56)  


## Included Litrature:

All approaches studied, with publication year (Year), supported languages (Langs), number of relations (\#Rel), the dataset name, KPIs, and implementation (Imp) are provided in the follwoing table:

| Approach | Year | Langs | #Rel | Domain | Dataset | KPI | Imp |
|----------|------|-------|------|--------|---------|-----|-----|
| FA4RC [[1]] | 2018 | en, zh | 6 | Adversarial RE | ACE05 | F1-score | [FA4RC](https://github.com/zoubowei/feature_adaptation4RC) |
| AMNRE [[2]] | 2018 | en, zh | 176 | Adversarial RE | Neural RE | AUC, Precision, Recall | [AMNRE](https://github.com/thunlp/AMNRE) |
| Structure Transfer [[3]] | 2019 | ar, en, zh | 18 | Joint Event and RE | ACE05 | F1-score | - |
| NCL RE [[4]] | 2019 | ar, de, en, es, it, ja, pt, zh | 59 | MRE | In-house & ACE05 | F1-score | - |
| LOREM [[5]] | 2020 | en, es, fr, hi, it, nl, ru | - | Open RE | WMORC | Precision, Recall, F1-score | [LOREM](https://github.com/tomharting/LOREM) |
| Multi²OIE [[6]] | 2020 | en, es, pt | - | Open IE | Re-OIE2016 | AUC, Precision, Recall, F1-score | [Multi²OIE](https://github.com/youngbin-ro/Multi2OIE) |
| GATE [[7]] | 2021 | ar, en, zh | 18 | Joint Event and RE | ACE05 | F1-score | [GATE](https://github.com/wasiahmad/GATE) |
| LOME [[8]] | 2021 | en, zh | 4 | Temporal RE | Time Bank | F1-score | [Lome](https://nlp.jhu.edu/demos/lome/) |
| PUCRJ-PUCPR-UFMG [[9]] | 2021 | en, es | 13 | Bio-Medical | eHealth-KD | Precision, Recall, F1-score | [PUCRJ-PUCPR-UFMG](https://github.com/eHealth-KD-PUCs-UFMG/pucrj-pucpr-ufmg) |
| CLARE [[10]] | 2021 | ar, en, zh | 6 | Adversarial RE | ACE05 | F1-score | - |
| HERBERTa [[11]] | 2021 | ar, de, en, es, fa, fr, it, ko, nl, pl, pt, ru, sv, uk | 16 | Joint NER & RE | SMiLER | F1-score | [HERBERTa](https://github.com/samsungnlp/smiler) |
| PARE [[12]] | 2021 | de, en, es, fr | 37 | Distant Supervision | Dis-ReX | AUC, F1-score | [DSRE](https://github.com/dair-iitd/DSRE) |
| Temp Prob [[13]] | 2022 | en, es, fr, it | 13 | Temporal RE | Time Bank | F1-score | [tlink_probing](https://github.com/irenedini/tlink_probing) |
| MRC Prompt [[14]] | 2022 | ar, de, en, es, fa, fr, it, ko, nl, pl, pt, ru, sv, uk | 36 | LLM-Based RE | SMiLER | F1-score | [meffi-prompt](https://github.com/DFKI-NLP/meffi-prompt) |
| TransRel [[15]] | 2022 | bn, en, hi, te | 51 | Low-resource | IndoRE | F1-score | [IndoRE](https://github.com/NLPatCNERG/IndoRE) |
| mERE [[16]] | 2023 | ar, de, en, es, fa, fr, it, ko, nl, pl, pt, ru, sv, uk | 16 | Joint NER & RE | SMiLER | F1-score | - |
| Prompt-XRE [[17]] | 2023 | ar, en, zh | 18 | Typed Open RE | ACE05, WMT17-EnZh XRE | F1-score | [XRE](https://github.com/HSU-CHIA-MING/Prompt-XRE) |
| SSDN [[18]] | 2023 | ar, en, zh | 18 | Joint EARL & RE | ACE05 | F1-score | - |


