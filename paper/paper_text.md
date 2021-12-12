# Using Machine Learning to Address the Opioid Crisis

### Abstract

##### Required length: 250 words

- Is enough information provided to get a clear idea about the subject matter?
- Is the abstract conveying the findings?
- Are the main points of the report described succinctly?

TODO: explain our implementation, goal, results

### Introduction

Opioid addiction and overdose have become tragic and inescapable threads in the fabric of American daily life. Many Americans know someone who has died of a drug overdose, and even if they do not, headlines announcing high-profile overdose deaths are common news items. Among the hundreds of thousands of opioid related deaths in the past few years are celebrated musicians Prince, Mac Miller, and Tom Petty; accomplished athletes including pitcher Tyler Skaggs, football player Jake Ehlinger, and NHL player Jimmy Hayes; and lauded actors like Philip Seymore Hoffman.

Data also sheds insight into the scope of this epidemic. According to the United States Center for Disease Control, in 2019 more than 50,000 people in the United States died from opioid-related overdoses \cite{dataabuse.gov}. It is also estimated that 3 million Americans suffer from opioid use disorder, and in 2020, a staggering 93,000 people died in the United States from drug overdoses \cite{stobbe}, most of which were related to opioids. Additionally, studies estimate that the total "economic burden" of prescription opioid misuse in the United States is $78.5 billion a year, including the costs of healthcare, lost productivity, addiction treatment, and criminal justice involvement \cite{dataabuse.gov}. While the United States is certainly not the only country suffering from this epidemic, statistics like these make it clear that COVID-19 is not the only major medical crisis nations are struggling to contain at the moment.

Despite numerous studies related to opioid use, we feel there is ample room to take a “deep dive” into publicly-available data and see if we can draw useful conclusions to perhaps provide insight into qualming this crisis. We plan to focus US federal and state datasets to both take a broad look at the situation while also allowing us to delve deeper into more localized data to potentially find trends. More specifically, we hope to place more emphasis on examining the impact of opioid prescribers instead of focusing solely on opioid users, as has been done in other studies. To do this, will first test various machine learning models to try and create classifiers to predict the likelihood that a given doctor is a significant prescriber of opioids using a national dataset. We will then take that model and use it for analysis of a more local dataset -- specifically for the state of Connecticut -- to see if we can find relationships between prescribers who are classified as likely to prescribe opioids and the side effects of opioids, such as drug overdose and rehab data. Finally, we will look to see if other outside factors could be potentially affecting the rate of opioid prescriptions, specifically investigating if we can find a correlation between lobbying efforts of pro-drug interest groups to the amount of opioids prescribed in the region where they exert influence.

While we do have high hopes for this project, we acknowledge that we are tackling a tough issue that does not necessarily have a perfect answer which can be prescribed by a single machine learning algorithm; indeed, some data we’d like to ideally have for our analysis (such as a better insight into the prevalence of illegal opioids by geography) are simply not available. We also recognize that we have certain limitations geographically on our datasets, as our data is only focused only on the United States. However, we are confident that our exploratory analysis will shed some insights into the nature of this crisis worldwide.

### Related Work

There have been several research efforts centered around this topic, particularly in the fields of machine learning and data science, even within the realm of individual study. For example, both Tara Boyle's "The Opioid Crisis in Data" \cite{boyle2019:online} and Kiros Gebremariam's capstone project \cite{KirosGPr71:online} use machine learning for exploratory analyses of opioid prescription trends. In both Boyle and Gebremariam's works, their analyses of publicly-available federal datasets show that of all medical specialities, general practitioners in family practice and internal medicine prescribed the greatest number of opioids. Additionally, Hydrocodone/Vicodin was far and above the most commonly-prescribed opioid, with more than double the amount of units than the second most-common opioid, Tramadol/Ultram, for the year 2016.

