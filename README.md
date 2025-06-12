# openTEPES

Here you will find everything to install and run openTEPES:
- [openTEPES user guide](https://opentepes.readthedocs.io/en/latest/index.html): these web pages include the following sections:
  - Introduction
  - Electric System Input Data
  - Hydropower System Input Data
  - Hydrogen System Input Data
  - Heat System Input Data
  - Flow-Based Market Coupling Method
  - Output Results
  - Mathematical Formulation
  - Research Projects
  - Publications
  - Download & Installation
  - Questions & Answers (Q&A)
  - Contact Us

- [openTEPES Installation](https://github.com/OM4A-Training-Material/openTEPES-Training-Material/openTEPES_InstallationGuide.pdf): this document contains the openTEPES installation guide
- [openTEPES Summary](https://github.com/OM4A-Training-Material/openTEPES-Training-Material/openTEPES_Summary.pdf): this presentation provides a general overview of the openTEPES features
- [openTEPES Résumé](https://github.com/OM4A-Training-Material/openTEPES-Training-Material/openTEPES_Resume.pdf): this presentation provides a general overview of the openTEPES features in French
- [openTEPES Q&A](https://github.com/OM4A-Training-Material/openTEPES-Training-Material/openTEPES_QuestionsAndAnswers.pdf): this document summarizes a short set of questions and answers that may help you when running openTEPES.

The openTEPES model represents a decision support system for defining the integrated generation, storage, and transmission resource planning (IRP, GEP+SEP+TEP) of a large-scale electric system at the tactical level (i.e., time horizons of 10-20 years), defined as a set of generation, storage, and (electricity, hydrogen, and heat) networks dynamic investment decisions for several future years. The user pre-defines the expansion candidates, so the model determines the optimal decisions among those specified by the user.


## Install openTEPES
We recommend to install miniconda3 wich contains python and other set of packages.

Then install one solver at least.

Then install openTEPES writing this in an anaconda console

- pip install openTEPES

## Run openTEPES
Create your case study adapting one of the several case studies provided with the model in the folder where you installed openTEPES to your system.

To run openTEPES introduce this in an anaconda console

- openTEPES_Main 

then you will be asked to select the folder where the case study is, the name of the case, the solver, results and log information


## 📬 Contact
👉 [Andrés Ramos](andres.ramos@comillas.edu) 