# Dataset introduction

The [ABC dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing. Changes and updates to the source data and have been coordinated in the [abc-data-dictionary repository](https://github.com/sleepepi/abc-data-dictionary).

**Disclaimer:** These data are not perfect. Please [submit issues](https://github.com/sleepepi/abc-data-dictionary/issues) for any problematic findings.

## Structure

The dataset is broken down into `baseline`, `month09`, and `month18` files, containing 49, 43, and 40 records, respectively. The primary subject identifier is [`nsrrid`](https://sleepdata.org/datasets/abc/variables/nsrrid).

## Explanation of treatment arms

Each ABC subject was randomized to bariatric surgery (LGB) or continuous positive airway pressure (CPAP). The assigned arm is represented by the [`rand_treatmentarm`](https://sleepdata.org/datasets/abc/variables/rand_treatmentarm) variable. The meanings of the arms are as follows:

1. Laparoscopic Gastric Banding (LGB)
2. Continuous Positive Airway Pressure (CPAP)

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
