# Vulnerability Scanning & Remediation using Nessus

This post documents the process of setting up and conducting vulnerability scans using Nessus on a client machine with a deprecated Firefox application, remediation and retesting the client machine for vulnerabilities. 

## Prerequisites

Before getting started, ensure you have the following prerequisites in place:

- A client machine with a deprecated Firefox application installed
- Nessus vulnerability scanner installed on your system

## Setup Instructions


1. **Install & Configure Nessus Vulnerability Scanner:** Download and install Nessus on your system. Create a user account, set up a scan policy, and configure the scan targets.

2. **Prepare the Client Machine & Run Scan:** Set up a client machine with a deprecated Firefox application installed. This outdated version of Firefox will act as the target for vulnerability scanning. Nessus will scan the client system, identify vulnerabilities, and provide a comprehensive report.

3. **Review Scan Results:** Analyze the Nessus scan results to identify vulnerabilities in the client machine. Pay special attention to the vulnerabilities related to the deprecated Firefox application. There are several critical vulnerabilites relating to the Firefox application alone that need to be remediated. This can be done by updating or deleting the software as Nessus recommends

![Screenshot 2023-07-07 154315](https://github.com/emeka789/Nessus/assets/99328320/d57002ba-20ad-4d1b-b7e8-bd6361240e5b)

4. **Remediate Vulnerabilities:** Take necessary steps to remediate the vulnerabilities discovered by Nessus. This includes updating or removing the deprecated Firefox application and applying any necessary patches or fixes.

5. **Retest the Client Machine:** Once the remediation steps are complete, rescan the client machine using Nessus to verify that the vulnerabilities have been successfully mitigated. 
![Screenshot 2023-07-07 154738](https://github.com/emeka789/Nessus/assets/99328320/c1d39f6b-ddd8-4d53-ac4c-3b48115ef0c5)


## Conclusion

By following the steps outlined in this post, you can gain hands-on experience in identifying vulnerabilities, implementing remediation measures, and verifying the effectiveness of your security efforts. Regularly scanning for vulnerabilities and retesting your systems will help you maintain a strong security posture and aid in protecting your valuable assets.
