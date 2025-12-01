#### Oct 2024 – Jun 2025   Intent-Adaptive Multimodal Recommendation with Collaborative-Modality Disentanglement

Project Description: Addressed the issues of feature homogenization and insufficient semantic relevance between historical interactions and candidate items in multimodal recommendation. Proposed an intent-adaptive recommendation framework based on collaborative-modality disentanglement. The framework mitigates feature coupling by separately modeling collaborative signals and multimodal semantic information and incorporates an intent-adaptive scorer to dynamically capture fine-grained user preferences toward candidates, thereby effectively enhancing recommendation performance.

Core Design:
✓ Collaborative-modality representation disentangler to suppress feature coupling.
✓ Hybrid graph enhancer to fuse multi-source information for generating discriminative representations.
✓ Intent-adaptive scorer for candidate-aware preference prediction.

Outcome: IAMRec significantly outperformed mainstream baselines on Recall and NDCG across multiple Amazon domain datasets. Submitted as first author to the data mining conference PAKDD.

#### Jun 2025 – Dec 2025 Graph-based Test-time Adaptation for Multimodal Recommender Systems

Project Description: This work addresses the problem of distribution shifts in user-item interaction data within recommender systems by proposing a data-centric test-time adaptation framework. The framework mitigates distribution shifts through dynamic adjustments to the user-item graph structure, overcoming challenges faced by traditional methods in recommendation scenarios—such as the difficulty of model fine-tuning and the lack of test labels—thereby enhancing recommendation performance during the inference phase.

Core Design:
✓ Constructed a pseudo-label guided user-item interaction graph and designed an adaptive adjustment mechanism to accommodate test-phase data distribution.
✓ Employed a distribution-aware contrastive learning framework with an adaptive sampling strategy to strengthen model robustness against distribution shifts.

Outcome: The model significantly outperformed mainstream baselines in Recall and NDCG on multiple Amazon domain datasets.

#### Nov 2024 – Dec 2025 Data-Centric Graph Learning Methods Survey, Graph-based Test-Time Adaptation Methods Survey

Content Description: 1) Proposed a systematic “Data-centric Graph Machine Learning (DC-GML)” framework covering the entire graph data lifecycle and established a comprehensive taxonomy and resource repository, providing systematic guidance for improving graph data quality and its efficient utilization. 2) Conducted the first systematic survey of the graph neural network test-time adaptation field, constructing a multidimensional analytical framework ranging from model optimization and data augmentation to hybrid strategies, and connecting theoretical research with practical applications such as recommender systems and anomaly detection.

Outcome: Submitted as the first author to TKDE and as the second author to the IJCAI Survey Track, respectively.


#### Sep 2025 – Oct 2025 News Recommendation System Optimization Project (Alibaba Tianchi Competition)

Project Description: Aimed to apply data mining and machine learning techniques to enhance the accuracy of news recommendations, thereby increasing the click-through rate on recommended news and achieving more personalized news recommendations aligned with user interests.

Personal Contributions:

Implemented recall and ranking solutions: Employed a 3-way recall strategy (improved ItemCF recall, bipartite network news recall, Word2Vec I2I recall), fused multi-channel results with normalization, and used an LGB binary classification model for ranking prediction after feature engineering (news/user/interaction features).

Model evaluation: Utilized a dual-metric evaluation system (HR and MRR) for multi-dimensional effectiveness analysis across different recommendation list lengths.

Outcome: Both HR and MMR metrics showed significant improvement as the recommendation list length increased. The fused multi-channel recall results outperformed the best single-channel method, with HR@5 increasing by 11.4% and MMR@5 by 12.8%. After ranking prediction, HR@5 improved by 31% and MMR@5 by 34%.

