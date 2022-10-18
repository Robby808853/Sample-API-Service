Java-API-Example
================
This repo has sapmle Java API source code, objective is to use GitHub out of the box Code Scanning tools like CodeQL to run code analysis, detect vulnerabilities, report them within GitHub reporting feature. Auto propose pull requests for detected vulnerabilities and verson updates from DependaBot future 

# GitHub Code Scanning
Code scanning enables vulnerabilities to be detected and remediated prior to release into production, eliminating the cybersecurity risks that they pose. I recommond to choose GitHub native solutions for code scanning, code reviews and static code analysis for seamless experience such as CodeQL or GraphQL etc

<img width="1232" alt="Screen Shot 2022-10-18 at 10 54 03 AM" src="https://user-images.githubusercontent.com/43921439/196513218-498f2878-7c9c-4b85-87ec-4768c4da90a4.png">

# GitHub Native Solutions
GitHub out of the box solutions are amazing, in this specific scenario, I want to scan the Sample-java-API repo code to make sure it meets the standards, auto review, check for vulnurabilities at the development stage itself, before the code with vulnerabilities gets deployed into any environments, expessally production env. This repos has GitHub CodeQL code scanning yml files and also SonarCloud as an alternative to address false positives, GitHub actions CI to execute actions under GitHub WorkFlows.

<img width="682" alt="Screen Shot 2022-10-17 at 1 48 41 AM" src="https://user-images.githubusercontent.com/43921439/196513752-15261906-bd9e-42fc-b21e-70b4502b435c.png">

<img width="1175" alt="Screen Shot 2022-10-16 at 11 34 31 PM" src="https://user-images.githubusercontent.com/43921439/196513823-0baf2a7a-a506-4185-9298-e8ad09167700.png">

# Note: Alternative Solutions
For your need GitHub provides alternative tools in GitHub marketplace, like SonarCloud run code scanning and analysis for GitHub workflows is an amazing feature. If you're consurned about false positives when using one code scanning tool, GitHub marketplace is always an option.
