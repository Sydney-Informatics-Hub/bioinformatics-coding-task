
# Background 

A researcher working in pharmacogenomics has approached SIH with a dataset they were given by a past collaborator. They are investigating population-level genetic variation to understand variable patient responses to medications. The dataset comprises a cohort-level VCF and sample metadata file.  

This researcher has not provided a specific hypothesis but is interested in exploratory analysis and has asked you the questions below. They are a clinician with no bioinformatics background and would appreciate a clear summary of your results. Before you handover your results, another bioinformatician in your team will review your work, including your code.  

# Client Questions 

- What is in this VCF? Can you give me a sense of what markers are in here? Are any of them known to be functional?  
- Who is in the dataset? How many people are included and how are they distributed across populations? Is the dataset complete or are there gaps?  
- Do individuals from different population groups look genetically distinct in this region?  
- What can you tell me about the SNP at 6:160136611 in this cohort?  Could it be clinically significant?   

# Provided Data 

You will receive: 

- `samples.vcf.gz`: A gzipped cohort VCF file covering a 10 Mb window of chromosome 6 from the human genome assembly hg38  
- `samples_meta.psam`: A sample metadata file with population assignments 

You can find these files in [`/data`](https://github.com/Sydney-Informatics-Hub/bioinformatics-coding-task/tree/main/dataset).

# Deliverables 

Create a **private GitHub repository in your personal account** that includes: 

- Scripts and/or notebooks used in your analysis
- `README.md` with: 
  - High level summary of the contents of the repository
  - Overview of the client request and your approach 
- `METHODS.md` that that will be shared with your colleagues and the researcher. It must contain: 
  - Links to any documentation or literature you used
  - Instructions for setting up an environment and running the code
  - A step-by-step methods summary
  - Justification of your methods where relevant 
- `HANDOVER.md` that will be given to the researcher. It must contain:
  - Key findings and visualisations
  - Plain language summary answering the client’s questions
  - A methods write up of your findings suitable for inclusion in a publication  

Your analysis should be reproducible, clearly documented, scientifically sound. Please submit your completed task by 9am AEST, 7th July. 

# Notes 

- You may perform this analysis in your coding language(s) of choice and platforms e.g. RStudio, Positron, Jupyter notebook, Unix/Linux terminal  
- Visual clarity and well-documented analytical workflows are expected
- A complete, polished set of results may not be feasible in the time allocated for this task. Prioritise clarity over completion. 
 
