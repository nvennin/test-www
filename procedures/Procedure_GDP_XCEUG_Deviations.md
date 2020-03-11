# Deviations

Item    |   Details
----    |   ----
Purpose | Recording, investigating and assigning corrective actions for deviations.
Departments | Quality
Categories    | GDP
Scope   | Applies to internal and external deviations derived from CMOs and contracted GDP services.

## References and Associated Documents

### References

* [Glossary][QEAIC]
* [Change control][UYNEF]
* [Quality Risk Management][LBHIY]
* [CAPA][YUISV]
* [EudraLex Volume 4 — Good Manufacturing Practice (GMP) guidelines][GMP Guidelines]
* [Good Distribution Practice GDP guidelines 2013/c343/01][GDP Guidelines]

### Associated Documents

None

## Roles

Role     |   Description    |   Who
------   |   --------       |  ----
Requester  | Raises the deviation  | Anyone
Manager |  Approves non-GDP deviations and oversees the process | Quality Manager
Investigator  |  Investigates deviations | Quality Officer
Reviewer | Reviews deviations and CAPA plan | Quality Manager, RP, other stakeholders
Responsible Person | Approves GDP deviations   | Responsible Person
Regulatory | Reviews deviations that impact regulatory filings | Regulatory

## Procedure

### Raising a deviation

A GitHub Issue is opened by the reqested for all deviations and labelled 'DEVIATION', and should be opened as soon as observed.

If the deviation is potentially critical, the Issue is labelled 'CRITICAL' and the @simplepharma/quality team is mentioned in the issue to ensure immediate notification.

The Issue includes the nature and a clear, detailed and factual description of the deviation. It references the impacted product, process, procedure, system and associated document should be included. Any immediate actions taken are also documented in the Issue or the comments.

### Assigning an investigator

The quality team assigns an investigator to the deviation (by assigning the Issue to that individual) under the oversight and responsibility of the Manager.

### Assessing the impact

The Investigator documents the impact of the Deviation,, including any impact on Medicinal Product, regulatory filing, WDA, QMS, validated activity/system, supply chain, third party as applicable. The impact of the Deviation on other products, processes and system is also assessed.

The Deviation is classified based on impact to product Quality and to the patient, and the appropriate Issue label is added. The table below describes the classification of Deviations.

|Classification     |Description                                                                     |
|-------------------|--------------------------------------------------------------------------------|
|Critical           |Any Deviation which has, or potentially could have an impact which could be potentially life threatening or could cause serious risk to health for example a contaminated Medicinal Product that is registered as sterile. |
|Major              |Any Deviation which has, or potentially could have an impact which could create a potential risk of illness or other mistreatment but where the impact would not be considered critical. Any Deviation which could potentially impact upon key document such as regulatory filing. |
|Minor              |Any Deviation which is not likely to pose a hazard to health, but where a departure has occurred from QMS procedures, processes or systems. |

A Risk Assessment should be performed for all Critical and Major Deviations and as required for other deviatons. (See [Quality Risk Management][LBHIY].)

The Investigator also assesses who should be notified of the deviation, including third-parties such as QPs and regulatory bodies.

### CAPA

An investigation is performed to determine root cause or most probable root cause of the Deviation when the root cause is unknown. Tools such as the 5 Whys, Fishbone/Cause and Effect Diagram and Brainstorming may be used to determine root cause. The investigation determines if this Deviation shares a root cause with a previous deviation.

A Corrective and Preventive Actions (CAPA) are raised in accordance with [CAPA][YUISV]. The CAPA is referenced in the Issue's comments.

### Review

The Deviation is reviewed by the Quality Manager, Responsible Person(s) and other relevant parties (Regulatory, Supply Chain). The Quality Manager ensures the relevant people review the Deviation.

The reviewers confirms classification of Deviation is appropriate, reviews impact assessment and risk assessment (if applicable), evaluates investigation thoroughness and outcomes and appropriateness of CAPAs assigned to address the root cause of the Deviation. They comment and approve using the comments function of GitHub Issues.

Quality Manager (for non-GDP Deviations) or RP (for GDP Deviations) perform final approval and close the issue in GitHub. Target is to close Deviations in 30 calendar days.

## Training

Anyone who performs the tasks as outlined in this procedure must be trained in deviations management.

[GMP Guidelines]: https://ec.europa.eu/health/documents/eudralex/vol-4_en]
[GDP Guidelines]: https://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=OJ:C:2013:343:0001:0014:EN:PDF
[GVP Guidelines]: https://www.ema.europa.eu/en/documents/regulatory-procedural-guideline/guideline-good-pharmacovigilance-practices-gvp-module-vi-collection-management-submission-reports_en.pdf
[Directive 2010/84/EU]: https://ec.europa.eu/health/sites/health/files/files/eudralex/vol-1/dir_2010_84/dir_2010_84_en.pdf
[Regulation EU No 1235/2010]: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32010R1235
[AMXWS]: /procedures/Procedure_GDP_AMXWS_Management_of_Standard_Operating_Procedures.md
[XIDEX]: /procedures/Procedure_GDP_XIDEX_Responsible_Person.md
[BWRPX]: /procedures/Procedure_GDP_BWRPX_Documentation_Control.md
[XCEUG]: /procedures/Procedure_GDP_XCEUG_Deviations.md
[UYNEF]: /procedures/Procedure_GDP_UYNEF_Change_Control.md
[OZCFN]: /procedures/Procedure_GDP_OZCFN_Management_Review_And_Monitoring.md
[LBHIY]: /procedures/Procedure_GDP_LBHIY_Quality_Risk_Management.md
[ZWJPR]: /procedures/Procedure_GDP_ZWJPR_Training.md
[VQICE]: /procedures/Procedure_GDP_VQICE_Receipt_Of_Medicinal_Products.md
[AGTXC]: /procedures/Procedure_GDP_AGTXC_Establishing_The_Authority_Of_Suppliers_To_Supply_Medicinal_Products.md
[ZIWKI]: /procedures/Procedure_GDP_ZIWKI_Customer_Complaints.md
[VOZWP]: /procedures/Procedure_GDP_VOZWP_Recall_Procedure.md
[HBQIN]: /procedures/Procedure_GDP_HBQIN_Outsourced_Activities.md
[GMQHI]: /procedures/Procedure_GDP_GMQHI_Self_Inspections.md
[VTOMR]: /procedures/Procedure_GDP_VTOMR_Falsified_Medicinal_Products.md
[BMAXZ]: /procedures/Procedure_GDP_BMAXZ_Medicinal_Product_Returns.md
[YUISV]: /procedures/Procedure_GDP_YUISV_CAPA.md
[QEAIC]: /procedures/Document_QEAIC_Glossary.md
[GGNHM]: /procedures/Procedure_GDP_GGNHM_Reporting_of_Adverse_Events.md
[AGDXV]: /procedures/Procedure_GDP_AGDXV_Serialisation.md
