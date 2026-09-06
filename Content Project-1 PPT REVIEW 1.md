PROJECT 1 - RAG

Title: **Claim Sense:** RAG-Based Insurance Claims Adjudication \& Policy Knowledge Assistant



**Background**



P\&C (property \& casualty) and health insurers process thousands of claims monthly. Each claim adjudication decision requires cross-referencing the specific policy document, coverage exclusions, past claim precedents, and regulatory/compliance guidelines — documents that are long, dense, and scattered across systems. Adjusters currently do this manually, causing slow turnaround (5–10 days per claim), inconsistent decisions between adjusters, and claim leakage (over/under-payment) from missed exclusion clauses.



**Problem statement**



Design and implement a RAG-based intelligent claims adjudication assistant that ingests a claim (structured claim data + free-text incident description), retrieves the relevant clauses from the customer's specific policy document and applicable regulatory guidelines, classifies the claim's fraud/anomaly risk using a trained ML model, and generates a structured, citation-backed adjudication recommendation (approve / investigate / deny) with the exact policy clause justifying it.



The system must:



. Generate realistic synthetic policy documents, claims, and claim-history datasets

. Build a RAG knowledge base over policy wordings, exclusion clauses, and regulatory circulars

. Classify each incoming claim's fraud/anomaly risk (Low/Medium/High) using structured claim features

. Retrieve and cite the exact policy clause(s) relevant to the claim

. Generate an explainable adjudication recommendation with reasoning

. Provide an adjuster-facing interactive dashboard

. Support scalable deployment on Microsoft Azure with full MLOps/CI-CD



**Objectives**



**Data engineering**: synthetic policy corpus (coverage terms, exclusions, riders) + synthetic claims (10,000–50,000 records) with realistic fraud-pattern injection



**ML objectives**: train a fraud/anomaly risk classifier (Logistic Regression, Random Forest, Gradient Boosting, XGBoost) on claim features (claim amount vs. sum insured, time-since-policy-start, claim frequency, prior claim history, incident-description sentiment/anomaly signals)



**RAG objectives**: chunk and embed policy documents + regulatory guidelines; hybrid retrieval (dense + keyword); generate adjudication explanation with inline clause citation



**Analytics objectives**: claim trend dashboards, fraud-risk distribution, clause-citation frequency (which exclusions get invoked most)



**Cloud/MLOps objectives**: Azure deployment, MLflow experiment tracking + model registry, CI/CD via Azure DevOps/GitHub Actions → ACR → AKS, drift monitoring with auto-retrain triggers



**Input features (structured)**: Claim amount, Sum insured, Policy tenure, Days since policy start, Prior claim count, Claim type, Incident location, Time-of-day pattern, Claimant history flags



**Knowledge base content**: Policy wordings \& riders, exclusion clause libraries, IRDAI/regulatory circulars, historical adjudication precedents, SOP for claims investigation



**Output categories**: Fraud/anomaly risk (Low / Medium / High) + Adjudication recommendation (Approve / Flag for investigation / Deny) + cited policy clause(s)



**Technology stack:**



**Category	       Technology**

Programming	       Python

RAG framework	       LangChain

Embeddings	       Sentence Transformers

Vector database	       FAISS / ChromaDB

LLM integration	       Azure OpenAI

ML classification      Scikit-learn, XGBoost

Experiment tracking    MLflow

Data processing	       Pandas, NumPy, Apache Spark

Backend API	       FastAPI

Frontend	       Streamlit

Database	       PostgreSQL / Azure SQL

Deployment	       Docker → Azure Container Registry → Azure Kubernetes Service

Monitoring	       Azure Monitor

Storage	               Azure Blob Storage



Make a PPT for this Project-1 title is **Claim Sense:** RAG-Based Insurance Claims Adjudication \& Policy Knowledge Assistant add this title in the first page of ppt where the Project title name is mentioned in that add this title name for Project-1.

Use the mentioned Font size for project title(Calibri Body-36).

&#x20;

Instead of team member in ppt Add my name in that place: S K Sricharan use the mentioned font size(Calibri Body-24)



For each slides use the mentioned font size(Calibri Body - The size which they have mentioned in each slides).



Each Slides contain:

1. Introduction.
2. Objective.
3. Scope.
4. Literature review.
5. Summary of Literature.
6. Additional Information.
7. Modules to cover.
8. Module Name.



Make a separate ppt for this topic collect  all the relevant current content, information for this topic(Project Title-1: **Claim Sense:** RAG-Based Insurance Claims Adjudication \& Policy Knowledge Assistant) make a content for all the above mentioned titles for the PPT SLIDES which I have mentioned above. I will mention it below for clarification.



Each Slides contain:

1. Introduction.
2. Objective.
3. Scope.
4. Literature review.
5. Summary of Literature.
6. Additional Information.
7. Modules to cover.
8. Module Name.

Collect the content for these topics make a PPT and don't forget to use mentioned font size which they mentioned in PPT Template.



First Page of PPT Project Title(add the project title name): **Claim Sense:** RAG-Based Insurance Claims Adjudication \& Policy Knowledge Assistant



Instead of team memeber place add my name: S K Sricharan.



After the first page all other slides in the top right of the ppt they have mentioned Project Title - Calibri Body - 18) - In that add the Project 1 title name: **Claim Sense:** RAG-Based Insurance Claims Adjudication \& Policy Knowledge Assistant(Use the mentioned fontsize(Calibri Body - 18)).



Analyse the topic well(**Claim Sense:** RAG-Based Insurance Claims Adjudication \& Policy Knowledge Assistant(RAG)) collect relevant information make a ppt from the given template.



Remember: Collect only the current releavant content and information to this topic and ppt slides topics which I have mentioned above.



Mention this project in a short summary like what it will be doing, what it's outcomes and how it will used as a product explain it from the title.



