# 🛡️ IMSSS AI Risk Assessor: The Sense, Assess, and Fix Compliance Tool

The IMSSS AI Risk Assessor is a **stable, server-less Single Page Application (SPA)** designed to quickly map and measure an organization's compliance readiness against leading global AI standards.

It operationalizes the **Sense, Assess, and Fix (SAF) Methodology** to turn abstract regulations into concrete, actionable steps.

## 🚀 Live Application

The current, stable version of the application is hosted on GitHub Pages:

➡️ **[Access the IMSSS AI Risk Assessor Now!](https://imsspakistan-commits.github.io/imsss-sync-services/)**

---

## 🧭 Our Methodology: Sense, Assess, Fix (SAF)

The tool structures the audit process into a simple, three-step methodology to ensure comprehensive coverage and clear next steps:

### 1. **SENSE (Discovery)**
* The tool uses a **structured, 5-question audit** to gather data on the current state of the AI system across core domains.
* *Outcome:* An inventory of compliance gaps across Governance, Security, Data Integrity, Risk Management, and Documentation.

### 2. **ASSESS (Evaluation)**
* Inputs are instantly scored against the mandates of **ISO 42001, the EU AI Act, and the NIST AI Risk Management Framework (RMF)**.
* *Outcome:* A **Confidence Score**, a visual **System Metrics** radar chart, and a calculation of potential **EU AI Act Liability**.

### 3. **FIX (Remediation)**
* The report generates a specific **Violation & Remediation Summary** that prescribes mandatory corrective actions.
* *Outcome:* A formal **action plan** (e.g., "Formalize Top Management sign-off. Assign clear roles (ISO 42001, 5.3)") that directly enables the organization's compliance efforts.

---

## ✨ Key Features & Technical Assurance

| Feature | Benefit & Assurance |
| :--- | :--- |
| **Immutable PDF Report** | Generate a permanent audit record suitable for regulatory documentation, complete with an **Immutable Hash** for verification and integrity assurance. |
| **Localized Data Storage** | The application is **server-less**. All audit progress and data are stored **only in your browser's local storage**—no external transmission occurs, ensuring maximum user privacy. |
| **Stable, Production Ready** | The application features custom routing logic using a `404.html` fallback to ensure **the app never breaks on browser refresh** on internal pages, enhancing the user experience. |
| **Clear User Guidance** | Updated **Secure Audit Terms** and **Audit Record Identification** screens clarify that contact information is solely for embedding into the final PDF report. |

---

## 🛠️ Installation and Development

This is a Single Page Application (SPA) built with React. To run locally for development:

```bash
# Clone the repository
git clone [YOUR-REPO-URL]
cd imsss-sync-services

# Install dependencies and start the development server
npm install
npm start
