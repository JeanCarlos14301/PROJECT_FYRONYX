📘 Fyronyx – Credit Risk Predictive Model (Hackathon 2025-2)

Fyronyx is a data-driven credit-risk assessment dashboard built for the Hackathon 2025-2 at Universidad Santo Tomás.
It visualizes the results of a machine-learning model trained on 5.5M+ financial records, reduced to 8 final variables through extensive cleaning, feature selection, and validation.

The interface presents the final model performance, key metrics, risk segmentation, and sample predictions in a modern, clean, responsive static webpage.

🚀 Features
🔍 1. Dataset Summary

Raw dataset: 5.5M records, 825 variables

After cleaning and filtering: 2.8M records, 8 final variables

Automatic variable selection

Removal of leakage-prone features

Outlier treatment & missing value analysis

🤖 2. Model Performance

Validation AUC: 0.84

Test AUC: 0.84

KS: 43

Model stability validated with bootstrap

ROC curve representation

Interpretable, non-collinear, production-ready model

🔑 3. Top Predictive Variables

Variables ranked based on univariate AUC:

P_2 (78%)

D_48 (69%)

D_77 (67%)

D_61 (64%)

B_1, B_4, D_42 (≈59%)

🧠 4. Risk Segmentation Rules

High Risk: >80% → credit should NOT be granted

Medium Risk: 40–60% → conditional credit

Low Risk: <30% → credit approved

📊 5. Sample Real Predictions

A table demonstrating how the model scores real clients and assigns:

Score (%)

Risk category (Low / Medium / High)

🗂️ Project Structure
/project-root
│
├── index.html        # Main HTML file (contains full layout and documentation)
├── style.css         # Stylesheet (if external)
├── /img              # Images, logo, graphs, icons
│     ├── Graph.png
│     ├── favicon.ico
│     └── volador no identificado.png
│
└── README.md         # Project documentation (this file)

🧩 Technology Stack
Component	Technology
Frontend	HTML5, CSS3
Typography	Google Fonts (Inter)
Deployment	Vercel
Version Control	Git + GitHub

No backend or JavaScript is required.
The dashboard is 100% static and deploys instantly on any hosting provider.

🔧 How to Run Locally

Clone the repository:
git clone https://github.com/JeanCarlos14301/PROJECT_FYRONYX.git


Enter the project directory:
cd PROJECT_FYRONYX


Open the index.html file in your browser:

start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux


No dependencies, no build steps — just open and view.

☁️ Deployment on Vercel

Go to https://vercel.com/

Import your GitHub repository

Select your project

Choose:

Framework Preset: Other

Deploy

Since this project is a static site, Vercel deploys it instantly.

Your application will be live at:

https://project-fyronyx.vercel.app/

🧪 Model Summary (Machine Learning)

Although the webpage displays the results, the underlying model included:

5.5M registry ingestion pipeline

Variable cleaning & encoding

Memory optimization

Univariate feature selection

Multicollinearity elimination

Bootstrap stability testing

Final model: interpretable and optimized for production scoring

The final model achieved:

AUC: 0.84

High discrimination between good and risky clients

Low computational cost

🏆 Hackathon Context

This project was developed for:

Hackathon 2025-2 — Universidad Santo Tomás
Financial Data Modeling & AI Category

The goal:
Build a high-performance, interpretable, and efficient credit-risk scoring system.

👨‍💻 Author

Jean Carlos Reyes Delgadillo- Juan David Rodriguez Jojoa
GitHub: https://github.com/JeanCarlos14301

📜 License

MIT License – free to use, modify, and distribute.
