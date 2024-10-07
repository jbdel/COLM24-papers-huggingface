# COLM 2024 Papers

Welcome to the COLM 2024 Papers repository! Below is a list of all accepted papers with their details.



Use it via API! [Documentation here](https://huggingface.co/spaces/ECCV/ECCV2024-papers?view=api).
```python
from gradio_client import Client
import json

client = Client("COLMConference/COLM24-papers")
result = client.predict(
    title_search_query="LLM",
    filter_names=["Model"],
    presentation_type="(ALL)",
    book_type="(ALL)",
    column_names=["Title", "Type", "Book", "Paper page", "Authors claimed", "👍", "💬", "Proceedings", "GitHub", "Spaces",
                  "Models"],
    api_name="/filter"
)
print(json.dumps(result, indent=4))
```


## [A Survey on Deep Learning for Theorem Proving](https://arxiv.org/abs/2404.09939)<br/>
**Authors:** Zhaoyu Li, Jialiang Sun, Logan Murphy, Qidong Su, Zenan Li, Xian Zhang, Kaiyu Yang, Xujie Si<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=zlw6AHwukB)<br/>
**arXiv:** [2404.09939](https://arxiv.org/abs/2404.09939)<br/>

---

## [Towards Measuring the Representation of Subjective Global Opinions in Language Models](https://huggingface.co/papers/2306.16388)<br/>
**Authors:** Esin DURMUS, Karina Nguyen, Thomas Liao, Nicholas Schiefer, Amanda Askell, Anton Bakhtin, Carol Chen, Zac Hatfield-Dodds, Danny Hernandez, Nicholas Joseph, Liane Lovitt, Sam McCandlish, Orowa Sikder, Alex Tamkin, Janel Thamkul, Jared Kaplan, Jack Clark, Deep Ganguli<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=zl16jLb91v)<br/>
**arXiv:** [2306.16388](https://arxiv.org/abs/2306.16388)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2306.16388](https://huggingface.co/papers/2306.16388)<br/>
**🤗 Datasets:** [Anthropic/llm_global_opinions](https://huggingface.co/datasets/Anthropic/llm_global_opinions)<br/>

---

## [Top Leaderboard Ranking = Top Coding Proficiency, Always? EvoEval: Evolving Coding Benchmarks via LLM](https://huggingface.co/papers/2403.19114)<br/>
**Authors:** Chunqiu Steven Xia, Yinlin Deng, LINGMING ZHANG<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=zZa7Ke7WAJ)<br/>
**arXiv:** [2403.19114](https://arxiv.org/abs/2403.19114)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.19114](https://huggingface.co/papers/2403.19114)<br/>

---

## Transformer Circuit Evaluation Metrics Are Not Robust<br/>
**Authors:** Joseph Miller, Bilal Chughtai, William Saunders<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=zSf8PJyQb2)<br/>

---

## [Long-Form Answers to Visual Questions from Blind and Low Vision People](https://arxiv.org/abs/2408.06303)<br/>
**Authors:** Mina Huh, Fangyuan Xu, Yi-Hao Peng, Chongyan Chen, Hansika Murugu, Danna Gurari, Eunsol Choi, Amy Pavel<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=z7FvXbyyrM)<br/>
**arXiv:** [2408.06303](https://arxiv.org/abs/2408.06303)<br/>

---

## [Locating and Editing Factual Associations in Mamba](https://huggingface.co/papers/2404.03646)<br/>
**Authors:** Arnab Sen Sharma, David Atkinson, David Bau<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=yoVRyrEgix)<br/>
**arXiv:** [2404.03646](https://arxiv.org/abs/2404.03646)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.03646](https://huggingface.co/papers/2404.03646)<br/>

---

## [Does Incomplete Syntax Influence Korean Language Model? Focusing on Word Order and Case Markers](https://arxiv.org/abs/2407.09184)<br/>
**Authors:** Jong Myoung Kim, Young-Jun Lee, Yong-Jin Han, Ho-Jin Choi, Sangkeun Jung<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=yfyHxvVzZT)<br/>
**arXiv:** [2407.09184](https://arxiv.org/abs/2407.09184)<br/>

---

## [LLM Discussion: Enhancing the Creativity of Large Language Models via Discussion Framework and Role-Play](https://huggingface.co/papers/2405.06373)<br/>
**Authors:** Li-Chun Lu, Shou-Jen Chen, Tsung-Min Pai, Chan-Hung Yu, Hung-yi Lee, Shao-Hua Sun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ybaK4asBT2)<br/>
**arXiv:** [2405.06373](https://arxiv.org/abs/2405.06373)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2405.06373](https://huggingface.co/papers/2405.06373)<br/>

---

## [Large Language Models are Capable of Offering Cognitive Reappraisal, if Guided](https://arxiv.org/abs/2404.01288)<br/>
**Authors:** Hongli Zhan, Allen Zheng, Yoon Kyung Lee, Jina Suh, Junyi Jessy Li, Desmond Ong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=yK8MT91dQY)<br/>
**arXiv:** [2404.01288](https://arxiv.org/abs/2404.01288)<br/>

---

## [NeMo-Aligner: Scalable Toolkit for Efficient Model Alignment](https://huggingface.co/papers/2405.01481)<br/>
**Authors:** Gerald Shen, Zhilin Wang, Olivier Delalleau, Jiaqi Zeng, Yi Dong, Daniel Egert, Shengyang Sun, Jimmy J. Zhang, Sahil Jain, Ali Taghibakhshi, Markel Sanz Ausin, Ashwath Aithal, Oleksii Kuchaiev<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=yK2eGE8QVW)<br/>
**arXiv:** [2405.01481](https://arxiv.org/abs/2405.01481)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2405.01481](https://huggingface.co/papers/2405.01481)<br/>

---

## Khayyam Challenge (PersianMMLU): Is Your LLM Truly Wise to The Persian Language?<br/>
**Authors:** Omid Ghahroodi, Marzia Nouri, Mohammad Vali Sanian, Alireza Sahebi, Doratossadat Dastgheib, Ehsaneddin Asgari, Mahdieh Soleymani Baghshah, Mohammad Hossein Rohban<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=yIEyHP7AvH)<br/>

---

## How Susceptible are LLMs to Influence in Prompts?<br/>
**Authors:** Sotiris Anagnostidis, Jannis Bulian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=y7JnjDcIQa)<br/>

---

## PairEval: Open-domain Dialogue Evaluation Metric with Pairwise Comparisons<br/>
**Authors:** ChaeHun Park, Minseok Choi, Dohyun Lee, Jaegul Choo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=y6aGT625Lk)<br/>

---

## HGRN2: Gated Linear RNNs with State Expansion<br/>
**Authors:** Zhen Qin, Songlin Yang, Weixuan Sun, Xuyang Shen, Dong Li, Weigao Sun, Yiran Zhong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=y6SqbJfCSk)<br/>

---

## Studying Large Language Model Behaviors Under Context-Memory Conflicts With Real Documents<br/>
**Authors:** Evgenii Kortukov, Alexander Rubinstein, Elisa Nguyen, Seong Joon Oh<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=xm8zYRfrqE)<br/>

---

## Investigating Instruction Tuning Large Language Models on Graphs<br/>
**Authors:** Kerui Zhu, Bo-Wei Huang, Bowen Jin, Yizhu Jiao, Ming Zhong, Kevin Chang, Shou-De Lin, Jiawei Han<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=xdg4CS5mkl)<br/>

---

## [FUSE-ing Language Models: Zero-Shot Adapter Discovery for Prompt Optimization Across Tokenizers](https://arxiv.org/abs/2408.04816)<br/>
**Authors:** Joshua Nathaniel Williams, J Zico Kolter<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=xWYRL1eR74)<br/>
**arXiv:** [2408.04816](https://arxiv.org/abs/2408.04816)<br/>

---

## [CLIN: A Continually Learning Language Agent for Rapid Task Adaptation and Generalization](https://huggingface.co/papers/2310.10134)<br/>
**Authors:** Bodhisattwa Prasad Majumder, Bhavana Dalvi Mishra, Peter Jansen, Oyvind Tafjord, Niket Tandon, Li Zhang, Chris Callison-Burch, Peter Clark<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=xS6zx1aBI9)<br/>
**arXiv:** [2310.10134](https://arxiv.org/abs/2310.10134)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2310.10134](https://huggingface.co/papers/2310.10134)<br/>

---

## [Helmsman of the Masses? Evaluate the Opinion Leadership of Large Language Models in the Werewolf Game](https://arxiv.org/abs/2404.01602)<br/>
**Authors:** Silin Du, Xiaowei Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=xMt9kCv5YR)<br/>
**arXiv:** [2404.01602](https://arxiv.org/abs/2404.01602)<br/>

---

## Factual and Tailored Recommendation Endorsements using Language Models and Reinforcement Learning<br/>
**Authors:** Jihwan Jeong, Yinlam Chow, Guy Tennenholtz, ChihWei Hsu, Mohammad Ghavamzadeh, Craig Boutilier<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=xI8C7sfN1H)<br/>

---

## [How Well Do LLMs Identify Cultural Unity in Diversity?](https://arxiv.org/abs/2408.05102)<br/>
**Authors:** Jialin Li, Junli Wang, Junjie Hu, Ming Jiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=wps3p2cqrA)<br/>
**arXiv:** [2408.05102](https://arxiv.org/abs/2408.05102)<br/>

---

## [Guiding Language Model Reasoning with Planning Tokens](https://arxiv.org/abs/2310.05707)<br/>
**Authors:** Xinyi Wang, Lucas Caccia, Oleksiy Ostapenko, Xingdi Yuan, William Yang Wang, Alessandro Sordoni<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=wi9IffRhVM)<br/>
**arXiv:** [2310.05707](https://arxiv.org/abs/2310.05707)<br/>

---

## [Dated Data: Tracing Knowledge Cutoffs in Large Language Models](https://arxiv.org/abs/2403.12958)<br/>
**Authors:** Jeffrey Cheng, Marc Marone, Orion Weller, Dawn Lawrie, Daniel Khashabi, Benjamin Van Durme<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=wS7PxDjy6m)<br/>
**arXiv:** [2403.12958](https://arxiv.org/abs/2403.12958)<br/>

---

## Large Language Model is not a (Multilingual) Compositional Relation Reasoner<br/>
**Authors:** Jinman Zhao, Xueyan Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=wLQ3I0F1oj)<br/>

---

## Instruction Mining: Instruction Data Selection for Tuning Large Language Models<br/>
**Authors:** Yihan Cao, Yanbin Kang, Chi Wang, Lichao Sun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=wF6k0aWjAu)<br/>

---

## [Does your data spark joy? Performance gains from domain upsampling at the end of training](https://huggingface.co/papers/2406.03476)<br/>
**Authors:** Cody Blakeney, Mansheej Paul, Brett W. Larsen, Sean Owen, Jonathan Frankle<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=vwIIAot0ff)<br/>
**arXiv:** [2406.03476](https://arxiv.org/abs/2406.03476)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2406.03476](https://huggingface.co/papers/2406.03476)<br/>

---

## Predicting Emergent Capabilities by Finetuning<br/>
**Authors:** Charlie Victor Snell, Eric Wallace, Dan Klein, Sergey Levine<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=vL8BIGuFTF)<br/>

---

## [Best-of-Venom: Attacking RLHF by Injecting Poisoned Preference Data](https://arxiv.org/abs/2404.05530)<br/>
**Authors:** Tim Baumgärtner, Yang Gao, Dana Alon, Donald Metzler<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=v74mJURD1L)<br/>
**arXiv:** [2404.05530](https://arxiv.org/abs/2404.05530)<br/>

---

## CATS: Context-Aware Thresholding for Sparsity in Large Language Models<br/>
**Authors:** Donghyun Lee, Jaeyong Lee, Genghan Zhang, Mo Tiwari, Azalia Mirhoseini<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=v3w2a7EInO)<br/>

---

## Efficient Hybrid Long Sequence Modeling with State Space Augmented Transformers<br/>
**Authors:** Simiao Zuo, Xiaodong Liu, Jian Jiao, Denis X Charles, Eren Manavoglu, Tuo Zhao, Jianfeng Gao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=uUIFTjBREk)<br/>

---

## Does Collaborative Human–LM Dialogue Generation Help Information Extraction from Human–Human Dialogues?<br/>
**Authors:** Bo-Ru Lu, Nikita Haduong, Chia-Hsuan Lee, Zeqiu Wu, Hao Cheng, Paul Koester, Jean Utke, Tao Yu, Noah A. Smith, Mari Ostendorf<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=uILyEJGKWw)<br/>

---

## [Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens](https://huggingface.co/papers/2401.17377)<br/>
**Authors:** Jiacheng Liu, Sewon Min, Luke Zettlemoyer, Yejin Choi, Hannaneh Hajishirzi<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=u2vAyMeLMm)<br/>
**arXiv:** [2401.17377](https://arxiv.org/abs/2401.17377)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2401.17377](https://huggingface.co/papers/2401.17377)<br/>
**🤗 Spaces:** [liujch1998/infini-gram](https://huggingface.co/spaces/liujch1998/infini-gram)<br/>

---

## RQ-RAG: Learning to Refine Queries for Retrieval Augmented Generation<br/>
**Authors:** Chi-Min Chan, Chunpu Xu, Ruibin Yuan, Hongyin Luo, Wei Xue, Yike Guo, Jie Fu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=tzE7VqsaJ4)<br/>

---

## [Exploring the Mystery of Influential Data for Mathematical Reasoning](https://arxiv.org/abs/2404.01067)<br/>
**Authors:** Xinzhe Ni, Yeyun Gong, Zhibin Gou, yelong shen, Yujiu Yang, Nan Duan, Weizhu Chen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=taThoOlDNQ)<br/>
**arXiv:** [2404.01067](https://arxiv.org/abs/2404.01067)<br/>

---

## [LalaEval: A Holistic Human Evaluation Framework for Domain-Specific Large Language Models](https://arxiv.org/abs/2408.13338)<br/>
**Authors:** Chongyan Sun, Ken Lin, Shiwei Wang, Hulong Wu, Chengfei Fu, Zhen Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=tRxIB7y3wF)<br/>
**arXiv:** [2408.13338](https://arxiv.org/abs/2408.13338)<br/>

---

## Trust No Bot: Discovering Personal  Disclosures in Human-LLM Conversations in the Wild<br/>
**Authors:** Niloofar Mireshghallah, Maria Antoniak, Yash More, Yejin Choi, Golnoosh Farnadi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=tIpWtMYkzU)<br/>

---

## Mamba: Linear-Time Sequence Modeling with Selective State Spaces<br/>
**Authors:** Albert Gu, Tri Dao<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=tEYskw1VY2)<br/>

---

## MultiHop-RAG: Benchmarking Retrieval-Augmented Generation for Multi-Hop Queries<br/>
**Authors:** Yixuan Tang, Yi Yang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=t4eB3zYWBK)<br/>

---

## How bad is training on synthetic data? A statistical analysis of language model collapse<br/>
**Authors:** Mohamed El Amine Seddik, Suei-Wen Chen, Soufiane Hayou, Pierre Youssef, Merouane Abdelkader DEBBAH<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=t3z6UlV09o)<br/>

---

## V-STaR: Training Verifiers for Self-Taught Reasoners<br/>
**Authors:** Arian Hosseini, Xingdi Yuan, Nikolay Malkin, Aaron Courville, Alessandro Sordoni, Rishabh Agarwal<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=stmqBSW2dV)<br/>

---

