# About

The Apnea, Bariatric surgery, and CPAP (ABC) study aimed to assess the role of bariatric (weight loss) surgery as compared to continuous positive airway pressure (CPAP) therapy plus weight loss counseling for the treatment of patients with class II obesity and those who have severe obstructive sleep apnea (OSA).

## Methods

## PSG Collection
PSG signal data were collected using the Compumedics E-Series system (Abbotsford, Victoria, Australia). EDF signal and XML signals were later exported from the Compumedics E-Series system. The raw data is captured by a NONIN Model 3100 Wrist Oximeter.

1. EDF - Signal files in the European Data Format exported from Compumedics Profusion.
2. XML (Profusion) - Annotation files exported from Compumedics Profusion. (Learn more...)
3. XML (NSRR) - Annotation files processed in the EDF Editor and Translator tool.

View the PSG data here: **[/polysomnography](:files_path:/polysomnography)** Overnight polysomnography (PSG) data from baseline and follow-up (9- and 18-Month) visits.

## PSG Scoring
Hypopnea events are represented by two different tags in the XML annotation files. Events with the Hypopnea tag are hypopneas with a reduction in airflow between 30% and 50% from baseline levels. Events with the Unsure tag are hypopneas with a reduction in airflow greater than 50% from baseline levels.

If interested in all hypopneas that have a 30% or more reduction in airflow, both event types should be included. If interested in events with greater reduction in airflow (>50%), use those that were labeled with the Unsure tag.

The Unsure tag does not represent uncertainty about the event, but rather was the only custom tag available in the original polysomnography scoring program.

Additional criteria can be applied to limit events based on associated desaturation and/or arousal.
## Data overview

### Covariate datasets

**[/datasets](:files_path:/datasets)** ([introduction](:pages_path:/dataset-introduction.md)) <br/> Core data from baseline and follow-up (9- and 18-Month) visits.

## Protocols and manuals

- [ABC Manual of Procedures](:files_path:/documentation?f=ABC_Manual_of_Procedures.pdf)

## Equipment
- [Montage and Sampling Rate Information](:pages_path:/montage-and-sampling-rate-information.md)

## Recent Changes

- Find a complete list of changes in the [CHANGELOG.md](:pages_path:/CHANGELOG.md)

## References
- ABC at ClinicalTrials.gov: [ClinicalTrials.gov (NCT01187771)](http://clinicaltrials.gov/ct2/show/NCT01187771)
