# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Fall 2022

+ Team # 5
+ Project title:Machine Learning Fairness
	+ Ying Gao
	+ Xiaoyuan Ge
	+ Christopher Halim
	+ Dhruv Limaye
	+ Zhejing Shi
	
+ Project summary: Supervised learning uses historical data to infer a relation between an instance and its label. However, historical data might contains distriminatory relations. If we directly use those data to train our classifiers, the model predictions will also be biased. Thus, we explored 2 major algorithms in the field of machine learning fairness, Maximizing accuracy under fairness constraints (A2) and Handling Conditional Discrimination (A6) . Under A6, 2 techniques, local massaging and local preferential sampling are applied, and we chose Calibritaion to be our evaluation metrics. Among all techniques, we believe local preferential sampling outputs the best results.
	
**Contribution statement**:  Ying Gao and Zhejing Shi were responsible for A6 (Handling Conditional Discrimination (LM and LPS)). Both Zhejing shi and Ying Gao helped with data cleaning for and build the base logistic regression model in A6. Ying read the paper and discussed with Zhejing on possible approchs the are different than the paper's . Zhejing wrote the codes implementing local massaging and local preferential sampling methods using pyhon, and present our work to the class. Christopher Halim and Dhruv Limaye took care of A2 (Maximizing accuracy under fairness constraints (C-SVM and C-LR)). Xiaoyuan Ge organized the GitHub repo. Zhejing Shi is the presenter. Everyone participated in the group meeting and helped prepare presentation slides. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
