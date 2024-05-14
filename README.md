
# Cybersecurity References 🛡️🔒

Welcome to the a curated collection of cybersecurity resources, tools, and references for people of all skill levels.

## 📁 Directory Structure

### [Automation](./Automation-Scripts)

Personal automation scripts are kept here.

[`firewall_rules.py`](./Automation-Scripts/firewall_rules.py) takes in the URL of a CSV file to block known problematic IP addresses. The default URL downloads the "Botnet C2 Indicators of Compromise (IOCs)" from FEODOtracker, which contains "information on tracked botnet c2s but also IP addresses that were acting as a botnet C2 within the **past 30 days**."

### [References](./References)

This directory contains various files. `git` commands, [search engines for pentesters](./References/Search_Engines_for_Pentesters.jpg), printed cybersecurity blog posts, and power commands using tools like `awk`.

The ["Get Started"](./References/Get_Started-MaderasSecurityArsenal.md) guide by Maderas provides a good overview of the skills that one is expected to have in the cybersecurity industry. The guide comes with tons of lists that all contain tons of links to different resources like educational materials, software tools, and guides to cybersecurity concepts.

### [Documents](./Documents)

This directory contains a collection of documents that can be useful for cybersecurity professionals. It includes a variety of documents that can be useful for different purposes.
- [Compliance](./Documents/Compliance)
    - [Security and Privacy Controls for Information Systems and Organizations](./Documents/Compliance//800-53r5/SP_800-53_v5_1-derived-OSCAL.pdf "PDF")
        - [Spreadsheet](./Documents/Compliance/800-53r5/sp800-53r5-control-catalog.xlsx "XLSX")
    - [Implementing the Health Insurance Portability and Accountability Act (HIPAA) Security Rule](./Documents/Compliance/800-66r2/NIST.SP.800-66r2.pdf "PDF")
    - [Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations](./Documents/Compliance/800-171/NIST.SP.800-171r2.pdf "PDF")
        - [Spreadsheet](./Documents/Compliance/800-171/NIST.SP.800-171r2.pdf "XLSX")
    - [Framework for Improving Critical Infrastructure Cybersecurity](./Documents/Compliance/NIST.CSWP.04162018.pdf "PDF")
- [Continuous Learning](./Documents/Continuous-Learning/)
    - [Generative AI](./Documents/Continuous-Learning/Generative-AI/)
    - [Privacy](./Documents/Continuous-Learning/Privacy/ "Learn about digital privacy.")
    - [US State Surveillance & Psychological Operations](./Documents/Continuous-Learning/US-State_Surveillance-Psyops/ "Learn about state-sanctioned psyops in the US and abroad.")
- [Starter Penetration Testing Resources by TCM Security](./Documents/Pentest_Resources-TCM_Security/ "Resources for pentesters in the making.")
- [Sample Datasets](./Documents/Sample_Datasets/ "A collection of datasets to practice working on.")

### [UsefulRepositories](./UsefulRepositories)

This is a meta-directory with links to useful cybersecurity-related GitHub repositories. You'll find offensive, defensive, and multi-purpose tools.

Please review the [README](./UsefulRepositories/README.md)

### [Web-Applications](./Web-Applications)

Here you'll find documents for common web application vulnerabilities, like those of the OWASP Top Ten. Each document is different, but all of them contain code examples, injection payloads, that could theoretically be used in the wild. [XSS](./Web-Applications/XSS.md), [SSRF], and [CORS](./Web-Applications/CORS.md) are just a few examples. The [WebApp Exploit Checklist](./Web-Applications/WebApp-ExploitsChecklist.pdf) is a great visual reference.

## 📜 License

Distributed under the GNU AGPL-3.0 License. See [LICENSE](./LICENSE) for more information.