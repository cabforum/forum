## S/MIME Certificate Working Group (SMCWG) Charter - Version 1.1

The S/MIME Certificate Working Group ("SMCWG") exists to perform the activities as specified in this Charter, subject to the terms and conditions of the CA/Browser Forum Bylaws and the Intellectual Property Rights Policy, as such documents may change from time to time. 

**Charter Expiration:** The SMCWG is chartered indefinitely until it is dissolved as specified in Bylaw 5.3.2(3).

**Type(s) of Voting Members Eligible to Participate:** Voting members of the SMCWG may be Certificate Issuers and Certificate Consumers as defined herein.  Other participants have an interest in the secure e-mail and S/MIME ecosystems.

**Voting Structure for WG:** The rules described in Bylaw 2.3 and 2.4 SHALL apply to all ballots.

### 1.	Working Group Scope

**1.1 Summary of Working Group Goals and Objectives** 

An S/MIME certificate contains a public key bound to an email address; and may also contain the identity of a natural person or legal entity that controls such email address. The key pair can then be used to sign, verify, encrypt, and decrypt email. 

An S/MIME certificate can be identified by the existence of an Extended Key Usage (EKU) for `id-kp-emailProtection` (OID: 1.3.6.1.5.5.7.3.4) and the inclusion of a `rfc822Name` or an `otherName` of `type id-on-SmtpUTF8Mailbox` in the `subjectAltName` extension.

The objective of an S/MIME certificate is to provide cryptographic security services for electronic messaging applications, namely sender authentication, message integrity, and message privacy through encryption. For effective authentication and privacy, it is imperative that the CA validates the subject’s identity (if present) and its email address. The recipient of a digitally signed message can authenticate an email message to receive protection against email spoofing and can encrypt a response to the original sender by referring to the public key, email address, and distinguished name (if present) contained in an S/MIME certificate.

The primary use case under consideration for the SMCWG is a model whereby senders and recipients of email messages receive “reasonable assurance” that the other party to the communication identified in the certificate has control of the domain or email address being asserted. A variation of this primary use case is where an individual or organization digitally signs email to establish its authenticity and source of origin.

Therefore, in order to provide reasonable assurance, it is crucial to establish a standard method to validate an email address and the subject’s identity (if present) prior to binding them to the public key. “Reasonable assurance” is to be determined and defined by this SMCWG through studying the existing methods that exist in the industry, as well as identity management frameworks and any applicable legislation.

An S/MIME certificate can also be used in an automated message with transfer agents that use cryptographic security services that do not require any human intervention, such as the signing of software-generated documents and the encryption of fax messages sent over the Internet. While these existing use cases are not in scope for the SMCWG, care will be exercised by the SMCWG to avoid unintended adverse effects to these uses. The security, stability and resiliency of the Internet shall be taken into consideration when the SMCWG forms its consensus. The SMCWG will consult other technical communities when and as necessary.

The objective of the SMCWG is to provide documents that describe an integrated set of technologies, protocols, identity-proofing, lifecycle management, and auditing requirements that are necessary for the issuance and management of Publicly-Trusted S/MIME Certificates.

### 2.	Summary of Work

**2.1 Guidelines** 

The authorized scope of the SMCWG SHALL be to discuss, adopt, and maintain policies, frameworks, and sets of standards related to the issuance and management of S/MIME certificates by CAs under a publicly trusted root.

The primary deliverable of the SMCWG SHALL include the "Baseline Requirements for the Issuance and Management of Publicly-Trusted S/MIME Certificates" which SHALL be scoped as follows:

- Verification of control over email addresses;
- Identity validation for natural persons and legal entities;
- Key management and certificate lifecycle (subject to coordination with other Forum WGs to ensure consistency and avoid redundancy);
- Certificate profiles for Subscriber and Issuing CA certificates (including the appropriateness of extensions and when those extensions should be present);
- CA operational practices, physical/logical security, etc.

