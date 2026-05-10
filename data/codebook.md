# Codebook

## Coding scale

Each selected concept was coded using the following scale:

- `0` – Absent: the concept was not found in the reviewed documents.
- `1` – Indirect or implicit: the concept is implied by a technical element, but not explicitly named.
- `2` – Explicit technical mention: the concept is explicitly mentioned, but not formulated as a cybersecurity requirement.
- `3` – Explicit cybersecurity requirement: the concept is explicitly connected to security, risk management, supplier obligations or contractual cybersecurity governance.

## Main variables

- `Record_ID` – stable internal identifier of the procurement record.
- `Country` – country of the procurement source.
- `Procurement_Platform` – source platform, e.g. NEN, TenderNed, Find a Tender.
- `Platform_Tender_ID` – tender identifier used by the source platform.
- `Master_Tender_Name` – harmonised English title used for analysis.
- `Contracting_Authority` – public authority or organisation responsible for the procurement.
- `Publication_Year` – year of publication.
- `Procurement_Type` – broad type of procurement.
- `Vehicle_Context` – explanation of the vehicle-related or fleet-related context.
- `Document_Completeness` – note on whether the reviewed documentation was complete, partial, redacted or otherwise limited.
- `Explicit_CV_Cybersecurity_Code` – whether connected-vehicle cybersecurity was explicitly visible.
- `Digital_Exposure_Code` – degree of visible digital, diagnostic, localisation, software or communication exposure.
- `Overall_Finding_Class` – interpretative classification of the procurement record.
