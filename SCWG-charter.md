# Server Certificate Working Group Charter - Version 1.3

The Server Certificate Working Group ("SCWG") exists to perform the activities as specified in this Charter, subject to the terms and conditions of the CA/Browser Forum Bylaws and the Intellectual Property Rights (IPR) Policy, as such documents may change from time to time. The definitions found in the Forum’s Bylaws shall apply to capitalized terms in this Charter.

**SCOPE:** The authorized scope of the SCWG shall be as follows:

  1. To specify Baseline Requirements, Extended Validation Guidelines, and other acceptable practices for the issuance and management of SSL/TLS server certificates used for authenticating servers accessible through the Internet.
  
  2. To update such requirements and guidelines from time to time, in order to address both existing and emerging threats to online security, including responsibility for the maintenance of and future amendments to the current CA/Browser Forum Baseline Requirements and Extended Validation Guidelines.
  
  3. To perform such other activities that are ancillary to the primary activities listed above.

**OUT OF SCOPE:** The SCWG will not address certificates intended to be used primarily for code signing, S/MIME, time-stamping, VoIP, IM, or Web services. The SCWG will not address the issuance, or management of certificates by enterprises that operate their own Public Key Infrastructure for internal purposes only, and for which the Root Certificate is not distributed by any Application Software Supplier.

**Anticipated End Date:** None.

**Members eligible to participate:**

(a) The SCWG shall consist of two classes of voting members--Certificate Issuers and Certificate Consumers, and non-voting participants--Associate Members, Interested Parties, and other types of participants as allowed pursuant to this Charter. 

The Certificate Issuer voting class shall consist of eligible Certificate Issuers and Root Certificate Issuers meeting the following criteria:

   1) **Certificate Issuer:** The member organization operates a certification authority that has a publicly-available audit report or attestation statement that complies with one of the following schemes:
* “WebTrust for CAs v2.6 - SSL Baseline with Network Security, or newer”; or
* ETSI EN 319 411-1 or ETSI EN 319 411-2 (with DVCP, OVCP, IVCP, QCP-w, QCP-w, QNCP-w, or QEVCP-w), which includes normative references to ETSI EN 319 401 (the latest version of the referenced ETSI documents should be applied); or
* If a Government Certificate Issuer is required by its Certificate Policy to use a different internal audit scheme, it MAY use such scheme provided that the audit either (a) encompasses all requirements of one of the above schemes or (b) consists of comparable criteria that are available for public review.

These audit reports must also meet the following requirements:
* They must report on the operational effectiveness of controls for a historic period of at least sixty (60) days;
* No more than twenty-seven (27) months have elapsed since the beginning of the reported-on period and no more than fifteen (15) months since the end of the reported-on period;
* The audit report was prepared by a properly-Qualified Auditor.

In addition, the member organization actively issues certificates to Web servers that are openly accessible from the Internet, such certificates being treated as valid when using a browser created by a Certificate Consumer Member. Applicants that do not meet this requirement, but otherwise meet membership criteria may be granted Probationary Member status under Bylaw Sections 2.1 and 3.3 for a period of time to be designated by the SCWG. Furthermore, all Certificate Issuers must attend at least 30% of SCWG teleconferences in any six-month period and at least one SCWG face-to-face meeting (either physically or virtually) in any twelve-month period.

   2) **Root Certificate Issuer:** The member organization operates a certification authority that has a publicly-available audit report or attestation statement that complies with one of the following schemes:
* “WebTrust for CAs v2.0 or newer”; or
* ETSI EN 319 411-1 or ETSI EN 319 411-2, which includes normative references to ETSI EN 319 401 (the latest version of the referenced ETSI documents should be applied); or
* If the CA is required to use a different audit scheme by any jurisdiction in which the CA operates or issues certificates, it MAY use such scheme provided that the audit scheme criteria are available for public and review and either (a) encompasses all requirements of one of the above schemes or (b) consists of comparable criteria.

These audit reports must also meet the following requirements:
* They must report on the operational effectiveness of controls for a historic period of at least sixty (60) days;
* No more than twenty-seven (27) months have elapsed since the beginning of the reported-on period and no more than fifteen (15) months since the end of the reported-on period;
* The audit report was prepared by a properly-Qualified Auditor.

In addition, the member organization must actively issue certificates to subordinate CAs that, in turn, actively issue certificates to web servers that are openly accessible from the Internet, such certificates being treated as valid when using a browser created by a Certificate Consumer Member. Applicants that do not meet this requirement, but otherwise meet membership criteria may be granted Probationary Member status under Bylaw Sections 2.1 and 3.3 for a period of time to be designated by the SCWG. Furthermore, all Root Certificate Issuers must attend at least 30% of SCWG teleconferences in any six-month period and at least one SCWG face-to-face meeting (either physically or virtually) in any twelve-month period.

   3) **A Certificate Consumer** can vote on ballots of the SCWG if it produces a software product intended for use by the general public for browsing the Web securely and:
* provides updates for its membership-qualifying software product at least every 6 months;
* has a publicly disclosed process for receiving software product problem reports concerning its membership-qualifying software product;
* has public documentation stating that it requires Certificate Issuers to comply with the Baseline Requirements; and
* publishes criteria that it follows in adding or removing CA certificates from the list of CA certificates that its membership-qualifying software product uses to validate the chain of trust from a TLS certificate to the trusted CA certificate in such list (and those criteria do not prevent Certificate Issuers from complying with the Baseline Requirements).

Furthermore, all Certificate Consumers must attend at least 30% of SCWG teleconferences in any six-month period and at least one SCWG face-to-face meeting (either physically or virtually) in any twelve-month period.

