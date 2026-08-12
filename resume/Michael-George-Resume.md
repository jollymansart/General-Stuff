# Michael George

Columbus, Ohio Metro · mdg.mike.george@gmail.com · [PHONE] · linkedin.com/in/michael-george-02866411

---

## Summary

Seventeen years in enterprise infrastructure, most of it as the person accountable when
something breaks at 2 a.m. I've worked both sides of the job — IT Director with budget,
vendor, and staff ownership, and hands-on engineer through voice, virtualization, and WAN
migrations. Today I run identity, virtualization, storage, and network for a national
manufacturer: 500+ Windows and Linux servers across VMware, Hyper-V, and Nutanix, three
hyper-converged platforms, five storage arrays, and a WAN I converted from MPLS to SD-WAN.
I use AI tooling daily for scripting and design work, and I read everything it produces
before it goes anywhere.

---

## How I Work With AI

- **In regular use:** Claude, ChatGPT, Gemini, and Google AI Studio.
- **What I use them for:** writing and refining PowerShell, working through error output
  faster than I would alone, and pressure-testing a design before I start building it.
- **What it's changed:** automation that kept losing to higher-priority work now gets
  finished — certificate renewal, Azure tasks, and a printer and hardware inventory that
  had been collected by hand for years.
- **Where I don't:** nothing reaches production until I've read every line and tested it,
  and company or user data stays out of any tool that isn't sanctioned.

---

## Experience

### System Network Administrator — Overhead Door Corporation
*Columbus, OH · Mar 2019 – Present*

- Primary administrator for Active Directory, Microsoft 365, and Azure, where I also build
  and run virtual machines alongside the on-premises estate.
- Manage **500+ Windows and Linux virtual servers** across multiple physical sites on VMware
  vCenter, Hyper-V with SCVMM, and Nutanix.
- **Led the migration from VMware to Hyper-V**, moving production workloads without
  interrupting the business.
- Built hyper-converged Hyper-V hosts on Storage Spaces Direct and run VMware vSAN alongside
  them, with failover clustering behind the high-availability workloads.
- **Converted the WAN from MPLS to SD-WAN**, running FortiGate over Cisco infrastructure and
  replacing fixed carrier circuits with a design that routes around failures on its own.
- Manage the F5 BIG-IP application delivery controller.
- Own the external storage estate across five platforms — Nimble, NetApp, EMC, Compellent,
  and Isilon.
- Own AD domain infrastructure end to end — sites and services, replication topology, OU
  structure, GPO design, LDAPS, and DFS.
- Run internal and external DNS and DHCP, plus all inbound and outbound SMTP mail routing.
- Deployed Windows Event Forwarding for centralized event collection and built account
  lockout analytics, which made a recurring support burden diagnosable at the source instead
  of one reset ticket at a time.
- Automated certificate issuance and renewal across three platforms — Windows and Active
  Directory, F5 BIG-IP, and Oracle Cloud Infrastructure — closing off the expiry outages that
  come with tracking certificates by hand.
- Automated server and printer deployment in PowerShell, standardized day-to-day server
  management on Windows Admin Center, and replaced a hardware inventory that had previously
  been collected by hand.
- Administer SQL Server; provide second-line support for the Citrix XenApp farm and VDI.
- Third-level escalation point for users; after-hours on-call on a six-week rotation.
- Implement changes under formal change control, and write the documentation the team
  actually opens during an incident — network diagrams, process flows, backup and recovery
  procedures.

### Skype for Business / Teams Voice Engineer — Smart Shared Services
*May 2018 – Apr 2019*

- Migrated enterprise voice from Lync to Skype for Business.
- Configured Sonus session border controllers for SIP trunking.
- Automated provisioning and policy enforcement in PowerShell, replacing per-user manual
  configuration.
- Ran telephony readiness assessments and utilization trending, so capacity was designed
  ahead of demand instead of after complaints.
- Translated business requirements into voice and network designs, and handed clients the
  operational documentation to run them.

### IT Director / System Administrator — Village Communities
*Westerville, OH · Jul 2011 – Aug 2017*

