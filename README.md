### How it works
Follow the step-by-step instructions to setup the application, connecting to a SQL Database hosted in Azure.  This provides a Web Application for configuration, and a Windows Service for automated data collection for the tools and projects that you choose.  At a specified frequency, the Service will collect the data from those tools, and store it to your database (no need for additional gateways or connectivity configuration).  Then download a template to build PowerBI Dashboards, preconfigured with queries for each supported tool (in the future, we intend to provide preconfigured Dashboards).

---

### Setup Procedures
- <a href="mailto:admin@hiveapps.io?subject=HivePro: Evaluation Request&body=Please sent me a link to download the HivePro Installer.">Download the Installer</a>
- [Procure a SQL Server Database](SQL-Server-Setup)
- [Install the Web Application and Windows Service](Install.md)
- [Configure a Project](Install.md#add-a-project)
- [Publish PowerBI Dashboard](Publish-PowerBI-Dashboard.md)

---

### Supported Integrations
- GitHub (On-Prem or github.com)
- JIRA (On-Prem or JIRA Cloud)
- PivotalTracker
- TeamCity
- Jenkins
