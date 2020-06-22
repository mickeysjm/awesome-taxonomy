# awesome-taxonomy
A curated resource for taxonomy research


## Datasets / Shared Tasks

1. SemEval-2015 Task 17: Taxonomy Extraction Evaluation (TExEval-1), [Home](http://alt.qcri.org/semeval2015/task17/), [Report](http://aclweb.org/anthology/S15-2151)

2. SemEval-2016 Task 13: Taxonomy Extraction Evaluation (TExEval-2), [Home](http://alt.qcri.org/semeval2016/task13/), [Report](http://www.aclweb.org/anthology/S16-1168)

3. SemEval-2016 Task 14: Semantic Taxonomy Enrichment, [Home](http://alt.qcri.org/semeval2016/task14/), [Report](https://www.aclweb.org/anthology/S16-1169)

4. SemEval-2018 Task 9: Hypernym Discovery, [Home](https://competitions.codalab.org/competitions/17119), [Report](http://aclweb.org/anthology/S18-1115)

5. UnsupervisedHypernymy, [Home](https://github.com/vered1986/UnsupervisedHypernymy), [EACL 2017 paper](https://www.aclweb.org/anthology/E17-1007), including 4 datasets:

	* (Hypernymy Detection): EVAL, BLESS, LEDS (a.k.a Lenci/Benotto), Weeds

6. HypernymySuite, [Home](https://github.com/facebookresearch/hypernymysuite), [ACL 2018 paper](https://www.aclweb.org/anthology/P18-2057), including (somewhat modified) datasets: 
	
	* (Hypernymy Detection): BLESS, LEDS, EVAL, SHWARTZ, WBLESS
	* (Hypernymy Direction): BLESS, WBLESS, BIBLESS
	* (Graded Entailment): HyperLex


## Paper


### Survey & Tutorials

- \[ACL 2017\] [A Short Survey on Taxonomy Learning from Text Corpora: Issues, Resources and Recent Advances](http://aclweb.org/anthology/D17-1123) 


### Hypernymy Discovery & Lexical Entailment

- \[IJCAI 2015\] [Learning Term Embeddings for Hypernymy Identification](https://www.ijcai.org/Proceedings/15/Papers/200.pdf) 
- \[ACL 2016\] [Improving Hypernymy Detection with an Integrated Path-based and Distributional Method](https://www.aclweb.org/anthology/P16-1226) (HypeNet) 
	* Code: [https://github.com/vered1986/HypeNET](https://github.com/vered1986/HypeNET)
- \[COLING 2016 CogALex-V\] [LexNET -- Integrated Path-based and Distributional Method for the Identification of Semantic Relations](https://www.aclweb.org/anthology/W16-5310)
	* Code: [https://github.com/vered1986/LexNET](https://github.com/vered1986/LexNET)
- \[SemEval 2016\] [TAXI at SemEval-2016 Task 13: a Taxonomy Induction Method based on Lexico-Syntactic Patterns, Substrings and Focused Crawling](https://www.aclweb.org/anthology/S16-1206)
- \[EMNLP 2016\] [Relations such as Hypernymy: Identifying and Exploiting Hearst Patterns in Distributional Vectors for Lexical Entailment](https://aclweb.org/anthology/D16-1234) 
	* Code: [https://github.com/stephenroller/emnlp2016](https://github.com/stephenroller/emnlp2016)
- \[EMNLP 2016\] [Learning Term Embeddings for Taxonomic Relation Identification Using Dynamic Weighting Neural Network](https://www.aclweb.org/anthology/D16-1039) 
- \[EACL 2017\] [Hypernyms under Siege: Linguistically-motivated Artillery for Hypernymy Detection](https://www.aclweb.org/anthology/E17-1007) 
	* Code: [https://github.com/vered1986/UnsupervisedHypernymy](https://github.com/vered1986/UnsupervisedHypernymy)
- \[EMNLP 2017\] [Hierarchical Embeddings for Hypernymy Detection and Directionality](https://aclweb.org/anthology/papers/D/D17/D17-1022/) (HyperVec)
	* Code: [https://github.com/nguyenkh/HyperVec](https://github.com/nguyenkh/HyperVec)
- \[NAACL 2018\] [Distributional Inclusion Vector Embedding for Unsupervised Hypernymy Detection](https://www.aclweb.org/anthology/N18-1045) 
- \[NAACL 2018\] [Specialising Word Vectors for Lexical Entailment](https://www.aclweb.org/anthology/N18-1103) 
	* Code: [https://github.com/nmrksic/lear](https://github.com/nmrksic/lear)
- \[SEM 2018\] [Term Definitions Help Hypernymy Detection](https://www.aclweb.org/anthology/S18-2025) 
- [Hearst Patterns Revisited: Automatic Hypernym Detection from Large Text Corpora](https://www.aclweb.org/anthology/P18-2057) \[ACL 2018\]
	* Code: [https://github.com/facebookresearch/hypernymysuite](https://github.com/facebookresearch/hypernymysuite)
- \[AAAI 2019\] [Improving Hypernymy Prediction via Taxonomy Enhanced Adversarial Learning](https://chywang.github.io/papers/aaai2019.pdf) 
	* Code: [https://github.com/chywang/TEAL](https://github.com/chywang/TEAL)
- \[WWW 2019\] [A Family of Fuzzy Orthogonal Projection Models for Monolingual and Cross-lingual Hypernymy Prediction](https://chywang.github.io/papers/www2019.pdf)
	* Code: [https://github.com/chywang/FOP](https://github.com/chywang/FOP)
- \[CIKM 2019\] [Discovering Hypernymy in Text-Rich Heterogeneous Information Network by Exploiting Context Granularity](https://arxiv.org/pdf/1909.01584.pdf)
	* Code: [https://github.com/ysyushi/HyperMine](https://github.com/ysyushi/HyperMine)
- \[AAAI 2020\] [Hypernym Detection Using Strict Partial Order Networks](https://arxiv.org/pdf/1909.10572.pdf)
- \[ACL 2020\] [BiRRE: Learning Bidirectional Residual Relation Embeddings for Supervised Hypernymy Detection](https://chywang.github.io/papers/acl2020.pdf)
- \[ACL 2020\] [Hypernymy Detection for Low-Resource Languages via Meta Learning]()


### Concept Taxonomy Construction (Instance-based Taxonomy)

- \[ACL 2006\] [Semantic Taxonomy Induction from Heterogenous Evidence](http://aclweb.org/anthology/P06-1101) 
- \[AAAI 2007\] [Deriving a Large Scale Taxonomy from Wikipedia](https://pdfs.semanticscholar.org/c360/b473ae80b715c5b725c592b6ab04fd4ac430.pdf) 
- \[ACL 2009\] [A Metric-based Framework for Automatic Taxonomy Induction](http://aclweb.org/anthology/P09-1031) 
- \[EMNLP 2010\] [A Semi-Supervised Method to Learn and Construct Taxonomies using the Web](http://aclweb.org/anthology/D10-1108) 
- \[CIKM 2010\] [MENTA: Inducing Multilingual Taxonomies from Wikipedia](http://gerard.demelo.org/papers/demelo-menta-cikm2010.pdf) 
- \[IJCAI 2011\] [A graph-based algorithm for inducing lexical taxonomies from scratch](https://www.ijcai.org/Proceedings/11/Papers/313.pdf) 
- \[SIGMOD 2012\] [Probase: A probabilistic taxonomy for text understanding](https://www.microsoft.com/en-us/research/wp-content/uploads/2012/05/paper.pdf) 
- \[ACL 2014\][Learning Semantic Hierarchies via Word Embeddings](https://www.aclweb.org/anthology/P14-1113) 
- \[ACL 2014\] [Two Is Bigger (and Better) Than One -- the Wikipedia Bitaxonomy Project](http://aclweb.org/anthology/P14-1089) 
	* Resources: [http://wibitaxonomy.org/](http://wibitaxonomy.org/)
- \[ACL 2014\] [Structured Learning for Taxonomy Induction with Belief Propagation](http://aclweb.org/anthology/P14-1098) 
- \[EMNLP 2014\] [Taxonomy Construction Using Syntactic Contextual Evidence](http://aclweb.org/anthology/D14-1088) 
- \[EMNLP 2015\] [Incorporating Trustiness and Collective Synonym and Contrastive Evidence into Taxonomy Construction](http://aclweb.org/anthology/D15-1117) 
- \[ICDM 2015\] [Automatic Taxonomy Extraction from Bipartite Graphs](https://ieeexplore.ieee.org/document/7373326) 
- \[ACL 2016\] [Learning Concept Taxonomies from Multi-modal Data](http://aclweb.org/anthology/P16-1169) 
- \[COLING 2016\] [Revisiting Taxonomy Induction over Wikipedia](http://www.aclweb.org/anthology/C16-1217) 
- \[CIKM 2017\] [Taxonomy Induction using Hypernym Subsequences](https://arxiv.org/pdf/1704.07626.pdf) 
- \[NAACL 2018 \] [Comparing Constraints for Taxonomic Organization](https://www.aclweb.org/anthology/N18-1030) 
	* Code: [https://github.com/acocos/tax-org](https://github.com/acocos/tax-org)
- \[KDD 2018\] [HiExpan: Task-Guided Taxonomy Construction by Hierarchical Tree Expansion](http://hanj.cs.illinois.edu/pdf/kdd18_jshen.pdf) 
	* Code: [https://github.com/mickeystroller/HiExpan](https://github.com/mickeystroller/HiExpan)
- \[ACL 2018\] [End-to-End Reinforcement Learning for Automatic Taxonomy Induction](http://aclweb.org/anthology/P18-1229) 
	* Code: [https://github.com/morningmoni/TaxoRL](https://github.com/morningmoni/TaxoRL)
- \[ACL 2019\] [Inferring Concept Hierarchies from Text Corpora via Hyperbolic Embeddings](https://arxiv.org/pdf/1902.00913.pdf) 
- \[ACL 2020\] [Taxonomy Construction of Unseen Domains via Graph-based Cross-Domain Knowledge Transfer]()
	* Code: [https://github.com/IBM/gnn-taxo-construction](https://github.com/IBM/gnn-taxo-construction)

### Topic Taxonomy Construction (Clustering-based Taxonomy)

- \[KDD 2012\] [Automatic Taxonomy Construction from Keywords](http://cgcad.thss.tsinghua.edu.cn/shixia/publications/brt/paper.pdf) 
- \[KDD 2013\] [A Phrase Mining Framework for Recursive Construction of a Topical Hierarchy](https://uofi.app.box.com/v/kdd13-cathy) 
- \[ACL 2015\] [Efficient Methods for Inferring Large Sparse Topic Hierarchies](http://aclweb.org/anthology/P15-1075) 
- \[KDD 2018\] [TaxoGen: Unsupervised Topic Taxonomy Construction by Adaptive Term Embedding and Clustering](http://hanj.cs.illinois.edu/pdf/kdd18_czhang.pdf) 
	* Code: [https://github.com/franticnerd/taxogen](https://github.com/franticnerd/taxogen)
- \[WWW 2020\] [NetTaxo: Automated Topic Taxonomy Construction from Text-Rich Network](http://hanj.cs.illinois.edu/pdf/www20_jshang.pdf)


### Taxonomy Expansion & Enrichment

- \[CIKM 2012\] [A graph-based approach for ontology population with named entities](https://dl.acm.org/citation.cfm?doid=2396761.2396807) 
- \[WWW 2014\] [A Hierarchical Dirichlet Model for Taxonomy Expansion for Search Engines](http://yichang-cs.com/yahoo/www14_local.pdf) 
- \[NAACL 2015\] [Reserating the awesometastic: An automatic extension of the WordNet taxonomy for novel terms](https://www.aclweb.org/anthology/N15-1169) 
- \[SemEval 2016\] [SemEval-2016 Task 14: Semantic Taxonomy Enrichment](https://www.aclweb.org/anthology/S16-1169) 
- \[SIGIR 2018\] [Enriching Taxonomies With Functional Domain Knowledge](https://dl.acm.org/doi/10.1145/3209978.3210000)
- \[ACL 2019\] [Every child should have parents: a taxonomy refinement algorithm based on hyperbolic term embeddings](https://www.aclweb.org/anthology/P19-1474/) 
	* Code: [https://github.com/uhh-lt/Taxonomy_Refinement_Embeddings](https://github.com/uhh-lt/Taxonomy_Refinement_Embeddings)
- \[ACL 2019\] [Automatic Taxonomy Induction and Expansion](https://www.aclweb.org/anthology/D19-3005.pdf) 	
- \[AKBC 2019\] [Synonym Expansion for Large Shopping Taxonomies](https://openreview.net/pdf?id=rJx2g-qaTm)
- \[WWW 2020\] [Expanding Taxonomies with Implicit Edge Semantics](http://emaadmanzoor.com/papers/20-www-arborist.pdf)
	* Website w/ code, slides, video, etc.: [https://cmuarborist.github.io/](https://cmuarborist.github.io/)
- \[WWW 2020\] [TaxoExpan: Self-supervised Taxonomy Expansion with Position-Enhanced Graph Neural Network](https://arxiv.org/abs/2001.09522)
	* Code: [https://github.com/mickeystroller/TaxoExpan](https://github.com/mickeystroller/TaxoExpan)
- \[KDD 2020\] [STEAM: Self-Supervised Taxonomy Expansion with Mini-Paths](https://arxiv.org/pdf/2006.10217.pdf)
	* Code: [https://github.com/yueyu1030/STEAM](https://github.com/yueyu1030/STEAM)


### Taxonomy Application

- \[CIKM 2004\] [Taxonomy-driven computation of product recommendations](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.90.3304&rep=rep1&type=pdf) 
- \[VLDB 2012\] [Supercharging Recommender Systems using Taxonomies for Learning User Purchase Behavior](https://arxiv.org/abs/1207.0136) 
- \[WSDM 2019\] [Taxonomy-Aware Multi-Hop Reasoning Networks for Sequential Recommendation](https://dl.acm.org/citation.cfm?id=3290972)
	* Code: [https://github.com/RUCDM/TMRN](https://github.com/RUCDM/TMRN)
- \[KDD 2019\] [A User-Centered Concept Mining System for Query and Document Understanding at Tencent ](https://arxiv.org/pdf/1905.08487.pdf)
	* Code: [https://github.com/BangLiu/ConcepT](https://github.com/BangLiu/ConcepT)
- \[KDD 2019\] [Universal Representation Learning of Knowledge Bases by Jointly Embedding Instances and Ontological Concepts](http://web.cs.ucla.edu/~yzsun/papers/2019_KDD_JOIE.pdf) 
	* Code: [https://github.com/JunhengH/joie-kdd19](https://github.com/JunhengH/joie-kdd19)
- \[CIKM 2019\] [STAR: Spatio-Temporal Taxonomy-Aware Tag Recommendation for Citizen Complaints.pdf](https://www.microsoft.com/en-us/research/uploads/prod/2019/10/lp0249-gaoA.pdf)
	* Code: [https://github.com/jygao97/STAR](https://github.com/jygao97/STAR)
- \[ACL 2020\] [TXtract: Taxonomy-Aware Knowledge Extraction for Thousands of Product Categories](https://arxiv.org/pdf/2004.13852.pdf)


### Joint Taxonomy Construction and Application

- \[EMNLP 2012\] [Constructing Task-Specific Taxonomies for Document Collection Browsing](http://aclweb.org/anthology/D12-1117) 
- \[WSDM 2014\] [Taxonomy Discovery for Personalized Recommendation](https://ai.google/research/pubs/pub42499) 
- \[KDD 2018\] [On Interpretation of Network Embedding via Taxonomy Induction](http://www.public.asu.edu/~jundongl/paper/KDD18_Network_Embedding_Interpretation.pdf) 
- \[WWW 2019\] [TiFi: Taxonomy Induction for Fictional Domains](https://arxiv.org/pdf/1901.10263.pdf) 
