## About

The Apnea, Bariatric surgery, and CPAP (ABC) study aimed to assess the role of bariatric (weight loss) surgery as compared to continuous positive airway pressure (CPAP) therapy plus weight loss counseling for the treatment of patients with class II obesity and those who have severe obstructive sleep apnea (OSA).

## Methods

### PSG Collection
PSG signal data were collected using the Compumedics E-Series system (Abbotsford, Victoria, Australia). EDF signal and XML signals were later exported from the Compumedics E-Series system. The raw data is captured by a NONIN Model 3100 Wrist Oximeter.

1. EDF - Signal files in the European Data Format exported from Compumedics Profusion.
2. XML (Profusion) - Annotation files exported from Compumedics Profusion. (Learn more...)
3. XML (NSRR) - Annotation files processed in the EDF Editor and Translator tool.

View the PSG data here: **[/polysomnography](:files_path:/polysomnography)** Overnight polysomnography (PSG) data from baseline and follow-up (9- and 18-Month) visits.

<details><summary>The settings below represent the standards set at the beginning of the project for E-Series data collection. There may be a small proportion of studies and signals that do not match these standards exactly. Please review the settings at the individual sleep study level as you proceed with any analyses.</summary>

| Channel               | EDF Label        | Input 1          | Input 2 | Sampling rate (Hz) | Hardware filters (Hz)       | Sensor type                          |
|:---------------------:|:----------------:|:----------------:|:-------:|:------------------:|:---------------------------:|:------------------------------------:|
| Left Frontal EEG      | F3               | F3               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Right Frontal EEG     | F4               | F4               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Left Central EEG      | C3               | C3               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Right Central EEG     | C4               | C4               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Left Occipital EEG    | O1               | O1               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Right Occipital EEG   | O2               | O2               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Left Mastoid EEG      | M1               | M1               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Right Mastoid EEG     | M2               | M2               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Left EOG              | E1               | E1               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Right EOG             | E2               | E2               | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| ECG1                  | ECG1             | ECG1             | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Ag/AgCl patch                        |
| ECG2                  | ECG2             | ECG2             | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Ag/AgCl patch                        |
| Left Leg EMG          | LLeg1            | LLeg1            | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Compumedics piezo leg leads          |
| Left Leg EMG          | LLeg2            | LLeg2            | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Compumedics piezo leg leads          |
| Right Leg EMG         | RLeg1            | RLeg1            | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Compumedics piezo leg leads          |
| Right Leg EMG         | RLeg2            | RLeg2            | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Compumedics piezo leg leads          |
| Center Chin EMG       | Chin1            | Chin1            | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Left Submentalis EMG  | Chin2            | Chin2            | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Right Submentalis EMG | Chin3            | Chin3            | Fpz     | 256                | High Pass 0.16/Low Pass 105 | Gold cup electrode                   |
| Airflow            | Airflow          | Airflow             | -       | 32                 | -                           | Compumedics thermistor               |
| Abdomen               | Abdo             | Abdo             | -       | 32                 | -                           | Compumedics Summit IP RIP            |
| Thorax                | Thorax           | Thorax           | -       | 32                 | -                           | Compumedics Summit IP RIP            |
| Snore                 | Snore            | Snore            | -       | 256                | -                           | Compumedics snore mic                |
| Sum                   | Sum              | Sum              | -       | 32                 | -                           | Compumedics Summit IP RIP            |
| Position              | PosSensor        | PosSensor        | -       | 16                 | -                           | Compumedics external position sensor |
| Oximetry Status       | Ox Status        | Ox Status        | -       | 16                 | -                           | Nonin 8000 sensor                    |
| Pulse                 | Pulse            | Pulse            | -       | 16                 | -                           | Nonin 8000 sensor                    |
| SpO2                  | SpO2             | SpO2             |         | 16                 | -                           | Nonin 8000 sensor                    |
| Nasal Pressure        | Nasal Pressure   | Nasal Pressure   | -       | 32                 | -                           | Nasal cannula                        |
| CPAP Flow             | CPAP Flow        | CPAP Flow        | -       | 32                 | -                           | -                                    |
| CPAP Pressure         | CPAP Press       | CPAP Press       | -       | 16                 | -                           | -                                    |
| Plethysmography       | Pleth            | Pleth            | -       | 256                | -                           | Nonin 8000 sensor                    |
| Derived Heart Rate    | Derived HR       | Derived HR       | -       | 64/512             | -                           | Derived from ECG1 and ECG2           |
| Light                 | Light            | Light            | -       | 64                 | -                           | -                                    |
| Manual Pos            | Manual Pos       | Manual Pos       | -       | 64                 | -                           | -                                    |
| Respiratory Rate      | Respiratory Rate | Respiratory Rate | -       | 512                | -                           | -                                    |
| REF                   | -                | Fpz              | -       | -                  | -                           | -                                    |

