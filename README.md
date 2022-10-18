java-api-example
================
This repo has sapmle Java API source code, objective is to use GitHub out of the box Code Scanning tools like CodeQL to run code analysis, detect vulnerabilities, report them within GitHub reporting feature. Auto propose pull requests for detected vulnerabilities and verson updates from DependaBot future 

# GitHub Code Scanning
Code scanning enables vulnerabilities to be detected and remediated prior to release into production, eliminating the cybersecurity risks that they pose. I recommond to choose GitHub native solutions for code scanning, code reviews and statit code analysis for seamless experience such as CodeQL or GraphQL etc

# GitHub Native and Alternative Solutions
GitHub out of the box solutions are amazing, in this specific scenario, I want to scan the Sample-java-API repo code to make sure it meets the standards, auto review, check for vulnurabilities at the development stage itself, before the code with vulnerabilities gets deployed into any environments, expessally production env. This repos has GitHub CodeQL code scanning yml files and also SonarCloud as an alternative to address false positives, GitHub actions CI to execute actions under GitHub WorkFlows.

# Note: 
For your need GitHub provides alternative tools in GitHub marketplace, like SonarCloud run code scanning and analysis for GitHub workflows is an amazing feature. If you're consurned about false positives when using one code scanning tool, GitHub marketplace is always an option.
