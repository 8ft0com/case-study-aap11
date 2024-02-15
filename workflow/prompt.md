

# phase 1

task: 
    - Perform an Comprehensive Regulatory Analysis on the attached document
      - In the context of adopting a policy-as-code approach, the primary step involves a detailed analysis of the regulatory environment to identify areas where compliance requirements can be translated into technical rules for automation.
      - This process is crucial for organisations, especially in sectors like fintech in Australia, where regulatory compliance is both complex and mandatory.
      - The goal is to focus on policy domains that offer clear pathways for codification into technical controls and automated monitoring systems.

output:
    - list of priority policy domains
    - markdown format
    - save as policy-domains.md

# phase 2

task:
    - create a folder called mandates
    - for each policy-domain in policy-domains.md
      - Formulate Compliance Mandates for each policy-domain
        - Following the comprehensive regulatory analysis, the next pivotal step in implementing a policy-as-code framework is the distillation of these regulatory requirements into clear, actionable compliance mandates. 
        - This process involves translating the broad and often complex language of regulations into discrete, specific mandates that directly inform the creation of technical controls and configurations. 
        - The aim is to produce a set of actionable, codifiable rules that can be automated within technology environments.
      - Each mandate should clearly state what needs to be done, how it should be done, and who is responsible. 
        - This clarity is crucial for the next stage, where these mandates are codified into policy rules.

output:
    - in the mandates folder create a sub-folder for the policy-domain
    - a document for each Compliance Mandates saved in the relevant policy-domain folder
    - save in markdown format 


# phase 3

task:
    - create a folder called policies
    - in the policies folder create a subfolder for each policy-domain and in each policy-domain folder further subfolders for each compliance-mandate
    - for each compliance-mandate identified in phase 2
      - draft a policy for that compliance-mandate


output:
    - a document for each policy saved in the relevant policy-domain/compliance-mandate folder
    - save in markdown format 


# final

task:
    - zip up all the files

output:
    - link to download the zip file