Deliverables of the SMCWG SHALL be constrained to certificates that contain the emailProtection (OID: 1.3.6.1.5.5.7.3.4) EKU or that are technically capable of such issuance.

**2.2 Other Deliverables**

The SMCWG MAY work on related deliverables and non-normative documents, seeking to improve the adoption and usability of S/MIME certificates and secure email.

### 3.	Membership

**3.1 Membership Criteria**

The SMCWG SHALL consist of two classes of Voting Members, Certificate Issuers and Certificate Consumers, meeting the eligibility criteria below.

A **Certificate Issuer** eligible for voting membership in the SMCWG MUST have a publicly-available audit report or attestation statement based upon a publicly-available audit criteria or attestation scheme relevant to the issuance of S/MIME certificates. This includes, but is not limited to, the following schemes and criteria:

* WebTrust for CAs v.2.0 or newer; or
* ETSI EN 319 411-1, which includes normative references to ETSI EN 319 401 (the latest version of the referenced ETSI documents should be applied).
  
These audit reports MUST also meet the following requirements:

* They MUST report on the operational effectiveness of controls for a historic period of at least 60 days;
* No more than 27 months have elapsed since the beginning of the reported-on period and no more than 15 months since the end of reported-on period; and
* The audit report was prepared by a natural or legal person that is duly authorized or licensed to conduct audits according to the relevant audit criteria or attestation scheme used.

In addition, the Certificate Issuer MUST actively issue S/MIME certificates that are treated as valid by at least one Certificate Consumer that produces a mail user agent or email service provider that processes S/MIME certificates.

A **Certificate Consumer** eligible for voting membership in the SMCWG must produce and maintain a mail user agent (web-based or application based) or an email service provider that processes S/MIME certificates.

The SMCWG shall include Interested Parties, Associate Members, and Probationary Members, as defined in the Bylaws.

### 3.2 Ending Membership 

Members may resign from the SMCWG at any time. Resignation, suspension, or other termination of membership does not prevent a Member from potentially having continuing obligations, under the Forum's IPR Policy or any other document.

A Certificate Consumer Member’s membership may be suspended if any of the following become true:

1. it stops providing support for its membership-qualifying software product; or
2. its membership-qualifying software product ceases to consume S/MIME certificates.

A Certificate Issuer’s membership in the SMCWG may be suspended if any of the
following become true:

1. it fails to perform and disclose its membership-qualifying audit and fifteen (15) months have elapsed since the end of the audit period of its last successful membership-qualifying audit;
1. its membership-qualifying audit is revoked, rescinded or withdrawn; or
1. its S/MIME certificates are not treated as valid by any Certificate Consumer Member of the SMCWG.

Any Voting Member who believes any of the above circumstances is true of any other Voting Member, that Voting Member may report it on the SMCWG Public Mail List. The SMCWG Chair will then investigate, including asking the reported Voting Member for an explanation or appropriate documentation. If evidence of continued qualification for membership is not forthcoming from the reported Voting Member within five (5) working days, the SMCWG Chair will announce that such Voting Member is suspended and has become a Probationary Member, such announcement to include the clause(s) from the above list under which the suspension has been made.

A Probationary Member who believes it has now re-met the membership criteria under the relevant clauses shall post evidence to the SMCWG Public Mail List. The SMCWG Chair will examine the evidence, and if appropriate, reinstate the member to voting status, by public announcement.

A Probationary Member may participate in the SMCWG and Forum Meetings, Teleconferences, and on the SMCWG and the Forum's discussion lists as set forth in the Bylaws.

Votes cast before a Voting Member's suspension is announced will stand.

### 3.3 Application Process 

**An Applicant** not already a member of the Forum SHALL provide the following information:

