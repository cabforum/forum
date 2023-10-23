# Server Certificate Working Group Charter - Version 1.3

The Server Certificate Working Group ("SCWG") exists to perform the activities as specified in this Charter, subject to the terms and conditions of the CA/Browser Forum Bylaws and the Intellectual Property Rights ("IPR") Policy, as such documents may change from time to time. The definitions found in the Forum’s Bylaws shall apply to capitalized terms in this Charter.

**1. Scope:** The authorized scope of the SCWG shall be as follows:

  (a) To specify Baseline Requirements, Extended Validation Guidelines, and other acceptable practices for the issuance and management of TLS server certificates used for authenticating servers accessible through the Internet;
  
  (b) To update such requirements and guidelines from time to time, in order to address both existing and emerging threats to online security, including responsibility for the maintenance of and future amendments to the current Baseline Requirements for the Issuance and Management of Publicly-Trusted TLS Server Certificates ("TLS BRs") and the Guidelines for the Issuance and Management of Extended Validation Certificates ("EVGs"); and
  
  (c) To perform such other activities that are ancillary to the primary activities listed above.

**Out of Scope:** The SCWG will not address certificates intended to be used primarily for code signing, S/MIME, time-stamping, VoIP, IM, or Web services. The SCWG will not address the issuance, or management of certificates by enterprises that operate their own Public Key Infrastructure for internal purposes only, and for which the Root Certificate is not distributed by any Certificate Consumer.

**2. Anticipated End Date:** None.

**3. Membership:**

The SCWG shall consist of two classes of Voting Members: Certificate Issuers and Certificate Consumers. Non-voting participants in the SCWG include Probationary Members, Associate Members, and Interested Parties. 

   **(a) Certificate Issuer:** The Certificate Issuer voting class shall consist of eligible organizations meeting the following criteria:
   
(1) it operates a certification authority that has a publicly-available audit report or attestation statement that complies with one of the following schemes:
  * “WebTrust for CAs v2.7 - SSL Baseline with Network Security, or newer”; or
  * ETSI EN 319 411-1 (v1.3.1 or newer) or ETSI EN 319 411-2 (v2.4.1 or newer) (with DVCP, OVCP, IVCP, QCP-w, QCP-w, QNCP-w, or QEVCP-w); or
  * If a Government Certificate Issuer is required by its Certificate Policy to use a different internal audit scheme, it MAY use such scheme provided that the audit either (a) encompasses all requirements of one of the above schemes or (b) consists of comparable criteria that are available for public review.

These audit reports must also meet the following requirements:
  * They must report on the operational effectiveness of controls for a historic period of at least sixty (60) days;
  * No more than twenty-seven (27) months have elapsed since the beginning of the reported-on period and no more than fifteen (15) months since the end of the reported-on period; and
  * The audit report was prepared by a Qualified Auditor, as defined in the TLS BRs.

**_and_**

(2) it actively issues certificates to Web servers that are openly accessible from the Internet, such certificates being treated as valid when using a browser created by a Certificate Consumer Member. 

   **(b) Certificate Consumer:** The Certificate Consumer voting class shall consist of eligible organizations meeting the following criteria:  
   
(1) it produces a software product intended for use by the general public for browsing the Web securely;

(2) it provides updates for its membership-qualifying software product at least every 6 months to ensure that customers of the Certificate Consumer are getting regular security patches;

(3) it has public documentation stating that it requires Certificate Issuers to comply with the TLS BRs;

(4) its membership-qualifying software product uses a list of CA certificates to validate the chain of trust from a TLS certificate to a CA certificate in such list;

(5) it publishes the list of CA certificates used to validate the chain of trust from a TLS certificate to a CA certificate in such list;  **_and_**

(6) it publishes how it adds or removes a CA certificate from such list.

   **(c) Probationary Member:** An organization that does not meet the requirements in (a) or (b) may be granted Probationary Member status, as set forth in Sections 2.1 and 3.3 of the Bylaws, for a period of time to be designated by the SCWG. In addition to the requirement in (a) or (b) above, section 4(d) establishes a six-month period during which any representative of a Probationary Member MUST attend at least 30% of SCWG teleconferences (not counting subcommittee meetings) and at least one SCWG face-to-face meeting (either physically or virtually). 
   
   A Probationary Member may participate in SCWG Meetings, Teleconferences, and on the SCWG's discussion lists, but may not propose or endorse ballots or take part in voting, except on special straw polls of the SCWG (e.g. when selecting meeting dates, locations, etc.).
   
   **(d)** The SCWG includes Associate Members and Interested Parties, whose qualifications and privileges are set forth in sections 3.1 and 3.2 of the Bylaws, respectively. 

**4. Applications for Membership**

**(a)** Applicants for membership must supply the following information:

   * The Forum's IPR Policy Agreement duly signed by a person with authority to bind the organization;

   * Confirmation that the Applicant meets the requirements in either 3(a) or 3(b), and if it satisfies both, then an indication of the single category under which the Applicant wishes to apply;

   * The organization name, as they wish it to appear on the Forum website and in official Forum documents;

   * URL of the Applicant's main website;

   * Names and email addresses of employees who will participate in the SCWG and Forum as representatives; **_and_**

   * Emergency contact information for security issues related to certificate trust.

