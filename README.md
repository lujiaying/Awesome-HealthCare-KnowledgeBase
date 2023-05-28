# Awesome-HealthCare-KnowledgeBase
A curated list of awesome healthcare taxonomies and knowledge graphs.
We know we may have missed important softwares or literatures, please feel free to create an issue for any suggesstions.


## HealthCare Ontology/Taxonomies

What are the differences between ontology and taxonomy? See discussion [🔗 here>>](taxonomy_and_ontology.md).

| Name | Paper | Misc. |
| -- | -- | -- |
| Disease Ontology | [The Human Disease Ontology 2022 update (Nucleic Acids Research'22)](https://pubmed.ncbi.nlm.nih.gov/34755882/) [[Website]](https://disease-ontology.org/) |  10,862 disease terms, 22,137 new SubClassOf Axioms|
| Mondo Disease Ontology | [[Website]](https://www.ebi.ac.uk/ols/ontologies/mondo) | A semi-automatically constructed ontology that merges in multiple disease resources to yield a coherent merged ontology. |
| MeSH Ontology | [[Website]](https://www.nlm.nih.gov/mesh/meshhome.html) | MeSH includes the subject headings appearing in MEDLINE/PubMed, the NLM Catalog, and other NLM databases. |
| UMLS Semantic Network | [[Website]](https://uts.nlm.nih.gov/uts/umls/semantic-network/T071) | Broad categories (semantic types) and their relationships (semantic relations) for [UMLS Metathesaurus](https://uts.nlm.nih.gov/uts/umls/home) |
| SNOMED | 
| Gene Ontology | [[Citation Policy]](http://geneontology.org/docs/go-citation-policy/) [[Website]](http://geneontology.org/) | three ontologies: Molecular Function, Cellular Component, Biological Process |
| Cell Taxonomy | [Cell Taxonomy: a curated repository of cell types with multifaceted characterization (Nucleic Acids Research'22)](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkac816/6717827) [[Website]](https://ngdc.cncb.ac.cn/celltaxonomy/) |  3,143 cell types, 26,613 associated cell markers in 257 conditions and 387 tissues across 34 species.|


## HealthCare Knowledge Graphs

| Name | Paper | Domain | Scale | Data Sources |
| -- | -- | -- | -- | -- |
| **General** KGs|
| ClinicalKG (CKG) | [Clinical Knowledge Graph Integrates Proteomics Data into Clinical Decision-Making (bioRxiv)](https://www.biorxiv.org/content/10.1101/2020.05.09.084897v1) [[Website]](https://ckg.readthedocs.io/en/latest/INTRO.html) [[Code]](https://github.com/MannLabs/CKG) | clinical, laboratory and imaging data, multiomics data, and EHRs | 16 million nodes and 220 million relationships | [integrate](https://ckg.readthedocs.io/en/latest/INTRO.html#important-note) 25 KGs, 10 ontologies(taxos)|
| MSI | [Identification of disease treatment mechanisms through the multiscale interactome (Nature Communications'21)](https://www.nature.com/articles/s41467-021-21770-8) [[Code]](https://github.com/snap-stanford/multiscale-interactome)| Drugs, Proteins, Diseases, Biological Functions, Gene | 1,661 drugs, 840 disease, 17,660 proteins, 9,798 biological functions|
| Hetionet | [Heterogeneous Network Edge Prediction: A Data Integration Approach to Prioritize Disease-Associated Genes (PLOS Computational Biology'15)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004259) [[Website]](https://het.io/)| [11 types](https://git.dhimmel.com/rephetio-manuscript/#tbl:metanodes) of nodes, [24 types](https://git.dhimmel.com/rephetio-manuscript/#tbl:metaedges) of edges |  combines information from 29 public databases. 47,031 nodes (11 types) and 2,250,197 relationships (24 types) | Entrez Gene, DrugBank, Uberon, Disease Ontology, MeSH ontology, SIDER, UMLS, Gene Ontology, WikiPathways, Reactome, Pathway Interaction Database, DrugCentral |
| iBKH | [iBKH: The integrative Biomedical Knowledge Hub (medRxiv'22)](https://www.medrxiv.org/content/10.1101/2021.03.12.21253461v3) [[Code]](https://github.com/wcm-wanglab/iBKH) | Anatomy, Disease, Drug, Gene, Molecule, Symptom, Dietary Supplement Ingredient/Product, Therapeutic Class, Pathway, Side-Effect | 2M entities, 48M relations | Integrate [18 public data sources](https://github.com/wcm-wanglab/iBKH/blob/3bae2aa50beb111a0e07a30cdbfc7a23a45d3e19/Source%20Information/README.md) |
| **Disease-specific** KGs |
| DRKG | [[Blog article'22]](https://www.dgl.ai/news/2020/06/09/covid.html) [[Code]](https://github.com/gnn4dr/DRKG) | genes, compounds, diseases, biological processes, side effects and symptoms focusing on drug repurposing for COVID-19. | 97,238 entities belonging to 13 entity-types; and 5,874,261 triplets belonging to 107 edge-types. | DrugBank, Hetionet, GNBR, String, IntAct and DGIdb, and Covid19 literatures. |
| COVID-KG | [COVID-19 Literature Knowledge Graph Construction and Drug Repurposing Report Generation (NAACL'21)](https://aclanthology.org/2021.naacl-demos.8.pdf) [[Website]](http://blender.cs.illinois.edu/covid19/)| Gene, Disease, Chemical, Organism focusing on COVID-19 | 50,752 Gene nodes, 10,781 Disease nodes, 5,738 Chemical nodes, and 535 Organism nodes; 133 relation types| COVID scientific literature, and existing [CTD](http://ctdbase.org/), MESH |
| KGHC | [KGHC: a knowledge graph for hepatocellular carcinoma (BMC Medical Informatics and Decision Making'20)](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1112-5)| focusing on hepatocellular carcinoma | |
| KG-COVID-19 | [KG-COVID-19: a framework to produce customized knowledge graphs for COVID-19 response (Patterns'20)](https://www.cell.com/patterns/fulltext/S2666-3899(20)30203-8?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2666389920302038%3Fshowall%3Dtrue) [[Website]](https://knowledge-graph-hub.github.io/kg-covid-19/index.html)| |
| **Drug-specific** KGs |
| repoDB | [A Standard Database for Drug Repositioning (Scientific Data'17)](https://www.nature.com/articles/sdata201729) [[Website]](http://apps.chiragjpgroup.org/repoDB/) | Drug, Disease | 1,571 drugs, 2,051 diseases | N/A |
| DrugBank | [DrugBank: a comprehensive resource for in silico drug discovery and exploration (Nucleic Acids Research'06)](https://academic.oup.com/nar/article/34/suppl_1/D668/1132926) [[Website]](https://go.drugbank.com/) | Drug, and drug target (i.e. sequence, structure, pathway)| 15,686 drug, 5,296 non-redundant protein sequences | N/A |

## KB Construction 

| Name | Paper | Used KB |
| -- | -- | -- |
| LM-Bio-KGC | [Scientific Language Models for Biomedical Knowledge Base Completion: An Empirical Study (AKBC'21)](https://arxiv.org/pdf/2106.09700.pdf) [[Code]](https://github.com/rahuln/lm-bio-kgc)| repoDB, MSI, Hetionet |

## KB Fusion: including ontology matching, entity alignment.

### Ontology Matching

**Problem Definition**: Given two ontoloties $\mathcal{O}_1, \mathcal{O}_2$, generating a 4-tuple $(e, e', r, c)$ where $e$ and $e'$ are entities of $\mathcal{O}_1$ and $\mathcal{O}_2$; $r$ is the semantic equivelant relation (can be extendted to $\\{ \sqsubseteq,\sqsupseteq, \equiv \\}$) ; and $c$ is a confident value within $[0, 1]$.

| Name | Paper | Datasets | Notes|
| -- | -- | -- | -- |
| LogMap | [LogMap: Logic-based and Scalable Ontology Matching (ISWC'11)](https://www.cs.ox.ac.uk/isg/projects/LogMap/papers/paper_ISWC2011.pdf) [[Github]](https://github.com/ernestojimenezruiz/logmap-matcher) | FMA-NCI, FMA-SNOMED, SNOMED-NCI, Mouse-NCI<sub>Anat</sub> | a highly scalable ontology matching system in Java |
| PARIS | [PARIS: Probabilistic Alignment of Relations, Instances, and Schema (VLDB'12)](https://suchanek.name/work/publications/vldb2012.pdf) [[Github]](https://github.com/dig-team/PARIS)| YAGO-DBpedia | a non-neural entity, relation and ontology alignment system in Java. |
| AML | [The AgreementMakerLight Ontology Matching System (OTM'13)](https://link.springer.com/chapter/10.1007/978-3-642-41030-7_38) [[Github]](https://github.com/AgreementMakerLight/AML-Project) | [OAEI'2012](https://oaei.ontologymatching.org/2012/): FMA-NCI, FMA-SNOMED, SNOMED-NCI| An element-level ontology alignment system in Java. |
| OAEI | [[Website]](http://www.cs.ox.ac.uk/isg/projects/SEALS/oaei/index.html) | [Mondo](https://mondo.monarchinitiative.org/): OMIM-ORDO, NCIT-DOID; UMLS: SNOMED-FMA, SNOMED-NCIT | Ontology Alignment Evaluation Initiative since 2011|
| MEDTO | [MEDTO: Medical Data to Ontology Matching Using Hybrid Graph Neural Networks (KDD'21)](https://dl-acm-org.proxy.library.emory.edu/doi/pdf/10.1145/3447548.3467138) | databases: MIMIC-III, [MDX](https://www.ibm.com/products/micromedex-with-watson); ontology: OAEI| database to ontology matching task |


### Entity Alignment (or KG Alignment)

**Problem Definition**: Given two KGs $\mathcal{G}_1=\\{ \mathcal{E}_1, \mathcal{R}_1, \mathcal{TP}_1 \\}$ and $\mathcal{G}_2= \\{ \mathcal{E}_2, \mathcal{R}_2, \mathcal{TP}_2 \\}$, where $\mathcal{E}$ and $\mathcal{R}$ denote the sets of entities and relations, $\mathcal{TP} \subseteq \mathcal{E}\times \mathcal{R}\times \mathcal{E}$ is the set of relational triplets. *Entity aligment* aims to identify entities in $\mathcal{G}_1$ and $\mathcal{G}_2$ that refer to the same real-world object, i.e., seeking a set of alignment $\mathcal{A}=\\{(e_1,e_2)\in \mathcal{E}_1\times\mathcal{E}_2 | e_1 \equiv  e_2 \\}$. A small set of seed entity algiment $\mathcal{A}_s \subset \mathcal{A}$ is usually provided as anchors (training data) beforehand to help align the remaining entities.

| Name | Paper | Baselines | Datasets |
| -- | -- | -- | -- |
| industry eval EA | [An Industry Evaluation of Embedding-based Entity Alignment (COLING'17)](https://aclanthology.org/2020.coling-industry.17.pdf) |  BootEA, MultiKE, RDGCN, RSN4EA, PARIS | cross-lingual EA: [DBP15K](https://arxiv.org/pdf/1708.05045v2.pdf), [WK3160K](https://www.ijcai.org/proceedings/2018/0556.pdf); cross-KG (DBpedia and Wikidata) EA: [DWY15K](https://arxiv.org/pdf/1811.02318.pdf), [DWY100K](https://www.ijcai.org/proceedings/2018/0611.pdf), **MED-BBK-9K**: contains two Chinese medical KGs. |
| OpenEA | [[Code]](https://github.com/nju-websoft/OpenEA) | 20+ methods | cross-lingual DBpedia: EN-FR, EN-DE; cross-KG: D-W(ikidata), D-Y(AGO)|
| UED | [Semi-constraint Optimal Transport for Entity Alignment with Dangling Cases (arxiv'22)](https://arxiv.org/pdf/2203.05744.pdf) [[Code]](https://github.com/luosx18/UED) | MTransE, JAPE, BootEA, RDGCN, RNM, RAGA, EchoEA, SelfKG, SoTead, UEA, SEU | cross-lingual EA: DBP15K, [DBP2.0](https://aclanthology.org/2021.acl-long.278.pdf); cross-lingual medical-KG EA: **MedED** |
| OntoEA | [OntoEA: Ontology-guided Entity Alignment via Joint Knowledge Graph Embedding (Findings of ACL 2021)](https://arxiv.org/abs/2105.07688) [[Code]](https://github.com/ZihengZZH/OntoEA) | OpenEA methods | shared Ontology: EN-FR, EN-DE, MED-BBK; not shared Ontology: D-W |
| HiPrompt | [HiPrompt: Few-Shot Biomedical Knowledge Fusion via Hierarchy-Oriented Prompting (SIGIR'23)](https://arxiv.org/abs/2304.05973)| LogMap, PARIS, AML, SapBERT, SelfKG, MTransE; HiPrompt: LLM-based entity alignment method | SDKG-DO, repoDB-DO |
