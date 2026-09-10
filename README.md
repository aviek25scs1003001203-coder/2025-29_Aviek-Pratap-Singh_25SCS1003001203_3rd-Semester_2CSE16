# AI-Powered Resume Screening & Job Recommendation System

**AICTE – Artificial Intelligence Internship | Codec Technologies Pvt. Ltd. | IILM University**

This repository contains my internship report, presentation, project documentation, and internship completion credentials for the **Artificial Intelligence Internship** conducted at **Codec Technologies Pvt. Ltd.** The internship project focused on developing an **AI-Powered Resume Screening & Job Recommendation System** using Natural Language Processing, feature engineering, similarity modelling, ranking, and an interactive application layer.

---

## 👤 Student Details

| Field | Details |
|---|---|
| **Name** | Aviek Pratap Singh |
| **Roll Number** | 25SCS1003001203 |
| **Institute** | IILM University |
| **Programme** | B.Tech (CSE) |
| **Academic Batch** | 2026–2027 |
| **Internship Domain** | Artificial Intelligence |
| **Organization** | Codec Technologies Pvt. Ltd. |
| **Duration** | 08/07/2026 – 08/08/2026 |
| **Project** | AI-Powered Resume Screening & Job Recommendation System |

---

## 📌 About the Internship

The internship was a **one-month Artificial Intelligence Internship** conducted in hybrid mode across India. The internship emphasized practical learning through project work and training tasks, with a focus on Artificial Intelligence, project development, and practical implementation.

The main project addressed the challenge of screening resumes and matching candidate profiles with suitable job opportunities. The proposed system processes resume and job-description text, extracts relevant information and skills, calculates candidate–job similarity, applies ranking logic, and produces suitable job recommendations.

The project combines **Natural Language Processing (NLP)**, **feature engineering**, **machine learning**, **similarity scoring**, **ranking**, and an **interactive application layer**.

---

## 🎯 Project Objectives

- Extract education, experience, skills, projects, and keywords from resume text
- Identify technical and professional skills using NLP and keyword/semantic matching
- Process and normalize resume and job-description text
- Convert text into useful machine-learning features
- Generate TF-IDF and semantic representations
- Compare candidate profiles with job descriptions using vector similarity
- Apply cosine similarity and weighted matching for candidate–job compatibility
- Combine skills, experience, education, and role requirements during recommendation
- Rank suitable job roles according to relevance
- Return match scores and relevant detected skills
- Provide an interactive interface for ranked recommendations

---

## 🧠 Project Overview

The project is designed as an end-to-end AI-assisted recruitment-support workflow.

### Problem

Recruiters may receive a large number of resumes for a single role. Manually reviewing and comparing each resume against job requirements can be time-consuming. Resumes can also describe similar skills using different terminology, making simple keyword-based screening less effective.

### Proposed Solution

The proposed system uses AI and NLP techniques to:

1. Accept resume or job-related input
2. Clean and preprocess the text
3. Extract candidate and role features
4. Identify relevant skills
5. Generate numerical/semantic representations
6. Calculate similarity between candidate and job profiles
7. Apply ranking and recommendation rules
8. Return ranked job recommendations

---

## 🏗️ System Architecture

The architecture presented in the internship project follows this pipeline:

```text
Resume / Job Input
        ↓
Text Preprocessing
        ↓
Feature Extraction
        ↓
Similarity Model
        ↓
Ranked Recommendations
```

### Architecture Components

| Component | Description |
|---|---|
| **Resume / Job Input** | Resume documents, job descriptions, target role, skills, and experience |
| **Text Preprocessing** | Cleaning, normalization, tokenization, and preparation of text |
| **Feature Extraction** | TF-IDF vectors, semantic representations, and skill features |
| **Similarity Model** | Calculates candidate–job compatibility using similarity techniques |
| **Recommendation Layer** | Applies ranking rules and returns matching roles |
| **Application Layer** | Provides interactive input and ranked recommendations |

---

## 🔄 Recommendation Workflow

