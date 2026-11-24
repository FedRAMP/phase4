# Agency-Provided Offerings Rules



## **Definitions**

**FRD-AGP** Agency Provider

> The federal agency provider responsible for a cloud service offering in the context of FedRAMP Certification under the Agency-Provided Offering ruleset.

**FRD-APO** Agency-Provided Offering

> A cloud service offering within the scope of agency-provided offerings; that is, a cloud service offering operated by an agency and offered as a shared service to other agencies.

## **Agency Provider Responsibilities**

**APO-APR-PFR** Pick One FedRAMP Certification

> Agency Providers MUST obtain and maintain only one FedRAMP Certification for an agency-provided offering.
>
> *Note: Agency providers may maintain two FedRAMP Certifications during the initial transition to Class G; FedRAMP recommends that all new agency-provided offerings obtain a Class G FedRAMP Certification.*

**APO-APR-ATO** Authorization to Operate

> Agency Providers MUST obtain and maintain an agency authorization to operate for an agency-provided offering, following the requirements and expectations of the OMB A-130 and related requirements, that accepts the risk of allowing other agencies to also use the agency-provided offering.

**APO-APR-POI** Public Offering Information

> Agency Providers MUST publicly share up-to-date information about the agency-provided offering in both human-readable and JSON formats, including at least the following information:
>
> 1. FedRAMP ID
> 2. Service Model
> 3. Deployment Model
> 4. Business Category
> 5. FIPS-200 Information System Impact Level (Low, Moderate, or High)
> 6. Authorizing Official Position Information (agency, title, etc. \- personal name not required)
> 7. Potential Customer Point of  Contact Information
> 8. Security Contact Information
> 9. Product Website Link
> 10. Link to Product Logo
> 11. Overall Service Description
> 12. Link to Secure Configuration Guidance
> 13. Overview of documentation supplied by the agency provider for the agency-provided offering
> 14. Instructions on how to request authorization materials
> 15. Date of the next upcoming continuous collaborative monitoring meeting (if the agency provides such)
>
> *Note: A JSON schema will be provided for this information. This information would typically be shared on the cloud service offering’s web page.*

**APO-APR-MKT** FedRAMP Marketplace and Application

> Agency Providers MUST apply for a FedRAMP Marketplace listing and a FedRAMP Certification assessment from FedRAMP to have their agency-provided cloud service offering FedRAMP Certified; agency providers are encouraged to engage directly with FedRAMP early in this process and will receive additional support from FedRAMP to complete the process.

**APO-APR-ADS** Authorization Data Sharing

> Agency Providers MUST supply authorization materials to current and prospective agency customers directly, using either a FedRAMP-compatible trust center or similar agency approved mechanism to distribute authorization materials; these materials are likely to include at least the following:
>
> 1. System Security and Privacy Plan
> 2. Incident Response Plan
> 3. Secure Configuration Guidance
> 4. Agency Use Template / Customer Responsibility Matrix
> 5. Agency Customer Support and Security Support Information
> 6. Collaborative Continuous Monitoring Plan
> 7. FedRAMP Agency-Provided Offerings Ruleset Implementation Summaries
>
> *Note: FedRAMP will not oversee package access or provide a centralized repository for offerings by agency, the overhead of supporting this activity should be baked into the transition to the Agency Provided FedRAMP Certification Path.*

**APO-APR-IMP** Implementation Summary

> Agency Providers MUST supply an implementation summary to all necessary parties that provides a high level summary of the implementation and justification for each rule in this FedRAMP Agency-Provided Offerings ruleset.
>
> *Note: This ensures potential agency customers have quick access to information that can be used to make an initial informed decision about potential use of the agency-provided cloud service offering. For example, some agencies may determine they will not use agency-provided cloud services that do not provide quarterly continuous monitoring reports or information on transformative changes.*

**APO-APR-SCG** Secure Configuration Guidance

> Agency Providers MUST supply guidance for agency tenants that explains how to securely configure and operate the cloud service.

**APO-APR-AFC** Addressing FedRAMP Communication

> Agency Providers MUST promptly and appropriately respond to urgent security communications from FedRAMP, preferably by designating a FedRAMP Security Inbox to receive email from FedRAMP and agency partners; this FedRAMP Security Inbox email should be clearly marked in the information provided to FedRAMP.

**APO-APR-AUN** Agency Use Notifications

> Agency Providers MUST promptly notify FedRAMP each time a new agency customer authorizes the use or operation of the agency-provided cloud service, along with any changes to existing customer use.
>
> *Note: The FedRAMP Authorization Act requires agencies notify FedRAMP when using a FedRAMP Certification to authorize the use of a cloud service; this rule enables interagency information sharing by ensuring FedRAMP and CISA are aware of which agencies are using what agency-provided services in the event agencies forget to notify FedRAMP.*

**APO-APR-ATU** Authorization to Use Templates

> Agency Providers SHOULD supply template Authorization to Use packages that can be used by agency customers to populate an Authorization to Use, including a template for the application of Secure Configuration Guidance by the agency customer such as a Customer Responsibility Matrix.
>
> *Note: This can be in whatever form the agency determines will best serve its customers, but FedRAMP recommends a traditional control implementation responsibilities matrix for critical controls that shows the separation of responsibilities between the agency provider and the agency customer.*

**APO-APR-CCR** Collaborative Continuous Reporting

> Agency Providers SHOULD supply continuous monitoring reports to all necessary parties, at least quarterly, that summarize the information security continuous monitoring program activities performed during the period since the last report; these reports SHOULD have a risk-based focus on relevant information that agency customers will need to make continuous risk decisions and include copies of critical agency Plans of Action and Milestones that might affect agency customers.
>
> *Note: Agency providers should be clear with potential customers if they intend to do this or not \- it may not be necessary for some services or agency customers, but in most cases it will ensure a high quality customer experience.*

**APO-APR-TCN** Transformative Change Notifications

> Agency Providers SHOULD notify all necessary parties within 1 month of completing an agency-identified transformative change.

**APO-APR-RIS** Responsible Information Sharing

> Agency Providers SHOULD NOT include sensitive information in their shared authorization materials that would likely enable a threat actor to gain unauthorized access, cause harm, disrupt operations, or otherwise have a negative adverse impact on the agency-provided offering.

**APO-APR-TCW** Transformative Change Warnings

> Agency Providers MAY notify all necessary parties of plans to initiate transformative changes at least 31 days before starting the transformative change, including a summary of any likely security impacts or changes in risk.
>
> *Note: For potentially sensitive cloud services, notifying agency customers in advance is absolutely the right thing to do.*

**APO-APR-FRA** FedRAMP Recognized Assessor

> Agency Providers MAY use a FedRAMP Recognized Independent Assessment Service to independently assess the security and privacy decisions made in the authorization of the cloud service offering if the authorizing official determines doing so is efficient and in the best interests of the government; however, independent assessments are NOT required or expected by FedRAMP for FedRAMP Class G Certifications as the authorizing official is entirely responsible for the A-130 process and is already independently reviewed by existing government oversight.

**APO-APR-CCM** Collaborative Continuous Meetings

> Agency Providers MAY host persistent collaborative meetings with agency customers to review significant changes and other security information that agency customers would benefit from discussing synchronously.

**APO-APR-IOR** Ignore Other Rules

> Agency Providers with a Class G FedRAMP Certification MAY ignore all other rules that apply to Providers in the Consolidated Rules for 2026, except for those in the Agency-Provided Offerings ruleset.
