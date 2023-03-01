### Public fMRI Dataset



*Functional magnetic resonance imaging (fMRI) is a neuroimaging technique. Its principle is to use magnetic resonance imaging to measure the hemodynamic changes induced by neuronal activity. Because of its non-invasive nature and low radiation exposure, fMRI has been an important part of the functional brain localization field since the 1990s. Currently, fMRI is mainly used in the study of the brain or spinal cord in humans and animals.*

*There are many MRI or fMRI databases that can be searched. For this reason, the editors have browsed the literature to summarize the 4 most widely used databases in the hope that they can help you in your imaging-related scientific work.*

***

**1. OpenfMRI  database**

OpenfMRI is a database based on fMRI datasets, and most of the datasets will be accompanied by literature published using the datasets, and the datasets can be accessed without registration or login, and are very easy to download. The datasets are stored in ASW (Amazon Web Services), and I have personally tested the download speed using the browser default method, which is quite impressive.
The database project is managed by the Portlake Laboratory and the Center for Neurorenewable Sciences at Stanford University. It receives funding from the National Science Foundation, the National Institute on Drug Abuse, and the John Arnold Foundation.

*The database project is located at: www.openfmri.org* 

The database currently contains 95 fMRI (MRI) datasets with a total of 3372 subjects data. Due to new grant support and other reasons, the database is currently not being updated and updated fMRI datasets are submitted to OpenNEURO.

***

**2. OpenNEURO database**

OpenNEURO is a free and open source database mainly for neuroscience data, and its datasets cover MRI, MEG, iEEG, ECoG, ASL and PET, which can be very rich. In the previous database, the editor also introduced that new datasets in OpenfMRI are also submitted to this database, so the number of datasets in this database is so large that even the editor did not imagine it. There are currently 577 case datasets with a total of 19,872 subjects included, and more than 110 datasets were retrieved using the keyword fMRI.

The database project is funded by the same foundation as the OpenfMRI database.

*The database project address: www.openneuro.org* 

Database use recommendations:

> a. To use this database for the first time, a webinar is recommended to learn how to use it.
> Webinar address: https://www.youtube.com/watch?v=FK_c1x1Pilk 
> b. You can search for keywords in the search bar to get the corresponding dataset, such as fMRI, ECoG, etc.
> c. You can submit and manage your own datasets after logging in.

***

**3. fastMRI database**

A project led by the Department of Radiology at New York University School of Medicine and the Center for Advanced Imaging Innovation and Research at NYU Langone Health in collaboration with the Facebook AI Research Center. The project aims to use AI technology to improve the efficiency of MRI scans. The database is divided into knee MRI and brain MRI. the brain MRI database provides T1,T2 and FLAIR data (1.5T and 3T) for 6970 subjects.
*Database URL: https://fastmri.med.nyu.edu/* 

*Database project address: https://fastmri.org/* 

*Project GitHub: https://github.com/facebookresearch/fastMRI/* 



> ***Please note:***
> a. Although it is free and open to use, this database uses the authorization access system, you need to apply for authorization to access and obtain, the database URL has detailed instructions on the authorization application.
> b. Many research papers have been published using this database, so if you need to know more about this database, we recommend reading it. PDF versions of the literature are available at the database project address or GitHub.

***

**4. fcon_1000 and INDI project**

1000 Functional Connectomes Project (fcon_1000) and International Neuroimaging Data-sharing Initiative (INDI). fcon_1000 and INDI projects are primarily aimed at advancing the open sharing of neuroimaging The main purpose of the fcon_1000 and INDI projects is to promote open sharing of neuroimaging data. The founder of the project, Dr. Michael Milham, currently runs a non-profit child psychological assistance organization. Domestic scholars from Professor Zang Yufeng's team at Hangzhou Normal University and a research team from the Imaging Center at Southwest University have also joined the project and contributed a very large number of datasets. The project has several sub-databases with different classifications and all data are also stored using AWS.

*Detailed description of the project's database: http://fcon_1000.projects.nitrc.org/indi/IndiPro.html* 

*Dataset authorization access request: https://www.nitrc.org/project/request.php?group_id=296* 

*(However, the editors have found a way to download it directly and have attached the download address to each example dataset)*


- [ ] 4.1 Simon dataset

The Simon dataset is an MRI and fMRI dataset consisting of 73 adult healthy male subjects aged 29-46 years with several features: acquired from several different sites, using several different MRI scanners, and scanned with several different T1, T2 sequences. The principal investigator of the project is Dr. Simon from the Cervo Brain Center in Canada, and the dataset is shared through the CC BY-SA protocol.

*The dataset project and access address: http://fcon_1000.projects.nitrc.org/indi/retro/SIMON.html* 


- [ ] 4.2 Parkinson's MRI dataset

The T1 and resting state dataset of Parkinson's disease (contributed by Neurocon team and Tao Wu team) was jointly constructed by Beijing Institute of Geriatrics, Xuanwu Hospital, Capital Medical University and Parkinson's Disease Center, Beijing Institute of Brain Diseases, China, which has a total of 47 cases of data and was published in 2017.

