
[![python](https://img.shields.io/badge/Python-3.9-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org) ![user](https://img.shields.io/badge/GoogleColab-grey?style=flat&logo=googlecolab) ![user](https://img.shields.io/badge/Chemodeling-App-yellow?) ![user](https://img.shields.io/badge/Userfriend-1.0-sgreen?) 



## PEÅS: An Application For Precision Ensemble Generation
<br /><img align = "center" width="425" alt="focus" src="https://github.com/user-attachments/assets/58f358a2-8aa9-4152-a288-50c60c28d0cd">


<br />
<br />

#
### **Introduction**
PEÅS (**P**recise **E**nsemble **A**utonomous **S**ampling) is an exceptionally user-friendly python based application for generating experimentally relevant gas phase chemical structures. PEÅS integrates and modulizes two in-house machine learning programs [(S∈∈R)](https://github.com/mitkeng/SEER) (**S**tate **E**nsemble **E**nergy **R**ecognition) and [(CCSF)](https://github.com/mitkeng/CCS_Focusing) (**C**ollision **C**ross **S**ection **F**ocusing) that function as a charge site (protonation or deprotonation) predictor and an empirical conformation space filter, respectively. Both programs were trained on datasets consisting of DFT (Density Functional Theory) ground truth systems, which experimental validities were assessed using ion-mobility mass spectrometry collision cross section. A third module in PEÅS employs Confab for conformation generation, as required for ensemble generation.

The resulting ensemble produced by PEÅS is ultra filtered in conformational space and energy.

#
### **Hallmark Steps**
<img align = "center" width="1435" alt="Screenshot 2024-11-16 at 2 50 08 PM" src="https://github.com/user-attachments/assets/bc6da1d6-94c9-47ec-b346-1ebd3732c9f5">

#
### **User Brief**

To initiate, in the **Seed Structure and Charge Selection** section, a SMILE or an XYZ format file is applicable. For the SMILE option, enter an ID or name in the _molecule_name_ field along with a SMILE string. For the XYZ file option, upload or drop the file into the local directory. Next, fill in the _folder_name_ field (this is where the system input will be temporarily stored) and select a desired ion species from the _charge_mode_ options (i.e., [M-H]- or [M+H]+). Finally, in the **CCS Focusing** section, enter a reference CCS value in the _Experimental_CCS_ field. 

In completion of job, ensemble(s) generated will be converted to a zip file and automatically downloaded. Additionally, accessory files containing run details and preliminary results are also avaiable for user's discretion.

#
### **Application Benefits**
- Improves modeling success
- Limited user-intervention
- No structural artifact
- Reasonable turnaround time
- Reduces false positives
- Stepwise preliminary results
- User-friendly interface
- Work volume reduction

#
### **Limitations**
Currently, PEÅS only generates a conformation ensemble exclusively for protonated, [M+H]+, or singly deprotonated, [M-H]-, molecular ion species. Protonation or deprotonation is assigned to either a nitrogen atom or an oxygen atom, thus, all other atom types are not supported. Refer to the documentations for the programs (i.e., CCSF, Confab, or S∈∈R) implemented in PEÅS for additional carryover limitations. 

#
### Accessibility
 [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">]() <code style="color : grey">access to the PEÅS platform is pending publication.</code>
<br />

#
### Acknowledgement 
-   [Merz research group](https://github.com/merzlab) 

-   Quantum mechanical calculations and data used in building the models that are modulized in PEÅS were organically generated with the aid computational resources and services provided by the Institute for Cyber-Enabled Research [(ICER)](https://github.com/MSU-iCER) at Michigan State University.

<br/>
