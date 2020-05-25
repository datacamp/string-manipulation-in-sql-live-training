# String Manipulation in SQL <br/>by **Brian Piccolo**

Live training sessions are designed to mimic the flow of how a real data scientist would address a problem or a task. As such, a session needs to have some “narrative” where learners are achieving stated learning objectives in the form of a real-life data science task or project. For example, a data visualization live session could be around analyzing a dataset and creating a report with a specific business objective in mind _(ex: analyzing and visualizing churn)_, a data cleaning live session could be about preparing a dataset for analysis etc ... 

As part of the 'Live training Spec' process, you will need to complete the following tasks:

Edit this README by filling in the information for steps 1 - 4.

## Step 1: Foundations 

This part of the 'Live training Spec' process is designed to help guide you through session design by having you think through several key questions. Please make sure to delete the examples provided here for you.

### A. What problem(s) will students learn how to solve? (minimum of 5 problems)

>- Explore a dataset in a SQL database by examining table structure and data types
>- Converting or casting common data types
>- How to manipulate date time data using built-in date and time functions
>- How to manipulate string data using built-in string and character functions
>- Create temporary tables and use them to simplify complex queries
>- Learn how to use temporary tables to create new fields from unstructured string data
>- Create user defined functions that can be used to simplify data manipulation tasks


### B. What technologies, packages, or functions will students use? Please be exhaustive.

>- EXTRACT, DATE_PART, DATE_TRUNC
>- SUBSTRING, LEFT, RIGHT
>- array()
>- split_part()
>- CHAR_LENGTH, POSITION
>- CAST
>- CREATE TABLE, DROP TABLE
>- CREATE FUNCTION

### C. What terms or jargon will you define?

_Whether during your opening and closing talk or your live training, you might have to define some terms and jargon to walk students through a problem you’re solving. Intuitive explanations using analogies are encouraged._

>- Data types
>- Built-in functions 
>- User-defined functions
>- Date / time characteristics like "date parts"
>- Normalization
>- TEMP tables

### E. What datasets will you use? 

Live training sessions are designed to walk students through something closer to a real-life data science workflow. Accordingly, the dataset needs to accommodate that user experience. 
As a rule of thumb, your dataset should always answer yes to the following question: 
> Short Term Rentals in Cambridge, MA - https://data.cambridgema.gov/Inspectional-Services/Short-Term-Rentals/wxgv-w968

## Step 2: Who is this session for?

Terms like "beginner" and "expert" mean different things to different people, so we use personas to help instructors clarify a live training's audience. When designing a specific live training, instructors should explain how it will or won't help these people, and what extra skills or prerequisite knowledge they are assuming their students have above and beyond what's included in the persona.

- [ ] Please select the roles and industries that align with your live training. 
- [ ] Include an explanation describing your reasoning and any other relevant information. 

### What roles would this live training be suitable for?

*Check all that apply.*

- [X] Data Consumer
- [ ] Leader 
- [X] Data Analyst
- [ ] Citizen Data Scientist
- [ ] Data Scientist
- [ ] Data Engineer
- [X] Database Administrator
- [ ] Statistician
- [ ] Machine Learning Scientist
- [ ] Programmer
- [ ] Other (please describe)

### What industries would this apply to?

*List one or more industries that the content would be appropriate for.*


### What level of expertise should learners have before beginning the live training?

*List three or more examples of skills that you expect learners to have before beginning the live training*

> - Can use SELECT queries to retrieve data from PostgreSQL database
> - Can use PostgreSQL built-in functions in SQL queries
> - Understands what a user-defined function is and how to use one in SQL queries

## Step 3: Prerequisites

List any prerequisite courses you think your live training could use from. This could be the live session’s companion course or a course you think students should take before the session. Prerequisites act as a guiding principle for your session and will set the topic framework, but you do not have to limit yourself in the live session to the syntax used in the prerequisite courses.

Functions for Manipulating Data in PostgreSQL
Intermediate SQL
Exploratory Data Analysis in SQL


## Step 4: Session Outline

A live training session usually begins with an introductory presentation, followed by the live training itself, and an ending presentation. Your live session is expected to be around 2h30m-3h long (including Q&A) with a hard-limit at 3h30m. You can check out our live training content guidelines [here](_LINK_). 

> ### Introduction Slides 
> - Introduction to the webinar and instructor (led by DataCamp TA)
> - Introduction to the topics
>   - Discuss need to become data fluent
>   - Define data fluency
>   - Discuss how learning Python fits into that and go over session outline
>   - Set expectations about Q&A
> ### Exploring the Dataset
> - What Have We Learned About the Short Term Rentals Data
> - Q&A
> ### Using built-in functions to mainpulate string and character data
> - Converting data from one type to another using `CAST()`
> - Extracting string data using `SUBSTRING()` and `POSTIION()`
> - Extracting string data using `split_part()
> - Using `ARRAYS` to manipulate strings stored as comma-separated-values
> - What Have We Learned About the Short Term Rentals Data
> - Q&A
> ### Using temporary tables to simplify complex queries
> - Creating a temporary table with our rental services
> ### User-defined functions to create reusable code
> ### Putting it all together!
> ### Q&A
> ### Recap and closing


## Authoring your session

To get yourself started with setting up your live session, follow the steps below:

1. Download and install the "Open in Colabs" extension from [here](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo?hl=en). This will let you take any jupyter notebook you see in a GitHub repository and open it as a **temporary** Colabs link.
2. Upload your dataset(s) to the `data` folder.
3. Upload your images, gifs, or any other assets you want to use in the notebook in the `assets` folder.
4. Check out the notebooks templates in the `notebooks` folder, and keep the template you want for your session while deleting all remaining ones.
5. Preview your desired notebook, press on "Open in Colabs" extension - and start developing your content in colabs _(which will act as the solution code to the session)_.  :warning: **Important** :warning: Your progress will **not** be saved on Google Colabs since it's a temporary link. To save your progress, make sure to press on `File`, `Save a copy in GitHub` and follow remaining prompts. You can also download the notebook locally and develop the content there as long you test out that the syntax works on Colabs as well.
6. Once your notebooks is ready to go, give it the name `session_name_solution.ipynb` create an empty version of the Notebook to be filled out by you and learners during the session, end the file name with `session_name_learners.ipynb`. 
7. Create Colabs links for both sessions and save them in notebooks :tada: 