## [Eagle and Finch: RWKV with Matrix-Valued States and Dynamic Recurrence](https://huggingface.co/papers/2404.05892)<br/>
**Authors:** Bo Peng, Daniel Goldstein, Quentin Gregory Anthony, Alon Albalak, Eric Alcaide, Stella Biderman, Eugene Cheah, Teddy Ferdinan, Kranthi Kiran GV, Haowen Hou, Satyapriya Krishna, Ronald McClelland Jr., Niklas Muennighoff, Fares Obeid, Atsushi Saito, Guangyu Song, Haoqin Tu, Ruichong Zhang, Bingchen Zhao, Qihang Zhao, Jian Zhu, Rui-Jie Zhu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=soz1SEiPeq)<br/>
**arXiv:** [2404.05892](https://arxiv.org/abs/2404.05892)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.05892](https://huggingface.co/papers/2404.05892)<br/>
**🤗 Models:** [BlinkDL/rwkv-6-world](https://huggingface.co/BlinkDL/rwkv-6-world), [TimeMobius/Mobius-RWKV-r5-chat-12B-8k](https://huggingface.co/TimeMobius/Mobius-RWKV-r5-chat-12B-8k), [TimeMobius/Mobius-RWKV-r6-12B](https://huggingface.co/TimeMobius/Mobius-RWKV-r6-12B), [xiaol/mobius-rwkv-r6-12B](https://huggingface.co/xiaol/mobius-rwkv-r6-12B), [xiaol/Mobius-RWKV-r5-chat-12B-8k](https://huggingface.co/xiaol/Mobius-RWKV-r5-chat-12B-8k)<br/>
**🤗 Spaces:** [BlinkDL/RWKV-Gradio-2](https://huggingface.co/spaces/BlinkDL/RWKV-Gradio-2), [BlinkDL/RWKV-Gradio-1](https://huggingface.co/spaces/BlinkDL/RWKV-Gradio-1), [devingulliver/subquadratic-llm-leaderboard](https://huggingface.co/spaces/devingulliver/subquadratic-llm-leaderboard), [FredZhang7/rwkv-6-world-1b6-chat](https://huggingface.co/spaces/FredZhang7/rwkv-6-world-1b6-chat)<br/>

---

## Linearizing Large Language Models<br/>
**Authors:** Jean Mercat, Igor Vasiljevic, Sedrick Scott Keh, Kushal Arora, Achal Dave, Adrien Gaidon, Thomas Kollar<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=soGxskHGox)<br/>

---

## VideoDirectorGPT: Consistent Multi-Scene Video Generation via LLM-Guided Planning<br/>
**Authors:** Han Lin, Abhay Zala, Jaemin Cho, Mohit Bansal<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=sKNIjS2brr)<br/>

---

## [OpenAgents: An Open Platform for Language Agents in the Wild](https://huggingface.co/papers/2310.10634)<br/>
**Authors:** Tianbao Xie, Fan Zhou, Zhoujun Cheng, Peng Shi, Luoxuan Weng, Yitao Liu, Toh Jing Hua, Junning Zhao, Qian Liu, Che Liu, Zeyu Liu, Yiheng Xu, Hongjin SU, Dongchan Shin, Caiming Xiong, Tao Yu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=sKATR2O1Y0)<br/>
**arXiv:** [2310.10634](https://arxiv.org/abs/2310.10634)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2310.10634](https://huggingface.co/papers/2310.10634)<br/>

---

## [TPD: Enhancing Student Language Model Reasoning via Principle Discovery and Guidance](https://huggingface.co/papers/2401.13849)<br/>
**Authors:** Haorui Wang, Rongzhi Zhang, Yinghao Li, Lingkai Kong, Yuchen Zhuang, Xiusi Chen, Chao Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=sJvhwDtFhQ)<br/>
**arXiv:** [2401.13849](https://arxiv.org/abs/2401.13849)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2401.13849](https://huggingface.co/papers/2401.13849)<br/>

---

## Trans-Tokenization and Cross-lingual Vocabulary Transfers: Language Adaptation of LLMs for Low-Resource NLP<br/>
**Authors:** François Remy, Pieter Delobelle, Hayastan Avetisyan, Alfiya Khabibullina, Miryam de Lhoneux, Thomas Demeester<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=sBxvoDhvao)<br/>

---

## RAFT: Adapting Language Model to Domain Specific RAG<br/>
**Authors:** Tianjun Zhang, Shishir G Patil, Naman Jain, Sheng Shen, Matei Zaharia, Ion Stoica, Joseph E. Gonzalez<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=rzQGHXNReU)<br/>

---

## PhonATe: Impact of Type-Written Phonological Features of African American Language on Generative Language Modeling Tasks<br/>
**Authors:** Nicholas Deas, Jessica A Grieser, Xinmeng Hou, Shana Kleiner, Tajh Martin, Sreya Nandanampati, Desmond U. Patton, Kathleen McKeown<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=rXEwxmnGQs)<br/>

---

## [Implicit Geometry of Next-token Prediction: From Language Sparsity Patterns to Model Representations](https://arxiv.org/abs/2408.15417)<br/>
**Authors:** Yize Zhao, Tina Behnia, Vala Vakilian, Christos Thrampoulidis<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=qyilOnIRHI)<br/>
**arXiv:** [2408.15417](https://arxiv.org/abs/2408.15417)<br/>

---

## [Look at the Text: Instruction-Tuned Language Models are More Robust Multiple Choice Selectors than You Think](https://huggingface.co/papers/2404.08382)<br/>
**Authors:** Xinpeng Wang, Chengzhi Hu, Bolei Ma, Paul Rottger, Barbara Plank<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=qHdSA85GyZ)<br/>
**arXiv:** [2404.08382](https://arxiv.org/abs/2404.08382)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.08382](https://huggingface.co/papers/2404.08382)<br/>
**🤗 Models:** [mainlp/MCQ-Classifier-MMLU-XYZ](https://huggingface.co/mainlp/MCQ-Classifier-MMLU-XYZ), [mainlp/MCQ-Classifier-MMLU-EFG](https://huggingface.co/mainlp/MCQ-Classifier-MMLU-EFG)<br/>

---

## [ChatGPT Based Data Augmentation for Improved Parameter-Efficient Debiasing of LLMs](https://arxiv.org/abs/2402.11764)<br/>
**Authors:** Pengrui Han, Rafal Dariusz Kocielnik, Adhithya Prakash Saravanan, Roy Luoyao Jiang, Or Sharir, Anima Anandkumar<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=q5Ft9ZJtHm)<br/>
**arXiv:** [2402.11764](https://arxiv.org/abs/2402.11764)<br/>

---

## [Large Language Models as Biomedical Hypothesis Generators: A Comprehensive Evaluation](https://huggingface.co/papers/2407.08940)<br/>
**Authors:** Biqing Qi, Kaiyan Zhang, Kai Tian, Haoxiang Li, Zhang-Ren Chen, Sihang Zeng, Ermo Hua, Hu Jinfang, Bowen Zhou<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=q36rpGlG9X)<br/>
**arXiv:** [2407.08940](https://arxiv.org/abs/2407.08940)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2407.08940](https://huggingface.co/papers/2407.08940)<br/>

---

## [Resolving Knowledge Conflicts in Large Language Models](https://arxiv.org/abs/2310.00935)<br/>
**Authors:** Yike Wang, Shangbin Feng, Heng Wang, Weijia Shi, Vidhisha Balachandran, Tianxing He, Yulia Tsvetkov<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ptvV5HGTNN)<br/>
**arXiv:** [2310.00935](https://arxiv.org/abs/2310.00935)<br/>

---

## How Far Are We from Intelligent Visual Deductive Reasoning?<br/>
**Authors:** Yizhe Zhang, Richard He Bai, Ruixiang ZHANG, Jiatao Gu, Shuangfei Zhai, Joshua M. Susskind, Navdeep Jaitly<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=pYEnhZ6NAv)<br/>

---

## DISTFLASHATTN: Distributed Memory-efficient Attention for Long-context LLMs Training<br/>
**Authors:** Dacheng Li, Rulin Shao, Anze Xie, Eric P. Xing, Xuezhe Ma, Ion Stoica, Joseph E. Gonzalez, Hao Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=pUEDkZyPDl)<br/>

---

## [Web Retrieval Agents for Evidence-Based Misinformation Detection](https://arxiv.org/abs/2409.00009)<br/>
**Authors:** Jacob-Junqi Tian, Hao Yu, Yury Orlovskiy, Tyler Vergho, Mauricio Rivera, Mayank Goel, Zachary Yang, Jean-François Godbout, Reihaneh Rabbany, Kellin Pelrine<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=pKMxO0wBYZ)<br/>
**arXiv:** [2409.00009](https://arxiv.org/abs/2409.00009)<br/>

---

## [Task Success is not Enough: Investigating the Use of Video-Language Models as Behavior Critics for Catching Undesirable Agent Behaviors](https://arxiv.org/abs/2402.04210)<br/>
**Authors:** Lin Guan, Yifan Zhou, Denis Liu, Yantian Zha, Heni Ben Amor, Subbarao Kambhampati<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=otKo4zFKmH)<br/>
**arXiv:** [2402.04210](https://arxiv.org/abs/2402.04210)<br/>

---

## Stop Reasoning! When Multimodal LLM with Chain-of-Thought Reasoning Meets Adversarial Image<br/>
**Authors:** Zefeng Wang, Zhen Han, Shuo Chen, Fan Xue, Zifeng Ding, Xun Xiao, Volker Tresp, Philip Torr, Jindong Gu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=oqYiYG8PtY)<br/>

---

## PolygloToxicityPrompts: Multilingual Evaluation of Neural Toxic Degeneration in Large Language Models<br/>
**Authors:** Devansh Jain, Priyanshu Kumar, Samuel Gehman, Xuhui Zhou, Thomas Hartvigsen, Maarten Sap<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ootI3ZO6TJ)<br/>

---

## [Reasoning about concepts with LLMs: Inconsistencies abound](https://huggingface.co/papers/2405.20163)<br/>
**Authors:** Rosario Uceda Sosa, Karthikeyan Natesan Ramamurthy, Maria Chang, Moninder Singh<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=oSG6qGkt1I)<br/>
**arXiv:** [2405.20163](https://arxiv.org/abs/2405.20163)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2405.20163](https://huggingface.co/papers/2405.20163)<br/>
**🤗 Datasets:** [ibm/knowledge_consistency_of_LLMs](https://huggingface.co/datasets/ibm/knowledge_consistency_of_LLMs)<br/>

---

## [Logits of API-Protected LLMs Leak Proprietary Information](https://huggingface.co/papers/2403.09539)<br/>
**Authors:** Matthew Finlayson, Xiang Ren, Swabha Swayamdipta<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=oRcYFm8vyB)<br/>
**arXiv:** [2403.09539](https://arxiv.org/abs/2403.09539)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.09539](https://huggingface.co/papers/2403.09539)<br/>

---

## [Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking](https://huggingface.co/papers/2403.09629)<br/>
**Authors:** Eric Zelikman, Georges Raif Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah Goodman<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=oRXPiSOGH9)<br/>
**arXiv:** [2403.09629](https://arxiv.org/abs/2403.09629)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.09629](https://huggingface.co/papers/2403.09629)<br/>
**🤗 Models:** [ezelikman/quietstar-8-ahead](https://huggingface.co/ezelikman/quietstar-8-ahead), [Crystalcareai/Quiet-Star-Custom](https://huggingface.co/Crystalcareai/Quiet-Star-Custom), [pharaouk/Quiet-Star-Custom](https://huggingface.co/pharaouk/Quiet-Star-Custom), [casperhansen/Mistral-7B-v0.1-qstar-original](https://huggingface.co/casperhansen/Mistral-7B-v0.1-qstar-original), [QuantFactory/quietstar-8-ahead-GGUF](https://huggingface.co/QuantFactory/quietstar-8-ahead-GGUF), [pharaouk/qstar](https://huggingface.co/pharaouk/qstar), [blockblockblock/Quiet-Star-Custom-bpw2.5](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw2.5), [blockblockblock/Quiet-Star-Custom-bpw3](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw3), [blockblockblock/Quiet-Star-Custom-bpw3.5](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw3.5), [blockblockblock/Quiet-Star-Custom-bpw4.8](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw4.8), [blockblockblock/Quiet-Star-Custom-bpw3.7](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw3.7), [blockblockblock/Quiet-Star-Custom-bpw4](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw4), [blockblockblock/Quiet-Star-Custom-bpw4.2](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw4.2), [blockblockblock/Quiet-Star-Custom-bpw4.4](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw4.4), [blockblockblock/Quiet-Star-Custom-bpw5](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw5), [blockblockblock/Quiet-Star-Custom-bpw4.6](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw4.6), [blockblockblock/Quiet-Star-Custom-bpw6](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw6), [blockblockblock/Quiet-Star-Custom-bpw5.5](https://huggingface.co/blockblockblock/Quiet-Star-Custom-bpw5.5)<br/>
**🤗 Spaces:** [awacke1/SelfTaughtReasonerAI](https://huggingface.co/spaces/awacke1/SelfTaughtReasonerAI)<br/>

---

## Branch-Train-MiX: Mixing Expert LLMs into a Mixture-of-Experts LLM<br/>
**Authors:** Sainbayar Sukhbaatar, Olga Golovneva, Vasu Sharma, Hu Xu, Xi Victoria Lin, Baptiste Roziere, Jacob Kahn, Shang-Wen Li, Wen-tau Yih, Jason E Weston, Xian Li<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=nqLAuMOF6n)<br/>

---

## [AdaMoLE: Fine-Tuning Large Language Models with Adaptive Mixture of Low-Rank Adaptation Experts](https://arxiv.org/abs/2405.00361)<br/>
**Authors:** Zefang Liu, Jiahua Luo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ndY9qFf9Sa)<br/>
**arXiv:** [2405.00361](https://arxiv.org/abs/2405.00361)<br/>

---

## Instruction-tuning Aligns LLMs to the Human Brain<br/>
**Authors:** Khai Loong Aw, Syrielle Montariol, Badr AlKhamissi, Martin Schrimpf, Antoine Bosselut<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=nXNN0x4wbl)<br/>

---

## [An Incomplete Loop: Instruction Inference, Instruction Following, and In-Context Learning in Language Models](https://arxiv.org/abs/2404.03028)<br/>
**Authors:** Emmy Liu, Graham Neubig, Jacob Andreas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=nUNbjMDBWC)<br/>
**arXiv:** [2404.03028](https://arxiv.org/abs/2404.03028)<br/>

---

## [Learning to Plan for Language Modeling from Unlabeled Data](https://arxiv.org/abs/2404.00614)<br/>
**Authors:** Nathan Cornille, Marie-Francine Moens, Florian Mai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=nT6fQIidrQ)<br/>
**arXiv:** [2404.00614](https://arxiv.org/abs/2404.00614)<br/>

---

## [Impact of Preference Noise on the Alignment Performance of Generative Language Models](https://arxiv.org/abs/2404.09824)<br/>
**Authors:** Yang Gao, Dana Alon, Donald Metzler<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=nMAaCsCTCI)<br/>
**arXiv:** [2404.09824](https://arxiv.org/abs/2404.09824)<br/>

---

## SKVQ: Sliding-window Key and Value Cache Quantization for Large Language Models<br/>
**Authors:** Haojie Duanmu, Zhihang Yuan, Xiuhong Li, Jiangfei Duan, Xingcheng ZHANG, Dahua Lin<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=nI6JyFSnyV)<br/>

---

## Eliciting Latent Knowledge from "Quirky" Language Models<br/>
**Authors:** Alex Troy Mallen, Madeline Brumley, Julia Kharchenko, Nora Belrose<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=nGCMLATBit)<br/>

---

## [AmbigDocs: Reasoning across Documents on Different Entities under the Same Name](https://huggingface.co/papers/2404.12447)<br/>
**Authors:** Yoonsang Lee, Xi Ye, Eunsol Choi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=mkYCfO822n)<br/>
**arXiv:** [2404.12447](https://arxiv.org/abs/2404.12447)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.12447](https://huggingface.co/papers/2404.12447)<br/>
**🤗 Datasets:** [yoonsanglee/AmbigDocs](https://huggingface.co/datasets/yoonsanglee/AmbigDocs)<br/>

---

## Is ChatGPT a Good Sentiment Analyzer?<br/>
**Authors:** Zengzhi Wang, Qiming Xie, Yi Feng, Zixiang Ding, Zinong Yang, Rui Xia<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=mUlLf50Y6H)<br/>

---

## Multi-FAct: Assessing Factuality of Multilingual LLMs using FActScore<br/>
**Authors:** Sheikh Shafayat, Eunsu Kim, Juhyun Oh, Alice Oh<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=lkrH6ovzsj)<br/>

---

## [Automatic Pseudo-Harmful Prompt Generation for Evaluating False Refusals in Large Language Models](https://huggingface.co/papers/2409.00598)<br/>
**Authors:** Bang An, Sicheng Zhu, Ruiyi Zhang, Michael-Andrei Panaitescu-Liess, Yuancheng Xu, Furong Huang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ljFgX6A8NL)<br/>
**arXiv:** [2409.00598](https://arxiv.org/abs/2409.00598)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2409.00598](https://huggingface.co/papers/2409.00598)<br/>
**🤗 Datasets:** [furonghuang-lab/PHTest](https://huggingface.co/datasets/furonghuang-lab/PHTest)<br/>

---

## [LlaSMol: Advancing Large Language Models for Chemistry with a Large-Scale, Comprehensive, High-Quality Instruction Tuning Dataset](https://huggingface.co/papers/2402.09391)<br/>
**Authors:** Botao Yu, Frazier N. Baker, Ziqi Chen, Xia Ning, Huan Sun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=lY6XTF9tPv)<br/>
**arXiv:** [2402.09391](https://arxiv.org/abs/2402.09391)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2402.09391](https://huggingface.co/papers/2402.09391)<br/>
**🤗 Models:** [osunlp/LlaSMol-Mistral-7B](https://huggingface.co/osunlp/LlaSMol-Mistral-7B), [osunlp/LlaSMol-CodeLlama-7B](https://huggingface.co/osunlp/LlaSMol-CodeLlama-7B), [osunlp/LlaSMol-Galactica-6.7B](https://huggingface.co/osunlp/LlaSMol-Galactica-6.7B)<br/>
**🤗 Datasets:** [osunlp/SMolInstruct](https://huggingface.co/datasets/osunlp/SMolInstruct)<br/>

---

## [Talk Less, Interact Better: Evaluating In-context Conversational Adaptation in Multimodal LLMs](https://arxiv.org/abs/2408.01417)<br/>
**Authors:** Yilun Hua, Yoav Artzi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=lVOw78nYXS)<br/>
**arXiv:** [2408.01417](https://arxiv.org/abs/2408.01417)<br/>

---

## [Rejection Improves Reliability: Training LLMs to Refuse Unknown Questions Using RL from Knowledge Feedback](https://huggingface.co/papers/2403.18349)<br/>
**Authors:** Hongshen Xu, Zichen Zhu, Situo Zhang, Da Ma, Shuai Fan, Lu Chen, Kai Yu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=lJMioZBoR8)<br/>
**arXiv:** [2403.18349](https://arxiv.org/abs/2403.18349)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.18349](https://huggingface.co/papers/2403.18349)<br/>

---

## AI-generated text boundary detection with RoFT<br/>
**Authors:** Laida Kushnareva, Tatiana Gaintseva, Dmitry Abulkhanov, Kristian Kuznetsov, German Magai, Eduard Tulchinskii, Serguei Barannikov, Sergey Nikolenko, Irina Piontkovskaya<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kzzwTrt04Z)<br/>

---

## [CA-LoRA: Adapting Existing LoRA for Compressed LLMs to Enable Efficient Multi-Tasking on Personal Devices](https://arxiv.org/abs/2307.07705)<br/>
**Authors:** Weilin Zhao, Yuxiang Huang, Xu Han, Zhiyuan Liu, Zhengyan Zhang, Kuai Li, Chen Chen, TAO YANG, Maosong Sun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kpf7UbnSAm)<br/>
**arXiv:** [2307.07705](https://arxiv.org/abs/2307.07705)<br/>

---

## Don't throw away your value model! Generating more preferable text with Value-Guided Monte-Carlo Tree Search decoding<br/>
**Authors:** Jiacheng Liu, Andrew Cohen, Ramakanth Pasunuru, Yejin Choi, Hannaneh Hajishirzi, Asli Celikyilmaz<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kh9Zt2Ldmn)<br/>

---

## Crystal: Illuminating LLM Abilities on Language and Code<br/>
**Authors:** Tianhua Tao, Junbo Li, Bowen Tan, Hongyi Wang, William Marshall, Bhargav M Kanakiya, Joel Hestness, Natalia Vassilieva, Zhiqiang Shen, Eric P. Xing, Zhengzhong Liu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kWnlCVcp6o)<br/>

---

## GeniL: A Multilingual Dataset on Generalizing Language<br/>
**Authors:** Aida Mostafazadeh Davani, Sagar Gubbi Venkatesh, Sunipa Dev, Shachi Dave, Vinodkumar Prabhakaran<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kLH4ccaL21)<br/>

