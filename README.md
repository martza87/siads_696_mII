<div align="center">

  <img src="assets/header.jpg" alt="logo" width="300" height="auto" />
  <h1>Predicting Health Care Costs of Grouped ICD-10 Procedures in Medicare Claims Data</h1>
  
  <p>
    As part of the MADS programe, for Milestone II project. Exploring the use of supervised learning to estimate costs for patient by predicting what bundle of procedures they would most likely use to treat their conditions.
  </p>

</div>

<br />

<!-- Badges -->

## Tools

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

<br />

<!-- Table of Contents -->

# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
- [Details on Data](#bookmark_tabs-details-on-data)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)

<!-- About the Project -->

## :star2: About the Project

The Centers for Medicare and Medicaid Services (CMS) is currently working on developing and evaluating alternative payment models to reward clinicians that more effectively deliver value-based care to patients. CMS has announced a new initiative to improve patient outcomes through evidence-based prevention to reduce costs for diseases and conditions. Prior Bundled Payments for Care Improvement (BPCI) models used an acute hospital stay as the start of an episode of care. Our project would use unsupervised learning to create alternative clusters of procedures beyond DRGs. This would allow for clustering of procedures where common comorbidities exist and links between them could be observed as well as looking at if there is compliance with preventative measures. We would use supervised learning to estimate costs for patients by predicting what bundle of procedures they would most likely use to treat their condition(s).

## :bookmark_tabs: Details on Data

Data comes from the [Beneficiary Claims Data API](https://bcda.cms.gov/bcda-data.html) containing patient and claims information. This is a synthetic dataset based on past claims, likely anonymised

- **ExplanationOfBenefit (EOB)** - Stores details for episodes of care, including where and when the service was performed, diagnosis codes, provider, and cost of care.
- **Patient** - Stores enrollees' demographic details and updates to their patient identifiers.
- **Coverage** - Stores enrollees' insurance coverage details, including dual coverage.
- **Claim** - Stores financial and clinical details on professional and institutional claims. This is typically used for treatment payment planning and reimbursement.
- **ClaimResponse** - Stores details about the adjudication status and processing results for a claim, predetermination, or preauthorization.

This is a link to our Google project folder where the raw ndjson files are located:

https://drive.google.com/drive/folders/1lsdKFhpVMF3YG3w7OsNe6j8OGwaVDbSv?usp=sharing

A copy of our final report is also in the folder.

## :handshake: Contact

Author: Adrienne Martz, Martin Ho

Project Link: [Github](https://github.com/martza87/siads_696_mII)

<!-- Acknowledgments -->

## :gem: Acknowledgements

- [Header Image](https://hmdi.com.au/wp-content/uploads/2025/03/image-2.jpeg)
