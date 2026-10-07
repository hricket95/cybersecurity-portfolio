# Computer Fraud Case Studies

**Course:** Chattahoochee Technical College, Cybersecurity program
**Format:** For each case I analyzed what happened, how the attack worked, how it was detected, which computer fraud concepts applied, and what an organization should change. I also wrote true/false review questions for each case to test understanding.

---

## Case 1: Credential Misuse by a Former Employee (Chapter 13)

**What happened.** A former employee had once been given a coworker's email password during an IT help request. After leaving, he guessed that the coworker's new password was a small variation of the old one, logged in, and posted sensitive information online as an act of revenge.

**How it was detected.** Investigators traced the logins to an IP address belonging to a local cable provider, at unusual overnight hours, in the area where the former employee lived. The content was taken down, and he faced federal charges under the Computer Fraud and Abuse Act (CFAA).

**Concepts involved.** Credential/password attack · social engineering · spoofing · insider threat

**Lessons for an organization**
- **Never share passwords, even with IT.** IT staff should reset access rather than ask for a user's password.
- **Ban predictable password changes.** "Password1" → "Password2" is effectively no change. Enforce password history and complexity, and require MFA so a known or guessed password alone isn't enough.
- **Revoke access immediately at offboarding**, and audit any credentials the departing employee may have seen.
- **Monitor for anomalies.** Logins at unusual hours from unfamiliar networks are exactly the signal that solved this case. Alerting on them catches problems sooner.
- **Build a security-awareness culture.** Most of this attack was enabled by human error, not technical weakness.

---

## Case 2: Counterfeit ID and Check-Fraud Operation (Chapter 14)

**What happened.** A group ran a scheme built on stolen mail, stolen checkbooks, and counterfeit driver's licenses. They used computers and printers to produce fake IDs matching stolen identities, "washed" checks (chemically removing ink so the check could be rewritten), and impersonated victims to cash them. The group even attempted to defraud a sheriff's office.

**How it was detected.** Investigators found counterfeit identification being produced on a computer, which led to the seizure of computers, printers, laminating materials, stolen mail, checkbooks, and fake IDs. Additional arrests followed, and the two lead participants each received prison sentences of roughly four years.

**Concepts involved.** Identity theft · digital forgery and document counterfeiting · check and card fraud · digital tampering

**Why it's a computer fraud case.** The computers weren't incidental. They were the production line. Without them, the group couldn't have produced convincing IDs at scale.

**Lessons**
- **Digital devices are evidence.** Investigators should examine every computer, printer, and storage device, not just the physical fraud materials.
- **Physical security feeds digital fraud.** Stolen mail was the starting point. Locked mailboxes, paperless statements, and credit monitoring cut off the raw material.
- **Verification beats appearance.** Banks and businesses that verify identity against systems, not just a card that looks real, stop this kind of fraud.

---

## Skills demonstrated

Incident analysis · threat identification · understanding of the CFAA · recommending controls (MFA, password policy, offboarding, monitoring) · digital evidence awareness · clear written communication for non-technical readers