---

## RULER: What’s the Real Context Size of Your Long-Context Language Models?<br/>
**Authors:** Cheng-Ping Hsieh, Simeng Sun, Samuel Kriman, Shantanu Acharya, Dima Rekesh, Fei Jia, Boris Ginsburg<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kIoBbc76Sy)<br/>

---

## [The N+ Implementation Details of RLHF with PPO: A Case Study on TL;DR Summarization](https://huggingface.co/papers/2403.17031)<br/>
**Authors:** Shengyi Huang, Michael Noukhovitch, Arian Hosseini, Kashif Rasul, Weixun Wang, Lewis Tunstall<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kHO2ZTa8e3)<br/>
**arXiv:** [2403.17031](https://arxiv.org/abs/2403.17031)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.17031](https://huggingface.co/papers/2403.17031)<br/>

---

## [Can Language Models Solve Olympiad Programming?](https://huggingface.co/papers/2404.10952)<br/>
**Authors:** Ben Shi, Michael Tang, Karthik R Narasimhan, Shunyu Yao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kGa4fMtP9l)<br/>
**arXiv:** [2404.10952](https://arxiv.org/abs/2404.10952)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.10952](https://huggingface.co/papers/2404.10952)<br/>
**🤗 Spaces:** [agentharbor/agenta](https://huggingface.co/spaces/agentharbor/agenta)<br/>

---

## From r to Q^*: Your Language Model is Secretly a Q-Function<br/>
**Authors:** Rafael Rafailov, Joey Hejna, Ryan Park, Chelsea Finn<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=kEVcNxtqXk)<br/>

---

## PRobELM: Plausibility Ranking Evaluation for Language Models<br/>
**Authors:** Moy Yuan, Eric Chamoun, Rami Aly, Chenxi Whitehouse, Andreas Vlachos<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=k8KS9Ps71d)<br/>

---

## Bring Your Own Data! Self-Sensitivity Evaluation for Large Language Models<br/>
**Authors:** Neel Jain, Khalid Saifullah, Yuxin Wen, John Kirchenbauer, Manli Shu, Aniruddha Saha, Micah Goldblum, Jonas Geiping, Tom Goldstein<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=k2xZYPZo34)<br/>

---

## Can MLLMs Perform Text-to-Image In-Context Learning?<br/>
**Authors:** Yuchen Zeng, Wonjun Kang, Yicong Chen, Hyung Il Koo, Kangwook Lee<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=jt0R50d5nk)<br/>

---

## [DeStein: Navigating Detoxification of Language Models via Universal Steering Pairs and Head-wise Activation Fusion](https://arxiv.org/abs/2404.10464)<br/>
**Authors:** Yu Li, Han Jiang, Chuanyang Gong, Zhihua Wei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=jq2kNXigPP)<br/>
**arXiv:** [2404.10464](https://arxiv.org/abs/2404.10464)<br/>

---

## [Understanding Retrieval Augmentation for Long-Form Question Answering](https://huggingface.co/papers/2310.12150)<br/>
**Authors:** Hung-Ting Chen, Fangyuan Xu, Shane Arora, Eunsol Choi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=j3AAkO5xgr)<br/>
**arXiv:** [2310.12150](https://arxiv.org/abs/2310.12150)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2310.12150](https://huggingface.co/papers/2310.12150)<br/>
**🤗 Datasets:** [lytang/LLM-AggreFact](https://huggingface.co/datasets/lytang/LLM-AggreFact), [osunlp/AttributionBench](https://huggingface.co/datasets/osunlp/AttributionBench)<br/>

---

## LAMPO: Large Language Models as Preference Machines for Few-shot Ordinal Classification<br/>
**Authors:** Zhen Qin, Junru Wu, Jiaming Shen, Tianqi Liu, Xuanhui Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ig6NI9oPhD)<br/>

---

## [LLM as a Mastermind: A Survey of Strategic Reasoning with Large Language Models](https://arxiv.org/abs/2404.01230)<br/>
**Authors:** Yadong Zhang, Shaoguang Mao, Tao Ge, Xun Wang, Yan Xia, Wenshan Wu, Ting Song, Man Lan, Furu Wei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=iMqJsQ4evS)<br/>
**arXiv:** [2404.01230](https://arxiv.org/abs/2404.01230)<br/>

---

## [Do Large Language Models Have Compositional Ability? An Investigation into Limitations and Scalability](https://arxiv.org/abs/2407.15720)<br/>
**Authors:** Zhuoyan Xu, Zhenmei Shi, Yingyu Liang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=iI1CzEhEMU)<br/>
**arXiv:** [2407.15720](https://arxiv.org/abs/2407.15720)<br/>

---

## Does In-Context Learning Really Learn? Rethinking How Large Language Models Respond and Solve Tasks via In-Context Learning<br/>
**Authors:** Quanyu Long, Yin Wu, Wenya Wang, Sinno Jialin Pan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=i2oJjC0ESQ)<br/>

---

## [Characterizing Multimodal Long-form Summarization: A Case Study on Financial Reports](https://arxiv.org/abs/2404.06162)<br/>
**Authors:** Tianyu Cao, Natraj Raman, Danial Dervovic, Chenhao Tan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=hDoN0CAy5e)<br/>
**arXiv:** [2404.06162](https://arxiv.org/abs/2404.06162)<br/>

---

## [NoFunEval: Funny How Code LMs Falter on Requirements Beyond Functional Correctness](https://huggingface.co/papers/2401.15963)<br/>
**Authors:** Manav Singhal, Tushar Aggarwal, Abhijeet Awasthi, Nagarajan Natarajan, Aditya Kanade<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=h5umhm6mzj)<br/>
**arXiv:** [2401.15963](https://arxiv.org/abs/2401.15963)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2401.15963](https://huggingface.co/papers/2401.15963)<br/>
**🤗 Datasets:** [ManavSinghal157/NoFunEval](https://huggingface.co/datasets/ManavSinghal157/NoFunEval)<br/>

---

## TarGEN: Targeted Data Generation with Large Language Models<br/>
**Authors:** Himanshu Gupta, Kevin Scaria, Ujjwala Anantheswaran, Shreyas Verma, Mihir Parmar, Saurabh Arjun Sawant, Chitta Baral, Swaroop Mishra<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=gpgMRWgv9Q)<br/>

---

## [Uncovering Intermediate Variables in Transformers using Circuit Probing](https://arxiv.org/abs/2311.04354)<br/>
**Authors:** Michael A. Lepori, Thomas Serre, Ellie Pavlick<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=gUNeyiLNxr)<br/>
**arXiv:** [2311.04354](https://arxiv.org/abs/2311.04354)<br/>

---

## UniMem: Towards a Unified View of Long-Context Large Language Models<br/>
**Authors:** Junjie Fang, Likai Tang, Hongzhe Bi, Yujia Qin, Si Sun, Zhenyu Li, Haolun Li, Yongjian Li, Xin Cong, Yankai Lin, Yukun Yan, Xiaodong Shi, Sen Song, Zhiyuan Liu, Maosong Sun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=gQAEGSGVnN)<br/>

---

## [Towards Verifiable Text Generation with Symbolic References](https://huggingface.co/papers/2311.09188)<br/>
**Authors:** Lucas Torroba Hennigen, Zejiang Shen, Aniruddha Nrusimha, Bernhard Gapp, David Sontag, Yoon Kim<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=fib9qidCpY)<br/>
**arXiv:** [2311.09188](https://arxiv.org/abs/2311.09188)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2311.09188](https://huggingface.co/papers/2311.09188)<br/>

---

## [VisualWebBench: How Far Have Multimodal LLMs Evolved in Web Page Understanding and Grounding?](https://huggingface.co/papers/2404.05955)<br/>
**Authors:** Junpeng Liu, Yifan Song, Bill Yuchen Lin, Wai Lam, Graham Neubig, Yuanzhi Li, Xiang Yue<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=egVSgtJJAx)<br/>
**arXiv:** [2404.05955](https://arxiv.org/abs/2404.05955)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.05955](https://huggingface.co/papers/2404.05955)<br/>
**🤗 Datasets:** [visualwebbench/VisualWebBench](https://huggingface.co/datasets/visualwebbench/VisualWebBench)<br/>

---

## HuatuoGPT-II, One-stage Training for Medical Adaption of LLMs<br/>
**Authors:** Junying Chen, Xidong Wang, Ke Ji, Anningzhe Gao, Feng Jiang, Shunian Chen, Hongbo Zhang, Song Dingjie, Wenya Xie, Chuyi Kong, Jianquan Li, Xiang Wan, Haizhou Li, Benyou Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=eJ3cHNu7ss)<br/>

---

## LMD3: Language Model Data Density Dependence<br/>
**Authors:** John Kirchenbauer, Garrett Honke, Gowthami Somepalli, Jonas Geiping, Katherine Lee, Daphne Ippolito, Tom Goldstein, David Andre<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=eGCw1UVOhk)<br/>

---

## [The Curious Case of Nonverbal Abstract Reasoning with Multi-Modal Large Language Models](https://huggingface.co/papers/2401.12117)<br/>
**Authors:** Kian Ahrabian, Zhivar Sourati, Kexuan Sun, Jiarui Zhang, Yifan Jiang, Fred Morstatter, Jay Pujara<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=eDWcNqiQWW)<br/>
**arXiv:** [2401.12117](https://arxiv.org/abs/2401.12117)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2401.12117](https://huggingface.co/papers/2401.12117)<br/>

---

## [Tuning Language Models by Proxy](https://huggingface.co/papers/2401.08565)<br/>
**Authors:** Alisa Liu, Xiaochuang Han, Yizhong Wang, Yulia Tsvetkov, Yejin Choi, Noah A. Smith<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=dribhnhm1i)<br/>
**arXiv:** [2401.08565](https://arxiv.org/abs/2401.08565)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2401.08565](https://huggingface.co/papers/2401.08565)<br/>

---

## [Evaluating LLMs at Detecting Errors in LLM Responses](https://huggingface.co/papers/2404.03602)<br/>
**Authors:** Ryo Kamoi, Sarkar Snigdha Sarathi Das, Renze Lou, Jihyun Janice Ahn, Yilun Zhao, Xiaoxin Lu, Nan Zhang, Yusen Zhang, Haoran Ranran Zhang, Sujeeth Reddy Vummanthala, Salika Dave, Shaobo Qin, Arman Cohan, Wenpeng Yin, Rui Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=dnwRScljXr)<br/>
**arXiv:** [2404.03602](https://arxiv.org/abs/2404.03602)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.03602](https://huggingface.co/papers/2404.03602)<br/>
**🤗 Datasets:** [ryokamoi/realmistake](https://huggingface.co/datasets/ryokamoi/realmistake)<br/>

---

## HDT: Hierarchical Document Transformer<br/>
**Authors:** Haoyu He, Markus Flicke, Jan Buchmann, Iryna Gurevych, Andreas Geiger<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=dkpeWQRmlc)<br/>

---

## [With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation](https://huggingface.co/papers/2401.11504)<br/>
**Authors:** Yan Wang, Dongyang Ma, Deng Cai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=dj9x6JuiD5)<br/>
**arXiv:** [2401.11504](https://arxiv.org/abs/2401.11504)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2401.11504](https://huggingface.co/papers/2401.11504)<br/>

---

## [CatCode: A Comprehensive Evaluation Framework for LLMs On the Mixture of Code and Text](https://arxiv.org/abs/2403.01784)<br/>
**Authors:** Zhenru Lin, Yiqun Yao, Yang Yuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=didvEO1can)<br/>
**arXiv:** [2403.01784](https://arxiv.org/abs/2403.01784)<br/>

---

## [Learning From Correctness Without Prompting Makes LLM Efficient Reasoner](https://huggingface.co/papers/2403.19094)<br/>
**Authors:** Yuxuan YAO, Han Wu, Zhijiang Guo, Zhou Biyan, Jiahui Gao, Sichun Luo, Hanxu Hou, Xiaojin Fu, Linqi Song<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=dcbNzhVVQj)<br/>
**arXiv:** [2403.19094](https://arxiv.org/abs/2403.19094)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.19094](https://huggingface.co/papers/2403.19094)<br/>

---

## [Unveiling LLMs: The Evolution of Latent Representations in a Dynamic Knowledge Graph](https://arxiv.org/abs/2404.03623)<br/>
**Authors:** Marco Bronzini, Carlo Nicolini, Bruno Lepri, Jacopo Staiano, Andrea Passerini<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=dWYRjT501w)<br/>
**arXiv:** [2404.03623](https://arxiv.org/abs/2404.03623)<br/>

---

## [Scalable Model Editing via Customized Expert Networks](https://arxiv.org/abs/2404.02699)<br/>
**Authors:** Zihan Yao, Yu He, Tianyu Qi, Ming Li<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=dJfBejh478)<br/>
**arXiv:** [2404.02699](https://arxiv.org/abs/2404.02699)<br/>

---

## Fine-grained Hallucination Detection and Editing for Language Models<br/>
**Authors:** Abhika Mishra, Akari Asai, Vidhisha Balachandran, Yizhong Wang, Graham Neubig, Yulia Tsvetkov, Hannaneh Hajishirzi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=dJMTn3QOWO)<br/>

---

## ORAG: Ontology-Guided Retrieval-Augmented Generation for Theme-Specific Entity Typing<br/>
**Authors:** Jinfeng Xiao, Linyi Ding, James Barry, Mohab Elkaref, Geeth De Mel, Jiawei Han<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=cKBmZ2PZ6c)<br/>

---

## Unified View of Grokking, Double Descent and Emergent Abilities: A Comprehensive Study on Algorithm Task<br/>
**Authors:** Yufei Huang, Shengding Hu, Xu Han, Zhiyuan Liu, Maosong Sun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=cG1EbmWiSs)<br/>

---

## [Fakes of Varying Shades: How Warning Affects Human Perception and Engagement Regarding LLM Hallucinations](https://arxiv.org/abs/2404.03745)<br/>
**Authors:** Mahjabin Nahar, Haeseung Seo, Eun-Ju Lee, Aiping Xiong, Dongwon Lee<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=c30qeMg8dv)<br/>
**arXiv:** [2404.03745](https://arxiv.org/abs/2404.03745)<br/>

---

## Personalized Collaborative Fine-Tuning for On-Device Large Language Models<br/>
**Authors:** Nicolas Wagner, Dongyang Fan, Martin Jaggi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=bwo3GVsgOv)<br/>

---

## [Benchmarks as Microscopes: A Call for Model Metrology](https://arxiv.org/abs/2407.16711)<br/>
**Authors:** Michael Saxon, Ari Holtzman, Peter West, William Yang Wang, Naomi Saphra<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=bttKwCZDkm)<br/>
**arXiv:** [2407.16711](https://arxiv.org/abs/2407.16711)<br/>

---

## [Tabular Transfer Learning via Prompting LLMs](https://arxiv.org/abs/2408.11063)<br/>
**Authors:** Jaehyun Nam, Woomin Song, Seong Hyeon Park, Jihoon Tack, Sukmin Yun, Jaehyung Kim, Kyu Hwan Oh, Jinwoo Shin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=bo4pauxnIR)<br/>
**arXiv:** [2408.11063](https://arxiv.org/abs/2408.11063)<br/>

---

## How Multilingual are Large Language Models Fine-tuned for Translation?<br/>
**Authors:** Aquia Richburg, Marine Carpuat<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=bnscREWUuc)<br/>

