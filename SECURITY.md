# Summary and Guidance
We/our refers to the organization USAF.


## Security Program Overview

- **Information Security Program and Scope**

  _This describes the USAf’s information security program scope and high level program management processes._

- **Understanding the Policies and Documents**

  _This describes how information security policies are structured._

- **Metrics and Reporting**

  _This describes the key metrics and high level reporting process for the information security management program._

## Security Architecture and Operating Model

- **Security Principles**

  _This describes the high level operating principles of a DevOps oriented security program. The cloud-native, zero-trust approach enables a modern security operating model and eliminates the need for certain legacy security controls._

- **Security Architecture**

  _A good security architecture is the starting point of a strong program foundation. We will need to maintain an up to date architecture diagram for security reviews with customers and auditors._

- **Metrics and Reporting**

  _We will need to define a set of KPIs and metrics for monitoring and reporting on the effectiveness of the security controls._

## Roles, Responsibilities and Training

- **Assignment of Roles and the Security Committee**

  _Regulatory compliance frameworks, such as HIPAA, require formal assignment of security and privacy responsibilities to someone in your organization. As the organization expands and matures, you may want to form an executive level security committee to meet this requirement. Often, such a committee is a requirement of security certifications such as HITRUST CSF. You can manage this role assignment manually (I.E. in this documented policy/control procedure)._

- **Policy and Compliance Training**

  _You will need to ensure all your employees are properly trained on the security policies and procedures. You may leverage a full featured learning management system (LMS) to develop, distribute, and track this training._

- **Ongoing Security Awareness Training**

  _Ongoing security awareness training is foundational to the overall risk reduction for any organization, not to mention is a compliance requirement almost universally._

## Policy Management

- **Policy Management Process**

  _Security policies and procedures are living documents.  They should be reviewed, updated, and distributed on a regular basis.  Our recommendation is to manage policy as code (e.g. as a git repo), and this procedure provides the details on how to do that._

## Risk Management and Risk Assessment Process

- **Risk Management Process**

  _Risk management involves conducting risk assessment, risk analysis, risk mitigation and the continuous monitoring and management of risks. Risk management is a continuous process.

- **Risk Assessment and Analysis**

  _At least annually, a risk assessment should be conducted for your organization. A well established process helps your team perform the assessment and manage the outcome. The assessment itself is often performed manually, supported by tools for the assessment of technical risks, and management tools to help document and track the issues identified. You may document the issues directly in an issue tracking system such as Jira.

- **Risk Mitigation and Monitoring**

  _Once the risks are identified and analyzed, they need to be addressed with appropriate mitigation plans and implementation of controls. The mitigating controls and residual risks should be continuously monitored and kept up-to-date._

- **Risk Registry**

  _In many cases, the risk registry is no more than a spreadsheet that serves as the inventory of risks identified as part of each risk assessment. Most mature enterprises implement a Governance, Risk and Compliance (GRC) solution to manage this process.  However, a full blown GRC solution is complex and often overkill for a SaaS company.

## Compliance Audits and External Communications

- **Compliance Program Management**

  _Your organization needs to define and document a process to identify and ensure compliance with applicable statutory, regulatory, and contractual requirements._

- **Requesting Audit and Compliance Reports**

  _You should have a pre-defined process for external entities to request audit and compliance reports._

## System Audits, Monitoring and Assessments

- **Types of System Audits**

  _There are several forms of system audits and they are defined here._

- **Security Event Analysis**

  _Security logs, events, and audit trails should be reviewed on a regular basis.  In a mature security practice, this is a major effort of the daily security operations.  It should be monitored proactively instead of when a breach occurs. The sheer volume of events can quickly result in alert fatigue. 

- **Manual Internal Auditing Activities**

  _From time to time, an internal audit may be needed on controls and processes that are not already covered via automated monitoring. This process is defined here._

- **Audit Requests**

  _The procedure documents how audit requests are handled._

- **Review and Reporting of Audit Findings**

  _Upon completion of an audit or assessment, the report and findings should be analyzed so that follow up on actions can be taken accordingly._

- **Audit Trails - System and Application Security Events Logging Standard**

  _Your systems and applications should be configured/developed to follow a pre-defined, pre-approved set of standards for logging. This document captures the details, while it is up to your engineering team to follow in actual implementation. This can be enforced by other procedures such as configuration management and code reviews._

- **Audit Trail Integrity - Security Controls and Log Retention**

  _Audit trails should be immutable. It is crucial to protect audit trails for record keeping and forensic analysis. Audit logs shall be retained according to your business needs and regulatory compliance requirements._

