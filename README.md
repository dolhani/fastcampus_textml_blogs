# 패스트캠퍼스, 자연어처리를 위한 머신러닝, 수업관련 포스트입니다.

강의노트, 실습 데이터, 실습 코드는 각각 다음의 repository 에 올려두었습니다.

- 강의 노트   : https://github.com/lovit/textmining-tutorial
- 실습 데이터 : https://github.com/lovit/textmining_dataset
- 실습 코드   : https://github.com/lovit/python_ml4nlp

## 1 일차

- 품사 판별, 형태소 분석, 그리고 미등록단어 문제에 대한 글 입니다. [(링크)](https://lovit.github.io/nlp/2018/04/01/pos_and_oov/)

- Java 로 구현된 Komoran 을 Jupyter notebook 의 python 에서 이용하기 위한 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/04/06/komoran/)

- Java 로 구현된 Komoran 을 Python package 로 만드는 과정과 Java, Python 간의 변수 호환에 대한 내용입니다 [(링크)](https://lovit.github.io/nlp/2018/07/06/java_in_python/)

- 텍스트 데이터를 KoNLPy 를 이용하여 term frequency matrix 로 만드는 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/03/26/from_text_to_matrix/)

- Logistic regression 의 이론설명 입니다. [(링크)](https://lovit.github.io/nlp/machine%20learning/2018/03/22/logistic_regression/)

## 2 일차

- soynlp 의 설치 / word extractor / tokenizer / noun extractor 사용법에 관한 포스트입니다. [(링크)](https://lovit.github.io/nlp/2018/04/09/three_tokenizers_soynlp/)

- 단어 추출 방법 중 하나인 cohesion 과 이를 이용한 L-tokenizer 의 구현 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/04/09/cohesion_ltokenizer/)

- 단어 추출 방법 중 하나인 Accessor Variety 와 Branching Entropy 의 설명입니다. [(링크)](https://lovit.github.io/nlp/2018/04/09/branching_entropy_accessor_variety/)

- 단어 추출 기법의 단어 점수를 이용하는 MaxScoreTokenizer 의 구현 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/04/09/cohesion_ltokenizer/)

- Google translator 에도 쓰이는 unsupervised tokenizer 인 word piece model 의 설명입니다. [(링크)](https://lovit.github.io/nlp/2018/04/02/wpm/)

- 토크나이저와 document representation 에 관련된 내용입니다.어절의 왼쪽 부분음절만 취하는 토크나이저를 이용해도 문서의 정보가 어느 정도 표현됩니다. [(링크)](https://lovit.github.io/nlp/2018/04/02/simplest_tokenizers/)

- 통계 정보를 이용하여 데이터 기반으로 명사를 추출하는 soynlp.noun.LRNounExtractor_v1 의 설명입니다. [(링크)](https://lovit.github.io/nlp/2018/05/07/noun_extraction_ver1/)

- 앞선 명사 추출기의 단점을 분석하고, 이를 보완한 soynlp.noun.LRNounExtractor_v2 의 개발 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/05/08/noun_extraction_ver2/)

- 한국어의 용언 (부사, 형용사)는 어근과 어미 형태소로 구성된 단어입니다. 원형 "하다" 동사는 어미가 변화하여 "하라고, 했는데" 처럼 그 형태가 변합니다. 이와 같은 용언을 활용하는 conjugator 를 구현하는 과정입니다. Conjugator 는 lemmatizer 의 반대 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/06/11/conjugator/)

- 한국어의 용언 (부사, 형용사)는 어근과 어미 형태소로 구성된 단어입니다. "했는데" 처럼 활용된 용언의 원형을 복원하는 lemmatizer 에 대한 설명과 개발 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/06/07/lemmatizer/)

- 형태소의 품사 태깅이 되어 있는 말뭉치가 있을 경우, 데이터 기반으로 lemmatizer 나 conjugator 를 손쉽게 만들 수 있습니다. [(링크)](https://lovit.github.io/nlp/2019/01/22/trained_kor_lemmatizer/)

## 3 일차

- Hidden Markov Model (HMM) 을 이용하여 말뭉치의 패턴을 학습하는 품사 판별기 (형태소 분석기) 의 작동 원리와 모델의 구조적 문제점들 입니다. [(링크)](https://lovit.github.io/nlp/2018/09/11/hmm_based_tagger/)

- Hidden Markov Model (HMM) 을 기반으로 하는 형태소 분석기의 형태소 분석 함수를 만드는 과정입니다 [(링크)](https://lovit.github.io/nlp/2018/10/23/hmm_based_tagger_tag/)

- Conditional Random Field (CRF) 를 이용하여 말뭉치의 패턴을 학습하는 품사 판별기 (형태소 분석기) 의 작동 원리와 HMM 기반 모델과의 차이점들 입니다 [(링크)](https://lovit.github.io/nlp/2018/09/13/crf_based_tagger/)

- scipy.sparse 에 구현된 sparse matrix 에 대한 내용과 이를 다룰 때 주의해야 할 점들 입니다. [(링크)](https://lovit.github.io/nlp/machine%20learning/2018/04/09/sparse_mtarix_handling/)

- Point Mutual Information 을 numpy 를 이용하여 구현하는 내용입니다. Matrix handling 연습을 할 수 있습니다. [(링크)](https://lovit.github.io/nlp/2018/04/22/implementing_pmi_numpy_practice/)

- 평상시 '폭우'라는 단어가 0.1 % 등장하는데, 오늘의 뉴스에서 1 % 등장하였다면 '폭우'의 키워드 점수는 1% / (1% + 0.1%) 로 정의할 수 있습니다. 단어의 출현 빈도 비율을 이용한 키워드 추출 방법의 구현 과정 입니다. [(링크)](https://lovit.github.io/nlp/2018/04/12/proportion_keywords/)

- Logistic regression 에 L1 regularization 을 더하면 키워드를 추출할 수 있습니다. [(링크)](https://lovit.github.io/nlp/machine%20learning/2018/03/24/lasso_keyword/)

- (word, context) co-occurrence 를 계산한 뒤, PMI 를 적용하면 단어의 문맥적 유사도를 표현할 수 있습니다. Co-occurrence 정보를 이용하여 semantics 을 표현하는 방법에 대하여 정리한 "From frequency to meaning, Vector space models of semantics (Turney & Pantel, 2010)" 논문의 리뷰입니다. [(링크)](https://lovit.github.io/machine%20learning/nlp/2018/04/18/from_frequency_to_meaning/)

- (word, context) co-occurrence matrix 에 PMI 를 적용한 뒤, SVD 를 적용하면 Negative sampling 을 이용하는 Skip-gram 의 word vector 와 동일한 값을 얻을 수 있다는 내용의 논문, "Neural Word Embedding as Implicit Matrix Factorization (Levy & Goldberg, 2014)"의 리뷰입니다. [(링크)](https://lovit.github.io/nlp/2018/04/22/context_vector_for_word_similarity/)

- 한국어 용언의 원형을 표현형으로 변환하는 (가다 -> 갔는데) conjugation 의 원리와 코드입니다. [(링크)](https://lovit.github.io/nlp/2018/06/11/conjugator/)

- 한국어 용언의 표현형을 원형으로 변환하는 (갔는데 -> 가다) lemmatization 의 원리와 코드입니다 [(링크)](https://lovit.github.io/nlp/2018/06/07/lemmatizer/)

## 4 일차

- Sequential labeling 에 자주 이용되었던 Conditional Random Field (CRF) 는 potential function 이 적용된 logistic regression 입니다. [(링크)](https://lovit.github.io/nlp/machine%20learning/2018/04/24/crf/)

- Conditional random field 를 이용한 한국어 띄어쓰기 교정기를 만들 수 있습니다. [(링크)](https://lovit.github.io/nlp/machine%20learning/2018/04/24/crf_korean_spacing/)

- Conditiaonal random field 를 이용한 한국어 띄어쓰기 교정기는 공격적인 띄어쓰기 교정을 하는 경향이 있습니다. 이 현상의 원리와 이를 보완하기 위한 휴리스틱 한국어 띄어쓰기 교정 알고리즘의 개발 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/04/25/soyspacing/)

- Decision tree (DT)에 대한 설명과 DT 가 text classification 에 적합하지 않은 이유에 대한 설명입니다. [(링크)](https://lovit.github.io/machine%20learning/2018/04/30/decision_tree/)

- Scikit-learn 에서 제공하는 Decision tree 에 학습된 rules 을 텍스트로 옮기는 과정입니다. 이를 손쉽게 도와주는 packages 들은 존재합니다. 하지만 직접 구현해 봄으로써 tree traversal 을 연습할 수 있습니다. [(링크)](https://lovit.github.io/machine%20learning/2018/04/30/get_rules_from_trained_decision_tree/)

## 5 일차

- 시각화 패키지인 Seaborn 의 튜토리얼 입니다 [(링크)](https://lovit.github.io/visualization/2019/11/22/seaborn_tutorial/)

- 시각화 패키지인 Bokeh 의 튜토리얼 입니다 [(링크)](https://lovit.github.io/visualization/2019/11/22/bokeh_tutorial/)

- Word2Vec 과 Doc2Vec 의 학습 원리 및 역사에 대하여 정리한 글입니다. [(링크)](https://lovit.github.io/nlp/representation/2018/03/26/word_doc_embedding/)

- Word2Vec 이 학습하는 word representation space 에 대하여 이해를 하기 위한 연구인 "All-but-the-top: simple and effective postprocessing for word representations (ICLR 2018)" 의 리뷰와 이에 대한 해석입니다. [(링크)](https://lovit.github.io/nlp/2018/04/05/space_odyssey_of_word2vec/)

- Glove 는 Word2Vec 과 더불어 가장 많이 이용되는 word embedding 방법 중 하나입니다. Word2Vec 과의 차이점에 대한 글입니다 [(링크)](https://lovit.github.io/nlp/representation/2018/09/05/glove/)

- Word2Vec 은 학습 때 보지 못했던 단어에 대해 word vector 를 알 수 없으며, infrequent words 에 대한 word vectors 도 학습이 잘 되지 않습니다. 이러한 단점을 보완하기 위하여 FastText 가 제안되었습니다. 이는 subword embedding 을 이용한 word embedding 방법으로, 미등록 단어와 infrequent words 에 대하여 frequent words 와의 형태적 유사성을 고려한 word vector 를 추정하여 줍니다. [(링크)](https://lovit.github.io/nlp/representation/2018/10/22/fasttext_subword/)

- Gensim Word2Vec 은 embedding vector 에 단어 빈도수 정보가 포함되어 있으며, infrequent words 는 embedding vector 가 잘 학습되지 않기도 합니다. Gensim Word2Vec 학습 시 min_count 설정에 대한 팁과 후처리를 통하여 질 좋은 embedding vector 를 고르는 방법입니다 [(링크)](https://lovit.github.io/nlp/representation/2018/12/05/min_count_of_word2vec/)

- t-SNE 는 벡터 시각화를 위하여 가장 많이 이용되는 임베딩 방법입니다. t-SNE 에서 가장 중요한 패러매터인 perplexity 의 역할과 설정 기준에 대한 글입니다 [(링크)](https://lovit.github.io/nlp/representation/2018/09/28/tsne/)

- MDS, LLE, ISOMAP 의 설명과 t-SNE 까지 포함한 네 종류의 임베딩 방법 간의 시각화 성능 비교 실험입니다. 시각화를 위한 임베딩에서는 네 알고리즘 중 t-SNE 가 안정적인 성능을 보여줍니다 [(링크)](https://lovit.github.io/nlp/representation/2018/09/28/mds_isomap_lle/)

## 6 일차

- Topic modeling 에 관련된 포스트를 작성할 예정입니다.

- Topic modeling 에 이용되는 대표적인 알고리즘인 Latent Dirichlet Allocation (LDA) 의 학습 결과를 시각화하여 설명하는 pyLDAvis 의 사용법 및 pyLDAvis 가 학습하는 정보에 관련된 설명입니다 [(링크)](https://lovit.github.io/nlp/2018/09/27/pyldavis_lda/)

- pyLDAvis 는 LDA 외에도 임의의 토픽 모델링 결과를 모두 시각화 할 수 있습니다. NMF 와 k-means 의 결과를 LDAvis 를 이용하여 시각화 하는 내용입니다 [(링크)](https://lovit.github.io/nlp/2019/06/10/visualize_topic_models_with_pyldavis/)

- Named Entity Recognition (NER) 을 위하여 Conditional Random Field (CRF) 는 이전부터 이용되었으며, 해석의 측면에서 여전히 좋은 모델입니다. CRF 를 이용한 NER model 을 만드는 과정입니다. [(링크)](https://lovit.github.io/nlp/2018/06/22/crf_based_ner/)

## 7 일차

- Random projection 의 설명과, 이를 이용한 Locality Sensitive Hashing 의 원리 입니다. [(링크)](https://lovit.github.io/machine%20learning/vector%20indexing/2018/03/28/lsh/)

- bag-of-words model 처럼 고차원의 sparse vector 로 표현된 데이터의 k-means 에는 Euclidean distance 보다는 Cosine distance 를 이용하는 것이 좋습니다. 그리고 Cosine distance 를 이용하는 k-means 를 Spherical k-means 라 합니다. 이에 대한 설명과 패키지 사용법에 대한 글 입니다 [(링크)](https://lovit.github.io/nlp/machine%20learning/2018/10/16/spherical_kmeans/)

- k-means 를 학습하여 얻은 centroid vector 에 keyword extraction 방법을 적용하면 데이터 기반으로 clustering labeling 을 할 수 있습니다. [(링크)](https://lovit.github.io/nlp/machine%20learning/2018/03/21/kmeans_cluster_labeling/)

- Sparse data 에 대해서는 k-means++ 과 같은 initializer 는 효과적이지 않습니다. Dissimilarity 에 대한 정의가 어려운 sparse data 상황에서의 효율적인 k-means initialization 방법입니다. [(링크)](https://lovit.github.io/nlp/machine%20learning/2018/03/19/kmeans_initializer/)

- 앞서 k-means 의 cluster labeling 방법도 살펴 보았습니다. pyLDAvis 를 이용하면 cluster label 의 결과 및 시각화를 할 수 있습니다. [(링크)](https://lovit.github.io/nlp/2018/09/27/pyldavis_kmeans/)

- Levenshtein distance 와 이를 변형하는 방법입니다. 한글의 초/중/종성을 분리하여 이를 기준으로 string distance 를 계산하는 방법도 포함하고 있습니다. [(링크)](https://lovit.github.io/nlp/2018/08/28/levenshtein_hangle/)

- Inverted index 를 이용하면 Levenshtein distance 가 가까울 가능성이 있는 단어 후보만을 추린 뒤, 이에 대해서만 실제 거리 계산을 하는 효율적인 오탈자 교정기를 만들 수 있습니다 [(링크)](https://lovit.github.io/nlp/2018/09/04/levenshtein_inverted_index/)

- 수업 때 자세한 설명은 하지 않았습니다만, LSH 와 같은 hash function 을 이용하는 방법 외에도 다양한 nearest neighbor search 를 위한 인덱서들이 있습니다. 한 예로, network 의 small-world phenomenon 성질을 이용한 인덱서의 원리와 이를 구현하는 과정에 대한 이야기 입니다 [(링크)](https://lovit.github.io/machine%20learning/vector%20indexing/2018/09/10/network_based_nearest_neighbors/)

## 8 일차

- Graph 로 표현된 데이터에서 centrality 기반으로 중요한 마디를 찾을 수 있습니다. 대표적인 알고리즘인 PageRank 와 HITS 에 대한 설명입니다. [(링크)](https://lovit.github.io/machine%20learning/2018/04/16/pagerank_and_hits/)

- PageRank 는 Python 의 dict 를 이용하여 구현할 수도 있고, scipy.sparse 를 이용할 수도 있습니다. 두 종류의 구현 방식에 따른 속도 비교 입니다 [(링크)](https://lovit.github.io/machine%20learning/2018/04/17/pagerank_implementation_dict_vs_numpy/)

- PageRank 를 이용하면 토크나이저를 이용하지 않으면서도 단어, 키워드를 추출할 수 있습니다. 토크나이저를 이용하지 않는 한국어 키워드 추출기인 KR-WordRank 의 구현 과정에 대한 포스트와 이 결과를 Word cloud 로 시각화하는 과정입니다. [(링크: KR-WordRank)](https://lovit.github.io/nlp/2018/04/16/krwordrank/), [(링크: Word cloud)](https://lovit.github.io/nlp/2018/04/17/word_cloud/)

- KR-WordRank 에 핵심 문장 추출 기능을 추가하였습니다. 이 과정에서 좋은 핵심 문장의 조건에 대해서도 고민하였습니다. 개발 과정과 TextRank 와의 요약문 품질 평가과정을 정리하였습니다 [(링크)](https://lovit.github.io/nlp/2019/05/01/krwordrank_sentence/)

- TextRank 는 PageRank 를 이용하여 키워드와 핵심 문장을 선택하는 전통적인 extractive summarization 방법 중 하나입니다. 이를 구현하는 과정 및 문장 간 유사도를 변화 시켰을 경우의 품질 변화 등의 내용을 정리하였습니다. [(링크)](https://lovit.github.io/nlp/2019/04/30/textrank/)

- Shortest path 를 찾는 알고리즘 중 하나인 포드 알고리즘의 원리 및 구현 과정 입니다 [(링크)](https://lovit.github.io/nlp/graph/2018/08/21/ford_for_shortestpath/)

- Shortest path 를 찾는 알고리즘 중 하나인 포드를 이용하여, 간단한 HMM 기반 품사 판별기를 만드는 과정입니다. 자세한 디테일보다는 HMM 과 shortest path 와의 관계 및 작동 원리에 대한 내용이 기술되어 있습니다 [(링크)](https://lovit.github.io/nlp/graph/2018/08/21/ford_for_pos/)

## 9 일차

- Convolutional Neural Network 에 관련된 포스트를 작성할 예정입니다.

## 10 일차

- Sequence to sequence 에 적용된 attention 부터 Transformer 와 BERT 까지, NLP 에서 이용된 attention mechanism 을 정리하였습니다 [(링크)](https://lovit.github.io/machine%20learning/2019/03/17/attention_in_nlp/)