---

## [O3D: Offline Data-driven Discovery and Distillation for Sequential Decision-Making with Large Language Models](https://arxiv.org/abs/2310.14403)<br/>
**Authors:** Yuchen Xiao, Yanchao Sun, Mengda Xu, Udari Madhushani Sehwag, Jared Vann, Deepeka Garg, Sumitra Ganesh<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=bkY8zEDdH9)<br/>
**arXiv:** [2310.14403](https://arxiv.org/abs/2310.14403)<br/>

---

## [LLM Reasoners: New Evaluation, Library, and Analysis of Step-by-Step Reasoning with Large Language Models](https://huggingface.co/papers/2404.05221)<br/>
**Authors:** Shibo Hao, Yi Gu, Haotian Luo, Tianyang Liu, Xiyan Shao, Xinyuan Wang, Shuhua Xie, Haodi Ma, Adithya Samavedhi, Qiyue Gao, Zhen Wang, Zhiting Hu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=b0y6fbSUG0)<br/>
**arXiv:** [2404.05221](https://arxiv.org/abs/2404.05221)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.05221](https://huggingface.co/papers/2404.05221)<br/>

---

## Do Membership Inference Attacks Work on Large Language Models?<br/>
**Authors:** Michael Duan, Anshuman Suri, Niloofar Mireshghallah, Sewon Min, Weijia Shi, Luke Zettlemoyer, Yulia Tsvetkov, Yejin Choi, David Evans, Hannaneh Hajishirzi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=av0D19pSkU)<br/>

---

## [Revenge of the Fallen? Recurrent Models Match Transformers at Predicting Human Language Comprehension Metrics](https://arxiv.org/abs/2404.19178)<br/>
**Authors:** James Michaelov, Catherine Arnett, Ben Bergen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=amhPBLFYWv)<br/>
**arXiv:** [2404.19178](https://arxiv.org/abs/2404.19178)<br/>

---

## [The Geometry of Truth: Emergent Linear Structure in Large Language Model Representations of True/False Datasets](https://arxiv.org/abs/2310.06824)<br/>
**Authors:** Samuel Marks, Max Tegmark<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=aajyHYjjsk)<br/>
**arXiv:** [2310.06824](https://arxiv.org/abs/2310.06824)<br/>

---

## [Hummer: Towards Limited Competitive Preference Dataset](https://huggingface.co/papers/2405.11647)<br/>
**Authors:** Yusen Wu, Li Jiang, Junwu Xiong, Jingqing Ruan, Yichuan Ding, Qingpei Guo, zujie wen, JUN ZHOU, Xiaotie Deng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=aKwQPRjdGa)<br/>
**arXiv:** [2405.11647](https://arxiv.org/abs/2405.11647)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2405.11647](https://huggingface.co/papers/2405.11647)<br/>
**🤗 Datasets:** [sarinw-2024/Hummer](https://huggingface.co/datasets/sarinw-2024/Hummer)<br/>

---

## Zephyr: Direct Distillation of LM Alignment<br/>
**Authors:** Lewis Tunstall, Edward Emanuel Beeching, Nathan Lambert, Nazneen Rajani, Kashif Rasul, Younes Belkada, Shengyi Huang, Leandro Von Werra, Clémentine Fourrier, Nathan Habib, Nathan Sarrazin, Omar Sanseviero, Alexander M Rush, Thomas Wolf<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=aKkAwZB6JV)<br/>

---

## [Nonparametric Variational Regularisation of Pretrained Transformers](https://huggingface.co/papers/2312.00662)<br/>
**Authors:** Fabio James Fehr, James Henderson<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Zu8OWNUC0u)<br/>
**arXiv:** [2312.00662](https://arxiv.org/abs/2312.00662)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2312.00662](https://huggingface.co/papers/2312.00662)<br/>

---

## Training Language Models on the Knowledge Graph: Insights on Hallucinations and Their Detectability<br/>
**Authors:** Jiri Hron, Laura A Culp, Gamaleldin Fathy Elsayed, Rosanne Liu, Jasper Snoek, Simon Kornblith, Alex Rizkowsky, Isabelle Simpson, Jascha Sohl-Dickstein, Noah Fiedel, Aaron T Parisi, Alexander A Alemi, Azade Nova, Ben Adlam, Bernd Bohnet, Gaurav Mishra, Hanie Sedghi, Izzeddin Gur, Jaehoon Lee, John D Co-Reyes, Kathleen Kenealy, Kelvin Xu, Kevin Swersky, Igor Mordatch, Lechao Xiao, Maxwell Bileschi, Peter J Liu, Roman Novak, Sharad Vikram, Tris Warkentin, Jeffrey Pennington<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Zt1dwG8xrK)<br/>

---

## Redesigning Information Markets in the Era of Language Models<br/>
**Authors:** Martin Weiss, Nasim Rahaman, Manuel Wuthrich, Yoshua Bengio, Li Erran Li, Bernhard Schölkopf, Christopher Pal<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Zq9Dfj4nBo)<br/>

---

## [Large Language Model Routing with Benchmark Datasets](https://huggingface.co/papers/2309.15789)<br/>
**Authors:** Tal Shnitzer, Anthony Ou, Mírian Silva, Kate Soule, Yuekai Sun, Justin Solomon, Neil Thompson, Mikhail Yurochkin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Zb0ajZ7vAt)<br/>
**arXiv:** [2309.15789](https://arxiv.org/abs/2309.15789)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2309.15789](https://huggingface.co/papers/2309.15789)<br/>

---

## [Language Models as Critical Thinking Tools: A Case Study of Philosophers](https://arxiv.org/abs/2404.04516)<br/>
**Authors:** Andre Ye, Jared Moore, Rose Novick, Amy X Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ZZzXpyv65G)<br/>
**arXiv:** [2404.04516](https://arxiv.org/abs/2404.04516)<br/>

---

## Cookbook: A framework for improving LLM generative abilities via programmatic data generating templates<br/>
**Authors:** Avanika Narayan, Mayee F Chen, Kush Bhatia, Christopher Re<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ZDdLamBX4P)<br/>

---

## [Prompt Exploration with Prompt Regression](https://arxiv.org/abs/2405.11083)<br/>
**Authors:** Michael Feffer, Ronald Xu, Yuekai Sun, Mikhail Yurochkin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=YwrNePfb3E)<br/>
**arXiv:** [2405.11083](https://arxiv.org/abs/2405.11083)<br/>

---

## FABLES: Evaluating faithfulness and content selection in book-length summarization<br/>
**Authors:** Yekyung Kim, Yapei Chang, Marzena Karpinska, Aparna Garimella, Varun Manjunatha, Kyle Lo, Tanya Goyal, Mohit Iyyer<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=YfHxQSoaWU)<br/>

---

## [Mapping the Increasing Use of LLMs in Scientific Papers](https://arxiv.org/abs/2404.01268)<br/>
**Authors:** Weixin Liang, Yaohui Zhang, Zhengxuan Wu, Haley Lepp, Wenlong Ji, Xuandong Zhao, Hancheng Cao, Sheng Liu, Siyu He, Zhi Huang, Diyi Yang, Christopher Potts, Christopher D Manning, James Y. Zou<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=YX7QnhxESU)<br/>
**arXiv:** [2404.01268](https://arxiv.org/abs/2404.01268)<br/>

---

## Scattered Mixture-of-Experts Implementation<br/>
**Authors:** Shawn Tan, Yikang Shen, Rameswar Panda, Aaron Courville<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=YDZ7GeFLxq)<br/>

---

## [What Are Tools Anyway? A Survey from the Language Model Perspective](https://huggingface.co/papers/2403.15452)<br/>
**Authors:** Zhiruo Wang, Zhoujun Cheng, Hao Zhu, Daniel Fried, Graham Neubig<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Xh1B90iBSR)<br/>
**arXiv:** [2403.15452](https://arxiv.org/abs/2403.15452)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.15452](https://huggingface.co/papers/2403.15452)<br/>

---

## A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration<br/>
**Authors:** Zijun Liu, Yanzhe Zhang, Peng Li, Yang Liu, Diyi Yang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=XII0Wp1XA9)<br/>

---

## Data Checklist: On Unit-Testing Datasets with Usable Information<br/>
**Authors:** Heidi Chenyu Zhang, Shabnam Behzad, Kawin Ethayarajh, Dan Jurafsky<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=XGJBEeziEb)<br/>

---

## MBBQ: A Dataset for Cross-Lingual Comparison of Stereotypes in Generative LLMs<br/>
**Authors:** Vera Neplenbroek, Arianna Bisazza, Raquel Fernández<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=X9yV4lFHt4)<br/>

---

## MambaByte: Token-free Selective State Space Model<br/>
**Authors:** Junxiong Wang, Tushaar Gangavarapu, Jing Nathan Yan, Alexander M Rush<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=X1xNsuKssb)<br/>

---

## Description-Based Text Similarity<br/>
**Authors:** Shauli Ravfogel, Valentina Pyatkin, Amir David Nissan Cohen, Avshalom Manevich, Yoav Goldberg<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=W8Rv1jVycX)<br/>

---

## Generating Synthetic Datasets for Few-shot Prompt Tuning<br/>
**Authors:** Xu Guo, Zilin Du, Boyang Li, Chunyan Miao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Vd0KvChLXr)<br/>

---

## [Crowd-Calibrator: Can Annotator Disagreement Inform Calibration in Subjective Tasks?](https://arxiv.org/abs/2408.14141)<br/>
**Authors:** Urja Khurana, Eric Nalisnick, Antske Fokkens, Swabha Swayamdipta<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=VWWzO3ewMS)<br/>
**arXiv:** [2408.14141](https://arxiv.org/abs/2408.14141)<br/>

---

## Does RoBERTa Perform Better than BERT in Continual Learning: An Attention Sink Perspective<br/>
**Authors:** Xueying Bai, Yifan Sun, Niranjan Balasubramanian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=VHhwhmtx3b)<br/>

---

## An In-Context Learning Agent for Formal Theorem-Proving<br/>
**Authors:** Amitayush Thakur, George Tsoukalas, Yeming Wen, Jimmy Xin, Swarat Chaudhuri<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=V7HRrxXUhN)<br/>

---

## [Efficient Parallelization Layouts for Large-Scale Distributed Model Training](https://huggingface.co/papers/2311.05610)<br/>
**Authors:** Johannes Hagemann, Samuel Weinbach, Konstantin Dobler, Maximilian Schall, Gerard de Melo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=UyNIH6CWHH)<br/>
**arXiv:** [2311.05610](https://arxiv.org/abs/2311.05610)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2311.05610](https://huggingface.co/papers/2311.05610)<br/>

---

## [Unforgettable Generalization in Language Models](https://huggingface.co/papers/2409.02228)<br/>
**Authors:** Eric Zhang, Leshem Choshen, Jacob Andreas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Ukf4301hXm)<br/>
**arXiv:** [2409.02228](https://arxiv.org/abs/2409.02228)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2409.02228](https://huggingface.co/papers/2409.02228)<br/>

---

## MileBench: Benchmarking MLLMs in Long Context<br/>
**Authors:** Song Dingjie, Shunian Chen, Guiming Hardy Chen, Fei Yu, Xiang Wan, Benyou Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Uhwze2LEwq)<br/>

---

