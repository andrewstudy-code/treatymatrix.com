# Treatymatrix — AI-Powered Legal Tech for Sanctions Compliance & Contract Automation

*Project developed as part of [Harvard CS50](https://cs50.harvard.edu/x/) — Introduction to Computer Science.*

## 🚩 The Problem

In the current geopolitical landscape, companies must verify their business partners against international sanctions lists (OFAC, EU, UN) before signing contracts. This routine task is time‑consuming and prone to human error.

## ⚙️ Solution

- **Automation:** Treatymatrix generates standardized legal documents with built‑in compliance checks.
- **Verification:** Integration with open‑source API databases allows instant verification of counterparties.
- **AI Analysis:** NLP module scans contract texts for risks and inconsistencies.

## 🛠 Architecture

| Component | Technologies |
|---|---|
| Backend | Python + Flask *(API for document generation)* |
| Frontend | HTML/CSS/JS *(responsive landing page)* |
| NLP Model | Planned integration with OpenAI / Fine‑tuned model for legal text analysis |
| Hosting | GitHub Pages + Cloudflare DNS (*SSL certificate, custom domain treatymatrix.com*) |

## 💼 MVP (Minimum Viable Product)

Currently implemented:
- Responsive "Under Construction" landing page with email subscription form.
- Domain infrastructure (`treatymatrix.com`) via Cloudflare.
- Ready‑to‑use architecture for future ML deployment.

## 🔥 Next Steps

1. Implement dynamic contract generator.
2. Integrate APIs from public sanctions databases.
3. Develop a fine‑tuned NLP model for legal terminology analysis.
