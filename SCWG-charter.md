# Server Certificate Working Group Charter - Version 1.3

The Server Certificate Working Group ("SCWG") exists to perform the activities as specified in this Charter, subject to the terms and conditions of the CA/Browser Forum Bylaws and the Intellectual Property Rights (IPR) Policy, as such documents may change from time to time. The definitions found in the Forum’s Bylaws shall apply to capitalized terms in this Charter.

**1. Scope:** The authorized scope of the SCWG shall be as follows:

  (a) To specify Baseline Requirements, Extended Validation Guidelines, and other acceptable practices for the issuance and management of SSL/TLS server certificates used for authenticating servers accessible through the Internet.
  
  (b) To update such requirements and guidelines from time to time, in order to address both existing and emerging threats to online security, including responsibility for the maintenance of and future amendments to the current CA/Browser Forum TLS Baseline Requirements and Extended Validation Guidelines.
  
  (c) To perform such other activities that are ancillary to the primary activities listed above.

**Out of Scope:** The SCWG will not address certificates intended to be used primarily for code signing, S/MIME, time-stamping, VoIP, IM, or Web services. The SCWG will not address the issuance, or management of certificates by enterprises that operate their own Public Key Infrastructure for internal purposes only, and for which the Root Certificate is not distributed by any Application Software Supplier.

**2. Anticipated End Date:** None.

**3. Membership:**

The SCWG shall consist of two classes of Voting Members: Certificate Issuers and Certificate Consumers. Non-voting participants in the SCWG include Probationary Members, Associate Members, and Interested Parties. Effective for periods beginning January 1, 2024, in order to maintain their right to vote, all Voting Members must attend at least 30% of SCWG teleconferences in any six-month period and at least one SCWG face-to-face meeting (either physically or virtually) in any twelve-month period. 

   **(a) Certificate Issuer:** The Certificate Issuer voting class shall consist of eligible organizations meeting the following criteria:
   
(1) it operates a certification authority that has a publicly-available audit report or attestation statement that complies with one of the following schemes:
  * “WebTrust for CAs v2.7 - SSL Baseline with Network Security, or newer”; or
  * ETSI EN 319 411-1 (v1.3.1 or newer) or ETSI EN 319 411-2 (v2.4.1 or newer) (with DVCP, OVCP, IVCP, QCP-w, QCP-w, QNCP-w, or QEVCP-w); or
  * If a Government Certificate Issuer is required by its Certificate Policy to use a different internal audit scheme, it MAY use such scheme provided that the audit either (a) encompasses all requirements of one of the above schemes or (b) consists of comparable criteria that are available for public review.

These audit reports must also meet the following requirements:
  * They must report on the operational effectiveness of controls for a historic period of at least sixty (60) days;
  * No more than twenty-seven (27) months have elapsed since the beginning of the reported-on period and no more than fifteen (15) months since the end of the reported-on period; and
  * The audit report was prepared by a properly-Qualified Auditor.

**_and_**

(2) it actively issues certificates to Web servers that are openly accessible from the Internet, such certificates being treated as valid when using a browser created by a Certificate Consumer Member. 

   **(b) Certificate Consumer:** The Certificate Consumer voting class shall consist of eligible organizations meeting the following criteria:  
   
(1) it produces a software product intended for use by the general public for browsing the Web securely;

(2) it provides updates for its membership-qualifying software product at least every 6 months to ensure that customers of this Certificate Consumer are getting regular security patches;

(3) it has public documentation stating that it requires Certificate Issuers to comply with the TLS Baseline Requirements;

(4) its membership-qualifying software product uses a list of CA certificates to validate the chain of trust from a TLS certificate to a CA certificate in such list; **_and_**

(5) it publishes how it decides to add or remove a CA certificate from the root store used in its membership-qualifying software product.

   **(c) Probationary Member:** An organization that does not meet the requirements in (a) or (b) may be granted Probationary Member status, as set forth in Sections 2.1 and 3.3 of the Bylaws, for a period of time to be designated by the SCWG. In addition to the requirement in (a) or (b) above, section 4(d) establishes a six-month period during which a representative of the Probationary Member MUST must attend at least 30% of SCWG teleconferences and at least one SCWG face-to-face meeting (either physically or virtually). 
   
   **(d)** The SCWG includes Associate Members and Interested Parties, as set forth in sections 3.1 and 3.2 of the Bylaws. 

**4. Applications for Membership**

**(a)** Applicants for membership must supply the following information:

   * Confirmation that the applicant meets the requirements in either 3(a) or 3(b), and if it satisfies both, then an indication of the single category under which the applicant wishes to apply;

   * The organization name, as they wish it to appear on the Forum Web site and in official Forum documents.

   * URL of the applicant's main Web site.

   * Names and email addresses of employees who will participate in the SCWG and Forum as Member representatives.

   * Emergency contact information for security issues related to certificate trust.