## [AmpleGCG: Learning a Universal and Transferable Generative Model of Adversarial Suffixes for Jailbreaking Both Open and Closed LLMs](https://huggingface.co/papers/2404.07921)<br/>
**Authors:** Zeyi Liao, Huan Sun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=UfqzXg95I5)<br/>
**arXiv:** [2404.07921](https://arxiv.org/abs/2404.07921)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.07921](https://huggingface.co/papers/2404.07921)<br/>
**🤗 Models:** [osunlp/AmpleGCG-llama2-sourced-llama2-7b-chat](https://huggingface.co/osunlp/AmpleGCG-llama2-sourced-llama2-7b-chat), [osunlp/AmpleGCG-llama2-sourced-vicuna-7b](https://huggingface.co/osunlp/AmpleGCG-llama2-sourced-vicuna-7b), [osunlp/AmpleGCG-llama2-sourced-vicuna-7b13b-guanaco-7b13b](https://huggingface.co/osunlp/AmpleGCG-llama2-sourced-vicuna-7b13b-guanaco-7b13b), [osunlp/AmpleGCG-plus-llama2-sourced-llama2-7b-chat](https://huggingface.co/osunlp/AmpleGCG-plus-llama2-sourced-llama2-7b-chat), [osunlp/AmpleGCG-plus-llama2-sourced-vicuna-7b13b-guanaco-7b13b](https://huggingface.co/osunlp/AmpleGCG-plus-llama2-sourced-vicuna-7b13b-guanaco-7b13b)<br/>

---

## [List Items One by One: A New Data Source and Learning Paradigm for Multimodal LLMs](https://huggingface.co/papers/2404.16375)<br/>
**Authors:** An Yan, Zhengyuan Yang, Junda Wu, Wanrong Zhu, Jianwei Yang, Linjie Li, Kevin Lin, Jianfeng Wang, Julian McAuley, Jianfeng Gao, Lijuan Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=UfWwBaLuXV)<br/>
**arXiv:** [2404.16375](https://arxiv.org/abs/2404.16375)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.16375](https://huggingface.co/papers/2404.16375)<br/>
**🤗 Models:** [zzxslp/som-llava-v1.5-13b](https://huggingface.co/zzxslp/som-llava-v1.5-13b), [zzxslp/som-llava-v1.5-13b-hf](https://huggingface.co/zzxslp/som-llava-v1.5-13b-hf)<br/>

---

## Source-Aware Training Enables Knowledge Attribution in Language Models<br/>
**Authors:** Muhammad Khalifa, David Wadden, Emma Strubell, Honglak Lee, Lu Wang, Iz Beltagy, Hao Peng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=UPyWLwciYz)<br/>

---

## [A Language Agent for Autonomous Driving](https://huggingface.co/papers/2311.10813)<br/>
**Authors:** Jiageng Mao, Junjie Ye, Yuxi Qian, Marco Pavone, Yue Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=UPE6WYE8vg)<br/>
**arXiv:** [2311.10813](https://arxiv.org/abs/2311.10813)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2311.10813](https://huggingface.co/papers/2311.10813)<br/>

---

## [Auxiliary task demands mask the capabilities of smaller language models](https://arxiv.org/abs/2404.02418)<br/>
**Authors:** Jennifer Hu, Michael Frank<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=U5BUzSn4tD)<br/>
**arXiv:** [2404.02418](https://arxiv.org/abs/2404.02418)<br/>

---

## [LoraHub: Efficient Cross-Task Generalization via Dynamic LoRA Composition](https://huggingface.co/papers/2307.13269)<br/>
**Authors:** Chengsong Huang, Qian Liu, Bill Yuchen Lin, Tianyu Pang, Chao Du, Min Lin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=TrloAXEJ2B)<br/>
**arXiv:** [2307.13269](https://arxiv.org/abs/2307.13269)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2307.13269](https://huggingface.co/papers/2307.13269)<br/>
**🤗 Spaces:** [sail/lorahub](https://huggingface.co/spaces/sail/lorahub)<br/>

---

## GPQA: A Graduate-Level Google-Proof Q   A Benchmark<br/>
**Authors:** David Rein, Betty Li Hou, Asa Cooper Stickland, Jackson Petty, Richard Yuanzhe Pang, Julien Dirani, Julian Michael, Samuel R. Bowman<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Ti67584b98)<br/>

---

## [Have Faith in Faithfulness: Going Beyond Circuit Overlap When Finding Model Mechanisms](https://huggingface.co/papers/2403.17806)<br/>
**Authors:** Michael Hanna, Sandro Pezzelle, Yonatan Belinkov<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=TZ0CCGDcuT)<br/>
**arXiv:** [2403.17806](https://arxiv.org/abs/2403.17806)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.17806](https://huggingface.co/papers/2403.17806)<br/>

---

## [Stronger Random Baselines for In-Context Learning](https://arxiv.org/abs/2404.13020)<br/>
**Authors:** Gregory Yauney, David Mimno<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=TRxQMpLUfD)<br/>
**arXiv:** [2404.13020](https://arxiv.org/abs/2404.13020)<br/>

---

## [Continual Pre-Training for Cross-Lingual LLM Adaptation: Enhancing Japanese Language Capabilities](https://huggingface.co/papers/2404.17790)<br/>
**Authors:** Kazuki Fujii, Taishi Nakamura, Mengsay Loem, Hiroki Iida, Masanari Ohi, Kakeru Hattori, Hirai Shota, Sakae Mizuki, Rio Yokota, Naoaki Okazaki<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=TQdd1VhWbe)<br/>
**arXiv:** [2404.17790](https://arxiv.org/abs/2404.17790)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.17790](https://huggingface.co/papers/2404.17790)<br/>
**🤗 Models:** [tokyotech-llm/Swallow-7b-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-instruct-hf), [tokyotech-llm/Swallow-70b-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-70b-instruct-hf), [tokyotech-llm/Swallow-13b-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-13b-instruct-hf), [tokyotech-llm/Swallow-7b-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-hf), [tokyotech-llm/Swallow-13b-hf](https://huggingface.co/tokyotech-llm/Swallow-13b-hf), [tokyotech-llm/Swallow-7b-plus-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-plus-hf), [tokyotech-llm/Swallow-70b-hf](https://huggingface.co/tokyotech-llm/Swallow-70b-hf), [tokyotech-llm/Swallow-7b-NVE-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-NVE-instruct-hf), [tokyotech-llm/Swallow-70b-NVE-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-70b-NVE-instruct-hf), [tokyotech-llm/Swallow-7b-NVE-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-NVE-hf), [tokyotech-llm/Swallow-70b-NVE-hf](https://huggingface.co/tokyotech-llm/Swallow-70b-NVE-hf), [tokyotech-llm/Swallow-13b-NVE-hf](https://huggingface.co/tokyotech-llm/Swallow-13b-NVE-hf), [RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-4bits](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-4bits), [RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-8bits](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-8bits), [RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-4bits](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-4bits), [RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-8bits](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-8bits), [RichardErkhov/tokyotech-llm_-_Swallow-13b-instruct-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-13b-instruct-hf-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-70b-NVE-instruct-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-70b-NVE-instruct-hf-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-70b-instruct-v0.1-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-70b-instruct-v0.1-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-13b-instruct-v0.1-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-13b-instruct-v0.1-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-7b-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-hf-gguf)<br/>
**🤗 Spaces:** [hayas/Swallow-13B-instruct](https://huggingface.co/spaces/hayas/Swallow-13B-instruct), [mmnga/vocabviewer](https://huggingface.co/spaces/mmnga/vocabviewer), [kmero/tokyotech-llm-Swallow-70b-instruct-hf](https://huggingface.co/spaces/kmero/tokyotech-llm-Swallow-70b-instruct-hf), [isonuma/marutenbo](https://huggingface.co/spaces/isonuma/marutenbo), [Huaibo/tokyotech-llm-Swallow-7b-instruct-hf](https://huggingface.co/spaces/Huaibo/tokyotech-llm-Swallow-7b-instruct-hf)<br/>

---

## Decoupling Noise and Toxic Parameters for Language Model Detoxification by Task Vector Merging<br/>
**Authors:** Yongmin Kim, Takeshi Kojima, Yusuke Iwasawa, Yutaka Matsuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=TBNYjdOazs)<br/>

---

## [Optimising Calls to Large Language Models with Uncertainty-Based Two-Tier Selection](https://arxiv.org/abs/2405.02134)<br/>
**Authors:** Guillem Ramírez, Alexandra Birch, Ivan Titov<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=T9cOYH0wGF)<br/>
**arXiv:** [2405.02134](https://arxiv.org/abs/2405.02134)<br/>

---

## Adaptive Quantization Error Reconstruction for LLMs with Mixed Precision<br/>
**Authors:** Lin Ou, Jinpeng Xia, Yuewei Zhang, Chuzhan Hao, Hao Henry Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=T5pGDydMkS)<br/>

---

## StyleTalker: Finetuning Audio Language Model and Style-Based Text-to-Speech Model for Fast Spoken Dialogue Generation<br/>
**Authors:** Yinghao Aaron Li, Xilin Jiang, Jordan Darefsky, Ge Zhu, Nima Mesgarani<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Szp33itD10)<br/>

---

## [Iteratively Prompting Multimodal LLMs to Reproduce Natural and AI-Generated Images](https://arxiv.org/abs/2404.13784)<br/>
**Authors:** Ali Naseh, Katherine Thai, Mohit Iyyer, Amir Houmansadr<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=SwUsFTtM9h)<br/>
**arXiv:** [2404.13784](https://arxiv.org/abs/2404.13784)<br/>

---

## [Compression Represents Intelligence Linearly](https://huggingface.co/papers/2404.09937)<br/>
**Authors:** Yuzhen Huang, Jinghan Zhang, Zifei Shan, Junxian He<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=SHMj84U5SH)<br/>
**arXiv:** [2404.09937](https://arxiv.org/abs/2404.09937)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.09937](https://huggingface.co/papers/2404.09937)<br/>
**🤗 Datasets:** [hkust-nlp/llm-compression](https://huggingface.co/datasets/hkust-nlp/llm-compression)<br/>

---

## Beyond A*: Better Planning with Transformers via Search Dynamics Bootstrapping<br/>
**Authors:** Lucas Lehnert, Sainbayar Sukhbaatar, DiJia Su, Qinqing Zheng, Paul McVay, Michael Rabbat, Yuandong Tian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=SGoVIC0u0f)<br/>

---

## [How Easily do Irrelevant Inputs Skew the Responses of Large Language Models?](https://huggingface.co/papers/2404.03302)<br/>
**Authors:** Siye Wu, Jian Xie, Jiangjie Chen, Tinghui Zhu, Kai Zhang, Yanghua Xiao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=S7NVVfuRv8)<br/>
**arXiv:** [2404.03302](https://arxiv.org/abs/2404.03302)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.03302](https://huggingface.co/papers/2404.03302)<br/>

---

## [Evaluating Cultural Adaptability of a Large Language Model via Simulation of Synthetic Personas](https://arxiv.org/abs/2408.06929)<br/>
**Authors:** Louis Kwok, Michal Bravansky, Lewis Griffin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=S4ZOkV1AHl)<br/>
**arXiv:** [2408.06929](https://arxiv.org/abs/2408.06929)<br/>

---

## [Deductive Beam Search: Decoding Deducible Rationale for Chain-of-Thought Reasoning](https://huggingface.co/papers/2401.17686)<br/>
**Authors:** Tinghui Zhu, Kai Zhang, Jian Xie, Yu Su<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=S1XnUsqwr7)<br/>
**arXiv:** [2401.17686](https://arxiv.org/abs/2401.17686)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2401.17686](https://huggingface.co/papers/2401.17686)<br/>

---

## [LLM economicus? Mapping the Behavioral Biases of LLMs via Utility Theory](https://arxiv.org/abs/2408.02784)<br/>
**Authors:** Jillian Ross, Yoon Kim, Andrew Lo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Rx3wC8sCTJ)<br/>
**arXiv:** [2408.02784](https://arxiv.org/abs/2408.02784)<br/>

---

## CALM : A Multi-task Benchmark for Comprehensive Assessment of Language Model Bias<br/>
**Authors:** Vipul Gupta, Pranav Narayanan Venkit, Hugo Laurençon, Shomir Wilson, Rebecca J. Passonneau<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=RLFca3arx7)<br/>

---

## Chinese Tiny LLM: Pretraining a Chinese-Centered Large Language Model<br/>
**Authors:** Xeron Du, Zhouliang Yu, Songyang Gao, Ding Pan, Cheng Yuyang, Ziyang Ma, Ruibin Yuan, Xingwei Qu, Jiaheng Liu, Tianyu Zheng, Xinchen Luo, Guorui Zhou, Wenhu Chen, Ge Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=RCdoMrg4I0)<br/>

---

## [Using Natural Language Explanations to Rescale Human Judgments](https://huggingface.co/papers/2305.14770)<br/>
**Authors:** Manya Wadhwa, Jifan Chen, Junyi Jessy Li, Greg Durrett<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Qmq4zqdnWh)<br/>
**arXiv:** [2305.14770](https://arxiv.org/abs/2305.14770)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2305.14770](https://huggingface.co/papers/2305.14770)<br/>
**🤗 Datasets:** [wadhma/EBR](https://huggingface.co/datasets/wadhma/EBR)<br/>

---

## LLM360: Towards Fully Transparent Open-Source LLMs<br/>
**Authors:** Zhengzhong Liu, Aurick Qiao, Willie Neiswanger, Hongyi Wang, Bowen Tan, Tianhua Tao, Junbo Li, Yuqi Wang, Suqi Sun, Omkar Pangarkar, Richard Fan, Yi Gu, Victor Miller, Yonghao Zhuang, Guowei He, Haonan Li, Fajri Koto, Liping Tang, Nikhil Ranjan, Zhiqiang Shen, Roberto Iriondo, Cun Mu, Zhiting Hu, Mark Schulze, Preslav Nakov, Timothy Baldwin, Eric P. Xing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=QdWhj0QZFw)<br/>

---

## From Narratives to Numbers: Valid Inference Using Language Model Predictions from Verbal Autopsies<br/>
**Authors:** Shuxian Fan, Adam Visokay, Kentaro Hoffman, Stephen Salerno, Li Liu, Jeffrey T. Leek, Tyler McCormick<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=QbCHlIqbDJ)<br/>

---

## [The Larger the Better? Improved LLM Code-Generation via Budget Reallocation](https://arxiv.org/abs/2404.00725)<br/>
**Authors:** Michael Hassid, Tal Remez, Jonas Gehring, Roy Schwartz, Yossi Adi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=QJvfpWSpWm)<br/>
**arXiv:** [2404.00725](https://arxiv.org/abs/2404.00725)<br/>

---

## "Merge Conflicts!'" Exploring the Impacts of External Knowledge Distractors to Parametric Knowledge Graphs<br/>
**Authors:** Cheng Qian, Xinran Zhao, Tongshuang Wu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Pvn1dKreZW)<br/>

---

## Emergent World Models and Latent Variable Estimation in Chess-Playing Language Models<br/>
**Authors:** Adam Karvonen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=PPTrmvEnpW)<br/>

---

## AgentKit: Structured LLM Reasoning with Dynamic Graphs<br/>
**Authors:** Yue Wu, Yewen Fan, So Yeon Min, Shrimai Prabhumoye, Stephen Marcus McAleer, Ruslan Salakhutdinov, Yonatan Bisk, Yuanzhi Li, Tom Mitchell<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=PKfAq8N4fK)<br/>

---

## [A Reparameterized Discrete Diffusion Model for Text Generation](https://huggingface.co/papers/2302.05737)<br/>
**Authors:** Lin Zheng, Jianbo Yuan, Lei Yu, Lingpeng Kong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=PEQFHRUFca)<br/>
**arXiv:** [2302.05737](https://arxiv.org/abs/2302.05737)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2302.05737](https://huggingface.co/papers/2302.05737)<br/>

---

## [Best Practices and Lessons Learned on Synthetic Data](https://huggingface.co/papers/2404.07503)<br/>
**Authors:** Ruibo Liu, Jerry Wei, Fangyu Liu, Chenglei Si, Yanzhe Zhang, Jinmeng Rao, Steven Zheng, Daiyi Peng, Diyi Yang, Denny Zhou, Andrew M. Dai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=OJaWBhh61C)<br/>
**arXiv:** [2404.07503](https://arxiv.org/abs/2404.07503)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.07503](https://huggingface.co/papers/2404.07503)<br/>

---

## Let’s Think Dot by Dot: Hidden computation in transformer language models<br/>
**Authors:** Jacob Pfau, William Merrill, Samuel R. Bowman<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=NikbrdtYvG)<br/>

---

## [Multi-hop Question Answering under Temporal Knowledge Editing](https://arxiv.org/abs/2404.00492)<br/>
**Authors:** Keyuan Cheng, Gang Lin, Haoyang Fei, Yuxuan Zhai, Lu Yu, Muhammad Asif Ali, Lijie Hu, Di Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Nd950RAcCW)<br/>
**arXiv:** [2404.00492](https://arxiv.org/abs/2404.00492)<br/>

---

## [DiagrammerGPT: Generating Open-Domain, Open-Platform Diagrams via LLM Planning](https://huggingface.co/papers/2310.12128)<br/>
**Authors:** Abhay Zala, Han Lin, Jaemin Cho, Mohit Bansal<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=NV8yRJRET1)<br/>
**arXiv:** [2310.12128](https://arxiv.org/abs/2310.12128)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2310.12128](https://huggingface.co/papers/2310.12128)<br/>
**🤗 Datasets:** [abhayzala/AI2D-Caption](https://huggingface.co/datasets/abhayzala/AI2D-Caption)<br/>

---

## [Autonomous Evaluation and Refinement of Digital Agents](https://huggingface.co/papers/2404.06474)<br/>
**Authors:** Jiayi Pan, Yichi Zhang, Nicholas Tomlin, Yifei Zhou, Sergey Levine, Alane Suhr<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=NPAQ6FKSmK)<br/>
**arXiv:** [2404.06474](https://arxiv.org/abs/2404.06474)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.06474](https://huggingface.co/papers/2404.06474)<br/>
**🤗 Spaces:** [Agent-Eval-Refine/Captioner](https://huggingface.co/spaces/Agent-Eval-Refine/Captioner)<br/>

---

## [Building a Large Japanese Web Corpus for Large Language Models](https://huggingface.co/papers/2404.17733)<br/>
**Authors:** Naoaki Okazaki, Kakeru Hattori, Hirai Shota, Hiroki Iida, Masanari Ohi, Kazuki Fujii, Taishi Nakamura, Mengsay Loem, Rio Yokota, Sakae Mizuki<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=N5EYQSwW26)<br/>
**arXiv:** [2404.17733](https://arxiv.org/abs/2404.17733)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.17733](https://huggingface.co/papers/2404.17733)<br/>
**🤗 Models:** [tokyotech-llm/Swallow-7b-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-instruct-hf), [tokyotech-llm/Swallow-70b-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-70b-instruct-hf), [tokyotech-llm/Swallow-MX-8x7b-NVE-v0.1](https://huggingface.co/tokyotech-llm/Swallow-MX-8x7b-NVE-v0.1), [tokyotech-llm/Swallow-MS-7b-v0.1](https://huggingface.co/tokyotech-llm/Swallow-MS-7b-v0.1), [tokyotech-llm/Swallow-13b-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-13b-instruct-hf), [tokyotech-llm/Swallow-7b-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-hf), [tokyotech-llm/Swallow-13b-hf](https://huggingface.co/tokyotech-llm/Swallow-13b-hf), [tokyotech-llm/Swallow-7b-plus-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-plus-hf), [tokyotech-llm/Llama-3-Swallow-8B-v0.1](https://huggingface.co/tokyotech-llm/Llama-3-Swallow-8B-v0.1), [tokyotech-llm/Swallow-70b-hf](https://huggingface.co/tokyotech-llm/Swallow-70b-hf), [tokyotech-llm/Llama-3-Swallow-70B-v0.1](https://huggingface.co/tokyotech-llm/Llama-3-Swallow-70B-v0.1), [tokyotech-llm/Swallow-7b-NVE-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-NVE-instruct-hf), [tokyotech-llm/Swallow-70b-NVE-instruct-hf](https://huggingface.co/tokyotech-llm/Swallow-70b-NVE-instruct-hf), [tokyotech-llm/Swallow-7b-NVE-hf](https://huggingface.co/tokyotech-llm/Swallow-7b-NVE-hf), [tokyotech-llm/Swallow-70b-NVE-hf](https://huggingface.co/tokyotech-llm/Swallow-70b-NVE-hf), [tokyotech-llm/Swallow-13b-NVE-hf](https://huggingface.co/tokyotech-llm/Swallow-13b-NVE-hf), [RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-4bits](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-4bits), [RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-8bits](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-NVE-instruct-hf-8bits), [RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-4bits](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-4bits), [RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-8bits](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-instruct-hf-8bits), [RichardErkhov/tokyotech-llm_-_Swallow-13b-instruct-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-13b-instruct-hf-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-70b-NVE-instruct-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-70b-NVE-instruct-hf-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-MS-7b-v0.1-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-MS-7b-v0.1-gguf), [RichardErkhov/tokyotech-llm_-_Llama-3-Swallow-8B-v0.1-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Llama-3-Swallow-8B-v0.1-gguf), [RichardErkhov/tokyotech-llm_-_Swallow-7b-hf-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Swallow-7b-hf-gguf), [RichardErkhov/tokyotech-llm_-_Llama-3-Swallow-70B-v0.1-gguf](https://huggingface.co/RichardErkhov/tokyotech-llm_-_Llama-3-Swallow-70B-v0.1-gguf)<br/>
**🤗 Spaces:** [featherless-ai/try-this-model](https://huggingface.co/spaces/featherless-ai/try-this-model), [hayas/Swallow-13B-instruct](https://huggingface.co/spaces/hayas/Swallow-13B-instruct), [Darok/Featherless-Feud](https://huggingface.co/spaces/Darok/Featherless-Feud), [mmnga/vocabviewer](https://huggingface.co/spaces/mmnga/vocabviewer), [Granther/try-this-model](https://huggingface.co/spaces/Granther/try-this-model), [emekaboris/try-this-model](https://huggingface.co/spaces/emekaboris/try-this-model), [isonuma/marutenbo](https://huggingface.co/spaces/isonuma/marutenbo), [kmero/tokyotech-llm-Swallow-70b-instruct-hf](https://huggingface.co/spaces/kmero/tokyotech-llm-Swallow-70b-instruct-hf), [Huaibo/tokyotech-llm-Swallow-7b-instruct-hf](https://huggingface.co/spaces/Huaibo/tokyotech-llm-Swallow-7b-instruct-hf)<br/>

---

## [Why do small language models underperform? Studying Language Model Saturation via the Softmax Bottleneck](https://huggingface.co/papers/2404.07647)<br/>
**Authors:** Nathan Godey, Éric Villemonte de la Clergerie, Benoît Sagot<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=MoitXWlXcS)<br/>
**arXiv:** [2404.07647](https://arxiv.org/abs/2404.07647)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.07647](https://huggingface.co/papers/2404.07647)<br/>

---

## Are Language Models Robust Coreference Resolvers?<br/>
**Authors:** Nghia T. Le, Alan Ritter<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=MmBQSNHKUl)<br/>

---

## Information Guided Regularization for Fine-tuning Language Models<br/>
**Authors:** Mandar Sharma, Nikhil Muralidhar, Shengzhe Xu, Raquib Bin Yousuf, Naren Ramakrishnan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=MkppMETE49)<br/>

---

## [Negative Preference Optimization: From Catastrophic Collapse to Effective Unlearning](https://arxiv.org/abs/2404.05868)<br/>
**Authors:** Ruiqi Zhang, Licong Lin, Yu Bai, Song Mei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=MXLBXjQkmb)<br/>
**arXiv:** [2404.05868](https://arxiv.org/abs/2404.05868)<br/>

---

## [ScenicNL: Generating Probabilistic Scenario Programs from Natural Language](https://arxiv.org/abs/2405.03709)<br/>
**Authors:** Karim Elmaaroufi, Devan Shanker, Ana Cismaru, Marcell Vazquez-Chanlatte, Alberto Sangiovanni-Vincentelli, Matei Zaharia, Sanjit A. Seshia<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=MNLAbfZwh2)<br/>
**arXiv:** [2405.03709](https://arxiv.org/abs/2405.03709)<br/>

---

## [Your Context Is Not an Array: Unveiling Random Access Limitations in Transformers](https://huggingface.co/papers/2408.05506)<br/>
**Authors:** MohammadReza Ebrahimi, Sunny Panchal, Roland Memisevic<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=MLD1cwfjUb)<br/>
**arXiv:** [2408.05506](https://arxiv.org/abs/2408.05506)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2408.05506](https://huggingface.co/papers/2408.05506)<br/>

---

## Commonsense-T2I Challenge: Can Text-to-Image Generation Models Understand Commonsense?<br/>
**Authors:** Xingyu Fu, Muyu He, Yujie Lu, William Yang Wang, Dan Roth<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=MI52iXSSNy)<br/>

---

## [From Words to Numbers: Your Large Language Model Is Secretly A Capable Regressor When Given In-Context Examples](https://huggingface.co/papers/2404.07544)<br/>
**Authors:** Robert Vacareanu, Vlad Andrei Negru, Vasile Suciu, Mihai Surdeanu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=LzpaUxcNFK)<br/>
**arXiv:** [2404.07544](https://arxiv.org/abs/2404.07544)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.07544](https://huggingface.co/papers/2404.07544)<br/>

---

## Beyond Accuracy: Evaluating the Reasoning Behavior of Large Language Models - A Survey<br/>
**Authors:** Philipp Mondorf, Barbara Plank<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Lmjgl2n11u)<br/>

---

## [Forklift: An Extensible Neural Lifter](https://arxiv.org/abs/2404.16041)<br/>
**Authors:** Jordi Armengol-Estapé, Rodrigo C. O. Rocha, Jackson Woodruff, Pasquale Minervini, Michael O'Boyle<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=LWfDcI6txJ)<br/>
**arXiv:** [2404.16041](https://arxiv.org/abs/2404.16041)<br/>

---

## Lory: Fully Differentiable Mixture-of-Experts for Autoregressive Language Model Pre-training<br/>
**Authors:** Zexuan Zhong, Mengzhou Xia, Danqi Chen, Mike Lewis<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=LKEJPySnlt)<br/>

---

## What makes a good metric? Evaluating automatic metrics for text-to-image consistency<br/>
**Authors:** Candace Ross, Melissa Hall, Adriana Romero-Soriano, Adina Williams<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=LFfktMPAci)<br/>

