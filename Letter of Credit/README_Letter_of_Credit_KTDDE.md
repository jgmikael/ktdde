# Letter of Credit (LoC) — KTDDE Application Profile (v0.0.4)

This repository contains the **KTDDE Application Profile for the Letter of Credit (LoC)** — a semantic data model based on the **Key Trade Documents and Data Elements (KTDDE) Ontology v0.0.4**.  
It provides a *machine-readable yet human-understandable* structure for representing international trade Letters of Credit as **Verifiable Credentials** within the **EU Business Wallet** and other digital trust infrastructures.

---

## 📘 Contents

| File | Description |
|------|--------------|
| [Letter_of_Credit_KTDDE_v004.md](Letter_of_Credit_KTDDE_v004.md) | Full documentation of the Letter of Credit SHACL Application Profile, including human-readable explanations, examples, and ontology mappings. |
| `Letter_of_Credit_KTDDE_v004.jsonld` | Example JSON-LD instance demonstrating a realistic LoC scenario (FinnLam Oy → Tokyo Builders Ltd.). |
| `KTDDE_Core_Vocabulary_v004.ttl` | Underlying ontology defining the reusable trade and data elements. |

---

## 🧭 Overview

The **Letter of Credit (LoC)** is one of the 36 trade documents defined in the *Key Trade Documents & Data Elements (KTDDE)* ecosystem.  
It formalizes the financial guarantee provided by an issuing bank to a beneficiary (exporter) on behalf of an applicant (importer).  

In this application profile, each part of the LoC (document data, financial terms, parties, shipment, and conditions) is modeled semantically using the **KTDDE Ontology** and validated with **SHACL Shapes** — ensuring interoperability across banking, logistics, and customs systems.

---

## 🌐 Example Use Case

> **FinnLam Oy (Finland)** exports glued laminated timber to **Tokyo Builders Ltd. (Japan)**.  
> Payment is secured via an irrevocable, confirmed Letter of Credit issued by **Nordea Bank Finland Plc** and advised/confirmed by **Mitsui Bank Ltd.**, Tokyo.  
> Shipment from *Port of Helsinki (FIHEL)* to *Port of Tokyo (JPTYO)* under **CIF Tokyo (Incoterms® 2020)** terms.

This digital LoC is expressed as a **Verifiable Credential**, enabling automatic validation, document chaining (invoice, transport, certificate of origin), and audit-proof transaction evidence in a **Business Information Data Space**.

---

## 🧩 Interoperability Highlights

- **Ontology-based modeling:** built on KTDDE OWL v0.0.4 and aligned with UN/CEFACT and ISO 20022 semantics.  
- **Validation-ready:** LoC SHACL Shape ensures all mandatory data points are complete and consistent.  
- **Cross-domain integration:** supports alignment with eFTI, ESPR, and EU Business Wallet ecosystems.  
- **Verifiable credentials:** natively supports W3C VC / JSON-LD for issuance and exchange.  

---

## 🧑‍💻 Maintainers & Contributors

Developed under the **WE BUILD LSP / KTDDE Semantic Group** as part of the **EU Business Wallet initiative**.  
Contributions, comments, and alignment proposals are welcome.

---

**© 2025 KTDDE Semantic Group — WE BUILD LSP / EU Business Wallet Initiative**
