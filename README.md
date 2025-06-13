# ⚡ openTEPES

## 📚 Documentation & Training Material

Here you will find everything you need to install and run **openTEPES**:

- 📖 [**User Guide**](https://opentepes.readthedocs.io/en/latest/index.html): This web manual includes detailed sections on:

  - Introduction
  - Electric, Hydropower, Hydrogen, and Heat System Input Data
  - Flow-Based Market Coupling Method
  - Output Results
  - Mathematical Formulation
  - Research Projects & Publications
  - Download & Installation
  - Questions & Answers (Q&A)
  - Contact Information

- 🛠️ [**Installation Guide (PDF)**](openTEPES_InstallationGuide.pdf)

- 🧾 [**Summary Presentation**](openTEPES_Summary.pdf)

- 🇫🇷 [**Résumé in French**](openTEPES_Resume.pdf)

- ❓ [**Q&A Summary**](openTEPES_QuestionsAndAnswers.pdf)

---

## 🧠 Model Overview

The **openTEPES** model serves as a decision support system for integrated resource planning (IRP), combining:

- Generation Expansion Planning (GEP)
- Storage Expansion Planning (SEP)
- Transmission Expansion Planning (TEP)

It optimizes generation, storage, and transmission investments over tactical time horizons (10–20 years), including electricity, hydrogen, and heat networks. Users predefine candidate projects, and the model identifies optimal investment decisions.

---

## 🛠️ Install openTEPES

To install **openTEPES**, follow these steps:

1. Install [**Miniconda3**](https://docs.conda.io/en/latest/miniconda.html), which includes Python and other essential packages.
2. Install at least one supported solver (e.g., Gurobi, HiGHS).
3. In the Anaconda terminal, install openTEPES by running:

```bash
pip install openTEPES
```

---

## 🚀 How to Run openTEPES

1. Create your custom case study by adapting one of the provided examples (included in the model directory).
2. Open the Anaconda console and run:

```bash
openTEPES_Main
```

3. You will be prompted to:
   - Select the folder containing your case study
   - Name the case
   - Choose the solver
   - Define result and log file outputs

## 🎥 Step-by-step Video Support

You can find all tutorials on <a href="https://www.youtube.com/playlist?list=PLHN93NPePQ1KDpQpxvlpPTeDZPdePdHIL" target="_blank" style="text-decoration: none;">
  <img src="https://cdn.simpleicons.org/youtube/FF0000/16" alt="YouTube" height="16" style="vertical-align: text-bottom; margin-left: 4px;">
</a>

## ❓ Need Help?

Check our [Questions & Answers](docs/faq.md) page for common issues and guidance.

---

## 📬 Contact

👉 For questions or feedback, please refer to the contact section in the [User Guide](https://opentepes.readthedocs.io/en/latest/index.html#contact-us).
