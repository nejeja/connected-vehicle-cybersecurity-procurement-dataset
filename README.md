# Connected Vehicle Cybersecurity in Public Procurement Dataset

This repository contains the dataset and supporting materials for the article:

**Connected Vehicles as Targets of AI-Enabled Hybrid Threats: Cybersecurity and Regulatory Implications for Public Institutions**

The study examines whether cybersecurity requirements related to connected vehicles are visible in public procurement documentation. The core Czech sample consists of 41 records from the National Electronic Tool (NEN) covering vehicle-related procurements from 2018 to 2026, especially in the context of state administration and functions relevant to the Integrated Rescue System.

The dataset records whether procurement documentation contains explicit or indirect references to selected cybersecurity-relevant concepts, including cybersecurity, vulnerabilities, software updates, OTA updates, telematics, remote diagnostics, remote access, cloud services, APIs, GPS, location data, operational data, mobile applications, UNECE R155/R156, CSMS/SUMS, incidents, supplier risk, data deletion and service deactivation.

## Repository contents

- `data/unified_coding_table.xlsx` – main coding table.
- `data/unified_coding_table.csv` – machine-readable version of the coding table.
- `data/codebook.md` – explanation of coding categories and variables.
- `documents/*/source_links.csv` – list of reviewed public procurement sources and document links.
- `article/` – article manuscript or author version.
- `figures/` – figures used in the article.

## Methodological note

The dataset is based on publicly available procurement documentation. The coding reflects only what was visible in the reviewed documents. Absence of a term or requirement in the dataset does not prove that the contracting authority or supplier did not address the issue elsewhere. It only means that the requirement was not visible in the publicly reviewed documentation.

Some procurement records contained partially redacted, anonymised, unreadable or otherwise incomplete technical annexes. These cases are treated as limitations of observability, not as evidence of absence.

## Citation

If you use this dataset, please cite:

Nejedlý, J. (2026). *Dataset of public procurement procedures related to vehicles of public administration and IZS-relevant functions in 2018–2026*. GitHub repository.

## Author

Mgr. Jan Nejedlý  
Police Academy of the Czech Republic in Prague  
Information Technology Department

## License

The original dataset and coding are released under the license specified in this repository. Third-party procurement documents remain subject to their original terms and are referenced only by source links unless explicitly included.