```text
Project Input
     ↓
Feature Analysis
     ↓
AI Matching
     ↓
Output
```

### 1. Project Input

The system can work with:

- Resume text
- Target role
- Candidate skills
- Candidate experience
- Job description

### 2. Feature Analysis

The system extracts:

- Skills
- Education
- Experience
- Keywords
- Role requirements

### 3. AI Matching

NLP features and matching logic are used to generate similarity scores between the candidate profile and job requirements.

### 4. Output

The system returns:

- Ranked job recommendations
- Match scores
- Relevant detected skills

---

## 🛠️ Technologies & Tools

`Python` · `Pandas` · `NumPy` · `NLP` · `NLTK/spaCy` · `Scikit-learn` · `TF-IDF` · `Embeddings` · `Cosine Similarity` · `Machine Learning` · `Streamlit`

### Technology Areas

| Area | Technologies / Concepts |
|---|---|
| **Programming & Data** | Python, Pandas, NumPy |
| **NLP Processing** | NLTK/spaCy, text cleaning, tokenization, extraction |
| **Feature Engineering** | TF-IDF vectors, semantic representations, skill features |
| **Machine Learning** | Scikit-learn, embeddings, similarity scoring |
| **Matching** | Cosine similarity, weighted matching |
| **Application** | Streamlit |

---

## 📚 Key Concepts

### Natural Language Processing

NLP is used to process unstructured resume and job-description text. The project presentation identifies text cleaning, tokenization, stop-word handling, and keyword extraction as relevant processing activities.

### TF-IDF

TF-IDF is used to transform text into numerical feature vectors. It provides a representation that can be used for comparing candidate and job-description text.

### Cosine Similarity

Cosine similarity is used to measure the similarity between vector representations of candidate and job profiles. It supports the job-matching stage of the project.

### Semantic Features

The project also identifies semantic representations and embeddings as part of its AI toolchain, allowing the matching process to work with richer representations than simple exact keyword overlap.

### Weighted Matching

The recommendation logic combines multiple candidate and role attributes, including:

- Skills
- Experience
- Education
- Role requirements

---

## 🗓️ Internship Timeline

| Week | Work Completed |
|---|---|
| **Week 1** | Explored the problem, reviewed resume/job datasets, examined text fields, and understood project requirements |
| **Week 2** | Cleaned resume and job-description text, extracted skills, and prepared NLP features |
| **Week 3** | Implemented similarity scoring, ranking logic, and recommendation workflow |
| **Week 4** | Tested recommendations, refined the workflow, and completed project documentation |

---

## 📊 Project Indicators

The internship presentation includes an example AI resume-screening output:

| Indicator | Value |
|---|---:|
| **Resume Match Score** | **87%** |
| **Skills Detected** | **14** |
| **Recommended Roles** | **5** |

> **Note:** These values are project/interface indicators shown in the internship presentation. They should not be interpreted as independently validated model accuracy or formal evaluation metrics.

---

## 💡 Key Project Work

### Data & Preprocessing

- Prepared resume and job-description text
- Cleaned noisy content
- Normalized terminology
- Created structured inputs

### NLP & Feature Engineering

- Applied text preprocessing
- Used tokenization
- Handled stop words
- Performed keyword extraction
- Prepared TF-IDF/semantic features

### Similarity & Ranking

- Used similarity-based candidate–job comparison
- Applied cosine similarity
- Used weighted matching
- Ranked candidate–job compatibility

### Recommendation Logic

- Combined skills
- Considered experience
- Considered education
- Considered role requirements
- Generated ranked job recommendations

---

## 🧪 Testing & Validation

The internship timeline identifies testing and recommendation refinement during **Week 4**.

Functional testing of the workflow can include:

- Verifying text preprocessing
- Checking skill extraction
- Checking similarity calculation
- Confirming ranking consistency
- Verifying recommendation output
- Checking application interaction

The supplied internship presentation does **not** provide formal accuracy, precision, recall, F1-score, ROC-AUC, confusion matrix, dataset size, or train/test split. Therefore, no formal model-performance claim is made in this repository.

---

