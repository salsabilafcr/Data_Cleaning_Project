# FIFA21_Dataset_Cleaning_With_Python

The FIFA21 dataset used in this project was obtained from the public dataset. This data consists of player attributes, statistics and other relevant information.
The original FIFA21 dataset contains over 18,000 player data records. Each record represents a unique player and includes various attributes such as player name, age, nationality, club, overall ranking and more.

## Issues Found in The Data
During the initial exploration and analysis of the FIFA21 dataset, several issues were identified including:
- **Missing values** - The Hits and Loan Date End columns had missing values which required careful handling and computation.
- **Inconsistent formatting** - This was seen in some columns that had varying and inconsistent values, hence the need to standardize the data. There are also some columns that have different unit formats.

## Tools Used
For the data cleaning project, the following tools and libraries were used:
- **Python** for data cleaning tasks.
- **Pandas Library** for instrumental in data manipulation, cleaning and handling missing values.
- **NumPy Library** for utilized for mathematical operations and array handling during the cleaning process.
- **Jupyter Notebooks** provided an interactive environment for code development, exploration and documentation.

## Data Cleaning Process
The data cleaning process involved the following steps:
1. **Data Understanding** - The dataset was thoroughly examined to understand the structure, columns and their meanings. The data did not have a data dictionary attached. With the help of online sources I was able to create one that helped me gain an understanding of what all the columns represented.
2. **Data Exploration** - Exploratory Data Analysis was performed to gain insights into the data, identify patterns and uncover anomalies.
3. **Handling Missing Values** - Through the EDA performed, I quickly realised there was a valid reason for the missing values in the Hits and Loan Date End columns. The Hits column represented the number of times a player had been searched in the FIFA database. Since some players had never been searched, their records were blank. For the Loan Date End column, this represented when the contracts for players who were On Loan would end. Since some of the players were free and others on contract, their records were left blank.
4. **Standardizing Formatting** - Inconsistent formatting issues eg the values in the Heights and Weights columns that were stored with different units were resolved by applying transformations, lambda functions and data normalization techniques.
5. **Validation and Quality Checks** - The cleaned dataset underwent rigorous validation to ensure the quality, accuracy and integrity of the data.
