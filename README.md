# finance_benchmark

the benchmark for finance

金融领域 评测/比赛，数据集，论文和预训练模型资源汇总。

Summary of finance evaluations/competitions, datasets, papers and pre-trained models.


## 1. Evaluation/Competition

### 1.1 Ongoing Contests

#### 1.1.1 FNS-2023 Shared Task Financial Narrative Summarisation

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

### 1.2 Ended assessments/competitions

## 2 Datasets

### 2.1 English Datasets

#### 2.1.1 FLUE datasets (26K)

- Source: When FLUE Meets FLANG: Benchmarks and Large Pretrained Language Model for Financial Domain
- Introduction: FLUE (Financial Language Understanding Evaluation) is a comprehensive benchmark, designed to foster advancements in the understanding of financial language. This benchmark is constituted from five diverse financial domain-specific datasets. The five tasks include financial sentiment analysis (from two different sources: FPB with 4,845 entries and FiQA SA with 1,173 entries), news headline classification (Headline with 11,412 entries), named entity recognition (NER with 1,466 entries), structure boundary detection (FinSBD3 with 756 entries), and question answering (FiQA QA with 6,640 entries). Collectively, these datasets comprise a total of 26,292 entries, providing a heterogeneous and substantial corpus for the development and evaluation of financial language understanding systems.
- [Official address](https://salt-nlp.github.io/FLANG/)

### 2.2 Chinese Datasets

#### 2.2.1 BQ Corpus（4.2M）

- Sourse：Chen J, Chen Q, Liu X, et al. The bq corpus: A large-scale domain-specific Chinese corpus for sentence semantic equivalence identification[C]//Proceedings of the 2018 conference on empirical methods in natural language processing. 2018: 4946-4951.
- Introduction： The issue-matching data for the banking and finance sector, which includes issue pairs drawn from a year's worth of online banking system logs, is the most extensive set of issue-matching data available for the banking sector.
- [Official address](https://www.luge.ai/#/luge/dataDetail?id=15)

#### 2.2.2 CCKS2022 FEW-SHOT event extraction dataset for the financial sector

- Source： The CCKS2022 "FEW-SHOT Event Extraction for the Financial Sector" academic evaluation task (https://www.biendata.xyz/competition/ccks2022_eventext/)
- Introduction: This dataset is derived from the academic evaluation task CCKS2022 "FEW-SHOT Event Extraction for the Financial Sector" academic evaluation task (https://www.biendata.xyz/competition/ccks2022_eventext/), provided by the Ant Group and the Institute of Automation, Chinese Academy of Sciences. The text corpus is taken from public news and reports on the Internet. Given a schema of M event types and their elements, the annotated data of N (N<M) of these event types are given in the training data, and the M event types and their elements are extracted from the test set.
- [Official address]((https://tianchi.aliyun.com/dataset/136800))

#### 2.2.3 CCKS 2019 Chapter-level event subject extraction dataset for the financial sector

- Source： CCKS2019 "Chapter-level event subject extraction for the financial sector" academic assessment task（https://www.biendata.xyz/competition/ccks_2019_4/）
- Introduction： This dataset is derived from the academic evaluation task CCKS2019 "Chapter-level event subject extraction for the financial domain" academic evaluation task (https://www.biendata.xyz/competition/ccks_2019_4/), jointly provided by Ant Group and the Institute of Automation, Chinese Academy of Sciences."Event identification" is one of the most important tasks in the field of public opinion monitoring and in the financial sector, where "events" are an important reference for investment analysis and asset management decisions. The complexity of "event identification" lies in determining of the type of event and the subject of the event. We refer to the subject of a particular type of event as the subject of the event, and in this task, the scope of the issue of the event is limited to: companies and institutions. The range of event types is defined as 22 types: problems with products, reduction of executives, violations of law, etc.
- [Official address](https://tianchi.aliyun.com/dataset/111237)

#### 2.2.4 FinNL

- Source：BBT-Fin: Comprehensive Construction of Chinese Financial Domain Pre-trained Language Model, Corpus and Benchmark
- Introduction： A financial news classification dataset. Given financial news articles, the model needs to classify them into up to 15 possible categories, with evaluation measured by F1-Score. The training set contains 8,000 articles, the validation set contains 1,000 articles, and the test set contains 1,000 articles.
- [Official address](https://github.com/ssymmetry/BBT-FinCUGE-Applications/tree/main/FinCUGE_Publish)

#### 2.2.6 FinNA

- Source：BBT-Fin: Comprehensive Construction of Chinese Financial Domain Pre-trained Language Model, Corpus and Benchmark
- Introduction： A financial news summarization dataset. Given financial news articles, the model needs to generate a summary, with evaluation measured by Rouge (Lin, 2004). The training set contains 24,000 articles, the validation set contains 3,000 articles, and the test set contains 3,000 articles.
- [Official address](https://github.com/ssymmetry/BBT-FinCUGE-Applications/tree/main/FinCUGE_Publish)

#### 2.2.7 FinRE

- Source：BBT-Fin: Comprehensive Construction of Chinese Financial Domain Pre-trained Language Model, Corpus and Benchmark
- Introduction： A financial news relation extraction dataset. Given financial news articles and head-tail entity pairs, the model needs to classify the relationship between entity pairs into up to 44 categories, including the null relation, with evaluation measured by F1-Score. The training set contains 7,454 articles, the validation set contains 1,489 articles, and the test set contains 3,727 articles.
- [Official address](https://github.com/ssymmetry/BBT-FinCUGE-Applications/tree/main/FinCUGE_Publish)

#### 2.2.8 FinFE

- Source：BBT-Fin: Comprehensive Construction of Chinese Financial Domain Pre-trained Language Model, Corpus and Benchmark
- Introduction： A financial social media text sentiment classification dataset. Given financial social media text, the model needs to classify the sentiment of the text into negative-neutralpositive categories, with evaluation measured by accuracy. The training set contains 8,000 articles, the validation set contains 1,000 articles, and the test set contains 1,000 articles.
- [Official address](https://github.com/ssymmetry/BBT-FinCUGE-Applications/tree/main/FinCUGE_Publish)

#### 2.2.9 FinQA

- Source：BBT-Fin: Comprehensive Construction of Chinese Financial Domain Pre-trained Language Model, Corpus and Benchmark
- Introduction： A financial news announcement event question-answering dataset, derived from the DuEE-fin (Han et al., 2022) dataset. Given financial news or announcement text and a question related to an event mentioned in the text, the model needs to generate an answer to the question based on the text, with evaluation measured by F1-Score. The training set contains 16,000 articles, the validation set contains 2,000 articles, and the test set contains 2,000 articles.
- [Official address](https://github.com/ssymmetry/BBT-FinCUGE-Applications/tree/main/FinCUGE_Publish)

#### 2.2.10 FinNSP

- Source：BBT-Fin: Comprehensive Construction of Chinese Financial Domain Pre-trained Language Model, Corpus and Benchmark
- Introduction： Financial negative news and its subject determination dataset. Given financial news or social media text and entities mentioned in the text, the model needs to determine if the text contains negative news related to any entity and identify which entity is the subject of the negative news, with evaluation measured by F1-Score. The training set contains 4,800 articles, the validation set contains 600 articles, and the test set contains 600 articles.
- [Official address](https://github.com/ssymmetry/BBT-FinCUGE-Applications/tree/main/FinCUGE_Publish)

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





