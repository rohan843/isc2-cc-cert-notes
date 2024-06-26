# ISC2 CC Certification Notes

## Contents

- [ISC2 CC Certification Notes](#isc2-cc-certification-notes)
  - [Contents](#contents)
  - [Security Principles](#security-principles)
    - [The CIA Triad](#the-cia-triad)
    - [Privacy](#privacy)
      - [GDPR: General Data Protection Legislation](#gdpr-general-data-protection-legislation)
    - [Risk Management](#risk-management)
    - [Threats, Vulnerabilities, and Likelihood](#threats-vulnerabilities-and-likelihood)
    - [Examples to threats to the elements of the CIA triad](#examples-to-threats-to-the-elements-of-the-cia-triad)
    - [Governance Elements](#governance-elements)
    - [Risk Identification](#risk-identification)
    - [Authentication](#authentication)

## Security Principles

### The CIA Triad

This triad is composed of 3 key terms: confidentiality, integrity, and availability. It is so-created to make important components of security sound relevant to non - technical people.

**Confidentiality**: Providing authorized access to information, and preventing its improper disclosure.

**Integrity**: A property of information, where it is kept and used in a way that it is accurate, complete, internally consistent, and useful.

**Availability**: Systems and data must be available when the users need them.

### Privacy

**It is the right of an individual to control the distribution of information about themselves.** Privacy is different from security, even though both focus on safeguarding information.

The legislation and regulations on privacy and data can affect organizations _irrespective of their physical location_.

There is a major push towards privacy legislation and compliance with existing policies. There are various laws defining privacy and data protection, which periodically change.

Merely ensuring proper security measures are in place is not enough for organizations to meet privacy regulations. **They are still liable for any mishandling or misuse of data.**

#### GDPR: General Data Protection Legislation

The EU passed this legislation in 2018, deeming privacy to be an individual human right. **GDPR applies to all organizations and individuals doing business in EU.** EU member countries and other jurisdictions such as several states in the US enact laws to enforce privacy regulations. For the EU countries, these laws may be more stringent than GDPR.

Any entity anywhere must abide by the legal requirements of its jurisdiction. It is important to properly assess how these laws apply to our organizations.

> HIPPA (health insurance portability and accountability act) controls the privacy of medical information in the US.

### Risk Management

The level of cybersecurity involved depends on the amount of risk that an entity is willing to accept.

**Risk refers to the potential consequences of what happens in our environment.**

We evaluate risk, and then **implement security controls to help mitigate the risk to an _acceptable level_**. When making decisions based on risk priorities, organizations must evaluate the likelihood, impack and their tolerance towards different kinds of risks. **The risk tolerance is to be decided by the executive management and the board of directors.**

Risks can vary from malware, social engineering, denial of service attacks, fires, crimes, natural disasters, etc.

Risk can be broadly categorized based on probability of occurrence and severity of impact, giving us 4 categories:

| High probability, low impact | High probability, high impact |
| ---------------------------- | ----------------------------- |
| Low probability, low impact  | Low probability, high impact  |

### Threats, Vulnerabilities, and Likelihood

**Threat**: A threat is any circumstance or event that has the potential to adversely impact organizational operations (including mission, function, image or reputation), organizational assets, individuals, other organizations or the nation through an information system via unauthorized access, destruction, disclosure, modification of information and/or denial of service. [NIST SP 800-30 Rev 1] **Essentially, something or someone that attempts to exploit a vulnerability to thwart protection efforts.**

**Vulnerability**: Weakness in an information system, system security procedures, internal controls or implementation that could be exploited by a threat source. [NIST SP 800-128] **Essentially, a gap or weakness in the protection efforts.**

**Threat Actor**: Any individual or group that attempts to exploit vulnerabilities to cause or force a threat to occur.

**Threat Vector**: The means by which a threat actor carries out their objectives.

**Asset**: Something in need of protection.

**Likelihood**: The probability that a potential vulnerability may be exercised within the construct of the associated threat environment.

Consider an example: Tourists are popular targets for pickpockets. Therefore, the existence of pickpockets in a crowded tourist spot is a _threat_ to the people gathered there, even to other pickpockets in the area. If a pickpocket identifies someone as a target, the pickpocket is the _threat actor_ w.r.t. the target. (The target may or may not know about the threat actor.) The approach and technique taken by the pickpocket is their _threat vector_. A pickpocket might choose to select a target that seems distracted or less likely to put up a struggle. In other words, the target appears more _vulnerable_ than other people and the pickpocket feels they can exploit that _vulnerability_.

Note: The same vulnerability may give rise to different threats, for example, a person focused on their phone screen (vulnerability) might be a target of pickpockets or a victim of a traffic accident (threats). **A vulnerability is a weakness, a threat is a potential exploit from a weakness.**

### Examples to threats to the elements of the CIA triad

If a password is shared among employees, or if work devices such as laptops are left unattended, or if there are natural disasters leading to events such as power outages, then the elements of the CIA triad may be threatened.

### Governance Elements

**Regulations and Laws**: These are imposed by national, regional and local governments. E.g., GDPR, HIPPA, etc. Organizations in multiple jurisdictions must comply with the most restrictive laws.

**Standards**: These cover a broad range of issues and ideas. These are well accepted in an industry. Some examples of organizations that create standards are: ISO, NIST, IETF.

### Risk Identification

Risk identification is a recurring process that involves identifying different possible risks, characterizing them and estimating their potential for disrupting the organization. This is done with the prior knowledge of the organization, its situation and its strategic, tactical and operational plans.

Risk must be identified to be communicated clearly.

All employees are responsible for identifying risks.

Security professionals assist in the risk identification process at the system level, focussing on process, control, monitoring or incidence response and recovery.

### Authentication

The process of verifying that a user is the rightful owner of an identity they claim to have. I.e., it is a way to **prove the identity of the requestor.** There are three common methods of authentication:

1. **Something you know**: passwords, passphrases
2. **Something you have**: tokens, memory cards, smart cards
3. **Something you are**: biometrics, measurable characteristics
