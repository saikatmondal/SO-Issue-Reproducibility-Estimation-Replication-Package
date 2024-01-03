# Reproducibility of Issues Reported in Stack Overflow Questions: Challenges, Impact & Estimation

**Abstract:** Software developers often submit questions to technical Q\&A sites like Stack Overflow to resolve code-level problems. In practice, they include example code snippets with questions to explain the programming issues. Existing research suggests that users attempt to reproduce the reported issues using given code snippets while answering questions. Unfortunately, such code snippets could not always reproduce the issues due to several unmet challenges that prevent questions from receiving appropriate and prompt solutions. A previous study investigated the potential reproducibility challenges discussed in 400 Java questions. Their investigation produced a catalog of reproducibility challenges (e.g., too short code snippets). However, it is unknown how the practitioners (i.e., users of Stack Overflow) perceive the challenge catalog. Practitioners' perspective is inevitable to validate those challenges and estimate their severity. In this study, we thus first survey 53 practitioners to understand their perspectives on reproducibility challenges. 
In particular, we attempt to - (a) see practitioners' viewpoints on the agreement to those challenges, (b) find the potential impact of each of those challenges to answer questions, and (c) determine tool support needs to promote reproducibility. Survey results show that -- (a) about 90\% of the participants agree with the challenges, (b) "missing an important part of code" most severely hurt reproducibility, and (c) participants strongly recommend introducing automated tool support to promote reproducibility. Second, we extract nine code-based features (e.g., LOC, compilability) and build five machine learning models to predict issue reproducibility. Early detection might help users improve code snippets and their reproducibility. Our models can predict issue reproducibility with 84.5% precision, 83.0% recall, 82.8% F1-score & 82.8% overall accuracy, which are highly promising. We also confirm the strength and generalizability of our extracted features by predicting the reproducibility status of C# code snippets employing these features. Third, we explain how the code snippets with reproducible issues differ from those with irreproducible issues by systematically interpreting the machine learning model.


## Materials Included (JSS Dataset)

### Agreement analysis (RQ1) ### 

* For reproducibility status agreement: Please consider columns (from `Survey_Responses.csv`) 9 (for Q1), 23 (for Q2), 38 (for Q3) and 52 (for Q4).
* For reproducibility challenge agreement: Please consider columns (from `Survey_Responses.csv`) 10-11 (for Q1), 24-26 (for Q2), 39-40 (for Q3) and 53 (for Q4).


### Impact analysis (RQ2) ###

* Please consider columns (from `Survey_Responses.csv`) 65-71

### Prioritization analysis (RQ3) ###

* Please consider columns (from `Survey_Responses.csv`) 73-75

### Code editing actions (RQ4) ###

* Please consider columns (from `Survey_Responses.csv`) 13 (for Q1), 28 (for Q2), 42 (for Q3) and 55 (for Q4). We manually analyzed the modified code and reported the actions (please see the file `Code_Editing_Actions.xlsx` for the action labels). The blank entries
mean that the participants can reproduce the issues. We did not analyze those codes to answer RQ4.

### Tool design requirement analysis (RQ5) ###

* Please consider columns (from `Survey_Responses.csv`) 76-82.
