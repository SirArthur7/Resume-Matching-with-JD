# Resume Matching with JD
Repo for Resume Matching with Job Descriptions by extracting details from CVs in PDF format, and matching them against the fetched job descriptions based on skills and education.
Parsed resumes into following categories- 
•	Category
•	Education
•	Skills
•	Experience
•	Achievements
•	Others (Awards, Publications, Certifications, Volunteer Experience, Interests, Languages, Licenses, etc.)
Summary

Datasets used- jacob-hugging-face/job-descriptions, https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset
Language Models used (for tokenizing and creating embeddings)- naver/splade-cocondenser-selfdistil
Libraries used- PyPDF2, fuzzywuzzy, unidecode, datasets, transformers, sentence-transformers
