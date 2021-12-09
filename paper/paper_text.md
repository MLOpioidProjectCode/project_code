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

Despite numerous studies related to opoiod use, we feel there is ample room to take a “deep dive” into publicly-available data and see if we can draw useful conclusions to perhaps provide insight into qualming this crisis. We plan to focus US federal and state datasets to both take a broad look at the situation while also allowing us to delve deeper into more localized data to potentially find trends. More specifically, we hope to place more emphasis on examining the impact of opioid prescribers instead of focusing solely on opioid users, as has been done in other studies. To do this, will first test various machine learning models to try and create classifiers to predict the likelihood that a given doctor is a significant prescriber of opioids using a national dataset. We will then take that model and use it for analysis of a more local dataset -- specifically for the state of Connecticut -- to see if we can find relationships between prescribers who are classified as likely to prescribe opioids and the side effects of opioids, such as drug overdose and rehab data.

While we do have high hopes for this project, we acknowledge that we are tackling a tough issue that does not necessarily have a perfect answer which can be prescribed by a single machine learning algorithm; indeed, some data we’d like to ideally have for our analysis (such as a better insight into the prevalence of illegal opioids by geography) are simply not available. We also recognize that we have certain limitations geographically on our datasets, as our data is only focused only on the United States. However, we are confident that our exploratory analysis will shed some insights into the nature of this crisis worldwide.


### Related Work

##### Required length: 1/2 to 1 page

There have been multiple studies and significant research centered around this topic, particularly in the fields of machine learning and data science. Individuals like Tara Boyle \cite{boyle2019:online} and Kiros Gebremariam \cite{KirosGPr71:online} have written capstone projects and articles attempting to make sense of publicly-available government datasets around the issue. However, the majority of scholarly research is focused around predicting one’s chances of opioid abuse based on personal characteristics. Several studies, such as Huinker’s analysis of machine learning models to predict opioid misuse \cite{huinkerpaper} go into more detail about possible machine learning algorithms which can be applied to predict possible opioid abuse, while others such as Kilby \cite{10.1145/3442188.3445891} and Lo-Ciganic W et al \cite{10.1001/jamanetworkopen.2019.0968} investigate issues with algorithmic methods currently being used in locales such as medical offices and police departments. Indeed, critique of machine learning algorithms predicting one’s chances of opioid abuse is so prevalent that even mainstream journalistic sources cover the topic, as in Szalavitz’s expose in Wired \cite{wiredarticle:online} published only two months ago.

TODO: Expand on these summaries/works, add more.

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

- Are all contributions listed clearly?
- Did each member contribute approximately equally to the project?

TODO: Implement
