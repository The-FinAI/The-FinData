# finance_benchmark

the benchmark for finance

金融领域 评测/比赛，数据集，论文和预训练模型资源汇总。

Summary of finance evaluations/competitions, datasets, papers and pre-trained models.


## 1. Evaluation/Competition

### 1.1 Ongoing Contests

#### 1.1.1 FNS-2023 Shared Task "Financial Narrative Summarisation"

- Source: FNS-2023 Shared Task: "Financial Narrative Summarisation"
- Introduction: The Financial Narrative Summarisation (FNS 2023) is a shared task designed to highlight the benefits and challenges of applying automated text summarisation to financial narratives. Focused on annual reports from UK, Spanish, and Greek firms, it requires participants to extract information from narrative sections to generate single summaries that reflect the firms' financial trend over the past year. The task utilizes a dataset extracted from 3,863 annual reports, distributed across training, testing, and validation sets. The participants' models need to operate effectively in English, Spanish, and Greek to be successful in the competition.
- [Official address](http://wp.lancs.ac.uk/cfie/fns2023/)

#### 1.1.2 FinTOC-2023 Shared Task: "Financial Document Structure Extraction"

- Source:  FinTOC-2023 Shared Task: "Financial Document Structure Extraction"
- Introduction: The Financial Document Structure Extraction task, FinTOC-2023, at the Financial Narrative Processing Workshop (FNP 2023), aims to address the challenge of extracting structural information from a range of financial documents. This task's primary focus is to develop efficient algorithms for Table of Contents (TOC) extraction from diverse financial documents, with the goal of demonstrating the versatility of machine learning in handling this task. This edition introduces a comprehensive dataset with both textual and visual (spatial) annotations, facilitating a more holistic analysis of financial documents. The languages involved include English, French, and Spanish, with a newly introduced Spanish track contributed by the Autonomous University of Madrid.
- [Official address](http://wp.lancs.ac.uk/cfie/fintoc2023/)

#### 1.1.3 FinCausal-2023 Shared Task: "Financial Document Causality Detection"

- Source: FinCausal-2023 Shared Task: "Financial Document Causality Detection"

- Introduction: The Financial Document Causality Detection Task, a part of the 5th Financial Narrative Processing Workshop (FNP 2023), is designed to identify causality within financial narratives in English and Spanish. The goal is to identify the elements within a sentence or paragraph that relate to the cause and the effect. For the English subtask, the dataset comes from 2019 financial news articles and the Edgar Database, focusing on quantified effects. The Spanish dataset, introduced for the first time, consists of Spanish financial annual reports from 2014 to 2018, seeking to detect all types of causes and effects. The task design varies, with English segments made up of up to three sentences and Spanish ones consisting of full paragraphs.
- [Official address](http://wp.lancs.ac.uk/cfie/fincausal2023/)

#### 1.1.4 ConvFinQA challenge

- Source: The 1st Workshop on Robust NLP for Finance (RobustFin)
- Introduction: The ConvFinQA Challenge, launching on April 5th, 2023, seeks to automate the analysis of a large corpus of financial documents through conversational question-answering (QA). The dataset, presented in the ConvFinQA paper, supports this large-scale task. Participants are required to submit their model results on the entire test set via the Codalab leaderboard for final evaluation, following which they must format their papers according to the ACM Conference Proceeding templates and submit them for review. The challenge allows dual submissions and does not enforce an anonymity period. The winners will be recognized as the champion, runner-up, and honorable mention, with awards for these positions.
- [Official address](https://robustfin.github.io/2023/shared_task)

#### 1.1.5 FinNLP-2023 Shared Task: "Multi-Lingual ESG Issue Identification (ML-ESG)"

- Source: FinNLP-2023 Shared Task: "Multi-Lingual ESG Issue Identification (ML-ESG)"
- Introduction: FinNLP-2023 presents a new dataset for the FinNLP community to explore multi-lingual ESG issue identification task based on MSCI ESG rating guidelines, where ESG-related news can be classified into 35 key issues. The challenge is to identify ESG issues in news articles in English, Chinese, and French, and annotation has been conducted on the raw material. In the Chinese dataset, issues from SASB Standard are merged into MSCI guidelines.
- [Official address](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp-2023/shared-task-esg-issue)


### 1.2 Ended assessments/competitions

#### 1.2.1 FinNLP-2022@EMNLP Shared Task: "Evaluating the Rationales of Amateur Investors (ERAI)"

- Source: FinNLP-2022 Shared Task: "Evaluating the Rationales of Amateur Investors (ERAI)"
- Introduction: FinNLP-2022 aims to create a platform for international participants to exchange knowledge on applying NLP to the FinTech domain, an industry that focuses on using technology to improve financial activity. With recent attention in the AI community on analyzing finance and economics documents, FinNLP aims to bridge the gap between NLP research and financial applications. One of the expected outcomes of FinNLP is to introduce financial domain insights to the NLP community, identify challenging problems in blending FinTech and NLP, shape future research directions, and broaden the interdisciplinary research area's scope, and the datasets are collected from PTT and Mobile01.
- [Official address](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp-2022-emnlp/erai-shared-task)

#### 1.2.2 FinNLP-2022@IJCAI Shared Task: "Learning Semantic Similarities for the Financial Domain.Extended edition to ESG insights (FinSim4-ESG)"

- Source: FinNLP-2022@IJCAI Shared Task: "Learning Semantic Similarities for the Financial Domain.Extended edition to ESG insights (FinSim4-ESG)"
- Introduction: FinSim4-ESG is a shared task aimed at expanding the coverage of manual resources using automatic methods in the financial domain, specifically in the "Environment, Social and Governance (ESG)" related issues. The task proposes two sub-tasks, with the first sub-task requiring participants to enrich an in-house sustainable finance taxonomy using financial and sustainability reports to induce semantically related terms to the concepts in the training set. The second sub-task requires participants to design a system that can automatically classify sentences into sustainable or unsustainable sentences, making use of the enriched taxonomy. Performance will be measured based on accuracy and recall. The task encourages the use of contextual word embeddings such as BERT and resources related to ESG and sustainability, including the EU taxonomy.
- [Official address](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp-2022/shared-task-finsim4-esg)
  
#### 1.2.3 FinNLP-2021 Shared Task: "Learning Semantic Similarities for the Financial Domain (FinSim-3)"

- Source: FinNLP-2021 Shared Task: "Learning Semantic Similarities for the Financial Domain (FinSim-3)"
- Introduction: FinSim-3 is a shared task that aims to evaluate semantic representations by automatically classifying carefully selected Financial terms against a domain ontology. The task requires participants to design a system that can classify Financial terms into the most relevant hypernym concept in an external ontology. The new edition proposes an extended dataset with more diversified Financial concepts and encourages the use of relevant resources such as ontologies, lexica, and contextual word embeddings such as BERT. The Financial Industry Business Ontology (FIBO) is used to measure the performance of the systems based on accuracy and recall. The task is open to everyone except the co-chairs of the organizing team, who cannot submit a system and serve as an authority to resolve any disputes concerning ethical issues or completeness of system descriptions. This task combines unsupervised corpus-derived representations and manually tagged resources, with the aim of expanding the coverage of manual resources using automatic methods.
- [Official address](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp2021/shared-task-finsim)

#### 1.2.4 FinNLP-2020 Shared Task: "Learning Semantic Representations for the Financial Domain (FinSim-2)"

- Source: FinNLP-2020 Shared Task: "Learning Semantic Representations for the Financial Domain (FinSim-2)"
- Introduction:The FinSim 2020 shared task, co-located with the FinNLP workshop, aims to automatically learn effective and precise semantic models to process financial documents. The task combines unsupervised corpus-derived representations like word embeddings and manually tagged resources such as corpora, lexica, taxonomies, and ontologies to expand the coverage of manual resources using automatic methods. Participants will design a system to classify financial terms into the most relevant hypernym in an external ontology and will be evaluated based on accuracy and recall. The task encourages the use of relevant resources such as ontologies, lexica, and contextual word embeddings such as BERT. The task is the first of its kind proposed for the financial domain.
- [Official address](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp2020/shared-task-finsim)

#### 1.2.5 FinNLP-2020 Shared Task: FinSBD-2

- Source: FinNLP-2020 Shared Task: FinSBD-2
- Introduction: Sentence boundary detection is a crucial first step in NLP applications, but research has focused on formal texts without addressing noisy texts in PDF files, such as financial documents. Financial prospectuses are official PDF documents that require parsing, cleaning, and formatting to extract information. They contain visual demarcations, such as lists and bullets, which require distinguishing between sentences and lists and organizing items. The shared task includes detecting sentence boundaries and extracting lists, which can improve information extraction accuracy.
- [Official address](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp2020/shared-task-finsbd-2)

#### 1.2.6 FinNALP-2019 Shared Task: "Sentence Boundary Detection in PDF Noisy Text in the Financial Domain (FinSBD-2019)

- Source: FinNALP-2019 Shared Task: "Sentence Boundary Detection in PDF Noisy Text in the Financial Domain (FinSBD-2019)
- Introduction: Sentence boundary detection (SBD) is a crucial step in many NLP applications, but it has not received enough attention in noisy texts extracted automatically from machine-readable formats such as financial documents. The FinNLP shared task focuses on detecting sentence boundaries in financial prospectuses in English and French by extracting well-segmented sentences from noisy text. Participants will be given textual documents extracted from PDF files and will submit systems for one or both languages. The task is open to everyone, except for the co-chairs of the organizing team. PDF original files and language resources will also be provided.
- [Official address](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp/shared-task-finsbd)

#### 1.2.7 FNS-2022 Shared Task: "Financial Narrative Summarisation"

- Source: FNS-2022 Shared Task: "Financial Narrative Summarisation"
- Introduction: The Financial Narrative Summarisation (FNS 2022) shared task aims to demonstrate the challenges and value of automatic text summarization for financial narrative disclosures in English, Spanish, and Greek from UK annual reports published in PDF. Participants must provide structured single summaries that analyze and assess the business's financial trend over the past year based on different key sections. The evaluation will use the Rouge Java package and focus on the F1-Score on the test set. The task is challenging due to the loose structure of UK annual reports, which require detecting narrative sections before creating summaries. The summary length should not exceed 1000 words. The MultiLing team, with experience in organizing summarization tasks since 2011, will help organize the shared task.
- [Official address](http://wp.lancs.ac.uk/cfie/fns2022/)

#### 1.2.8 FinTOC-2022 Shared Task: "Financial Document Structure Extraction"

- Source: FinTOC-2022 Shared Task: "Financial Document Structure Extraction"
- Introduction: Financial documents published in machine-readable formats are often lacking structure information, making automatic analyses of prospectuses and other financial reports to extract their structure vital. FinTOC shared task focuses on analyzing Financial Prospectuses, which have a sophisticated structure including parts, sections, sub-sections, and sub-sub-sections, and proposes a new track for Spanish documents in addition to English and French. Participants must register and will be provided with a common training dataset containing PDF documents and associated TOC annotation to score systems on both Title detection and TOC generation performance. TOC recognition is a challenging problem due to the visual layout and style differences between documents from different domains, making it difficult to recognize TOC in a large scale collection of heterogeneous documents and books.
- [Official address](http://wp.lancs.ac.uk/cfie/fintoc2022/)

#### 1.2.9 FinCausal-2022 Shared Task: "Financial Document Causality Detection"

- Source: FinCausal-2022 Shared Task: "Financial Document Causality Detection"
- Introduction: The Task aims to develop an ability to explain external events that cause a transformation in the financial landscape, to generate accurate and meaningful financial narrative summaries. Participants will detect which elements of causal sentences relate to the cause and effect. The task dataset has been extracted from 2019 financial news and SEC data, normalized for the research task. The FinCausal Task is part of the Financial Narrative workshop and focuses on detecting causality associated with a quantified fact, defining an event as the arising of a new object or context. Participants will be provided with a sample of text blocks labeled through inter-annotator agreement.
- [Official address](http://wp.lancs.ac.uk/cfie/fincausal2022/)

#### 1.2.10 FNS-2021 Shared Task: "Financial Narrative Summarisation"

- Source: FNS-2021 Shared Task: "Financial Narrative Summarisation"
- Introduction: The Financial Narrative Summarisation (FNS 2021) aims to demonstrate the value and challenges of applying automatic text summarization to financial narrative disclosures in English extracted from UK annual reports in PDF format. Participants are asked to provide structured single summaries reflecting analysis and assessment of a business's financial trend over the past year by extracting information from different key sections. The evaluation will use the Rouge Java package, with the highest F1-Score on the Test set being the main metric for ranking and submission comparisons. UK annual reports have a looser structure, making automatic summarization challenging due to the need to detect narrative sections before creating summaries. The summary length should not exceed 1000 words, and the MultiLing team will help organize the shared task.
- [Official address](http://wp.lancs.ac.uk/cfie/fns2021/)

#### 1.2.11 FinTOC-2021 Shared Task: "Financial Document Structure Extraction"

- Source: FinTOC-2021 Shared Task: "Financial Document Structure Extraction"
- Introduction: Financial documents published in machine-readable formats lack structure information, making automatic analyses of prospectuses to extract their structure vital. The FinTOC shared task focuses on analyzing Financial Prospectuses, where investment funds describe their characteristics and investment modalities, without a standardized format and often without a table of contents (TOC). The task proposes two tracks for English and French documents, evaluating systems on both Title detection and TOC generation performance. Participants need to register and will receive a common training dataset containing PDF documents and associated TOC annotation. Financial documents have a more sophisticated structure including parts, sections, sub-sections, and sub-sub-sections, making TOC recognition a challenging problem.
- [Official address](http://wp.lancs.ac.uk/cfie/fintoc2021/)

#### 1.2.12 FinCausual-2021 Shared Task: "Financial Document Causality Detection”

- Source: FinCausual-2021 Shared Task: "Financial Document Causality Detection”
- Introduction: The task aims to develop the ability to explain external events that cause a transformation in the financial landscape, in order to generate accurate and meaningful financial narrative summaries. The task dataset has been extracted from 2019 financial news and SEC data, normalized for the research task. Participants will detect which elements of causal sentences relate to the cause and effect, with a focus on determining causality associated with a quantified fact. An event is defined as the arising or emergence of a new object or context in regard to a previous situation. Participants will be provided with a sample of text blocks labeled through inter-annotator agreement.
- [Official address](http://wp.lancs.ac.uk/cfie/fincausal2021/)

#### 1.2.13 FNS-2020 Shared Task: "Financial Narrative Summarisation"

- Source: FNS-2020 Shared Task: "Financial Narrative Summarisation"
- Introduction: The Financial Narrative Summarisation (FNS 2020) task aims to demonstrate the value and challenges of applying automatic text summarization to financial narrative disclosures from UK annual reports in PDF format. Participants are asked to provide structured single summaries based on real-world financial annual reports of UK firms by extracting information from different key sections. The goal is to evaluate the summary's analysis and assessment of the financial trend of the business over the past year, using the JRouge package for ROUGE. Annual reports from UK firms listed on The London Stock Exchange will be used, which have a looser structure than those produced in the US, making automatic summarization challenging. The task requires extracting from different key sections, typically containing reviews by the firm's management and board of directors, and not exceeding 1000 words. The MultiLing team will help organize the shared task, including evaluating the results and final proceedings.
- [Official address](http://wp.lancs.ac.uk/cfie/fns2020/)

#### 1.2.14 FinTOC-2020 Shared Task: "Financial Document Structure Extraction"

- Source: FinTOC-2020 Shared Task: "Financial Document Structure Extraction"
- Introduction: The FinTOC shared task focuses on analyzing Financial Prospectuses, which have a more sophisticated structure including parts, sections, sub-sections, and sub-sub-sections, making TOC recognition a challenging problem. The task proposes two tracks for English and French documents, evaluating systems on both Title detection and TOC generation performance. Participants need to register and will receive a common training dataset containing PDF documents and associated TOC annotation. Financial documents have a lack of standardization, making automatic analyses of prospectuses to extract their structure vital. The task aims to simplify data formats to make it accessible for researchers to participate and submit their system outputs.
- [Official address](http://wp.lancs.ac.uk/cfie/fintoc2020/)

#### 1.2.15 FinCausual-2020 Shared Task: "Financial Document Causality Detection”

- Source: FinCausual-2020 Shared Task: "Financial Document Causality Detection”
- Introduction: The Financial Document Causality Detection Task aims to explain why a transformation occurs in the financial landscape by detecting the external causes or chain of events that led to a financial object's modification or event occurrence. The task evaluates which events or chain of events can cause a financial object to be modified or an event to occur in a given external context, which is available in financial news. Participants will evaluate whether a sentence is causal or not and detect which elements of the sentence relate to the cause and which relate to the effect. The dataset is extracted from 2019 financial news provided by Qwam and SEC data from the Edgar Database, normalized for the research task. The task focuses on detecting causality associated with the transformation of financial objects embedded in quantified facts. The shared task contains two sub-tasks: Sentence Classification and Relation Detection.
- [Official address](http://wp.lancs.ac.uk/cfie/fincausal2020/)

#### 1.2.16 FinTOC-2019 Shared Task: "Financial Document Structure Extraction"

- Source: FinTOC-2019 Shared Task: "Financial Document Structure Extraction"
- Introduction: The Financial Narrative Processing Workshop presents a shared task on Financial Document Structure Extraction. The task aims to automatically analyze Financial Prospectuses to extract structural information and build a table of contents. The task contains two sub-tasks: Title Detection and TOC Structure Extraction. Participants need to register and will be provided with a common training dataset, a common development set, and a blind test dataset for evaluation. The dataset includes both PDF and XML versions of the documents.
- [Official address](http://wp.lancs.ac.uk/cfie/shared-task/)

#### 1.2.17 FNP-2018 

- Source: FNP-2018 
- Introduction: The workshop focuses on the use of NLP, ML, and CL methods for financial text mining and FNP. There is a growing interest in automatic and computer-aided approaches for extracting, summarizing, and analyzing financial data. The workshop aims to develop a better understanding of financial disclosure quality and factors influencing the quality of information disclosed to investors. The workshop encourages efforts to build resources and tools to advance research on financial narrative processing due to the limited availability of publicly available datasets and high cost and limited access to content providers. The workshop aims to advance research on lexical properties and narrative aspects of corporate disclosures, including glossy annual reports, financial documents, press releases, conference calls, media articles, and social media. The motivation is to clarify complex accounting methods, provide information on corporate strategy and social responsibility, and provide forward-looking information for investors, while also detecting potential obfuscation and manipulation of accounting results.
- [Official address](http://wp.lancs.ac.uk/cfie/fnp2018/)

### 1.3 Spanish

- FNS-2022 Shared Task: "Financial Narrative Summarisation", [Official address](http://wp.lancs.ac.uk/cfie/fns2023/)
- FNS-2022 Shared Task: "Financial Narrative Summarisation", [Official address](http://wp.lancs.ac.uk/cfie/fns2022/)
- FinTOC-2022 Shared Task: "Financial Document Structure Extraction", [Official address](http://wp.lancs.ac.uk/cfie/fintoc2022/)


## 2 Datasets

### 2.1 English Datasets

#### 2.1.1 FLUE datasets (26K)

- Source: When FLUE Meets FLANG: Benchmarks and Large Pretrained Language Model for Financial Domain
- Introduction: FLUE (Financial Language Understanding Evaluation) is a comprehensive benchmark, designed to foster advancements in the understanding of financial language. This benchmark is constituted from five diverse financial domain-specific datasets. The five tasks include financial sentiment analysis (from two different sources: FPB with 4,845 entries and FiQA SA with 1,173 entries), news headline classification (Headline with 11,412 entries), named entity recognition (NER with 1,466 entries), structure boundary detection (FinSBD3 with 756 entries), and question answering (FiQA QA with 6,640 entries). Collectively, these datasets comprise a total of 26,292 entries, providing a heterogeneous and substantial corpus for the development and evaluation of financial language understanding systems.
- [Official address](https://salt-nlp.github.io/FLANG/)

### 2.2 Chinese Datasets

### 2.3 Knowledge and information sources

## 3 Pre-trained model

### 3.1 after GPT

#### 3.1.1 BloombergGPT

- Source: BloombergGPT: A Large Language Model for Finance
- Introduction: Bloomberg has unveiled BloombergGPT, a large-scale generative artificial intelligence model specifically trained on a diverse set of financial data to enhance various natural language processing (NLP) tasks within the finance sector. Built by integrating financial data with general-purpose datasets, the model excels at financial NLP tasks such as sentiment analysis, named entity recognition, news classification, and question answering, without compromising performance on general language model benchmarks. The model was trained on a massive corpus of over 700 billion tokens, derived from a combination of a 363 billion token dataset from Bloomberg's extensive archive of financial documents and a 345 billion token public dataset. Remarkably, BloombergGPT outperforms similarly-sized open models on financial NLP tasks significantly, while maintaining or surpassing performance on general-purpose NLP benchmarks.
- Project: N/A (Not published!)

#### 3.1.2 Xuanyuan

- Source: XuanYuan: A Large Chinese Financial Chat Model with Hundreds of Billions Parameters
- Introduction: XuanYuan, the first domestically developed and open-sourced Chinese chat model with hundreds of billions of parameters, has been specifically optimized for the Chinese financial sector. Building upon BLOOM-176B, XuanYuan was pre-trained and fine-tuned for both the general and financial Chinese domains, exhibiting competence in handling general inquiries as well as financial-related questions. The model, available for download on Huggingface, outperforms the four main open-source models in the financial sector with a win rate of 63.33% in 150 answers. Despite its impressive financial domain performance, XuanYuan also excels in general capabilities, matching or exceeding the performance of ChatGPT on 71% of diversified questions in a general test set. Developed to spur academic research, technology exploration, and personal learning, the open-source XuanYuan serves as a powerful tool for advancing dialogue systems and financial technology.
- [Project](https://github.com/Duxiaoman-DI/XuanYuan)

### 3.2 before GPT

### 3.3 General Domain

## 4 Related Papers





