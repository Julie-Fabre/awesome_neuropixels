# Awesome Neuropixels [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Neuropixels resources, in no particular order. Create a pull request or raise a github issue to add any resources to this list. 

# Contents

<!-- START_TOC -->

* [Contents](#contents)
* [Data acquisition](#data_acquisition)
* [Data preprocessing](#data_preprocessing)
* [Spike-sorting](#spike_sorting)
* [Quality control](#quality_control)
* [Loading and plotting data](#loading_and_plotting_data)
* [Trajectory planning and histology](#trajectory_planning_and_histology)
* [General frameworks](#general_frameworks)
* [Courses and talks](#courses_and_talks)


<!-- END_TOC -->
# Community
- [Neuropixels slack](https://app.slack.com/client/T93QUDDCM)

# Neuropixels papers 
- [Neuropixels 1.0](https://www.nature.com/articles/nature24636/)
- [Neuropixels 2.0](https://www.science.org/doi/10.1126/science.abf4588)
- [Neuropixels ultra](https://www.biorxiv.org/content/10.1101/2023.08.23.554527v2)
- [Neuropixels for humans](https://www.nature.com/articles/s41596-023-00871-2)

# Data acquisition
- [SpikeGLX](https://github.com/billkarsh/SpikeGLX)
- [Open Ephys](https://github.com/open-ephys)
- [Aligning channels to each other](https://open-ephys.github.io/gui-docs/Tutorials/Data-Synchronization.html), arduino code [here](https://github.com/cortex-lab/neuropixels/wiki/Synchronization). 

# Data preprocessing
- Aligning Neuropixels channels to each other:
  - details [here](https://billkarsh.github.io/SpikeGLX/help/catgt_tshift/catgt_tshift/)
  - ![icons8-binary-file-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/0715213f-4c33-4ef7-adb4-374e7575c73a)
[code](https://github.com/billkarsh/CatGT)
- Common-average-referencing (gets rid of noise): 
  - ![icons8-binary-file-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/0715213f-4c33-4ef7-adb4-374e7575c73a) https://github.com/billkarsh/CatGT
  - ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096)
 https://github.com/cortex-lab/spikes/blob/master/preprocessing/applyCARtoDat.m
- Data compression/decompression:
  - ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [compression/decompression](https://github.com/int-brain-lab/mtscomp)
  - ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [decompression](https://github.com/Julie-Fabre/bombcell/blob/master/decompressData/bc_extractCbinData.m)

# Spike-sorting 
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [Kilosort 2/2.5/3](https://github.com/MouseLand/Kilosort)
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [Python port of Kilosort 2.5](https://github.com/int-brain-lab/pykilosort) , [white paper](https://figshare.com/articles/online_resource/Spike_sorting_pipeline_for_the_International_Brain_Laboratory/19705522/3)
  
# Quality control 
- Manual curation GUI: [Phy](https://github.com/cortex-lab/phy), [docs](https://phy.readthedocs.io/en/latest/)
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [Quality metrics](https://github.com/Julie-Fabre/bombcell), [wiki](https://github.com/Julie-Fabre/bombcell/wiki) 
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) / ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [IBL quality metrics](https://github.com/SteinmetzLab/qualityMetrics)
  
# Loading and plotting data
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [NeuroPyxels](https://github.com/m-beau/NeuroPyxels)
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [Spikes](https://github.com/cortex-lab/spikes)

# Trajectory planning
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) https://github.com/petersaj/neuropixels_trajectory_explorer
- ![icons8-web-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b0cee380-c778-4889-b6c4-3ebb5bc908cd) [Pinpoint](https://github.com/VirtualBrainLab/Pinpoint)
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [HERBS](https://github.com/Whitlock-Group/HERBS)

# Histology
- ![icons8-matlab-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/1a18a394-f415-445e-9519-44787ce09096) [HERBS](https://github.com/Whitlock-Group/HERBS)
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [Brainglobe](https://brainglobe.info/index.html)
  
# General frameworks that incorporate many of these steps
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [SpikeInterface](https://github.com/SpikeInterface)
- ![icons8-python-20](https://github.com/Julie-Fabre/awesome-neuropixels/assets/29582008/b80293ba-3ab1-4b9c-89c5-16a329bcb932) [Allen Institute pipeline](https://github.com/AllenInstitute/ecephys_spike_sorting), [fork specifically tailored to spikeGLX data](https://github.com/jenniferColonell/ecephys_spike_sorting)

# Courses and talks 
- **Ongoing: 2023 October - UCL Neuropixels Course 2023: [more information and signup](https://www.ucl.ac.uk/neuropixels/training/2023-neuropixels-course)**
- **2022 October - [UCL Neuropixels Course 2022](https://www.ucl.ac.uk/neuropixels/training/2022-intro-neuropixels-course)**
- **2021 October - [UCL Neuropixels Course 2021](https://www.ucl.ac.uk/neuropixels/training/2021-neuropixels-course)**
- _2020 July - University of Strathclyde_
- _2020 June - Neuropixels Workshop at the Allen Institute for Brain Science_
- _2020 April - [UCL Neuropixels Course 2020](https://www.ucl.ac.uk/neuropixels/training/2020-neuropixels-course)_
- _2019 July - FENS Cajal "Interacting With Neural Circuits"_
- _2019 June - Neuropixels Workshop at the Allen Institute for Brain Science_
- _2019 May - [Paris Neuro](http://parisneuro.ovh/)_
- _2019 April - [UCL Neuropixels Course 2019](http://www.ucl.ac.uk/neuropixels/courses/2019-course)_
- _2018 October - FENS Cajal "Linking Neural Circuits and Behavior"_
- _2018 May - [Paris Neuro](http://parisneuro.ovh/)_
- _2018 April - [UCL Neuropixels Course 2018](http://www.ucl.ac.uk/neuropixels/courses/2018-course)_
- _2017 July - FENS Cajal "Interacting With Neural Circuits"_
- _2017 May - [UCL Neuropixels Course 2017](http://www.ucl.ac.uk/neuropixels/courses/2017-course)_
