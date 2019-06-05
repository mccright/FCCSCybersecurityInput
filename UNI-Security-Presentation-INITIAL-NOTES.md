
### If the presentation were this week,
 I would use the following cybersecurity incidents as an introduction (they need to be 'current' and there should be no trouble finding 'current' incidents whenever the session is presented):  

 * Last Thursday Microsoft released security updates for some out-of-support systems to fix a bug that could be weaponized as a worm if exploited.
 [https://www.darkreading.com/endpoint/microsoft-patches-wormable-vuln-in-windows-7-2003-xp-server-2008/d/d-id/1334709](https://www.darkreading.com/endpoint/microsoft-patches-wormable-vuln-in-windows-7-2003-xp-server-2008/d/d-id/1334709)
 This is a critical unauthenticated, remote code execution flaw in Remote Desktop Services (RDS, also known as Terminal Services) which affects some older versions of Windows
 This type of vulnerability supports malware propagating across vulnerable machines -- 'worm' behavior.  

 * Last Wednesday, more than a week after a ransomware cyberattack hobbled Baltimore’s computer network, city officials still say they can’t predict when its operations will be up and running...
 [https://wtop.com/baltimore/2019/05/8-days-after-cyberattack-baltimores-network-still-hobbled/](https://wtop.com/baltimore/2019/05/8-days-after-cyberattack-baltimores-network-still-hobbled/)
 They still cannot support financial or property transactions or interact with anyone via email.  

 * Last Tuesday, the more than 1.5 billion WhatsApp users learned that the application's end-to-end encryption failed to stop attacks against its audio call features that allowed attackers to install malware & conduct surveillance on exploited users -- even when they did not even answer the attacker's call.
 [https://www.wired.co.uk/article/whats-app-hacked](https://www.wired.co.uk/article/whats-app-hacked)  

#### FROM: "Most Important Security Elements."   
[https://dzone.com/articles/most-important-security-elements-part-1](https://dzone.com/articles/most-important-security-elements-part-1) and  
[https://dzone.com/articles/most-important-security-elements-part-2](https://dzone.com/articles/most-important-security-elements-part-2)  
Visibility, mitigation, prioritization, and encryption — these are the most important elements to security right now.  By Tom Smith, May. 24, 2019  

START "DZone surey of 50 security professionals."  

SUMMARY:  
-------  
 * INVENTORY. We cannot understand our risk load until we have accurate data about the infrastructure and processes that represent our organizations.  This is sometimes also called "visibility," "know your environment," or "know your data."    
 * EVENT TRANSPARENCY. Organizations need access to and an understanding of inventory, attack vectors, and security events to inform security decision-making.  Simply responding to successful attack is not a sustainable goal.   
 * CONTEXTUAL AWARENESS. Effective threat hunting and incident identification/triage/response require events-in-context requires application, infrastructure & operations documentation, modern SIM integration, as well as real-time access to data, logging systems, and penetration test & code assessment results.  Contextual awareness is also essential for effective risk management at application/system architecture, design, and development time.   
 * HARDENING.  Our attack surface needs to resist the activities of all hostile actors.  
 * PRIORITIZE. All organizations have more risks than can be addressed at any given time.  Most organizations are in the risk-taking business.  

SUPPORTING DISCUSSION:
---------------------
### INVENTORY  
We cannot understand our risk load until we have accurate data about the infrastructure and processes that represent our organizations.  This is sometimes also called "visibility," "know your environment," or "know your data," and addresses questions about who, what, and where.  
a. Comprehensive Inventory. Organizations evolve and expand.  'Inventory' needs to detail the attack surface throughout this evolution.
### EVENT TRANSPARENCY  
Organizations need access to and an understanding of inventory, attack vectors, and security events to inform security decision-making.  Simply responding to successful attack is not a sustainable goal.  Event transparency enhances addressing questions about who, what, where and when.  
a. Monitoring, which requires decomposing & correlation of high-velocity event streams into "relevant" events and some level of antomated analysis.  Events from application and infrastructure changes are as important as attack indicators.  
a. Event data needs to drive evolution and optimization of your risk management strategies, tooling, and techniques.  
### CONTEXTUAL AWARENESS  
Effective threat hunting and incident identification/triage/response require events-in-context.  This requires application, infrastructure & operations documentation, modern SIM integration, as well as real-time access to data, logging systems, and penetration test & code assessment results.  Contextual awareness is also essential for effective risk management at application/system architecture, design, and development time.  Contextual awareness enhances addressing questions about who, what, where, when, and why.  
a. Mature monitoring capabilities integrate events into risk-relevant collections that enhance our understanding of event context.  
a. Effective evolution and optimization of our risk management capabilities require we understand events in context.  
### HARDENING  
Our attack surface needs to resist the activities of all hostile actors.  
a. The implementation of our applications, infrastructure & operations need to align one or another of the mature best practice frameworks (OWASP, WASC, etc.).
b. The increasing complexity and diversity of our business infrastructure ecosystem drives the criticality of hardening all aspects of our applications, infrastructure & operations.  
c. Attack resistance needs to exist at runtime, in real-time, all-the-time.  We need to be able to detect and resist vulnerabilities before they enter any hostile environment (production, test, or other).  This can enhance our risk posture in the face of zero-day exploits.
d. Our efforts need to confront the fact that attacks evolve.  One foundational competency for dealing with this is to build and maintain the capability of resolving vulnerabilities quickly.  Only mature architectural, design, and implementation practices have a hope of achieving this goal in our increasingly distributed infrastructure and operations.  
e. Attack resistance requires embedding risk management practices throughout every relevant software development lifecycle.  
### PRIORITIZE  
All organizations have more risks than can be addressed at any given time.  Most organizations are in the risk-taking business.  Efficient and effective risk and work prioritization is a foundational competency.  
a. Risk management priorities are influenced by industry and culture.  
b. Scarcity and trade-offs are a constant reality.  Establish and maintain processes to work through them.  
c. Threat modelling requires "inventory," "event transparency," and "contextual awareness"
d. "Inventory," "event transparency," and "contextual awareness" are essential to effective risk management prioritization, which feeds "hardening" efforts.  

HARDENING involves a lot more than we initially discussed.  
Identification/Access Control.  
Planning/Have a Plan.  
Defense in Depth.   
Education.  

Organizations are in a race to create and launch revolutionary applications and services to differentiate themselves from the competition and deliver an exceptional customer experience. Fortunately, the adoption of transformative technologies – like DevOps, artificial intelligence, machine learning and robotic process automation – make this possible. These technologies, however, also expand organizations’ attack surfaces, creating heightened levels of risk that attackers are eager to exploit. Organizations like Uber may have grown to be billion-dollar behemoths by embracing innovations like DevOps to dramatically scale and growth, but this same innovation was the cause of the massive data breach at Uber that cost the company more than $150 million in settlement fees and fines.   

Privileged and administrative accounts in cloud environments need to be managed, protected and monitored just like privileged accounts in traditional datacenter. Organizations should establish a single control point to manage the credentials of cloud administrators, developers and other users accessing the management consoles and portals of the various cloud platforms.  

Ever-evolving threats.  

END DZone surey of 50 security professionals.  


Why should I care?  
-----------------
 * Because these types of costly & intrusive incidents happen every day, and each is associated with attacks from one or another hostile actors.  For many hostile actors, this activity is just 'business.'  
 * Hostile actors have a range of motivations, including, but not limited to: money/profit, espionage (industrial, nation-state, or other), blackmail, destruction (data, or capability), exploitation, revenge, political gains, hactivism, terrorism & more.  
 * Hostile actors have a range of personas, including, but not limited to: nation-state espionage, non-nation-state espionage, cyber-criminal (targeted), cyber-criminal (broad-based), insider, hacktivist, terrorist, nuisance.  
 * Also, the systems used to deliver the 'stuff' and services that we all consider part of our daily lives continue to grow more complex and interdependent.  
 * That complexity and interdependency results in more attack surface.  That increasing attack surface provides adversaries expanding opportunities to exploit vulnerabilities.  Common design & implementation practices continue to produce weaknesses and deficiencies in the components of the underlying systems that we build and deploy.  
 * Much effort goes into reactive security measures like intrusion or data loss detection and response capabilities.  
 * Measures like these fail to address the foundational risk management challenges that require a holistic approach based on sound systems security engineering techniques and security design principles.  
 * A more holistic approach can make our systems more penetration-resistant; capable of limiting the damage from disruptions, modification, breach, 'injury,' and other threats. 
 * It can also help make our systems and services more resilient -- more able to continue support of critical missions and business functions after they are compromised.  
"Rethinking Cybersecurity from the Inside Out."  
By: Ron Ross, November 15, 2016.   
[https://www.nist.gov/blogs/taking-measure/rethinking-cybersecurity-inside-out](https://www.nist.gov/blogs/taking-measure/rethinking-cybersecurity-inside-out)  

What might that kind of systems engineering look like?  
-----------------------------------------------------
**Strategic Cyber Resiliency Design Principles** [page 17]  
Focus on common critical assets.   
Support agility and architect for adaptability.  
Reduce attack surfaces.   
Assume compromised resources.  
Expect adversaries to evolve.  

**Structural Design Principles for Cyber Resiliency** [page 22]  
Limit the need for trust   
Control visibility and use  
Contain and exclude behaviors  
Layer and partition defenses  
Plan and manage diversity  
Maintain redundancy  
Make resources location-versatile  
Leverage health and status data  
Maintain situational awareness  
Manage resources (risk-) adaptively  
Maximize transience; minimize persistence  
Determine ongoing trustworthiness  
Change or disrupt the attack surface  
Make unpredictability and deception user-transparent  

"Cyber Resiliency Design Principles."  
**Cyber Resiliency Goals** [page 62]   
Anticipate  
Withstand  
Recovery  
Evolve  

**Cyber Resiliency Objectives** [page 62]  
Understand  
Prepare  
Prevent / Avoid  
Continue  
Constrain  
Reconstitute  
Transform  
Re-architect  

**Cyber Resiliency Techniques** [page 62]  
Adaptive response  
Analytic monitoring  
Deception  
Diversity  
Dynamic positioning  
Non-persistence  
Privilege restriction  
Segmentation / isolation  
Coordinated defense  
Dynamic representation  
Realignment  
Redundancy  
Substantiated integrity  
"Cyber Resiliency Design Principles" MITRE Technical Report, By Deborah Bodeau & Richard Graubart, January 2017  
[https://www.mitre.org/sites/default/files/publications/PR%2017-0103%20Cyber%20Resiliency%20Design%20Principles%20MTR17001.pdf](https://www.mitre.org/sites/default/files/publications/PR%2017-0103%20Cyber%20Resiliency%20Design%20Principles%20MTR17001.pdf)  


The ISO 27000 includes a model for thinking about cybersecurity:  
QUOTE:  
Organizations of all types and sizes:  
 a) collect, process, store, and transmit information;  
 b) recognize that information, and related processes, systems, networks and people are important assets for achieving organization objectives;  
 c) face a range of risks that can affect the functioning of assets; and  
 d) address their perceived risk exposure by implementing information security controls.  

All information held and processed by an organization is subject to threats of attack, error, nature (for example, flood or fire), etc., and is subject to vulnerabilities inherent in its use. The term information security is generally based on information being considered as an asset which has a value requiring appropriate protection, for example, against the loss of availability, confidentiality and integrity. Enabling accurate and complete information to be available in a timely manner to those with an authorized need is a catalyst for business efficiency.  
Protecting information assets through defining, achieving, maintaining, and improving information security effectively is essential to enable an organization to achieve its objectives, and maintain and enhance its legal compliance and image. These coordinated activities directing the implementation of suitable controls and treating unacceptable information security risks are generally known as elements of information security management.  
As information security risks and the effectiveness of controls change depending on shifting circumstances, organizations need to:  
 a) monitor and evaluate the effectiveness of implemented controls and procedures;  
 b) identify emerging risks to be treated; and  
 c) select, implement and improve appropriate controls as needed.  

