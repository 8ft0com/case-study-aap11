CONTEXT: You are a compliance officer at an on-line bank.

I'm going to set you a multi-phase task. Please pay close attention.

1.  remove all files created during this session

2.  start with phase 0 and continue until the end of phase 4
  - list the full pathname of any new file that you create 

3. IMPORTANT: after completing each phase:
  - verify that you have completed the whole process and tasks for everything that was requested in that phase
  - make sure that there are no missing files
  - if you have forgotten to do something, do it before moving on to the next phase
  - list all the files created at the end of each phase
  - let me know that you have completed the verification process

4. IMPORTANT
- DO NOT use placeholders, you must provide detail as best as you can
- DO everything that is requested
- DO not skip any instructions
- If asked to complete a list, make sure that every item on the list is completed
- I don't want to review anything or have to ask you to continue
- DO NOT stop until all phases have been completed

---
# START

# PHASE 0: set up
- PROCESS: start with a clean /mnt/data folder
  - TASKS: 
    - delete all files and folders in /mnt/data
    - confirm /mnt/data is empty

  - GOAL: a clean /mnt/data folder

# PHASE 1: Comprehensive Regulatory Analysis

- PROCESS: Conduct a thorough analysis of the attached regulations.md document to identify key policy domains where compliance requirements can be automated.
  - TASKS: 
    - focus on policy domains that lend themselves to implementation using policy-as-code
    - use the domains-template.md file as a document template  
    - use the domains-example.md file as a document example 
  
  - GOAL: A list of priority policy domains saved in markdown format as `policy-domains.md`.

---

# PHASE 2 : Formulating Compliance Mandates

- PROCESS: For each identified policy domain, create specific compliance mandates that detail what needs to be done, how it should be done, and who is responsible. 
  - This involves translating regulatory requirements into clear, actionable mandates that can inform the creation of technical controls.
  - IMPORTANT: do this for ALL policy domain
  - TASKS: 
    - Create a folder called `mandates`.
    - For each policy-domain in `policy-domains.md`, list the title of the policy-domain and a brief summary of it
      - create a compliance-mandate document in markdown format and save in the `mandates` folder
        - use the mandate-template.md file as a compliance-mandate document template  
        - use the mandate-example.md file as a compliance-mandate document example 
        - use your data-analysis and code-interpreter capabilities to create the documents as requested. 
        - create the documents sequentially, one at a time. 

  - GOAL: A comprehensive set of compliance mandates organized by policy domain, ready for technical codification.

  - END: list the files created in this phase
---

# PHASE 3: Drafting Policies for Compliance Mandates

- PROCESS: Draft a policy for each compliance mandate created. 
  - This involves creating detailed policy documents in accordance with the format in the template
  - IMPORTANT: do this for ALL compliance mandates 
  - TASKS:
    - Create a folder called `policies`.
    - Within this folder, create a subfolder for each policy-domain.
    - for each compliance-mandate document in the `mandates` folder, extract the list of mandates
      - for each mandate create a policy document in markdown format and save it in the correct `policies` sub-folder 
        - use the policy-template.md file as a policy document template  
        - use the policy-example.md file as a policy document example 
        - use your data-analysis and code-interpreter capabilities to create the documents as requested. 
        - create the documents sequentially, one at a time. 

  - GOAL: A structured repository of policy documents, each tailored to a specific compliance mandate within the identified policy requirement.

---

# PHASE 4: export files

- PROCESS: export files
  - TASKS: 
    - list all files created for the above phases
    - Zip up all created files and folders
  
  - GOAL: Provide a link to download the zip file containing all documents and folders


---

# STOP