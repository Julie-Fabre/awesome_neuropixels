# Awesome Neuropixels [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Neuropixels resources, in no particular order. Create a pull request or raise a github issue to add any resources to this list. 

## Contents

<!-- START_TOC -->
* [Community](#community)
* [Neuropixels papers and manuals](#neuropixels-papers-and-manuals)
* [Courses, talks and videos](#courses-talks-and-videos)
* [Probe setup, care and sharpening](#probe-setup-care-and-sharpening)
* [Chronic implants](#chronic-implants)
* [Data acquisition](#data-acquisition)
* [General frameworks](#General-frameworks-that-many-incorporate-of-the-steps-below)
* [Data preprocessing](#data-preprocessing)
* [Spike-sorting](#spike-sorting)
* [Quality control](#quality-control)
* [Classifying cell types](#classifying-cell-types)
* [Tracking cells across days](#tracking-cells-over-days)
* [Loading and plotting data](#loading-and-plotting-data)
* [Trajectory planning and histology](#trajectory-planning-and-histology)

<!-- END_TOC -->

## Community
- [Neuropixels slack](https://app.slack.com/client/T93QUDDCM)

## Neuropixels papers and manuals
- [Neuropixels 1.0](https://www.nature.com/articles/nature24636/), [manual](https://www.neuropixels.org/_files/ugd/832f20_ba7f3e9e639b49809458cf64d76abdcc.pdf)
- [Neuropixels 2.0](https://www.science.org/doi/10.1126/science.abf4588), [manual](https://github.com/Julie-Fabre/awesome-neuropixels/blob/master/Neuropixels%202.0%20User%20Manual%20V1.0.pdf)
- [Neuropixels ultra](https://www.biorxiv.org/content/10.1101/2023.08.23.554527v2)
- [Neuropixels for NHP](https://www.biorxiv.org/content/10.1101/2023.02.01.526664v3)
- [Neuropixels for humans](https://www.nature.com/articles/s41596-023-00871-2)

## Courses, talks and videos
- **2023 October - [UCL Neuropixels Course 2023](https://www.ucl.ac.uk/neuropixels/training/2023-neuropixels-course)**, [youtube videos](https://www.youtube.com/watch?v=epxx_w2mhhg&list=PLfhWmWntvjl4Wi-K9Wx1Wx3WkCqpHnwaQ)
- **2022 October - [UCL Neuropixels Course 2022](https://www.ucl.ac.uk/neuropixels/training/2022-intro-neuropixels-course)**, [youtube videos](https://www.youtube.com/watch?v=koukfLPyPSc&list=PLfhWmWntvjl7fpEDt-Ip8phYETFGUQDXc)
- **2021  October - [UCL Neuropixels Course 2021 ](https://www.ucl.ac.uk/neuropixels/training/2021-neuropixels-course)**, [youtube videos](https://www.youtube.com/watch?v=KBjwNRp41T4&list=PLfhWmWntvjl64ti_a-MzHlwqwEU0ZlALb)
- _2020 April - [UCL Neuropixels Course 2020](https://www.ucl.ac.uk/neuropixels/training/2020-neuropixels-course)_, [youtube videos](https://www.youtube.com/watch?v=5pAI3Rs_GTg&list=PLfhWmWntvjl7kljKozClpjS29DoY8V5pB)
- _2019 April - [UCL Neuropixels Course 2019](http://www.ucl.ac.uk/neuropixels/courses/2019-course)_
- _2018 April - [UCL Neuropixels Course 2018](http://www.ucl.ac.uk/neuropixels/courses/2018-course)_
- _2017 May - [UCL Neuropixels Course 2017](http://www.ucl.ac.uk/neuropixels/courses/2017-course)_

## Probe setup, care and sharpening
- [Sharpening probes](https://github.com/cortex-lab/neuropixels/wiki/Sharpening)
- [Cleaning and caring for probes](https://github.com/cortex-lab/neuropixels/wiki/Probe_care)
- [Slack thread about how to store probes](https://neuropixelsgroup.slack.com/archives/C93JDLKJP/p1699504147935669), and [files for a wall-mounted enclorsure](https://github.com/MarinManuel/NeuropixelsEnclosure)

## Chronic implants 

Recoverable implants:
- Aery Jones implant, Giocomo lab ([protocol](https://open-neuroscience.com/post/chronic_recoverable_neuropixels_in_mice/))
- Apollo (Bimbard & Coen) implant, Carandini/Harris lab ([paper](https://elifesciences.org/reviewed-preprints/98522), [GitHub page](https://github.com/Coen-Lab/chronic-neuropixels))
- Aydin & van Daal, implant, Haesler lab ([paper](https://www.science.org/doi/full/10.1126/science.abf4588), [citation](https://zenodo.org/records/4564136), [GitHub page](https://github.com/nerf-common/chronic-neuropixels2))
- Ghestem implant, Ferraris lab ([paper](https://iopscience.iop.org/article/10.1088/1741-2552/ace218), [GitHub page](https://github.com/INS-PhysioNet/npx-ghestem))
- Juavinett implant, Churchland lab ([paper](https://elifesciences.org/articles/47188), [GitHub page](https://github.com/churchlandlab/ChronicNeuropixels))
- Luo & Bondy implant, Brody lab ([paper](https://elifesciences.org/articles/59716), [GitHub page](https://github.com/Brody-Lab/chronic_neuropixels))
- Melin & Couto implant, Churchland lab ([GitHub page](https://github.com/spkware/chronic_holder))
- van Daal, Aydin & Michon implant, Haesler lab ([paper](https://www.nature.com/articles/s41596-021-00539-9), [GitHub page](https://github.com/nerf-common/chronic-neuropixels-protocol))
- Vöröslakos et al. microdrive implant, Buzsáki lab ([paper](https://elifesciences.org/articles/65859), [Github link](https://buzsakilab.github.io/3d_print_designs/microdrives/microdrives/), [modified version for 2.0 probes](https://github.com/3Dneuro/R2np)).

Non recoverable implants:
- See [Steinmetz et al., 2019](https://www.science.org/doi/10.1126/science.abf4588)
  
## Data acquisition
- [SpikeGLX](https://billkarsh.github.io/SpikeGLX/)
- [Open Ephys GUI](https://open-ephys.org/gui)
- [Synchronizing data streams](https://open-ephys.github.io/gui-docs/Tutorials/Data-Synchronization.html), optional Arduino code for applying external sync pulses [here](https://github.com/cortex-lab/neuropixels/wiki/Synchronization). 
- Generating IMROs and channel maps - via SpikeGLX [video 1](https://vimeo.com/781678605), [video 2](https://vimeo.com/783581937)
- [Some tips to reduce noise](https://github.com/Julie-Fabre/awesome-neuropixels/Some_tips_to_reduce_noise.md)
- [Some tips to seperate shanks from each other](https://github.com/Julie-Fabre/awesome_neuropixels/Some_tips_to_seperate_shanks_from_each_other.md)

## General frameworks that incorporate many of the steps below
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [SpikeInterface](https://github.com/SpikeInterface)
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [Allen Institute pipeline](https://github.com/AllenInstitute/ecephys_spike_sorting), [fork specifically tailored to spikeGLX data](https://github.com/jenniferColonell/ecephys_spike_sorting)

## Data preprocessing
- [Getting a channel map for spike-sorting based on your IMRO (spikeGLX)](https://github.com/jenniferColonell/SGLXMetaToCoords)
- Applying a phase shift to Neuropixels channels (to correct asynchronous sampling across ADCs):
  - details [here](https://billkarsh.github.io/SpikeGLX/help/catgt_tshift/catgt_tshift/)
  - ![icons8-binary-file-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/0715213f-4c33-4ef7-adb4-374e7575c73a)
[code](https://github.com/billkarsh/CatGT)
- Common-average-referencing (gets rid of noise): 
  - ![icons8-binary-file-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/0715213f-4c33-4ef7-adb4-374e7575c73a) [CatGT](https://github.com/billkarsh/CatGT)
  - ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096)
 [CAR](https://github.com/cortex-lab/spikes/blob/master/preprocessing/applyCARtoDat.m)
- Data compression/decompression:
  - ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [compression/decompression](https://github.com/int-brain-lab/mtscomp)
  - ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [decompression](https://github.com/Julie-Fabre/bombcell/blob/master/decompressData/bc_extractCbinData.m)

## Spike-sorting 
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [Kilosort 4](https://github.com/MouseLand/Kilosort), [paper](https://www.nature.com/articles/s41592-024-02232-7)
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [Kilosort 1/2/2.5/3 (archived)](https://github.com/MouseLand/Kilosort/releases), [Kilosort 1 paper](https://www.biorxiv.org/content/10.1101/061481v1)
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [Python port of Kilosort 2.5](https://github.com/int-brain-lab/pykilosort) , [white paper](https://figshare.com/articles/online_resource/Spike_sorting_pipeline_for_the_International_Brain_Laboratory/19705522/3)
- Potential errors (spikes missing in chunks) with Kilosort versions before 09 April 2024, [github thread](https://github.com/MouseLand/Kilosort/issues/594).
  
## Quality control 
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [Bombcell: automated quality control and metrics](https://github.com/Julie-Fabre/bombcell), [wiki](https://github.com/Julie-Fabre/bombcell/wiki), [talk](https://www.youtube.com/watch?v=8Gauba3KzvM&list=PLfhWmWntvjl7kljKozClpjS29DoY8V5pB&index=12) at the annual Neuropixels course about quality control.
- Manual curation GUI: [Phy](https://github.com/cortex-lab/phy), [docs](https://phy.readthedocs.io/en/latest/). Example workflow [here](https://github.com/Julie-Fabre/bombcell/blob/main/manualCurationPhyWorkflow.md).
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) / ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [IBL quality metrics](https://github.com/SteinmetzLab/qualityMetrics)

## Classifying cell types 
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) Striatal and cortical cell types: [Bombcell](https://github.com/Julie-Fabre/bombcell), [wiki](https://github.com/Julie-Fabre/bombcell/wiki) 
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [Cerebellar cell types](https://www.biorxiv.org/content/10.1101/2024.01.30.577845v2) (code not available yet, coming soon!) 
  
## Tracking cells over days
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096)/![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [UnitMatch](https://github.com/EnnyvanBeest/UnitMatch), paper [here](https://www.nature.com/articles/s41592-024-02440-1)
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [Neuron_Tracking](https://github.com/AugustineY07/Neuron_Tracking), paper [here](https://www.biorxiv.org/content/10.1101/2023.08.03.551724v2.full.pdf)

## Loading and plotting data
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [NeuroPyxels](https://github.com/m-beau/NeuroPyxels)
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [Spikes](https://github.com/cortex-lab/spikes)
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [neuropixel-utils](https://github.com/djoshea/neuropixel-utils/)

## Trajectory planning
- 3D trajectory planning tools (
⚠️ Note that the 3D tools below use a (scaled) version of the Allen Atlas, and they disagree with other standard atlases like Franklin & Paxinos. This is because the Allen CCF atlas is not the size of the average mouse brain, and the tilt of the atlas is not leveled at bregma and lambda. To correct for these, scaling and tilt values have been approximated, but they still disagree significantly with the Franklin & Paxinos Atlas. ⚠️ )
  - ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [Neuropixels Trajectory Explorer](https://github.com/petersaj/neuropixels_trajectory_explorer)
  - ![icons8-web-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b0cee380-c778-4889-b6c4-3ebb5bc908cd) [Pinpoint](https://github.com/VirtualBrainLab/Pinpoint)
  - ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [HERBS](https://github.com/Whitlock-Group/HERBS)

- atlases:
  - [Allen Brain Atlases - includes adult mouse, developing mouse, mouse spinal cord, adult human, and developing human](https://atlas.brain-map.org/)
  - [Mouse (adult) Franklin & Paxinos, ed. 2](https://www.researchgate.net/profile/Eva_Troyano_Rodriguez/post/Could_someone_provide_me_with_the_mouse_brain_atlas_by_Paxinos_and_Franklin_please/attachment/59d62d7e79197b807798bc53/AS:350559606460416@1460591331585/download/The+mouse+brain+in+stereotaxic+coordinates.pdf)
  - [Mouse (adult) Allen + Franklin&Paxinos unified Atlas - Chon et al.](https://www.nature.com/articles/s41467-019-13057-w)
  - [Sprague Dawley rat (adult) Waxholm](https://www.nitrc.org/projects/whs-sd-atlas)

## Histology
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) For classical slice-by-slice histology (2D) [AP histology](https://github.com/petersaj/AP_histology)
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) For 3D histology (cleared whole brains, brainsaw-ed brains) [Brainglobe](https://brainglobe.info/index.html)
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [HERBS](https://github.com/Whitlock-Group/HERBS)

  

