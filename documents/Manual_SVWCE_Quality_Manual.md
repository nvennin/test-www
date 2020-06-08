# QUALITY MANUAL  
  
## HEADER
   
|Item          |Details                                                                                       | 
|--------------|-------------------------------------------------------------------------------------------| 
|Purpose       |Detailing the Quality Management System (QMS) and activities applicable to the company
|Department    |Quality                                                                                    |   
|Categorie     |GDP                                                                                        | 

## LICENSES AND AUTHORISATIONS

Ths Simple Pharma Company hold the following licences:

WDA issued by the HPRA: W12691/00001 (draft authorization number, not granted).

## QUALITY MANAGEMENT SYSTEM (QMS)

**The QMS comprises:**

* Business structure with defined roles & responsibilities
* Systems and processes
* Procedural documents
* Personnel including their training and development needs
* Management of documentation

**The QMS is managed through:**

* Quality Risk Management
* Training on Standard Operating Procedures (SOPs) and relevant Work Instructions (WI)
* Self—inspection of systems and processes
* Change control
* Deviations
* Supplier approval

**The QMS is improved by:**

* Regular review by the Management
* CAPAs
* Customer feedback
* Employee feedback

### Quality Management Review

Those are annual meetings with senior management to review the status of quality, level of compliance and identify areas for improvement.
The complete process is explained in the SOP for GXP Quality [Management Review and monitoring][OZCFN].

### Product Quality Review 

PQR’s are compiled by the relevant Contract Manufacturing Organisation (CMO) and/or Contract Packaging Organisation (CPO). The company review and assess these reports to determine if further / follow up actions are required.
The complete process is explained in the SOP for GXP Quality [Management Review and monitoring][OZCFN].

### Quality Risk Management (QRM)

The company apply Risk Management both proactively by regular assessment of business risks, with routine activities and when considering changes and retrospectively in response to quality incidents or non-conformances.
The complete process is explained in the SOP for GXP Quality [Management Review and monitoring][OZCFN].

### Release Procedure of Finished Products

Batch certification is performed either by the finished product manufacturer or a third—party supplier under their Manufacturers / Importation Authorisations (MIA) in accordance with the product registrations (MA’s) and as defined in QTA’s. In—market batch disposition is performed once batches arrive in the intended territories to ensure the applicable storage conditions have been maintained throughout the transportation. Responsibility for in—market batch disposition may be delegated to local distributors or pre-wholesalers as per QTA’s. The full process is explained in the SOP for [In-Market Batch Disposition][VQICE].

## COMPUTERIZED SYSTEMS

Simple Pharma uses GitHub to manage its QMS. All files are text files using the Markdown format/

### Version Control (Repositories and Branches)

GitHub provides version control capabilities through the management *branches* within a *repository*.

A *repository* is a set of documents that are grouped logically together. Simple Pharma's QMS is contained in a single repository, accessible at [github.com/simplopharma/qms].

A *repository* has multiple *branches*. Each *branch* is a version of the documents contained in the repository. The in-force, approved, documents are contained in the `master` branch.

### Pull Requests

While any user of the system is free to create new branches, any modification to the `master` branch is subject to the quality team's review and approval. Furthermore, any changes to any GDP file have to be reviewed by the RP. GDP files are contain `_GDP_` in their file name.

This validation is done through `pull requests`, which are formal requests by a user to merge modifications made in a given branch into another branch.

We parametrized GitHub to prevent direct modifications to the `master` branch. They  have to be processed through a pull request, approved by the relevant persons as described above.

The pull request process allows for users to comment and ask questions, as required, documenting the rationale for changes being submitted.

### Audit trail

All changes made to individual files are traceable back to individual pull requests, and even to individual changes submitted by users. 

### Issues

In lieu of individual trackers, we favor the use of GitHub Issues to track quality actions, such as Change Requests, Checks on suppliers and customers, major changes to controlled documents, etc. Minor changes to controlled documents are handled directly through the change request process that provides full traceability.

Using GitHub Issues to track quality actions provides transparency on processes, and centralizes all documents in one place, while providing flexibility and auditability.

SOPs define the labels to apply to each Issue as a function of requirement. For example, a change request will be labelled 'CHANGE REQUEST'.

### Markdown

