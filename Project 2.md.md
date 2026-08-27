**Agentic AI**

**Project 2: Site Guard AI — Multi-Agent Construction Safety \& Quality Incident Resolution System.**



Make a ppt for this title I'am going to do project for this title and I give you the background for this topic.



**Category:** Agentic AI (LangGraph) | **Domain:** Construction / EPC / Infrastructure



**I'am going to do a PPT presentation for zeroth review so make a ppt, In my ppt I'am going to include these topics:**



**1. Problem statement**

**2. Objectives in detail**

**3. Dataset including how it is collected or generated and it's relevance to the objectives**

**4. Technical stack**

**5. Expected outcomes.**



**From the above topics I have mentioned provide the necessary things, content for each topics for my PPT presentation, Make the content for my ppt.**



**Give me the contents for each topics all should be able to add in PPT within TWO Slides.**



**Here I will give my problem statement include these contents and also analyse well based on the given topic.**



**Problem Statement:**



Large EPC construction sites generate thousands of safety observations, near-miss reports, quality non-conformance reports (NCRs), and daily progress reports (DPRs) across multiple contractors. Site engineers currently cross-reference IS codes, OSHA/BOCW safety norms, and past incident logs manually — this takes hours per incident and root causes are inconsistently tracked, leading to repeat safety violations and project delays.



**What makes it different from Secure Ops / Prop Agent / P004:** 



Those are SOC alerts, real-estate title diligence, and IT-ops logs respectively. This is physical-site safety/quality incident triage — a new domain entirely, and squarely L\&T's own business.



**Multi-agent design (LangGraph):**



&#x20;      1. Intake Agent – structures free-text safety/quality reports (site, contractor, severity, trade)

&#x20;      2. Retrieval Agent – RAG over IS codes, BOCW safety regulations, site SOPs, past incident corpus

&#x20;      3. Root-Cause Agent – chain-of-thought analysis against a construction-specific FMEA/5-Why library

&#x20;      4. Corrective Action Agent – drafts corrective/preventive action (CAPA) with responsible party and due date

&#x20;      5. Escalation Agent – auto-flags Critical/repeat violations to the safety officer



**Tech stack:**

**Layer	          Technology**

Agent framework	  Lang Graph

LLM	          Ollama + Llama 3.1 8B (local) / Azure OpenAI (cloud option)

Knowledge base	  ChromaDB / Qdrant + Sentence Transformers

Backend	          FastAPI + Pydantic

Frontend	  Streamlit or React dashboard (incident queue, agent reasoning trace, CAPA tracker)

Database	  PostgreSQL (incidents, CAPA, audit trail)

Deployment	  Docker Compose → Azure Container Instances / AKS, or fully local

Synthetic data	  Generate synthetic DPRs, safety observations, NCRs (5,000–15,000 records) simulating multiple trades/sites.



Include the all other things releted to this topic for the  Project 2.



Finally the above mentioned topics for ppt presentation should be included all contents within Two Slides.

&#x20;









