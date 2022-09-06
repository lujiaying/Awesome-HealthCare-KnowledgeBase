# Awesome-HealthCare-KnowledgeBase
A curated list of awesome healthcare taxonomies and knowledge graphs.


## HealthCare Taxonomies

| Name | Paper | Misc. |
| -- | -- | -- |
| Disease Ontology | [The Human Disease Ontology 2022 update (Nucleic Acids Research'22)](https://pubmed.ncbi.nlm.nih.gov/34755882/) [[Website]](https://disease-ontology.org/) |  10,862 disease terms, 22,137 new SubClassOf Axioms|
| MeSH Ontology | [[Website]](https://www.nlm.nih.gov/mesh/meshhome.html) | MeSH includes the subject headings appearing in MEDLINE/PubMed, the NLM Catalog, and other NLM databases. |
| UMLS Semantic Network | [[Website]](https://uts.nlm.nih.gov/uts/umls/semantic-network/T071) | Broad categories (semantic types) and their relationships (semantic relations) for [UMLS Metathesaurus](https://uts.nlm.nih.gov/uts/umls/home) |
| Gene Ontology | [[Citation Policy]](http://geneontology.org/docs/go-citation-policy/) [[Website]](http://geneontology.org/) | three ontologies: Molecular Function, Cellular Component, Biological Process |
 
## HealthCare Knowledge Graphs

| Name | Paper | Domain | Scale |
| -- | -- | -- | -- |
| ClinicalKG (CKG) | [Clinical Knowledge Graph Integrates Proteomics Data into Clinical Decision-Making (bioRxiv)](https://www.biorxiv.org/content/10.1101/2020.05.09.084897v1) [[Website]](https://ckg.readthedocs.io/en/latest/INTRO.html) [[Code]](https://github.com/MannLabs/CKG) | clinical, laboratory and imaging data, multiomics data, and EHRs | 16 million nodes and 220 million relationships |
| repoDB | [A Standard Database for Drug Repositioning (Scientific Data'17)](https://www.nature.com/articles/sdata201729) [[Website]](http://apps.chiragjpgroup.org/repoDB/) | Drug, Disease | 1,571 drugs, 2,051 diseases |
| MSI | [Identification of disease treatment mechanisms through the multiscale interactome (Nature Communications'21)](https://www.nature.com/articles/s41467-021-21770-8) [[Code]](https://github.com/snap-stanford/multiscale-interactome)| Drugs, Proteins, Diseases, Biological Functions, Gene | 1,661 drugs, 840 disease, 17,660 proteins, 9,798 biological functions|
| Hetionet | [Heterogeneous Network Edge Prediction: A Data Integration Approach to Prioritize Disease-Associated Genes (PLOS Computational Biology'15)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004259) [[Website]](https://het.io/)| [11 types](https://git.dhimmel.com/rephetio-manuscript/#tbl:metanodes) of nodes, [24 types](https://git.dhimmel.com/rephetio-manuscript/#tbl:metaedges) of edges | 47,031 nodes (11 types) and 2,250,197 relationships (24 types) |

## KB Construction 

| Name | Paper | Used KB |
| -- | -- | -- |
| LM-Bio-KGC | [Scientific Language Models for Biomedical Knowledge Base Completion: An Empirical Study (AKBC'21)](https://arxiv.org/pdf/2106.09700.pdf) [[Code]](https://github.com/rahuln/lm-bio-kgc)| repoDB, MSI, Hetionet |

## KB Alignment 
