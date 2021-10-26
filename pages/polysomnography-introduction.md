# Polysomnography introduction

Patients underwent attended polysomnography (PSG) using the Compumedics E-Series (Abbotsford, Victoria Australia).

Notes:

- [Montage and Sampling Rate Information](:pages_path:/montage-and-sampling-rate-information.md)

## Signal and annotation files

[Raw polysomnography data](:files_path:/polysomnography) are available for ABC participants at baseline and at follow-up. Each recording has a signal file (.EDF) and two versions of the event scoring and epoch staging annotations (.XML).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from Compumedics Profusion.
2. **[XML (Profusion)](:files_path:/polysomnography/annotations-events-profusion)** - Annotation files exported from Compumedics Profusion. ([Learn more...](https://github.com/nsrr/edf-editor-translator/wiki/Compumedics-Annotation-Format))
3. **[XML (NSRR)](:files_path:/polysomnography/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://github.com/nsrr/edf-editor-translator) tool.

NSRR XML files can be overlaid onto EDF signal files using the [EDF Viewer tool](https://github.com/nsrr/edf-viewer). For more information about the XML translation (mapping) process, review the files available on the [EDF Editor and Translator Releases page](https://github.com/nsrr/edf-editor-translator/releases).

## Hypopnea event tags

Hypopnea events are represented by two different tags in the XML annotation files. Events with the `Hypopnea` tag are hypopneas with a reduction in airflow between 30% and 50% from baseline levels. Events with the `Unsure` tag are hypopneas with a reduction in airflow greater than 50% from baseline levels.

If interested in all hypopneas that have a 30% or more reduction in airflow, both event types should be included. If interested in events with greater reduction in airflow (>50%), use those that were labeled with the `Unsure` tag.

The `Unsure` tag **does not represent uncertainty about the event**, but rather was the only custom tag available in the original polysomnography scoring program.

Additional criteria can be applied to limit events based on associated desaturation and/or arousal.

## Known issues

- None at this time.

## History / changelog

*July 2018*
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
