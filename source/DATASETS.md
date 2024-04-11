# Datasets

## BIDS

All functional and anatomical data has been formatted in [BIDS](https://bids.neuroimaging.io/), for more information visit the Brain Imaging Data Structure documentation [site](https://bids-specification.readthedocs.io/en/stable/).
Some of the files do not follow the main BIDS convention:
- Anatomical sequences with multiple contrasts are following [BEP001](https://bids.neuroimaging.io/bep001).

Note that BIDS session names have no meaning apart from being data acquired in the same session. The number of runs, the tasks and their order within each session will not match from one participant to another. Note that a few session indices are skipped if the whole session was discarded for various scanning issues.

## Coventure

The `Coventure` dataset is a 5 year longitudinal ...

:::{important}
Some variables are transformed from existing raw variables. 
:::

### Participants

`<Description of sample demographics>`

Exclusion criteria included ... .

## Proventure

The `Proventure` dataset ...


:::{important}
Some variables are transformed from existing raw variables. 
:::

### Participants

`<Description of sample demographics>`

Exclusion criteria included visual or auditory impairments that would prevent participants from seeing and/or hearing stimuli in the scanner and major psychiatric or neurological problems. Standard exclusion criteria for MRI and MEG were also applied. Lastly, given that stimuli and instructions are presented in either English or French, all participants had to identify their language of choice.


## Neuroventure

The `Neuroventure` dataset is a 5 year longitudinal neuroimaging dataset, accompanied by behavioral and cognitive information acquired at each year. Participant behavioral information is acquired at each of the 5 years. The following tasks are described below

:::{important}
Some variables are transformed from existing raw variables. 
:::

### Participants

`<Description of sample demographics>`

Exclusion criteria included visual or auditory impairments that would prevent participants from seeing and/or hearing stimuli in the scanner and major psychiatric or neurological problems. Standard exclusion criteria for MRI and MEG were also applied. Lastly, given that stimuli and instructions are presented in either English or French, all participants had to identify their language of choice.


### anat

The anatomical dataset includes longitudinal anatomical images of the brain acquired 3 times over the 5 year span of the study. The primary intended use of this dataset is to ... . Many quantitative measures of brain structure can also be derived and included in analyses, such as `<types of anatomically derived metrics>`.

The MRI sequences are described in more detailed in [](Brain_anatomical_sequences), including pdfs of the Siemens exam cards.

All images covering the face were anonymized by zeroing the data in the face, teeth and ears regions with a custom mask warped from the MNI space based on a linear registration of the T1w brain MRI series. This defacing script is available [here](https://bokenlink.com).


### Stop Signal Task fMRI

The `Stop Signal Task` is a functional MRI task where the participant ...

:::{important}
Notes on Stop-Signal Task: 
Due to a `<enter type of error that results in bad files>` . Choice is left to the user whether to exclude the corresponding fMRI volumes or not for their analysis.
:::

### MID Task fMRI

The `MID Task` (Monetary Incentive Delay) is a functional MRI task where the participant ... The structure of the task is as follows:
 * `Anticipation` corresponded to the phase of the trial where the participant receives information on ...

:::{important}
Notes on MID Task: 
Due to a `<enter type of error that results in bad files>` . Choice is left to the user whether to exclude the corresponding fMRI volumes or not for their analysis.
:::

