# Using Machine Learning to Address the Opioid Crisis

### Abstract

According to the US Center for Disease Control and Prevention, since 1999 almost 850,000 people have died from drug overdoses, and in 2019 more than 70% of these deaths were attributed solely to opioids \cite{cdc:dataOverview}. While previous studies have used publicly-available data and machine learning models to try and aid in solving this crisis, the vast majority of previous works have focused mainly on users of opioids, specifically using models to predict an individual’s chance to become addicted to opioids. For our contribution to this body of work, we instead focus on another side of the opioid supply chain: opioid prescribers. We tackle this topic on three separate fronts, narrowing our analyses to the United States. We first analyze possible influencers to opioid prescribing rates, specifically whether we can find any correlation between pro-prescription lobbying efforts and opioid prescribing rates. We then test several machine learning models to fit a predictor which can identify providers likely to be prescribers of opioids. Finally, we take that model, trained on national data, and apply it to a hyper-local dataset for the state of Connecticut to see if we can garner any additional insights. Surprisingly, we find that lobbying efforts didn’t have as much of an impact as we thought on opioid distribution rates, despite the huge sums of money being used for said efforts. We also find that Gradient Boosting worked best for both our national predictor model as well as our state-level analysis.


### Introduction

Opioid addiction and overdose have become tragic and inescapable threads in the fabric of American daily life. Many Americans know someone who has died of a drug overdose, and even if they do not, headlines announcing high-profile overdose deaths are common news items. Among the hundreds of thousands of opioid related deaths in the past few years are celebrated musicians Prince, Mac Miller, and Tom Petty; accomplished athletes including pitcher Tyler Skaggs, football player Jake Ehlinger, and NHL player Jimmy Hayes; and lauded actors like Philip Seymore Hoffman.

Data also sheds insight into the scope of this epidemic. According to the United States Center for Disease Control, in 2019 more than 50,000 people in the United States died from opioid-related overdoses \cite{dataabuse.gov}. It is also estimated that 3 million Americans suffer from opioid use disorder, and in 2020, a staggering 93,000 people died in the United States from drug overdoses \cite{stobbe}, most of which were related to opioids. Additionally, studies estimate that the total "economic burden" of prescription opioid misuse in the United States is $78.5 billion a year, including the costs of healthcare, lost productivity, addiction treatment, and criminal justice involvement \cite{dataabuse.gov}. While the United States is certainly not the only country suffering from this epidemic, statistics like these make it clear that COVID-19 is not the only major medical crisis nations are struggling to contain at the moment.

Despite numerous studies related to opioid use, we feel there is ample room to take a “deep dive” into publicly-available data and see if we can draw useful conclusions to perhaps provide insight into qualming this crisis. We plan to focus US federal and state datasets to both take a broad look at the situation while also allowing us to delve deeper into more localized data to potentially find trends. More specifically, we hope to place more emphasis on examining the impact of opioid prescribers instead of focusing solely on opioid users, as has been done in other studies. To do this, will first test various machine learning models to try and create classifiers to predict the likelihood that a given doctor is a significant prescriber of opioids using a national dataset. We will then take that model and use it for analysis of a more local dataset -- specifically for the state of Connecticut -- to see if we can find relationships between prescribers who are classified as likely to prescribe opioids and the side effects of opioids, such as drug overdose and rehab data. Finally, we will look to see if other outside factors could be potentially affecting the rate of opioid prescriptions, specifically investigating if we can find a correlation between lobbying efforts of pro-drug interest groups to the amount of opioids prescribed in the region where they exert influence.

While we do have high hopes for this project, we acknowledge that we are tackling a tough issue that does not necessarily have a perfect answer which can be prescribed by a single machine learning algorithm; indeed, some data we’d like to ideally have for our analysis (such as a better insight into the prevalence of illegal opioids by geography) are simply not available. We also recognize that we have certain limitations geographically on our datasets, as our data is only focused only on the United States. However, we are confident that our exploratory analysis will shed some insights into the nature of this crisis worldwide.

### Related Work

