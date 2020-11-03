## SRE Dashboard for Full Stack Backend Services Only

This dashboard provides SRE Teams, Application Owners, etc... an end to end summary view into the current status of the backend services, databases and infrastructure.  

Focus areas: 

- Health Status: Problems, Service, Database & Host 
- Four golden signals of monitoring: Latency, Traffic, Errors, and Saturation
- Drilldown links for quick analysis (Service, Database, Process & Host) are included

![SRE Dashboard](SRE_Services_WFS.png)

# Prerequisites Highlights

- Management zone created for target application/service backend which includes services,  databases,  processes & hosts.

# Notes

- Targeted for appplication backend services observability where no real user monitoring is enabled or possible
- Latency metrics set to median
- Service & Database requests metrics as shown as per second
