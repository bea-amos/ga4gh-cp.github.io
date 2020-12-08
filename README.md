---
layout: default
permalink: index.html
---

# GA4GH Clinical & Phenotypic Data Capture & Exchange

The "Clinical & Phenotypic Data Capture & Exchange" ([GA4GH::CP](http://ga4gh-cp.github.io)) Work Stream is one of the elements of the Global Alliance for Genomics and Health ([GA4GH](http://ga4gh.org)), aimed at developing standard formats for the exchange of genomic data for research and biomedical applications.  All members of this team must follow the [GA4GH Standards of Professional Conduct]( https://www.ga4gh.org/docs/GA4GH-Standards-for-Professional-Conduct_22-Jan-2018.pdf).

This Work Stream supports the clinical adoption of genomics through establishing standard ontologies, best practices and information models to describe the clinical phenotype for use in genomic medicine and research, including the capture and exchange of information between electronic health records and research systems.

### Work Stream Leads:

- [Melissa Haendel](https://www.ohsu.edu/people/melissa-haendel/AFE044BDE8046E5D6FBDA51F448BDE2A)
- [David Hansen](http://people.csiro.au/H/D/David-Hansen)

#### Work Stream Manager:

- [Lindsay Smith](https://ca.linkedin.com/in/lindsaysmithh)


This workstream has several project areas, focusing on different aspects of the mission:

### [Phenopackets](https://github.com/phenopackets)
While ontologies and terminologies provide the standard data concept definitions for capturing clinical information, an information model is required to successfully exchange that information between clinical information systems and with related information systems. A standardized structure for phenotypic data would catalyze integration from distributed sources such as authors, journals, data repositories and clinics when appropriately consented, and accelerate clinical utilization of this data to effect more precise health outcomes. The “Phenopackets” standard will provide information models with different levels of complexity to enable high level clinical phenotype information as well as deep clinical phenotype information to be exchanged.
- [Github Space](https://github.com/phenopackets) + [Submit Comments](https://github.com/phenopackets/phenopacket-schema/issues)
- [Documentation](https://phenopacket-schema.readthedocs.io/en/latest/index.html)
- [Phenopackets Subgroup Minutes](https://docs.google.com/document/d/1BsNt_hegpmDcEK4RliDC3EJc9B19jdJyAj6rhrgaluo/edit?usp=sharing)
- [Cancer Task Team Minutes](https://docs.google.com/document/d/1-j60KM54XB59wSn6Uok2iDk2At9Grj2_o9zu2z9A2zA/edit?usp=sharing)

### [Phenopackets on FHIR Implementation Guide](https://github.com/phenopackets/phenopacket-schema-fhir-implementation-guide)
The Phenopackets Schema FHIR Implementation Guide is an HL7 FHIR Implementation guide based on the approved Phenopackets standard. It will support the standardized exchange of phenotypic information from one health health information system to another through the FHIR API.
- [Domain Analysis Github](https://github.com/phenopackets/domain-analysis) + [Readthedocs](https://phenopackets-analysis.readthedocs.io/en/latest/)
- [Core Implementation Guide Github](https://github.com/phenopackets/core-ig)
- [Phenopackets IG First Draft](https://aehrc.github.io/fhir-phenopackets-ig/s) (1:1 mapping)

### [Family History/Pedigree Representation](https://github.com/ga4gh-cp/family-history)
Pedigree data is currently represented in heterogeneous formats that frequently result in the use of lowest-common-denominator formats (e.g., PED) or custom JSON formats for data transfer. The need for high quality, unambiguous, computable pedigree and family history information is critical for informing genomic analysis as well as using the information to inform risk to family members. Standardizing the way systems represent family structure will allow patients to share this information more easily between healthcare systems and help software tools to use this information to improve genome analysis and diagnosis. 
- [Draft model v0.9](https://docs.google.com/spreadsheets/d/1iO8FR9XhGnqElbOqqvPfdw9Fb4H779Q3jRrVi37feF0/edit#gid=0)
- [Draft minimal dataset](https://docs.google.com/document/d/1UAtSLBEQ_7ePRLvDPRpoFpiXnl6VQEJXL2eQByEmfGY/edit)

## Work Stream Meetings
- Full Work Stream Monthly Calls: Monthly on Thursdays at 12pm PST/3pm EST/8pm BST/9pm CEST/6am (Friday) AEDT, etc.  (19:00 UTC).
- Pedigree Technical Subgroup Calls: Bi-weekly/fortnightly Thursdays at 12pm PST/3pm EST/8pm BST/9pm CEST/6am (Friday) AEDT, etc.  (19:00 UTC).
- Phenopackets Technical Subgroup Calls: Bi-weekly/fortnightly Thursdays, rotating times. Opposite weeks of the Pedigree calls.
  - Week A: 6am PT/ 9am ET/ 2pm BST/ 10pm JST/ 12am (Fri) AEDT
  - Week B: 2pm PT/ 5pm ET/ 10pm BST/ 6am JST/ 8am (Fri) AEDT


Please email [Lindsay Smith](mailto:lindsay.smith@ga4gh.org) for meeting invitations.

## Relevant Links
- [2020 Roadmap](https://docs.google.com/document/d/1dO2uRrcHavXcN0NOCZ3hcNfHRxVb2nT9u_9xD1ZWWIc/edit?usp=sharing) (In Development)
- [2019 Roadmap](https://docs.google.com/document/d/1Xjtlm_G_zHJoHZkEELgNG8nSvxfeJczHaxBQ89ckxF4/edit) (Old)
- [2019-2020 Meeting Minutes](https://docs.google.com/document/d/1gxRaduk2bv6_cCSiDVJomVtfMD2AOFeDVGELsShh21U/edit?usp=sharing)
- [Slack](https://ga4gh.slack.com/) - Clin/Pheno channel is #clin_pheno_full

## Recent F2F Meetings
- GA4GH Virtual 8th Plenary, September 2020. See [here](https://docs.google.com/document/d/1tNYQOSrNLYPDWU8Njui4zadCh5URtsHOfe-ybVtmEjY/edit?usp=sharing) for Clin/Pheno working meeting notes and agendas, and [here](https://broadinstitute.swoogo.com/ga4gh-8th-plenary/meeting-materials) for Plenary session meeting materials
- GA4GH Virtual Connect, March 2020. See [here](https://docs.google.com/document/d/1rGU8Xt6aF1sL8ckIwjviSeXaGT6uu6sdo0_0e4d_qfY/edit?usp=sharing) for notes and presentations.
- GA4GH 7th Plenary in Boston, USA, October 2019. See [here](https://drive.google.com/drive/u/0/folders/1o434LggP5tTZJA179SDsH1zR45GeeiMu) for notes and presentations.
- GA4GH Connect in Hinxton, UK, April 2019. See [documentation](https://drive.google.com/open?id=1Nenj5FyjUoxvo6TtHYxuPEknYMbAfd_V).
- GA4GH 6th Plenary in Basel, Switzerland, October 2018. See [here](https://www.ga4gh.org/event/ga4gh-6th-plenary/) for more information.
