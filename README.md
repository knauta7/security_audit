<h1>Security Audit</h1>

<h2>Description</h2>
This project scenario (from the Google Cybersecurity Certificate) will demonstrate my role in conducting an internal security audit for a company called Botium Toys.
<br><br>
<i>Disclaimer: Botium Toys is a fictional company.</i>
<br />


<h2>Scenario: Part 1</h2>

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide.<br><br>
The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).<br><br>
The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department.<br><br>
My task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a controls assessment and compliance checklist. 

- <b>[BOTIUM TOYS: AUDIT SCOPE AND GOALS](https://drive.google.com/file/d/1vJSe_2CyXUg03pfYNKlSOnBN0h73U-20/view?usp=drive_link)</b>
- <b>[BOTIUM TOYS: RISK ASSESSMENT](https://drive.google.com/file/d/1ScpKZfqXjSgSfK6fsFlcR6w_cQBiyG8N/view?usp=drive_link)</b><br><br><br>

Email from the IT manager:<br><br>
<i>Hello!<br>
I have completed the audit scope and goals, as well as a risk assessment. At a high level, the main goals and risks are as follows:<br><br>
<b>Goals:</b><br>
-Improve Botium Toys’ current security posture by aligning to industry best practices (e.g., adhere to the NIST CSF, implement concept of least permissions)<br>
-Provide mitigation recommendations (i.e., controls, policies, documentation), based on current risks<br>
-Identify compliance regulations Botium Toys must adhere to, primarily based on where we conduct business and how we accept payments<br>
-To review the full report, read the <b>BOTIUM TOYS: AUDIT SCOPE AND GOALS</b> document<br><br>
<b>Risks:</b><br>
-Inadequate management of assets<br>
-Proper controls are not in place<br>
-May not be compliant with U.S. and international regulations and guidelines<br>
-Current risk score is 8/10 (high), due to a lack of controls and adherence to compliance regulations and standards<br>
-To review the complete list of assets and risks, read the <b>BOTIUM TOYS: RISK ASSESSMENT</b> document<br><br>
Thank you,<br>
Botium Toys IT Manager</i><br><br>


<h2>Controls Assessment </h2>

<b>Current assets</b><br><br>
Assets managed by the IT Department include:<br>
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Management of systems, software, and servicees: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Vendor access management
- Data center hosting services
- Data retention and storage
- Badge readers
- Legacy system maintenance: end-of-life systems that require human monitoring<br><br><br>

<table>
  <tr>
  <tr><center><b>Administrative Control</b></center></tr><tr>
    <th><th><th><th>
  </tr>
  <tr>
    <th>Control Name</th>
    <th>Control type and explanation</th>
    <th>Needs to be implemented (X)</th>
    <th>Priority</th>
  </tr>
  <tr>
    <td>Least Privilege</td>
    <td>Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs</td>
    <td>X</td>
    <td>high</td>
  </tr>
  <tr>
    <td>Disaster recovery plans</td>
    <td>Corrective; business continuity to ensure systems are able to run in the even of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration</td>
    <td>X</td>
    <td>high</td>
  </tr>
   <tr>
    <td>Password policies</td>
    <td>Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques</td>
    <td>X</td>
    <td>high</td>
  </tr>
     <tr>
    <td>Access control policies</td>
    <td>Preventative; increase confidentiality and integrity of data</td>
    <td>X</td>
    <td>high</td>
  </tr>
   <tr>
    <td>Account management policies</td>
    <td>Preventative; reduce attack surface and limit overall impact from disgruntled/former employees</td>
    <td>X</td>
    <td>medium/high</td>
  </tr>
     <tr>
    <td>Separation of duties</td>
    <td>Preventative; ensure no one has so much access that they can abuse the system for personal gain</td>
    <td>X</td>
    <td>high</td>
  </tr>
</table><br>
<table>
  <tr>
  <tr><center><b>Technical Controls</b></center></tr><tr>
    <th><th><th><th>
  </tr>
  <tr>
    <th>Control Name</th>
    <th>Control type and explanation</th>
    <th>Needs to be implemented (X)</th>
    <th>Priority</th>
  </tr>
  <tr>
    <td>Firewall</td>
    <td>Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network</td>
    <td>NA</td>
    <td>NA</td>
  </tr>
  <tr>
    <td>Intrusion Detection System (IDS)</td>
    <td>Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly</td>
    <td>X</td>
    <td>high</td>
  </tr>
   <tr>
    <td>Encryption</td>
    <td>Deterrent; makes confidential information/data more secure (e.g., website payment transactions)</td>
    <td>X</td>
    <td>medium/high</td>
  </tr>
     <tr>
    <td>Backups</td>
    <td>Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan</td>
    <td>X</td>
    <td>high</td>
  </tr>
   <tr>
    <td>Password management system</td>
    <td>Corrective; password recovery, reset, lock out notifications</td>
    <td>X</td>
    <td>medium/high</td>
  </tr>
     <tr>
    <td>Antivirus (AV) software</td>
    <td>Corrective; detect and quarantine known threats</td>
    <td>X</td>
    <td>high</td>
  </tr>
       <tr>
    <td>Manual monitoring, maintenance, and intervention</td>
    <td>Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities</td>
    <td>X</td>
    <td>high</td>
  </tr>
</table>
<table>
  <tr>
  <tr><center><b>Physical Controls</b></center></tr><tr>
    <th><th><th><th>
  </tr>
  <tr>
    <th>Control Name</th>
    <th>Control type and explanation</th>
    <th>Needs to be implemented (X)</th>
    <th>Priority</th>
  </tr>
  <tr>
    <td>Time-controlled safe</td>
    <td>Deterrent; reduce attack surface/impact of physical threats</td>
    <td>X</td>
    <td>low/medium</td>
  </tr>
  <tr>
    <td>Adequate lighting</td>
    <td>Deterrent; limit "hiding" places to deter threats</td>
    <td>X</td>
    <td>medium/low</td>
  </tr>
   <tr>
    <td>Closed-circuit television (CCTV) surveillance</td>
    <td>Preventative/detective; can reduce risk of certain events; can be used after event for investigation</td>
    <td>X</td>
    <td>medium/high</td>
  </tr>
     <tr>
    <td>Locking cabinets (for network gear)</td>
    <td>Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear</td>
    <td>X</td>
    <td>medium</td>
  </tr>
   <tr>
    <td>Signage indicating alarm service provider</td>
    <td>Deterrent; makes the likelihood of a successful attack seem low</td>
    <td>X</td>
    <td>low</td>
  </tr>
     <tr>
    <td>Locks</td>
    <td>Preventative; physical and digital assets are more secure</td>
    <td>X</td>
    <td>high</td>
  </tr>
       <tr>
    <td>Fire detection and prevention (fire alarm, sprinkler systems, etc.)</td>
    <td>Detective/Preventative; detect fire in the toy store's physical location to prevent damage to inventory, servers, etc.</td>
    <td>X</td>
    <td>medium/low</td>
  </tr>
</table>

<h2>Compliance Checklist</h2>

<b>[ ] The Federal Energy Regulatory Commission - North American Electric Reliability Corporation (FERC-NERC)</b></label><br>
    The FERC-NERC regulation applies to organizations that work with electricity or that are involved with the U.S. and North American power grid. Organizations have an obligation to prepare for, mitigate, and report any potential security incident that can negatively affect the power grid. Organizations are legally required to adhere to the Critical Infrastructure Protection Reliability Standards (CIP) defined by the FERC. <br><br>
    <b>Explanation:</b> NA<br><br><br>
 <b>[X] General Data Protection Regulation (GDPR)</b></label><br>
    GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.<br><br>
    <b>Explanation:</b> Botium Toys needs to adhere to GDPR because they conduct business and collect personal information from people worldwide, including the E.U.<br><br><br>
<b>[X] Payment Card Industry Data Security Standard (PCI DSS)</b></label><br>
    PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. <br><br>
    <b>Explanation:</b> Botiuim Toys needs to adhere to PCI DSS for the protection of the organizations storing, accepting, processing, and transmitting of credit card information.<br><br><br>
<b>[ ] The Health Insurance Portability and Accountability Act (HIPAA)</b></label><br>
    HIPAA is a federal law established in 1996 to protect U.S. patients’ health information. This law prohibits patient information from being shared without their consent. Organizations have a legal obligation to inform patients of a breach. <br><br>
    <b>Explanation:</b> NA<br><br><br>
<b>[X] System and Organizations Controls (SOC type 1, SOC type 2)</b></label><br>
    The SOC1 and SOC2 are a series of reports that focus on an organization’s user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.<br><br>
    <b>Explanation:</b> Botium Toys needs to establish and enforce appropriate user access for internal and external (third party vendor) personnel to mitigate risk and ensure data safety.<br><br><br>

<h2>Scenario: Part 2</h2>
The Botium Toys’ IT manager asked me to conduct an internal audit of the company’s assets, controls, and adherence to compliance regulations and standards. Then, based on the company’s current goals and level of risk, she requested that I complete a controls assessment and compliance checklist to identify and explain ways that the company can improve its security posture. 
<br><br>
My task is to clearly and concisely communicate my findings and recommendations to the IT manager and other stakeholders, so they can implement the necessary controls and create appropriate documentation, processes, and procedures to ensure business continuity, the safety of critical assets, and compliance.<br><br>

<h2>Stakeholder Memorandum</h2>
TO: IT Manager, Stakeholders<br>
FROM: Kenny Nauta<br>
DATE: August 22th, 2023<br>
SUBJECT: Internal IT Audit Findings and Recommendations<br><br>

Dear Colleagues,

Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary and recommendations.

<b>Scope:</b><br>
The following systems are in scope: accounting, end point detection, firewalls, intrusion detection system, SIEM tool. The systems will be evaluated for:<br>
-Current user permissions<br>
-Current implemented controls<br>
-Current procedures and protocols<br>
Ensure current user permissions, controls, procedures, and protocols in place align with PCI DSS and GDPR compliance requirements.<br>
Ensure current technology is accounted for both hardware and system access.<br><br>
<b>Goals:</b><br>
The goals for Botium Toys pertained to the following:<br>
-To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)<br>
-Establish a better process for their systems to ensure they are compliant<br>
-Fortify system controls<br>
-Implement the concept of least permissions when it comes to user credential management<br>
-Establish their policies and procedures, including their playbooks<br>
-Ensure they are meeting compliance requirements<br><br>
<b>Critical findings:</b> (must be addressed immediately):<br>
-Control of least privilege and separation of duties<br>
-Disaster recovery plans<br>
-Password policies, access control policies, and account management policies<br>
-Intrusion detection system (IDS)<br>
-Encryption, backups, and password management system<br>
-Antivirus (AV) software<br>
-Manual monitoring, maintenance, and intervention<br>
-Closed-circuit tv (CCTV) surveillance<br>
-Fire detection and prevention systems<br><br>
<b>Findings</b> (should be addressed, but no immediate need):<br>
The controls and policies that need to be addressed in the future include:<br>
-Time-controlled safe<br>
-Adequate lighting<br>
-Locking cabinets (for network gear)<br>
-Signage indicating alarm service provider<br><br>
<b>Summary/Recommendations:</b><br>
With its growing popularity of Botium Toys, it is essential that their scope and goals are looked at seriously and taken with immediate action to ensure that their customers and employees are protected from threats and risks. It’s recommended to comply with the PCI DSS compliance due to the critical findings that were found, as well as GDPR since the company accepts online payments for its worldwide online store, which includes the E.U. It’s important to also have disaster recovery plans and backups in place to ensure continuity of the company’s business. The development of the proper procedures and policies should be enforced with SOC1 and SOC2 guidance which relates to user access policies and data safety, and would therefore tackle one of their goals of adapting to the concept of least permissions. Integrating IDS and AV software, as well as encryption, into the current systems will support our ability to identify and mitigate potential risks. Installing locks and CCTV at the company’s physical location will help in securing their physical assets and monitor for any potential threats in the future. Though it’s a lower priority, having adequate lighting, installing a time-controlled safe, providing clear signage, and updating the fire detection systems will all help improve the security posture of Botium Toys.



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>