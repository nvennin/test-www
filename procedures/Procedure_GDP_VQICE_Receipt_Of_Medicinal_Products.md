# RECEIPT OF MEDICINAL PRODUCTS

## Header


|Item          |Details                                                                                                                                                                                                                                                                                            | 
|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------| 
|Purpose       |Describe the process of reception of medicial products                                                                                           |
|Department    |Quality                                                                                                                                                                                                                                                                                            |   
|Categorie     |GDP         

## REFERENCES AND ASSOCIATED DOCUMENTS

### References

* [Customer Complaint][ZIWKI] 
* [Deviations][XCEUG]
* Work Instruction for In Market Release in D365
* Release Notification Recipient List

## ROLES

Role     |   Description    |   Who
------   |   --------       |  ----
Reviewer | Reviews documentation of the supplier and ensures that all changes are documented | Quality Officer

## PROCEDURE

### Receipt of Batch Documentation
The below information is required to be available to perform release in D365.

| Document                                                       | Source              |
| -------------------------------------------------------------- | ------------------- |
| Finished Product CoA / COC                                     | Supplier            |
| Temperature Data during transportation to Distribution center  | Distribution Centre | 
| Purchase/sales invoices, delivery slips                        | Supplier            |

#### COA / COC Review

* The finished product CoA and CoC are reviewed for accuracy and completeness for the following data:
  * Product Name
  * Product Strength
  * Lot Number
  * Date of Manufacture
  * Expiry Date
  * Finished Product Quantity
  * Country / Territory product released to

#### Temperature Data Review
* Review temperature data associated with the batch during transportation and ensure that product remained within specification for the full duration.
* If a temperature excursion has occurred during transportation, raise a Distribution Complaint. The batch must only be released upon confirmation from the Responsible Person.

#### D365 Data Review
* If the requirements are satisfactory to allow release the batch data must also be verified in D365. This includes confirmation of the batch number, SKU, quantity and expiry date.
* Errors in the D365 data observed during the in-market release process should be noted and rectified where possible. If the error cannot be corrected while the Quarantine Order remains open the batch may be released to allow Supply Chain to immediately make the adjustment within D365 as required. Quality will confirm that the correction has been made and is as required. Evidence of correction should be notified.
* All errors post Quality release will be documented, investigated and addressed under Deviations.

### In Market Batch Disposition
* After the review checks, proceed to perform in Market batch disposition i.e. approve or reject and record the disposition status in the In Market Disposition Tracker and in D365.
* Where additional packaging activities e.g. Bollini label application have been performed post shipment of goods from the CMO the Change Request for the activity must be consulted and referenced. Quality must ensure that the final QP release has been conducted as per the process agreed with the CMO.
* A copy of the following documentation is retained : COA; COC; Invoice and/or delivery note.

### Material Status Change
* If the status of a batch must temporarily change post release the communication of this must be made to the pre—wholesaler in target market.

### Release in D365 of Batch ln-Market Released by Pre-Wholesaler 
* Where previously agreed, and in line with the QTA, a pre-wholesaler may perform the In-Market release for a specific market. Quality will release the batch in D365 upon communication from the pre-wholesaler.
* A copy of the CoA, CoC and release communication is retained.

## TRAINING
Anyone who performs the In—Market release must first complete read and understand training in this procedure.

[GMP Guidelines]: https://ec.europa.eu/health/documents/eudralex/vol-4_en]
[GDP Guidelines]: https://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=OJ:C:2013:343:0001:0014:EN:PDF
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
