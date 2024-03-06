# Open Source Malaria Series 4 Manuscript
This repository contains executable notebooks and links related to the OSM Series 4 work by Ersilia.

## The manuscript

The current manuscript is publicly visible in [this online document](https://docs.google.com/document/d/121GO12g6MR0axZ0z6C3ODscIa0lhyg6wOZW_NBjPfoA/edit?usp=sharing). We expect to submit it as a _Note_ to _ACS Medicinal Chemistry Letters_ in response to [this call for papers](https://axial.acs.org/medicinal-chemistry/cfp-exploring-the-use-of-ai-ml-technologies-in-medicinal-chemistry-and-drug-discovery) related to AI.

### Author guidelines
Author guidelines can be found [here](https://publish.acs.org/publish/author_guidelines?coden=amclct) and a short comment on how to increase chances of acceptance can be found [here](https://pubs.acs.org/doi/10.1021/acsmedchemlett.4c00059).

In sum:
* Abstract: 150 words.
* Text: 2500 words, no sections.
* References: 30.
* Figures and tables: 2-4.
* Figures format: One column: up to 240 pt (3.33 in). Two columns: between 300 and 504 pt (4.167 in. and 7 in.). Lettering no smaller than 4.5 pt.

## Resources

* [OSM Issue #34](https://github.com/OpenSourceMalaria/Series4_PredictiveModel/issues/34 )
* [Generative modelling, round 1](https://github.com/ersilia-os/osm-series4-candidates)
* [Generative modelling, round 2](https://github.com/ersilia-os/osm-series4-candidates-2)
* [Predictive model](https://github.com/ersilia-os/osm-series4-predictive-model)
* [Selection of candidates for synthesis](https://github.com/ersilia-os/osm-series4-synthesis-round1)
* [PfATP4 AlphaFold Structure](https://github.com/ersilia-os/osm-pfatp4-structure)
* [ChemSampler](https://github.com/ersilia-os/chem-sampler)

## Installation

Create a conda environment and activate it.

```bash
conda create -n osms4 python=3.11
conda activate osms4
```

Install [Ersilia Compound Embeddings](https://github.com/ersilia-os/compound-embedding) and after you have installed it.

```bash
cd ~/Desktop
git clone https://github.com/ersilia-os/compound-embedding.git
cd compound-embedding/lite
pip install .
cd ../..
rm -r compound-embedding
```

Install other necessary Python libraries.

```bash
pip install pandas
pip install umap-learn
pip install git+https://github.com/ersilia-os/stylia.git
```

## Usage

