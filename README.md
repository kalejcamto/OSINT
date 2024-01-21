# OSINT
OSINT intelligence is part of the Reconnaissance phase

# Open-source Intelligence
Open-source intelligence or OSINT is conducted on the content or information that is free to use and is in the public domain. You can find data or information that is available and use it for various purposes, such as analysis. In the security domain, open-source intelligence is about using tools and techniques to find information.

It is important to understand that anything that can be found by the security professionals; can also be found by hackers or any kind of threat actor.

Therefore, as a security professional, you should have a strategy to perform open-source intelligence to find information that could be beneficial to any threat actor. You should locate and remove such information from the public domain.

OSINT intelligence is part of the Reconnaissance phase, and it helps you collect important information from public sources. A threat actor has a clear plan in mind to find information about an identified target and can be searched from different sources. However, one of the key issues with OSINT information is that you, as the threat actor, may end with a wide variety and quantity of information.

This may delay the process because more information you find, more time you spend in filtering and finding the information that is relevant to you.

## There are different phases in OSINT. These are:

- Source Identification: The threat actor identifies sources from which information can be gathered.
- Data Harvesting: The threat actor collects information from identified sources.
- Data Processing: The threat actor processes and identifies information that can help in enumerating the target.
- Data Analysis: The threat actor performs data analysis of information that was processed in the previous phase.
- Result Delivery: This is the final phase in OSINT in which information about the target is finalized.
Several sources can be targeted in OSINT. Some of the key ones are:

Social media
WHOIS repository
Search engines
Proprietary/Closed-source Intelligence
Closed-source intelligence is the opposite of open-source intelligence. The closed-source, which is also known as proprietary intelligence, is about gathering information from sources that are closed and are not generally available in the public domain.

Some key sources can include:

Business information
Legal data
Educational records
Banking information
Medical records
Most closed intelligence sources are meant to be confidential or secret and have limited access and then only to selective individuals. This type of information is considered to be the most accurate and reliable as it is validated and stored with limited access.

In most cases, regulations protect such information. For example, in the case of health information, there is the Health Insurance Portability and Accountability Act (HIPAA) in the United States of America that requires the protection of patients’ health records. Anyone dealing with the health records must be regulated under HIPAA and then protect the information as defined with the regulation.

The key intent of the closed-source or proprietary source information is to ensure that its privacy, confidentiality, availability, and integrity must be protected. Therefore, getting access to this information, even though can be difficult, but is the prime source of information as it is already validated and accurate.

Some of the key sources of closed or proprietary information are:

Marketing information that may include competitive position or marketing strategy.
Manufacturing information that may include future product information, formulas, or the methods to develop the product.
Financial information may include the cost of manufacturing the product, targets, profits, balance statements, and order pipeline.
Research and development may include the research information on a specific product that has not been created or is in its inception stage.
There are four key pillars of intelligence gathering or information gathering, and these are known as CART, which stands for:

Completeness
Accuracy
Relevance
Timeliness
Let’s look at each one of them in detail.

Completeness
The intelligence process or information gathering must be complete in all senses. It should be able to provide an appropriate level of detail and enable you to gather a level of information that must help in conducting a full attack.

You, as the Security Analyst, must be able to use this information to find loopholes and be able to protect the infrastructures by filling said loopholes. To be able to respond to a threat, you need to have complete information and sufficient detail.

Threat intelligence must provide sufficient detail to enable a proper response.

Accuracy
Intelligence gathered must be accurate. If it is not accurate, it will lead you to make decisions that will not help you protect information or an infrastructure. Incomplete intelligence can also be severe in consequence as it would not only save you time, but it will also reduce the cost. Therefore, the sources that you use must be reliable.

Timeliness
The intelligence that you gather must be prompt. If you are engaging with a target or trying to protect a target, you need to acquire the information about it much before time. Getting the information about the target after the attack has occurred is of no use.

Relevancy
Intelligence that you gather must address a threat so that you can protect an asset or target. If you are gathering information about the threats that are not relevant to your organization, then such intelligence is of no use.

Confidence Levels
Confidence levels define how sure you are about the occurrence of a particular threat. You can use the confidence level for decision-making and accordingly make changes to the security controls within the domain.

You can use various ratings and define the confidence level. For example, Confirmed gets the rating of 100%, which means that the threat has been confirmed. A sample of confidence levels is given below.

Unknown: 0% (The threat has not been assessed)
Discredited: 1% (It has been confirmed as inaccurate or poses no threat)
Improbable: 2 - 29% (It is possible, but it is not logical to expect)
Doubtful: 30 - 49% (The threat is semi-logical to expect, but not plausible)
Possible: 50 - 69% (The threat is reasonably plausible, and could be exploited)
Probable: 70 - 99% (The threat is definitely plausible, and should be expected)
Confirmed - 100% (Confirmed as accurate and a definite threat)
You can arrive at different confidence levels using different methods. For example, it is the threat from your analysis, or it has been confirmed by external and independent sources. Then, is it a practical threat? Is the threat current or something that may occur in the future? Has the organization faced a threat in the past?

These are some of the factors that you can use to define the confidence levels.

Indicator Management
Indicator Management or Threat Indicator Management is about finding threat indicators and track their movement.

