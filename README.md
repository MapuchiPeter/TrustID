# TrustID: Blockchain-Powered Digital Identity and Verification

TrustID is a blockchain-powered digital identity verification system that ensures secure, tamper-proof, and verifiable credentials. TrustID allows users to manage and share their credentials (e.g., National ID, Passports, Degrees) with organizations in a privacy-preserving, decentralized way.

<p align="center">
  <img src="https://github.com/Nexa-Bites/trustid_front_and_backend/blob/main/WhatsApp%20Image%202025-03-20%20at%2013.23.22_3df22ccf.png?raw=true" alt="TrustID Logo" width="250">
</p>

---

## 📌 Our Mission
To provide a trustworthy, efficient, and privacy-centric digital identity system for seamless verification across industries like **finance, healthcare, education and more**.

---
## 🏠 TrustID | Signup Now
[🌐 Visit TrustID App](https://trust-id-snowy.vercel.app/)


## 🔹 Key Features
- ✅ **Decentralized Identifiers (DIDs)** for secure user authentication.
- ✅ **Verifiable Credentials** stored on blockchain for authenticity.
- ✅ **Automated Data Extraction** using OCR/AI for easy document verification.
- ✅ **Revocation Registry** to track and prevent fraudulent credentials.
- ✅ **Seamless Integration** for organizations to verify credentials in real-time.

---

## 📊 Project Presentation And Documentaion Summary

[➡️ Presenation: Click here to view the Google Slides](https://docs.google.com/presentation/d/1P1hOViR7TNffz5H2b4t8dL0hz_HxIsuIRW3yM1SCKPs/edit#slide=id.g3446bf115aa_0_15)

[📑 Project Summary: View Google Doc](https://docs.google.com/document/d/1fH9gBXEnQuEC7aTgMOzYQs4nQfhRIcNT883S0Sb38Ns/edit?usp=sharing)



## Data Workflow Summary

1. **User Submission & Verification (Backend Responsibility)**  
   Users **either upload documents or manually enter credentials** (license, certificate, national ID, etc.).  
   Backend **extracts data** from uploaded documents.  
   Backend **verifies credentials** with external sources before sending them to storage.

2. **Data Ingestion**  
   Once credentials are verified, the **backend sends validated data** to the data pipeline.  
   The **data_ingestion** module receives and prepares the data for processing.

3. **Data Processing & Security**  
   Verified data is **cleaned, transformed, and encrypted** before storage.

4. **Storage & Blockchain Integration**  
   **PostgreSQL stores structured user credentials.**  
   **Hyperledger Indy stores decentralized verifiable credentials.**

5. **Integration & Retrieval**  
   Organizations or users can retrieve credentials via APIs or blockchain queries.  
   **Integration module ensures smooth data exchange between the backend and storage layers.**
