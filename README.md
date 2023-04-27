# ICSZeroTrustAudit
ICSZeroTrustAudit: a python ICS security audit based on zero trust principles

-The purpose of this script is to perform a security audit on a target Industrial Control System (ICS). The script includes multiple tests and checks, such as vulnerability scanning, network traffic analysis, credential checking, firewall and Intrusion Detection System (IDS) testing, and ICS-specific protocol testing (Modbus, DNP3, and IEC 60870-5-104). Additionally, it performs a compliance check based on Zero Trust principles.
-The script uses a configuration file (config.ini) to read the necessary settings and command-line arguments for flexibility. It also logs the results and any errors encountered during the execution of the script.

You will need to modify the hardcoded values within the code and include certain aspects to suit your use case.

The script makes use of a multitude of requests to test ICS standards, compliance checks, etc. This script attempts to automate at least 75 percent of an ICS security audit based on zero trust principles. 

The script uses openvas vulnerability scanner, snort, and more.

The included config.ini file has been boilerplate designed to be quickly edited to include the required credentials and information to smoothly run the script. The configuration file includes sections for OpenVAS credentials, target IP and network traffic timeout, default or weak credentials to test, and logging settings.

Developed by @abtzpro @AdamR @HelloSecurity

End Goal: an open source, publicly available, automated ICS Security Audit script to ease the workload of security technicians and save money where possible.