- Ran IT for the organization — infrastructure, budget, vendor contracts, and services for
  150–250 employees and roughly 500 network accounts with heavy turnover.
- Operated a centralized ISP service for other tenants in the buildings, which made IT a
  **revenue line rather than only a cost center**.
- Led the JD Edwards EnterpriseOne conversion from 8.11 to 9.1 with the CFO, and carried the
  CNC work throughout: package builds, OCM mappings, OMW object promotions, ESUs and tools
  releases, environment creation and refresh, Server Manager administration, and E1 security.
- Consolidated physical servers onto Hyper-V, cutting hardware count substantially, and added
  a Nimble SAN for VM storage and site-to-site backup.
- Re-architected the network into segmented layers, which killed the broadcast storms and put
  management traffic on separate paths from end users.
- Upgraded a multi-domain environment across Windows 2000 → 2003 → 2012, and restructured
  Exchange users by department and company.
- Designed and ran multi-site WAN routing on Cisco hardware using OSPF, EIGRP, and RIP.
- Deployed Peplink SpeedFusion bonded VPN across sites, aggregating circuits for failover and
  throughput — an SD-WAN approach before the term was in common use.
- Diagnosed and fixed the data traffic that had been degrading VOIP call quality.
- Migrated the phone system from Inter-Tel to Avaya.
- Built Crystal Reports for the business and migrated the club SQL database to a new vendor.
- Administered PeopleSoft and Yardi operations, SQL Server, and the backup estate.

### Systems Administrator — ADiO Pharmacy
*Oct 2009 – Jul 2011*

- Managed Exchange across multiple domains, plus SharePoint, web, terminal, and domain servers.
- Handled VPN, wireless, NAS storage, and SonicWall firewall administration with remote
  management, including mobile device management and tracking.
- Scripted routine administration in VBScript and PowerShell.
- Built reporting against the Rx30 and Prodigy pharmacy systems, and worked directly with
  pharmacy managers and CSRs to improve day-to-day operations.
- Deployed VMware Server and document management; installed Unix servers inside Windows 2003
  and 2008 domains with failover clustering, and owned their backups.
- Worked with senior management on IT budgets, policy, and the resourcing needed for growth.

### Earlier

**Network Administrator**, Peer Assist (Jan – Oct 2009) — network and security administration,
VOIP management, cabling, and SQL databases behind in-house and document management applications.

**Customer Service Representative**, Definitive Homecare Solutions (Oct 2007 – Nov 2008) —
supported the CPR+ client-server application and built SQL reports against its data model.

---

## Technical Skills

- **Identity & Directory:** Active Directory, Entra/Azure AD, GPO, LDAPS, DFS, DNS, DHCP,
  SMTP, certificate management
- **Cloud & Productivity:** Azure IaaS, Oracle Cloud Infrastructure (OCI), Microsoft 365,
  Exchange, SharePoint, Teams
- **Virtualization & HCI:** VMware vCenter/ESXi/vSAN, Hyper-V, SCVMM, Storage Spaces Direct,
  Nutanix, failover clustering, Windows Admin Center, Citrix XenApp, VDI
- **Storage:** Nimble, NetApp, EMC, Compellent, Isilon
- **Monitoring & Operations:** Windows Event Forwarding, account lockout analytics,
  System Center (Operations Manager, Data Protection Manager, Service Manager)
- **Operating Systems:** Windows Server (2000 through current), Linux, Unix
- **Networking:** Cisco, FortiGate, Peplink SpeedFusion, SD-WAN, MPLS, F5 BIG-IP, OSPF,
  EIGRP, RIP, VLAN segmentation, spanning tree, VPN, WAN, subnetting
- **Voice:** Skype for Business, Teams Voice, Sonus SBC, SIP, H.323, Avaya, VOIP QoS
- **Automation & AI:** PowerShell, VBScript; Claude, ChatGPT, Gemini, Google AI Studio
- **Business Systems:** JD Edwards EnterpriseOne (CNC), SQL Server, Yardi, PeopleSoft,
  Crystal Reports
- **Management:** budget ownership, vendor contracts, change control, project planning,
  technical documentation

---

## Education

Columbus State Community College — [PROGRAM / DEGREE, YEAR]
