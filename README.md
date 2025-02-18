# Cybersecurity & Infrastructure Security Agency

## Course: 210W-05 Industrial Control System (ICS) Cybersecurity Risk

---

## Learning Objective 1: Describe Risk Elements

### Risk Defined:
Risk is measured by considering **Threats, Vulnerabilities, and Consequences** to determine whether a system is at high or low risk for a successful cyber attack.

#### Risk Equation:
```
Threat * Vulnerability * Consequence = Risk
```

### Threat:
A **threat** is the potential for someone to exploit a particular information system vulnerability. In the context of cybersecurity, this would be a hacker. As technology advances, vulnerabilities arise that malicious actors (nation-state actors, terrorist organizations, organized crime, and mainstream threats) can exploit.

#### Three Attributes of a Threat:
- **Capability**
- **Opportunity**
- **Intent**

> If all attributes are present, an attack is likely to succeed. Applying cybersecurity strategies to deter, detect, and mitigate a threat can reduce the attacker's opportunity.

#### Strategies to Deter a Potential Threat:
- **Network segmentation** with strict ingress and egress firewall rule sets.
- **No externally routable network connections.**
- **Network monitoring, host logging, and maintaining a Collection Management Framework (CMF).**
- **Secure credential management** (no credential sharing, Active Directory enforcement, strict account/group management).
- **Incident response plan** (ability to detect and declare cyber incidents).

> The **Internet, removable media, and email** are the main attack vectors for Industrial Control Systems.

### Vulnerability:
A **vulnerability** is any weakness that can be exploited by an adversary or caused by an accident.

#### Examples of Intentional Attacks:
- **Phishing scams** used to gain login credentials.
- **Exploitation of unpatched vulnerabilities** in systems.
- **Pivoting into different networks**, including control systems, to cause harm.

#### Mitigating Vulnerabilities:
- Asset owners should have a **program in place** to provide timely ICS vulnerability information.
- Even with accurate vulnerability data, verification and mitigation can be challenging:
  - **Extensive testing** is needed before applying mitigations (patches) to prevent disruptions.
  - **Strategic planning and downtime** must be considered before implementing patches.
  - **Continuous monitoring** is required to ensure mitigation effectiveness.

### Consequences:
- Consequences in **IT systems** are often measured in **financial loss** (lost revenue, asset replacement, system repair costs, etc.).
- Consequences in **ICS environments** can extend beyond financial loss to impact safety, infrastructure, and operations.

### Risk Management:
- Risk can be adjusted by **altering one or more of the variables** in the risk equation.
- If any **risk equation element is zero, risk is eliminated** (though this is nearly impossible in real-world scenarios).

#### Review Questions:
- **Threat Examples:** Hacker, Tornado
- **Vulnerability Example:** Old Computer
- **Consequence Example:** Stolen Credit Cards

---

## Learning Objective 2: Discuss Elevated Risk Factors

### Cultural and Technical Factors:
- **Cultural Factors:** Involves people and processes involved in designing, building, operating, and maintaining ICS. The shift toward integrating ICS with corporate and customer networks introduces security risks.
- **Technical Factors:** Relates to the actual systems and components making up ICS.

### Cyber Risk to ICS:
#### Cultural - Policies & Procedures:
- Outdated policies and procedures may **fail to account for cybersecurity risks**.

#### Cultural - People (Owners, IT, etc.):
- Many processes were created **without considering cybersecurity risks**, leading to vulnerabilities.

#### Technical - Vendors:
- System-specific vulnerabilities must be **assessed carefully**.
- Security solutions **must not hinder ICS functionality** (e.g., an antivirus program that locks up a control system).

#### Technical - Cybersecurity Vulnerabilities:
- **Legacy devices** (old modems, computers, ICS hardware).
- **Current devices** (security gaps between ICS and networks).

#### Technical - Increasing Threats:
- The number of malicious groups targeting ICS has increased **from 11 to 15**.

#### Technical - Interconnected Networks:
- Poorly protected interconnected networks create security vulnerabilities.

### Control System Solutions:
#### Security Considerations:
- Be **mindful of vulnerabilities** in software (operating systems, browsers, database applications).
- **Don't delay updates and patching** when possible.

#### Review Question:
- Security concerns related to ICS components fall under **technical factors**.

---

## Integrated IT/ICS Networks

- Understanding the **risk of merging IT and ICS networks** is crucial.
- Organizations must **balance risk and reward** when integrating networks.

### Security Concerns:
#### Phishing Emails:
- Often appear legitimate and **include malicious links or attachments**.
- Create a sense of **urgency** to trick targets into acting quickly.

#### Pop-Ups:
- Unexpected pop-ups requesting **sensitive actions** may be signs of malware or phishing attempts.

---

## Availability, Integrity, and Confidentiality

### IT Environments - Security Priorities:
1. **Confidentiality**
2. **Integrity**
3. **Availability**

### ICS Environments - Security Priorities:
1. **Availability**
2. **Integrity**
3. **Confidentiality**

#### Definitions:
- **Availability:** Ensuring system functionality and accessibility when needed.
- **Integrity:** Maintaining **accuracy and consistency** of data throughout its lifecycle.
- **Confidentiality:** Ensuring **only authorized access** to sensitive information.

### Security Mitigations:
- **Communication speeds** must be optimized.
- **Intrusion detection** and monitoring systems are critical.
- **Adequate resource allocation** is necessary for security.
- Security techniques must be **tailored to ICS environments** where availability and integrity take precedence.

---

## Summary
- Stay up to date with the **latest vulnerabilities, threats, and incidents**.
- Be mindful of cultural and technical factors that contribute to cybersecurity risks.
- Identify risks within your **organization’s ICS infrastructure** and work to mitigate them effectively.

---

### 📌 **Resources for Staying Updated:**
- [CISA ICS-CERT](https://www.cisa.gov/ics)
- [MITRE ATT&CK for ICS](https://attack.mitre.org/matrices/ics/)
- [SANS ICS Security](https://ics.sans.org/)