**(b)** Applicants that qualify as Certificate Issuers must supply the following additional information:

   * URL of the current qualifying audit report.

   * The URLs of three web pages that comply with section 2.2 of the TLS Baseline Requirements (respectively secured with a valid, a revoked, and an expired certificate).

   * Links or references to an issued end-entity certificate that demonstrates it being treated as valid by a Certificate Consumer Member.

**(c)** Applicants that qualify as Certificate Consumers must supply the following additional information:

   * URL or other evidence demonstrating that it provides updates for its membership-qualifying software product at least every 6 months;

   * URL to its statement requiring Certificate Issuer compliance with the TLS Baseline Requirements;

   * URL for its list of CA certificates that its membership-qualifying software product uses to validate the chain of trust from a TLS certificate to a CA certificate in such list; and

   * URL for its criteria for adding and removing certificates from such list.

**(d)**  There is a mandatory six-month probationary period during which an Applicant must attend at least 30% of all SCWG teleconferences and at least one SCWG face-to-face meeting (either physically or virtually). After successful completion of the mandatory probationary period, an Applicant may become a Voting Member, if the SCWG determines by consensus among the Members during a Meeting or Teleconference, or upon the request of any Member, by a Ballot among the Members, that the Applicant meets the requirements of section 3(a) or 3(b). Acceptance by consensus shall be determined, or a Ballot of the Members shall be held, as soon as the Applicant indicates that it has presented all information required and has responded to all follow-up questions from the SCWG and the Member has complied with the requirements of Section 5.5 of the CA/Browser Forum Bylaws.

**4. Ending SCWG Membership:** Members may resign from the SCWG at any time. Resignation or other form of membership termination does not prevent a Member from potentially having continuing obligations, under the Forum's IPR Policy or any other document.

   **(a) Certificate Consumer:** A Certificate Consumer Member is suspended, and its right to vote automatically ceases, if any of the following become true:

   * it ceases to maintain a list of CA certificates that its membership-qualifying software product uses to validate the chain of trust from the TLS certificate to a root certificate in its root store;

   * it ceases to maintain criteria for adding and removing root certificates from its root store;

   * it ceases to require that Certificate Issuers comply with the TLS Baseline Requirements;

   * six (6) months have elapsed since it last updated its membership-qualifying software product.

   **(b) Certificate Issuer:** A Certificate Issuer Member is suspended, and its right to vote automatically ceases, if any of the following become true:

   * it fails to perform and disclose its membership-qualifying audit and fifteen (15) months have elapsed since the end of the audit period of its last successful membership-qualifying audit;
   
   * its membership-qualifying audit is revoked, rescinded or withdrawn;
   
   * fifteen (15) months have elapsed since the end of the audit period of its last membership-qualifying audit; or
   
   * its currently-issued certificates are no longer treated as valid by at least one (1) Certificate Consumer Member of the SCWG.

**(c) Suspension Procedure:** Any Member who believes any of the above circumstances is true of any other Member may report that Member on the SCWG Public Mail List. The SCWG Chair will then investigate, including asking the reported Member for an explanation or appropriate documentation. If evidence of continued qualification for voting membership is not forthcoming from the reported Member within five (5) working days, the Chair will announce that such Member is suspended and has become a Probationary Member, such announcement to include the clause(s) from the above list under which the suspension has been made.

A Probationary Member who believes that it then meets the membership criteria under the relevant clauses shall post evidence to the SCWG Public Mail List. The SCWG Chair will examine the evidence, and if appropriate, reinstate the member, by public announcement.

A Probationary Member may participate in SCWG and Forum Meetings, Teleconferences, and on the SCWG and Forum's discussion lists, but may not propose or endorse ballots or take part in any form of voting.

Votes cast before the Voting Member's suspension is announced will stand.

**5. Voting structure:** In order for a ballot to be adopted by the SCWG, two-thirds or more of the votes cast by the Certificate Issuers must be in favor of the ballot and more than 50% of the votes cast by the Certificate Consumers must be in favor of the ballot. At least one member of each voting class must vote in favor of a ballot for it to be adopted. Quorum is the average number of voting members (cumulative of both Certificate Issuer and Certificate Consumer classes) that have participated in the previous three SCWG Meetings or Teleconferences (not counting subcommittee meetings thereof). For transition purposes, if three meetings have not yet occurred, quorum is ten (10).

**6. Summary of the work that the WG plans to accomplish:** As specified in Scope section above.

**7. Summary of major WG deliverables and guidelines:** As specified in Scope section above.

**8. Primary means of communication:** listserv-based email, periodic teleconference calls, and face-to-face meetings.

**9. IPR Policy:** The CA/Browser Forum Intellectual Rights Policy, v. 1.3 or later, SHALL apply to all SCWG activity.
