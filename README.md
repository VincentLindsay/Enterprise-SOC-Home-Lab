# Enterprise SOC HomeLab
This repository features a virtualized enterprise SOC environment built to simulate real‑world security monitoring and analysis. The lab includes an Active Directory domain with several workstations, and a dedicated Ubuntu Server hosting the Elastic Stack for the SIEM. Additionally, a separate Zeek sensor will be used to monitor network‑level visibility, and a pfSense firewall will handle segmentation and logging. An Ubuntu Desktop workstation is used to access Kibana dashboards, investigate alerts, and perform Tier 1 SOC analyst workflows. Moreover, a Kali Linux machine will also be used to conduct simulated attacks on our environment to generate telemetry, and even stop the attacks.

# Table of contents
- [Developing virtual environment](https://github.com/VincentLindsay/Enterprise-SOC-Home-Lab/blob/main/Developing%20virtual%20environment/README.md)
- [Creating active directory domain]
- [Creating pfSense Firewall]
- [Developing Zeek Sensor]
- [Making attacker VM](https://github.com/VincentLindsay/Enterprise-SOC-Home-Lab/tree/main/Making%20attacker%20VM)