* Confirmation that the applicant satisfies at least one (1) of the membership eligibility criteria (and if it satisfies more than one (1), indication of the single category under which the applicant wishes to apply).
* The organization name, as they wish it to appear on the Forum Web site and in official Forum documents.
* URL of the applicant’s main Web site.
* Names and email addresses of designated representatives who will participate in the Working Group and Forum on behalf of the Member.
* Emergency contact information for security issues related to certificate trust.

 Applicants that qualify as Certificate Issuers or Root Certificate Issuers MUST supply the following additional information:

* URL of the current qualifying audit report.
* Links or references to issued end-entity certificates that demonstrate them being treated as valid by a Certificate Consumer Member.

Such Applicant SHALL become a Member once the SMCWG has determined by consensus among the Members during a SMCWG Meeting or Teleconference that the Applicant meets all of the requirements above or, upon the request of any Member of the SMCWG, by a Ballot among Members of the SMCWG. Acceptance by consensus SHALL be determined or a Ballot of the Members SHALL be held as soon as the Applicant indicates that it has presented all information required above and has responded to all follow-up questions from the SMCWG and the Member has complied with the requirements of Bylaw 5.5.

Certificate Issuer applicants that are not actively issuing S/MIME certificates but otherwise meet these membership criteria MAY request to the SMCWG that they be granted an invitation for Associate Member status in accordance with Bylaw 3.1, subject to conditions designated by the SMCWG.

**Existing CAB Forum Members** seeking to participate in the SMCWG, in accordance to Bylaw 5.3.1(3), MUST formally declare their intent to participate in writing and provide the SMCWG Chair with this declaration and evidence that they meet the criteria set forth above. Such Applicants SHALL become Members of the SMCWG as determined by consensus during a SMCWG Meeting or Teleconference, or upon the request of any Member of the SMCWG, by a Ballot among Members of the SMCWG.

### 4.	Dependencies and Liaisons

The SMCWG will coordinate with, and seek guidance from, other CA/B Forum Working Groups, ETSI, the IETF and other related groups.

### 5.	Participation

To be successful, the SMCWG is expected to have an internationally diverse representation of Certificate Issuers and Certificate Consumers, as well as other industry participants, for its duration. The SMCWG participants are expected to contribute an appropriate number of hours per week towards the Working Group’s activities.

### 6.	Communication

Most SMCWG teleconferences will focus on discussion of particular specifications, and will be conducted on an as-needed basis. This group conducts its work primarily on the list at smcwg-public@groups.cabforum.org, which is available to the public. Information about the group will be available via the CA/B Forum website.


### 7.	Decision Process

The SMCWG will seek to make decisions when there is consensus and with due process. The expectation is that, typically, the SMCWG Chair or other participant makes an initial proposal, which is then refined in discussion with the SMCWG participants, and consensus emerges with little formal voting being required. However, if a decision is necessary for timely progress, but consensus is not achieved after careful consideration of the range of views presented, the SMCWG Chair should put the question out for voting within the WG (using email and/or web-based survey techniques) according to Section 2 (Forum Membership and Voting) of the Forum Bylaws and record a decision, along with any objections. The matter should then be considered resolved unless and until new information becomes available.

### 8.	IPR Policy

The SMCWG is subject to the CA/B Forum Intellectual Rights Policy v.1.3 or later (the “IPR Policy”). To promote the widest adoption of the CA/B Forum Guidelines, CA/B Forum seeks to issue Final Guidelines and Final Maintenance Guidelines that can be implemented, according to the IPR Policy, on a CA/B Forum Royalty-Free License basis. For information about exclusion of Essential Claims, see Section 4 of the IPR Policy.

### 9.	About this Charter

This Charter for the SMCWG has been created according to Section 5.3.1 of the Bylaws of the CA/B Forum. In the event of a conflict between this charter and any provision in either the Bylaws or the IPR Policy, the provision in the Bylaws or IPR Policy shall take precedence. The definitions found in the Forum’s Bylaws SHALL apply to capitalized terms in this Charter.