## 🎓 Learning Outcomes

Through this internship, I gained practical exposure to:

- Artificial Intelligence applications
- Natural Language Processing
- Text preprocessing
- Resume parsing
- Skill extraction
- Feature engineering
- TF-IDF
- Semantic representations
- Cosine similarity
- Machine-learning-based matching
- Ranking and recommendation logic
- Streamlit application development
- End-to-end AI project workflow

The project helped connect theoretical AI concepts with a practical recruitment-oriented application.

---

## 🚀 Advantages

- Reduces repetitive manual screening effort
- Provides a structured candidate–job comparison workflow
- Produces ranked recommendations
- Identifies relevant skills from textual information
- Supports consistent matching logic
- Provides match scores for easier interpretation
- Uses a modular architecture that can be improved stage by stage

---

## ⚠️ Limitations

The supplied internship presentation does not document:

- Complete source code
- Exact dataset provenance
- Package versions
- Exact model configuration
- Exact embedding model
- Scoring weights
- Database architecture
- Deployment infrastructure
- Formal benchmark results

Resume data may also contain inconsistent formatting, ambiguous terminology, missing information, and different descriptions of similar skills.

For a real recruitment deployment, fairness, bias, explainability, robustness, privacy, and human review would require additional consideration and validation.

---

## 🔮 Future Scope

Possible future improvements include:

- Advanced semantic embeddings
- Improved skill ontologies
- Better synonym and related-skill matching
- More accurate experience extraction
- Improved education extraction
- Configurable recommendation weights
- Explainable recommendation reasons
- Recruiter-controlled preferences
- Larger and more diverse datasets
- Formal model evaluation
- Bias and fairness testing
- Robustness testing across different resume formats
- Secure document processing
- Scalable deployment and monitoring

---

## 🏆 Internship Credentials

The supplied internship presentation includes internship verification material and an internship certificate.

| Field | Details |
|---|---|
| **Internship Title** | Artificial Intelligence Internship |
| **Role / Designation** | Artificial Intelligence Intern |
| **Organization** | Codec Technologies Pvt. Ltd. |
| **Internship Domain** | Artificial Intelligence |
| **Duration** | 08/07/2026 – 08/08/2026 |
| **Project** | AI-Powered Resume Screening & Job Recommendation System |

---

## 📁 Repository Contents

```text
├── Internship_Report_Aviek_Pratap_Singh.pdf
├── Internship_Report_Aviek_Pratap_Singh.docx
├── AI_Internship_Presentation.pdf
├── Internship_Certificate.png
├── Internship_Offer_Letter.png
└── README.md
```

> Rename the files above to match the exact filenames you upload to your GitHub repository.

---

## 📄 Report Structure

1. Executive Summary
2. Introduction
3. Internship and Candidate Profile
4. Organization Profile
5. Problem Statement and Industry Context
6. Project Objectives
7. Technologies and Al Toolchain
8. System Architecture
9. Methodology and Workflow
10. Implementation Work
11. Internship Timeline
12. Project Performance Indicators
13. Skills Demonstrated and Learning Outcomes
14. Advantages of the Proposed System
15. Limitations
16. Future Scope
17. Conclusion
18. Internship Verification
19. Source Note
---

## 🙏 Acknowledgement

I would like to express my gratitude to **Codec Technologies Pvt. Ltd.** for providing the opportunity to undertake an Artificial Intelligence internship and work on an application-oriented AI project.

I also acknowledge **IILM University** for its academic support and guidance during the internship period.

The internship provided valuable practical exposure to Natural Language Processing, machine learning, feature engineering, similarity modelling, recommendation systems, and AI application development.

---

## 👨‍💻 Author

**Aviek Pratap Singh**  
B.Tech (CSE)  
IILM University  
Roll No. **25SCS1003001203**

---

> **Project:** AI-Powered Resume Screening & Job Recommendation System  
> **Internship:** Artificial Intelligence Internship  
> **Organization:** Codec Technologies Pvt. Ltd.  
> **Duration:** 08/07/2026 – 08/08/2026