</details>

### PSG Scoring
Hypopnea events are represented by two different tags in the XML annotation files. Events with the Hypopnea tag are hypopneas with a reduction in airflow between 30% and 50% from baseline levels. Events with the Unsure tag are hypopneas with a reduction in airflow greater than 50% from baseline levels.

If interested in all hypopneas that have a 30% or more reduction in airflow, both event types should be included. If interested in events with greater reduction in airflow (>50%), use those that were labeled with the Unsure tag.

The Unsure tag does not represent uncertainty about the event, but rather was the only custom tag available in the original polysomnography scoring program.

Additional criteria can be applied to limit events based on associated desaturation and/or arousal.

## Data overview

<details>

<summary>Old data documentation</summary>

### Covariate datasets

**[/datasets](:files_path:/datasets)** ([introduction](:pages_path:/dataset-introduction.md)) <br/> Core data from baseline and follow-up (9- and 18-Month) visits.

### Data Collection

The [ABC dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing.

### Structure

The dataset is broken down into `baseline`, `month09`, and `month18` files, containing 49, 43, and 40 records, respectively. The primary subject identifier is [`nsrrid`](https://sleepdata.org/datasets/abc/variables/nsrrid).

### Explanation of treatment arms

Each ABC subject was randomized to bariatric surgery (LGB) or continuous positive airway pressure (CPAP). The assigned arm is represented by the [`rand_treatmentarm`](https://sleepdata.org/datasets/abc/variables/rand_treatmentarm) variable. The meanings of the arms are as follows:

1. Laparoscopic Gastric Banding (LGB)
2. Continuous Positive Airway Pressure (CPAP)

</details>

## Access and usage restrictions
The ABC dataset is only available for non-commercial use.

## Citation and acknowledgement
When using this dataset, please cite the following:

[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: doi.org/10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://doi.org/10.1093/jamia/ocy064)

[Bakker JP, Tavakkoli A, Rueschman M, Wang W, Andrews R, Malhotra A, Owens RL, Anand A, Dudley KA, Patel SR. Gastric Banding Surgery versus Continuous Positive Airway Pressure for Obstructive Sleep Apnea: A Randomized Controlled Trial. Am J Respir Crit Care Med. 2018 Apr 15;197(8):1080-1083. doi: doi.org/10.1164/rccm.201708-1637LE. PMID: 29035093; PMCID: PMC5909166.](https://www.atsjournals.org/doi/10.1164/rccm.201708-1637LE?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed)

Please include the following text in the Acknowledgements:

The Apnea, Bariatric surgery, and CPAP study (ABC Study) was supported by National Institutes of Health grants R01HL106410 and K24HL127307. Philips Respironics donated the CPAP machines and supplies used in the perioperative period for patients undergoing bariatric surgery. The National Sleep Research Resource was supported by the National Heart, Lung, and Blood Institute (R24 HL114473, 75N92019R002).

### Protocols and manuals
- [ABC Manual of Procedures](:files_path:/documentation?f=ABC_Manual_of_Procedures.pdf)

### Equipment
- [Montage and Sampling Rate Information](:pages_path:/montage-and-sampling-rate-information.md)

## Changelog
*July 2018*
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion.

*June 12, 2020*
- Update suggested citation and acknowledgment language

*December 28, 2018*
- Add note about hypopnea event tags to PSG introduction

*July 11, 2018*
- Start fleshing out documentation

## References
- ABC at ClinicalTrials.gov: [ClinicalTrials.gov (NCT01187771)](http://clinicaltrials.gov/ct2/show/NCT01187771)
- NSRR ABC GitHub Data Dictionary: https://github.com/nsrr/abc-data-dictionary
- NSRR ABC GitHub Documentation: https://github.com/nsrr/abc-documentation