---

## [Empowering Large Language Model Agents through Action Learning](https://huggingface.co/papers/2402.15809)<br/>
**Authors:** Haiteng Zhao, Chang Ma, Guoyin Wang, Jing Su, Lingpeng Kong, Jingjing Xu, Zhi-Hong Deng, Hongxia Yang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=KqK5XcgEhR)<br/>
**arXiv:** [2402.15809](https://arxiv.org/abs/2402.15809)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2402.15809](https://huggingface.co/papers/2402.15809)<br/>

---

## On Limitations of the Transformer Architecture<br/>
**Authors:** Binghui Peng, Srini Narayanan, Christos Papadimitriou<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=KidynPuLNW)<br/>

---

## [IsoBench: Benchmarking Multimodal Foundation Models on Isomorphic Representations](https://huggingface.co/papers/2404.01266)<br/>
**Authors:** Deqing Fu, Ruohao Guo, Ghazal Khalighinejad, Ollie Liu, Bhuwan Dhingra, Dani Yogatama, Robin Jia, Willie Neiswanger<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=KZd1EErRJ1)<br/>
**arXiv:** [2404.01266](https://arxiv.org/abs/2404.01266)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.01266](https://huggingface.co/papers/2404.01266)<br/>
**🤗 Datasets:** [isobench/IsoBench](https://huggingface.co/datasets/isobench/IsoBench)<br/>

---

## On Fairness of Low-Rank Adaptation of Large Models<br/>
**Authors:** Zhoujie Ding, Ken Liu, Pura Peetathawatchai, Berivan Isik, Sanmi Koyejo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=K1M3gLW0MX)<br/>

---

## [Mind the Privacy Unit! User-Level Differential Privacy for Language Model Fine-Tuning](https://arxiv.org/abs/2406.14322)<br/>
**Authors:** Lynn Chua, Badih Ghazi, Yangsibo Huang, Pritish Kamath, Ravi Kumar, Daogao Liu, Pasin Manurangsi, Amer Sinha, Chiyuan Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Jd0bCD12DS)<br/>
**arXiv:** [2406.14322](https://arxiv.org/abs/2406.14322)<br/>

---

## Information-Theoretic Distillation for Reference-less Summarization<br/>
**Authors:** Jaehun Jung, Ximing Lu, Liwei Jiang, Faeze Brahman, Peter West, Pang Wei Koh, Yejin Choi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=JXcXnJJSuL)<br/>

---

## [LLM2Vec: Large Language Models Are Secretly Powerful Text Encoders](https://huggingface.co/papers/2404.05961)<br/>
**Authors:** Parishad BehnamGhader, Vaibhav Adlakha, Marius Mosbach, Dzmitry Bahdanau, Nicolas Chapados, Siva Reddy<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=IW1PR7vEBf)<br/>
**arXiv:** [2404.05961](https://arxiv.org/abs/2404.05961)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.05961](https://huggingface.co/papers/2404.05961)<br/>
**🤗 Models:** [McGill-NLP/LLM2Vec-Meta-Llama-3-8B-Instruct-mntp-supervised](https://huggingface.co/McGill-NLP/LLM2Vec-Meta-Llama-3-8B-Instruct-mntp-supervised), [McGill-NLP/LLM2Vec-Mistral-7B-Instruct-v2-mntp-supervised](https://huggingface.co/McGill-NLP/LLM2Vec-Mistral-7B-Instruct-v2-mntp-supervised), [McGill-NLP/LLM2Vec-Meta-Llama-3-8B-Instruct-mntp](https://huggingface.co/McGill-NLP/LLM2Vec-Meta-Llama-3-8B-Instruct-mntp), [McGill-NLP/LLM2Vec-Mistral-7B-Instruct-v2-mntp](https://huggingface.co/McGill-NLP/LLM2Vec-Mistral-7B-Instruct-v2-mntp), [McGill-NLP/LLM2Vec-Mistral-7B-Instruct-v2-mntp-unsup-simcse](https://huggingface.co/McGill-NLP/LLM2Vec-Mistral-7B-Instruct-v2-mntp-unsup-simcse), [knowledgator/Qwen-encoder-0.5B](https://huggingface.co/knowledgator/Qwen-encoder-0.5B), [McGill-NLP/LLM2Vec-Sheared-LLaMA-mntp](https://huggingface.co/McGill-NLP/LLM2Vec-Sheared-LLaMA-mntp), [McGill-NLP/LLM2Vec-Sheared-LLaMA-mntp-supervised](https://huggingface.co/McGill-NLP/LLM2Vec-Sheared-LLaMA-mntp-supervised), [McGill-NLP/LLM2Vec-Meta-Llama-3-8B-Instruct-mntp-unsup-simcse](https://huggingface.co/McGill-NLP/LLM2Vec-Meta-Llama-3-8B-Instruct-mntp-unsup-simcse), [McGill-NLP/LLM2Vec-Llama-2-7b-chat-hf-mntp-supervised](https://huggingface.co/McGill-NLP/LLM2Vec-Llama-2-7b-chat-hf-mntp-supervised), [McGill-NLP/LLM2Vec-Sheared-LLaMA-mntp-unsup-simcse](https://huggingface.co/McGill-NLP/LLM2Vec-Sheared-LLaMA-mntp-unsup-simcse), [knowledgator/Sheared-LLaMA-encoder-1.3B](https://huggingface.co/knowledgator/Sheared-LLaMA-encoder-1.3B), [knowledgator/Qwen-encoder-1.5B](https://huggingface.co/knowledgator/Qwen-encoder-1.5B), [macadeliccc/dolphin-2.9-llama3-8b-emb](https://huggingface.co/macadeliccc/dolphin-2.9-llama3-8b-emb), [McGill-NLP/LLM2Vec-Llama-2-7b-chat-hf-mntp](https://huggingface.co/McGill-NLP/LLM2Vec-Llama-2-7b-chat-hf-mntp), [McGill-NLP/LLM2Vec-Llama-2-7b-chat-hf-mntp-unsup-simcse](https://huggingface.co/McGill-NLP/LLM2Vec-Llama-2-7b-chat-hf-mntp-unsup-simcse), [knowledgator/Llama-encoder-1.0B](https://huggingface.co/knowledgator/Llama-encoder-1.0B), [uzabase/LLM2Vec-Llama-2-7b-hf-mntp](https://huggingface.co/uzabase/LLM2Vec-Llama-2-7b-hf-mntp), [uzabase/LLM2Vec-Llama-2-7b-hf-wikipedia-jp-mntp](https://huggingface.co/uzabase/LLM2Vec-Llama-2-7b-hf-wikipedia-jp-mntp), [uzabase/LLM2Vec-Swallow-7b-hf-wikipedia-jp-mntp](https://huggingface.co/uzabase/LLM2Vec-Swallow-7b-hf-wikipedia-jp-mntp), [uzabase/LLM2Vec-Llama-2-7b-hf-mntp-unsup-simcse](https://huggingface.co/uzabase/LLM2Vec-Llama-2-7b-hf-mntp-unsup-simcse), [uzabase/LLM2Vec-Llama-2-7b-hf-wikipedia-jp-mntp-unsup-simcse](https://huggingface.co/uzabase/LLM2Vec-Llama-2-7b-hf-wikipedia-jp-mntp-unsup-simcse), [uzabase/LLM2Vec-Swallow-7b-hf-wikipedia-jp-mntp-unsup-simcse](https://huggingface.co/uzabase/LLM2Vec-Swallow-7b-hf-wikipedia-jp-mntp-unsup-simcse), [RichardErkhov/knowledgator_-_Llama-encoder-1.0B-gguf](https://huggingface.co/RichardErkhov/knowledgator_-_Llama-encoder-1.0B-gguf), [RichardErkhov/knowledgator_-_Qwen-encoder-0.5B-gguf](https://huggingface.co/RichardErkhov/knowledgator_-_Qwen-encoder-0.5B-gguf), [RichardErkhov/knowledgator_-_Qwen-encoder-1.5B-gguf](https://huggingface.co/RichardErkhov/knowledgator_-_Qwen-encoder-1.5B-gguf)<br/>
**🤗 Spaces:** [mteb/leaderboard](https://huggingface.co/spaces/mteb/leaderboard), [mteb/arena](https://huggingface.co/spaces/mteb/arena), [Nymbo/MTEB-Arena](https://huggingface.co/spaces/Nymbo/MTEB-Arena), [Abhijit-192-168-1-1/example_LLM2Vec](https://huggingface.co/spaces/Abhijit-192-168-1-1/example_LLM2Vec)<br/>

---

## Faithful and Unfaithful Error Recovery in Chain of Thought<br/>
**Authors:** Evelyn Yee, Alice Li, Chenyu Tang, Yeon Ho Jung, Ramamohan Paturi, Leon Bergen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=IPZ28ZqD4I)<br/>

---

## AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models<br/>
**Authors:** Sicheng Zhu, Ruiyi Zhang, Bang An, Gang Wu, Joe Barrow, Zichao Wang, Furong Huang, Ani Nenkova, Tong Sun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=INivcBeIDK)<br/>

---

## [Evaluating Language Models for Efficient Code Generation](https://huggingface.co/papers/2408.06450)<br/>
**Authors:** Jiawei Liu, Songrun Xie, Junhao Wang, Yuxiang Wei, Yifeng Ding, LINGMING ZHANG<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=IBCBMeAhmC)<br/>
**arXiv:** [2408.06450](https://arxiv.org/abs/2408.06450)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2408.06450](https://huggingface.co/papers/2408.06450)<br/>

---

## [Early Weight Averaging meets High Learning Rates for LLM Pre-training](https://huggingface.co/papers/2306.03241)<br/>
**Authors:** Sunny Sanyal, Atula Tejaswi Neerkaje, Jean Kaddour, Abhishek Kumar, sujay sanghavi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=IA8CWtNkUr)<br/>
**arXiv:** [2306.03241](https://arxiv.org/abs/2306.03241)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2306.03241](https://huggingface.co/papers/2306.03241)<br/>

---

## Chain-of-Symbol Prompting For Spatial Reasoning in Large Language Models<br/>
**Authors:** Hanxu Hu, Hongyuan Lu, Huajian Zhang, Yun-Ze Song, Wai Lam, Yue Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Hvq9RtSoHG)<br/>

---

## [What is in Your Safe Data? Identifying Benign Data that Breaks Safety](https://arxiv.org/abs/2404.01099)<br/>
**Authors:** Luxi He, Mengzhou Xia, Peter Henderson<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Hi8jKh4HE9)<br/>
**arXiv:** [2404.01099](https://arxiv.org/abs/2404.01099)<br/>

---

## [TriForce: Lossless Acceleration of Long Sequence Generation with Hierarchical Speculative Decoding](https://huggingface.co/papers/2404.11912)<br/>
**Authors:** Hanshi Sun, Zhuoming Chen, Xinyu Yang, Yuandong Tian, Beidi Chen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=HVK6nl3i97)<br/>
**arXiv:** [2404.11912](https://arxiv.org/abs/2404.11912)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.11912](https://huggingface.co/papers/2404.11912)<br/>

---

## Elephants Never Forget: Memorization and Learning of Tabular Data in Large Language Models<br/>
**Authors:** Sebastian Bordt, Harsha Nori, Vanessa Cristiny Rodrigues Vasconcelos, Besmira Nushi, Rich Caruana<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=HLoWN6m4fS)<br/>

---

## [Reverse Training to Nurse the Reversal Curse](https://huggingface.co/papers/2403.13799)<br/>
**Authors:** Olga Golovneva, Zeyuan Allen-Zhu, Jason E Weston, Sainbayar Sukhbaatar<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=HDkNbfLQgu)<br/>
**arXiv:** [2403.13799](https://arxiv.org/abs/2403.13799)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.13799](https://huggingface.co/papers/2403.13799)<br/>

---

## LLM4Causal: Democratized Causal Tools for Everyone via Large Language Model<br/>
**Authors:** Haitao Jiang, Lin Ge, Yuhe Gao, Jianian Wang, Rui Song<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=H1Edd5d2JP)<br/>

---

## Starling-7B: Improving Helpfulness and Harmlessness with RLAIF<br/>
**Authors:** Banghua Zhu, Evan Frick, Tianhao Wu, Hanlin Zhu, Karthik Ganesan, Wei-Lin Chiang, Jian Zhang, Jiantao Jiao<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=GqDntYTTbk)<br/>

---

## RAVEN: In-Context Learning with Retrieval-Augmented Encoder-Decoder Language Models<br/>
**Authors:** Jie Huang, Wei Ping, Peng Xu, Mohammad Shoeybi, Kevin Chang, Bryan Catanzaro<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=GMalvQu0XL)<br/>

---

## JailBreakV: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks<br/>
**Authors:** Weidi Luo, Siyuan Ma, Xiaogeng Liu, Xiaoyu Guo, Chaowei Xiao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=GC4mXVfquq)<br/>

---

## [A Long Way to Go: Investigating Length Correlations in RLHF](https://huggingface.co/papers/2310.03716)<br/>
**Authors:** Prasann Singhal, Tanya Goyal, Jiacheng Xu, Greg Durrett<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=G8LaO1P0xv)<br/>
**arXiv:** [2310.03716](https://arxiv.org/abs/2310.03716)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2310.03716](https://huggingface.co/papers/2310.03716)<br/>

---

## [Counting Like Transformers: Compiling Temporal Counting Logic Into Softmax Transformers](https://arxiv.org/abs/2404.04393)<br/>
**Authors:** Andy Yang, David Chiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=FmhPg4UJ9K)<br/>
**arXiv:** [2404.04393](https://arxiv.org/abs/2404.04393)<br/>

---

## CoLLEGe: Concept Embedding Generation for Large Language Models<br/>
**Authors:** Ryan Teehan, Brenden Lake, Mengye Ren<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Fkr1yVUb9G)<br/>

---

