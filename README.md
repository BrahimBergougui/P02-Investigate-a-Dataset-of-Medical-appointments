# P02-Investigate-a-Dataset-of-Medical-appointments
> Investigate a Dataset of Medical appointments - Project done for Udacity Data Analyst Nanodegree Program as a part of Introduction to Data Analysis course.
# Project Details
> ### Introduction
In this project, we will conduct our own data analysis and create a file to share that documents our findings. we start by taking a look at our dataset and brainstorming what questions we could answer using it. Then we used pandas and NumPy to answer the questions we are most interested in, and create a report sharing the answers. we make it clear in our communications that our findings are tentative. 

> ###  Step One - Choose Your Data Set
As first step we choose the data sets that we are going to investigate for this project. which called [No-show appointments](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv) which contains information about 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.
Here are a brief overview  for 14 variables (characteristics) were used in this dataset

- **`PatientId`**: Identification of a patient 
- **`AppointmentID`**: Identification of each appointment
- **`Gender`**:  patient's gender (M/F)     
- **`ScheduledDay`**: The day of the actuall appointment, when they have to visit the doctor.
- **`AppointmentDay`**:The day someone called or registered the appointment, this is before appointment of course.
- **`Age`**: How old is the patient.
- **`Neighborhood`**: Where the appointment takes place (location of hospital).
- **`Scholarship`**: indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
- **`Hipertension`**: indicates whether or not the patient is experiencing Hypertension.
- **`Diabetes`**: indicates whether or not the patient is experiencing Diabetes.
- **`Alcoholism`**: indicates whether or not the patient is experiencing Alcoholism.
- **`Handcap`**: indicates whether or not the patient is with special needs.
- **`SMS_received`**: indicates whether or not the patient has received a reminder text message.
- **`Show-up`**: This is our main varaible. ‘No’ if the patient showed up to their appointment, other wise 'yes'

> ###  Step Two - Get the Dataset Organized
Eventually you’ll want to submit your project (and share it with friends, family, and employers). Get organized before you begin. We recommend creating a single folder that will eventually contain:

> ###  The report communicating your findings

Any Python code you wrote as part of your analysis
The data set you used (which you will not need to submit)
You may wish to use a Jupyter notebook, in which case you can submit both the code you wrote and the report of your findings in the same document. Otherwise, you will need to submit your report and code separately. If you would like a notebook template to help organize your investigation, you can click here. Or there may be a page in the project here called Project Workspace: Complete and Submit Project, where you can do all your work and submit the project.

> ###  Step Three - Analyze Your Data

Brainstorm some questions you could answer using the data set you chose, then start answering those questions. You can find some questions in the data set options to help you get started.

Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and pandas where they are appropriate!

> ###  Step Four - Share Your Findings

Once you have finished analyzing the data, create a report that shares the findings you found most interesting. If you use a Jupyter notebook, share your findings alongside the code you used to perform the analysis. Make sure that your report text is contained in Markdown cells to clearly distinguish your comments and findings from your code work. You should also feel free to use other tools and software to craft your final report, but make sure that you can submit your report as an HTML or PDF file so that it can be opened easily.

> ###  Step Five - Review
Use the Project Rubric to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project!