(b) Applicants must supply the following information:

   * Confirmation that the applicant satisfies at least one (1) of the membership criteria (and if it satisfies more than one (1), indication of the single category under which the applicant wishes to apply).

   * The organization name, as they wish it to appear on the Forum Web site and in official Forum documents.

   * URL of the applicant's main Web site.

   * Names and email addresses of employees who will participate in the SCWG and Forum as Member representatives.

   * Emergency contact information for security issues related to certificate trust.

Applicants that qualify as Certificate Issuers or Root Certificate Issuers must supply the following additional information:

   * URL of the current qualifying audit report.

   * The URLs of three web pages that comply with section 2.2 of the Baseline Requirements (respectively secured with a valid, a revoked, and an expired certificate).

   * Links or references to issued end-entity certificates that demonstrate them being treated as valid by a Certificate Consumer Member.

Applicants that qualify as Certificate Consumers must supply the following additional information:

   * URL demonstrating that it provides updates for its membership-qualifying software product at least every 6 months;

   * URL for receipt of reports about problems with its membership-qualifying software product;

   * URL to its statement requiring Certificate Issuer compliance with the Baseline Requirements for TLS server certificates;

   * URL for its list of CA certificates that its membership-qualifying software product uses to validate the chain of trust from a TLS certificate to a CA certificate in such list; and

   * URL for its criteria for adding and removing certificates from such list.

(c) After a six-month probationary period of attending at least 30% of all SCWG teleconferences, an Applicant may become a Voting Member if the SCWG determines by consensus among the Members during a Meeting or Teleconference that the Applicant meets all of the requirements of subsection (a) or, upon the request of any Member, by a Ballot among the Members. Acceptance by consensus shall be determined or a Ballot of the Members shall be held as soon as the Applicant indicates that it has presented all information required and has responded to all follow-up questions from the SCWG and the Member has complied with the requirements of Section 5.5 of the CA/Browser Forum Bylaws.

The SCWG shall include Associate Members, Interested Parties, and other types of participants as allowed pursuant to this Charter. 

**Ending SCWG Membership:** Members may resign from the SCWG at any time. Resignation or other form of membership termination does not prevent a Member from potentially having continuing obligations, under the Forum's IPR Policy or any other document.

   1) **Certificate Consumer:** A Certificate Consumer Member is suspended, and its right to vote automatically ceases, if any of the following become true:

   * it fails to attend at least 30% of SCWG meetings in any six-month period;

   * it fails to attend at least one SCWG face-to-face meeting (either physically or virtually) in any twelve-month period;

   * it ceases providing a process for receiving software product problem reports concerning its membership-qualifying software product;

   * it ceases to maintain a list of CA certificates that its membership-qualifying software product uses to validate the chain of trust from the TLS certificate to a root certificate in its root store;

   * it ceases to maintain criteria for adding and removing root certificates from its root store;

   * it ceases to require that Certificate Issuers comply with the Baseline Requirements for TLS server certificates;

   * it stops providing updates for its membership-qualifying software product; or 

   * six (6) months have elapsed since it last updated its membership-qualifying software product.

   2) **Certificate Issuer or Root Certificate Issuer:** A Certificate or Root Certificate Issuer Member is suspended, and its right to vote automatically ceases, if any of the following become true:
   
   * it fails to attend at least 30% of SCWG meetings in any six-month period;

   * it fails to attend at least one SCWG face-to-face meeting (either physically or virtually) in any twelve-month period;

   * it fails to perform and disclose its membership-qualifying audit and fifteen (15) months have elapsed since the end of the audit period of its last successful membership-qualifying audit;
   
   * its membership-qualifying audit is revoked, rescinded or withdrawn;
   
   * fifteen (15) months have elapsed since the end of the audit period of its last membership-qualifying audit; or
   
   * its currently-issued certificates are no longer treated as valid by at least one (1) Certificate Consumer Member of the SCWG.

Any Member who believes any of the above circumstances is true of any other Member may report that Member on the SCWG Public Mail List. The SCWG Chair will then investigate, including asking the reported Member for an explanation or appropriate documentation. If evidence of continued qualification for voting membership is not forthcoming from the reported Member within five (5) working days, the Chair will announce that such Member is suspended, such announcement to include the clause(s) from the above list under which the suspension has been made.

A suspended Member who believes that it then meets the membership criteria under the relevant clauses shall post evidence to the SCWG Public Mail List. The SCWG Chair will examine the evidence and unsuspend the member, or not, by public announcement. A Member's membership will automatically cease six (6) months after it becomes suspended if the Member has not re-met the membership criteria by that time or it has not been allowed by the SCWG to participate in a non-voting capacity.

While suspended, a Member may participate in SCWG and Forum Meetings, Teleconferences, and on the SCWG and Forum's discussion lists, but may not propose or endorse ballots or take part in any form of voting.
Votes cast before a Member's suspension is announced will stand.

**Voting structure:** In order for a ballot to be adopted by the SCWG, two-thirds or more of the votes cast by the Certificate Issuers must be in favor of the ballot and more than 50% of the votes cast by the Certificate Consumers must be in favor of the ballot. At least one member of each voting class must vote in favor of a ballot for it to be adopted. Quorum is the average number of voting members (cumulative of both Certificate Issuer and Certificate Consumer classes) that have participated in the previous three SCWG Meetings or Teleconferences (not counting subcommittee meetings thereof). For transition purposes, if three meetings have not yet occurred, quorum is ten (10).

**Summary of the work that the WG plans to accomplish:** As specified in Scope section above.

**Summary of major WG deliverables and guidelines:** As specified in Scope section above.

**Primary means of communication:** listserv-based email, periodic teleconference calls, and face-to-face meetings.

**IPR Policy:** The CA/Browser Forum Intellectual Rights Policy, v. 1.3 or later, SHALL apply to all SCWG activity.
