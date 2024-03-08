# Project: No Show Appointments - Python, Investigate a Dataset

## Project Details

Analyze a dataset and then communicate the findings. 

Skills demonstrated in this project include:

* Proficiency in the steps of a typical data analysis process
* Formulating and answering dataset-related inquiries
* Wrangling data into a usable format for thorough investigation
* Effective communication of analysis results
* Optimization of data analysis through vectorized operations in NumPy and Pandas
* Accessing data conveniently using Pandas' Series and DataFrame objects
* Generating illustrative plots with Matplotlib to showcase analysis findings.

## Analysis and Statistics

1. Which day(s) are clients more likely to be a no-show?
2. Is there a correlation between no-shows and not receiving an SMS reminder?


### Statistical and Analytical techniques used:

**Descriptive Statistics:**   
Descriptive statistics, such as counts, percentages, and averages, were calculated to summarize key metrics, including the total number of appointments, the number of no-shows, and the distribution of appointments across weekdays.

**Data Visualization:**   
Visualizations, including bar charts, pie charts, and stacked bar charts, were utilized to present the findings visually and facilitate the interpretation of trends and patterns in the data.

**Comparative Analysis:**   
Comparative analysis was conducted to compare the proportion of no-shows among different weekdays and between patients who received SMS reminders and those who did not. This involved calculating percentages and conducting statistical tests to determine significant differences.

**Correlation Analysis:**   
Correlation analysis was performed to assess the relationship between receiving SMS reminders and appointment attendance. This involved examining the correlation coefficient and conducting hypothesis testing to determine the strength and significance of the association.

**Summarization Techniques:**   
Techniques such as summarizing weekday statistics and calculating percentages were used to provide a comprehensive overview of appointment no-show patterns and the effectiveness of SMS reminders.


## Dataset

[No-Show Apointments](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv&sa=D&ust=1532469042118000) (original source on Kaggle).  
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number ofcharacteristics about the patient are
included in each row.  

● ‘ScheduledDay’ tells us on what day the patient set up their appointment.  
● ‘Neighborhood’ indicates the location of the hospital.  
● ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.  



### Step One - Choose Your Data Set

Click [this link](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True) to open a document with links and information about data sets that you can investigate for this project. You must choose one of these datasets to complete the project.

### Step Two - Get Organized
Eventually you’ll want to submit your project (and share it with friends, family, and employers). Get organized before you begin. We recommend creating a single folder that will eventually contain:

The report communicating your findings
Any Python code you wrote as part of your analysis
The data set you used (which you will not need to submit)
You may wish to use Jupyter notebook, in which case you can submit both the code you wrote and the report of your findings in the same document. Otherwise, you will need to submit your report and code separately. If you would like a notebook template to help organize your investigation, you can find a link in the resources at the bottom of the page or you can click [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd0f5a_investigate-a-dataset-template/investigate-a-dataset-template.ipynb). You can also complete and submit the project in the classroom by going to the Project Notebook part of this lesson.

**Selected dataset**: [No-show appointments](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv&sa=D&ust=1510020454356000&usg=AFQjCNEEOPkttwxzEyo0gjL5cfxq6ynIgg)

**Dataset Description**:
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.
- ‘ScheduledDay’ tells us on what day the patient set up their appointment.
- ‘Neighborhood’ indicates the location of the hospital.
- ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
- Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

### Step Three - Analyze Your Data
Brainstorm some questions you could answer using the data set you chose, then start answering those questions. You can find some questions in the [data set options](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True) to help you get started.

Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and Pandas where they are appropriate!

### Step Four - Share Your Findings
Once you have finished analyzing the data, create a report that shares the findings you found most interesting. If you use a Jupyter notebook, share your findings alongside the code you used to perform the analysis. make sure that your report text is contained in Markdown cells to clearly distinguish your comments and findings from your code work. You should also feel free to use other tools and software to craft your final report, but make sure that you can submit your report as an HTML or PDF file so that it can be opened easily.

### Step Five - Review
Use the [Project Rubric](https://review.udacity.com/#!/rubrics/107/view) to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project!
Supporting Materials
[Investigate a Dataset - Template Notebook](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd0f5a_investigate-a-dataset-template/investigate-a-dataset-template.ipynb)

The project walkthrough can be found [here](https://www.youtube.com/watch?time_continue=83&v=OtDZCYxbHB4)