*The dataset and project address:* *http://fcon_1000.projects.nitrc.org/indi/retro/parkinsons.html *

- [ ] 4.3 Resting-state fMRI dataset from the Key Laboratory of Cognitive Neuroscience, Beijing Normal University

R-fMRI and DTI imaging data of 180 healthy subjects shared by the State Key Laboratory of Cognitive Neuroscience, Beijing Normal University.

*Dataset and project address:* *http://fcon_1000.projects.nitrc.org/indi/retro/BeijingEnhanced.html*
*Dataset download address: http://fcon_1000.projects.nitrc.org/indi/retro/BeijingEnhanced/* 


- [ ] 4.4 The fMRI Dataset for Children with Attention Deficit Disorder

Data from MPRAGE, R-fMRI and ASL imaging of 68 children with ADHD shared by Professor Victor's team in the Department of Child and Adolescent Psychiatry at New York University Grossman School of Medicine. Professor Victor focuses on the pathogenesis and prognosis of ADHD using brain imaging techniques such as fMRI.

*Dataset and project address: http://fcon_1000.projects.nitrc.org/indi/retro/CUNMET.html* 
*Download the dataset at: http://fcon_1000.projects.nitrc.org/indi/retro/COBRE/*

- [ ] 4.5 Adult resting-state fMRI dataset

Six-minute resting-state fMRI data for 31 adults, also including respiratory and heart rate data.

*Address of the dataset and project: http://fcon_1000.projects.nitrc.org/indi/retro/ClevelandCCF.html*
*The dataset can be downloaded at: http://fcon_1000.projects.nitrc.org/indi/retro/ClevelandCCF/*

- [ ] 4.6 Adult resting-state fMRI dataset

Also an adult resting-state fMRI dataset, this dataset contains data from 321 subjects, a very large sample size.

*Dataset and project address: http://fcon_1000.projects.nitrc.org/indi/retro/MPI.html*
*The dataset can be downloaded at: http://fcon_1000.projects.nitrc.org/indi/retro/MPI*


- [ ] 4.7 Longitudinal fMRI study dataset

This dataset aggregates fMRI datasets obtained from subjects listening to oral stories over a seven-year period (2011-2018). The results of the study were published in 2019.

*The dataset and project address: http://fcon_1000.projects.nitrc.org/indi/retro/Narratives.html*
*The dataset download address is in the text section.*

- [ ] 4.8 Resting-state fMRI dataset of patients undergoing epilepsy surgery

The dataset contains data from 6 patients with what is known in medicine as refractory epilepsy. To localize the causative lesion, the six patients underwent neurosurgery to implant electrodes into the skull. A 5-minute resting-state fMRI scan was performed prior to the electrode implantation procedure.

*Address of the dataset and project: http://fcon_1000.projects.nitrc.org/indi/retro/NorthShoreLIJ.html*
*The dataset can be downloaded at: http://fcon_1000.projects.nitrc.org/indi/retro/NorthShoreLIJ/*

- [ ] 4.9 fMRI dataset of 39 subjects playing video games

Thirty-nine subjects were trained for 20 hours to play the Battlestar Galactica video game while adding the oddball task, and fMRI was scanned to assess the differences in their learning and training processing strategies.

*Dataset and project address: http://fcon_1000.projects.nitrc.org/indi/retro/Train-39.html*
*The dataset can be downloaded at: http://fcon_1000.projects.nitrc.org/indi/retro/TRAIN-39/*

- [ ] 4.10 fMRI dataset for aging-related studies

The Dallas Longevity Study (DLBS) project, focuses on the causes of preservation and decline of cognitive function at different stages of adult life span, with a particular focus on the early stages of healthy brain progression to Alzheimer's disease. The dataset includes 315 DTI MRI and fMRI, as well as 147 PET cases, making the dataset large and diverse.

*The dataset and project address: http://fcon_1000.projects.nitrc.org/indi/retro/dlbs.html*
*The dataset can be downloaded at: http://fcon_1000.projects.nitrc.org/indi/retro/dlbs_content/*

- [ ] 4.11 fMRI dataset for the study of cocaine addiction mechanisms

This dataset contains 6-minute resting-state fMRI data from 29 cocaine dependent individuals and 24 healthy comparison participants.

*The dataset and project address: http://fcon_1000.projects.nitrc.org/indi/retro/nyuCocaine.html*


- [ ] 4.12 Southwestern University multimodal magnetic resonance (mMRI) dataset

A three-and-a-half year longitudinal study of the brain and behavior dataset shared by the Department of Psychology at Southwestern University. mMRI data include resting-state fMRI, DTI, structural images, etc. Notably, numerous publications have been published by related researchers using this dataset.

*The dataset and project address: http://fcon_1000.projects.nitrc.org/indi/retro/southwestuni_qiu_index.html*




#### The End