## [CoCA: Regaining Safety-awareness of Multimodal Large Language Models with Constitutional Calibration](https://arxiv.org/abs/2409.11365)<br/>
**Authors:** Jiahui Gao, Renjie Pi, Tianyang Han, Han Wu, Lanqing HONG, Lingpeng Kong, Xin Jiang, Zhenguo Li<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=FgHpT6u7pk)<br/>
**arXiv:** [2409.11365](https://arxiv.org/abs/2409.11365)<br/>

---

## [Hydra: Sequentially-Dependent Draft Heads for Medusa Decoding](https://huggingface.co/papers/2402.05109)<br/>
**Authors:** Zachary Ankner, Rishab Parthasarathy, Aniruddha Nrusimha, Christopher Rinard, Jonathan Ragan-Kelley, William Brandon<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=FbhjirzvJG)<br/>
**arXiv:** [2402.05109](https://arxiv.org/abs/2402.05109)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2402.05109](https://huggingface.co/papers/2402.05109)<br/>

---

## Model Autophagy Analysis to Explicate Self-consumption within Human-AI Interactions<br/>
**Authors:** Shu Yang, Muhammad Asif Ali, Lu Yu, Lijie Hu, Di Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=FX4fUThO9H)<br/>

---

## [EnvGen: Generating and Adapting Environments via LLMs for Training Embodied Agents](https://huggingface.co/papers/2403.12014)<br/>
**Authors:** Abhay Zala, Jaemin Cho, Han Lin, Jaehong Yoon, Mohit Bansal<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=F9tqgOPXH5)<br/>
**arXiv:** [2403.12014](https://arxiv.org/abs/2403.12014)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.12014](https://huggingface.co/papers/2403.12014)<br/>

---

## [Massive Activations in Large Language Models](https://arxiv.org/abs/2402.17762)<br/>
**Authors:** Mingjie Sun, Xinlei Chen, J Zico Kolter, Zhuang Liu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=F7aAhfitX6)<br/>
**arXiv:** [2402.17762](https://arxiv.org/abs/2402.17762)<br/>

---

## Suspicion Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4<br/>
**Authors:** Jiaxian Guo, Bo Yang, Paul Yoo, Bill Yuchen Lin, Yusuke Iwasawa, Yutaka Matsuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=F2yGbwXJAi)<br/>

---

## Evaluating the Adversarial Robustness of Retrieval-Based In-Context Learning for Large Language Models<br/>
**Authors:** Simon Chi Lok Yu, Jie He, Pasquale Minervini, Jeff Z. Pan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Ecgev5ZZpq)<br/>

---

## StructLM: Towards Building Generalist Models for Structured Knowledge Grounding<br/>
**Authors:** Alex Zhuang, Ge Zhang, Tianyu Zheng, Xinrun Du, Junjie Wang, Weiming Ren, Wenhao Huang, Jie Fu, Xiang Yue, Wenhu Chen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=EKBPn7no4y)<br/>

---

## [D2PO: Discriminator-Guided DPO with Response Evaluation Models](https://huggingface.co/papers/2405.01511)<br/>
**Authors:** Prasann Singhal, Nathan Lambert, Scott Niekum, Tanya Goyal, Greg Durrett<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=EIjJ6ykPnh)<br/>
**arXiv:** [2405.01511](https://arxiv.org/abs/2405.01511)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2405.01511](https://huggingface.co/papers/2405.01511)<br/>

---

## Tower: An Open Multilingual Large Language Model for Translation-Related Tasks<br/>
**Authors:** Duarte Miguel Alves, José Pombal, Nuno M Guerreiro, Pedro Henrique Martins, João Alves, Amin Farajian, Ben Peters, Ricardo Rei, Patrick Fernandes, Sweta Agrawal, Pierre Colombo, José G. C. de Souza, Andre Martins<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=EHPns3hVkj)<br/>

---

## Ferret-v2: An Improved Baseline for Referring and Grounding with Large Language Models<br/>
**Authors:** Haotian Zhang, Haoxuan You, Philipp Dufter, Bowen Zhang, Chen Chen, Hong-You Chen, Tsu-Jui Fu, William Yang Wang, Shih-Fu Chang, Zhe Gan, Yinfei Yang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=EEPBOB2Xww)<br/>

---

## Self-Guide: Better Task-Specific Instruction Following via Self-Synthetic Finetuning<br/>
**Authors:** Chenyang Zhao, Xueying Jia, Vijay Viswanathan, Graham Neubig, Tongshuang Wu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Dt6qXZsgaU)<br/>

---

## 3M-Diffusion: Latent Multi-Modal Diffusion for Language-Guided Molecular Structure Generation<br/>
**Authors:** Huaisheng Zhu, Teng Xiao, Vasant G Honavar<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=DomBynQsqt)<br/>

---

## [CULTURE-GEN: Revealing Global Cultural Perception in Language Models through Natural Language Prompting](https://arxiv.org/abs/2404.10199)<br/>
**Authors:** Huihan Li, Liwei Jiang, Nouha Dziri, Xiang Ren, Yejin Choi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=DbsLm2KAqP)<br/>
**arXiv:** [2404.10199](https://arxiv.org/abs/2404.10199)<br/>

---

## [LITE: Modeling Environmental Ecosystems with Multimodal Large Language Models](https://arxiv.org/abs/2404.01165)<br/>
**Authors:** Haoran Li, Junqi Liu, Zexian Wang, Shiyuan Luo, Xiaowei Jia, Huaxiu Yao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=DRffhKBVlE)<br/>
**arXiv:** [2404.01165](https://arxiv.org/abs/2404.01165)<br/>

---

## CTIKG: LLM-Powered Knowledge Graph Construction from Cyber Threat Intelligence<br/>
**Authors:** Liangyi Huang, Xusheng Xiao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=DOMP5AgwQz)<br/>

---

## Enhancing Adversarial Robustness of LLMs with Analytic Hierarchy Process<br/>
**Authors:** Jiahao Zhao, Minzheng Wang, Nan Xu, YinLuo, Wenji Mao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=DMUGTMWrKZ)<br/>

---

## Can It Edit? Evaluating the Ability of Large Language Models to Follow Code Editing Instructions<br/>
**Authors:** Federico Cassano, Luisa Li, Akul Sethi, Noah Shinn, Abby Brennan-Jones, Jacob Ginesin, Edward Berman, George Chakhnashvili, Anton Lozhkov, Carolyn Jane Anderson, Arjun Guha<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=D06yk3DBas)<br/>

---

## Length-Controlled AlpacaEval: A Simple Debiasing of Automatic Evaluators<br/>
**Authors:** Yann Dubois, Percy Liang, Tatsunori Hashimoto<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=CybBmzWBX0)<br/>

---

## [STaR-GATE: Teaching Language Models to Ask Clarifying Questions](https://huggingface.co/papers/2403.19154)<br/>
**Authors:** Chinmaya Andukuri, Jan-Philipp Fränken, Tobias Gerstenberg, Noah Goodman<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=CrzAj0kZjR)<br/>
**arXiv:** [2403.19154](https://arxiv.org/abs/2403.19154)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.19154](https://huggingface.co/papers/2403.19154)<br/>
**🤗 Models:** [scandukuri/mistral-stargate](https://huggingface.co/scandukuri/mistral-stargate), [scandukuri/mistral-stargate-m1](https://huggingface.co/scandukuri/mistral-stargate-m1), [scandukuri/llama3-8b-stargate-m1](https://huggingface.co/scandukuri/llama3-8b-stargate-m1), [RichardErkhov/scandukuri_-_llama3-8b-stargate-m1-gguf](https://huggingface.co/RichardErkhov/scandukuri_-_llama3-8b-stargate-m1-gguf)<br/>

---

## [Should We Attend More or Less? Modulating Attention for Fairness](https://arxiv.org/abs/2305.13088)<br/>
**Authors:** Abdelrahman Zayed, Goncalo Mordido, Samira Shabanian, Sarath Chandar<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=CI7D2kiih1)<br/>
**arXiv:** [2305.13088](https://arxiv.org/abs/2305.13088)<br/>

---

## On Robustness-Accuracy Characterization of Language Models using Synthetic Datasets<br/>
**Authors:** Ching-Yun Ko, Pin-Yu Chen, Payel Das, Yung-Sung Chuang, Luca Daniel<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=C0j44uRPcl)<br/>

---

## Handling Open-Vocabulary Constructs in Formalizing Specifications: Retrieval Augmented Parsing with Expert Knowledge<br/>
**Authors:** Mohammad Saqib Hasan, Sayontan Ghosh, Dhruv Verma, Geoff Kuenning, Erez Zadok, Scott Smolka, Niranjan Balasubramanian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=BgvgMxY8s5)<br/>

---

## Do Language Models Plan Ahead for Future Tokens?<br/>
**Authors:** Wilson Wu, John Xavier Morris, Lionel Levine<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=BaOAvPUyBO)<br/>

---

## Automata-based constraints for language model decoding<br/>
**Authors:** Terry Koo, Frederick Liu, Luheng He<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=BDBdblmyzY)<br/>

---

## AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversations<br/>
**Authors:** Qingyun Wu, Gagan Bansal, Jieyu Zhang, Yiran Wu, Beibin Li, Erkang Zhu, Li Jiang, Xiaoyun Zhang, Shaokun Zhang, Jiale Liu, Ahmed Hassan Awadallah, Ryen W White, Doug Burger, Chi Wang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=BAakY1hNKS)<br/>

---

## [TOFU: A Task of Fictitious Unlearning for LLMs](https://huggingface.co/papers/2401.06121)<br/>
**Authors:** Pratyush Maini, Zhili Feng, Avi Schwarzschild, Zachary Chase Lipton, J Zico Kolter<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=B41hNBoWLo)<br/>
**arXiv:** [2401.06121](https://arxiv.org/abs/2401.06121)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2401.06121](https://huggingface.co/papers/2401.06121)<br/>
**🤗 Models:** [locuslab/tofu_ft_phi-1.5](https://huggingface.co/locuslab/tofu_ft_phi-1.5), [locuslab/tofu_ft_llama2-7b](https://huggingface.co/locuslab/tofu_ft_llama2-7b), [RichardErkhov/locuslab_-_tofu_ft_llama2-7b-4bits](https://huggingface.co/RichardErkhov/locuslab_-_tofu_ft_llama2-7b-4bits), [RichardErkhov/locuslab_-_tofu_ft_llama2-7b-8bits](https://huggingface.co/RichardErkhov/locuslab_-_tofu_ft_llama2-7b-8bits)<br/>
**🤗 Datasets:** [locuslab/TOFU](https://huggingface.co/datasets/locuslab/TOFU), [LZ12DH/unlearning](https://huggingface.co/datasets/LZ12DH/unlearning), [kimperyang/TOFU-C](https://huggingface.co/datasets/kimperyang/TOFU-C), [an1118/TOFU-C](https://huggingface.co/datasets/an1118/TOFU-C), [an1118/TOFU-Cf](https://huggingface.co/datasets/an1118/TOFU-Cf), [an1118/TOFU-Cr](https://huggingface.co/datasets/an1118/TOFU-Cr), [kimperyang/TOFUCr1](https://huggingface.co/datasets/kimperyang/TOFUCr1), [kimperyang/TOFUCrP](https://huggingface.co/datasets/kimperyang/TOFUCrP), [kimperyang/TOFU-C-Shuffle](https://huggingface.co/datasets/kimperyang/TOFU-C-Shuffle), [Gyikoo/TOFU-C-single](https://huggingface.co/datasets/Gyikoo/TOFU-C-single), [an1118/TOFU-Cbin](https://huggingface.co/datasets/an1118/TOFU-Cbin), [kimperyang/TOFU-C-Direct](https://huggingface.co/datasets/kimperyang/TOFU-C-Direct), [Gyikoo/TOFU-C-All](https://huggingface.co/datasets/Gyikoo/TOFU-C-All), [an1118/TOFU-C-All](https://huggingface.co/datasets/an1118/TOFU-C-All)<br/>
**🤗 Spaces:** [locuslab/tofu_leaderboard](https://huggingface.co/spaces/locuslab/tofu_leaderboard)<br/>

---

## SynerGPT: In-Context Learning for Personalized Drug Synergy Prediction and Drug Design<br/>
**Authors:** Carl Edwards, Aakanksha Naik, Tushar Khot, Martin D. Burke, Heng Ji, Tom Hope<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=Aaz6R4Tlwv)<br/>

---

## [Inspecting and Editing Knowledge Representations in Language Models](https://huggingface.co/papers/2304.00740)<br/>
**Authors:** Evan Hernandez, Belinda Z. Li, Jacob Andreas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=ADtL6fgNRv)<br/>
**arXiv:** [2304.00740](https://arxiv.org/abs/2304.00740)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2304.00740](https://huggingface.co/papers/2304.00740)<br/>

---

## [Aligning with Human Judgement: The Role of Pairwise Preference in Large Language Model Evaluators](https://huggingface.co/papers/2403.16950)<br/>
**Authors:** Yinhong Liu, Han Zhou, Zhijiang Guo, Ehsan Shareghi, Ivan Vulić, Anna Korhonen, Nigel Collier<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=9gdZI7c6yr)<br/>
**arXiv:** [2403.16950](https://arxiv.org/abs/2403.16950)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.16950](https://huggingface.co/papers/2403.16950)<br/>

---

## [CHOPS: CHat with custOmer Profile Systems for Customer Service with LLMs](https://arxiv.org/abs/2404.01343)<br/>
**Authors:** Jingzhe Shi, Jialuo Li, Qinwei Ma, Zaiwen Yang, Huan Ma, Lei Li<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=9Wmdk94oKF)<br/>
**arXiv:** [2404.01343](https://arxiv.org/abs/2404.01343)<br/>

---

## [Forcing Diffuse Distributions out of Language Models](https://arxiv.org/abs/2404.10859)<br/>
**Authors:** Yiming Zhang, Avi Schwarzschild, Nicholas Carlini, J Zico Kolter, Daphne Ippolito<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=9JY1QLVFPZ)<br/>
**arXiv:** [2404.10859](https://arxiv.org/abs/2404.10859)<br/>

---

## [Certifying LLM Safety against Adversarial Prompting](https://huggingface.co/papers/2309.02705)<br/>
**Authors:** Aounon Kumar, Chirag Agarwal, Suraj Srinivas, Aaron Jiaxun Li, Soheil Feizi, Himabindu Lakkaraju<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=9Ik05cycLq)<br/>
**arXiv:** [2309.02705](https://arxiv.org/abs/2309.02705)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2309.02705](https://huggingface.co/papers/2309.02705)<br/>
**🤗 Spaces:** [TrustSafeAI/GradientCuff-Jailbreak-Defense](https://huggingface.co/spaces/TrustSafeAI/GradientCuff-Jailbreak-Defense)<br/>

---

## [Latent Causal Probing: A Formal Perspective on Probing with Causal Models of Data](https://arxiv.org/abs/2407.13765)<br/>
**Authors:** Charles Jin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=98ekcwQqb7)<br/>
**arXiv:** [2407.13765](https://arxiv.org/abs/2407.13765)<br/>

---

## TMMLU+: An Improved Traditional Chinese Evaluation Suite for Foundation Models<br/>
**Authors:** Zhi Rui Tam, Ya Ting Pai, Yen-Wei Lee, Hong-Han Shuai, Jun-Da Chen, Wei Min Chu, Sega Cheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=95TayIeqJ4)<br/>

---

## BumbleBee: Dynamic KV-Cache Streaming Submodular Summarization for Infinite-Context Transformers<br/>
**Authors:** Lilly Kumari, Shengjie Wang, Tianyi Zhou, Nikhil Sarda, Anthony Rowe, Jeff Bilmes<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=8w0RApM5yG)<br/>

---

## Keep the Cost Down: A Review on Methods to Optimize LLM’s KV-Cache Consumption<br/>
**Authors:** Shi Luohe, Hongyi Zhang, Yao Yao, Zuchao Li, hai zhao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=8tKjqqMM5z)<br/>

---

## [PAPERCLIP: Associating Astronomical Observations and Natural Language with Multi-Modal Models](https://arxiv.org/abs/2403.08851)<br/>
**Authors:** Siddharth Mishra-Sharma, YIDING SONG, Jesse Thaler<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=8TdcXwfNRB)<br/>
**arXiv:** [2403.08851](https://arxiv.org/abs/2403.08851)<br/>

---

## IllusionVQA: A Challenging Optical Illusion Dataset for Vision Language Models<br/>
**Authors:** Haz Sameen Shahgir, Khondker Salman Sayeed, Abhik Bhattacharjee, Wasi Uddin Ahmad, Yue Dong, Rifat Shahriyar<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=7ysaJGs7zY)<br/>

---

## Yes, no, maybe? Revisiting language models' response stability under paraphrasing for the assessment of political leaning<br/>
**Authors:** Patrick Haller, Jannis Vamvas, Lena Ann Jäger<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=7xUtka9ck9)<br/>

---

