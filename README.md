# 🔍 Label Lens — AI-Powered Product Label Analysis

**Label Lens** is an intelligent product label analysis system designed to scan product labels, extract important information using Optical Character Recognition (OCR), and verify compliance with applicable Legal Metrology regulations. It aims to simplify label verification, identify potential labeling errors, and improve consumer transparency.

## 🚀 Project Overview

Product labels contain essential information such as product names, net quantity, maximum retail price (MRP), manufacturing details, and expiry dates. Manually checking this information for regulatory compliance can be time-consuming.

Label Lens aims to automate this process using Artificial Intelligence, OCR, Computer Vision, and rule-based validation to make product label analysis faster and more accessible.

## ✨ Key Features

- 📸 **Label Scanning:** Capture or upload product label images.
- 🔎 **OCR-Based Extraction:** Extract relevant text and product details from labels.
- 🤖 **AI-Powered Analysis:** Analyze extracted information to identify potential issues.
- ⚖️ **Compliance Verification:** Check applicable label declarations against configured Legal Metrology rules.
- ⚠️ **Error Detection:** Highlight missing information and potential labeling inconsistencies.
- 📊 **Structured Results:** Present extracted information and verification results in an understandable format.
- 🔐 **Digital Verification:** Support traceable verification records and reporting, where implemented.

## 🛠️ Technology Stack

The final technology stack depends on the modules implemented in the project.

- **Frontend:** React.js, HTML, CSS, JavaScript
- **Backend:** Python, FastAPI
- **AI and Text Processing:** OCR, Computer Vision, Natural Language Processing
- **Mobile Application:** Flutter (if enabled)
- **Database:** MySQL
- **Tools:** Git, GitHub, Visual Studio Code

## 🏗️ System Workflow

1. **Upload or Capture:** The user uploads a product label image or captures one using a camera.
2. **Text Extraction:** The OCR component extracts text from the image.
3. **Information Processing:** Relevant product declarations are identified and organized.
4. **Compliance Checking:** Extracted information is compared with configured regulatory requirements.
5. **Result Generation:** The system displays extracted details, potential violations, missing declarations, and verification results.

## 🎯 Project Objectives

- Reduce manual effort in product label verification.
- Help identify missing or inconsistent product declarations.
- Support digital compliance checking using AI-assisted tools.
- Improve transparency and accessibility of product information.
- Provide a foundation for more efficient Legal Metrology verification workflows.

## 📂 Project Structure

The project structure may vary depending on the modules implemented.

```text
Label_lens/
├── frontend/          # Web application
├── backend/           # API and application logic
├── mobile/            # Flutter app, if applicable
├── docs/              # Project documentation
├── .gitignore
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

Install the tools required by your implementation:

- Git
- Node.js and npm (for a React frontend)
- Python 3.10+ (for a Python backend)
- MySQL (if database integration is enabled)

### 1. Clone the repository

```bash
git clone https://github.com/skhaneefa42/Label_lens.git
cd Label_lens
```

### 2. Set up the frontend

If your project contains a React frontend:

```bash
cd frontend
npm install
npm run dev
```

### 3. Set up the backend

If your project contains a FastAPI backend:

```bash
cd backend
python -m venv venv
```

Activate the virtual environment.

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

Install the project dependencies:

```bash
pip install -r requirements.txt
```

Start the API server if your application entry point is `main.py`:

```bash
uvicorn main:app --reload
```

The API documentation is typically available at `http://127.0.0.1:8000/docs`.

> **Note:** These commands and folder names are examples. Adjust them to match your actual project structure and configuration.

## 🔒 Environment Configuration

If the application requires API keys or database credentials, store them in environment variables or a local `.env` file.

Never commit API keys, passwords, access tokens, or other sensitive information to GitHub. Add `.env` and other private configuration files to `.gitignore`.

## 🧪 Testing

Test the application with different product label images and verify:

- OCR extraction accuracy.
- Identification of required declarations.
- Detection of missing or inconsistent information.
- Correct behavior when images are unclear or incomplete.
- Reliability of compliance results.

## ⚖️ Compliance Disclaimer

Label Lens is intended to assist with product label analysis and preliminary compliance checks. Its results depend on image quality, OCR accuracy, implemented rules, and available product information. Results should be reviewed by a qualified person before being used for official regulatory decisions. The application does not independently guarantee legal compliance or replace official verification.

## 🔮 Future Enhancements

- Improved OCR accuracy for multilingual labels.
- Real-time camera-based label scanning.
- More comprehensive and configurable compliance rules.
- Downloadable verification reports.
- QR-based access to digital verification records.
- Mobile application integration.
- Improved dashboards and analytics.

## 👩‍💻 Contributors

Developed as a technology project focused on AI-assisted product label analysis and regulatory compliance.

**GitHub:** [@skhaneefa42](https://github.com/skhaneefa42)

## 📄 License

A license has not yet been specified. Add a `LICENSE` file if you intend to publish the project under an open-source license.
