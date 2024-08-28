﻿<h2 align='center'> Awesome-Attention-Heads </h2>
<div align='center'>

[![Awesome Attention Heads](https://img.shields.io/static/v1?label=&message=Awesome+Attention+Heads&color=black&logo=awesomelists)](https://github.com/IAAR-Shanghai/Awesome-Attention-Heads) ![](https://img.shields.io/github/last-commit/IAAR-Shanghai/Awesome-Attention-Heads?color=green)

</div>

Welcome to **Awesome-Attention-Heads**! This is a platform to get the latest research on different kinds of LLM's Attention Heads. We hope to provide complete and clear cutting-edge informations for researchers studying LLM interpretability and LLM hallucination. We will be grateful if you can :star: the project or commit a PR!

### Background
With the development of large language models, their underlying network structure, the Transformer, is being extensively studied. Researching the Transformer structure helps us enhance our understanding of this "black box" and improve model interpretability. Recently, there has been an increasing body of work suggesting that the model contains two distinct partitions: attention mechanisms used for behavior, inference, and analysis, and feed-forward networks (FFN) for knowledge storage. The former is crucial for revealing the functional capabilities of the model, leading to a series of studies exploring various functions within attention mechanisms, which we have termed **Attention Head Mining**.

### Table of Contents
- [Latest Papers](#lastest-papers)
- [Star Trends](#star-trends)

### Lastest Papers
Papers below are ordered by **publication date**:

#### Year 2024

| Date | Paper & Summary | Tags | Links |
| --- | --- | --- | --- |
| 2024-08-01 | **Enhancing Semantic Consistency of Large Language Models through Model Editing: An Interpretability-Oriented Approach**<br><sub>&nbsp;&nbsp;• Introduces a cost-effective model editing approach focusing on attention heads to enhance semantic consistency in LLMs without extensive parameter changes.<br>&nbsp;&nbsp;• Analyzed attention heads, injected biases, and tested on NLU and NLG datasets.<br>&nbsp;&nbsp;• Achieved notable improvements in semantic consistency and task performance, with strong generalization across additional tasks.</sub> | ![](https://img.shields.io/badge/Consistency_Head-blue)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | [![Paper](https://img.shields.io/badge/ACL_Findings-Paper-%23D2691E)](https://aclanthology.org/2024.findings-acl.199/) |
| 2024-07-31 | **Correcting Negative Bias in Large Language Models through Negative Attention Score Alignment**<br><sub>&nbsp;&nbsp;• Introduced Negative Attention Score (NAS) to quantify and correct negative bias in language models.<br>&nbsp;&nbsp;• Identified negatively biased attention heads and proposed Negative Attention Score Alignment (NASA) for fine-tuning.<br>&nbsp;&nbsp;• NASA effectively reduced the precision-recall gap while preserving generalization in binary decision tasks.</sub> | ![](https://img.shields.io/badge/Negative_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2408.00137) |
| 2024-07-29 | **Detecting and Understanding Vulnerabilities in Language Models via Mechanistic Interpretability**<br><sub>&nbsp;&nbsp;• Introduces a method using Mechanistic Interpretability (MI) to detect and understand vulnerabilities in LLMs, particularly adversarial attacks.<br>&nbsp;&nbsp;• Analyzes GPT-2 Small for vulnerabilities in predicting 3-letter acronyms.<br>&nbsp;&nbsp;• Successfully identifies and explains specific vulnerabilities in the model related to the task.</sub> | ![](https://img.shields.io/badge/Vulnerable_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2407.19842) |
| 2024-07-22 | **RazorAttention: Efficient KV Cache Compression Through Retrieval Heads**<br><sub>&nbsp;&nbsp;• Introduced RazorAttention, a training-free KV cache compression technique using retrieval heads and compensation tokens to preserve critical token information.<br>&nbsp;&nbsp;• Evaluated RazorAttention on large language models (LLMs) for efficiency.<br>&nbsp;&nbsp;• Achieved over 70% KV cache size reduction with no noticeable performance impact.</sub> | ![](https://img.shields.io/badge/Retrieval_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2407.15891) |
| 2024-07-21 | **Answer, Assemble, Ace: Understanding How Transformers Answer Multiple Choice Questions**<br><sub>&nbsp;&nbsp;• The paper introduces vocabulary projection and activation patching to localize hidden states that predict the correct MCQA answers.<br>&nbsp;&nbsp;• Identified key attention heads and layers responsible for answer selection in transformers.<br>&nbsp;&nbsp;• Middle-layer attention heads are crucial for accurate answer prediction, with a sparse set of heads playing unique roles.</sub> | ![](https://img.shields.io/badge/Answer_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2407.15018) |
| 2024-07-09 | **Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning**<br><sub>&nbsp;&nbsp;• The article identifies induction heads as crucial for pattern matching in in-context learning (ICL).<br>&nbsp;&nbsp;• Evaluated Llama-3-8B and InternLM2-20B on abstract pattern recognition and NLP tasks.<br>&nbsp;&nbsp;• Ablating induction heads reduces ICL performance by up to ~32%, bringing it close to random for pattern recognition.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2407.07011) |
| 2024-07-01 | **Steering Large Language Models for Cross-lingual Information Retrieval**<br><sub>&nbsp;&nbsp;• Introduces Activation Steered Multilingual Retrieval (ASMR), using steering activations to guide LLMs for improved cross-lingual information retrieval.<br>&nbsp;&nbsp;• Identified attention heads in LLMs affecting accuracy and language coherence, and applied steering activations.<br>&nbsp;&nbsp;• ASMR achieved state-of-the-art performance on CLIR benchmarks like XOR-TyDi QA and MKQA.</sub> | ![](https://img.shields.io/badge/Accuracy_Head-blue) ![](https://img.shields.io/badge/Coherence_Head-blue) | [![Paper](https://img.shields.io/badge/SIGIR-Paper-%23D2691E)](https://dl.acm.org/doi/10.1145/3626772.3657819) |
| 2024-06-21 | **MoA: Mixture of Sparse Attention for Automatic Large Language Model Compression**<br><sub>&nbsp;&nbsp;• The paper introduces Mixture of Attention (MoA), which tailors distinct sparse attention configurations for different heads and layers, optimizing memory, throughput, and accuracy-latency trade-offs.<br>&nbsp;&nbsp;• MoA profiles models, explores attention configurations, and improves LLM compression.<br>&nbsp;&nbsp;• MoA increases effective context length by 3.9×, while reducing GPU memory usage by 1.2-1.4×.</sub> | ![](https://img.shields.io/badge/Local--context_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2406.14909) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/thu-nics/MoA) |
| 2024-06-19 | **On the Difficulty of Faithful Chain-of-Thought Reasoning in Large Language Models**<br><sub>&nbsp;&nbsp;• Introduced novel strategies for in-context learning, fine-tuning, and activation editing to improve Chain-of-Thought (CoT) reasoning faithfulness in LLMs.<br>&nbsp;&nbsp;• Tested these strategies across multiple benchmarks to evaluate their effectiveness.<br>&nbsp;&nbsp;• Found only limited success in enhancing CoT faithfulness, highlighting the challenge in achieving truly faithful reasoning in LLMs.</sub> | ![](https://img.shields.io/badge/Faithfulness_Head-blue) | [![Paper](https://img.shields.io/badge/ICML-Paper-%23D2691E)](https://openreview.net/forum?id=3h0kZdPhAC) |
| 2024-05-28 | **Knowledge Circuits in Pretrained Transformers**<br><sub>&nbsp;&nbsp;• Introduced "knowledge circuits" in transformers, revealing how specific knowledge is encoded through interaction among attention heads, relation heads, and MLPs.<br>&nbsp;&nbsp;• Analyzed GPT-2 and TinyLLAMA to identify knowledge circuits; evaluated knowledge editing techniques.<br>&nbsp;&nbsp;• Demonstrated how knowledge circuits contribute to model behaviors like hallucinations and in-context learning.</sub> | ![](https://img.shields.io/badge/Mover_Head-blue) ![](https://img.shields.io/badge/Relation_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2405.17969) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/zjunlp/KnowledgeCircuits) |
| 2024-05-23 | **Linking In-context Learning in Transformers to Human Episodic Memory**<br><sub>&nbsp;&nbsp;• Links in-context learning in Transformer models to human episodic memory, highlighting similarities between induction heads and the contextual maintenance and retrieval (CMR) model.<br>&nbsp;&nbsp;• Analysis of Transformer-based LLMs to demonstrate CMR-like behavior in attention heads.<br>&nbsp;&nbsp;• CMR-like heads emerge in intermediate layers, mirroring human memory biases.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2405.14992) |
| 2024-05-07 | **How does GPT-2 Predict Acronyms? Extracting and Understanding a Circuit via Mechanistic Interpretability**<br><sub>&nbsp;&nbsp;• First mechanistic interpretability study on GPT-2 for predicting multi-token acronyms using attention heads.<br>&nbsp;&nbsp;• Identified and interpreted a circuit of 8 attention heads responsible for acronym prediction.<br>&nbsp;&nbsp;• Demonstrated that these 8 heads (~5% of total) concentrate the acronym prediction functionality.</sub> | ![](https://img.shields.io/badge/Letter_Mover_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2405.04156) |
| 2024-05-02 | **What needs to go right for an induction head? A mechanistic study of in-context learning circuits and their formation**<br><sub>&nbsp;&nbsp;• Introduced an optogenetics-inspired causal framework to study induction head (IH) formation in transformers.<br>&nbsp;&nbsp;• Analyzed IH emergence in transformers using synthetic data and identified three underlying subcircuits responsible for IH formation.<br>&nbsp;&nbsp;• Discovered that these subcircuits interact to drive IH formation, coinciding with a phase change in model loss.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue) | [![Paper](https://img.shields.io/badge/ICML-Paper-%23D2691E)](https://openreview.net/forum?id=O8rrXl71D5) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/aadityasingh/icl-dynamics) |
| 2024-04-24 | **Retrieval Head Mechanistically Explains Long-Context Factuality**<br><sub>&nbsp;&nbsp;• Identified "retrieval heads" in transformer models responsible for retrieving information across long contexts.<br>&nbsp;&nbsp;• Systematic investigation of retrieval heads across various models, including analysis of their role in chain-of-thought reasoning.<br>&nbsp;&nbsp;• Pruning retrieval heads leads to hallucination, while pruning non-retrieval heads doesn't affect retrieval ability.</sub> | ![](https://img.shields.io/badge/Retrieval_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2404.15574) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/nightdessert/Retrieval_Head) |
| 2024-03-27 | **Non-Linear Inference Time Intervention: Improving LLM Truthfulness**<br><sub>&nbsp;&nbsp;• Introduced Non-Linear Inference Time Intervention (NL-ITI), enhancing LLM truthfulness by multi-token probing and intervention without fine-tuning.<br>&nbsp;&nbsp;• Evaluated NL-ITI on multiple-choice datasets, including TruthfulQA.<br>&nbsp;&nbsp;• Achieved a 16% relative improvement in MC1 accuracy on TruthfulQA over baseline ITI.</sub> | ![](https://img.shields.io/badge/Truthfulness_Head-blue)  | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2403.18680) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/Samsung/NL-ITI) |
| 2024-02-28 | **Cutting Off the Head Ends the Conflict: A Mechanism for Interpreting and Mitigating Knowledge Conflicts in Language Models**<br><sub>&nbsp;&nbsp;• Introduces the PH3 method to prune conflicting attention heads, mitigating knowledge conflicts in language models without parameter updates.<br>&nbsp;&nbsp;• Applied PH3 to control LMs' reliance on internal memory vs. external context and tested its effectiveness on open-domain QA tasks.<br>&nbsp;&nbsp;• PH3 improved internal memory usage by 44.0% and external context usage by 38.5%.</sub> | ![](https://img.shields.io/badge/Memory_Head-blue) ![](https://img.shields.io/badge/Context_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2402.18154) |
| 2024-02-27 | **Information Flow Routes: Automatically Interpreting Language Models at Scale**<br><sub>&nbsp;&nbsp;• Introduces "Information Flow Routes" using attribution for graph-based interpretation of language models, avoiding activation patching.<br>&nbsp;&nbsp;• Experiments with Llama 2, identifying key attention heads and behavior patterns across different domains and tasks.<br>&nbsp;&nbsp;• Uncovered specialized model components; identified consistent roles for attention heads, such as handling tokens of the same part of speech.</sub> | ![](https://img.shields.io/badge/Positional_Head-blue) ![](https://img.shields.io/badge/Subword_merging_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2403.00824) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/facebookresearch/llm-transparency-tool) |
| 2024-02-20 | **Identifying Semantic Induction Heads to Understand In-Context Learning**<br><sub>&nbsp;&nbsp;• Identifies and studies "semantic induction heads" in large language models (LLMs) that correlate with in-context learning abilities.<br>&nbsp;&nbsp;• Analyzed attention heads for encoding syntactic dependencies and knowledge graph relations.<br>&nbsp;&nbsp;• Certain attention heads enhance output logits by recalling relevant tokens, crucial for understanding in-context learning in LLMs.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue)  | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2402.13055v1) |
| 2024-02-16 | **The Evolution of Statistical Induction Heads: In-Context Learning Markov Chains**<br><sub>&nbsp;&nbsp;• Introduces a Markov Chain sequence modeling task to analyze how in-context learning (ICL) capabilities emerge in transformers, forming "statistical induction heads."<br>&nbsp;&nbsp;• Empirical and theoretical investigation of multi-phase training in transformers on Markov Chain tasks.<br>&nbsp;&nbsp;• Demonstrates phase transitions from unigram to bigram predictions, influenced by transformer layer interactions.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2402.11004) |
| 2024-02-11 | **Summing Up the Facts: Additive Mechanisms Behind Factual Recall in LLMs**<br><sub>&nbsp;&nbsp;• Identifies and explains the "additive motif" in factual recall, where LLMs use multiple independent mechanisms that constructively interfere to recall facts.<br>&nbsp;&nbsp;• Extended direct logit attribution to analyze attention heads and unpacked the behavior of mixed heads.<br>&nbsp;&nbsp;• Demonstrated that factual recall in LLMs results from the sum of multiple, independently insufficient contributions.</sub> | ![](https://img.shields.io/badge/Mover_Head-blue) ![](https://img.shields.io/badge/Relation_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://www.arxiv.org/abs/2402.07321) |
| 2024-02-05 | **How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning**<br><sub>&nbsp;&nbsp;• Introduces the concept that query and key matrices in in-context heads operate as "two towers" for metric learning, facilitating similarity computation between label features.<br>&nbsp;&nbsp;• Analyzed in-context learning mechanisms; identified specific attention heads crucial for ICL.<br>&nbsp;&nbsp;• Reduced ICL accuracy from 87.6% to 24.4% by intervening in only 1% of these heads.</sub> | ![](https://img.shields.io/badge/In--Context_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2402.02872) |
| 2024-01-16 | **Circuit Component Reuse Across Tasks in Transformer Language Models**<br><sub>&nbsp;&nbsp;• The paper demonstrates that specific circuits in GPT-2 can generalize across different tasks, challenging the notion that such circuits are task-specific.<br>&nbsp;&nbsp;• It examines the reuse of circuits from the Indirect Object Identification (IOI) task in the Colored Objects task.<br>&nbsp;&nbsp;• Adjusting four attention heads boosts accuracy from 49.6% to 93.7% in the Colored Objects task.</sub> | ![](https://img.shields.io/badge/Content_Gatherer_Head-blue) | [![Paper](https://img.shields.io/badge/ICLR-Paper-%23D2691E)](https://openreview.net/forum?id=fpoAYV6Wsk)  [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/jmerullo/circuit_reuse) |
| 2024-01-16 | **Successor Heads: Recurring, Interpretable Attention Heads In The Wild**<br><sub>&nbsp;&nbsp;• The paper introduces "Successor Heads," attention heads in LLMs that increment tokens with natural orderings, like days or numbers.<br>&nbsp;&nbsp;• It analyzes the formation of successor heads across various model sizes and architectures, such as GPT-2 and Llama-2.<br>&nbsp;&nbsp;• Successor heads are found in models ranging from 31M to 12B parameters, revealing abstract, recurring numeric representations.</sub> | ![](https://img.shields.io/badge/Successor_Head-blue) | [![Paper](https://img.shields.io/badge/ICLR-Poster-%23D2691E)](https://openreview.net/forum?id=kvcbV8KQsi) |
| 2024-01-16 | **Function Vectors in Large Language Models**<br><sub>&nbsp;&nbsp;• The article introduces "Function Vectors (FVs)," compact, causal representations of tasks within autoregressive transformer models.<br>&nbsp;&nbsp;• FVs were tested across diverse in-context learning (ICL) tasks, models, and layers.<br>&nbsp;&nbsp;• FVs can be summed to create vectors that trigger new, complex tasks, demonstrating internal vector composition.</sub> | ![](https://img.shields.io/badge/Function_Vector_Head-blue) | [![Paper](https://img.shields.io/badge/ICLR-Paper-%23D2691E)](https://openreview.net/forum?id=AwyxtyMwaG&noteId=6Qv7kx00La) [![Project](https://img.shields.io/badge/Git-Page-black?logo=internet-explorer)](https://functions.baulab.info/) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/ericwtodd/function_vectors) [![Data](https://img.shields.io/badge/GitHub-Data-brightgreen?logo=github)](https://github.com/ericwtodd/function_vectors/tree/main/dataset_files) |

#### Year 2023
| Date | Paper & Summary | Tags | Links |
| --- | --- | --- | --- |
| 2023-10-23 | **Linear Representations of Sentiment in Large Language Models**<br><sub>&nbsp;&nbsp;• The paper identifies a linear direction in activation space that captures sentiment representation in Large Language Models (LLMs).<br>&nbsp;&nbsp;• They isolated this sentiment direction and tested it on tasks including Stanford Sentiment Treebank.<br>&nbsp;&nbsp;• Ablating this sentiment direction leads to a 76% reduction in classification accuracy, highlighting its importance.</sub> | ![](https://img.shields.io/badge/Direct_effect_Head-blue)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2310.15154) |
| 2023-10-06 | **Copy Suppression: Comprehensively Understanding an Attention Head**<br><sub>&nbsp;&nbsp;• The paper introduces the concept of copy suppression in a GPT-2 Small attention head (L10H7), which reduces naive token copying, enhancing model calibration.<br>&nbsp;&nbsp;• The paper investigates and explains the mechanism of copy suppression and its role in **self-repair**.<br>&nbsp;&nbsp;• 76.9% of L10H7's impact in GPT-2 Small is explained, making it the most comprehensive description of an attention head's role.</sub> | ![](https://img.shields.io/badge/Copy_Suppression_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2310.04625) [![Demo](https://img.shields.io/badge/Demo-View-purple?logo=internet-explorer)](https://copy-suppression.streamlit.app/) |
| 2023-09-22 | **Inference-Time Intervention: Eliciting Truthful Answers from a Language Model**<br><sub>&nbsp;&nbsp;• Introduced Inference-Time Intervention (ITI) to enhance LLM truthfulness by adjusting model activations in select attention heads.<br>&nbsp;&nbsp;• Improved LLaMA model performance on the TruthfulQA benchmark.<br>&nbsp;&nbsp;• ITI increased Alpaca model's truthfulness from 32.5% to 65.1%.</sub> | ![](https://img.shields.io/badge/Truthfulness_Head-blue) | [![Paper](https://img.shields.io/badge/NeurIPS-Paper-%23D2691E)](https://openreview.net/forum?id=aLLuYpn83y) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/likenneth/honest_llama) |
| 2023-09-22 | **Birth of a Transformer: A Memory Viewpoint**<br><sub>&nbsp;&nbsp;• The paper presents a memory-based perspective on transformers, highlighting associative memories in weight matrices and their gradient-driven learning.<br>&nbsp;&nbsp;• Empirical analysis of training dynamics on a simplified transformer model with synthetic data.<br>&nbsp;&nbsp;• Discovery of rapid global bigram learning and the slower emergence of an "induction head" for in-context bigrams.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue) | [![Paper](https://img.shields.io/badge/NeurIPS-Paper-%23D2691E)](https://openreview.net/forum?id=3X2EbBLNsk) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/albietz/transformer-birth) |
| 2023-07-18 | **Does Circuit Analysis Interpretability Scale? Evidence from Multiple Choice Capabilities in Chinchilla**<br><sub>&nbsp;&nbsp;• Scalable circuit analysis applied to a 70B Chinchilla language model for understanding multiple-choice question answering.<br>&nbsp;&nbsp;• Logit attribution, attention pattern visualization, and activation patching to identify and categorize key attention heads.<br>&nbsp;&nbsp;• Identified "Nth item in an enumeration" feature in attention heads, though it's only a partial explanation.</sub> | ![](https://img.shields.io/badge/Correct_Letter_Head-blue) ![](https://img.shields.io/badge/Content_Gatherer_Head-blue) ![](https://img.shields.io/badge/Amplification_Head-blue) ![](https://img.shields.io/badge/Constant_Head-blue) ![](https://img.shields.io/badge/Single_Letter_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2307.09458) |
| 2023-02-02 | **Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 small**<br><sub>&nbsp;&nbsp;• The paper introduces a detailed explanation of how GPT-2 small performs indirect object identification (IOI) using a large circuit involving 28 attention heads grouped into 7 classes.<br>&nbsp;&nbsp;• They reverse-engineered the IOI task in GPT-2 small using causal interventions and projections.<br>&nbsp;&nbsp;• The study demonstrates that mechanistic interpretability of large language models is feasible.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue)  ![](https://img.shields.io/badge/S--Inhibition_Head-blue) ![](https://img.shields.io/badge/Name_Mover_Head-blue) ![](https://img.shields.io/badge/Previous_Token_Head-blue) ![](https://img.shields.io/badge/Duplicate_Token_Head-blue) ![](https://img.shields.io/badge/Negative_Name_Mover_Head-blue) ![](https://img.shields.io/badge/Backup_Name_Mover_Head-blue) | [![Paper](https://img.shields.io/badge/ICLR-Paper-%23D2691E)](https://openreview.net/forum?id=NpsVSN6o4ul) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/redwoodresearch/Easy-Transformer) |

#### Before ChatGPT Announced
| Date | Paper & Summary | Tags | Links |
| --- | --- | --- | --- |
| 2022-03-08 | **In-context Learning and Induction Heads**<br><sub>&nbsp;&nbsp;• The paper identifies "induction heads" in Transformer models, which enable in-context learning by recognizing and copying patterns in sequences.<br>&nbsp;&nbsp;• Analyzes attention patterns and induction heads across various layers in different Transformer models.<br>&nbsp;&nbsp;• Found that induction heads are crucial for enabling Transformers to generalize and perform in-context learning tasks effectively.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | [![Paper](https://img.shields.io/badge/Anthropic-Paper-%23D2691E)](https://transformer-circuits.pub/2022/in-context-learning-and-induction-heads/index.html) |
| 2021-12-22 | **A Mathematical Framework for Transformer Circuits**<br><sub>&nbsp;&nbsp;• Introduces a mathematical framework to reverse-engineer small attention-only transformers, focusing on understanding attention heads as independent, additive components.<br>&nbsp;&nbsp;• Analyzed zero, one, and two-layer transformers to identify the role of attention heads in information movement and composition.<br>&nbsp;&nbsp;• Discovered "induction heads," crucial for in-context learning in two-layer transformers.</sub> | ![](https://img.shields.io/badge/Induction_Head-blue) | [![Paper](https://img.shields.io/badge/Anthropic-Paper-%23D2691E)](https://transformer-circuits.pub/2021/framework/index.html) |
| 2021-05-18 | **The Heads Hypothesis: A Unifying Statistical Approach Towards Understanding Multi-Headed Attention in BERT**<br><sub>&nbsp;&nbsp;• The paper proposes a novel method called "Sparse Attention" that reduces the computational complexity of attention mechanisms by selectively focusing on important tokens.<br>&nbsp;&nbsp;• The method was evaluated on machine translation and text classification tasks.<br>&nbsp;&nbsp;• The sparse attention model achieves comparable accuracy to dense attention while significantly reducing computational cost.</sub> |  ![](https://img.shields.io/badge/Local_Head-blue)   ![](https://img.shields.io/badge/Syntactic_Head-blue)  ![](https://img.shields.io/badge/Delimiter_Head-blue)  ![](https://img.shields.io/badge/Block_Head-blue)    | [![Paper](https://img.shields.io/badge/AAAI-Paper-%23D2691E)](https://ojs.aaai.org/index.php/AAAI/article/view/17605) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/iitmnlp/heads-hypothesis) |
| 2021-04-01 | **Have Attention Heads in BERT Learned Constituency Grammar?**<br><sub>&nbsp;&nbsp;• The study introduces a syntactic distance method to analyze constituency grammar in BERT and RoBERTa attention heads.<br>&nbsp;&nbsp;• Constituency grammar was extracted and analyzed pre- and post-fine-tuning on SMS and NLI tasks.<br>&nbsp;&nbsp;• NLI tasks increase constituency grammar inducing ability, while SMS tasks decrease it in upper layers.</sub> | ![](https://img.shields.io/badge/Constituency_grammar_inducing_Head-blue) | [![Paper](https://img.shields.io/badge/ACL-Paper-%23D2691E)](https://aclanthology.org/2021.eacl-srw.2/) |
| 2019-11-27 | **Do Attention Heads in BERT Track Syntactic Dependencies?**<br><sub>&nbsp;&nbsp;• The paper investigates whether individual attention heads in BERT capture syntactic dependencies, using attention weights to extract dependency relations.<br>&nbsp;&nbsp;• Analyzed BERT's attention heads using maximum attention weights and maximum spanning trees, comparing them to Universal Dependency trees.<br>&nbsp;&nbsp;• Some attention heads track specific syntactic dependencies better than baselines, but no head performs holistic parsing significantly better.</sub> | ![](https://img.shields.io/badge/Syntactic_dependency_Head-blue) | [![Paper](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/1911.12246) |
| 2019-11-01 | **Adaptively Sparse Transformers**<br><sub>&nbsp;&nbsp;• Introduced the adaptively sparse Transformer using alpha-entmax to allow flexible, context-dependent sparsity in attention heads.<br>&nbsp;&nbsp;• Applied to machine translation datasets to assess interpretability and head diversity.<br>&nbsp;&nbsp;• Achieved diverse attention distributions and improved interpretability without compromising accuracy.</sub> | ![](https://img.shields.io/badge/Positional_Head-blue) ![](https://img.shields.io/badge/BPE--merging_Head-blue) ![](https://img.shields.io/badge/Interrogation_Head-blue) | [![Paper](https://img.shields.io/badge/EMNLP-Paper-%23D2691E)](https://aclanthology.org/D19-1223/) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/deep-spin/entmax) |
| 2019-08-01 | **What does BERT look at? An Analysis of BERT’s Attention**<br><sub>&nbsp;&nbsp;• The paper introduces methods to analyze BERT's attention mechanisms, revealing patterns that align with linguistic structures like syntax and coreference.<br>&nbsp;&nbsp;• Analysis of attention heads, identification of syntactic and coreferential patterns, and development of an attention-based probing classifier.<br>&nbsp;&nbsp;• BERT's attention heads capture substantial syntactic information, particularly in tasks like identifying direct objects and coreference.</sub> |  ![](https://img.shields.io/badge/Syntactic_Head-blue)  | [![Paper](https://img.shields.io/badge/ACL-Paper-%23D2691E)](https://aclanthology.org/W19-4828/) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/clarkkev/attention-analysis) |
| 2019-07-01 | **Analyzing Multi-Head Self-Attention: Specialized Heads Do the Heavy Lifting, the Rest Can Be Pruned**<br><sub>&nbsp;&nbsp;• The paper introduces a novel pruning method for multi-head self-attention that selectively removes less important heads without major performance loss.<br>&nbsp;&nbsp;• Analysis of individual attention heads, identification of their specialized roles, and application of a pruning method on the Transformer model.<br>&nbsp;&nbsp;• Pruning 38 out of 48 heads in the encoder led to only a 0.15 BLEU score drop.</sub> | ![](https://img.shields.io/badge/Positional_Head-blue) ![](https://img.shields.io/badge/Syntactic_Head-blue) ![](https://img.shields.io/badge/Rare_words_Head-blue) | [![Paper](https://img.shields.io/badge/ACL-Paper-%23D2691E)](https://aclanthology.org/P19-1580/) [![Code](https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github)](https://github.com/lena-voita/the-story-of-heads) |
| 2016-03-21 | **Incorporating Copying Mechanism in Sequence-to-Sequence Learning**<br><sub>&nbsp;&nbsp;• Introduces a copying mechanism into sequence-to-sequence models to allow direct copying of input tokens, improving handling of rare words.<br>&nbsp;&nbsp;• Applied to machine translation and summarization tasks.<br>&nbsp;&nbsp;• Achieved substantial improvements in translation accuracy, especially on rare word translation, compared to standard sequence-to-sequence models.</sub> | ![](https://img.shields.io/badge/Retrieval_Head-blue)  | [![Paper](https://img.shields.io/badge/ACL-Paper-%23D2691E)](https://aclanthology.org/P16-1154/) |

## :star: Star Trends

<a href="https://star-history.com/#IAAR-Shanghai/Awesome-Attention-Heads&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=IAAR-Shanghai/Awesome-Attention-Heads&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=IAAR-Shanghai/Awesome-Attention-Heads&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=IAAR-Shanghai/Awesome-Attention-Heads&type=Date" />
  </picture>
</a>
