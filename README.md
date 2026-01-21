# Information-Security-Management
Background to the (Fictitious) Case Study 

InnoVAR is an engineering company, established in 2016, that provides Virtual and Augmented Reality (VR/AR) services to industry (e.g., energy, construction) and government agencies (e.g., Ministry of Defence). The company is headquartered in Aberdeen and has branches in Canada, Germany, Qatar and Singapore. They employ approximately 300 employees in total, 100 in Aberdeen (main office) and the rest evenly split between the other branches. Each branch houses a data centre. 

• Each office building has physical security in place in the form of
 1 Reception desk issuing passes to visitors and contractors (contractors are generally trusted and do not require supervision);
 2 Use of passes to get through optical turnstiles; and
 3 A further optical reader on the data centre door to allow access to employees only. 

• The major data types used or stored at InnoVAR include source code of VR/AR software, engineering diagrams (e.g., digital twin model of oil platform), client contact details and financial data, and company financial data.

• They primarily use Microsoft servers and PCs with some Mac computers used by engineers to perform design work. They use Active Directory and have a web server for their website, ten servers housing their VR/AR applications, eight Microsoft SQL database servers 2022, and a Microsoft Exchange server 2019 for email. They have their own internal cloud architecture for file sharing across the company using a combination of legacy SharePoint and shared folders.
 1 There are 24 virtualized Windows Server 2022 servers in the main office on eight physical server blades.
 2 System updates and patches are pushed from the main office using Windows Server Update Services (WSUS). Most servers and clients get Microsoft updates once a month, but some are missed. Also, most third-party products (for example, Adobe PDF, Java, AutoCAD, and web browsers) are not kept up to date.
 3 Each satellite office has their own virtualized servers for storing files, printing, and running local applications.
 4 Each office has its own decentralized wireless network connected to the production network. Default SSID is used with a common password of Spartans2018.
 5 Each employee has a desktop or laptop PC running Windows 10. HR personnel have laptops for conducting interviews.

• They outsource their email spam filter and all HR applications to two separate third-party companies.

• The network at each location sits behind a gateway router and firewall (Cisco ASA 5525).

• Trend Micro Antivirus is in use but is not automatically updated across the company since many employees work remotely.

• Employees often work remotely and use the DUO multifactor authenticator app to gain access to the corporate systems through a company VPN (Cisco AnyConnect v4.6.). Once connected through the VPN, many engineering employees will RDP to Windows desktops and servers to access their applications and files.

• Remote employees have local administrator capabilities and often store files on their local PCs. Many will back up their own data on their own USB drives.

• The InnoVAR Accounting team is spread across each location to provide local support for clients. The accounting application they use is KPMG Spark.

• A password policy is in place requiring at least eight characters with complexity. Employees need to change their passwords at least once every 90 days.

• InnoVAR director of IT, has a full-time staff of 10 employees, one of whom does security duties part time. There is at least one IT staff member at each location.

• Recently, a few laptops and office equipment were stolen from the office.

• Two employees (an HR manager and an architect) in the Canada office were victims of CryptoLocker ransomware.

• It is at the data owner’s discretion as to whether to secure their data files or folders. Many do not secure their files because there are many other employees who often need to work with the files. 

• Two employees recently left the company and went to InnoVAR’s biggest competitor, where they just landed a contract with one of their main clients.

• On-site staff at each location provides IT support part time along with their other responsibilities. Password resets are done by giving out a generic password of InnoVAR2020.

• The company’s IT policies were written in 2016. There have been many attempts to update them, but it is not seen as a priority. Each new employee needs to sign an acceptable user agreement upon hire and go through a 30-minute security awareness presentation. 

• The last audit of system accounts was in 2020. It was found that 10 prior employees still had access to internal networks and applications.

• Vulnerability scanning is conducted monthly by a third-party company (IT Works), based in London, which has a 24x7x365 security operation centre (SOC) to monitor and alert on anomalies and potential threats or vulnerabilities. The Security Information and Event Management (SIEM) application will send high-risk alerts to the IT director’s email. The SIEM was initially put in place in 2022, but it has not been updated with new rules since.

• The InnoVAR incident response plan was written in 2020 and updated in 2022. It contains contact information for now-terminated employees. There is no specific response or recovery tests nor training, as IT says they rely on the third-party company (IT Works). The recovery plan is failover to one of the other sites.

InnoVAR have been told by the UK’s Ministry of Defence that, to bid for future contracts, they must prove a minimum of cyber hygiene by obtaining Cyber Essentials certification as well as aligning their security program to a recognised standard such as ISO/IEC 27001 or NIST CSF. InnoVAR have hired you as a consultant to help them undertake the following tasks and report back to the director of IT.
 
Task(s) 

Task 1: 
An analysis of risks, facing the company, summarised in the report and detailed in a risk register (Excel File).

Task 2: 
A gap analysis of the company’s current security practices against one of the following:
(i) ISO/IEC 27001:2022 or  
(ii) NIST CSF (v2).  

The gap analysis should be summarised in the report and fully detailed in the Excel File using ISO 27001 – Annex A or NIST CSF template provided

Task 3: 
A security programme that addresses the risks and gaps identified in Task 1 and Task 2, and that provides a roadmap to a better security hygiene and compliance with the above standards. The security program should be summarised in the report and fully detailed in an Excel spreadsheet, It should outline a 1-year plan, with clear tasks, dates or frequency, metrics, etc.

Task 4:
A detailed report summarising all tasks.
