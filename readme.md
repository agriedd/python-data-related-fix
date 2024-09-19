## Data Related Fix

This repository is how I managed to fix issues with unrelated data.

the current data structures are listed below:

## Respondent
|respondent_id|date|gender|...|
|-------------|----|------|---|
| "60"|"2023-02-28"|"1"|...|
| ... | ... | ... | ... |
|"64"|"2023-03-01"|"1"|...|

## User Answer Question Two
|respondent_id|date|id|...|
|-------------|----|------|---|
| "60"|"2023-02-28"|"1"|...|
| ... | ... | ... | ... |
|"64"|"2023-03-01"|"200"|...|

## User Answer Question Three
|date|id|...|
|----|------|---|
|"2023-02-28"|"1"|...|
| ... | ... | ... |
|"2023-03-01"|"200"|...|

## User Answer ...

## Result

|respondent_id|gender|id_2|id_3|...|
|----|------|---|---|---|
|"2023-02-28"|"1"|"1"|"1"|...|
| ... | ... | ... | ... | ... |
|"2023-03-01"|"1"|"200"|...| ... |

## Disclaimer

The dataset is used for education and analytical purposes. The original data has been anonymized, altered, and merged with random values to ensure it is not represent the real dataset