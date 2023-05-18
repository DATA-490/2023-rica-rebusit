# <Project Title>
* **Author**: Rica Rebusit, github: [rrebusit](https://github.com/rrebusit)
* **Major**: B.S. Applied Mathematics
* **Year**: Senior 2023

# Type of project
Text descriptions are reported and text based and machine learning models are used to predict the priority of the activity based on the descriptions. Descriptions are cleaned and tokenized where topic modeling such as Latent Dirichlet Allocation is used to find key topics from clustering the rows of activity descriptions. Then to predict the priority of the activity, Random Forest classification machine learning model is used.  

# Purpose (including intended audience)
Intended audience is for Center for Healthy Communities who wants to understand the impact these activities have on the amount of applications being submitted. This will give them insight on how to distribute money to their campus partners and which activity to prioritize. Students who receive food assistance through CalFresh Outreach will also benefit from this project. Most of work was cleaning up and streamline predicting process.

# Explanation of files

* `scripts` - Where the work was done
    - `LDA.qmd`: The process where cleaning, pre-processing, and tokenizing the data done in here
      - Data Variables: `shortcode`, `quarter`, `contract_year`, `train_meet`, `partner`, `descrip`, `level`, `document`, `topic_1`, `topic_2`, `topic_3`, `topic_4`, `topic_5`
    - `modeling_apps_using_partnerships.qmd`: Side project. Uses linear regression to understand relationship of total amount of applications sent and partnerships
      - Data Variables: `subcontractor`, `quarter`, `calendar_year`, `total_submitted`, `paper`, `total_approved`, `denied`, `paper_approved`, `sar7`, `re`, `prescreen`, `trainings`
    - `Random_Forest.qmd`: The file where data that ran through the cleaning and LDA process goes through the machine learning Random Forest model.



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
