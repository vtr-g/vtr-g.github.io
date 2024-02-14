
# Codewars Grader
Developer: Vitor Gonçalves </br>
Contact: vgoncalves@usn.org
## Project Overview

This Codewars Grader is a Python-based tool designed to streamline the grading process for coding assignments on Codewars. This tool is especially useful for educators and instructors who manage a large number of students and need an efficient way to track and grade their progress on various coding challenges.


**Features:**
- User and Kata Data Processing: Retrieves detailed information about users and specific coding challenges (katas) from Codewars using their API.
- Automated Grading: Grades student submissions for assigned coding challenges.
- CSV Integration: Supports importing student usernames and coding challenge details through CSV files.
- Data Presentation: Uses Pandas for data manipulation and presentation, offering a clear view of students' performance.
- Scalable: Functionality to handle CSV files for student usernames

**Implementation Details:**
- User Summary Functions: Fetch and process user data from Codewars, including their completed challenges.
- Question Summary Functions: Retrieve and display details of specific coding challenges.
- Bulk Read and Grade Functions: Read lists of student usernames and coding challenge IDs from CSV files and grade them accordingly.
- Grading Function: A flexible grading system that allows for various input formats and outputs a grading dataframe.

**Technologies Used:**
- Python: Primary programming language for scripting and data manipulation.
- Pandas: Utilized for handling and organizing data efficiently.
- Requests: Employed to make API calls to Codewars for data retrieval.

**Future Improvements:**
- Add automatic data entry for Modern LMS
- Implement grading for specific Codewars challenge IDs.
- Create a form that is in .py specifically instead of .ipynb

[Code Repository](https://github.com/vvttrr/codewars-autograder)


