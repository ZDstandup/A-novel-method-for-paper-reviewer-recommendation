# A-novel-method-for-paper-reviewer-recommendation
A novel method for paper-reviewer recommendation


This project is for a toy research, which is paper-reviewer recommendation. And we proposed a novel and simple method which transformed the recommendation problem into a classification issue. The paper can represented by the abstracts, titles, keywords. And the reviewer can represented by thier publications and thier profile. So we proposed a method named WMD-CCA.

--------------------------------------------------------------
A novel method for paper-reviewer recommendation

Reviewer recommendation problem in the research field usually refers to invite experts to comment on the quality of papers, proposals, etc. How to effectively and accurately recommend reviewers for the submitted papers and proposals is a meaningful and still tough task. At present, many unsupervised recommendation methods have been researched to solve this task. In this paper, a novel classification method named Word Mover’s Distance–Constructive Covering Algorithm (WMD–CCA, for short) is proposed to solve the reviewer recommendation problem as a classification issue. A submission or a reviewer is described by some tags, such as keywords, research interests, and so on. First, the submission or the reviewer is represented as some vectors by a word embedding method. That is to say, each tag describing a submission or a reviewer is represented as a vector. Second, the Word Mover’s Distance (WMD, for short) method is used to measure the minimum distances between submissions and reviewers. Actually, the papers usually have research field information, and utilizing them well might improve the reviewer recommendation accuracy. So finally, the reviewer recommendation task is transformed into a classification problem which is solved by a supervised learning method- Constructive Covering Algorithm (CCA, for short). Comparative experiments are conducted with 4 public datasets and a synthetic dataset from Baidu Scholar, which show that the proposed method WMD–CCA effectively solves the reviewer recommendation task as a classification issue and improves the recommendation accuracy.

---------------------------------------------------------------

In this project, we used WMD method to measure the research field relationship and then we applied the CCA (Constructive Covering Algorithm) to predict the related reviewer to review some papers.

The wmd method is a method which can compute the distance between documents and it was aften applied to text classification research. The related paper is here. http://proceedings.mlr.press/v37/kusnerb15.pdf

CCA is a constructive and fast machine learning algorithm, which always applied to classification and community detection. The related paper is here. http://www.wanfangdata.com.cn/details/detail.do?_type=perio&id=jsjxb200508006 http://www.jos.org.cn/1000-9825/18/2691.pdf

And the paper for this project is here. https://rd.springer.com/article/10.1007/s11192-018-2726-6#citeas
