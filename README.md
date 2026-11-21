<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=160&section=header&text=Matheus%20Guida&fontSize=42&fontColor=ffffff&fontAlignY=55&desc=Back-end%20Developer&descAlignY=75&descSize=18&descColor=8892b0"/>
</p>
<p align="center">
  Back-end &nbsp;|&nbsp; APIs, internal systems and security &nbsp;|&nbsp; Fatec Americana
</p>
<p align="center">
  Americana - SP, Brazil &nbsp;•&nbsp; On-site and remote
</p>
---
 
I build back-end systems end to end, from database modeling to API integration, testing and release. My main project is an open source mod manager with **46,000+ downloads**, integrated with a third-party REST API and covered by 500+ automated checks. I also co-authored three research papers in 2026 on latency and architecture of generative AI APIs.
 
```java
public class MatheusGuida {
    private final String role = "Back-end Developer";
    private final String[] languages = {
        "Java",
        "TypeScript",
        "PHP",
        "Python",
        "JavaScript",
        "C#"
    };
    private final String[] databases = { "MySQL", "MariaDB", "SQLite" };
 
    public void learning() {
        System.out.println("Spring Boot");
        System.out.println("PostgreSQL");
        System.out.println("Docker & CI/CD");
    }
}
```
 
---
 
## Stack
 
**Languages**
 
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
 
**Databases**
 
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
 
**Frameworks & Runtime**
 
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
 
**Tools**
 
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
 
---
 
## Featured projects
 
### [SPT Mod Manager](https://github.com/Nevek20/SPT_Mod_Manager) &nbsp;·&nbsp; `TypeScript` `Node.js` `Electron` `React`
 
Open source desktop mod manager (MIT) with **46,000+ downloads**, actively maintained with releases driven by real user bug reports.
 
- **Third-party REST API integration**: batched requests, local cache with expiry and rate limiting with backoff on HTTP 429. Checking ~140 installed items dropped from 47s to ~2s
- **Dependency resolution**: one batched API call per page, version compatibility checks, and dependencies installed before the main package
- **Binary metadata parsing**: reads mod identity (GUID, name, author, version, dependencies) straight from .NET assemblies, handling format changes between platform versions
- **Security**: path traversal (zip-slip) validation on `.zip` / `.7z` / `.rar` extraction, external URL allowlist and write protection for core runtime files
- **Large files**: streaming downloads with backpressure, plus a separate extraction path for archives over 3 GB
- **Quality**: 500+ automated checks in 26 test suites, run as a gate before every release
- **Release pipeline**: NSIS installer, semantic versioning, community pull requests and a UI in 7 languages
### [Inventory System (RMA)](https://github.com/Nevek20/Sistema_RMA) &nbsp;·&nbsp; `PHP` `MySQL`
 
Internal web system for CPU inventory control, used by the whole technical and operations team. Cut registration and lookup time by roughly 70% by replacing spreadsheets.
 
- Session login with hashed passwords, admin and operator roles enforced on the server, and CSRF protection on every form
- Prepared statements throughout, login lockout after repeated failures, and an audit log of who did what
- CSV export, dashboard with Chart.js and database backup
### [GameXchange](https://github.com/Nevek20/GameXchange) &nbsp;·&nbsp; `PHP` `MySQL` `JavaScript`
 
Game marketplace built as a team project, with user authentication, CRUD, relational modeling and REST API integration between front-end and back-end.
 
### [Vendas Informática](https://github.com/Nevek20/Vendas_informatica) &nbsp;·&nbsp; `PHP` `MySQL`
 
B2B-style sales system with full CRUD for products and orders.
 
---
 
## Research
 
Co-author of three undergraduate research papers in 2026, all with Python prototypes and benchmarks:
 
- **Latency management in generative AI APIs**: semantic cache vs. async queues vs. streaming. SIICUSP 2026 (USP) &nbsp;·&nbsp; [repo](https://github.com/Nevek20/USP)
- **Auditable infrastructure for generative AI under LGPD**: hash-chained audit log and data lineage. Unicamp Undergraduate Research Congress 2026
- **Architectures for LLM applications**: monolith vs. SOA vs. microservices, load tested up to 200 req/s. Fatec 2026
---
 
## Currently learning
 
- **Java and Spring Boot**: building a back-end for the SPT Mod Manager ecosystem
- **PostgreSQL, Docker and CI/CD**
- *IBM Java Developer* certification in progress
<sub>Completed certifications: Python for Everybody Specialization (University of Michigan) · Introduction to Software Engineering (IBM) · Java Programming for Beginners (IBM) · Getting Started with Linux (Red Hat)</sub>
 
---
 
## Contact
 
<p align="center">
  <a href="https://linkedin.com/in/matheus-guida2">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:matheus.guida.08@hotmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=maildotru&logoColor=white"/>
  </a>
</p>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=80&section=footer"/>
</p>
<p align="center">
  <i>si vis pacem, para bellum.</i>
</p>
 
