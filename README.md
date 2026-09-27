# Awesome-Electronic-Data-Capture

## Top Electronic Data Capture (EDC) Platform Ecosystem

**Curated list of SaaS products and open-source GitHub projects**  
*Focusing on clinical trial data collection, GCP compliance, electronic Case Report Forms (eCRF), and CDISC standards*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** in the **Electronic Data Capture (EDC)** domain. These tools help clinical research teams, pharmaceutical companies, and CROs capture, manage, and export clinical trial data in compliance with GCP, 21 CFR Part 11, and CDISC standards.

**Examples** include Medidata Rave, Castor EDC, OpenClinica, REDCap, Oracle Clinical One, Clinion, TrialKit, Ennov, DATATRAK, Viedoc, Veeva Vault EDC, ClinCapture, MACRO EDC, Ennov Clinical, IBM Clinical Development, MACRO by Elsevier, and Anju EDC (leaders in this space).

**Open Source Focus**: The EDC domain boasts a **mature open-source ecosystem**, contrasting sharply with many enterprise software categories. **REDCap** is used by 8,378 active partners across 166 countries, serving ~3.8 million users from nearly 8,000 institutions. **OpenClinica** Community Edition and **LibreClinica** provide GCP-compliant EDC capabilities, supporting complete audit trails, electronic signatures, and CDISC ODM-XML exports. This list highlights all major active open-source EDC projects.

Contributions are welcome! Submit a PR to add/update entries. Keep descriptions factual and link to official websites.

## Table of Contents

- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Hosted Platforms

