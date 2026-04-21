# Monetary Policy Statement Database (MPSD)

[![Version](https://img.shields.io/badge/version-v0.1%20Beta-blue)](https://github.com/CentralBankTexts/monetary-policy-statement-database)
[![Data License: CC BY-NC 4.0](https://img.shields.io/badge/Data%20License-CC%20BY--NC%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Code License: MIT](https://img.shields.io/badge/Code%20License-MIT-green)](https://opensource.org/licenses/MIT)
[![DOI](https://img.shields.io/badge/DOI-IFC%20Bulletin%2067-orange)](https://www.bis.org/ifc/publ/ifcb67_14.pdf)

The Monetary Policy Statement Database (MPSD) is a comprehensive collection of central bank communications designed for research on global financial conditions and monetary policy transmission. It provides a standardized, machine-readable dataset of policy statements from major central banks worldwide.

* **Version:** v0.1 (Beta Release)
* **Date:** March 2026
* **Status:** Preliminary release. Future updates may modify structure and content.

---

## Table of Contents

- [Access Policy](#access-policy)
- [Database Features](#database-features)
- [Future Updates](#future-updates)
- [Key Research Findings](#key-research-findings)
- [Citation](#citation)
- [License](#license)
- [Contact](#contact)

---

## Access Policy

The MPSD is a **semi-public resource**. This is a beta (early access) release; the full version will be released upon journal publication. To access the dataset and accompanying codebase, please follow these steps:

1. **Complete the Sign-up Form:** Fill out the [Official Registration Form](https://forms.gle/NkbDNdzvYwFrSpSR6) to provide your name, affiliation, and research intent.
2. **Provide GitHub Username:** Ensure your GitHub handle is included correctly in the form.
3. **Wait for Authorization:** Once your request is processed, your GitHub account will be granted access to this repository.

> **Note:** Access is granted for academic research purposes only.

## Database Features

* **Scope:** 6,693 statements from 51 central banks.
* **Timeframe:** 1990 to 2024.
* **Methodology:** Advanced pipeline combining standard NLP preprocessing with Large Language Model (LLM) tools for aspect-based sentiment and question answering.
* **Reproducibility:** Includes full codebase for cross-country analysis and indicator generation.

## Future Updates

The database is actively maintained to ensure it remains a relevant tool for the research community:

* **Update Frequency:** Data is refreshed on a quarterly or semi-annual basis.
* **Expansion:** The list of jurisdictions is continuously growing, with 57 countries currently in the expansion pipeline.

## Key Research Findings

* **Communication Trends:** Policy statements have increased in length since the 2008 Global Financial Crisis, with modest improvements in readability.
* **Global Synchronization:** Inflation references show significant comovement across countries during global inflation episodes.
* **Sentiment Impact:** LLM-derived sentiment indicators suggest that central bank communication can predict the Global Financial Cycle rather than merely reacting to it.

## Citation

If you use this database or the associated methodology in your research, please cite the following research paper:

> Baird, C., Benchimol, J., Vyshnevska, V., Sohn, W., & Vyshnevskyi, I. (2026). The Monetary Policy Statement Database. In *Data Science in Central Banking*, IFC Bulletin No. 67, Chapter 14. Bank for International Settlements.
> @incollection{BairdBenchimolVyshnevskaSohnVyshnevskyi2026a, author={Baird, Cory and Benchimol, Jonathan and Vyshnevska, Vira and Sohn, Wook and Vyshnevskyi, Iegor}, editor={{Bank for International Settlements}}, title={{The Monetary Policy Statement Database}}, booktitle={Data Science in Central Banking}, publisher={Bank for International Settlements}, year={2026}, volume={67}, series={IFC Bulletins chapters}}

Detailed documentation and technical specifications can be found in the [BIS IFC Bulletin No 67](https://www.bis.org/ifc/publ/ifcb67_14.pdf).

*Use of this dataset implies agreement to cite the above reference in any resulting research.*

## License

* **Data:** Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Use is permitted for academic research only; commercial use is prohibited.
* **Code:** Licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

For questions, bug reports, or access issues, please open a [GitHub Issue](https://github.com/CentralBankTexts/monetary-policy-statement-database/issues).
