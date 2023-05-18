# <Project Title>
* **Author**: Rica Rebusit, github: [rrebusit](https://github.com/rrebusit)
* **Major**: B.S. Applied Mathematics
* **Year**: Senior, Spring 2023

# Type of project
Text descriptions are reported and text based and machine learning models are used to predict the priority of the activity based on the descriptions. Descriptions are cleaned and tokenized where topic modeling such as Latent Dirichlet Allocation is used to find key topics from clustering the rows of activity descriptions. Then to predict the priority of the activity, Random Forest classification machine learning model is used. Most of work was organizing and cleaning up to streamline predicting process.

# Purpose (including intended audience)
Intended audience is for Center for Healthy Communities who wants to understand the impact these activities have on the amount of applications being submitted. This will give them insight on how to distribute money to their campus partners and which activity to prioritize. Students who receive food assistance through CalFresh Outreach will also benefit from this project.

# Explanation of files

* `data` - Single text file where you would have to ask Robin about the data.

* `documentations` - Notes about meetings, general flow of the classification model, and how to install python.

* `presentation` - This file contains the 2023 NSC Poster Session work and the final stakeholder report.
    - `images` - Has the graphs and pictures that were added to the poster and as well as the stakeholder report.
    - `2023 NSC Poster Session.qmd` - The file where graphs were coded.
    - `Stakeholder_Report.html` - A quarto presentation to present to stakeholder.

* `scripts` - Where the work was done.
    - `LDA.qmd`: The process where cleaning, pre-processing, and tokenizing the data done in here.
      - Data Variables: `shortcode`, `quarter`, `contract_year`, `train_meet`, `partner`, `descrip`, `level`, `document`, `topic_1`, `topic_2`, `topic_3`, `topic_4`, `topic_5`
    - `Random_Forest.qmd`: The file where data that ran through the cleaning and LDA process goes through the machine learning Random Forest model.
      - Data Variables: Same as `LDA.qmd`

# Completion status 

<as applicable> Pending steps include: 

- [ ] Get more labeled data for accurate predictions 

## Enhancements: 
<List at least 2>

- [ ] Update and refine cleaning/tokenization process
- [ ] Compare Random Forest model using a different machine learning model

# Can someone else work on this project? 
Yes

# Public Display/dissemination
2023 California State University, Chico College of Natural Sciences Poster Session

# License
