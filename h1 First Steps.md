# First Steps

https://terokarvinen.com/2023/information-security-2023-autumn/#homework

## Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains: A Summary

Advanced Persistent Threats (APTs) are a new domain of threats that threaten sensitive areas. APTs are able to circumvent traditional securities placed into networks. Traditionally, security measures are knowledgable of previous efforts and methods, and build their security capabilities upon previous attempts. The kill chain model offers insight into how an adversary performs an attack, and understanding the adversary allows us to identify our weak spots and reinforce them. Alternatively, we can also use the kill chain to identify our adversary and engage them. 

Each link in the chain leads to the next stage, and inability to succeed in any part of the chain naturally halts the progress of the chain, and the objective cannot be accomplished. The cyber kill chain presented in the paper is specific to intrusions, and contains seven stages: 

1. Reconnaissance: Gathering information, so we can identify what we want to attack, and how. 

2. Weaponization: Making the attack into a deliverable format. 

3. Delivery: Once weaponized, the delivery method is identified. Generally, the delivery methods are email attachments, physical USB devices, and websites. 

4. Exploitation: The attack targets and exploits a specific application or OS weakness. 

5. Installation: The attack is installed onto the exploitable system. 

6. Command & Control: Secure remote access on the targeted system. 

7. Actions on Objectives: The objectives set to be accomplished are acted upon.

As mentioned above, the cyber kill chain can be used by defenders to identify areas within their own framework that can be improved and fortified, and plug any weak spots. Understanding how an enemy might attack the defender is crucial for pre-emptive defense. The paper by Hutchins et al. illustrates a matrix on courses of action which identifies what stages of the cyber kill chain can be detected, denied, disrupted, degraded, deceived, or destroyed. The matrix shows methods that defenders can employ to protect themselves from hostile actors.

Zero-day exploits are so called as they are entirely fresh exploits that have recently been identified, and there is roughly 'zero days' to fix the vulnerability. They are aptly named for their urgency. If an zero-day exploit or zero-day attack work in tandem with previously identified weaknesses, they are more likely to be ineffective in achieving the objective set out to execute.

Defenders must stay constantly vigilant of security threats and exploits, as new exploits are identified over time. Likewise, old exploits can be re-used as new techniques are adopted for different stages of the cyber kill chain, in order to circumvent existing courses of action defenses.

* Hutchins et al. Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains. URL https://lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf

## Ep 47. Project Raven

* The host, Jack Rhysider, interviews David, a self-described offensive intelligence analyst. David's job is to investigate foreign actors who try to access US infrastructure.
* David began his career in the United States Armed Forces, before moving to the NSA. Following this, David is recruited to CyberPoint, a company that is contracted to hack systems.
* David was assigned to a hacking unit known as 'Project Raven', and were based in the United Arab Emirates.
* Project Raven would front as an unit focused on defensive cyber measures. In actuality, they conducted offensive cyber operations for the UAE's secret intelligence agency (NISSA).
* Project Raven would spy on targets and 'vacuum' data from the targets devices without the targets ever knowing they were spied upon.
* Initially, Project Raven would focus on data exfiltration. Eventually, the UAE government requested Project Raven to gain access to a foreign governments network (to see if they were funding terrorists).
* Project Raven successfully accessed a VPN portal of the foreign government using default credentials, which were U:administrator and P:administrator.
* Using this exploit, David's team was able to access IPs and and passwords for other areas of the foreign governments network outside this VPN portal.
* The UAE government was very keen on all the information that David's team could access, monitor, and learn from.
* In essence, the legality of everything was extremely murky, and David describes that they were in essence 'cyber-mercenaries'.
* It was discovered that Project Raven had collected data on US citizens as well, something that did not sit right with David and other employees.
* The red flags were starting to prop up and David was able to leave Project Raven, although the unit would continue working after David and many other employees left.
* Project Raven would be used for the UAE's political agenda, which involves suppressing dissent about human rights issues.
* Rori Donaghy, a human rights activist and journalist who documented human rights issues in UAE, would be among those targeted and succesfully infiltrated by Project Raven.
* Project Raven and CyberPoint's contract with the UAE would eventually be terminated and replaced with a new contractor known as DarkMatter.

TRANSCRIPT: https://darknetdiaries.com/transcript/47/

## Fundaments of Security

What I consider the fundaments of security are identifying why something needs to be secure, how that something will or should be secured, and the effectiveness of theose security measures. The objective of security is to provide a safe environment for that which should be secured. If something that should be secured cannot be secured, we must atleast identify how it could be accessed, and have contingency plans in place in case of a breach. 

