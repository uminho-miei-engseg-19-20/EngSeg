# TP  Class Assignment - 16/Mar/2020

Each group must answer the questions of the following exercises in the Github area of their group until the end of 30/Mar/2020\. For each day of delay, 0.15 points will be deducted from the grade of this assignment.



## Exercises

### 1\. GDPR (General Data Protection Regulation)

Among others, the following documents are available in the Aula6 directory:
+ Regulation (UE) 2016/679 (GDPR), in [portuguese](Aula6/UE_2016_679.RGPD.PT.pdf) and [english](Aula6/UE_2016_679.GDPR.ENG.pdf);
+ [Draft of the ISO 27552](Aula6/Draft.PIM_PbD.pdf) (_Security techniques - Extension to ISO/IEC 27001 and to ISO/IEC 27002 for privacy management — Requirements and guidelines_);
+ [_Standard	Data	Protection	Model_](Aula6/Germany.SDM-Methodology_V1.0.pdf) published by the german DPA (_Data Protection Atuhority_);
+ [_Handbook on European data protection law_](Aula6/EDPS-2018-handbook-data-protection_en.pdf), published by the [_European Data Protection Supervisor_](https://edps.europa.eu/);
+ Several documents provided by ENISA (_European Union Agency for Network and Information Security_) from its [Data Protecion](https://www.enisa.europa.eu/topics/data-protection) web page.


#### Experience 1.1

In this question each group will perform a short review of the Regulation (UE) 2016/679 (RGPD) or the ISO 27552 (_Security techniques - Extension to ISO/IEC 27001 and to ISO/IEC 27002 for privacy management — Requirements and guidelines_) or the _Handbook on European data protection law_, in accordance with the following rules:

+ If the group chooses the GDPR, it should review the following article of the regulation and write a short text (between 1/2 and 1 page A4) that reflects on how this regulation article can influence the development of the software. Note that the document has 173 initial recitals, some of which may be relevant to this reflection.
  - Article 5º 
  - Article 25º 
  - Article 32º 
  - Section 4 (Data Protection Officer)  


+ If the group chooses the ISO 27552 draft, it should review the following section and write a short text (between 1/2 and 1 A4 page) that reflects on the implications that this point has on software development and / or operation.
  - 6.4 (_Human resource security_) e 6.5 (_Asset management_)  
  - 6.9 (_Operations Security_)  
  - 6.13 (_Information security incident management_)  
  - 6.15 (_Compliance_)  


+ If the group chooses the _Handbook on European data protection law_, it should review the following section and write a short text (between 1/2 and 1 A4 page) reflecting on the implications of this subject for software development:
  + _Lawfulness, fairness and transparency of processing principles_ - section 3.1  
  + _Principle of purpose limitation_ - section 3.2  
  + _Data minimisation principle_ - section 3.3  
  + _Data accuracy principle_ - section 3.4  
  + _Storage limitation principle_ - section 3.5  
  + _Data security principle_ - section 3.6  
  + _Accountability principle_ - section 3.7  
  + _Right to be informed_ - section 6.1.1  
  + _Right to rectification_  - section 6.1.2  
  + _Right to erasure_ - section 6.1.3  
  + _Right to restriction of processing_ - section 6.1.4  
  + _Right to data portability_ - section 6.1.5  


Note that the analysis should only be done to one of the documents, and the group should choose which one it prefers, according to the previous rules.


#### Question P1.1

ENISA (European Union Agency for Network and Information Security) has done an excellent job in producing relevant documentation for data protection.


In the document  [_Recommendations on shaping technology according to GDPR provisions - An overview on data pseudonymisation_](Aula6/ENISA.WP2018-O.2.2.5-Recomendations-on-shaping-technology-according-to-GDPR-provisions-Part1.pdf) analyze the _Pseudonymisation techniques_ (section 3), and summarize them (between 1/2 and 1 page A4) - Groups 1, 4, 7, 10, 13.


In the document [_Recommendations on shaping technology according to GDPR provisions - Exploring the notion of data protection by default_](Aula6/ENISA.WP2018-O.2.2.5-Recommendations-on-shaping-technology-according-to-GDPR-provisions-Part2.pdf) analyze the _Data protection by default in practice_ (section 3), and summarize them (between 1/2 and 1 page A4) - Groups 2, 5, 8, 11, 14.

In the document [_Privacy and Data Protection by Design – from policy to engineering_](Aula6/ENISA.Privacy-and-Data-Protection-by-Design.pdf) analyze the eight strategies of _privacy design_ (section 3.2), and summarize them (between 1/2 and 1 page A4) - Groups 3, 6, 9, 12.


#### Experience 1.2

Table 1 of document  [_Online privacy tools for the general public - Towards a methodology for the evaluation of PETs for internet & mobile users_](Aula6/ENISA.Study-on-the-availability-of-trustworthy-online-privacy-tools-for-the-general-public.pdf) identifies
the most relevant web portals in promoting the use of tools that guarantee the privacy of the data (and / or the user).

Based on the web portals identified, carry out the following experiments:
+ Use the Panopticlick tool from _Electronic Frontier Foundation_ (EFF) to check if your browser is safe against _tracking_ - https://panopticlick.eff.org/
+ On _PRISM Break_ check which applications to avoid and which ones you should prefer on your platform - https://prism-break.org/en/
+ In _Security in-a-box_ check the tactic to protect sensitive files on your computer - https://securityinabox.org/en/guide/secure-file-storage/
+ Privacytools.io provides information on a broad set of privacy-preserving tools - https://www.privacytools.io/



#### Experience 1.3

_ARTICLE 29 DATA PROTECTION WORKING PARTY_ published the [_Guidelines on Data Protection Impact Assessment (DPIA) and determining whether processing is “likely to result in a high risk” for the purposes of Regulation 2016/679_](Aula6/EU.20171013_wp248_rev01_enpdf.pdf). These guidelines include the nine criteria that should be considered in order to assess whether the processing of personal data will result in a high risk - a DPIA should be performed whenever the processing meets two of these criteria.

1. Identify the nine criteria
2. Imagine that you are initiating a project that involves the use of personal data whose processing results in a high risk. Briefly explain the project and the processing, as well as the criteria that the processing satisfies.
3. Fill in the [DPIA template](Aula6/ICO.dpia-template.pdf).



#### Experience 1.4

CNIL (_Commission Nationale de l'Informatique et des Libertés_) provided an open-source tool to help with the _Data Protection Impact Assessment_ (DPIA) at https://www.cnil.fr/en/open-source-pia-software-helps-carry-out-data-protection-impact-assesment.

1. Install the DPIA tool (available for Linux, Windows and MacOS) - https://www.cnil.fr/en/open-source-pia-software-helps-carry-out-data-protection-impact-assesment
2. Use the DPIA tool for the project you explained in the previous question, briefly filling in all the required components.
3. At the end of the validation, go to the dashboard and choose the list presentation, select "Display PIA" and print to PDF file. Put it in your group space in github, as a response to this question.



#### Question P1.2

ENISA (European Union Agency for Network and Information Security) has done an excellent job in producing relevant documentation for data protection.

The document [_Handbook on Security of Personal Data Processing_](Aula6/ENISA.WP2017.GDPRMeasuresHandbook.pdf) is relevant in that it presents a methodology for assessing the security risk in the processing of personal data, as well as a series of use cases that calculate the level of risk based on the methodology used.

The purpose of this exercise is for each group to analyze a use case, discuss the various methodological steps followed until the risk assessment, identify the existing risk and propose appropriate measures to reduce the risk based on Annexes A.1, A.2 and A.3 of the document.

Use case to evaluate:

+ Payroll management - Groups 1, 7, 13
+ Recruitment - Groups 2, 8, 14
+ Evaluation of employees - Groups 3, 9
+ Order and delivery of goods - Groups 4, 10
+ Marketing/advertising - Groups 5, 11
+ Suppliers of services and goods - Groups 6, 12