## [Measuring Taiwanese Mandarin Language Understanding](https://huggingface.co/papers/2403.20180)<br/>
**Authors:** Po-Heng Chen, Sijia Cheng, Wei-Lin Chen, Yen-Ting Lin, Yun-Nung Chen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=7jSMMvXLri)<br/>
**arXiv:** [2403.20180](https://arxiv.org/abs/2403.20180)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.20180](https://huggingface.co/papers/2403.20180)<br/>
**🤗 Models:** [yentinglin/Llama-3-Taiwan-70B-Instruct](https://huggingface.co/yentinglin/Llama-3-Taiwan-70B-Instruct), [yentinglin/Llama-3-Taiwan-8B-Instruct](https://huggingface.co/yentinglin/Llama-3-Taiwan-8B-Instruct), [yentinglin/Llama-3-Taiwan-8B-Instruct-128k](https://huggingface.co/yentinglin/Llama-3-Taiwan-8B-Instruct-128k), [yentinglin/Llama-3-Taiwan-70B-Instruct-DPO](https://huggingface.co/yentinglin/Llama-3-Taiwan-70B-Instruct-DPO), [yentinglin/Llama-3-Taiwan-70B-Instruct-128k](https://huggingface.co/yentinglin/Llama-3-Taiwan-70B-Instruct-128k), [chienweichang/Llama-3-Taiwan-8B-Instruct-128k-GGUF](https://huggingface.co/chienweichang/Llama-3-Taiwan-8B-Instruct-128k-GGUF), [chienweichang/Llama-3-Taiwan-70B-Instruct-GGUF](https://huggingface.co/chienweichang/Llama-3-Taiwan-70B-Instruct-GGUF), [nihaomur/Llama-3-Taiwan-8B-Instruct-AWQ-4bit](https://huggingface.co/nihaomur/Llama-3-Taiwan-8B-Instruct-AWQ-4bit), [yentinglin/Llama-3-Taiwan-8B-Instruct-DPO](https://huggingface.co/yentinglin/Llama-3-Taiwan-8B-Instruct-DPO), [chienweichang/Llama-3-Taiwan-8B-Instruct-DPO-GGUF](https://huggingface.co/chienweichang/Llama-3-Taiwan-8B-Instruct-DPO-GGUF), [chienweichang/Llama-3-Taiwan-8B-Instruct-GGUF](https://huggingface.co/chienweichang/Llama-3-Taiwan-8B-Instruct-GGUF), [RichardErkhov/yentinglin_-_Llama-3-Taiwan-8B-Instruct-gguf](https://huggingface.co/RichardErkhov/yentinglin_-_Llama-3-Taiwan-8B-Instruct-gguf), [pigfoot/Llama-3-Taiwan-8B-Instruct-V1-5bpw-exl2](https://huggingface.co/pigfoot/Llama-3-Taiwan-8B-Instruct-V1-5bpw-exl2)<br/>
**🤗 Spaces:** [yentinglin/Taiwan-LLaMa2](https://huggingface.co/spaces/yentinglin/Taiwan-LLaMa2), [Chiuzu/yentinglin-Llama-3-Taiwan-70B-Instruct](https://huggingface.co/spaces/Chiuzu/yentinglin-Llama-3-Taiwan-70B-Instruct), [kevindomo/yentinglin-Llama-3-Taiwan-70B-Instruct](https://huggingface.co/spaces/kevindomo/yentinglin-Llama-3-Taiwan-70B-Instruct), [kevindomo/yentinglin-Llama-3-Taiwan-70B-Instruct-DPO](https://huggingface.co/spaces/kevindomo/yentinglin-Llama-3-Taiwan-70B-Instruct-DPO), [rubengtsui/yentinglin-Llama-3-Taiwan-8B-Instruct](https://huggingface.co/spaces/rubengtsui/yentinglin-Llama-3-Taiwan-8B-Instruct), [chienweichang/lmdeploy](https://huggingface.co/spaces/chienweichang/lmdeploy)<br/>

---

## Pairwise Proximal Policy Optimization: Language Model Alignment with Comparative RL<br/>
**Authors:** Tianhao Wu, Banghua Zhu, Ruoyu Zhang, Zhaojin Wen, Kannan Ramchandran, Jiantao Jiao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=7iaAlIlV2H)<br/>

---

## [Beyond Relevance: Evaluate and Improve Retrievers on Perspective Awareness](https://arxiv.org/abs/2405.02714)<br/>
**Authors:** Xinran Zhao, Tong Chen, Sihao Chen, Hongming Zhang, Tongshuang Wu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=7VPKtz8CHN)<br/>
**arXiv:** [2405.02714](https://arxiv.org/abs/2405.02714)<br/>

---

## Poly-Visual-Expert Vision-Language Models<br/>
**Authors:** Xiaoran Fan, Tao Ji, 江常皓, Shuo Li, Senjie Jin, Sirui Song, Junke Wang, Boyang Hong, Lu Chen, Guodong Zheng, Ming Zhang, Huangcaishuang, Rui Zheng, Zhiheng Xi, Yuhao Zhou, Shihan Dou, Junjie Ye, Hang Yan, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang, Zuxuan Wu, Yu-Gang Jiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=7QaEO9WYMa)<br/>

---

## [Corex: Pushing the Boundaries of Complex Reasoning through Multi-Model Collaboration](https://huggingface.co/papers/2310.00280)<br/>
**Authors:** Qiushi Sun, Zhangyue Yin, Xiang Li, Zhiyong Wu, Xipeng Qiu, Lingpeng Kong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=7BCmIWVT0V)<br/>
**arXiv:** [2310.00280](https://arxiv.org/abs/2310.00280)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2310.00280](https://huggingface.co/papers/2310.00280)<br/>

---

## [MANGO: A Benchmark for Evaluating Mapping and Navigation Abilities of Large Language Models](https://arxiv.org/abs/2403.19913)<br/>
**Authors:** Peng Ding, Jiading Fang, Peng Li, Kangrui Wang, Xiaochen Zhou, Mo Yu, Jing Li, Hongyuan Mei, Matthew Walter<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=6vEfyp0o68)<br/>
**arXiv:** [2403.19913](https://arxiv.org/abs/2403.19913)<br/>

---

## [ExoViP: Step-by-step Verification and Exploration with Exoskeleton Modules for Compositional Visual Reasoning](https://huggingface.co/papers/2408.02210)<br/>
**Authors:** Yuxuan Wang, Alan Yuille, Zhuowan Li, Zilong Zheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=6U1FEKP7Ar)<br/>
**arXiv:** [2408.02210](https://arxiv.org/abs/2408.02210)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2408.02210](https://huggingface.co/papers/2408.02210)<br/>

---

## [Measuring and Controlling Instruction (In)Stability in Language Model Dialogs](https://huggingface.co/papers/2402.10962)<br/>
**Authors:** Kenneth Li, Tianle Liu, Naomi Bashkansky, David Bau, Fernanda Viégas, Hanspeter Pfister, Martin Wattenberg<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=60a1SAtH4e)<br/>
**arXiv:** [2402.10962](https://arxiv.org/abs/2402.10962)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2402.10962](https://huggingface.co/papers/2402.10962)<br/>
**🤗 Datasets:** [Naomibas/llm-system-prompts-benchmark](https://huggingface.co/datasets/Naomibas/llm-system-prompts-benchmark)<br/>

---

## [Helping or Herding? Reward Model Ensembles Mitigate but do not Eliminate Reward Hacking](https://huggingface.co/papers/2312.09244)<br/>
**Authors:** Jacob Eisenstein, Chirag Nagpal, Alekh Agarwal, Ahmad Beirami, Alexander Nicholas D'Amour, Krishnamurthy Dj Dvijotham, Adam Fisch, Katherine A Heller, Stephen Robert Pfohl, Deepak Ramachandran, Peter Shaw, Jonathan Berant<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=5u1GpUkKtG)<br/>
**arXiv:** [2312.09244](https://arxiv.org/abs/2312.09244)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2312.09244](https://huggingface.co/papers/2312.09244)<br/>
**🤗 Datasets:** [taesiri/arxiv_qa](https://huggingface.co/datasets/taesiri/arxiv_qa)<br/>

---

## [SteP: Stacked LLM Policies for Web Actions](https://huggingface.co/papers/2310.03720)<br/>
**Authors:** Paloma Sodhi, S.R.K Branavan, Yoav Artzi, Ryan McDonald<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=5fg0VtRxgi)<br/>
**arXiv:** [2310.03720](https://arxiv.org/abs/2310.03720)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2310.03720](https://huggingface.co/papers/2310.03720)<br/>

---

## LLM-Datasets: An Open Framework for Pretraining Datasets of Large Language Models<br/>
**Authors:** Malte Ostendorff, Pedro Ortiz Suarez, Lucas Fonseca Lage, Georg Rehm<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=5RdIMlGLXL)<br/>

---

## [Pack of LLMs: Model Fusion at Test-Time via Perplexity Optimization](https://arxiv.org/abs/2404.11531)<br/>
**Authors:** Costas Mavromatis, Petros Karypis, George Karypis<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=5Nsl0nlStc)<br/>
**arXiv:** [2404.11531](https://arxiv.org/abs/2404.11531)<br/>

---

## [Exploiting the Potential of Seq2Seq Models as Robust Few-Shot Learners](https://arxiv.org/abs/2307.14856)<br/>
**Authors:** Jihyeon Lee, Dain Kim, Doohae Jung, Boseop Kim, Kyoung-Woon On<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=5Evv4tIjUI)<br/>
**arXiv:** [2307.14856](https://arxiv.org/abs/2307.14856)<br/>

---

## [Is Model Collapse Inevitable? Breaking the Curse of Recursion by Accumulating Real and Synthetic Data](https://huggingface.co/papers/2404.01413)<br/>
**Authors:** Matthias Gerstgrasser, Rylan Schaeffer, Apratim Dey, Rafael Rafailov, Tomasz Korbak, Henry Sleight, Rajashree Agrawal, John Hughes, Dhruv Bhandarkar Pai, Andrey Gromov, Dan Roberts, Diyi Yang, David L. Donoho, Sanmi Koyejo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=5B2K4LRgmz)<br/>
**arXiv:** [2404.01413](https://arxiv.org/abs/2404.01413)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.01413](https://huggingface.co/papers/2404.01413)<br/>

---

## Prompt-prompted Adaptive Structured Pruning for Efficient LLM Generation<br/>
**Authors:** Harry Dong, Beidi Chen, Yuejie Chi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=4aqq9xTtih)<br/>

---

## [WorkBench: a Benchmark Dataset for Agents in a Realistic Workplace Setting](https://arxiv.org/abs/2405.00823)<br/>
**Authors:** Olly Styles, Sam Miller, Patricio Cerda-Mardini, Tanaya Guha, Victor Sanchez, Bertie Vidgen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=4HNAwZFDcH)<br/>
**arXiv:** [2405.00823](https://arxiv.org/abs/2405.00823)<br/>

---

## Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation<br/>
**Authors:** Eric Zelikman, Eliana Lorch, Lester Mackey, Adam Tauman Kalai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=46Zgqo4QIU)<br/>

---

## [Cohesive Conversations: Enhancing Authenticity in Multi-Agent Simulated Dialogues](https://arxiv.org/abs/2407.09897)<br/>
**Authors:** KuanChao Chu, Yi-Pei Chen, Hideki Nakayama<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=3ypWPhMGhV)<br/>
**arXiv:** [2407.09897](https://arxiv.org/abs/2407.09897)<br/>

---

## StateFlow: Enhancing LLM Task-Solving through State-Driven Workflows<br/>
**Authors:** Yiran Wu, Tianwei Yue, Shaokun Zhang, Chi Wang, Qingyun Wu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=3nTbuygoop)<br/>

---

## MiniCPM: Unveiling the Potential of Small Language Models with Scalable Training Strategies<br/>
**Authors:** Shengding Hu, Yuge Tu, Xu Han, Ganqu Cui, Chaoqun He, Weilin Zhao, Xiang Long, Zhi Zheng, Yewei Fang, Yuxiang Huang, Xinrong Zhang, Zhen Leng Thai, Chongyi Wang, Yuan Yao, Chenyang Zhao, Jie Zhou, Jie Cai, Zhongwu Zhai, Ning Ding, Chao Jia, Guoyang Zeng, dahai li, Zhiyuan Liu, Maosong Sun<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=3X2L2TFr0f)<br/>

---

## Timo: Towards Better Temporal Reasoning for Language Models<br/>
**Authors:** Zhaochen Su, Jun Zhang, Tong Zhu, Xiaoye Qu, Juntao Li, Min zhang, Yu Cheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=3TzGD95Jw1)<br/>

---

## [Bot or Human? Detecting ChatGPT Imposters with A Single Question](https://huggingface.co/papers/2305.06424)<br/>
**Authors:** Hong Wang, Xuan Luo, Weizhi Wang, Melody Yu, Xifeng Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=3HTVP34WWE)<br/>
**arXiv:** [2305.06424](https://arxiv.org/abs/2305.06424)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2305.06424](https://huggingface.co/papers/2305.06424)<br/>

---

## [Will the Real Linda Please Stand up...to Large Language Models? Examining the Representativeness Heuristic in LLMs](https://arxiv.org/abs/2404.01461)<br/>
**Authors:** Pengda Wang, Zilin Xiao, Hanjie Chen, Frederick L. Oswald<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=3GhOWfSLrD)<br/>
**arXiv:** [2404.01461](https://arxiv.org/abs/2404.01461)<br/>

---

## Enhancing Language Models with Idiomatic Reasoning<br/>
**Authors:** Jianing Zhou, Ziheng Zeng, Hongyu Gong, Suma Bhat<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=2wtj0up8rv)<br/>

---

## ACORN: Aspect-wise Commonsense Reasoning Explanation Evaluation<br/>
**Authors:** Ana Brassard, Benjamin Heinzerling, Keito Kudo, Keisuke Sakaguchi, Kentaro Inui<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=2oHnsM9M9D)<br/>

---

## ProLLM: Protein Chain-of-Thoughts Enhanced LLM for Protein-Protein Interaction Prediction<br/>
**Authors:** Mingyu Jin, Haochen Xue, Zhenting Wang, Boming Kang, Ruosong Ye, Kaixiong Zhou, Mengnan Du, Yongfeng Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=2nTzomzjjb)<br/>

---

## Stream of Search (SoS): Learning to Search in Language<br/>
**Authors:** Kanishk Gandhi, Denise H J Lee, Gabriel Grand, Muxin Liu, Winson Cheng, Archit Sharma, Noah Goodman<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=2cop2jmQVL)<br/>

---

## [Risks from Language Models for Automated Mental Healthcare: Ethics and Structure for Implementation](https://arxiv.org/abs/2406.11852)<br/>
**Authors:** Declan Grabb, Max Lamparth, Nina Vasan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=1pgfvZj0Rx)<br/>
**arXiv:** [2406.11852](https://arxiv.org/abs/2406.11852)<br/>

---

## [Prompt Public Large Language Models to Synthesize Data for Private On-device Applications](https://arxiv.org/abs/2404.04360)<br/>
**Authors:** Shanshan Wu, Zheng Xu, Yanxiang Zhang, Yuanbo Zhang, Daniel Ramage<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=1eg6UnpYu7)<br/>
**arXiv:** [2404.04360](https://arxiv.org/abs/2404.04360)<br/>

---

## Agent-DocEdit: Language-Instructed LLM Agent for Content-Rich Document Editing<br/>
**Authors:** Te-Lin Wu, Rajiv Jain, Yufan Zhou, Puneet Mathur, Vlad I Morariu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=1ba209BACA)<br/>

---

## From Strategic Narratives to Code-Like Cognitive Models: An LLM-Based Approach in A Sorting Task<br/>
**Authors:** Hanbo Xie, Hua-Dong Xiong, Robert Wilson<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=1Tny4KgGO2)<br/>

---

## [See What LLMs Cannot Answer: A Self-Challenge Framework for Uncovering LLM Weaknesses](https://arxiv.org/abs/2408.08978)<br/>
**Authors:** Yulong Chen, Yang Liu, Jianhao Yan, Xuefeng Bai, Ming Zhong, Yinghao Yang, Ziyi Yang, Chenguang Zhu, Yue Zhang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=18iNTRPx8c)<br/>
**arXiv:** [2408.08978](https://arxiv.org/abs/2408.08978)<br/>

---

## [SPEER: Sentence-Level Planning of Long Clinical Summaries via Embedded Entity Retrieval](https://arxiv.org/abs/2401.02369)<br/>
**Authors:** Griffin Thomas Adams, Jason Zucker, Noémie Elhadad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=0oiG1KigYN)<br/>
**arXiv:** [2401.02369](https://arxiv.org/abs/2401.02369)<br/>

---

## [Effective Prompt Extraction from Language Models](https://huggingface.co/papers/2307.06865)<br/>
**Authors:** Yiming Zhang, Nicholas Carlini, Daphne Ippolito<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=0o95CVdNuz)<br/>
**arXiv:** [2307.06865](https://arxiv.org/abs/2307.06865)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2307.06865](https://huggingface.co/papers/2307.06865)<br/>

---

## ReAct Meets ActRe: Autonomous Annotation of Agent Trajectories for Contrastive Self-Training<br/>
**Authors:** Zonghan Yang, Peng Li, Ming Yan, Ji Zhang, Fei Huang, Yang Liu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=0VLBwQGWpA)<br/>

---

## InstructAV: Instruction Fine-tuning Large Language Models for Authorship Verification<br/>
**Authors:** Yujia Hu, Zhiqiang Hu, Chun Wei Seah, Roy Ka-Wei Lee<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://openreview.net/forum?id=0UK8c2kg7c)<br/>

---
