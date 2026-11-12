# Data

The survey data is **not included** in this repository.

## Source

Data Professional Survey, shared by Alex the Analyst:

- File: [`Power BI - Final Project.xlsx`](https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx)
- Repository: https://github.com/AlexTheAnalyst/Power-BI

The source repository does not state a licence, so I have not copied the dataset here. Download it from the link above to reproduce the analysis.

## Column descriptions

The cleaned records I worked from have **630 rows (one per respondent) and 28 columns**. The meanings below are inferred from the column names and values, because I did not have the original survey questionnaire.

| Column | Meaning |
|---|---|
| `Unique ID` | Anonymous respondent code |
| `Career_Switch` | Whether the respondent switched into data from another field (Yes / No) |
| `Salary_Range` | Salary band chosen (`0-40k` to `225k+`) |
| `Salary (Midppoint USD)` | Midpoint of the chosen band, in USD (renamed `Salary USD` in my model) |
| `Salary` | Satisfaction with pay, rated 0 to 10 (renamed `Salary Satisfaction`; **not** an amount of money) |
| `Work/Life Balance`, `Coworkers`, `Management`, `Upward Mobility`, `Learning` | Satisfaction ratings, 0 to 10 |
| `Transition_into_Data` | How hard it was to break into data (Very Easy to Very Difficult) |
| `Transition_sorting` | Helper number (1 to 5) that orders the difficulty answers |
| `Gender` | Male or Female in this file |
| `Age` | Age in years |
| `Age Brand` | Age bracket (renamed `Age Bracket`) |
| `Age_sorting` | Helper number for age brackets (contains an error; I rebuilt it) |
| `Education` | Highest education level |
| `Ethnicity` | Ethnicity |
| `Country` | Country of residence |
| `Job Role` | Current role |
| `Industry` | Industry |
| `Favorite Programming Language` | Favourite programming language |
| `Priority` | What the respondent values most in a job |
| `job_Role.2`, `Industry.2`, `Favorite_Programming_Language.2`, `Priority.2`, `Ethnicity.2` | Typed "Other" answers (mostly blank) |

## Cleaning steps

See "Data preparation" in the main [README](../README.md).
