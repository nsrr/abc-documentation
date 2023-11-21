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

## Access and usage restrictions
The ABC dataset is only available for non-commercial use.

## Citations and Acknowledgements
When using this dataset, please cite the following:

Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.

Bakker JP, Tavakkoli A, Rueschman M, Wang W, Andrews R, Malhotra A, Owens RL, Anand A, Dudley KA, Patel SR. Gastric Banding Surgery versus Continuous Positive Airway Pressure for Obstructive Sleep Apnea: A Randomized Controlled Trial. Am J Respir Crit Care Med. 2018 Apr 15;197(8):1080-1083. doi: 10.1164/rccm.201708-1637LE. PMID: 29035093; PMCID: PMC5909166.

Please include the following text in the Acknowledgements:

The Apnea, Bariatric surgery, and CPAP study (ABC Study) was supported by National Institutes of Health grants R01HL106410 and K24HL127307. Philips Respironics donated the CPAP machines and supplies used in the perioperative period for patients undergoing bariatric surgery. The National Sleep Research Resource was supported by the National Heart, Lung, and Blood Institute (R24 HL114473, 75N92019R002).
## Protocols and manuals

- [ABC Manual of Procedures](:files_path:/documentation?f=ABC_Manual_of_Procedures.pdf)

## Equipment
- [Montage and Sampling Rate Information](:pages_path:/montage-and-sampling-rate-information.md)

## Changelog
July 2018
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion.

June 12, 2020
- Update suggested citation and acknowledgment language

December 28, 2018
- Add note about hypopnea event tags to PSG introduction

July 11, 2018
- Start fleshing out documentation

## References
- ABC at ClinicalTrials.gov: [ClinicalTrials.gov (NCT01187771)](http://clinicaltrials.gov/ct2/show/NCT01187771)
- NSRR ABC GitHub Data Dictionary: https://github.com/nsrr/abc-data-dictionary
- NSRR ABC GitHub Documentation: https://github.com/nsrr/abc-documentation