- **Auditing Customer and Partner Activity**

  _You may want to have a process defined to monitor the security logs and account access activities for the customers of your product._

- **Tools Used for Auditing and Security Assessments**

  _This is a documentation of certain tools your team may choose to use for performing security audits and assessments (such as an internal vulnerability scan)._

- **Tools Used for Auditing and Security Assessments**

  _Workforce members (and customers, if applicable) shall be informed and trained on the system auditing processes._

## HR and Personnel Security

- **Acceptable Use of End-user Computing**

  _The acceptable use policy should be distributed to all employees. Employee review and acceptance of the acceptable user policy should be captured._

- **Employee Screening Procedures**

  _Background checks should be conducted as part of the hiring process, prior to an employee/contractor starting._

- **Employee Onboarding Procedures**

  _When new employees join your organization, a set of activities are required as part of their onboarding, such as training, access provisioning, and configuration of their workstations. This procedure documents that process, while the actual implementation of them are covered by their corresponding procedures and controls._

- **Employee Exiting/Termination Procedures**

  _Similar to employee onboarding, when someone leaves your organization, a set of actions shall be performed.  This may include termination of access, return of equipment, etc._

- **Employee Issue Escalation**

  _As part of your HR operations, you should have a defined process for an employee to safely escalate an issue that might arise in the workplace._

- **Whistleblower Policy and Process**

  _Your organization should define policies and procedures to ensure a proper channel is established for reporting concerns and violations with respect to standards of business and personal ethics and conduct._

- **Non-Compliance Investigation and Sanctions**

  _All workforce members should be trained on and accept your organizational security policies and procedures. In the case of a violation, there should be a pre-defined procedure to identify, investigate, and fairly treat each incident._

## Access

- **Standards for Access Provisioning**

  _You need to be able describe how your access control is implemented.  For example, using role-based access control, unique account/ID for each user, automatic log on/log off, etc. These should match the configuration of your identity provider or access control system such as Okta._

- **Password Management**

  _You need to have policies/standards around password length, complexity, age, etc.

- **Centralized Access Control and Single Sign On**

  _USAF most likely relies on multiple business applications to support its operations, including it’s websites. This may include end-user systems, collaboration tools, development and production environments, etc. Managing access to all of your business applications and systems centrally ensures consistent access policy and auditing. Being a cloud-native organization, I highly recommend using a cloud-based identity provider, such as Okta, OneLogin, Google and others for centralized access control and single sign on._

- **Multi-factor Authentication**

  _Passwords are hard to remember but easy to compromise. Even with long and complex passwords, it is no longer sufficient by itself as the only control to prevent unauthorized access to critical systems and data. Okta and other similar IdP vendors provide multi-factor authentication (MFA) capability as part of their offering, and it is very easy to enable especially if you already use it for single sign on._

- **Role Based Access Control (RBAC)**

  _Role based access control (RBAC) is an industry standard method for implementing access authorization to users. This is supported by most identity and access systems as 'Groups' and assigning users to the 'Groups' that match their job function/role._

- **VPN Remote Access**

  _Remote access is typically secured via VPN. This could be implemented as a server on whatever private network in your hosted or internal environment. Pritunl is a lightweight, OpenVPN based solution that is free to start, and can scale as you grow. WireGuard is a good open-source option as well._