Threat indicator would move through different phases, such as response, detection, and then prevention. It is about tracking movements, and indicator management can be performed using various methods. Some of the key methods are described below.

# Structured Threat Information eXpression (STIX)
STIX is a language that has been developed by a community to provide cyber threat information. It has certain attributes, which are:

Expressive
Extensible
Human-readable
Automatable
There are several uses of STIX. It helps you analyze cyber threats and also provides indicator patterns for cyber threats. STIX also helps you to manage cyber threat prevention, and it also helps in sharing cyber threat information.

It also helps in sharing threat indicators with different users as necessary.

# Trusted Automated eXchange of Indicator Information (TAXII)
TAXII is a free method that helps you exchange and share threat information in an automated way.

With the use of TAXII, organizations can share timely information amongst themselves and also different internal and external communities that relate the cybersecurity.

The adoption of TAXII is simple, and it can be easy with the help of existing protocols, such as HTTP and HTTPS. It can also be used using three different architectures, which are:

Hub and spoke: There is a centralized hub that shares the information with the spokes, which are the partners. The hub can share and receive information from spokes.
Source and Subscriber: One organization or community becomes the central point of information, and it shares the information with their subscriber organizations.
Peer to Peer: Organizations share information. There is no centralized point. Information is shared in an ad-hoc manner.
Open Indicators of Compromise (OpenIoC)
When an attack takes place, it is difficult to trace the indicators of compromise or the methods that the attacker has used. OpenIoC provides a method to address this challenge by providing a standardized format. It helps in defining the standard format for describing artefacts that are discovered during the investigation.

IoC can be of various types. Some of the key IoC that can be tracked using OpenIoC are:

Unusual network traffic that is either inbound or outbound
Unusual activities performed by an administrative or privileged user account
Unusual changes in the operating system or registry
Unusual connections established from
Unusual DNS modifications and requests
Untimely system patching

# Intelligence Cycle
The intelligence cycle is a framework that is used for gathering threat information to prepare an organization to respond to threats. If the intelligence cycle does not exist within an organization, then it will have to respond to threats in an ad-hoc manner. Therefore, it can be used as a base for making security decisions to handle risks that may occur.

The intelligence cycle is mainly used when you need to gather intel, mainly with intelligence or military agencies. With the use of the intelligence cycle, you can process the gathered input and generate actionable tasks.

There are different phases in the intelligence cycle. These phases are:

## - Requirements
This is the first phase of the intelligence cycle. A decision-maker provides the requirements for the information to be gathered.

Collection
After the requirements phase, you need to start with the information collection plan. You have to make a list of the available information sources. The information must be gathered to meet the requirements as stated by the decision-maker.

## - Processing
After gathering information, you need to start with information processing. In this phase, you will need to filter out irrelevant information. Captured information is processed in a manner that it can be used for analysis.

Analysis
After filtering and sorting relevant information, you need to analyze it. This phase requires putting together different pieces of information and generating an output that you require. This is the phase in which the data is processed to be the answer.

## - Dissemination and Feedback
In the dissemination and feedback phase, you need to put the information in a format that is required by the stakeholder. The output is shared with the decision-maker for final evaluation and feedback.

Finally, with feedback, the intelligence loop is closed. The decision-maker provides feedback, and if there is any discrepancy pointed out by the decision-maker, the existing requirements are reviewed and revised if required.

Information Sharing and Analysis Communities (ISAC)
Information Sharing and Analysis Centers (ISACs) are created for specific industries, and they are meant for sharing information. They are meant to protect the critical infrastructure across different industries, such as Automotive, Health, Information Technology, Oil and Gas, and Space.

These organizations gather threat information about in their domain and then share it with the other organizations in both public and private sectors. There are various ISACs across different countries, which are:

Canada: Global Mining and Metals Information Sharing & Analysis Centre (MM-ISAC)
Europe: European Energy - Information Sharing & Analysis Centre (EE-ISAC)
India: National Critical Information Infrastructure Protection Center (NCIIPC)

Let’s look at some of the ISACs across different industries.

## Healthcare
Healthcare Ready, which is the ISAC in the healthcare sector, focuses on strengthening supply chains. It also focuses on building collaboration between the public and the private sectors. One of its main agendas is to safeguard patient's health data by providing best practices to healthcare organizations. Some of its key responsibilities are:

## Training and education
Highlighting the importance of building resiliency into operations and activities that are performed in daily life.
It mainly targets the following:

## Healthcare officials
Policymakers
Organizations
General public
## Financial
FS-ISAC focuses on the financial sector. It is a non-profit corporation that was established by the member organizations in the financial sector. The key role that FS-ISAC plays is to ensure the following:

Help the organizations build resilience and continuity of their infrastructure.
Share threat and vulnerability information with the organizations in the financial sector.
Helps the organizations in training and building collaboration with the other organizations within the financial sector.
## Aviation
The Aviation ISAC is mainly focused on the aviation industry and helps organizations globally by sharing information related to cybersecurity. From time to time, it shares the information with the organizations on the vulnerabilities, threats, and incidents as and when they occur. Some of its key tasks are to:

Share the threat information as and when threats occur.
Help in building strategies against threats that occur.
Help in implementing the best practices in building a secure and resilient infrastructure.
