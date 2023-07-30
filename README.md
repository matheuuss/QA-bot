# QA-bot

 Performs Q&A on upto 150+ documents by running inference on Hugging Face's open source google/flan-t5-xxl model.
 
 Additonally, the model (sentence-transformers/all-mpnet-base-v2) which is again, open source on Hugging Face, is used to generate embeddings as well as find sentences/paragraphs in the document with similiar embeddings to the question, to give as input to the LLM.

 Some inputs qs and output answers:
 The document in question is a paper on cloud security auditing titled, "Cloud security audit – issues and challenges" by Livia Maria Brumă.
 
 Q1. What is this paper about?
     Cloud Security Auditing
     
 Q2. Why is cloud security audit important?
     The results obtained provide useful information for understanding and addressing the risks associated with cloud technologies

 Q3. What is the role of internal audit?
     to help manage and assess the security and compliance risks of the services provided by CSP

 Q4. What is the conclusion of this paper?
     Cloud-based systems need specific security methods; traditional methods are not enough.


 Note that the answers are one liners as the LLM is not a powerful one.