The majority of scholarly research is focused around predicting one’s chances of opioid abuse disorder based on personal characteristics, as opposed to focusing on the prescribers themselves. Several studies, such as Huinker’s analysis \cite{huinkerpaper} go into more detail about possible machine learning algorithms which can be applied to predict the possibility of opioid abuse disorder. Huinkers' study uses four popular machine learning algorithms -- Decision Trees, Artificial Neural Networks, Support Vector Machines, and Logistic Regression -- and ultimately finds a SVM with k-fold cross-validation to be the superior model for predicting individual opioid misuse. Similarly, Lo-Ciganic W et al \cite{10.1001/jamanetworkopen.2019.0968} conclude that machine learning algorithms using administrative data appear to be a valuable and feasible tool for more accurate identification of opioid overdose risk.

Despite these insights, there has been several recent works which highlight potential issues with these models. Rather than try to develop models for opioid abuse indicators, Angela Kilby \cite{10.1145/3442188.3445891} investigates issues with such algorithmic methods currently being used in locales such as medical offices and police departments. Kilby's work, which uses several proprietary datasets, finds that machine-generated risk scores are a form of algorithmic unfairness in machine learning applications as they are heavily dependent on the researcher's choice of objective function, and as such are not reliable indicators of actual risk when deciding treatment. Indeed, critique of machine learning algorithms predicting one’s chances of opioid abuse is so prevalent that even mainstream journalistic sources cover the topic. For example, Szalavitz’s exposé in Wired \cite{wiredarticle:online} displays how such algorithms currently in use by doctors and drug companies have unfairly discriminated against patients with complex or chronic illnesses, histories of sexual abuse, and women.

### Proposed Method

##### Required length: 1 to 2 pages

- Are there any missing descriptions of symbols used in mathematical notations (if applicable)?
- Are the main algorithms described well enough so that they can be implemented by a knowledgeable reader?

TODO: Implement

### Experiments

##### Required length: 1/2 to 1 page

- Is the experimental setup and methodology described well enough so that it can be repeated?
- If datasets are used, are they referenced appropriately?
- Dataset details:
  - Link to the dataset is provided
  - Description of relevant statistics, such as the number of examples
  - Details of train/validation/test splits
  - Explanation if data was excluded; all pre-processing steps are described

TODO: Implement

### Results and Discussion

##### Required length: 2 to 3 pages

- Are the results described clearly?
- Is the data analyzed well, and are the results logical?
- Are the figures clear and have no missing labels?
- Do the figure captions have sufficient information to understand the figure?
- Is each figure referenced in the text?
- Is the discussion critical/honest, and are potential weaknesses/shortcomings are discussed as well?

TODO: Implement

### Conclusions

##### Required length: 1/3 to 1/2 page

- Do the authors describe whether the initial motivation/task was accomplished or not based on the results?
- Is it discussed adequately how the results relate to previous work?
- If applicable, are potential future directions given?

TODO: Implement

### Acknowledgements

##### Required length: 2 to 4 sentences

List acknowledgements if any. For example, if someone provided you a dataset, or
you used someone else's resources, this is a good place to acknowledge
the help or support you received.

TODO: Implement

### Contribution

##### Required length: 1/3 to 1/2 page

- Megan
  - Wrote two sections of Proposal
  - Created Github org/repo for our code, pushed raw datasets
  - Helped clean datasets, specifically classifying drugs in federal datasets as opioid or non-opioid for training our models
  - Wrote about half of paper, put paper together using LaTex template
  - Put together powerpoint
- Yoselyn
  - Wrote section of Proposal, put together into LaTex format
  - Contributed analysis on impact of lobbying groups on opioid distrubution
  - Found several new national datasets to use and cleaned them
- Matthew
  - Wrote section of proposal
  - Contributed analysis on opioid prescriber rates at the state level
  - Found new state-level datasets to use and cleaned them
- Adithya
  - Wrote section of proposal
  - Contributed analysis on opioid prescriber characteristics at the federal level to train a classifier which can predict whether a prescriber is a likely dispenser of opioids
  - Cleaned datasets for analysis

TODO: Make sure this list is accurate, once it is make it prose
