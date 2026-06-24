# Secure Asset Delivery & Monetization Pipeline (Azure)

## 📌 Project Overview
An enterprise-grade, cloud-hosted file delivery system designed to securely host, restrict, and monetize digital assets. This project bridges the gap between secure cloud infrastructure and e-commerce automated workflows using my Azure for Students environment.

## 🛠️ Tech Stack & Services
* **Cloud Provider:** Microsoft Azure
* **Storage Engine:** Azure Blob Storage (Object Storage)
* **Replication Tier:** Locally-Redundant Storage (LRS)
* **Security Layer:** Shared Access Signatures (SAS) Tokens
* **Fulfillment Platform:** Gumroad / Stripe Checkout Engine

## 🔒 Security Best Practices Implemented
* **Principle of Least Privilege:** Storage containers are set to `Private` with anonymous read access completely disabled. 
* **Time-Bound Authentication:** Implemented granular, read-only Shared Access Signature (SAS) tokens to grant temporary file access, eliminating the need to expose master storage account keys.

## 📈 Learning Outcomes
* Gained hands-on experience navigating the Microsoft Azure Portal dashboard.
* Mastered object storage management, data segmentation, and data access policies.
* Developed a strong understanding of cloud cost management and cloud security principles.
