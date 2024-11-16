
[![python](https://img.shields.io/badge/Python-3.9-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org) ![user](https://img.shields.io/badge/GoogleColab-grey?style=flat&logo=googlecolab) ![user](https://img.shields.io/badge/Chemodeling-App-yellow?) ![user](https://img.shields.io/badge/Userfriend-1.0-sgreen?) 



## PEÅS: A Platform For Streamline Precision Ensemble Generation
<br /><img align = "center" width="425" alt="focus" src="https://github.com/user-attachments/assets/58f358a2-8aa9-4152-a288-50c60c28d0cd">
<br />
<br />
#
### **Introduction**
PEÅS (**P**recise **E**nsemble **A**utonomous **S**ampling) is an exceptionally user-friendly python based platform for generating experimentally revelant gas phase chemical structures. PEÅS integrates and modulizes two in-house machine learning programs [(S∈∈R)](https://github.com/mitkeng/SEER) and (**S**tate **E**nsemble **E**nergy **R**ecognition) and [(CCSF)](https://github.com/mitkeng/CCS_Focusing) (**C**ollision **C**ross **S**ection **F**ocusing)that function as a charge site (protonation or deprotonation) predictor and an empirical conformation space filter. Both programs were trained on datasets consisting of DFT (Density Functional Theorty) ground truth systems, which experimental vadilities were assessed using ion-mobility mass spectrometry collision cross section. A third module in PEÅS employs Confab for conformation generation, as required for ensemble sampling.

The resulting ensemble produced by PEÅS is ultra filtered in conformational space and energy.

#
### **Hallmark Steps**
<img align = "center" width="1000" alt="focus" src="https://github.com/user-attachments/assets/e29fbdef-6e3f-4f2a-8b43-70602ae1a5a5">

#
### **Benefits**
- Improves modeling success
- Limited user-intervention
- No structural artifact
- Reasonable turnaround time
- Reduces false positives
- Stepwise preliminary results
- User-friendly interface

#
### **Limitations**
Currently, PEÅS only generates a conformation ensemble exclusively for protonated, [M+H]+, or singly deprotonated, [M-H]-, molecular ion species. Protonation or deprotonation is assigned to either a nitrogen atom or an oxygen atom, thus, all other atom types are not supported. Refer to the documentations for the programs (i.e., CCSF, Confab, or S∈∈R) implemented in PEÅS for additional carryover limitations. 

#
### Accessibility
 [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/drive/1zuXFbOpdVfl6mGeSy_ydBIoPKtFji6vu#scrollTo=Ul_OFH_c2jB5) <code style="color : grey">to access the PEÅS platform.</code>
<br />

#
### Acknowledgement 
-   [Merz research group](https://github.com/merzlab) 

-   Quantum mechanical calculations and data used in building the models that are modulized in PEÅS were organically generated through computational resources and services provided by the Institute for Cyber-Enabled Research [(ICER)](https://github.com/MSU-iCER) at Michigan State University.

<br/>
<br/>
