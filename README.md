# Phone-Plan-Recommender
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. In models.ipynb, multiple models are trained and tested in order to determine which will have the highest accuracy for this task. 

### Data description
Every observation in the dataset contains monthly behavior information about one user. The information given is as follows: 

- сalls — number of calls,
- minutes — total call duration in minutes,
- messages — number of text messages,
- mb_used — Internet traffic used in MB,
- is_ultra — plan for the current month (Ultra - 1, Smart - 0).

### Set Up Requirements 
In order to run this project, an environment must be set up with Jupyter, Scikit-Learn, Matplotlib, and Pandas. 