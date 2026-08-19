![Banner](dorking.png)

# 🕵️ Advanced Google Dork Archive

[![Total Dorks](https://img.shields.io/badge/Total%20Dorks-1100+%2B-red?style=for-the-badge&logo=google)](https://github.com)
[![Categories](https://img.shields.io/badge/Categories-35-blue?style=for-the-badge&logo=bookmarks)](https://github.com)
[![Purpose](https://img.shields.io/badge/Purpose-OSINT%20%26%20Security%20Research-orange?style=for-the-badge&logo=shield)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=opensourceinitiative)](https://github.com)
[![Developer](https://img.shields.io/badge/Developer-tc4dy-purple?style=for-the-badge&logo=github)](https://github.com/tc4dy)

---

## 📖 What Are Google Dorks?

**Google Dorking** (also known as Google Hacking) is the practice of using advanced Google Search operators to find specific information that is not easily accessible through a standard search. These operators allow you to filter and narrow results by file type, URL structure, page title, specific text content, and more.

### 🔍 Core Operators

| Operator | Description | Example |
|---|---|---|
| `site:` | Limit results to a specific domain | `site:gov.uk` |
| `inurl:` | Search within URLs | `inurl:admin` |
| `intitle:` | Search within page titles | `intitle:login` |
| `intext:` | Search within page body text | `intext:password` |
| `filetype:` | Filter by file extension | `filetype:pdf` |
| `cache:` | View Google's cached version | `cache:example.com` |
| `related:` | Find related websites | `related:amazon.com` |
| `"quotes"` | Exact phrase match | `"admin password"` |
| `-` | Exclude a term | `-site:youtube.com` |
| `OR` | Match either term | `filetype:xls OR filetype:xlsx` |
| `*` | Wildcard | `"password *"` |

---

## 🧠 Why Google Dorks Matter for OSINT

Open Source Intelligence (OSINT) is the collection and analysis of data gathered from public sources. Google Dorks are one of the most **powerful and accessible OSINT tools** available because:

- **Zero cost** — no special tools or subscriptions required
- **Massive index** — Google indexes billions of pages, including accidentally exposed content
- **Granular targeting** — combine operators to pinpoint exact information
- **Reconnaissance** — essential first step in any security assessment or investigation
- **Exposure discovery** — find your own organization's unintentionally public data
- **Journalism & research** — locate public records, leaked documents, statistics
- **Threat intelligence** — identify misconfigured servers, exposed credentials, vulnerable systems

> ⚠️ **The same techniques used by security researchers are used by malicious actors.** Understanding them is essential for defense. This archive exists so defenders know what to look for.

---

## 📊 Archive Statistics

| Metric | Value |
|---|---|
| 📁 Total Dorks | **1.100+** |
| 🗂️ Categories | **35** |
| 🔧 Operators Covered | **15+** |

---

## 🗺️ Category Index

> Click any category badge to jump directly to that section.

### 📄 Documents & Files
[📄 PDF Documents](#-pdf-documents) · [📊 Excel & Spreadsheets](#-excel--spreadsheets) · [📝 Word Documents](#-word-documents) · [📋 Text & Config Files](#-text--config-files) · [🗜️ Archive & Backup Files](#️-archive--backup-files)

### 🔐 Credentials & Secrets
[🔑 Passwords & Credentials](#-passwords--credentials) · [🗝️ API Keys & Tokens](#️-api-keys--tokens) · [⚙️ Config & Environment Files](#️-config--environment-files) · [🔒 SSH & Certificates](#-ssh--certificates)

### 🖥️ Servers & Panels
[🛡️ Admin Panels](#️-admin-panels) · [🔐 Login Pages](#-login-pages) · [🗄️ Database Panels](#️-database-panels) · [🖥️ cPanel & Hosting](#️-cpanel--hosting) · [📂 Open Directories](#-open-directories)

### 🌐 Network & Infrastructure
[📡 Routers & Network Devices](#-routers--network-devices) · [📷 IP Cameras & IoT](#-ip-cameras--iot) · [🏭 SCADA & Industrial](#-scada--industrial) · [🔗 VPN & Proxy](#-vpn--proxy)

### 🗃️ Databases & Logs
[🗃️ Database Files](#️-database-files) · [📋 Log Files](#-log-files) · [🔍 Database Errors](#-database-errors)

### 👁️ OSINT & Reconnaissance
[👤 People & Profiles](#-people--profiles) · [📱 Social Media](#-social-media) · [🏢 Corporate Intelligence](#-corporate-intelligence) · [📍 Geolocation & Maps](#-geolocation--maps)

### 💻 Development & Code
[💻 Code & Repositories](#-code--repositories) · [🐛 Debug & Developer Tools](#-debug--developer-tools) · [🔌 API Endpoints](#-api-endpoints) · [☁️ Cloud & Storage](#️-cloud--storage)

### 🏦 Finance & Legal
[💳 Financial Documents](#-financial-documents) · [⚖️ Legal & Contracts](#️-legal--contracts)

### 🏥 Domain-Specific
[🏥 Healthcare & Medical](#-healthcare--medical) · [🎓 Education & Academic](#-education--academic) · [📰 News & Media](#-news--media) · [🛒 E-Commerce](#-e-commerce)

### 🔒 Security Research
[🛡️ Vulnerability & Security](#️-vulnerability--security) · [🔎 CMS & Frameworks](#-cms--frameworks)

---

## 📄 PDF Documents

> Find publicly exposed PDF files across the web — reports, manuals, contracts, and more.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:pdf` | `filetype:pdf site:gov.uk` | All PDF files |
| `filetype:pdf intext:confidential` | `filetype:pdf intext:confidential site:gov` | Confidential PDFs |
| `filetype:pdf intext:secret` | `filetype:pdf intext:secret` | PDFs with "secret" |
| `filetype:pdf intext:"internal use only"` | `filetype:pdf intext:"internal use only" site:edu` | Internal-only docs |
| `filetype:pdf intext:classified` | `filetype:pdf intext:classified site:mil` | Classified documents |
| `filetype:pdf intext:budget` | `filetype:pdf intext:budget 2024` | Budget reports |
| `filetype:pdf intext:salary` | `filetype:pdf intext:salary schedule site:gov` | Salary documents |
| `filetype:pdf intext:contract` | `filetype:pdf intext:contract agreement` | Contract PDFs |
| `filetype:pdf intext:invoice` | `filetype:pdf intext:invoice total` | Invoice documents |
| `filetype:pdf intext:report` | `filetype:pdf intext:"annual report"` | Annual reports |
| `filetype:pdf intext:thesis` | `filetype:pdf intext:thesis site:edu` | Academic theses |
| `filetype:pdf intext:dissertation` | `filetype:pdf intext:dissertation 2024` | Dissertations |
| `filetype:pdf intext:"research paper"` | `filetype:pdf intext:"research paper"` | Research papers |
| `filetype:pdf intext:"white paper"` | `filetype:pdf intext:"white paper" security` | White papers |
| `filetype:pdf intext:manual` | `filetype:pdf intext:manual technical` | Technical manuals |
| `filetype:pdf intext:procedure` | `filetype:pdf intext:procedure operations` | Procedure docs |
| `filetype:pdf intext:policy` | `filetype:pdf intext:policy security` | Policy documents |
| `filetype:pdf intext:audit` | `filetype:pdf intext:audit report site:gov` | Audit reports |
| `filetype:pdf intext:"meeting minutes"` | `filetype:pdf intext:"meeting minutes"` | Meeting minutes |
| `filetype:pdf intext:"financial statement"` | `filetype:pdf intext:"financial statement" 2024` | Financial statements |
| `filetype:pdf intext:"board of directors"` | `filetype:pdf intext:"board of directors" meeting` | Board meeting docs |
| `filetype:pdf intext:proposal` | `filetype:pdf intext:proposal business` | Business proposals |
| `filetype:pdf intext:"project plan"` | `filetype:pdf intext:"project plan"` | Project plans |
| `filetype:pdf intext:curriculum` | `filetype:pdf intext:curriculum vitae` | CVs/Resumes |
| `filetype:pdf intext:resume` | `filetype:pdf intext:resume email phone` | Resumes with contacts |
| `filetype:pdf intext:passport` | `filetype:pdf intext:passport number` | Passport info leaks |
| `filetype:pdf intext:"social security"` | `filetype:pdf intext:"social security number"` | SSN documents |
| `filetype:pdf intext:"date of birth"` | `filetype:pdf intext:"date of birth"` | DOB-containing PDFs |
| `filetype:pdf intext:username` | `filetype:pdf intext:username password` | PDFs with credentials |
| `filetype:pdf intext:"user list"` | `filetype:pdf intext:"user list"` | User listing PDFs |
| `filetype:pdf intext:"employee"` | `filetype:pdf intext:"employee list"` | Employee documents |
| `filetype:pdf intext:"price list"` | `filetype:pdf intext:"price list"` | Price lists |
| `filetype:pdf intext:nda` | `filetype:pdf intext:nda "non-disclosure"` | NDA documents |
| `filetype:pdf intext:"terms and conditions"` | `filetype:pdf intext:"terms and conditions"` | Legal terms |
| `filetype:pdf intext:memorandum` | `filetype:pdf intext:memorandum` | Memorandums |
| `filetype:pdf intext:specification` | `filetype:pdf intext:specification technical` | Technical specs |
| `filetype:pdf intext:"system requirements"` | `filetype:pdf intext:"system requirements"` | System requirement docs |
| `filetype:pdf intext:"network diagram"` | `filetype:pdf intext:"network diagram"` | Network diagrams |
| `filetype:pdf intext:"architecture document"` | `filetype:pdf intext:"architecture document"` | Architecture docs |
| `filetype:pdf intext:"security policy"` | `filetype:pdf intext:"security policy"` | Security policies |
| `filetype:pdf intext:"incident report"` | `filetype:pdf intext:"incident report"` | Incident reports |
| `filetype:pdf intext:"risk assessment"` | `filetype:pdf intext:"risk assessment"` | Risk assessment docs |
| `filetype:pdf intext:"vulnerability assessment"` | `filetype:pdf intext:"vulnerability assessment"` | Vulnerability reports |
| `filetype:pdf intext:"penetration test"` | `filetype:pdf intext:"penetration test"` | Pentest reports |
| `filetype:pdf intext:roadmap` | `filetype:pdf intext:roadmap product` | Product roadmaps |
| `filetype:pdf intext:"strategic plan"` | `filetype:pdf intext:"strategic plan"` | Strategic plans |
| `filetype:pdf intext:inventory` | `filetype:pdf intext:inventory list` | Inventory lists |
| `filetype:pdf intext:"purchase order"` | `filetype:pdf intext:"purchase order"` | Purchase orders |
| `filetype:pdf intext:warranty` | `filetype:pdf intext:warranty certificate` | Warranty documents |
| `filetype:pdf intext:certificate` | `filetype:pdf intext:certificate` | Certificate files |
| `filetype:pdf site:edu` | `filetype:pdf site:edu "student"` | Edu site PDFs |
| `filetype:pdf site:gov` | `filetype:pdf site:gov "classified"` | Gov PDFs |
| `filetype:pdf site:mil` | `filetype:pdf site:mil` | Military PDFs |
| `filetype:pdf intext:"access denied"` | `filetype:pdf intext:"access denied"` | Access control PDFs |
| `filetype:pdf intext:"ip address"` | `filetype:pdf intext:"ip address" network` | Network info PDFs |
| `filetype:pdf intext:firewall` | `filetype:pdf intext:firewall configuration` | Firewall config docs |
| `filetype:pdf intext:"vpn"` | `filetype:pdf intext:"vpn configuration"` | VPN config docs |
| `filetype:pdf intext:"backup"` | `filetype:pdf intext:"backup procedure"` | Backup procedure docs |
| `filetype:pdf intext:"disaster recovery"` | `filetype:pdf intext:"disaster recovery plan"` | DR plans |
| `filetype:pdf intext:"incident response"` | `filetype:pdf intext:"incident response plan"` | IR plans |
| `filetype:pdf intext:"business continuity"` | `filetype:pdf intext:"business continuity"` | BCP documents |
| `filetype:pdf intext:"privacy policy"` | `filetype:pdf intext:"privacy policy" GDPR` | GDPR privacy policies |
| `filetype:pdf intext:GDPR` | `filetype:pdf intext:GDPR compliance` | GDPR compliance docs |
| `filetype:pdf intext:"data breach"` | `filetype:pdf intext:"data breach" notification` | Breach notifications |
| `filetype:pdf intext:"access control"` | `filetype:pdf intext:"access control list"` | ACL documents |
| `filetype:pdf intext:"change management"` | `filetype:pdf intext:"change management"` | Change management docs |
| `filetype:pdf intext:"patch management"` | `filetype:pdf intext:"patch management"` | Patch management |
| `filetype:pdf intext:"software license"` | `filetype:pdf intext:"software license"` | License documents |
| `filetype:pdf intext:topology` | `filetype:pdf intext:topology network` | Network topology |
| `filetype:pdf intext:"physical security"` | `filetype:pdf intext:"physical security"` | Physical security docs |
| `filetype:pdf "index of"` | `filetype:pdf "index of" site:edu` | PDF index pages |

---

## 📊 Excel & Spreadsheets

> Discover exposed spreadsheets containing databases, financials, and user data.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:xls` | `filetype:xls site:example.com` | All XLS files |
| `filetype:xlsx` | `filetype:xlsx budget` | All XLSX files |
| `filetype:csv` | `filetype:csv database` | CSV data files |
| `filetype:xls intext:salary` | `filetype:xls intext:salary 2024` | Salary spreadsheets |
| `filetype:xlsx intext:salary` | `filetype:xlsx intext:salary` | Salary XLSX files |
| `filetype:xls intext:password` | `filetype:xls intext:password username` | Credential sheets |
| `filetype:xlsx intext:password` | `filetype:xlsx intext:password` | XLSX password files |
| `filetype:xls intext:customer` | `filetype:xls intext:customer database` | Customer lists |
| `filetype:xlsx intext:customer` | `filetype:xlsx intext:customer email phone` | Customer XLSX |
| `filetype:xls intext:email` | `filetype:xls intext:email list` | Email lists |
| `filetype:csv intext:email` | `filetype:csv intext:email password` | CSV with emails |
| `filetype:xls intext:financial` | `filetype:xls intext:financial statement` | Financial sheets |
| `filetype:xlsx intext:budget` | `filetype:xlsx intext:budget annual` | Budget sheets |
| `filetype:xls intext:inventory` | `filetype:xls intext:inventory` | Inventory lists |
| `filetype:xlsx intext:inventory` | `filetype:xlsx intext:inventory stock` | Stock inventories |
| `filetype:xls intext:employee` | `filetype:xls intext:employee list` | Employee sheets |
| `filetype:xlsx intext:employee` | `filetype:xlsx intext:employee HR` | HR spreadsheets |
| `filetype:xls intext:payroll` | `filetype:xls intext:payroll` | Payroll sheets |
| `filetype:xlsx intext:payroll` | `filetype:xlsx intext:payroll 2024` | Payroll XLSX |
| `filetype:xls intext:credit card` | `filetype:xls intext:"credit card"` | Credit card data |
| `filetype:xls intext:SSN` | `filetype:xls intext:SSN OR "social security"` | SSN spreadsheets |
| `filetype:xls intext:phone` | `filetype:xls intext:phone number` | Phone directories |
| `filetype:csv intext:phone` | `filetype:csv intext:phone` | CSV phone lists |
| `filetype:xls intext:username` | `filetype:xls intext:username password` | Username sheets |
| `filetype:xlsx intext:username` | `filetype:xlsx intext:username` | XLSX credential files |
| `filetype:xls intext:account` | `filetype:xls intext:account number` | Account data |
| `filetype:xls intext:"bank account"` | `filetype:xls intext:"bank account"` | Bank account data |
| `filetype:xlsx intext:statistics` | `filetype:xlsx intext:statistics` | Statistical sheets |
| `filetype:xls intext:report` | `filetype:xls intext:report` | Report sheets |
| `filetype:xlsx intext:report` | `filetype:xlsx intext:report monthly` | Monthly reports |
| `filetype:csv intext:password` | `filetype:csv intext:password` | CSV passwords |
| `filetype:xls intext:address` | `filetype:xls intext:address city state` | Address databases |
| `filetype:csv intext:address` | `filetype:csv intext:address` | CSV address lists |
| `filetype:xls intext:invoice` | `filetype:xls intext:invoice total` | Invoice sheets |
| `filetype:xlsx intext:invoice` | `filetype:xlsx intext:invoice` | Invoice XLSX |
| `filetype:xls intext:product` | `filetype:xls intext:product price` | Product pricing |
| `filetype:xlsx intext:price` | `filetype:xlsx intext:price list` | Price lists |
| `filetype:xls intext:student` | `filetype:xls intext:student grade` | Student grade sheets |
| `filetype:xlsx intext:grade` | `filetype:xlsx intext:grade student` | Grade books |
| `filetype:xls intext:subscription` | `filetype:xls intext:subscription` | Subscription lists |
| `filetype:xlsx intext:user` | `filetype:xlsx intext:user list` | User lists |
| `filetype:csv intext:user` | `filetype:csv intext:user id email` | CSV user databases |
| `filetype:xls intext:login` | `filetype:xls intext:login` | Login data sheets |
| `filetype:xlsx intext:access` | `filetype:xlsx intext:access control` | Access control sheets |
| `filetype:xls intext:server` | `filetype:xls intext:server ip address` | Server listings |
| `filetype:xlsx intext:network` | `filetype:xlsx intext:network topology` | Network docs |
| `filetype:csv intext:ip` | `filetype:csv intext:ip address` | IP address lists |
| `filetype:xls intext:api` | `filetype:xls intext:api key` | API key sheets |
| `filetype:xls site:gov` | `filetype:xls site:gov` | Government spreadsheets |
| `filetype:csv site:edu` | `filetype:csv site:edu` | Education CSV files |
| `filetype:xlsx intext:secret` | `filetype:xlsx intext:secret` | Sheets with secrets |

---

## 📝 Word Documents

> Locate exposed Word documents — memos, policies, contracts, internal reports.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:doc` | `filetype:doc` | All DOC files |
| `filetype:docx` | `filetype:docx` | All DOCX files |
| `filetype:doc intext:confidential` | `filetype:doc intext:confidential` | Confidential docs |
| `filetype:docx intext:confidential` | `filetype:docx intext:confidential site:gov` | Confidential DOCX |
| `filetype:doc intext:memo` | `filetype:doc intext:memo` | Internal memos |
| `filetype:docx intext:memo` | `filetype:docx intext:memo` | DOCX memos |
| `filetype:doc intext:password` | `filetype:doc intext:password` | Docs with passwords |
| `filetype:docx intext:password` | `filetype:docx intext:password` | DOCX with passwords |
| `filetype:doc intext:resume` | `filetype:doc intext:resume` | Resume docs |
| `filetype:docx intext:resume` | `filetype:docx intext:resume` | DOCX resumes |
| `filetype:doc intext:meeting` | `filetype:doc intext:meeting minutes` | Meeting minutes |
| `filetype:docx intext:meeting` | `filetype:docx intext:meeting` | DOCX meeting notes |
| `filetype:doc intext:policy` | `filetype:doc intext:policy` | Policy documents |
| `filetype:docx intext:policy` | `filetype:docx intext:policy` | DOCX policies |
| `filetype:doc intext:procedure` | `filetype:doc intext:procedure` | Procedure docs |
| `filetype:docx intext:procedure` | `filetype:docx intext:procedure` | DOCX procedures |
| `filetype:doc intext:nda` | `filetype:doc intext:nda` | NDA agreements |
| `filetype:docx intext:nda` | `filetype:docx intext:nda` | DOCX NDAs |
| `filetype:doc intext:contract` | `filetype:doc intext:contract agreement` | Contract docs |
| `filetype:docx intext:contract` | `filetype:docx intext:contract` | DOCX contracts |
| `filetype:doc intext:proposal` | `filetype:doc intext:proposal` | Proposals |
| `filetype:docx intext:proposal` | `filetype:docx intext:proposal` | DOCX proposals |
| `filetype:doc intext:report` | `filetype:doc intext:report` | Report docs |
| `filetype:docx intext:report` | `filetype:docx intext:report` | DOCX reports |
| `filetype:doc intext:employee` | `filetype:doc intext:employee` | Employee docs |
| `filetype:docx intext:employee` | `filetype:docx intext:employee` | DOCX employee files |
| `filetype:doc intext:salary` | `filetype:doc intext:salary` | Salary documents |
| `filetype:docx intext:salary` | `filetype:docx intext:salary` | DOCX salary docs |
| `filetype:doc intext:audit` | `filetype:doc intext:audit` | Audit documents |
| `filetype:docx intext:security` | `filetype:docx intext:security` | Security documents |
| `filetype:doc intext:"access control"` | `filetype:doc intext:"access control"` | Access control docs |
| `filetype:docx intext:username` | `filetype:docx intext:username` | DOCX with usernames |
| `filetype:doc intext:network` | `filetype:doc intext:network` | Network docs |
| `filetype:docx intext:firewall` | `filetype:docx intext:firewall` | Firewall docs |
| `filetype:doc intext:budget` | `filetype:doc intext:budget` | Budget docs |
| `filetype:docx intext:budget` | `filetype:docx intext:budget` | DOCX budgets |
| `filetype:doc site:gov` | `filetype:doc site:gov` | Government Word docs |
| `filetype:docx site:edu` | `filetype:docx site:edu` | Education DOCX files |
| `filetype:doc intext:"internal"` | `filetype:doc intext:"internal only"` | Internal docs |
| `filetype:docx intext:draft` | `filetype:docx intext:draft` | Draft documents |
| `filetype:doc intext:plan` | `filetype:doc intext:plan project` | Project plans |
| `filetype:docx intext:strategy` | `filetype:docx intext:strategy` | Strategy docs |
| `filetype:doc intext:legal` | `filetype:doc intext:legal` | Legal documents |
| `filetype:docx intext:compliance` | `filetype:docx intext:compliance` | Compliance docs |

---

## 📋 Text & Config Files

> Plain text files that often contain credentials, lists, and configurations.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:txt intext:password` | `filetype:txt intext:password` | TXT with passwords |
| `filetype:txt intext:credentials` | `filetype:txt intext:credentials` | Credential files |
| `filetype:txt intext:username` | `filetype:txt intext:username password` | Username+password TXT |
| `filetype:txt intext:"admin password"` | `filetype:txt intext:"admin password"` | Admin credentials |
| `filetype:txt intext:"root password"` | `filetype:txt intext:"root password"` | Root passwords |
| `filetype:txt intext:"ftp password"` | `filetype:txt intext:"ftp password"` | FTP passwords |
| `filetype:txt intext:"email password"` | `filetype:txt intext:"email password"` | Email passwords |
| `filetype:txt intext:"db password"` | `filetype:txt intext:"db password"` | DB passwords |
| `filetype:txt intext:api_key` | `filetype:txt intext:api_key` | API keys in text |
| `filetype:txt intext:secret_key` | `filetype:txt intext:secret_key` | Secret keys |
| `filetype:txt intext:access_token` | `filetype:txt intext:access_token` | Access tokens |
| `filetype:txt intext:private_key` | `filetype:txt intext:private_key` | Private keys |
| `filetype:txt intext:socks` | `filetype:txt intext:socks` | SOCKS proxy lists |
| `filetype:txt intext:"http proxy"` | `filetype:txt intext:"http proxy"` | HTTP proxy lists |
| `filetype:txt intext:ssh` | `filetype:txt intext:ssh password` | SSH credentials |
| `filetype:txt intext:mysql` | `filetype:txt intext:mysql password` | MySQL credentials |
| `filetype:txt intext:smtp` | `filetype:txt intext:smtp password` | SMTP credentials |
| `filetype:txt intext:hosts` | `filetype:txt intext:hosts` | Hosts files |
| `filetype:txt intext:ip` | `filetype:txt intext:ip address list` | IP address lists |
| `filetype:txt intext:wordlist` | `filetype:txt intext:wordlist` | Password wordlists |
| `filetype:txt intext:hash` | `filetype:txt intext:hash password` | Hash files |
| `filetype:txt intext:credit` | `filetype:txt intext:credit card number` | Credit card TXTs |
| `filetype:txt intext:ssn` | `filetype:txt intext:ssn` | SSN text files |
| `filetype:txt intext:token` | `filetype:txt intext:token bearer` | Token files |
| `filetype:txt intext:exploit` | `filetype:txt intext:exploit` | Exploit notes |
| `filetype:txt intext:CVE` | `filetype:txt intext:CVE-202` | CVE information |
| `filetype:txt intext:"account number"` | `filetype:txt intext:"account number"` | Account numbers |
| `filetype:txt intext:backup` | `filetype:txt intext:backup credentials` | Backup credentials |
| `filetype:txt intext:server` | `filetype:txt intext:server list` | Server lists |
| `filetype:txt intext:admin` | `filetype:txt intext:admin list` | Admin user lists |
| `filetype:ini intext:password` | `filetype:ini intext:password` | INI file passwords |
| `filetype:cfg intext:password` | `filetype:cfg intext:password` | CFG file passwords |
| `filetype:conf intext:password` | `filetype:conf intext:password` | CONF passwords |
| `filetype:inf intext:password` | `filetype:inf intext:password` | INF passwords |
| `filetype:properties intext:password` | `filetype:properties intext:password` | Properties passwords |
| `filetype:xml intext:password` | `filetype:xml intext:password` | XML passwords |
| `filetype:yaml intext:password` | `filetype:yaml intext:password` | YAML passwords |
| `filetype:yml intext:password` | `filetype:yml intext:password` | YML passwords |
| `filetype:json intext:password` | `filetype:json intext:password` | JSON passwords |
| `filetype:toml intext:password` | `filetype:toml intext:password` | TOML passwords |

---

## 🗜️ Archive & Backup Files

> Find exposed archive files that may contain source code, databases, or backups.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:bak` | `filetype:bak` | BAK backup files |
| `filetype:backup` | `filetype:backup` | BACKUP files |
| `filetype:old` | `filetype:old` | Old file versions |
| `filetype:orig` | `filetype:orig` | Original file copies |
| `filetype:save` | `filetype:save` | Saved file versions |
| `filetype:tar` | `filetype:tar` | TAR archives |
| `filetype:zip` | `filetype:zip intext:backup` | ZIP backup files |
| `filetype:gz` | `filetype:gz intext:backup` | GZIP archives |
| `filetype:7z` | `filetype:7z` | 7-Zip archives |
| `filetype:rar` | `filetype:rar` | RAR archives |
| `filetype:tgz` | `filetype:tgz` | TGZ compressed archives |
| `inurl:backup.zip` | `inurl:backup.zip` | Site backup ZIPs |
| `inurl:backup.tar` | `inurl:backup.tar` | Site backup TARs |
| `inurl:backup.gz` | `inurl:backup.gz` | GZ backups |
| `inurl:site.zip` | `inurl:site.zip` | Site archive ZIPs |
| `inurl:dump.sql.gz` | `inurl:dump.sql.gz` | Compressed SQL dumps |
| `intitle:"index of" backup` | `intitle:"index of" backup` | Backup directories |
| `intitle:"index of" "backup"` | `intitle:"index of" "backup" site:com` | Backup listing pages |
| `intitle:"index of" ".bak"` | `intitle:"index of" ".bak"` | BAK file directories |
| `inurl:_bak` | `inurl:_bak` | Folders named _bak |
| `inurl:old` | `inurl:old` | Old version URLs |
| `inurl:.old` | `inurl:.old` | URLs with .old extension |
| `inurl:archive` | `inurl:archive filetype:zip` | Archive URL directories |
| `inurl:dump` | `inurl:dump filetype:sql` | SQL dump files |
| `filetype:zip intext:config` | `filetype:zip intext:config` | Config ZIPs |
| `filetype:tar intext:database` | `filetype:tar intext:database` | DB TARs |
| `filetype:bak intext:sql` | `filetype:bak intext:sql` | SQL backup files |
| `filetype:bak intext:password` | `filetype:bak intext:password` | BAK with passwords |
| `filetype:zip intext:password` | `filetype:zip intext:password` | ZIPs with passwords |
| `filetype:zip site:edu` | `filetype:zip site:edu` | Education archives |

---

## 🔑 Passwords & Credentials

> One of the most critical OSINT targets — accidentally exposed credential files.

| Dork | Example Usage | Description |
|---|---|---|
| `intext:"password" filetype:txt` | `intext:"password" filetype:txt` | TXT password files |
| `intext:"passwd" filetype:txt` | `intext:"passwd" filetype:txt` | Passwd-style files |
| `intext:"pwd" intext:"username"` | `intext:"pwd" intext:"username" filetype:txt` | PWD+username pairs |
| `intext:"pass" intext:"login"` | `intext:"pass" intext:"login" filetype:txt` | Login files |
| `intext:"credentials" filetype:txt` | `intext:"credentials" filetype:txt` | Credential TXTs |
| `intext:"login: " intext:"password:"` | `intext:"login: " intext:"password:" filetype:txt` | Login:Password pairs |
| `intext:"user: " intext:"pass: "` | `intext:"user: " intext:"pass: " filetype:txt` | User:Pass format |
| `intext:admin intext:password filetype:txt` | `intext:admin intext:password filetype:txt` | Admin passwords |
| `intext:"default password"` | `intext:"default password" filetype:pdf` | Default passwords |
| `intext:"root password"` | `intext:"root password" filetype:txt` | Root passwords |
| `intext:"mysql password"` | `intext:"mysql password" filetype:txt` | MySQL passwords |
| `intext:"ftp password"` | `intext:"ftp password" filetype:txt` | FTP passwords |
| `intext:"ssh password"` | `intext:"ssh password" filetype:txt` | SSH passwords |
| `intext:"smtp password"` | `intext:"smtp password" filetype:txt` | SMTP passwords |
| `intext:"db_password"` | `intext:"db_password" filetype:php` | DB password in PHP |
| `intext:"DB_PASSWORD"` | `intext:"DB_PASSWORD" filetype:env` | ENV DB password |
| `intext:"database password"` | `intext:"database password" filetype:conf` | Database passwords |
| `intext:"connection string"` | `intext:"connection string" password` | DB connection strings |
| `intext:"password=" filetype:log` | `intext:"password=" filetype:log` | Passwords in logs |
| `intext:"password=" filetype:env` | `intext:"password=" filetype:env` | Passwords in env |
| `intext:"PASS=" filetype:conf` | `intext:"PASS=" filetype:conf` | PASS in config files |
| `intext:"Authorization: Basic"` | `intext:"Authorization: Basic" filetype:log` | Base64 basic auth |
| `intext:htpasswd` | `intext:htpasswd filetype:txt` | HTPasswd files |
| `filetype:htpasswd` | `filetype:htpasswd` | HTPasswd files |
| `intext:"BEGIN RSA PRIVATE KEY"` | `intext:"BEGIN RSA PRIVATE KEY"` | RSA private keys |
| `intext:"BEGIN PRIVATE KEY"` | `intext:"BEGIN PRIVATE KEY"` | Private keys |
| `intext:"BEGIN CERTIFICATE"` | `intext:"BEGIN CERTIFICATE" filetype:txt` | SSL certificates |
| `intext:id_rsa` | `intext:id_rsa filetype:txt` | SSH private keys |
| `intext:id_dsa` | `intext:id_dsa filetype:txt` | DSA private keys |
| `intext:"password hash"` | `intext:"password hash" filetype:txt` | Password hashes |
| `intext:"MD5 hash"` | `intext:"MD5 hash" filetype:txt` | MD5 hashes |
| `intext:"SHA1 hash"` | `intext:"SHA1 hash" filetype:txt` | SHA1 hashes |
| `intext:"bcrypt"` | `intext:"bcrypt" filetype:txt` | Bcrypt hashes |
| `intext:"shadow" filetype:txt` | `intext:"shadow" intext:root filetype:txt` | Shadow password files |
| `intext:"passwd" filetype:conf` | `intext:"passwd" filetype:conf` | Passwd in configs |
| `intext:"admin:admin"` | `intext:"admin:admin" filetype:txt` | Default admin creds |
| `intext:"guest:guest"` | `intext:"guest:guest"` | Default guest creds |
| `intext:"administrator:password"` | `intext:"administrator:password"` | Administrator passwords |

---

## 🗝️ API Keys & Tokens

> Discover accidentally exposed API keys across public pages, repos, and files.

| Dork | Example Usage | Description |
|---|---|---|
| `intext:api_key` | `intext:api_key filetype:json` | Generic API keys |
| `intext:apikey` | `intext:apikey filetype:txt` | API key variables |
| `intext:api_secret` | `intext:api_secret` | API secrets |
| `intext:access_token` | `intext:access_token filetype:json` | Access tokens |
| `intext:bearer` | `intext:bearer filetype:txt` | Bearer tokens |
| `intext:"Authorization: Bearer"` | `intext:"Authorization: Bearer" filetype:log` | Auth headers |
| `intext:aws_access_key_id` | `intext:aws_access_key_id` | AWS access keys |
| `intext:aws_secret_access_key` | `intext:aws_secret_access_key` | AWS secret keys |
| `intext:AKID` | `intext:AKID filetype:txt` | AWS key format |
| `intext:AKIA` | `intext:AKIA filetype:txt` | AWS AKIA keys |
| `intext:AIza` | `intext:AIza` | Google API keys |
| `intext:"google_api_key"` | `intext:"google_api_key" filetype:js` | Google API key variable |
| `intext:"GOOGLE_API_KEY"` | `intext:"GOOGLE_API_KEY" filetype:env` | ENV Google key |
| `intext:sk_live` | `intext:sk_live` | Stripe live secret keys |
| `intext:pk_live` | `intext:pk_live` | Stripe live public keys |
| `intext:sk_test` | `intext:sk_test` | Stripe test keys |
| `intext:ghp_` | `intext:ghp_ filetype:txt` | GitHub personal tokens |
| `intext:gho_` | `intext:gho_` | GitHub OAuth tokens |
| `intext:ghs_` | `intext:ghs_` | GitHub server tokens |
| `intext:ghr_` | `intext:ghr_` | GitHub refresh tokens |
| `intext:"GITHUB_TOKEN"` | `intext:"GITHUB_TOKEN" filetype:env` | GitHub token ENV |
| `intext:xoxb-` | `intext:xoxb-` | Slack bot tokens |
| `intext:xoxp-` | `intext:xoxp-` | Slack user tokens |
| `intext:xoxa-` | `intext:xoxa-` | Slack workspace tokens |
| `intext:"SLACK_TOKEN"` | `intext:"SLACK_TOKEN" filetype:env` | Slack token ENV |
| `intext:"twilio"` | `intext:"twilio" intext:api_key` | Twilio API keys |
| `intext:"sendgrid"` | `intext:"sendgrid" intext:api_key` | SendGrid keys |
| `intext:"mailgun"` | `intext:"mailgun" intext:api_key` | Mailgun keys |
| `intext:"mailchimp"` | `intext:"mailchimp" intext:api_key` | Mailchimp keys |
| `intext:firebase` | `intext:firebase intext:api_key` | Firebase keys |
| `intext:"FIREBASE_API_KEY"` | `intext:"FIREBASE_API_KEY"` | Firebase API key |
| `intext:dropbox_token` | `intext:dropbox_token` | Dropbox tokens |
| `intext:"azure_client_secret"` | `intext:"azure_client_secret"` | Azure secrets |
| `intext:"AZURE_CLIENT_ID"` | `intext:"AZURE_CLIENT_ID" filetype:env` | Azure client IDs |
| `intext:heroku` | `intext:heroku intext:api_key` | Heroku API keys |
| `intext:paypal` | `intext:paypal intext:client_secret` | PayPal secrets |
| `intext:shopify` | `intext:shopify intext:api_key` | Shopify keys |
| `intext:twitter` | `intext:twitter intext:consumer_key` | Twitter API keys |
| `intext:"consumer_secret"` | `intext:"consumer_secret"` | Consumer secrets |
| `intext:facebook` | `intext:facebook intext:app_secret` | Facebook secrets |
| `intext:instagram` | `intext:instagram intext:access_token` | Instagram tokens |
| `intext:linkedin` | `intext:linkedin intext:client_secret` | LinkedIn secrets |
| `intext:openai` | `intext:openai intext:api_key` | OpenAI keys |
| `intext:"sk-"` | `intext:"sk-" filetype:txt` | OpenAI-style keys |
| `intext:anthropic` | `intext:anthropic intext:api_key` | Anthropic API keys |
| `intext:cloudflare` | `intext:cloudflare intext:api_key` | Cloudflare keys |
| `intext:digitalocean` | `intext:digitalocean intext:token` | DigitalOcean tokens |
| `intext:linode` | `intext:linode intext:api_key` | Linode keys |
| `intext:vultr` | `intext:vultr intext:api_key` | Vultr API keys |
| `intext:jwt` | `intext:jwt intext:secret` | JWT secrets |
| `intext:"JWT_SECRET"` | `intext:"JWT_SECRET" filetype:env` | JWT secret ENV |

---

## ⚙️ Config & Environment Files

> Configuration and environment files that often contain database URLs and credentials.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:env` | `filetype:env` | All ENV files |
| `filetype:env intext:DB_PASSWORD` | `filetype:env intext:DB_PASSWORD` | DB password in ENV |
| `filetype:env intext:DB_USER` | `filetype:env intext:DB_USER` | DB user in ENV |
| `filetype:env intext:DATABASE_URL` | `filetype:env intext:DATABASE_URL` | DB URL in ENV |
| `filetype:env intext:SECRET_KEY` | `filetype:env intext:SECRET_KEY` | Secret keys in ENV |
| `filetype:env intext:APP_KEY` | `filetype:env intext:APP_KEY` | App keys in ENV |
| `filetype:env intext:MAIL_PASSWORD` | `filetype:env intext:MAIL_PASSWORD` | Mail passwords |
| `filetype:env intext:SMTP` | `filetype:env intext:SMTP` | SMTP config in ENV |
| `filetype:env intext:REDIS` | `filetype:env intext:REDIS` | Redis config |
| `filetype:env intext:MONGO` | `filetype:env intext:MONGO` | MongoDB config |
| `filetype:env intext:AWS` | `filetype:env intext:AWS` | AWS config in ENV |
| `filetype:php intext:db_password` | `filetype:php intext:db_password` | PHP DB passwords |
| `filetype:php intext:mysql_connect` | `filetype:php intext:mysql_connect` | MySQL connections |
| `filetype:php intext:"define('DB_PASSWORD"` | `filetype:php intext:"define('DB_PASSWORD"` | WP DB password |
| `filetype:php intext:wp-config` | `filetype:php intext:wp-config` | WP config files |
| `filetype:php intext:"DB_HOST"` | `filetype:php intext:"DB_HOST"` | DB host in PHP |
| `filetype:php intext:"DB_NAME"` | `filetype:php intext:"DB_NAME"` | DB name in PHP |
| `filetype:php intext:config` | `filetype:php intext:config` | PHP config files |
| `filetype:php intext:database` | `filetype:php intext:database` | PHP database config |
| `filetype:php intext:settings` | `filetype:php intext:settings` | PHP settings files |
| `filetype:json intext:config` | `filetype:json intext:config` | JSON config files |
| `filetype:json intext:database` | `filetype:json intext:database password` | JSON DB config |
| `filetype:yml intext:password` | `filetype:yml intext:password` | YAML passwords |
| `filetype:yaml intext:password` | `filetype:yaml intext:password` | YAML passwords |
| `filetype:yml intext:database` | `filetype:yml intext:database` | YAML DB config |
| `filetype:xml intext:password` | `filetype:xml intext:password` | XML passwords |
| `filetype:xml intext:connectionString` | `filetype:xml intext:connectionString` | .NET connection strings |
| `filetype:conf intext:password` | `filetype:conf intext:password` | CONF passwords |
| `filetype:conf intext:nginx` | `filetype:conf intext:nginx` | Nginx configs |
| `filetype:conf intext:apache` | `filetype:conf intext:apache` | Apache configs |
| `filetype:conf intext:mysql` | `filetype:conf intext:mysql` | MySQL configs |
| `filetype:ini intext:password` | `filetype:ini intext:password` | INI passwords |
| `filetype:ini intext:database` | `filetype:ini intext:database` | INI DB config |
| `inurl:wp-config.php` | `inurl:wp-config.php` | WordPress config |
| `inurl:config.php` | `inurl:config.php intext:password` | PHP config files |
| `inurl:settings.php` | `inurl:settings.php intext:password` | Settings PHP |
| `inurl:database.php` | `inurl:database.php` | Database PHP files |
| `inurl:.env` | `inurl:.env` | ENV file URLs |
| `inurl:config.json` | `inurl:config.json intext:password` | Config JSON |
| `inurl:settings.json` | `inurl:settings.json intext:password` | Settings JSON |
| `inurl:secrets.json` | `inurl:secrets.json` | Secrets JSON |
| `inurl:credentials.json` | `inurl:credentials.json` | Credentials JSON |
| `inurl:appsettings.json` | `inurl:appsettings.json` | .NET appsettings |
| `inurl:.htpasswd` | `inurl:.htpasswd` | HTPasswd files |
| `inurl:.htaccess` | `inurl:.htaccess` | HTACCESS files |
| `inurl:web.config` | `inurl:web.config` | ASP.NET web.config |
| `inurl:application.properties` | `inurl:application.properties intext:password` | Spring properties |
| `inurl:application.yml` | `inurl:application.yml intext:password` | Spring YAML |

---

## 🔒 SSH & Certificates

> Exposed SSH keys, SSL certificates, and cryptographic material.

| Dork | Example Usage | Description |
|---|---|---|
| `intext:"BEGIN RSA PRIVATE KEY"` | `intext:"BEGIN RSA PRIVATE KEY"` | RSA private keys |
| `intext:"BEGIN DSA PRIVATE KEY"` | `intext:"BEGIN DSA PRIVATE KEY"` | DSA private keys |
| `intext:"BEGIN EC PRIVATE KEY"` | `intext:"BEGIN EC PRIVATE KEY"` | EC private keys |
| `intext:"BEGIN OPENSSH PRIVATE KEY"` | `intext:"BEGIN OPENSSH PRIVATE KEY"` | OpenSSH keys |
| `intext:"BEGIN PGP PRIVATE KEY"` | `intext:"BEGIN PGP PRIVATE KEY"` | PGP private keys |
| `intext:"BEGIN PGP PUBLIC KEY"` | `intext:"BEGIN PGP PUBLIC KEY"` | PGP public keys |
| `filetype:pem intext:PRIVATE` | `filetype:pem intext:PRIVATE` | PEM private keys |
| `filetype:key intext:PRIVATE` | `filetype:key intext:PRIVATE` | KEY private files |
| `filetype:ppk` | `filetype:ppk` | PuTTY private keys |
| `filetype:p12` | `filetype:p12` | P12 certificate files |
| `filetype:pfx` | `filetype:pfx` | PFX certificate files |
| `filetype:crt` | `filetype:crt` | CRT certificate files |
| `filetype:cer` | `filetype:cer` | CER certificate files |
| `inurl:id_rsa` | `inurl:id_rsa` | id_rsa key files |
| `inurl:id_dsa` | `inurl:id_dsa` | id_dsa key files |
| `inurl:.ssh` | `inurl:.ssh` | SSH directories |
| `inurl:authorized_keys` | `inurl:authorized_keys` | Authorized keys files |
| `inurl:known_hosts` | `inurl:known_hosts` | Known hosts files |
| `filetype:pub intext:ssh-rsa` | `filetype:pub intext:ssh-rsa` | SSH public keys |
| `intext:ssh-rsa AAAA` | `intext:ssh-rsa AAAA filetype:txt` | SSH public key strings |

---

## 🛡️ Admin Panels

> Find exposed administrative interfaces and control panels.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:admin` | `inurl:admin site:example.com` | Admin pages |
| `inurl:admin/login` | `inurl:admin/login` | Admin login pages |
| `intitle:admin` | `intitle:admin` | Pages titled admin |
| `intitle:admin dashboard` | `intitle:admin dashboard` | Admin dashboards |
| `intitle:admin panel` | `intitle:admin panel` | Admin panels |
| `intitle:admin console` | `intitle:admin console` | Admin consoles |
| `intitle:administration` | `intitle:administration` | Admin pages |
| `inurl:administration` | `inurl:administration` | Admin URLs |
| `inurl:admin-area` | `inurl:admin-area` | Admin areas |
| `inurl:backend/admin` | `inurl:backend/admin` | Backend admin |
| `inurl:adminpanel` | `inurl:adminpanel` | Admin panel URLs |
| `inurl:manage` | `inurl:manage` | Management pages |
| `inurl:manager` | `inurl:manager` | Manager pages |
| `inurl:management` | `inurl:management` | Management URLs |
| `inurl:controlpanel` | `inurl:controlpanel` | Control panels |
| `inurl:control-panel` | `inurl:control-panel` | Control panel URLs |
| `inurl:admin.php` | `inurl:admin.php` | Admin PHP pages |
| `inurl:admin.aspx` | `inurl:admin.aspx` | Admin ASPX pages |
| `inurl:admin.html` | `inurl:admin.html` | Admin HTML pages |
| `inurl:administrator` | `inurl:administrator` | Administrator URLs |
| `intitle:"admin login"` | `intitle:"admin login"` | Admin login pages |
| `intitle:"admin index"` | `intitle:"admin index"` | Admin index pages |
| `intitle:"index.of admin"` | `intitle:"index.of admin"` | Admin directories |
| `intitle:"site administration"` | `intitle:"site administration"` | Site admin pages |
| `intitle:"site manager"` | `intitle:"site manager"` | Site manager |
| `intitle:"web admin"` | `intitle:"web admin"` | Web admin interfaces |
| `inurl:admin intext:login` | `inurl:admin intext:login` | Admin login forms |
| `inurl:/admin/` | `inurl:/admin/` | Admin directory |
| `inurl:wp-admin` | `inurl:wp-admin` | WordPress admin |
| `inurl:joomla-administrator` | `inurl:joomla-administrator` | Joomla admin |
| `inurl:drupal/admin` | `inurl:drupal/admin` | Drupal admin |
| `inurl:sitecore` | `inurl:sitecore/shell` | Sitecore admin |
| `inurl:umbraco` | `inurl:umbraco` | Umbraco admin |
| `inurl:typo3` | `inurl:typo3` | TYPO3 admin |
| `inurl:magento/admin` | `inurl:magento/admin` | Magento admin |
| `intitle:"Tomcat" inurl:manager` | `intitle:"Tomcat" inurl:manager` | Tomcat manager |
| `intitle:"Jenkins"` | `intitle:"Jenkins" inurl:dashboard` | Jenkins dashboard |
| `intitle:"Kibana"` | `intitle:"Kibana" inurl:app` | Kibana admin |
| `intitle:"Grafana"` | `intitle:"Grafana" inurl:login` | Grafana login |
| `intitle:"Portainer"` | `intitle:"Portainer" inurl:auth` | Portainer Docker admin |

---

## 🔐 Login Pages

> Discover login interfaces across the web — useful for reconnaissance and audit.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:login` | `inurl:login` | Login pages |
| `inurl:signin` | `inurl:signin` | Sign-in pages |
| `inurl:sign-in` | `inurl:sign-in` | Sign-in hyphenated |
| `inurl:auth/login` | `inurl:auth/login` | Auth login |
| `inurl:user/login` | `inurl:user/login` | User login |
| `inurl:member/login` | `inurl:member/login` | Member login |
| `inurl:account/login` | `inurl:account/login` | Account login |
| `inurl:customer/login` | `inurl:customer/login` | Customer login |
| `inurl:secure/login` | `inurl:secure/login` | Secure login |
| `inurl:portal/login` | `inurl:portal/login` | Portal login |
| `inurl:login.php` | `inurl:login.php` | Login PHP |
| `inurl:login.asp` | `inurl:login.asp` | Login ASP |
| `inurl:login.aspx` | `inurl:login.aspx` | Login ASPX |
| `inurl:login.html` | `inurl:login.html` | Login HTML |
| `intitle:"login"` | `intitle:"login"` | Pages titled login |
| `intitle:"user login"` | `intitle:"user login"` | User login pages |
| `intitle:"portal login"` | `intitle:"portal login"` | Portal logins |
| `intitle:"member login"` | `intitle:"member login"` | Member logins |
| `intitle:"account login"` | `intitle:"account login"` | Account logins |
| `intitle:"please log in"` | `intitle:"please log in"` | Login prompts |
| `intitle:"sign in"` | `intitle:"sign in"` | Sign in pages |
| `intext:"username" intext:"password" inurl:login` | `intext:"username" intext:"password" inurl:login` | Login forms |
| `inurl:login intext:"forgot password"` | `inurl:login intext:"forgot password"` | Reset password pages |
| `inurl:login intext:"remember me"` | `inurl:login intext:"remember me"` | Remember-me logins |
| `inurl:owa` | `inurl:owa` | Outlook Web Access |
| `intitle:"Outlook Web App"` | `intitle:"Outlook Web App"` | OWA login |
| `intitle:"Citrix"` | `intitle:"Citrix" inurl:login` | Citrix login |
| `intitle:"VPN" inurl:login` | `intitle:"VPN" inurl:login` | VPN login pages |
| `inurl:vpn/login` | `inurl:vpn/login` | VPN login |
| `inurl:remote/login` | `inurl:remote/login` | Remote access login |
| `inurl:rdp/login` | `inurl:rdp/login` | RDP login |
| `inurl:ssh/login` | `inurl:ssh/login` | SSH web login |

---

## 🗄️ Database Panels

> Find exposed database management interfaces.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:phpmyadmin` | `inurl:phpmyadmin` | phpMyAdmin panels |
| `intitle:phpMyAdmin` | `intitle:phpMyAdmin` | PMA page titles |
| `inurl:phpmyadmin/index.php` | `inurl:phpmyadmin/index.php` | PMA login |
| `intitle:"phpMyAdmin" intext:"Welcome to"` | `intitle:"phpMyAdmin" intext:"Welcome to"` | PMA welcome page |
| `inurl:db/phpmyadmin` | `inurl:db/phpmyadmin` | DB admin paths |
| `inurl:phpmyadmin/setup` | `inurl:phpmyadmin/setup` | PMA setup page |
| `intitle:adminer` | `intitle:adminer` | Adminer DB admin |
| `inurl:adminer.php` | `inurl:adminer.php` | Adminer PHP |
| `inurl:adminer` | `inurl:adminer` | Adminer panels |
| `intitle:"SQL Server" inurl:asp` | `intitle:"SQL Server" inurl:asp` | SQL Server web |
| `intitle:"MongoDB" inurl:28017` | `intitle:"MongoDB" inurl:28017` | MongoDB HTTP |
| `inurl:27017` | `inurl:27017` | MongoDB default port |
| `inurl:5432` | `inurl:5432` | PostgreSQL port |
| `inurl:3306` | `inurl:3306` | MySQL port URLs |
| `intitle:"Cassandra" inurl:admin` | `intitle:"Cassandra" inurl:admin` | Cassandra admin |
| `intitle:"Redis" inurl:admin` | `intitle:"Redis" inurl:admin` | Redis admin |
| `intitle:"Elasticsearch"` | `intitle:"Elasticsearch"` | Elasticsearch UI |
| `inurl:elasticsearch` | `inurl:elasticsearch` | Elasticsearch URLs |
| `inurl:_cat/indices` | `inurl:_cat/indices` | Elasticsearch indices |
| `inurl:kibana` | `inurl:kibana` | Kibana dashboards |
| `intitle:"RabbitMQ"` | `intitle:"RabbitMQ"` | RabbitMQ mgmt |
| `inurl:rabbitmq` | `inurl:rabbitmq` | RabbitMQ URLs |

---

## 🖥️ cPanel & Hosting

> Identify web hosting control panels that may be misconfigured.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:cpanel` | `inurl:cpanel` | cPanel panels |
| `intitle:cpanel` | `intitle:cpanel login` | cPanel login |
| `inurl:2082` | `inurl:2082` | cPanel port 2082 |
| `inurl:2083` | `inurl:2083` | cPanel SSL port |
| `inurl:2086` | `inurl:2086` | WHM port |
| `inurl:2087` | `inurl:2087` | WHM SSL port |
| `inurl:whm` | `inurl:whm` | WHM panels |
| `intitle:"WHM"` | `intitle:"WHM"` | WHM page titles |
| `inurl:webmail` | `inurl:webmail` | Webmail interfaces |
| `intitle:webmail` | `intitle:webmail` | Webmail pages |
| `intitle:plesk` | `intitle:plesk` | Plesk panels |
| `inurl:plesk` | `inurl:plesk` | Plesk URLs |
| `intitle:directadmin` | `intitle:directadmin` | DirectAdmin |
| `inurl:directadmin` | `inurl:directadmin` | DirectAdmin URLs |
| `intitle:ispconfig` | `intitle:ispconfig` | ISPConfig panels |
| `inurl:ispconfig` | `inurl:ispconfig` | ISPConfig URLs |
| `intitle:"Webmin"` | `intitle:"Webmin"` | Webmin panels |
| `inurl:webmin` | `inurl:webmin` | Webmin URLs |
| `inurl:10000` | `inurl:10000` | Webmin port |
| `intitle:"VirtualMin"` | `intitle:"VirtualMin"` | VirtualMin panels |
| `inurl:virtualmin` | `inurl:virtualmin` | VirtualMin URLs |
| `intitle:"HestiaCP"` | `intitle:"HestiaCP"` | HestiaCP panels |
| `inurl:8083` | `inurl:8083` | HestiaCP port |
| `intitle:"Froxlor"` | `intitle:"Froxlor"` | Froxlor panels |
| `inurl:froxlor` | `inurl:froxlor` | Froxlor URLs |

---

## 📂 Open Directories

> Directory listing pages that expose all files in a folder.

| Dork | Example Usage | Description |
|---|---|---|
| `intitle:"index of"` | `intitle:"index of"` | All directory listings |
| `intitle:"index of /"` | `intitle:"index of /"` | Root directories |
| `intitle:"index of" "parent directory"` | `intitle:"index of" "parent directory"` | Parent directory listings |
| `intitle:"directory listing"` | `intitle:"directory listing"` | Directory listing pages |
| `intitle:"index of" site:.edu` | `intitle:"index of" site:.edu` | Edu open directories |
| `intitle:"index of" site:.gov` | `intitle:"index of" site:.gov` | Gov open directories |
| `intitle:"index of" apache` | `intitle:"index of" apache` | Apache listings |
| `intitle:"index of" nginx` | `intitle:"index of" nginx` | Nginx listings |
| `intitle:"index of" iis` | `intitle:"index of" iis` | IIS listings |
| `intitle:"autoindex"` | `intitle:"autoindex"` | Auto-index pages |
| `intitle:"index of" uploads` | `intitle:"index of" uploads` | Upload directories |
| `intitle:"index of" files` | `intitle:"index of" files` | Files directories |
| `intitle:"index of" images` | `intitle:"index of" images` | Image directories |
| `intitle:"index of" media` | `intitle:"index of" media` | Media directories |
| `intitle:"index of" documents` | `intitle:"index of" documents` | Document directories |
| `intitle:"index of" downloads` | `intitle:"index of" downloads` | Download directories |
| `intitle:"index of" assets` | `intitle:"index of" assets` | Asset directories |
| `intitle:"index of" public` | `intitle:"index of" public` | Public directories |
| `intitle:"index of" private` | `intitle:"index of" private` | Private directories |
| `intitle:"index of" backup` | `intitle:"index of" backup` | Backup directories |
| `intitle:"index of" config` | `intitle:"index of" config` | Config directories |
| `intitle:"index of" settings` | `intitle:"index of" settings` | Settings directories |
| `intitle:"index of" conf` | `intitle:"index of" conf` | Conf directories |
| `intitle:"index of" etc` | `intitle:"index of" etc` | ETC directories |
| `intitle:"index of" logs` | `intitle:"index of" logs` | Log directories |
| `intitle:"index of" log` | `intitle:"index of" log` | Log file directories |
| `intitle:"index of" tmp` | `intitle:"index of" tmp` | Temp directories |
| `intitle:"index of" temp` | `intitle:"index of" temp` | Temp file directories |
| `intitle:"index of" cache` | `intitle:"index of" cache` | Cache directories |
| `intitle:"index of" include` | `intitle:"index of" include` | Include directories |
| `intitle:"index of" lib` | `intitle:"index of" lib` | Library directories |
| `intitle:"index of" vendor` | `intitle:"index of" vendor` | Vendor directories |
| `intitle:"index of" node_modules` | `intitle:"index of" node_modules` | Node modules exposed |
| `intitle:"index of" .git` | `intitle:"index of" .git` | Git directories |
| `intitle:"index of" .svn` | `intitle:"index of" .svn` | SVN directories |
| `intitle:"index of" sql` | `intitle:"index of" sql` | SQL file directories |
| `intitle:"index of" db` | `intitle:"index of" db` | DB directories |
| `intitle:"index of" dump` | `intitle:"index of" dump` | Dump file directories |

---

## 🗃️ Database Files

> Raw database files exposed on the web — a goldmine for security research.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:sql` | `filetype:sql` | All SQL dump files |
| `filetype:sql intext:"INSERT INTO"` | `filetype:sql intext:"INSERT INTO"` | SQL dumps with data |
| `filetype:sql intext:mysql` | `filetype:sql intext:mysql` | MySQL SQL files |
| `filetype:sql intext:backup` | `filetype:sql intext:backup` | SQL backup dumps |
| `filetype:sql intext:password` | `filetype:sql intext:password` | SQL files with passwords |
| `filetype:sql intext:CREATE DATABASE` | `filetype:sql intext:CREATE DATABASE` | DB creation scripts |
| `filetype:sql intext:CREATE TABLE` | `filetype:sql intext:CREATE TABLE` | Table creation SQL |
| `filetype:sql intext:DROP TABLE` | `filetype:sql intext:DROP TABLE` | DROP table SQL |
| `filetype:sql intext:ALTER TABLE` | `filetype:sql intext:ALTER TABLE` | ALTER table SQL |
| `filetype:sql intext:username` | `filetype:sql intext:username` | SQL with usernames |
| `filetype:sql intext:email` | `filetype:sql intext:email` | SQL with emails |
| `filetype:sql intext:users` | `filetype:sql intext:users` | User table dumps |
| `filetype:mdb` | `filetype:mdb` | MS Access databases |
| `filetype:db` | `filetype:db` | SQLite DB files |
| `filetype:sqlite` | `filetype:sqlite` | SQLite files |
| `filetype:sqlite3` | `filetype:sqlite3` | SQLite3 files |
| `filetype:accdb` | `filetype:accdb` | MS Access ACCDB |
| `filetype:dbf` | `filetype:dbf` | DBF database files |
| `filetype:json intext:mongodb` | `filetype:json intext:mongodb` | MongoDB JSON export |
| `filetype:json intext:"_id"` | `filetype:json intext:"_id"` | MongoDB documents |
| `inurl:dump.sql` | `inurl:dump.sql` | SQL dump files |
| `inurl:database.sql` | `inurl:database.sql` | Database SQL files |
| `inurl:backup.sql` | `inurl:backup.sql` | SQL backup files |
| `inurl:data.sql` | `inurl:data.sql` | Data SQL files |
| `inurl:db.sql` | `inurl:db.sql` | DB SQL files |

---

## 📋 Log Files

> Exposed log files can reveal internal IP addresses, user actions, and system info.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:log` | `filetype:log` | All log files |
| `filetype:log intext:error` | `filetype:log intext:error` | Error log files |
| `filetype:log intext:warning` | `filetype:log intext:warning` | Warning logs |
| `filetype:log intext:debug` | `filetype:log intext:debug` | Debug log files |
| `filetype:log intext:exception` | `filetype:log intext:exception` | Exception logs |
| `filetype:log intext:fatal` | `filetype:log intext:fatal` | Fatal error logs |
| `filetype:log intext:access` | `filetype:log intext:access` | Access logs |
| `filetype:log intext:auth` | `filetype:log intext:auth` | Authentication logs |
| `filetype:log intext:apache` | `filetype:log intext:apache` | Apache logs |
| `filetype:log intext:nginx` | `filetype:log intext:nginx` | Nginx logs |
| `filetype:log intext:ftp` | `filetype:log intext:ftp` | FTP log files |
| `filetype:log intext:ssh` | `filetype:log intext:ssh` | SSH log files |
| `filetype:log intext:mysql` | `filetype:log intext:mysql` | MySQL logs |
| `filetype:log intext:php` | `filetype:log intext:php` | PHP error logs |
| `filetype:log intext:sql` | `filetype:log intext:sql` | SQL logs |
| `filetype:log intext:password` | `filetype:log intext:password` | Passwords in logs |
| `filetype:log intext:username` | `filetype:log intext:username` | Usernames in logs |
| `filetype:log intext:login` | `filetype:log intext:login` | Login activity logs |
| `filetype:log intext:failed` | `filetype:log intext:failed login` | Failed login logs |
| `filetype:log intext:invalid` | `filetype:log intext:invalid user` | Invalid user logs |
| `filetype:log intext:ip` | `filetype:log intext:ip address` | IP address logs |
| `filetype:log intext:user-agent` | `filetype:log intext:user-agent` | UA string logs |
| `filetype:log intext:404` | `filetype:log intext:404` | 404 error logs |
| `filetype:log intext:500` | `filetype:log intext:500` | 500 error logs |
| `filetype:log intext:403` | `filetype:log intext:403` | Forbidden error logs |
| `intitle:"index of" "access.log"` | `intitle:"index of" "access.log"` | Access log directories |
| `intitle:"index of" "error.log"` | `intitle:"index of" "error.log"` | Error log directories |
| `inurl:access.log` | `inurl:access.log` | Access log URLs |
| `inurl:error.log` | `inurl:error.log` | Error log URLs |
| `inurl:debug.log` | `inurl:debug.log` | Debug log URLs |

---

## 🔍 Database Errors

> Database error messages that reveal structure, software versions, and connection info.

| Dork | Example Usage | Description |
|---|---|---|
| `intext:"mysql_fetch_array()"` | `intext:"mysql_fetch_array()"` | MySQL PHP errors |
| `intext:"mysql_num_rows()"` | `intext:"mysql_num_rows()"` | MySQL row errors |
| `intext:"mysql_connect()"` | `intext:"mysql_connect()"` | MySQL connection errors |
| `intext:"supplied argument is not a valid MySQL"` | `intext:"supplied argument is not a valid MySQL"` | MySQL argument errors |
| `intext:"You have an error in your SQL syntax"` | `intext:"You have an error in your SQL syntax"` | SQL syntax errors |
| `intext:"Warning: mysql"` | `intext:"Warning: mysql"` | MySQL PHP warnings |
| `intext:"ORA-00921"` | `intext:"ORA-00921"` | Oracle DB errors |
| `intext:"ORA-00933"` | `intext:"ORA-00933"` | Oracle SQL errors |
| `intext:"ORA-01017"` | `intext:"ORA-01017"` | Oracle login errors |
| `intext:"Microsoft OLE DB Provider for ODBC"` | `intext:"Microsoft OLE DB Provider for ODBC"` | MSSQL ODBC errors |
| `intext:"Microsoft OLE DB Provider for SQL Server"` | `intext:"Microsoft OLE DB Provider for SQL Server"` | MSSQL OLE errors |
| `intext:"ODBC SQL Server Driver"` | `intext:"ODBC SQL Server Driver"` | MSSQL driver errors |
| `intext:"PostgreSQL query failed"` | `intext:"PostgreSQL query failed"` | PostgreSQL errors |
| `intext:"pg_connect():"` | `intext:"pg_connect():"` | PostgreSQL connection errors |
| `intext:"Warning: pg_"` | `intext:"Warning: pg_"` | PHP PostgreSQL warnings |
| `intext:"SQLite3::query"` | `intext:"SQLite3::query"` | SQLite errors |
| `intext:"java.sql.SQLException"` | `intext:"java.sql.SQLException"` | Java SQL exceptions |
| `intext:"com.mysql.jdbc"` | `intext:"com.mysql.jdbc"` | Java MySQL errors |
| `intext:"Unclosed quotation mark"` | `intext:"Unclosed quotation mark"` | SQL quote errors |
| `intext:"syntax error, unexpected"` | `intext:"syntax error, unexpected"` | SQL syntax errors |

---

## 📡 Routers & Network Devices

> Locate exposed network device management interfaces.

| Dork | Example Usage | Description |
|---|---|---|
| `intitle:"router"` | `intitle:"router" inurl:login` | Router login pages |
| `intitle:"Cisco" inurl:home` | `intitle:"Cisco" inurl:home` | Cisco routers |
| `intitle:"MikroTik"` | `intitle:"MikroTik"` | MikroTik routers |
| `intitle:"TP-Link"` | `intitle:"TP-Link" inurl:web` | TP-Link routers |
| `intitle:"D-Link"` | `intitle:"D-Link" inurl:login` | D-Link routers |
| `intitle:"NETGEAR"` | `intitle:"NETGEAR" inurl:login` | Netgear routers |
| `intitle:"Linksys"` | `intitle:"Linksys" inurl:index` | Linksys routers |
| `intitle:"ASUS"` | `intitle:"ASUS" inurl:router` | ASUS routers |
| `intitle:"ZTE"` | `intitle:"ZTE" inurl:login` | ZTE modems |
| `intitle:"Huawei"` | `intitle:"Huawei" inurl:login` | Huawei devices |
| `intitle:"pfSense"` | `intitle:"pfSense"` | pfSense firewalls |
| `intitle:"Sophos"` | `intitle:"Sophos" inurl:login` | Sophos firewalls |
| `intitle:"FortiGate"` | `intitle:"FortiGate"` | FortiGate firewalls |
| `intitle:"ASA"` | `intitle:"ASA" inurl:webvpn` | Cisco ASA firewalls |
| `intitle:"SonicWALL"` | `intitle:"SonicWALL"` | SonicWall firewalls |
| `intitle:"Ubiquiti"` | `intitle:"Ubiquiti" inurl:unifi` | Ubiquiti devices |
| `intitle:"UniFi"` | `intitle:"UniFi" inurl:login` | UniFi controllers |
| `intitle:"HP Switch"` | `intitle:"HP Switch"` | HP network switches |
| `intitle:"ProCurve"` | `intitle:"ProCurve"` | HP ProCurve switches |
| `intitle:"Juniper"` | `intitle:"Juniper" inurl:login` | Juniper devices |
| `intitle:"Aruba"` | `intitle:"Aruba" inurl:login` | Aruba wireless |
| `intitle:"Ruckus"` | `intitle:"Ruckus" inurl:login` | Ruckus wireless |
| `intitle:"Arris"` | `intitle:"Arris"` | Arris modems |
| `inurl:8080` | `inurl:8080 intitle:router` | Router alternate ports |
| `inurl:8443` | `inurl:8443 intitle:login` | Alternate SSL ports |
| `intitle:"network map"` | `intitle:"network map"` | Network diagrams |
| `intitle:"network management"` | `intitle:"network management"` | Network mgmt pages |
| `intext:"Default Password" intitle:router` | `intext:"Default Password" intitle:router` | Default router creds |
| `intitle:"System Information" intext:uptime` | `intitle:"System Information" intext:uptime` | Network device info |
| `intitle:"SNMP" inurl:admin` | `intitle:"SNMP" inurl:admin` | SNMP admin interfaces |

---

## 📷 IP Cameras & IoT

> Find exposed surveillance cameras, smart devices, and IoT interfaces.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:axis-cgi/mjpg` | `inurl:axis-cgi/mjpg` | Axis camera MJPEG |
| `inurl:netcam.jpg` | `inurl:netcam.jpg` | Network camera images |
| `intitle:"webcamXP"` | `intitle:"webcamXP"` | WebcamXP interface |
| `intitle:"IP Camera Viewer"` | `intitle:"IP Camera Viewer"` | IP camera viewer |
| `intitle:"Network Camera"` | `intitle:"Network Camera"` | Generic network cameras |
| `intitle:"Live View / - AXIS"` | `intitle:"Live View / - AXIS"` | Axis live camera |
| `intitle:"Hikvision"` | `intitle:"Hikvision" inurl:login` | Hikvision cameras |
| `intitle:"Dahua"` | `intitle:"Dahua" inurl:login` | Dahua cameras |
| `intitle:"D-Link"` | `intitle:"D-Link" inurl:webcam` | D-Link webcams |
| `intitle:"TRENDnet"` | `intitle:"TRENDnet" inurl:webcam` | TRENDnet cameras |
| `intitle:"Foscam"` | `intitle:"Foscam" inurl:webcam` | Foscam cameras |
| `intitle:"Panasonic"` | `intitle:"Panasonic" inurl:view` | Panasonic cameras |
| `intitle:"Sony"` | `intitle:"Sony" inurl:view` | Sony cameras |
| `intitle:"Bosch"` | `intitle:"Bosch" inurl:view` | Bosch cameras |
| `intitle:"Vivotek"` | `intitle:"Vivotek" inurl:view` | Vivotek cameras |
| `intitle:"Geovision"` | `intitle:"Geovision" inurl:view` | Geovision cameras |
| `intitle:"YawCam"` | `intitle:"YawCam"` | YawCam software |
| `inurl:view/index.shtml` | `inurl:view/index.shtml` | Camera index pages |
| `inurl:view/viewer_index.shtml` | `inurl:view/viewer_index.shtml` | Viewer index |
| `inurl:/cgi-bin/viewer/video.jpg` | `inurl:/cgi-bin/viewer/video.jpg` | CGI camera video |
| `inurl:mjpg/video.mjpg` | `inurl:mjpg/video.mjpg` | MJPEG video streams |
| `inurl:/video.cgi` | `inurl:/video.cgi` | Video CGI streams |
| `inurl:/snapshot.jpg` | `inurl:/snapshot.jpg` | Camera snapshots |
| `inurl:/jpg/image.jpg` | `inurl:/jpg/image.jpg` | JPEG camera images |
| `intitle:"IoT Dashboard"` | `intitle:"IoT Dashboard"` | IoT dashboards |
| `intitle:"Home Automation"` | `intitle:"Home Automation"` | Home automation |
| `intitle:"Smart Home"` | `intitle:"Smart Home" inurl:login` | Smart home panels |
| `intitle:"DVR Login"` | `intitle:"DVR Login"` | DVR login pages |
| `intitle:"NVR Login"` | `intitle:"NVR Login"` | NVR login pages |
| `intitle:"CCTV"` | `intitle:"CCTV" inurl:view` | CCTV viewing pages |

---

## 🏭 SCADA & Industrial

> Industrial Control Systems, PLCs, and SCADA interfaces exposed to the internet.

| Dork | Example Usage | Description |
|---|---|---|
| `intitle:SCADA` | `intitle:SCADA` | SCADA interfaces |
| `intitle:PLC` | `intitle:PLC` | PLC panels |
| `intitle:HMI` | `intitle:HMI` | HMI interfaces |
| `intitle:Wonderware` | `intitle:Wonderware` | Wonderware SCADA |
| `intitle:Siemens inurl:web` | `intitle:Siemens inurl:web` | Siemens controllers |
| `intitle:Rockwell inurl:web` | `intitle:Rockwell inurl:web` | Rockwell Automation |
| `intitle:Modbus` | `intitle:Modbus` | Modbus devices |
| `intitle:OPC` | `intitle:OPC` | OPC servers |
| `intitle:Citect` | `intitle:Citect` | Citect SCADA |
| `intitle:"GE Proficy"` | `intitle:"GE Proficy"` | GE Proficy |
| `intitle:"InduSoft"` | `intitle:"InduSoft"` | InduSoft SCADA |
| `intitle:"iFIX"` | `intitle:"iFIX"` | GE iFIX SCADA |
| `intitle:"Inductive Automation"` | `intitle:"Inductive Automation"` | Ignition SCADA |
| `intitle:"Ignition"` | `intitle:"Ignition" inurl:login` | Ignition panels |
| `intitle:"EnergyAxis"` | `intitle:"EnergyAxis"` | Energy management |
| `intitle:"Power Monitor"` | `intitle:"Power Monitor"` | Power monitors |
| `intitle:"BAS" inurl:login` | `intitle:"BAS" inurl:login` | Building automation |
| `intitle:"Building Management"` | `intitle:"Building Management"` | Building mgmt systems |
| `intext:"SCADA" intext:"login"` | `intext:"SCADA" intext:"login"` | SCADA login pages |
| `intext:"industrial control"` | `intext:"industrial control" inurl:login` | Industrial control |

---

## 🔗 VPN & Proxy

> Find VPN configurations, proxy files, and remote access portals.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:ovpn` | `filetype:ovpn` | OpenVPN configs |
| `filetype:conf intext:"[Interface]"` | `filetype:conf intext:"[Interface]"` | WireGuard configs |
| `filetype:conf intext:OpenVPN` | `filetype:conf intext:OpenVPN` | OpenVPN conf files |
| `inurl:vpn inurl:login` | `inurl:vpn inurl:login` | VPN login pages |
| `intitle:"VPN" inurl:login` | `intitle:"VPN" inurl:login` | VPN page titles |
| `intitle:"Cisco SSL VPN"` | `intitle:"Cisco SSL VPN"` | Cisco SSL VPN |
| `intitle:"FortiClient VPN"` | `intitle:"FortiClient VPN"` | FortiClient VPN |
| `intitle:"Pulse Secure"` | `intitle:"Pulse Secure"` | Pulse Secure VPN |
| `intitle:"GlobalProtect"` | `intitle:"GlobalProtect"` | Palo Alto VPN |
| `intitle:"Citrix Gateway"` | `intitle:"Citrix Gateway"` | Citrix gateway |
| `intitle:"Check Point VPN"` | `intitle:"Check Point VPN"` | Check Point VPN |
| `intitle:"SonicWall VPN"` | `intitle:"SonicWall VPN"` | SonicWall VPN |
| `intitle:"OpenVPN Access Server"` | `intitle:"OpenVPN Access Server"` | OpenVPN AS |
| `filetype:txt intext:socks5` | `filetype:txt intext:socks5` | SOCKS5 proxy lists |
| `filetype:txt intext:socks4` | `filetype:txt intext:socks4` | SOCKS4 proxy lists |
| `filetype:txt intext:"http proxy"` | `filetype:txt intext:"http proxy"` | HTTP proxy lists |
| `filetype:txt intext:"https proxy"` | `filetype:txt intext:"https proxy"` | HTTPS proxy lists |
| `inurl:proxy.pac` | `inurl:proxy.pac` | Proxy auto-config |
| `filetype:pac intext:proxy` | `filetype:pac intext:proxy` | PAC proxy files |
| `intext:"ProxyList"` | `intext:"ProxyList" filetype:txt` | Proxy list files |

---

## 👤 People & Profiles

> OSINT on individuals — useful for research, background checks, and investigation.

| Dork | Example Usage | Description |
|---|---|---|
| `site:linkedin.com/in/` | `site:linkedin.com/in/ "software engineer"` | LinkedIn profiles |
| `site:linkedin.com/pub/` | `site:linkedin.com/pub/` | LinkedIn pub profiles |
| `site:pipl.com` | `site:pipl.com` | Pipl people search |
| `site:spokeo.com` | `site:spokeo.com` | Spokeo profiles |
| `site:whitepages.com` | `site:whitepages.com` | Whitepages listings |
| `site:zabasearch.com` | `site:zabasearch.com` | Zaba search |
| `site:intelius.com` | `site:intelius.com` | Intelius profiles |
| `site:myspace.com` | `site:myspace.com` | MySpace profiles |
| `site:classmates.com` | `site:classmates.com` | Classmates profiles |
| `intext:"curriculum vitae" filetype:pdf` | `intext:"curriculum vitae" filetype:pdf` | CV documents |
| `intext:resume intext:email filetype:pdf` | `intext:resume intext:email filetype:pdf` | Resume with emails |
| `intext:resume intext:phone filetype:pdf` | `intext:resume intext:phone filetype:pdf` | Resume with phones |
| `intext:"personal email"` | `intext:"personal email" filetype:txt` | Personal emails |
| `intext:"phone number" filetype:txt` | `intext:"phone number" filetype:txt` | Phone numbers |
| `intext:"home address"` | `intext:"home address" filetype:txt` | Home addresses |
| `intext:"date of birth"` | `intext:"date of birth" filetype:txt` | Date of birth info |
| `intext:"SSN" intext:"name"` | `intext:"SSN" intext:"name" filetype:txt` | SSN with names |
| `intext:"driving license"` | `intext:"driving license" filetype:pdf` | Driver's license info |
| `intext:"passport number"` | `intext:"passport number" filetype:pdf` | Passport numbers |
| `intext:"voter registration"` | `intext:"voter registration" filetype:pdf` | Voter registration |

---

## 📱 Social Media

> Find public posts, profiles, and content across social platforms.

| Dork | Example Usage | Description |
|---|---|---|
| `site:twitter.com` | `site:twitter.com "confidential"` | Twitter posts |
| `site:x.com` | `site:x.com intext:"password"` | X.com posts |
| `site:facebook.com/posts/` | `site:facebook.com/posts/` | Facebook posts |
| `site:instagram.com/p/` | `site:instagram.com/p/` | Instagram posts |
| `site:reddit.com` | `site:reddit.com intext:"leak"` | Reddit posts |
| `site:pastebin.com` | `site:pastebin.com intext:password` | Pastebin pastes |
| `site:paste.ee` | `site:paste.ee intext:password` | Paste.ee pastes |
| `site:ghostbin.com` | `site:ghostbin.com` | Ghostbin pastes |
| `site:rentry.co` | `site:rentry.co intext:password` | Rentry pastes |
| `site:hastebin.com` | `site:hastebin.com` | Hastebin pastes |
| `site:youtube.com/channel/` | `site:youtube.com/channel/` | YouTube channels |
| `site:tiktok.com/@` | `site:tiktok.com/@` | TikTok profiles |
| `site:t.me` | `site:t.me` | Telegram channels |
| `site:discord.gg` | `site:discord.gg` | Discord invites |
| `site:discord.com/channels` | `site:discord.com/channels` | Discord channels |
| `site:github.com` | `site:github.com intext:password` | GitHub pages |
| `site:gist.github.com` | `site:gist.github.com intext:password` | GitHub gists |
| `site:pastebin.pl` | `site:pastebin.pl` | Polish Pastebin |
| `site:justpaste.it` | `site:justpaste.it intext:password` | JustPaste pastes |
| `site:dpaste.com` | `site:dpaste.com` | Dpaste pastes |

---

## 🏢 Corporate Intelligence

> Gather intelligence about organizations — internal documents, org charts, and more.

| Dork | Example Usage | Description |
|---|---|---|
| `site:company.com filetype:pdf` | `site:target.com filetype:pdf` | Company PDFs |
| `site:company.com intext:confidential` | `site:target.com intext:confidential` | Confidential company docs |
| `site:company.com intext:internal` | `site:target.com intext:internal` | Internal company docs |
| `site:company.com intext:employee` | `site:target.com intext:employee list` | Employee lists |
| `site:company.com intext:salary` | `site:target.com intext:salary` | Salary info |
| `site:company.com filetype:xls` | `site:target.com filetype:xls` | Company spreadsheets |
| `site:company.com inurl:login` | `site:target.com inurl:login` | Company login pages |
| `site:company.com inurl:admin` | `site:target.com inurl:admin` | Company admin pages |
| `site:company.com intext:password` | `site:target.com intext:password` | Company passwords |
| `site:company.com filetype:log` | `site:target.com filetype:log` | Company log files |
| `"@company.com" intext:password` | `"@target.com" intext:password` | Corp email+password |
| `"@company.com" filetype:xls` | `"@target.com" filetype:xls` | Corp email lists |
| `intext:"company name" intext:budget filetype:pdf` | `intext:"Acme Corp" intext:budget filetype:pdf` | Company budget docs |
| `intext:"org chart"` | `intext:"org chart" filetype:pdf` | Organization charts |
| `intext:"organizational chart"` | `intext:"organizational chart"` | Org charts |
| `intext:"company directory"` | `intext:"company directory"` | Company directories |
| `intext:"staff directory"` | `intext:"staff directory"` | Staff directories |
| `intext:"employee directory"` | `intext:"employee directory"` | Employee directories |
| `intext:"phone directory"` | `intext:"phone directory" filetype:pdf` | Phone directories |
| `intext:"email directory"` | `intext:"email directory" filetype:pdf` | Email directories |

---

## 📍 Geolocation & Maps

> Location data, GPS files, and mapping information.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:gpx` | `filetype:gpx` | GPS exchange files |
| `filetype:kml` | `filetype:kml` | Google Earth KML |
| `filetype:kmz` | `filetype:kmz` | Google Earth KMZ |
| `filetype:loc` | `filetype:loc` | GPS location files |
| `filetype:geojson` | `filetype:geojson` | GeoJSON data files |
| `filetype:shp` | `filetype:shp` | Shapefile GIS data |
| `inurl:openstreetmap` | `inurl:openstreetmap` | OpenStreetMap data |
| `intitle:MapServer` | `intitle:MapServer` | MapServer interfaces |
| `intitle:"static map"` | `intitle:"static map"` | Static map pages |
| `intext:"AIza" inurl:maps` | `intext:"AIza" inurl:maps` | Google Maps API keys |
| `inurl:maps.google.com` | `inurl:maps.google.com` | Google Maps links |
| `filetype:csv intext:latitude` | `filetype:csv intext:latitude longitude` | CSV location data |
| `filetype:csv intext:longitude` | `filetype:csv intext:longitude` | CSV with coordinates |
| `intext:"GPS coordinates"` | `intext:"GPS coordinates" filetype:txt` | GPS coordinate files |
| `intext:"lat=" intext:"lon="` | `intext:"lat=" intext:"lon="` | Lat/lon data |
| `filetype:gpx intext:trk` | `filetype:gpx intext:trk` | GPX track files |
| `filetype:kml intext:coordinates` | `filetype:kml intext:coordinates` | KML coordinate files |
| `intitle:"ESRI" inurl:gis` | `intitle:"ESRI" inurl:gis` | ESRI GIS servers |
| `intitle:"ArcGIS"` | `intitle:"ArcGIS" inurl:login` | ArcGIS portals |
| `intitle:"QGIS Server"` | `intitle:"QGIS Server"` | QGIS map server |

---

## 💻 Code & Repositories

> Find source code, repositories, and version control data.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:.git/config` | `inurl:.git/config` | Git config file |
| `inurl:.git/HEAD` | `inurl:.git/HEAD` | Git HEAD file |
| `inurl:.git/index` | `inurl:.git/index` | Git index file |
| `inurl:.git/logs` | `inurl:.git/logs` | Git log files |
| `inurl:.git/refs` | `inurl:.git/refs` | Git refs |
| `inurl:.git/objects` | `inurl:.git/objects` | Git objects |
| `inurl:.svn/entries` | `inurl:.svn/entries` | SVN entries |
| `inurl:.svn/wc.db` | `inurl:.svn/wc.db` | SVN working copy |
| `inurl:.hg/requires` | `inurl:.hg/requires` | Mercurial files |
| `inurl:.hg/store` | `inurl:.hg/store` | Mercurial store |
| `site:github.com intext:password` | `site:github.com intext:password filetype:txt` | GitHub passwords |
| `site:github.com intext:api_key` | `site:github.com intext:api_key` | GitHub API keys |
| `site:github.com intext:secret` | `site:github.com intext:secret` | GitHub secrets |
| `site:github.com filetype:env` | `site:github.com filetype:env` | GitHub ENV files |
| `site:gitlab.com intext:password` | `site:gitlab.com intext:password` | GitLab passwords |
| `site:bitbucket.org intext:password` | `site:bitbucket.org intext:password` | Bitbucket passwords |
| `filetype:py intext:password` | `filetype:py intext:password` | Python password files |
| `filetype:js intext:password` | `filetype:js intext:password` | JS password files |
| `filetype:rb intext:password` | `filetype:rb intext:password` | Ruby password files |
| `filetype:java intext:password` | `filetype:java intext:password` | Java password files |
| `filetype:go intext:password` | `filetype:go intext:password` | Go password files |
| `filetype:php intext:password` | `filetype:php intext:password` | PHP password files |
| `filetype:sh intext:password` | `filetype:sh intext:password` | Shell script passwords |
| `filetype:ps1 intext:password` | `filetype:ps1 intext:password` | PowerShell passwords |
| `filetype:py intext:api_key` | `filetype:py intext:api_key` | Python API keys |
| `filetype:js intext:api_key` | `filetype:js intext:api_key` | JS API keys |
| `filetype:js intext:token` | `filetype:js intext:token` | JS token files |
| `filetype:json intext:token` | `filetype:json intext:token` | JSON tokens |
| `inurl:Makefile` | `inurl:Makefile intext:password` | Makefile credentials |
| `inurl:Dockerfile` | `inurl:Dockerfile intext:password` | Dockerfile secrets |

---

## 🐛 Debug & Developer Tools

> Development and debugging interfaces that should never be publicly accessible.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:php intext:phpinfo()` | `filetype:php intext:phpinfo()` | PHP info pages |
| `inurl:phpinfo.php` | `inurl:phpinfo.php` | PHP info URL |
| `intitle:"PHP Version"` | `intitle:"PHP Version"` | PHP version pages |
| `intitle:"Debug Bar"` | `intitle:"Debug Bar"` | Debug bars |
| `inurl:_debugbar` | `inurl:_debugbar` | Laravel debugbar |
| `inurl:debug_toolbar` | `inurl:debug_toolbar` | Django debug toolbar |
| `inurl:debug/` | `inurl:debug/` | Debug URL paths |
| `inurl:actuator` | `inurl:actuator` | Spring Boot actuator |
| `inurl:actuator/env` | `inurl:actuator/env` | Spring Boot env dump |
| `inurl:actuator/health` | `inurl:actuator/health` | Spring health check |
| `inurl:actuator/beans` | `inurl:actuator/beans` | Spring beans dump |
| `inurl:trace.axd` | `inurl:trace.axd` | ASP.NET trace viewer |
| `inurl:elmah.axd` | `inurl:elmah.axd` | ASP.NET error logger |
| `intitle:"Kibana"` | `intitle:"Kibana"` | Kibana dashboards |
| `intitle:"Grafana"` | `intitle:"Grafana"` | Grafana dashboards |
| `intitle:"Prometheus"` | `intitle:"Prometheus"` | Prometheus metrics |
| `inurl:9090` | `inurl:9090 intitle:Prometheus` | Prometheus port |
| `intitle:"Jaeger"` | `intitle:"Jaeger" inurl:ui` | Jaeger tracing |
| `intitle:"Zipkin"` | `intitle:"Zipkin"` | Zipkin tracing |
| `intitle:"Datadog"` | `intitle:"Datadog" inurl:dashboard` | Datadog dashboards |
| `intitle:"New Relic"` | `intitle:"New Relic"` | New Relic APM |
| `inurl:/_profiler` | `inurl:/_profiler` | Symfony profiler |
| `inurl:/__debug__` | `inurl:/__debug__` | Django debug |
| `intitle:"Sentry"` | `intitle:"Sentry" inurl:login` | Sentry error tracking |
| `intitle:"Loggly"` | `intitle:"Loggly"` | Loggly log mgmt |
| `intitle:"Splunk"` | `intitle:"Splunk" inurl:login` | Splunk SIEM |
| `intitle:"Graylog"` | `intitle:"Graylog"` | Graylog log mgmt |
| `intitle:"ELK Stack"` | `intitle:"ELK Stack"` | ELK stack |
| `inurl:/_cluster/health` | `inurl:/_cluster/health` | Elasticsearch health |
| `inurl:/_nodes` | `inurl:/_nodes` | Elasticsearch nodes |

---

## 🔌 API Endpoints

> Find publicly exposed API documentation, endpoints, and specifications.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:swagger-ui.html` | `inurl:swagger-ui.html` | Swagger UI |
| `inurl:swagger-ui` | `inurl:swagger-ui` | Swagger interfaces |
| `inurl:/api-docs` | `inurl:/api-docs` | API documentation |
| `inurl:/api/docs` | `inurl:/api/docs` | API docs |
| `inurl:/api/v1` | `inurl:/api/v1` | API v1 endpoints |
| `inurl:/api/v2` | `inurl:/api/v2` | API v2 endpoints |
| `inurl:/api/v3` | `inurl:/api/v3` | API v3 endpoints |
| `filetype:json intext:swagger` | `filetype:json intext:swagger` | OpenAPI JSON specs |
| `filetype:yaml intext:swagger` | `filetype:yaml intext:swagger` | OpenAPI YAML specs |
| `filetype:json intext:openapi` | `filetype:json intext:openapi` | OpenAPI 3.0 specs |
| `filetype:json intext:postman` | `filetype:json intext:postman` | Postman collections |
| `inurl:graphql` | `inurl:graphql` | GraphQL endpoints |
| `inurl:/graphql` | `inurl:/graphql` | GraphQL root |
| `inurl:graphiql` | `inurl:graphiql` | GraphiQL explorer |
| `inurl:wsdl` | `inurl:wsdl` | SOAP WSDL files |
| `filetype:wsdl` | `filetype:wsdl` | WSDL files |
| `inurl:odata` | `inurl:odata` | OData endpoints |
| `inurl:/rest/api` | `inurl:/rest/api` | REST API paths |
| `inurl:webhook` | `inurl:webhook` | Webhook endpoints |
| `intitle:"ReDoc"` | `intitle:"ReDoc"` | ReDoc API docs |
| `intitle:"API Reference"` | `intitle:"API Reference"` | API reference pages |
| `intext:"application/json" inurl:api` | `intext:"application/json" inurl:api` | JSON API responses |
| `intext:"Bearer" filetype:json` | `intext:"Bearer" filetype:json` | Bearer auth JSON |
| `inurl:/v1/keys` | `inurl:/v1/keys` | API key endpoints |
| `inurl:/v1/users` | `inurl:/v1/users` | User API endpoints |
| `inurl:/v1/admin` | `inurl:/v1/admin` | Admin API endpoints |

---

## ☁️ Cloud & Storage

> Find files and data exposed in cloud storage services.

| Dork | Example Usage | Description |
|---|---|---|
| `site:s3.amazonaws.com` | `site:s3.amazonaws.com` | AWS S3 buckets |
| `inurl:s3.amazonaws.com` | `inurl:s3.amazonaws.com filetype:pdf` | S3 bucket files |
| `site:storage.googleapis.com` | `site:storage.googleapis.com` | GCP storage |
| `inurl:storage.googleapis.com` | `inurl:storage.googleapis.com` | GCS files |
| `site:blob.core.windows.net` | `site:blob.core.windows.net` | Azure Blob storage |
| `inurl:blob.core.windows.net` | `inurl:blob.core.windows.net` | Azure blob files |
| `site:dropbox.com/s/` | `site:dropbox.com/s/` | Dropbox shared links |
| `site:drive.google.com` | `site:drive.google.com` | Google Drive files |
| `site:onedrive.live.com` | `site:onedrive.live.com` | OneDrive files |
| `site:box.com/s/` | `site:box.com/s/` | Box shared files |
| `site:mega.nz` | `site:mega.nz` | Mega.nz links |
| `site:mediafire.com` | `site:mediafire.com` | MediaFire files |
| `site:wetransfer.com` | `site:wetransfer.com` | WeTransfer links |
| `site:sendspace.com` | `site:sendspace.com` | SendSpace files |
| `site:file.io` | `site:file.io` | File.io links |
| `site:anonfiles.com` | `site:anonfiles.com` | AnonFiles |
| `intext:"s3.amazonaws.com" intext:password` | `intext:"s3.amazonaws.com" intext:password` | S3 URL with password |
| `intext:"bucket_name"` | `intext:"bucket_name" filetype:json` | S3 bucket names |
| `intext:"azure_storage"` | `intext:"azure_storage" intext:key` | Azure storage keys |
| `intext:"gcs_bucket"` | `intext:"gcs_bucket" filetype:yml` | GCS bucket configs |
| `intext:"CloudFront"` | `intext:"CloudFront" intext:password` | CloudFront configs |
| `intext:"DO_SPACES_KEY"` | `intext:"DO_SPACES_KEY" filetype:env` | DigitalOcean Spaces |
| `intext:"WASABI_ACCESS_KEY"` | `intext:"WASABI_ACCESS_KEY"` | Wasabi storage keys |
| `intext:"B2_APPLICATION_KEY"` | `intext:"B2_APPLICATION_KEY"` | Backblaze B2 keys |
| `intext:"R2_ACCESS_KEY"` | `intext:"R2_ACCESS_KEY"` | Cloudflare R2 keys |

---

## 💳 Financial Documents

> Financial records, bank statements, and payment information.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:pdf intext:"bank statement"` | `filetype:pdf intext:"bank statement"` | Bank statements |
| `filetype:pdf intext:"account statement"` | `filetype:pdf intext:"account statement"` | Account statements |
| `filetype:pdf intext:"credit card"` | `filetype:pdf intext:"credit card" number` | Credit card docs |
| `filetype:pdf intext:invoice` | `filetype:pdf intext:invoice total` | Invoice PDFs |
| `filetype:xls intext:payroll` | `filetype:xls intext:payroll` | Payroll sheets |
| `filetype:pdf intext:"tax return"` | `filetype:pdf intext:"tax return"` | Tax returns |
| `filetype:pdf intext:"tax form"` | `filetype:pdf intext:"tax form"` | Tax form documents |
| `filetype:pdf intext:"W-2"` | `filetype:pdf intext:"W-2"` | W-2 tax forms |
| `filetype:pdf intext:"1099"` | `filetype:pdf intext:"1099"` | 1099 forms |
| `filetype:pdf intext:"financial report"` | `filetype:pdf intext:"financial report"` | Financial reports |
| `filetype:pdf intext:"balance sheet"` | `filetype:pdf intext:"balance sheet"` | Balance sheets |
| `filetype:pdf intext:"income statement"` | `filetype:pdf intext:"income statement"` | Income statements |
| `filetype:pdf intext:"cash flow"` | `filetype:pdf intext:"cash flow"` | Cash flow statements |
| `filetype:pdf intext:"audit report"` | `filetype:pdf intext:"audit report"` | Financial audit reports |
| `filetype:pdf intext:"loan application"` | `filetype:pdf intext:"loan application"` | Loan applications |
| `filetype:pdf intext:mortgage` | `filetype:pdf intext:mortgage` | Mortgage documents |
| `filetype:pdf intext:investment` | `filetype:pdf intext:investment` | Investment docs |
| `filetype:pdf intext:"portfolio"` | `filetype:pdf intext:"portfolio"` | Financial portfolios |
| `filetype:pdf intext:"annual report"` | `filetype:pdf intext:"annual report"` | Company annual reports |
| `inurl:paypal.com` | `inurl:paypal.com` | PayPal links |
| `inurl:stripe.com` | `inurl:stripe.com` | Stripe pages |
| `intext:"routing number"` | `intext:"routing number" filetype:pdf` | Bank routing numbers |
| `intext:"IBAN" filetype:pdf` | `intext:"IBAN" filetype:pdf` | IBAN documents |
| `intext:"SWIFT code"` | `intext:"SWIFT code" filetype:pdf` | SWIFT code docs |
| `intext:"wire transfer"` | `intext:"wire transfer" filetype:pdf` | Wire transfer docs |

---

## ⚖️ Legal & Contracts

> Legal documents, contracts, and court records.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:pdf intext:contract` | `filetype:pdf intext:contract` | Legal contracts |
| `filetype:pdf intext:agreement` | `filetype:pdf intext:agreement` | Agreement documents |
| `filetype:pdf intext:nda` | `filetype:pdf intext:nda` | NDA documents |
| `filetype:pdf intext:"non-disclosure"` | `filetype:pdf intext:"non-disclosure"` | NDA full text |
| `filetype:pdf intext:settlement` | `filetype:pdf intext:settlement` | Settlement docs |
| `filetype:pdf intext:lawsuit` | `filetype:pdf intext:lawsuit` | Lawsuit documents |
| `filetype:pdf intext:litigation` | `filetype:pdf intext:litigation` | Litigation documents |
| `filetype:pdf intext:"court order"` | `filetype:pdf intext:"court order"` | Court orders |
| `filetype:pdf intext:subpoena` | `filetype:pdf intext:subpoena` | Subpoena documents |
| `filetype:pdf intext:warrant` | `filetype:pdf intext:warrant` | Legal warrants |
| `filetype:pdf intext:"terms of service"` | `filetype:pdf intext:"terms of service"` | TOS documents |
| `filetype:pdf intext:"privacy policy"` | `filetype:pdf intext:"privacy policy"` | Privacy policies |
| `filetype:pdf intext:"intellectual property"` | `filetype:pdf intext:"intellectual property"` | IP agreements |
| `filetype:pdf intext:"cease and desist"` | `filetype:pdf intext:"cease and desist"` | C&D letters |
| `filetype:pdf intext:"power of attorney"` | `filetype:pdf intext:"power of attorney"` | POA documents |
| `filetype:pdf intext:"affidavit"` | `filetype:pdf intext:"affidavit"` | Affidavits |
| `filetype:pdf intext:deposition` | `filetype:pdf intext:deposition` | Deposition docs |
| `filetype:pdf intext:"GDPR"` | `filetype:pdf intext:"GDPR"` | GDPR compliance docs |
| `filetype:pdf intext:"HIPAA"` | `filetype:pdf intext:"HIPAA"` | HIPAA documents |
| `filetype:pdf intext:"CCPA"` | `filetype:pdf intext:"CCPA"` | CCPA compliance docs |

---

## 🏥 Healthcare & Medical

> Medical records, patient data, and healthcare systems.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:pdf intext:"patient name"` | `filetype:pdf intext:"patient name"` | Patient PDFs |
| `filetype:pdf intext:"medical report"` | `filetype:pdf intext:"medical report"` | Medical reports |
| `filetype:pdf intext:prescription` | `filetype:pdf intext:prescription` | Prescription docs |
| `filetype:pdf intext:"lab result"` | `filetype:pdf intext:"lab result"` | Lab results |
| `filetype:pdf intext:"discharge summary"` | `filetype:pdf intext:"discharge summary"` | Discharge summaries |
| `filetype:pdf intext:"medical history"` | `filetype:pdf intext:"medical history"` | Medical history |
| `filetype:pdf intext:"patient record"` | `filetype:pdf intext:"patient record"` | Patient records |
| `filetype:pdf intext:diagnosis` | `filetype:pdf intext:diagnosis` | Diagnosis docs |
| `filetype:pdf intext:treatment` | `filetype:pdf intext:treatment` | Treatment plans |
| `filetype:pdf intext:"clinical trial"` | `filetype:pdf intext:"clinical trial"` | Clinical trial docs |
| `intitle:hospital inurl:patient` | `intitle:hospital inurl:patient` | Hospital patient portals |
| `inurl:epic` | `inurl:epic inurl:login` | EPIC healthcare |
| `inurl:cerner` | `inurl:cerner inurl:login` | Cerner portals |
| `inurl:allscripts` | `inurl:allscripts` | Allscripts systems |
| `inurl:meditech` | `inurl:meditech` | Meditech systems |
| `inurl:nextgen` | `inurl:nextgen inurl:login` | NextGen health |
| `intitle:"Patient Portal"` | `intitle:"Patient Portal"` | Patient portals |
| `intitle:"Electronic Health Record"` | `intitle:"Electronic Health Record"` | EHR systems |
| `intext:HIPAA intext:patient` | `intext:HIPAA intext:patient filetype:pdf` | HIPAA patient docs |
| `filetype:hl7` | `filetype:hl7` | HL7 health data |

---

## 🎓 Education & Academic

> Educational materials, student records, and academic institutions.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:pdf intext:"lecture notes" site:edu` | `filetype:pdf intext:"lecture notes" site:edu` | Lecture notes |
| `filetype:pdf intext:syllabus site:edu` | `filetype:pdf intext:syllabus site:edu` | Course syllabi |
| `filetype:pdf intext:"exam" site:edu` | `filetype:pdf intext:"exam" site:edu` | Exam papers |
| `filetype:pdf intext:thesis site:edu` | `filetype:pdf intext:thesis site:edu` | Thesis documents |
| `filetype:pdf intext:dissertation site:edu` | `filetype:pdf intext:dissertation site:edu` | Dissertations |
| `filetype:xls intext:grade site:edu` | `filetype:xls intext:grade site:edu` | Grade spreadsheets |
| `filetype:xls intext:student site:edu` | `filetype:xls intext:student site:edu` | Student lists |
| `intitle:"Moodle" inurl:login` | `intitle:"Moodle" inurl:login` | Moodle LMS |
| `intitle:"Canvas" inurl:login` | `intitle:"Canvas" inurl:login` | Canvas LMS |
| `intitle:"Blackboard" inurl:login` | `intitle:"Blackboard" inurl:login` | Blackboard LMS |
| `intitle:"Brightspace"` | `intitle:"Brightspace" inurl:login` | D2L Brightspace |
| `intitle:"Schoology"` | `intitle:"Schoology"` | Schoology LMS |
| `intitle:"Google Classroom"` | `intitle:"Google Classroom"` | Google Classroom |
| `intitle:"Edmodo"` | `intitle:"Edmodo"` | Edmodo platform |
| `inurl:admin site:edu` | `inurl:admin site:edu` | Edu admin pages |
| `inurl:login site:edu` | `inurl:login site:edu` | Edu login pages |
| `filetype:pdf intext:"scholarship" site:edu` | `filetype:pdf intext:"scholarship" site:edu` | Scholarship docs |
| `filetype:pdf intext:"financial aid" site:edu` | `filetype:pdf intext:"financial aid" site:edu` | Financial aid |
| `filetype:pdf intext:"enrollment" site:edu` | `filetype:pdf intext:"enrollment" site:edu` | Enrollment docs |
| `site:edu filetype:sql` | `site:edu filetype:sql` | Edu database files |

---

## 📰 News & Media

> News feeds, APIs, and media content.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:wp-json/wp/v2/posts` | `inurl:wp-json/wp/v2/posts` | WordPress REST API |
| `inurl:wp-json/wp/v2/users` | `inurl:wp-json/wp/v2/users` | WordPress user API |
| `filetype:rss` | `filetype:rss` | RSS feed files |
| `filetype:atom` | `filetype:atom` | Atom feed files |
| `inurl:sitemap.xml` | `inurl:sitemap.xml` | XML sitemaps |
| `inurl:news-sitemap.xml` | `inurl:news-sitemap.xml` | News sitemaps |
| `intext:newsapi.org` | `intext:newsapi.org intext:apikey` | News API keys |
| `site:cnn.com inurl:news` | `site:cnn.com inurl:news "leak"` | CNN news search |
| `site:bbc.com inurl:news` | `site:bbc.com inurl:news` | BBC news search |
| `site:reuters.com inurl:article` | `site:reuters.com inurl:article` | Reuters articles |
| `site:apnews.com` | `site:apnews.com` | AP News |
| `site:aljazeera.com` | `site:aljazeera.com` | Al Jazeera |
| `inurl:rss.xml` | `inurl:rss.xml` | RSS XML files |
| `inurl:feed.xml` | `inurl:feed.xml` | Feed XML files |
| `intitle:"RSS"` | `intitle:"RSS" inurl:feed` | RSS feed pages |
| `intext:"podcastMediaType"` | `intext:"podcastMediaType"` | Podcast feeds |
| `filetype:xml intext:rss` | `filetype:xml intext:rss` | RSS XML files |
| `filetype:xml intext:atom` | `filetype:xml intext:atom` | Atom XML feeds |
| `inurl:api intext:news` | `inurl:api intext:news` | News API endpoints |
| `intitle:"press release"` | `intitle:"press release" filetype:pdf` | Press releases |

---

## 🛒 E-Commerce

> Online stores, payment systems, and shopping platforms.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:wp-content/plugins/woocommerce` | `inurl:wp-content/plugins/woocommerce` | WooCommerce sites |
| `inurl:app/code/core/Mage` | `inurl:app/code/core/Mage` | Magento sites |
| `inurl:modules/prestashop` | `inurl:modules/prestashop` | PrestaShop sites |
| `intext:Shopify inurl:product` | `intext:Shopify inurl:product` | Shopify stores |
| `inurl:index.php?route=common/home` | `inurl:index.php?route=common/home` | OpenCart stores |
| `intitle:"Zen Cart"` | `intitle:"Zen Cart"` | Zen Cart stores |
| `inurl:bigcommerce` | `inurl:bigcommerce` | BigCommerce |
| `intitle:"Wix" inurl:store` | `intitle:"Wix" inurl:store` | Wix stores |
| `inurl:shop/admin` | `inurl:shop/admin` | Shop admin URLs |
| `inurl:store/admin` | `inurl:store/admin` | Store admin |
| `intext:"Powered by Shopify"` | `intext:"Powered by Shopify"` | Shopify-powered sites |
| `intext:"Powered by WooCommerce"` | `intext:"Powered by WooCommerce"` | WooCommerce sites |
| `intext:"Powered by PrestaShop"` | `intext:"Powered by PrestaShop"` | PrestaShop-powered |
| `intext:"Powered by Magento"` | `intext:"Powered by Magento"` | Magento-powered |
| `inurl:cart` | `inurl:cart intext:checkout` | Shopping cart pages |
| `inurl:checkout` | `inurl:checkout intext:payment` | Checkout pages |
| `intext:"stripe publishable key"` | `intext:"stripe publishable key"` | Stripe PK exposed |
| `intext:"paypal.me/"` | `intext:"paypal.me/" intext:send` | PayPal.me links |
| `filetype:xls intext:product intext:price` | `filetype:xls intext:product intext:price` | Product price sheets |
| `inurl:magento/admin` | `inurl:magento/admin` | Magento admin panels |

---

## 🛡️ Vulnerability & Security

> Security research, vulnerability reports, and exposed security tools.

| Dork | Example Usage | Description |
|---|---|---|
| `filetype:txt intext:CVE-202` | `filetype:txt intext:CVE-202` | CVE text files |
| `filetype:pdf intext:Nessus` | `filetype:pdf intext:Nessus` | Nessus scan reports |
| `filetype:pdf intext:OpenVAS` | `filetype:pdf intext:OpenVAS` | OpenVAS reports |
| `filetype:pdf intext:"penetration test"` | `filetype:pdf intext:"penetration test"` | Pentest reports |
| `filetype:pdf intext:"vulnerability scan"` | `filetype:pdf intext:"vulnerability scan"` | Vuln scan reports |
| `filetype:pdf intext:"security audit"` | `filetype:pdf intext:"security audit"` | Security audits |
| `filetype:pdf intext:OWASP` | `filetype:pdf intext:OWASP` | OWASP documents |
| `filetype:pdf intext:"risk assessment"` | `filetype:pdf intext:"risk assessment"` | Risk assessments |
| `filetype:pdf intext:"threat model"` | `filetype:pdf intext:"threat model"` | Threat models |
| `filetype:txt intext:exploit` | `filetype:txt intext:exploit` | Exploit text files |
| `filetype:txt intext:"proof of concept"` | `filetype:txt intext:"proof of concept"` | PoC files |
| `inurl:burp` | `inurl:burp intext:report` | Burp Suite reports |
| `intitle:"Shodan"` | `intitle:"Shodan"` | Shodan-related pages |
| `inurl:nmap` | `inurl:nmap intext:scan` | Nmap output files |
| `filetype:xml intext:nmap` | `filetype:xml intext:nmap` | Nmap XML output |
| `intext:"sqlmap"` | `intext:"sqlmap" filetype:txt` | SQLmap output |
| `intext:"metasploit"` | `intext:"metasploit" filetype:txt` | Metasploit outputs |
| `intext:"nikto"` | `intext:"nikto" filetype:txt` | Nikto scan results |
| `intext:"hydra"` | `intext:"hydra" filetype:txt` | Hydra outputs |
| `filetype:pdf intext:"red team"` | `filetype:pdf intext:"red team"` | Red team reports |
| `filetype:pdf intext:"blue team"` | `filetype:pdf intext:"blue team"` | Blue team reports |
| `filetype:pdf intext:"SOC report"` | `filetype:pdf intext:"SOC report"` | SOC 2 reports |
| `filetype:pdf intext:"ISO 27001"` | `filetype:pdf intext:"ISO 27001"` | ISO 27001 docs |
| `filetype:pdf intext:"PCI DSS"` | `filetype:pdf intext:"PCI DSS"` | PCI DSS docs |
| `filetype:pdf intext:"NIST"` | `filetype:pdf intext:"NIST"` | NIST framework docs |

---

## 🔎 CMS & Frameworks

> Identify specific CMS installations, versions, and potential weaknesses.

| Dork | Example Usage | Description |
|---|---|---|
| `inurl:wp-content` | `inurl:wp-content/plugins` | WordPress sites |
| `inurl:wp-login.php` | `inurl:wp-login.php` | WordPress login |
| `inurl:wp-admin` | `inurl:wp-admin` | WordPress admin |
| `intext:"Powered by WordPress"` | `intext:"Powered by WordPress"` | WordPress-powered |
| `intext:"WordPress" intext:"version"` | `intext:"WordPress" intext:"version"` | WordPress version |
| `inurl:joomla` | `inurl:joomla/administrator` | Joomla sites |
| `inurl:administrator intext:Joomla` | `inurl:administrator intext:Joomla` | Joomla admin |
| `intext:"Powered by Joomla"` | `intext:"Powered by Joomla"` | Joomla-powered |
| `inurl:drupal/admin` | `inurl:drupal/admin` | Drupal admin |
| `intext:"Powered by Drupal"` | `intext:"Powered by Drupal"` | Drupal-powered |
| `inurl:user/login intext:Drupal` | `inurl:user/login intext:Drupal` | Drupal login |
| `intext:"Powered by TYPO3"` | `intext:"Powered by TYPO3"` | TYPO3 sites |
| `intext:"Powered by vBulletin"` | `intext:"Powered by vBulletin"` | vBulletin forums |
| `intext:"Powered by phpBB"` | `intext:"Powered by phpBB"` | phpBB forums |
| `intext:"Powered by Discourse"` | `intext:"Powered by Discourse"` | Discourse forums |
| `intext:"Powered by Ghost"` | `intext:"Powered by Ghost"` | Ghost CMS |
| `intext:"Powered by Craft CMS"` | `intext:"Powered by Craft CMS"` | Craft CMS |
| `intext:"Powered by Umbraco"` | `intext:"Powered by Umbraco"` | Umbraco CMS |
| `intext:"Built with Django"` | `intext:"Built with Django"` | Django sites |
| `intext:"Powered by Laravel"` | `intext:"Powered by Laravel"` | Laravel sites |
| `intext:"Ruby on Rails"` | `intext:"Ruby on Rails"` | Rails sites |
| `intext:"ASP.NET"` | `intext:"ASP.NET" intext:version` | ASP.NET sites |
| `inurl:/wp-json` | `inurl:/wp-json intext:users` | WordPress JSON API |
| `inurl:?page_id=` | `inurl:?page_id=` | WordPress URL pattern |
| `inurl:?p=` | `inurl:?p=` | WordPress post URLs |
| `inurl:?cat=` | `inurl:?cat=` | WordPress category URLs |
| `inurl:index.php?option=com_` | `inurl:index.php?option=com_` | Joomla component URLs |
| `inurl:node/ site:example.com` | `inurl:node/ site:example.com` | Drupal node URLs |
| `intext:"Generator" intext:"WordPress"` | `intext:"Generator" intext:"WordPress"` | WP meta generator |
| `intext:"generator" intext:"Joomla"` | `intext:"generator" intext:"Joomla"` | Joomla meta generator |

---

---

## ⚠️ Ethical Use Warning

```
██╗    ██╗ █████╗ ██████╗ ███╗   ██╗██╗███╗   ██╗ ██████╗ 
██║    ██║██╔══██╗██╔══██╗████╗  ██║██║████╗  ██║██╔════╝ 
██║ █╗ ██║███████║██████╔╝██╔██╗ ██║██║██╔██╗ ██║██║  ███╗
██║███╗██║██╔══██║██╔══██╗██║╚██╗██║██║██║╚██╗██║██║   ██║
╚███╔███╔╝██║  ██║██║  ██║██║ ╚████║██║██║ ╚████║╚██████╔╝
 ╚══╝╚══╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝╚═╝  ╚═══╝ ╚═════╝ 
```

### 🚨 Legal Disclaimer

> **This archive is provided for educational, research, and authorized security testing purposes ONLY.**

---

### ✅ Authorized Uses

| Use Case | Description |
|---|---|
| [+] **Security Research** | Studying attack surfaces and exposure risks |
| [+] **Defensive Security** | Finding your own organization's exposed assets |
| [+] **Education** | Learning how search operators work |
| [+] **Authorized Pentesting** | Testing systems you have written permission to test |
| [+] **Journalism & OSINT** | Researching public information lawfully |
| [+] **CTF Challenges** | Capture-the-flag and security competitions |

---

### ❌ Prohibited Uses

| Prohibited Action | Consequence |
|---|---|
| [-] Accessing systems without authorization | Criminal charges in most jurisdictions |
| [-] Collecting personal data without consent | GDPR, CCPA, HIPAA violations |
| [-] Using dorks to exploit vulnerabilities | Computer fraud and abuse laws |
| [-] Selling or distributing found credentials | Criminal prosecution |
| [-] Attacking critical infrastructure | Federal criminal charges |
| [-] Unauthorized data exfiltration | Serious criminal penalties |

---

### 🧠 Responsible Disclosure

If you discover a vulnerability through this research:

1. **Do NOT exploit it** — document it carefully
2. **Contact the organization** — via their security contact or `security@domain.com`
3. **Use bug bounty platforms** — HackerOne, Bugcrowd, Intigriti
4. **Allow remediation time** — typically 90 days before public disclosure
5. **Follow CVD guidelines** — Coordinated Vulnerability Disclosure

---

### 📞 Resources

| Resource | URL |
|---|---|
| Google Hacking Database (GHDB) | https://www.exploit-db.com/google-hacking-database |
| OWASP Testing Guide | https://owasp.org/www-project-web-security-testing-guide/ |
| HackerOne Bug Bounty | https://www.hackerone.com |
| Bugcrowd | https://www.bugcrowd.com |
| Shodan | https://www.shodan.io |
| Censys | https://censys.io |

---

![Ethical Hacking](https://img.shields.io/badge/Ethical-Hacking%20Only-red?style=for-the-badge)
![No Unauthorized Access](https://img.shields.io/badge/No-Unauthorized%20Access-critical?style=for-the-badge)
![Educational](https://img.shields.io/badge/Purpose-Educational-blue?style=for-the-badge)
