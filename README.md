# Document Signing similar to Zoho Sign

## Open Source Solutions

1.  [DocuSeal](https://www.docuseal.co/)
    Best overall implementation with respect to self hosting, customisations,
    compliance.
2.  [Open Sign](https://www.opensignlabs.com/)
3.  [Documenso](https://documenso.com/)

## Compliance

### USA

The Uniform Electronic Transactions Act (UETA) and the Electronic
Signature in Global and National Commerce Act (ESIGN Act) are pivotal U.S.
laws that establish the legal validity of electronic signatures and
records. Both statutes ensure that electronic documents and signatures are
as legally binding as their traditional counterparts.

- Legal Validity: Electronic signatures and records are considered legally
  valid and have the same legal status as handwritten signatures and paper
  documents, ensuring that contracts and agreements formed electronically
  are enforceable.
- Electronic Records: Electronic records are deemed to be in writing and
  are legally recognized, satisfying the requirement for a written
  document.
- Consumer Consent: Parties involved in electronic transactions must
  consent to conduct the transaction electronically. However, consent
  cannot be denied solely on the grounds that it is in electronic form.
- Record Retention: UETA establishes guidelines for the retention of
  electronic records to ensure that they remain accessible and accurate
  for future reference.

Requirements for compliance:

- Authentication
- Record Retention
- Audit Trail

### EU

#### eIDAS

The Electronic Identification, Authentication and Trust Services (eIDAS)
regulation is an EU initiative that standardizes electronic
identification and trust services for electronic transactions. It ensures
that electronic interactions between businesses, citizens, and public
authorities are secure, seamless, and have legal standing.

- Electronic Signatures: eIDAS defines three types of electronic signatures:
  simple, advanced, and qualified electronic signatures. These signatures have
  varying levels of security and legal validity, allowing users to choose the
  appropriate type based on the context and requirements of the transaction.
- Record Retention: Businesses must provide consumers with the option to receive
  electronic records in a format that is accessible and can be retained for
  future reference. Additionally, businesses are required to maintain accurate
  records of electronic transactions.

         Requirements for compliance:
         - Signer Intent
         - Data Integrity

#### GDPR

The General Data Protection Regulation (GDPR) is a regulation introduced by
the European Union to protect the privacy and personal data of its
citizens. It sets forth guidelines for the collection, processing, and
storage of personal data and emphasizes transparency, security, and
accountability by businesses.

Requirements for compliance:

- Servers in the EU
- No data sharing with 3rd party
- No data tracking

### India

#### Section 3A of the Information Technology Act 2000

3A. Electronic signature.
(1) Notwithstanding anything contained in section 3, but subject to the
provisions of sub-section (2), a subscriber may authenticate any
electronic record by such electronic signature or electronic
authentication technique which--
(a) is considered reliable; and
(b) may be specified in the Second Schedule.
(2) For the purposes of this section any electronic signature or
electronic authentication technique shall be considered reliable if--
(a) the signature creation data or the authentication data are, within
the context in which they are used, linked to the signatory or, as the
case may be, the authenticator and to no other person;
(b) the signature creation data or the authentication data were, at the
time of signing, under the control of the signatory or, as the case may
be, the authenticator and of no other person;
(c) any alteration to the electronic signature made after affixing such
signature is detectable;
(d) any alteration to the information made after its authentication by
electronic signature is detectable; and
(e) it fulfils such other conditions which may be prescribed.
(3) The Central Government may prescribe the procedure for the purpose of
ascertaining whether electronic signature is that of the person by whom
it is purported to have been affixed or authenticated.
(4) The Central Government may, by notification in the Official Gazette,
add to or omit any electronic signature or electronic authentication
technique and the procedure for affixing such signature from the Second
Schedule:
Provided that no electronic signature or authentication technique shall
be specified in the Second Schedule unless such signature or technique is
reliable.
(5) Every notification issued under sub-section (4) shall be laid before
each House of Parliament.

## System Design

### ERD

![Zoho Sign ERD](./ERD.svg)