There have been several research efforts centered around this topic, particularly in the fields of machine learning and data science, even within the realm of individual study. For example, both Tara Boyle's "The Opioid Crisis in Data" \cite{boyle2019:online} and Kiros Gebremariam's capstone project \cite{KirosGPr71:online} use machine learning for exploratory analyses of opioid prescription trends. In both Boyle and Gebremariam's works, their analyses of publicly-available federal datasets show that of all medical specialities, general practitioners in family practice and internal medicine prescribed the greatest number of opioids. Additionally, Hydrocodone/Vicodin was far and above the most commonly-prescribed opioid, with more than double the amount of units than the second most-common opioid, Tramadol/Ultram, for the year 2016.

The majority of scholarly research is focused around predicting one’s chances of opioid abuse disorder based on personal characteristics, as opposed to focusing on the prescribers themselves. Several studies, such as Huinker’s analysis \cite{huinkerpaper} go into more detail about possible machine learning algorithms which can be applied to predict the possibility of opioid abuse disorder. Huinkers' study uses four popular machine learning algorithms -- Decision Trees, Artificial Neural Networks, Support Vector Machines, and Logistic Regression -- and ultimately finds a SVM with k-fold cross-validation to be the superior model for predicting individual opioid misuse. Similarly, Lo-Ciganic W et al \cite{10.1001/jamanetworkopen.2019.0968} conclude that machine learning algorithms using administrative data appear to be a valuable and feasible tool for more accurate identification of opioid overdose risk.

Despite these insights, there have been several recent works which highlight potential issues with these models. Rather than try to develop models for opioid abuse indicators, Angela Kilby \cite{10.1145/3442188.3445891} investigates issues with such algorithmic methods currently being used in locales such as medical offices and police departments. Kilby's work, which uses several proprietary datasets, finds that machine-generated risk scores are a form of algorithmic unfairness in machine learning applications as they are heavily dependent on the researcher's choice of objective function, and as such are not reliable indicators of actual risk when deciding treatment. Indeed, critique of machine learning algorithms predicting one’s chances of opioid abuse is so prevalent that even mainstream journalistic sources cover the topic. For example, Szalavitz’s exposé in Wired \cite{wiredarticle:online} displays how such algorithms currently in use by doctors and drug companies have unfairly discriminated against patients with complex or chronic illnesses, histories of sexual abuse, and women.

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

We would like to acknowledge the assistance of our Machine Learning professor, Aanchan Mohan, for his insight in the early stages of our project. He was especially helpful to us when trying to hone in on specific aspects to focus on for our analysis of the opioid crisis, taking time to help find previous scholarly works as inspiration for our final product.

### Contributions

Overall, the amount of work necessary for this project, and its broad scope, made having four group members an asset, and allowed us to evenly split the workload relatively easily. In the work leading up to the proposal, each group member equally researched potential ideas for our project; and when we settled on the opioid crisis, we all spent time looking up datasets we could potentially use. When it came to actually writing the proposal itself, that too was more or less split equally; each of us was responsible for at least one section, and we came together to transform our prose into an acceptable LaTex format. Once the proposal was submitted and we received feedback, we also met regularly to discuss changes to our implementation and next steps.

When it came to the main piece of our project, we decided to ultimately do three unique analyses, so three of our group members took responsibility for those specific analyses. Yoselyn focused on the piece of our analysis which covered the effect of lobbying groups on opioid distribution rates; Adithya was responsible for the prescriber classifier portion of our analysis; and Matthew finished the piece on our state-level analysis. To get their analyses to work, all three of these group members needed to clean the raw datasets to their liking, and in some cases find additional datasets to complement the shared federal ones in our Github repo. They all also completed a python workbook with their findings, wrote the sections of this paper specific to their analyses, and added some slides to our PowerPoint presentation about their findings. This left Megan to handle most of the other work necessary for this project. She set up the initial Github repo holding our shared works and populated with raw datasets; helped other group members with cleaning and formatting datasets; put together the majority of the PowerPoint presentation; and wrote about half of this report, including putting it together in LaTex format.
