# vra-reporting-networkres
The Reservation Network Capacity Report workflow gathers information regarding each network profile defined in one or more vRealize Automation instances, then logs the data (e.g., remaining number of unallocated IPs, linked reservations, whether those reservations are enabled).

Optionally, sends an email with the data.

Installation:
1) Download com.vmware.pso.vra.reporting.networkres.package
2) In the vRealize Orchestrator client, import the package

Execution:
1) In the vRealize Orchestrator client, run the Reservation Network Capacity Report workflow