This [guide](https://guides.github.com/features/mastering-markdown/) provides an overview of the Markdown syntax. 

## PERSONNEL

### GxP Training

GXP training covers all relevant aspects of Good Manufacturing Practice (GMP), Good Distribution Practice (GDP) and Good Pharmacovigilance Practice (GVP) training for personnel relevant to an individual’s job role.
All applicable new joiners receive training and assessment against approved GDP and GVP training courses when they join. Refreshertraining is conducted regularly.
The complete process is explained in the SOP for [Training][ZWJPR].

### Job Specific / SOP Training

All relevant employees need to receive the appropriate training to fulfil their roles. Specifically, SOP training is performed through reading the SOPs (available freely to all employees on the internet). Employees are requested to read the SOPs, ask their manager and the quality manager any questions they have and post ’Read and Understood’ acknowledgement statements on the QMS's GitHub Issues.

Non GXP/SOP training specific to an employee’s role are coordinated and managed by Human Resources or the appropriate line manager.
The complete process is explained in the SOP for [Training][ZWJPR].

### Job Descriptions

The roles of all key staff is defined in a Job Description which is updated as roles evolve or change. Deputies for key roles, where applicable, are defined within Job Descriptions.

### Use of Consultants

The company does not use consultants to perform key duties.

## DOCUMENTATION

### Standard Operating Procedures (SOPs), Work Instructions (WIs) and Controlled Forms

All quality documents are managed 
SOP’s are written by the subject matter experts. All GXP procedures are approved by the Quality Team.
Changes to SOP's are managed through a Document Change Request. Access to SOP’s, WI’s and controlled forms is controlled with GitHub's version control functionalities. Changes to all GDP SOPs are subject to the RP's review and approval.

The complete process is explained in the SOPs for [Management of Standard Operating Procedures][AMXWS].

### Good Documentation Practice and Retention of Documents

Original copies of manufacturing, packing, analytical and distribution records are maintained by the contract service providers as defined in the applicable QTA’s. Electronic copies of these documents received for review and release are saved in the Egnyte system by the Quality Unit.
The complete process is explained in the SOP for Good Documentation Practice and Data Integrity.

## Serialisation

Responsibility for compliance with the EU Falsified Medicines Directive and other serialization requirements set by local regulations is defined and agreed with product suppliers as per individual QTAs.

The company does not have an established serialization setup as of today. 

## QUALITY CONTROL

All testing activities are either the agreed responsibility of finished product manufacturer or approved contract laboratories. Specific roles and responsibilities about quality control are outlined in individual QTAs. The complete process is explained in the SOP for [Outsourced Services][HBQIN].

## GxP OUTSOURCED ACTIVITIES

All manufacturing, testing and distribution activities are contracted to approved suppliers based on the following attributes.

### Quality Technical Agreements (QTAs)

All service providers who deal directly with the company must have approved QTA’s in place. This includes finished product manufacturing sites, primary distribution sites and logistic providers. The QTA defines the specific responsibilities of each party in relation to all relevant activities. In particular, it ensures the adherence of each party to GMP and GDP (as appropriate) and ensures the Qualified Person (QP) releasing each batch is assured of acceptable quality standards. The Quality Unit is responsible for the preparation, review, approval, issue and control of QTAs. The complete process is explained in the SOP for [Outsourced Services][HBQIN].

### Auditing External Suppliers

GMP and GDP suppliers are audited according to a defined schedule. All finished product manufacturers, primary distributors and logistics providers are audited with an on—site presence or approved contract auditors. Risk assessments of suppliers determines the audit frequency. The responsibility for conducting audits of API suppliers is defined in QTA's with respective finished product manufacturers. The complete process is explained in the SOP for [Outsourced Services][HBQIN].

## QUALITY ASSURANCE

### Deviation Management

All internal deviations and deviations classified as Major or Critical by third party providers are logged into the Deviation management system for investigation, risk assessment and assignment of CAPA’s. The complete process is explained in the SOP for [Deviations][XCEUG].

### Change Control

All changes identified internally or communicated by external sources impacting Theramex products and processes; related to GMP, GDP and GVP activities are logged into the change control system. The changes are approved or rejected after determining the feasibility as well as need for the change. Changes are impact and risk assessed by relevant departments and actions are assigned to different individuals based on the suggested actions. The complete process is explained in the SOP for [Change Management][UYNEF]. New Product Introductions are managed via the change control process.

### Product Quality Complaints

All staff are trained to immediately report all potential complaints and adverse events. Quality related complaints are notified to quality and logged into the complaints system. All complaints are assessed, classified and investigated where required. Any need for market action is considered. The complete process is explained in the SOP for [Product Quality Complaints][GGNHM].

### Product Recall

All product recalls or potential product recalls are immediately notified to the appropriate regulatory body, releasing QP, RP, QPPV and the Recall Committee. Distribution history is requested from primary distributors and reports including stock reconciliation are written and approved. Mock recalls are conducted at least annually to test the recall procedure, unless a product recall has been conducted in that timeframe. The complete process is explained in the SOP for [Medicinal Product Recalls][VOZWP].

## SELF INSPECTION

An annual audit schedule is issued and approved each calendar year. All relevant areas of GxP regulations are audited. The high-level scope of each audit is defined on the audit schedule. All audits are written up using approved report templates. Any non-conformances are categorised (critical, major or other) and are detailed in the report and tracked through appropriate CAPA. Auditors are defined as independent as is practically possible of the subject matter being inspected. Reports and CAPA plans are sent to the Responsible Person for all GDP related self-inspections.

The complete process is defined in SOP for [Self-Inspection][GMQHI].

## DISTRIBUTION OF MEDICINAL PRODUCTS

The company seeks to obtain a licence for wholesale distribution activities. The company has appointed approved primary distributors for distribution of products. The responsibility of distribution is clearly defined in the QTA with individual manufacturer and distributors. Distributors are responsible for complying with relevant GDP obligations for contracted activities as per signed QTA.
Additionally, where the company is responsible for distribution of the medicinal products to the customer, adequate checks and controls are followed to ensure that the medicinal products are delivered as per the defined temperature conditions. In case of failures, appropriate deviations are raised and risk assessed by Quality Unit.

The applicable RP must approve any stock returned to saleable status.

The complete process is defined in SOP for [In-Market Batch Disposition][VQICE].

### Bona Fide Checks of Customers

Medicinal products are only distributed via approved distributors or wholesalers to persons authorised to purchase medicinal products or persons authorised to supply medicinal products. In most cases these checks are conducted by of the third party storage or distribution sites as defined by QTA’s.
The Responsible Person is responsible for ensuring that the above is undertaken through process review and audits.
The complete process is defined in SOP for Establishing the Bona Fides of Customers and Suppliers.

### Responsible Person

Responsible Person(s) are either full time employees or consultants. All are named on all applicable licences. The job description and /or QTA for the Responsible Person(s) details the specific responsibilities. 
Responsible Person(s) maintain oversight of effective functioning of the Quality Systems from GDP perspective; however, the responsibility for approval of individual quality documents/records have been delegated to authorised personnel as defined in relevant procedures.

### Operations

For licensed products, responsibility for the following activities are primarily delegated to primary distribution sites as per QTA’s (this list is not exhaustive - refer to signed QTA for assigned responsibilities):

* Receipt of Goods
* Storage
* Temperature and Environmental Control
* Segregation of Goods Destruction of obsolete Goods
* Picking
* Packing
* Delivery
* Destruction
* Customer Qualification
* In-market release

### Suspected Falsified Medicinal Products

The company minimises the risk of Falsified Medicines by ensuring the integrity and control of the supply chain through the approval of new suppliers and bona—fide checks process. Responsibility for checking of Falsified Medicines is defined in QTA's with distribution sites.
All complaints received are assessed for the possibility of Falsified Medicines entering the supply chain.
The full process is defined in the SOP for [Falsified Medicinal Products][VTOMR].

### Transportation

Temperature control and/or monitoring is performed for all consignments from manufacturers to primary distributors. It is the responsibility of the primary distributors as defined in the QTAs to download / check the temperature records on receipt of the consignment and either provide it or assess for further release decision.

The company procure and supply data loggers to suppliers via an approved pre—wholesaler site. All data loggers are provided with a certificate of calibration.

The complete process is defined in SOP for [In-Market Batch Disposition][VQICE]






[GMP Guidelines]: https://ec.europa.eu/health/documents/eudralex/vol-4_en]
[GDP Guidelines]: https://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=OJ:C:2013:343:0001:0014:EN:PDF
[GVP Guidelines]: https://www.ema.europa.eu/en/documents/regulatory-procedural-guideline/guideline-good-pharmacovigilance-practices-gvp-module-vi-collection-management-submission-reports_en.pdf
[Directive 2010/84/EU]: https://ec.europa.eu/health/sites/health/files/files/eudralex/vol-1/dir_2010_84/dir_2010_84_en.pdf
[Regulation EU No 1235/2010]: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32010R1235
[EudraGMDP]: http://eudragmdp.ema.europa.eu
[AMXWS]: /procedures/Procedure_GDP_AMXWS_Management_Of_Procedures.md
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
[GGNHM]: /procedures/Procedure_GDP_GGNHM_Reporting_Of_Adverse_Events.md
[PSGBV]: /procedures/Procedure_GDP_PSGBV_Artwork_&_Labelling.md

_Appending a new line_