| Name | Description | Pricing / Free Tier |
| --- | --- | --- |
| **[Medidata Rave](https://www.medidata.com/)** | Leading EDC platform in the pharmaceutical industry, widely used for registrational clinical trials. Offers electronic data capture, data management, coding, and CDISC export capabilities, deeply integrated with the Medidata Clinical Cloud ecosystem. | Commercial / Enterprise pricing. No free tier available. |
| **[Castor EDC](https://www.castoredc.com/)** | Lightweight EDC designed for academic and investigator-initiated trials. Provides **Castor Essentials** (entry-level, pay-as-you-go) and **Castor for Impact** (funded research projects). Supports Phase I–IV trials, observational studies, and patient registries with a no-code form builder. Compliance covers 21 CFR Part 11, GDPR, and HIPAA. | **Castor Essentials**: Free tier available for small/non-profit academic studies (up to limited participants/subjects); paid plans on a per-study or per-subject basis. |
| **[OpenClinica](https://www.openclinica.com/)** | World's leading open-source clinical trial software, offering Community Edition (free self-hosted) and Enterprise Edition (commercially hosted). Features cover EDC, ePRO, eCRF, eTMF, and CDMS with full GCP compliance support. | **Community Edition**: Free & open-source (self-hosted). <br>**Enterprise/Cloud**: Subscription based per study/site. |
| **[REDCap](https://projectredcap.org/)** | Research Electronic Data Capture platform created by Vanderbilt University, **free for non-profit institutions via the REDCap Consortium**. As of mid-2026, it serves 8,378 active partners in 166 countries (~3.8 million users across ~8,000 institutions). Supports surveys, data collection, CDISC export, and mobile data capture. | **Free** for non-profit consortium partners (requires joining consortium). Commercial licensing available via Vanderbilt for non-consortium / corporate use. |
| **[Oracle Clinical One](https://www.oracle.com/)** | Cloud-based clinical data management platform providing EDC, data management, and trial management capabilities. Oracle reports CRO Atorus Research configured Oracle Clinical One EDC for a gene therapy study in ~4 weeks. | Commercial / Enterprise pricing. No free tier available. |
| **[Clinion](https://clinion.com/)** | AI-driven EDC and clinical trial management platform. Offers electronic data capture, ePRO, randomization, and trial management, focusing on mid-market and emerging markets. | Commercial pricing (subscription/per-study). Contact vendor for quotes. |
| **[TrialKit](https://www.trialkit.com/)** | Cloud-based clinical research platform providing EDC, ePRO, and eConsent. Known for its flexibility and configurability across web and mobile. | Commercial pricing. Custom quotes per study size and feature requirements. |
| **[Ennov](https://www.ennov.com/)** | EDC module within a regulatory and quality suite. Provides document management, workflow automation, and clinical trial compliance tracking. | Enterprise licensing / Subscription pricing. |
| **[DATATRAK](https://www.datatrak.com/)** | Cloud-based EDC and clinical trial management platform. Offers electronic data capture, randomization, and trial management capabilities. | Commercial subscription pricing. |
| **[Viedoc](https://www.viedoc.com/)** | Scandinavian EDC platform known for its modern, user-friendly interface. Provides electronic data capture, ePRO, and CDISC export. | Commercial pricing based on trial scope and duration. |
| **[Veeva Vault EDC](https://www.veeva.com/)** | EDC module within the Veeva Clinical Suite, integrated with Veeva Vault CDMS. Offers electronic data capture and data management, seamlessly connected to the Veeva ecosystem. | Enterprise subscription pricing. |
| **[ClinCapture](https://www.clincapture.com/)** | Clinically validated open-source EDC software (commercially supported edition). Offers electronic data capture, ePRO modules, CTMS integration, and CDISC conversion. | Free trial / Freemium options depending on study scope; paid commercial support plans. |
| **[MACRO EDC](https://www.elsevier.com/)** | Elsevier's EDC platform. Provides electronic data capture, data management, and CDISC export, supporting cloud or on-premise deployment. | Commercial enterprise licensing. |
| **[IBM Clinical Development](https://www.ibm.com/)** | IBM's clinical data management platform. Offers EDC, data management, and CDISC capabilities suited for large pharmaceutical companies and CROs. | Enterprise commercial pricing. |
| **[Anju EDC](https://www.anjusoftware.com/)** | Clinical data management platform. Provides electronic data capture, ePRO, and trial management, focusing on oncology and rare disease research. | Commercial pricing (per study / annual enterprise). |

## Open-Source GitHub Projects

- **[LibreClinica](https://github.com/reliatec-gmbh/LibreClinica)**  
  Community-driven successor to OpenClinica. Provides all essential features required for GCP-compliant clinical trials: web-based electronic forms (eCRF) with versioning, simple and complex field validation, full audit trails and electronic signatures, double-data entry support, discrepancy notes, and Source Data Verification (SDV), CDISC ODM-XML import, and export to CDISC ODM-XML/TSV/Excel/SPSS/SAS. Supports OpenRosa API backend for integration with the **ODK ecosystem for mobile data capture (e.g., ePRO and eCOA)**. **LGPL-3.0**, Java tech stack (OpenJDK 11, Tomcat 9, PostgreSQL 16). Version 1.4.0 (July 2025). Used by institutions such as the German Cancer Consortium (DKTK), RWTH Aachen University Hospital, and WHO Europe's Childhood Obesity Surveillance Initiative.

- **[clinicedc](https://github.com/clinicedc)**  
  Django-based multi-site longitudinal clinical trial data management framework. Provides a suite of Python modules to build EDC/eSource systems, handling informed consent, scheduled data collection, quality assurance, trial monitoring, reporting, adverse events, clinical event grading, data export, and auditing. Source code is publicly hosted on GitHub, with runnable local demos for recent trials. **GPL-3.0**. Used in NIH-funded trials by Harvard T.H. Chan School of Public Health, Botswana-Harvard AIDS Institute Partnership, London School of Hygiene & Tropical Medicine, and Liverpool School of Tropical Medicine. Contains 119 repositories, including `edc-qol` (EQ-5D quality of life tool) and `edc-he` (health economics model).

- **[OpenDataCapture](https://github.com/DouglasNeuroInformatics/OpenDataCapture)**  
  Open-source electronic data capture platform developed by Douglas NeuroInformatics for managing remote and on-site clinical assessments. Features 98 stars with active updates. Ideal for neuroinformatics research requiring remote patient data collection.

- **[COSMOS](https://github.com/at2e19/SCTU_COSMOS_DQDV_Shiny)**  
  FAIR- and GCP-aligned Clinical Trial Unit infrastructure tailored for academic clinical and multi-omics trial data. Integrates an automated data quality & validation "trust layer" with a relational SQL schema, offering programmatic and interactive data access via an R Shiny application. **GPL-3.0** licensed.

- **[GNU Health](https://github.com/gnuhealth/gnuhealth)**  
  Free/Open-Source Health and Hospital Information System by the GNU Project. Offers modules for hospital management, Electronic Medical Records (EMR), laboratory, pharmacy, and epidemiology. **GPL-3.0**, Python tech stack. **Note**: GNU Health is an HIS (Hospital Information System) tool, not a dedicated EDC tool.

- **[OpenEMR](https://github.com/openemr/openemr)**  
  Most popular open-source electronic health records and medical practice management solution. **ONC Certified** (Ambulatory EHR), version 8.0.0 certified in February 2026. Features include fully integrated EHR, practice management, scheduling, electronic billing, e-prescribing, and patient portal. **GNU GPL**. **Note**: OpenEMR is an EHR/practice management tool, not a dedicated clinical trial EDC.

- **[OpenMRS](https://github.com/openmrs/openmrs-core)**  
  Open-source medical record system designed specifically for resource-constrained environments. Modular architecture with strong HL7/FHIR support. **Note**: OpenMRS is an EMR tool, not a dedicated EDC.

### Other Strong Open-Source Options

- **EDC Dedicated**: **LibreClinica** (OpenClinica successor, GCP compliant), **clinicedc** (Django-based, multi-site longitudinal trials).
- **FAIR Data Infrastructure**: **COSMOS** (FAIR/GCP aligned, interactive access via R Shiny).
- **Remote Data Capture**: **OpenDataCapture** (remote and on-site clinical tool management).
- **Important Distinction**: **GNU Health**, **OpenEMR**, and **OpenMRS** are EHR/EMR/HIS tools, **not dedicated clinical trial EDC tools**. They can be used for clinical data management, but lack EDC-specific functionality (e.g., CDISC ODM export, eCRF versioning, SDV workflows).

**Framework for Building Custom Systems**: Combine **LibreClinica** as the core EDC platform (GCP compliance, CDISC export, ODK integration), **clinicedc** for Django-based multi-site trial frameworks, **COSMOS** for FAIR data warehousing and validation, and **OpenDataCapture** for remote clinical tool management. Add **PostgreSQL** for persistence and the **ODK** ecosystem for mobile data capture.

## How to Contribute

1. Fork the repository.
2. Add/edit entries in `README.md` following the existing format.
3. Include: Name, link, 1–2 sentence description, and whether it is SaaS or Open Source.
4. Submit a PR with a brief note.

If you find this repository useful, please give it a star!

## Disclaimer

- This is a **community-curated** list—it is neither exhaustive nor an endorsement.
- EDC systems handle sensitive clinical trial data; ensure compliance with applicable regulations such as 21 CFR Part 11, GCP, HIPAA, and GDPR.
- **Open-Source Reality**: The EDC space features **mature open-source alternatives**. **REDCap** is the de facto standard for academic research with a massive global user base. **LibreClinica** is an active community successor to OpenClinica, delivering full GCP compliance capabilities. **clinicedc** is production-proven across multiple NIH-funded trials. However, open-source EDCs require institutional IT or data management capacity to deploy, host, and maintain—the inherent trade-off of self-hosting. For large registrational trials requiring vendor hosting, professional services, and validation support, commercial platforms (Medidata, Veeva, Oracle) remain the primary choice.

---

**Built for Clinical Research Coordinators, Data Managers, CRO Tech Teams, and Academic Researchers.**  
Making clinical trial data capture more open, compliant, and accessible.