{{#needStandardHIPAA}}
- **Access to PHI/ePHI**

  _Access to PHI/ePHI should be limited to those with a business need only, and protected by strong access control and auditing. Additionally, an extra layer of protection may be added to restrict risky or privileged actions.  This can be implemented using Explicit Deny actions policies.  A tool like Dome9 can help automate that process._
{{/needStandardHIPAA}}

- **Platform Customer Access to Systems**

  _I strongly recommend against any direct customer access to systems, other than through the application interface, such as an authenticated Web UI or API interface. Depending on the nature of your solution, you will need to document how customers access their data and if they have direct access to the systems that host/process their data._

- **Access Establishment, Modification and Termination**

  _From time to time, you may need to add, change, or remove access to certain resources for an employee/contractor. It is required you have a process to capture the request, approval, and provisioning of such actions. If you already use an issue management tool like Jira, it is pretty straightforward to create a Service Desk project and manage it there._

- **Access Reviews**

  _Your security/audit/compliance team should perform regular access reviews to understand who has access to what.  This is done in order to maintain the minimum need-to-know best practices when provisioning access. The access should be documented and updated regularly.  Access no longer needed should be removed.  This process typically involves a manual review of all business applications, systems, cloud accounts and mapping the level of access to each user and/or service. It can take days, if not weeks, to complete._

- **Privileged Access**

  _A privileged user is someone who has administrative access to critical systems or data, for instance the USAF President. This type of access should be highly restricted and managed with a more controlled process than typical/non-privileged user access. There are security solutions dedicated to privileged access management. However, you might not need to purchase and implement a separate tool if you follow the recommended procedure using cloud-native SSO._

- **Service Accounts**

  _The provisioning of access given to application services and components should be managed as code._

- **Production Access and Secrets Management**

  _In additional to privileged user access, how do your applications and services gain access to keys and secrets in production? You need tools and controls around that._

- **Password Reset and other Helpdesk Requests**

  _Password reset is most likely self service. In any case, if there is a need for someone with Administrative access to help someone else reset their password, a process should be properly followed for audit and compliance.  This is pretty straightforward if you just implement a Service Desk project in Jira. It can be the same IT & Security service desk project that you use to manage other similar tickets._

## Asset Inventory Management

- **Digital Asset Inventory**

  _You will need to maintain an up-to-date inventory of your physical assets, such as virtual machine instances, database instances, data repositories, etc._

- **Paper Records**

  _We are in the age of the cloud, are we not?  Let's not use paper records for any sensitive data, and this procedure indicates so._

## Data Management

- **Data Classification Model**

  _How do you know what data to protect and how to protect it accordingly? Taking a one-size-fits-all approach is not the best approach to data security. Treating all data the same way is like saying I'm going to put the strongest lock on every door of my house, but whoever needs access, I'll just hand over the same key. Having a good data classification is paramount to your data protection strategy. I recommend four levels of classification - Critical, Confidential, Internal, and Public. This documentation describes the details._

- **Data Handling Process**

  _How data is handled, including the retention period and whether or not encryption of data is required, should be defined based on the company data classification model._

- **Data Inventory and Lifecycle Management**

  _Keep an up-to-date inventory for all of your data repositories, properly tag data according to their data classification. The lifecycle of data should be tracked from its creation to deletion._

- **Data Deletion Procedures**

  _You should only keep data for as long as needed per business and/or regulatory requirements. A well defined process should be in place to securely delete data when necessary. For systems that you self manage, using a secure wipe utility such as Shred is usually sufficient. For data managed in the cloud, you should follow the documented procedures from the cloud service provider._

## Data Protection

- **Data Protection Implementation and Processes**

  _You need to properly document how data is protected according to its classification. This should cover controls such as encryption and access control for data at rest, data in transit, and data in use._

- **Protecting Data At Rest**

  _Data-at-rest refers to persistent data storage, including physical media such as laptop hard drives, virtual data volumes, and logical data repository. Strong encryption, typically AES-256, and key management is typically required to protect data-at-rest._

- **Protecting Data In Transit**

  _Data-at-rest refers to data being transmitted from one system/service to another, either internally or across an open network (e.g. the Internet). Encryption is required, typically in the form of HTTPS/TLS, SSH or IPSec VPN._

- **Protecting Data In Use**

  _Data-in-use refers to active data being processed by systems and applications. Application layer security capabilities and access control mechanisms typically apply._

- **Encryption Key Management**

  _Encryption is only as strong as its associated key management process._

- **Certificate Management**

  _SSL/TLS certificates should be managed and monitored._

- **Data Integrity Protection**

  _There may be additional considerations for data integrity protection applicable to your applications and environments, in addition to data encryption._

## Secure Software Development and Product Security

- **Software Development Process**

  _How do you ensure security in your product development lifecycle? There are specific controls such as static application security testing (code scanning) that are documented individually. Here, you need to start with documentation the overall software development process and standards your development team follows._

- **Source Code Management**

  _A source code management system such as GitHub, Bitbucket or GitLab should be used._

- **High Level Application Security Requirements**

  _A set of high level application security requirements should be defined. This is the foundation for training your development team on secure coding, and it serves as the basis for security considerations throughout your product design. OWASP is referenced as a key part of the high level requirements._

- **Secure Design and Application Threat Modeling**

  _Security should be built in to your application / product as early as possible, starting from the design phase. Proper security consideration and even formal threat modeling can help dramatically reduce risk around application logic flaws, that are difficult to uncover with any scanning software, often lead to significant adverse impact, and are the most costly to fix down the road._

- **Access Control of the Application (Identification, Authentication, Authorization, Accounting)**

  _If your organization develops external facing applications with access to customer data, such as PII/ePHI, you must implement and document mechanisms for user identification and access control._

- **Free and Open Source Software (FOSS) Security**

  _Modern software development is much more than first party code. The open source dependencies used in your software application should be scanned for vulnerability to ensure they do not put your offerings and customers at risk. A recommended solution to scan for open source package vulnerabilities and licensing issues is Snyk.io. Snyk's engine also powers Javascript libraries linting in Microsoft Sonar and Google Chrome browser._

- **Static Application Security Testing (SAST)**

  _The software code written by your developers should be scanned for vulnerability before putting into production. Veracode, WhiteHat, etc. are example solutions that support most modern programming languages such as Java, Javascript, Python, etc._

- **Dynamic Application Security Testing (DAST)**

  _In additional to static code analysis, a dynamic application scan should be performed regularly. This is a blackbox testing of the application from an external perspective. Suitable solutions for dynamic scanning include Tenable, Veracode, Rapid7, Qualys, and OWASP Zap. Keep in mind that dynamic application scanning helps uncover many vulnerabilities but it is not a replacement for application penetration testing._

- **Application Penetration Testing**

  _An external penetration testing is performed at least once a year by a qualified security professional. Many compliance frameworks require this to be done by an external third party security vendor. I also strongly recommend having a public vulnerability disclosure program, often known as bug bounty, to leverage crowd-sourced security researchers to perform continuous testing of your external-facing applications. The recommended vendor is HackerOne (BugCrowd is also a good alternative)._

- **Outsourced Software Development**

  _If you leverage outsourced resources for software development, a formal set of requirements and processes must be established to ensure the quality and security of the product._


## Configuration and Change Management

- **Configuration Management Processes**

  _There are many approaches to configuration management. My recommendation for USAF organization is to let the users manage the devices themselves, but provide them the requirements and automation scripts as necessary, and use an endpoint audit agent to check for compliance._

- **Production Systems Provisioning**

  _Defines the standards and processes for provisioning and promoting systems into production._

- **User Endpoint Security Controls and Configuration**

  _Define the security controls and configuration standards for end-user systems. A provisioning management system may be used, or this can be accomplished via a set of automation scripts that runs on each local system to handle the initial configuration.  For end-user systems that are self managed by each employee, you should provide them with the configuration standards and the automation scripts, if applicable._

- **Server Hardening Guidelines and Processes**

  _Define the standards for provisioning and hardening a new server system based on its operating system and operating environment. A provisioning management system may be used, or this can be accomplished via a set of automation scripts that runs on each local system to handle the initial configuration.  For end-user systems that are self managed by each employee, you should provide them with the configuration standards and the automation scripts, if applicable._

- **Configuration and Management of Network Controls**

  _USAF will have a combination of cloud and on-premise networks. Certain network layer security controls should be in place, such as firewalls for traffic filtering, Subnets/VLANs for segregation, IDS/IPS, etc. For traditional on-premise networks, these controls are typically physical or virtual appliances. In the Cloud, these are often infrastructure and platform services you should enable._

- **Patch Management Procedures**

  _The simplest way to ensure your end-user systems are patched is to enable auto-update.  You can use the same configuration compliance audit agent to ensure auto-update is turned on for all systems (Windows, macOS, Linux) in your environment._

- **Production Deploy / Code Promotion Processes**

  _Each production deploy should follow a defined process to ensure proper review, approval and traceability. This can be fully automated using the appropriate code integrated with your continuous integration / continuous deploy orchestration such as Jenkins or Travis CI._

- **Emergency Change**

  _Emergency conditions should be considered.  Should there be a need for an emergency change that cannot follow your typical change management process, this emergency process should be followed instead._

## Threat Detection and Prevention

- **Malware Protection**

  _Anti-malware continue to be a compliance requirement, although traditional AV solutions have been proven to be ineffective against zero-day attacks and advanced malware. Modern operating systems usually come with some basic malware defense capability, such as Windows Defender. You may also consider something like ClamAV as a free, open-source solution to meet compliance needs. But for real security, I highly recommend a next generation endpoint protection solution such as Carbon Black Cb Defense or SentinelOne._

- **Firewall Protection**

  _Firewall protection should be enabled at the appropriate layers, including network, host and application._

- **Web Application Protection**

  _For our web application in your product portfolio, we should definitely consider deploying a web application firewall and protection against DDoS attacks._

- **Threat Intelligence Monitoring**

  _As part of your ongoing security operations, you need to be informed of new regulations, compliance requirements, as well as valuable external threat intel that might help your spot indicators of compromise in your own environments. A good source of intel is the various Sector-based Information Sharing and Analysis Centers (ISACs). For example, if you are in the healthcare industry, it is recommended for you to become a member of the National Health Information Sharing and Analysis Center (NH-ISAC)._

## Vulnerability Management

- **Vulnerability Scanning and Infrastructure Penetration Testing**

  _Vulnerability scanning for your infrastructure (not applications) is a must. OpenVAS is an excellent open source solution that you can run yourself._

- **Security Findings Reporting, Tracking and Remediation**

  _Vulnerability findings can come from a variety of sources, such as open source dependency scanning, static application code analysis, dynamic application security testing, penetration testing, infrastructure vulnerability scanning, etc. Tracking the vulnerabilities and ensuring they are remediated in a timely manner can be an exhausting task if handled manually. JupiterOne can connect to the various vulnerability sources and help manage them in a consistent and automated manner. The vulnerability management program, including the detailed process and SLA levels, should be well defined._

## Mobile Device Security and Media Management

## Business Continuity and Disaster Recovery

- **BCDR Objectives and Roles**

  _You should have a plan and procedures for business continuity and disaster recovery. The process should be documented and tested. This is mostly a manual effort. First and foremost, clear objectives should be established and a team with specific roles and responsibilities should be assigned._

- **General Disaster Recovery Procedures**

  _Document the DR procedures including notification of a disaster, activation of the DR process, recovery and reconstitution._

- **BCDR Testing and Maintenance**

  _The business continuity and disaster recovery plan and process should be regularly tested and maintained. This can be in the form of tabletop exercise, simulation and/or technical testing such as data restore._

- **Application Service Event Recovery**

  _You should include a process that describes how you recover from a service outage that impacts your application, including notification to users/customers._

- **Production Environments and Data Recovery**

  _You should include a process that describes how you recover your production environments and data._

## Incident Response

- **Security Incident Response Team (SIRT)**

  _To support incident response efforts, you should form a security incident response team. If you do not have dedicated security operations resources, this team can be made up with your engineering and DevOps resources. They are the go-to people when an inevitable incident occurs._

- **Incident Management Process**

  _In the inevitable event of a security incident, you should have a tested process to follow instead of panicking at the moment of impact._

- **Incident Categories and Playbooks**

  _A set of playbooks are referenced here according to the defined categories of incident. This can be done manually by following the playbooks.  As your security practice matures, you may later consider implementing a dedicated incident response / forensic solution._

- **Emergency Operations Mode**

  _If a security incident escalates into an emergency situation, you should have a set of pre-defined procedures to avoid unrecoverable data loss._

- **Tabletop Exercise**

  _Practice makes perfect. Perform drills according to incident response procedures, playbooks, and emergency procedures so that you know what to expect in an real event._

## Breach Investigation and Notification

- **Breach Investigation and Notification Process**

  _Wish for the best and prepare for the worst. In the unfortunate event that a breach occurs, you need to have defined procedures for the investigation and notification of such breach._

- **Platform Customer Responsibilities in a Possible Breach**

  _A breach is sometimes caused by the customer and not you. You should clearly define and communicate such responsibilities to your customers._

- **Sample Notification Letter to Customers in Case of Breach**

  _If a breach is confirmed, you are legally obligated to notify your customers.  A notification template helps your streamline this process._

## Third Party Security and Vendor Risk Management

- **Vendor Technology Risk Review**

  _A technology risk review / security assessment should be conducted prior to engaging with a vendor that involves any type of data exchange, technical integration or professional services. There are a number of options on commercial IT Risk Vendor Management solutions. However, instead of jumping in on one of those, I recommend starting with Google's open-source Vendor Security Assessment Questionnaires (VSAQ). Its Github repo has detailed usage instructions._

- **Vendor Contractual Agreements**

  _Your vendors and subcontractors must meet certain legal and contractual requirements under regulations such as HIPAA - Business Associate Agreement (BAA), and GDPR - Data Processing Agreement (DPA)._

- **Software and Systems Acquisition Process**

  _You should maintain a list of approved software and vendors. A process should be defined and agreed on with your procurement lead for the acquisition of new system or software._

## Privacy Practice and Consent

- **Privacy, Terms and Consent Notices**

  _Create and publish Privacy Policy, Notice of Privacy Practices, as well as Terms and Conditions for using your product, as applicable. Any change should be promptly and formally communicated to all customers._

## Addendum and References

[created by blancos khim](https://github.com/bkhim)

- **Key Definitions**

- **Employee Handbook**

- **Approved Software**

- **Approved Vendors**

- **Cookie Policy**

- **Privacy Policy**

- **HIPAA Business Associate Agreement**

- **GDPR Data Processing Agreement**

- **HIPAA Controls Mapping**

- **NIST Controls Mapping**


