# ICSZeroTrustAudit
ICSZeroTrustAudit: a python ICS security audit based on zero trust principles

-The purpose of this script is to perform a security audit on a target Industrial Control System (ICS). The script includes multiple tests and checks, such as vulnerability scanning, network traffic analysis, credential checking, firewall and Intrusion Detection System (IDS) testing, and ICS-specific protocol testing (Modbus, DNP3, and IEC 60870-5-104). Additionally, it performs a compliance check based on Zero Trust principles.

-The script uses a configuration file (config.ini) to read the necessary settings and command-line arguments for flexibility. It also logs the results and any errors encountered during the execution of the script.

-The included config.ini file has been boilerplate designed to be quickly edited to include the required credentials and information to smoothly run the script. The configuration file includes sections for OpenVAS credentials, target IP and network traffic timeout, default or weak credentials to test, and logging settings.

-The script is easily modified to suit an individual use case or as a general ICS audit baseline to automate what can be automated.

The command line arguments for the script are:

-t or --target: Target IP address - Specifies the IP address of the target ICS system to perform the security audit on. The default value is taken from the config.ini file.
-nt or --network_traffic_timeout: Duration for network traffic analysis in seconds - Specifies the duration, in seconds, for which the script will analyze the network traffic during the audit. The default value is taken from the config.ini file.

To run the script with command line arguments, use the following syntax:

python ICSZeroTrustAudit.py -t TARGET_IP -nt NETWORK_TRAFFIC_TIMEOUT

Replace  TARGET_IP with the target IP address, and NETWORK_TRAFFIC_TIMEOUT with the desired duration for network traffic analysis.


Developed by @abtzpro @AdamR @HelloSecurity

End Goal: an open source, publicly available, automated ICS Security Audit script to ease the workload of security technicians and save money where possible.
