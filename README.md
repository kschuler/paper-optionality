# optionality

Contains the code and data for the paper: 

Schuler, K.D. & Chen**, Y. (under review) The role of frequency and optionality in the regularization of linguistic variation. Glossa Psycholinguistics


--- 

## 📁 Contents 

- `data_anonymized.csv` - CSV file contining experiment data
- `analysis.ipynb` - analysis notebook
- `README.md` - repository overview

## 📋 Codebook 

| Column Name        | Description                                              |
|--------------------|----------------------------------------------------------|
| `experiment`   | Which Experiment (1 or 2)                  |
| `condition`        | Experimental condition (e.g., "Alternating", "Optional") |
| `random_id`             | Identifier for each paritcipant              |
| `exp_phase`         | Phase of experiment (e.g., "exposure", "test"                   |
| `trial_order` | Order of the trial in the experiment |
| `meaning`               | The intended noun meaning (e.g., "pig", "truck")          |
| `noun`     | The noun in the artificial language (e.g., "mawg", "geed")                   |
| `case`              | Whether the trial was singular or plural                    |
| `marker` | Whether the trial was marked (ka or po) or unmarked (is_null)  |
| `question`               | Debriefing question number           |
| `responses`     | Debriefing question response                   |
| `whichPressed`             | Participant’s response (which button they pressed in the 2AFC test)      |
| `isKa`             | Whether the button they pressed was 'ka', for the logistic regression                |
