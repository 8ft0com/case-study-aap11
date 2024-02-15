# Workflow

The prompt outlines a structured approach to adopting a policy-as-code framework, focusing on regulatory compliance within a specific sector, such as fintech in Australia. It is divided into distinct phases, each building upon the previous to create a comprehensive set of policy documents and technical mandates aimed at automating compliance processes. Here's a breakdown of each phase:

### Phase 1: Comprehensive Regulatory Analysis
- **Objective**: Conduct a thorough analysis of the attached document to identify key policy domains where compliance requirements can be automated.
- **Output**: A list of priority policy domains saved in markdown format as `policy-domains.md`.

### Phase 2: Formulating Compliance Mandates
- **Objective**: For each identified policy domain, create specific compliance mandates that detail what needs to be done, how it should be done, and who is responsible. This involves translating regulatory requirements into clear, actionable mandates that can inform the creation of technical controls.
- **Tasks**: 
  - Create a folder called `mandates`.
  - Within this folder, create a sub-folder for each policy domain.
  - For each policy domain, draft documents for each compliance mandate in markdown format.
- **Output**: A structured repository of compliance mandates organized by policy domain, ready for technical codification.

### Phase 3: Drafting Policies for Compliance Mandates
- **Objective**: Draft a policy for each compliance mandate identified in Phase 2. This involves creating detailed policy documents that outline the implementation steps, roles, and responsibilities for each mandate.
- **Tasks**:
  - Create a folder called `policies`.
  - Within this folder, create a subfolder for each policy domain and further subfolders for each compliance mandate.
  - Draft a policy document for each compliance mandate in markdown format.
- **Output**: A comprehensive set of policy documents, each tailored to a specific compliance mandate within the identified policy domains.

### Final Phase: Compilation and Distribution
- **Task**: Zip up all the files created in the previous phases.
- **Output**: A link to download the zip file, providing a consolidated package of all policy domains, compliance mandates, and policy documents created throughout the process.

This structured approach ensures that regulatory requirements are meticulously analyzed, translated into actionable mandates, and finally, codified into detailed policies. By doing so, it facilitates the automation of compliance within technology environments, making it an essential process for organizations in sectors where regulatory compliance is complex and mandatory.

# Pseudo Code


// Define a structured approach to adopt a policy-as-code framework for regulatory compliance

// Phase 1: Comprehensive Regulatory Analysis
BEGIN PHASE 1
  INPUT: Attached document: app11.md
  TASK: Analyse the document to identify policy domains for suitability for policy-as-code
  OUTPUT: 
    - Create a markdown document named 'policy-domains.md'
    - List priority policy domains in 'policy-domains.md'
    - provied details as to why the policy domain was chosen
END PHASE 1

// Phase 2: Formulating Compliance Mandates
BEGIN PHASE 2
  CREATE FOLDER: 'mandates'
  FOR EACH policy_domain IN 'policy-domains.md'
    TASK: 
      - Formulate compliance mandates for each policy_domain
      - Translate regulatory requirements into clear, actionable mandates
      - Include specifics on what needs to be done, how, and who is responsible
    OUTPUT:
      - In 'mandates' folder, create a sub-folder named after the policy_domain
      - In each policy_domain sub-folder, create markdown documents for each compliance mandate
END PHASE 2

// Phase 3: Drafting Policies for Compliance Mandates
BEGIN PHASE 3
  INPUT: Template.md
  CREATE FOLDER: 'policies'
  FOR EACH policy_domain IN 'mandates' folder
    FOR EACH compliance_mandate IN policy_domain folder
      TASK: create a draft policy for the compliance_mandate using the supplied tyemplate file
      OUTPUT:
        - In 'policies' folder, create a sub-folder for policy_domain
        - Within each policy_domain sub-folder, create further sub-folders for each compliance_mandate
        - In each compliance_mandate sub-folder, create a markdown document named 'policy.md' detailing the policy for the mandate
END PHASE 3

// Final: Compilation and Distribution
BEGIN FINAL
  TASK: Zip up all created files and folders
  OUTPUT: Provide a link to download the zip file containing all documents and folders
END FINAL

NOTE
  - do not stop until you have completed creating all policies for each compliance mandate