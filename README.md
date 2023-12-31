# CReTIHC: Designing Causal Reasoning Tasks about Temporal Interventions and Hallucinated Confoundings

**Authors:**
- Changwoo Chun$^{1}$
- Songeun Lee$^{1}$
- Jaehyung Seo$^{2}$
- Heuiseok Lim$^{2\dagger}$

**Affiliations:**
- $^1$ Hyundai Motor Company
- $^2$ Department of Computer Science and Engineering, Korea University

**Contact:**
- $^{1}$ [cwchun@hyundai.com](mailto:cwchun@hyundai.com)
- $^{1}$ [songeun.lee@hyundai.com](mailto:songeun.lee@hyundai.com)
- $^{2}$ [seojae777@korea.ac.kr](mailto:seojae777@korea.ac.kr)
- $^{2\dagger}$ [limhseok@korea.ac.kr](mailto:limhseok@korea.ac.kr)

## Abstract
Large language models (LLMs) have demonstrated impressive capabilities in natural language processing. However, their ability to establish causal relationships, particularly in the context of temporal interventions and language hallucinations, remains challenging. This paper presents **CReTIHC**, a novel dataset designed to test and enhance the causal reasoning abilities of LLMs. The dataset is constructed using a unique approach that incorporates elements of verbal hallucinations and temporal interventions through the reengineering of existing causal inference datasets. This transformation creates complex scenarios that push LLMs to critically evaluate the information presented and identify cause-and-effect relationships. The CReTIHC dataset serves as a pioneering tool for improving LLM's causal inference capabilities, paving the way for a more nuanced understanding of causal relationships in natural language processing (NLP) tasks.

**Access the Dataset:**
The whole dataset is publicly accessible at: [CReTIHC GitHub Repository](https://github.com/ChangwooChun/CReTIHC)

*Corresponding author: Heuiseok Lim* ($\dagger$)


## Citation
If you find this work useful for your research, please cite it using the following BibTeX entry:

```bibtex
@inproceedings{chun-etal-2023-cretihc,
    title = "{CR}e{TIHC}: Designing Causal Reasoning Tasks about Temporal Interventions and Hallucinated Confoundings",
    author = "Chun, Changwoo  and
      Lee, SongEun  and
      Seo, Jaehyung  and
      Lim, Heuiseok",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2023",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-emnlp.693",
    pages = "10334--10343",
    abstract = "Large language models (LLMs) have demonstrated impressive capabilities in natural language processing. However, their ability to establish causal relationships, particularly in the context of temporal interventions and language hallucinations, remains challenging. This paper presents \textbf{CReTIHC}, a novel dataset designed to test and enhance the causal reasoning abilities of LLMs. The dataset is constructed using a unique approach that incorporates elements of verbal hallucinations and temporal interventions through the reengineering of existing causal inference datasets. This transformation creates complex scenarios that push LLMs to critically evaluate the information presented and identify cause-and-effect relationships. The CReTIHC dataset serves as a pioneering tool for improving LLM{'}s causal inference capabilities, paving the way for a more nuanced understanding of causal relationships in natural language processing (NLP) tasks. The whole dataset is publicly accessible at: (https://github.com/ChangwooChun/CReTIHC)",
}
