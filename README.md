
# Survey Responses Dataset

This dataset contains anonymous survey responses collected in 2018. The dataset includes information about respondents' demographics, employment status, student status, and their feedback emails. The dataset is in CSV format and contains 34 columns.

## Dataset Description

### Columns

1. **started_datetime**: The date and time when the survey was started.
2. **completed_date_time**: The date and time when the survey was completed.
3. **time_taken**: The time taken to complete the survey in seconds.
4. **num_approvals**: The number of approvals received.
5. **num_rejections**: The number of rejections received.
6. **reviewed_at_datetime**: The date and time when the survey was reviewed.
7. **Country.of.Birth**: The country of birth of the respondent.
8. **Student.Status**: Indicates if the respondent is a student ("Yes") or not ("No").
9. **Employment.Status**: The employment status of the respondent (e.g., Full-Time, Part-Time, Unemployed).
10. **Current.Country.of.Residence**: The current country of residence of the respondent.
11. **total_ans_time**: The total time spent answering the survey in seconds.
12. **percent_qs_ans**: The percentage of questions answered by the respondent.
13. **qs_answrd**: The number of questions answered by the respondent.
14. **birthyear**: The birth year of the respondent.
15. **gender**: The gender of the respondent.
16. **parent_educ**: The education level of the respondent's parents.
17. **education**: The education level of the respondent.
18. **job**: The job title of the respondent.
19. **industry**: The industry in which the respondent is employed.
20. **incomegroup**: The income group of the respondent.
21. **feedback**: General feedback provided by the respondent.
22. **question_number**: The question number in the survey.
23. **question**: The survey question.
24. **answer**: The respondent's answer to the survey question.
25. **percent_answered**: The percentage of the survey answered by the respondent.
26. **relation_type**: The type of relationship (e.g., friend, family, other).
27. **email1**: Feedback email 1.
28. **email2**: Feedback email 2.
29. **email3**: Feedback email 3.
30. **email4**: Feedback email 4.
31. **email5**: Feedback email 5.
32. **relation_type_numeric**: Numeric representation of the relationship type.
33. **Student.Status_numeric**: Numeric representation of the student status.
34. **Employment.Status_numeric**: Numeric representation of the employment status.

### Example Code
Here is an example of how to load and analyze the dataset:

# Load necessary library
library(dplyr)

# Load the dataset
file_path <- "path/to/updatedsurveyResponsesAnon.csv"
survey_data <- read.csv(file_path)

# Display the first few rows of the dataset
head(survey_data)