To interrelate and coordinate such information security activities, each organization needs to establish its policy and objectives for information security and achieve those objectives effectively by using a management system.
END QUOTE:  
From: ISO 27000 Overview & Vocabulary 5th ed. 2018-02., page 11.  
[https://standards.iso.org/ittf/PubliclyAvailableStandards/c073906_ISO_IEC_27000_2018_E.zip](https://standards.iso.org/ittf/PubliclyAvailableStandards/c073906_ISO_IEC_27000_2018_E.zip)  

None of us are likely to be in the 'risk elimination' business.  That is not an economic goal.  
Instead, we implement processes to identify risks and processes/tools to modify risks.  
We might chose to:  
— avoid a risk by deciding not to start or continue with the activity that gives rise to the risk;  
— take or increase our risk in order to pursue a given opportunity;  
— remove a risk source;  
— alter the likelihood of a given risk;  
— modify the consequences of a given risk;  
— share the risk with another party or parties (think contracts and risk underwriting/insurance);  
— assume the risk (ensuring that decision-makers are making an informed choice).  
From: ISO 27000 Overview & Vocabulary 5th ed. 2018-02., page 10.  
[https://standards.iso.org/ittf/PubliclyAvailableStandards/c073906_ISO_IEC_27000_2018_E.zip](https://standards.iso.org/ittf/PubliclyAvailableStandards/c073906_ISO_IEC_27000_2018_E.zip)  

## Another approach to thinking about your risks:
Risk Response  
-------------  
Risk acceptance  
Risk avoidance  
Risk mitigation  
  Reduce threat (likelihood of occurence)  
  Reduce vulnerability (likelihood of consequence)  
  Seek specific effects on adversaries  
Risk Sharing  
Risk Transfer  
[page 42]  
"Cyber Resiliency Design Principles" MITRE Technical Report, By Deborah Bodeau & Richard Graubart, January 2017  
[https://www.mitre.org/sites/default/files/publications/PR%2017-0103%20Cyber%20Resiliency%20Design%20Principles%20MTR17001.pdf](https://www.mitre.org/sites/default/files/publications/PR%2017-0103%20Cyber%20Resiliency%20Design%20Principles%20MTR17001.pdf)  


Why is it important to manage risk well?  At the highest level:
 * Your customers rely on it.  
 * Your shareholders/owners expect it.  
 * Your regulators demand it.  Many industries are regulated by one or more authorities.  Effective risk management is core to many regulatory contexts.  
 * Rating agencies look for it.  If your organization borrows money, this matters to you.  Better ratings generally result in more favorable terms, including lower interest payments.  



What can you do?  
---------------  
Pen Testing  
Threat Intelligence  
Threat hunting  
Red Team Exercises  
Red-vs-Blue Team Exercises  
...Another approach is to adopt or adapt one of the available frameworks.  


Frameworks to help you evolve your cybersecurity program:  
--------------------------------------------------------
 * Financial Services Sector "Cybersecurity Profile:" [https://www.fsscc.org/Financial-Sector-Cybersecurity-Profile](https://www.fsscc.org/Financial-Sector-Cybersecurity-Profile) 280 "diagnostic statements"  
 * PCI DSS - Payment Card Industry Data Security Standard: [https://www.pcisecuritystandards.org/pci_security/standards_overview and https://www.pcisecuritystandards.org/document_library](https://www.pcisecuritystandards.org/pci_security/standards_overview and https://www.pcisecuritystandards.org/document_library)  
 * ISO 27001/27002 (paywall) ISO/IEC 27000 family - Information security management systems: [https://www.iso.org/isoiec-27001-information-security.html](https://www.iso.org/isoiec-27001-information-security.html)  
 * CIS Critical Security Controls - Center for Internet Security Best Practices (Controls & Benchmarks): [https://www.cisecurity.org/cybersecurity-best-practices/](https://www.cisecurity.org/cybersecurity-best-practices/)  
 * NIST Framework for Improving Critical Infrastructure Security: [https://www.nist.gov/publications/framework-improving-critical-infrastructure-cybersecurity-version-11](https://www.nist.gov/publications/framework-improving-critical-infrastructure-cybersecurity-version-11)  
 (employs NIST SP 800-53 rev. 4: 1,683 specific Controls organized into 257 Control Sections, rolled up into 17 Control Families)  
 * OASIS  


EXAMPLE - NIST 800-53 Control Families:
-------------------------------------
[https://github.com/mccright/rand-notes/blob/master/NIST-Pub-800-53-Rev4-Controls-List.htm](https://github.com/mccright/rand-notes/blob/master/NIST-Pub-800-53-Rev4-Controls-List.htm)  
Access Control  
Audit And Accountability  
Awareness And Training  
Configuration Management  
Contingency Planning  
Identification And Authentication  
Incident Response  
Maintenance  
Media Protection  
Personnel Security  
Physical And Environmental Protection  
Planning  
Program Management  
Risk Assessment  
Security Assessment And Authorization  
System And Communications Protection  
System And Information Integrity  
System And Services Acquisition  


LEARNER RESOURCES:
-----------------
"Threat Modeling Cheat Sheet (OWASP)" [https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Threat_Modeling_Cheat_Sheet.md](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Threat_Modeling_Cheat_Sheet.md)  
Mitre Att&ck threat list https://mitre.github.io/attack-navigator/enterprise/.  ATT&CK is a catalog of techniques and tactics that describe post-compromise adversary behavior on typical enterprise IT environments. The core use cases involve using the catalog to analyze, triage, compare, describe, relate, and share post-compromise adversary behavior.  See the descriptions of all 244 Attack Techniques at: https://attack.mitre.org/techniques/enterprise/; and the 13 more that are specific to mobile environments at: [https://attack.mitre.org/tactics/mobile/](https://attack.mitre.org/tactics/mobile/).  
For a Q1 2019 Thread Overview using the MITRE ATT&CK framework, see: [https://www.rapid7.com/research/report/2019-q1-threat-report/#MITRE-ATTCK-Framework](https://www.rapid7.com/research/report/2019-q1-threat-report/#MITRE-ATTCK-Framework)  


======================================================================  


Scenario #1: On-Boarding Customers at 'Foremost Global Financial Group' (FGFG)
----------------------------------------------------------------------
Foremost is a global financial services enterprise.  
FGFG provides organizations and individuals investment, insurance, retirement products and services.  
FGFG maintains a global customer base.  
Our scenario is associated with their retirement services division (FRS).  
Retirement products and services are regulated by national & state governments.  
The retirement products and services is competitive & evolving rapidly.  Providers are driven to reduce internal/operational expenses while at the same time providing positive interactions with covered employees at every contact point (browser, mobile device, phone, and surface mail).  
Employers contract with FRS on behalf of their employees.  
Employees may get a range of retirement investment opportunities -- generally FRS customers choose to enable a default monthly contribution from & for each employee.  Employees would need to opt-out if that was their desire.  Therefore, most employee's FRS accounts tend to accumulate money.  

In the process, employers share a collection of demographic information about each of their employees.  
The nature of that data also makes this business the target of national & state privacy/data security laws and regulations.  
In financial services, it is critically important to link only the authorized individual(s) to any given account, and to maintain strong resistance to granting anyone else access to that account.  
Because it is impossible to 'know' the party on the other end of any Internet-enabled interaction, the initial customer 'on-boarding' process can be a high-risk interaction in some business contexts.  

FRS uses the employer-supplied demographic data to help identify given individuals when they initially point their browser at the FRS web site or download the FRS mobile app, and traverse a 'question-answer' on-boarding process to establish a new FGFG identity and link that new identity to their pre-established retirement account.

FRS provides 401(k) services to thousands of companies and millions of employees.
While every company is unique, the life-cycle of any given employee's relationship with FRS tends to fall along a number of continuums.  For example:    
    Active <------------------------------------> Passive  
    Engaged <-----------------------------------> Disengaged  
    Financial planner <-------------------------> Not a planner  
    Tech savvy <--------------------------------> Tech challenged  

Tech savvy, active, engaged, financial planners tend to explore & interact with our platforms as soon as they are available.  
As a result, the demographic data about them tends to be accurate, and initial on-boarding into our systems tended to go smoothly and result in relatively safer Internet-facing retirement participant accounts.  

Tech challenged, passive, disengaged participants continue living their lives as before.  FRS, and retirement in general, remains a vague and distant concept.  These participants tend not to interact with FRS systems until some trigger, some life-event that brings new relevance to retirement savings & investing (this could be a financial emergency, starting a family, reaching retirement age, etc.).  
As a result, more or less time will pass between our initial employer on-boarding and this employee's initial on-boarding into our systems.  During that time, a broad universe of life, employer, and data changes can occur.  
Achieving the FRS goal of providing positive interactions with every covered employee at every contact point is a challenge with this group.  They have ignored or just missed communications about their retirement plan and how to use FRS services.  
FRS expects calls, emails, surface mail, and sometimes chat sessions from this group -- and expects that they will not always go as smoothly because we have not built an active relationship with them.  
Regardless of those challenges, FRS is paid fees for this business and possesses the employee's retirement money and owes them excellent service.  

### ACTORS & COMPONENTS:  
-------------------  
Identity data brokers               Contract 'Quality Assurance'  

                            Attacker  
             
Authorized End user  

FRS web site        FRS call centers        FRS 'back room' employee processes  

FRS applications    FGFG applications  

FRS data stores    FGFG APIs --> FGFG data stores  

### Key Infrastructure and Operations Assumptions and Realities: ### 
-----------------------------------------------------------  
 * FGFG maintains a number of relatively independent subsidiaries.  FGFG provides some 'shared' infrastructure and services across all its subsidiaries.  Some of these include identity management, authentication, coarse-grained web application access control, log management, security operations (which includes a certain amount of incident identification, triage, and management), database management, firewalls, data centers, servers.  
 * FRS is engaged in a highly competitive and rapidly evolving industry.  One of their key metrics is customer/participant sentiment -- 'happier' more satisfied is better.  
 * FRS management expects little 'friction' in any retirement product/service customer interaction and 'exemplary' ease-of-use for all customer-facing systems.  At the time of this scenario, new retirement customer/participant on-boarding identification depended on the customer knowing their full name, tax ID, their company name, their phone number, and their mother's maiden name.  
 * FRS applications are integration in a way that requires the FGFG authentication infrastructure prompt new users (users who don't currently have an identity established in the FGFG enterprise systems) for one or another new customer on-boarding application.  
 * FGFG enterprise web authentication infrastructure includes top-tier endpoint finger-printing & geolocation capabilities, and can infer user patterns of access.  The system also enables enterprises to create policies that use this data to describe expected versus unexpected patterns of activity and policy violations can initiate alarms or other actions.  FGFG has 'tuned' this system to be 'friendly' to customers and to generate few alarms (alarms result in investigations, which consume resources).  
 * FRS call center representatives are incented to complete calls quickly and to have them result in positive caller responses (FRS does customer follow-up surveys).  In addition, representatives also receive calls from individuals having a broad spectrum of cultural & educational backgrounds -- resulting in a broad range of vocabulary, accents, financial literacy, etc.  
 * FRS and FGFG applications, installed on company servers in company data centers, tend to 'trust' inputs coming from 'internal' hosts and tend to omit logic that might detect, log or alarm on potential abuse cases.   
 * FRS database management assumes that data is 'cleansed' by applications prior to arrival.  

Over time, some passive, disengaged retirement participants leave a trail of temporary, discarded, and forgotton email addresses.  
Some also changes phone numbers and plans without informing their employer nor FRS.  
Others also move from one street address to another, even one country to another, they may get divorced, add a child to their family with a new partner, and they may speak an Arabic dialect at home and know English as a distant fourth language -- all without updating their employer or FRS.  
The name that their employer is known by can also evolve over time.  
All of that and more can add material confusion and uncertainty to the initial on-boarding interaction for some individuals.  
FRS has evolved their processes to help compensate for the difficulties imposed by characteristics like these in order to maximize efficiency, to on-board the maximum percentage of new employees who need no 'special' handling, and to help ensure that this initial interaction with FRS is a positive one.  


### Your assignment: What could go wrong?  
------------------------------------  
 * Carefully review the scenario material.  
 * Make some assumptions about each of the actors & components in this system and describe likely points of vulnerability.    
 * What are the most important vulnerabilities?  
 * Propose and describe in some detail an attack against this business.
 * How would you add attack resistance and attack awareness (alerting & alarming) to address the most important of the vulnerabilities in the scenario above.


### One Model FUBAR (many are possible):  
-----------------------------------  
 * Internet-interactions are mediated by layers of abstraction, technology, distance, time, automation and more.  
 * This adds complexity and uncertainty to the FRS participant on-boarding processes.  
 * These issues are exaggerated when dealing with one of those 'dormant' retirement accounts (the ones waiting for a disengaged individual to on-board and use FRS systems).  

 * In this scenario, assume that a hostile actor decides to attack 'unused' or 'dormant' retirement accounts.  
 * Their goal is to extract as many financial assets and as much personal data as is economical while assuming minimum risk.  
 * They engage in a certain amount of reconnosance, learning that FGFG web login infrastructure makes it easy to determine whether an individual associated with an FRS account has already worked through their on-boading process, or not.  
 * They explore the FRS site to document the new Retirement customer on-boarding process.  In doing so, they learn the types of information that new Retirement customers are asked to provide during on-boarding.  
 * Knowing the data they need, they buy FRS customer lists and associated demographic data from data brokers.  This is not a big investment.  
 * They hire contractors in a South East Asian country to 'quality check' the list against FRS systems -- looking for 'useful' accounts, accounts that are not yet associated with a validated identity.  The contractors return a vetted subset of the original list.  
 * They hire contractors in another Asia Pacific country to 'on-board' the available accounts using the purchased data -- establishing an identity now under the control of the attacker.  The contractors return a subset of the previous list containing 'working' username/password pairs, security question/answer pairs, and associated account balances.  Because of data inaccuracies & inconsistencies this on-boarding was not always straight foreward and the contractors sometimes had to call FRS 1-800 numbers for on-boarding help.  
 * They slowly explore and document the account functionality for given employer groups -- learning that some have different business rules in place for address changes, bank routing number changes, loan amounts, and impediments to making 'whole account' withdrawls.  
 * Finally, they quickly order a wide range of loan amounts, one against each account, requesting a check to be sent to an address input in the request form.  
 * FRS completed a number of the hostile actor's transactions before one of the 'dormant' retirement account holders called an FRS 1-800 number asking why they received a 'password change' letter in the mail -- which led to an investigation and identification of unauthorized activity on the account (and others).  
 * The hostile actors received enough of the requested checks to result in what they considered a useful net profit for the exercise.  
 * FRS replaced the lost funds in all the 'hacked' accounts.  
 * FRS conducted a thorough investigation of what happened (which was technically challenging because of 'unfriendly' logging practices and a lack of relevant analysis automation).  
 * FRS reported the breaches to all relevant parties (individuals, employers, regulators, etc.).  
 * FRS employer on-boarding, employee on-boarding, and identity verification processes were re-engineered.  

### NOTE:  
Other common approaches might have incorporated spearphishing (with links or attachments), drive-by compromise, 'hacking' one or more of the FRS web or mobile applications, compromising another FGFG subsidiary application and then exploiting assumptions about trust between different subsidiaries' applications...  
FUBAR == "Fouled up beyond recognition."  


#### LEADER RESOURCES:  
BSIMM Definitions of Architecture Risk Analysis - Builds an ARA definition by describing a set of increasingly mature risk analysis practices: https://www.bsimm.com/framework/software-security-development-lifecycle/architecture-analysis/  
Legacy U.S. CERT Definition & Best Practices Document on Architecture Risk Analysis: https://www.us-cert.gov/bsi/articles/best-practices/architectural-risk-analysis/architectural-risk-analysis  
"Threat Modeling Cheat Sheet (OWASP)" https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Threat_Modeling_Cheat_Sheet.md  
OWASP Cheatsheet Collection: https://github.com/OWASP/CheatSheetSeries/tree/master/cheatsheets  
OWASP Application Security Verification Standard (ASVS) attempts provides a basis for designing, building, and testing technical application security controls, including architectural concerns, secure development lifecycle, threat modelling, agile security including continuous integration / deployment, serverless, and configuration concerns: https://github.com/OWASP/ASVS  
FINANCIAL SERVICES SECTOR CYBERSECURITY PROFILE DOWNLOADS  
Financial Services Sector "Cybersecurity Profile:" https://www.fsscc.org/Financial-Sector-Cybersecurity-Profile [280 "diagnostic statements"]  



### Potential Signals of An Active Threat  
----------------------------------  
 * Account Authenticated To Critical Asset: A new user authenticates to a restricted asset.  
 * Account Authenticated To Critical Asset From New Source: A permitted user authenticates to a restricted asset from a new source asset.  
 * Account Authenticates With New Asset: A permitted user is authenticating to an application from a new source asset.  
 * Account Created: An account was created on a 'monitored' or 'flagged' asset.  
 * Account Enabled: A previously-disabled user account is re-enabled by an identity using an administrator role.  
 * Account Leak: A user's credentials may have been leaked to the public domain.  
 * Account Password Reset: A user resets the password for an account (special emphasis on 'monitored' or 'flagged' accounts, out-of-norm times/locations/endpoints, etc.)  
 * Account Privilege Escalated: An identity using administrator permissions assigns higher level of privileges to the account (special emphasis on 'monitored' or 'flagged' accounts, out-of-norm times/locations/endpoints, etc.).  
 * Account Received Suspicious: Link A user receives an email containing a link flagged by 'threat feeds' or another trusted source of threat information.  
 * Account Visits Suspicious Link: A user accesses a link URL identified as a threat by your 'threat feeds' or another trusted source of threat information.  
 * Malware Alert: An malware-identification system generates an alert.  
 * Asset Connects To Network Honeypot: There was an attempt to interact with to a network honeypot -- or some level of 'successful' interaction.  
 * Attacker Behavior Analytics: A detection model in your intrustion detection system fired -- alerting you for follow-up analysis and correlation with threat intelligence inputs.  
 * Authentication Attempt From Disabled Account: A disabled user attempts to authenticate and/or directly access an asset.  
 * Brute Force Attack Against Domain Account: One or more sources/assets has unsuccessfully attempted to authenticate using a domain account too many times within a given time threshold.  
 * Brute Force Attack Against Local Account: One or more sources/assets has unsuccessfully attempted to authenticate using a local account too many times within a given time threshold.  
 * Brute Force From Unknown Source: One or more unknown/unauthorized sources/assets failed to authenticate using a local account too many times within a given time threshold.   
 * Domain Admin Added: A user has been added to a privileged group.  
 * Local Admin Added: A user has been added to a privileged group.  
 * First Ingress Authentication From Country: A user logged onto the network/system for the first time from a given country.  
 * First Time Admin Action: An identity using administrator rights was employed for the first time in this domain or on this asset.  
 * Harvested Credentials Multiple accounts are attempting to authenticate to a single, unusual location.  
 * Ingress From Disabled Account A disabled user logs onto the network or a monitored cloud service.  
 * Ingress From Non Expiring Account An account with a password that never expires accesses the network from an external location.  
 * Ingress From Service Account A service account accesses the network from an external location.  
 * Lateral Movement Domain Credentials A domain account attempts to access several new assets in a short period of time.  
 * Lateral Movement Local Credentials A local account attempts to access several assets in a short period of time.  
 * Log Deletion A user deletes event logs on an asset.  
 * Log Deletion Local Account A local account deletes event logs on an asset.  
 * Malicious Hash On Asset A flagged process hash starts running on an asset for the first time.  
 * Multiple Country Authentications A user accesses the network from several different countries within a short period of time.  
 * Multiple Organization Authentications A user accesses the network from multiple external organizations too quickly.  
 * Network Access For Threat A user accesses a domain or IP address tagged in the Threats section.  
 * New Local User Primary Asset A new local user account was added to the primary asset of a domain user.  
 * New Mobile Device A user accesses the network from a new mobile device.  
 * Password Set To Never Expire A password of an account has been set to never expire.  
 * Protocol Poison Poisoning of a network protocol, such as via Responder, is detected  



In the context of your course about foundational concepts of computer science   

(Social, ethical, and legal issues)  
Why is it important to manage risk well?  
 * Our customers rely on it.  
 * Our shareholders expect it.  
 * Regulators demand it.  
 * Rating agencies look for it.  


security (or a closely related term, application security) is about ensuring that software does not have vulnerabilities. This is different than "security software" (like a firewall, or antivirus, or using a crypto protocol). A security feature can be one way to tackle a security risk in software, but security software also needs to be secure.  

Software security is one of the 'qualities' of software. Therefore, it is not surprising that secure software can be described by extending the notion of good quality. Security could be said to be "robust quality".  

A key point is that security is quality against an active attacker. Therefore, traditional quality assurance does not always perform well enough. Active attackers will try to exploit the weakest (e.g., the least tested) areas.  

There are a lot of ways in which to (try to) ensure that software has no vulnerabilities. Every tool vendor is likely to portray their solution as the best one, or at least a necessary one. In reality, what you use depends on your culture, budget, language / environment / frameworks, skills, and time.  



### Pursuing cybersecurity maturity at financial institutions"  
[Deloitte and FS-ISAC survey spotlights key traits among more advanced risk managers]  
By Sam Friedman (United States) & Nikhil Gokhale (India)  
[https://www2.deloitte.com/insights/us/en/industry/financial-services/cybersecurity-maturity-financial-institutions-cyber-risk.html](https://www2.deloitte.com/insights/us/en/industry/financial-services/cybersecurity-maturity-financial-institutions-cyber-risk.html)  

Security teams must continuously strive to fulfill their fiduciary and regulatory responsibilities, while meeting rising expectations for consumer privacy and innovative business solutions.  
This is a material challenge as global financial services enterprises extend their businesses & supporting technology operations into a diverse and expanding ecosystem of Internet-enabled platforms and services.  

Deloitte has worked for the past 2 years with the Financial Services Information Sharing and Analysis Center (FS-ISAC) to survey members on how they are confronting these cyber challenges.  Many North American global financial services enterprises are FSISAC members.  

"Enterprise Risk Management at ________"  
Why and how we identify and manage risk across the company  
"As you identify and understand risks, you can make better, more informed  
decisions about which ones are worth taking and which need to be kept in check  
at all costs." (p. 3, /sites/intranet/bu/Risk/Documents/Enterprise%20Risk%20Mgmt/ERM%20Booklet.pdf)  

Why is it important to manage risk well?
• Our customers rely on it.  
• Our shareholders expect it.  
• Regulators demand it.  
• Rating agencies look for it.  
( p. 5, /sites/intranet/bu/Risk/Documents/Enterprise%20Risk%20Mgmt/ERM%20Booklet.pdf) 

1. Investment and market risk  
 a. Credit risk  
 b. Interest rate risk  
 c. Equity market risk  
 d. Inflation risk  
 e. Foreign exchange risk  
 f. Liquidity risk  
 g. Real estate risk  
2. Product / pricing risk  
 a. Mortality/longevity risk  
 b. Morbidity risk  
 c. Policyholder behavior risk  
3. Operational risk  
 a. Fraud risk  
 b. Employment practices & workplace safety risk  
 c. Business practice risk  
 d. Execution, delivery and process management risk  
 e. Damage to physical assets risk  
 f. Business disruption & system failure risk  
4. Business risk  
 a. Reputation risk  
 b. Regulatory & accounting change risk  
 c. Strategic risk  
(p. 6, /sites/intranet/bu/Risk/Documents/Enterprise%20Risk%20Mgmt/ERM%20Booklet.pdf and p. 1, /gfr/docs/riskmanagementatpfg.pdf)  


### Machine Learning/AI Attack families  
 * DeepFool  
 * Fast gradient method  
 * Basic iterative method  
 * Projected gradient descent  
 * Jacobian saliency map  
 * Universal perturbation  
 * Virtual adversarial method  
 * C&W L_2 and L_inf attacks  
 * NewtonFool  
 * Elastic net attack  
 * Spatial transformations attack  
 * Query-efficient black-box attack  
 * Zeroth-order optimization attack  
 * Decision-based attack  
 * Adversarial patch  


Attacks often occur at application interfaces.  
A typical business application includes a broad range of application interfaces.  

Hostile Professionals are Different  
http://imgs.xkcd.com/comics/security.png  

a.	Case Study A {trading off release time and vulnerabilities. Lesson to learn – early inquisition avoids late surprises}  
b.	Case Study B {matching assets at risk with threats & control responses. Lesson to learn – don’t overspend on low-value assets, match response to exposure.}  
c.	Case Study C {matching controls to system interdependencies. Lesson to learn – Attackers frequently jump systems – deny them a way to use yours. Defense in depth}  


Week Four – July 15-21  
Topic:  Software Engineering and Development Principles  
Readings:  Chapter 7 from Brookshear and Brylow  


Internet-enabled business is complicated, characterized by its tradeoffs, and security is not the center of that universe.  
M:\ \Architecture\Requirements-Diagrams-Chapter-15-Conclusion-Figures.pptx

Ethical behavior is central to business success.  
    In its absence, business devolves into crime.  

There are many risks.  
Most businesses  risk management  

Characterizing Risks  
(use the "Info Sec Risk in Context" diagram)  



Mobile Risks [An ecosystem characterized by organizations (large & small) whose business model depends on monitizing the data they collect about you]
Mobile Security Threat Categories
---------------------------------
 * Malware Targeting Mobile Platforms  
 * Mobile Spoofing / SIM Cloning (Recently, $2M stolen for $580 payment to Telecom employee)  
 * Inadequate Mobile Fraud Controls  
 * Rogue Applications  
 * Misrepresented Applications  
 * 'Infected' Applications  
 * Web Browser Attacks  
 * Marketplace Misrepresentation  
 * SMS Redirection – Hijack or Exploit Forwarding  
 * Vendor Breach  
 * Transport or Protocol Gaps (API implementation matters -- Need SSL everywhere & mutual auth)  
 * User Device Management  
 * Platform Specific Attacks  
 * Device Specific Attacks  

Fraud Scenarios  
---------------  
 * Malware Attack  
 * Phishing/Smishing/Vishing  
 * Impersonation/Hijacking  
 * Identity Theft  
 * System Breach  
 * Browser Attacks  
 * Marketplace Misrepresentation  
 * User/Merchant/Employee/False ID  


Sample Fraud Scenario: Account Takeover (Mobile Transfer)  







Enterprises are not victims, they’re vectors  
While ecosystem-driven business depends on interconnectedness, those connections increase companies’ exposure to risks. Leading businesses are recognizing that just as they already collaborate with entire ecosystems to deliver best-in-class products, services, and experiences, it’s time security  joins that effort as well.   

The Institutes RiskBlock Alliance, a blockchain consortium representing 31 risk management and insurance companies, is building an open, secure ecosystem that any and every insurance and risk management company can plug into.  
Only a quarter (26 percent) of insurance executives know for sure that their ecosystem partners are working as diligently as they are to be compliant and resilient with regard to security.  
["Future of IT:  Art of the Possible." Accenture presentation to _________________, April 2019]  