**(b)** Applicants that qualify as Certificate Issuers must supply the following additional information:

   * URL of the current qualifying audit report;

   * The URLs of three web pages that comply with section 2.2 of the TLS Baseline Requirements (respectively secured with a valid, a revoked, and an expired certificate); **_and_**

   * Links or references to an issued end-entity certificate that demonstrates it being treated as valid by a Certificate Consumer Member.

**(c)** Applicants that qualify as Certificate Consumers must supply the following additional information:

   * URL from which to download its software product intended for use by the general public for browsing the Web securely;
     
   * URL or other evidence demonstrating that it provides updates for its membership-qualifying software product at least every 6 months;

   * URL to its statement requiring Certificate Issuer compliance with the TLS Baseline Requirements;

   * URL for its list of CA certificates that its membership-qualifying software product uses to validate the chain of trust from a TLS certificate to a CA certificate in such list; **_and_**

   * URL to documentation explaining its process for adding or removing a CA certificate from such list.

**(d)**  There is a mandatory six-month probationary period during which any representative of an Applicant must attend at least 30% of all SCWG teleconferences (not counting subcommittee meetings) and at least one SCWG face-to-face meeting (either physically or virtually). After successful completion of the mandatory probationary period and meeting all requirements of section 3(a) or 3(b), an Applicant may become a Voting Member, if the SCWG determines by consensus among the Members during a Meeting or Teleconference, or upon the request of any Member that challenges the Applicant's adherence to all of the requirements of section 3(a) or 3(b), by a Ballot among the Members. Acceptance by consensus shall be determined, or a Ballot of the Members shall be held, as soon as the Applicant indicates that it has presented all information required and has responded to all follow-up questions from the SCWG and the Applicant has complied with the requirements of Section 5.5 of the CA/Browser Forum Bylaws.

**5. Ending SCWG Membership:** Members may resign from the SCWG at any time. Resignation or other form of membership termination does not prevent a Member from potentially having continuing obligations, under the Forum's IPR Policy or any other document.

   **(a) Certificate Consumer:** A Certificate Consumer Member is suspended, and its right to vote automatically ceases, if any of the following become true:

   * six (6) months have elapsed since it last updated its membership-qualifying software product;

   * it ceases to require that Certificate Issuers comply with the TLS Baseline Requirements;
   
   * its membership-qualifying software product ceases to use a list of CA certificates to validate the chain of trust from a TLS certificate to a CA certificate in such list;

   * it ceases to publish such list of CA certificates used to validate the chain of trust; **_or_**
  
   * it ceases to publish how it adds or removes a CA certificate from such list.

   **(b) Certificate Issuer:** A Certificate Issuer Member is suspended, and its right to vote automatically ceases, if any of the following become true:

   * it fails to perform and disclose its membership-qualifying audit and fifteen (15) months have elapsed since the end of the audit period of its last successful membership-qualifying audit;
   
   * its membership-qualifying audit is revoked, rescinded or withdrawn;
   
   * fifteen (15) months have elapsed since the end of the audit period of its last membership-qualifying audit; **_or_**
   
   * its currently-issued certificates are no longer treated as valid by at least one (1) Certificate Consumer Member of the SCWG.

**(c) Suspension Procedure:** Any Member who believes any of the above circumstances is true of any other Member may report that Member on the SCWG Public Mail List. The SCWG Chair will then investigate, including asking the reported Member for an explanation or appropriate documentation. If evidence of continued qualification for voting membership is not forthcoming from the reported Member within five (5) working days, the Chair will announce that such Member is suspended and has become a Probationary Member, such announcement to include the clause(s) from one of the above lists under which the suspension has been made.

A Probationary Member who believes that it then meets the membership criteria under the relevant clauses shall post evidence to the SCWG Public Mail List. The SCWG Chair will examine the evidence, and if appropriate, reinstate the member, by public announcement.

Votes cast before the Voting Member's suspension is announced will stand.

**6. Voting structure:** In order for a ballot to be adopted by the SCWG, two-thirds or more of the votes cast by the Certificate Issuers must be in favor of the ballot and more than 50% of the votes cast by the Certificate Consumers must be in favor of the ballot. At least one member of each voting class must vote in favor of a ballot for it to be adopted. Quorum is half the average number of voting members (cumulative of both Certificate Issuer and Certificate Consumer classes) that have participated in the previous three SCWG Meetings or Teleconferences (not counting subcommittee meetings thereof).

**7. Summary of the work that the SCWG plans to accomplish:** As specified in Scope section above.

**8. Summary of major SCWG deliverables and guidelines:** As specified in Scope section above.

**9. Primary means of communication:** listserv-based email, periodic teleconference calls, and face-to-face meetings.

**10. IPR Policy:** The CA/Browser Forum Intellectual Rights Policy, v. 1.3 or later, SHALL apply to all SCWG activity.
