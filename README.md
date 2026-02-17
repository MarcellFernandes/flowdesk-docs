# 📚 FlowDesk Documentation

[![DITA-OT](https://img.shields.io/badge/DITA--OT-4.4-green.svg)](https://www.dita-ot.org/) 
[![Documentation](https://img.shields.io/badge/documentation-technical-blue.svg)](#) 
[![Status](https://img.shields.io/badge/status-fictional%20project-purple.svg)](#)

**FlowDesk** is a fictional **Incident & Service Management Platform** created as a portfolio project to demonstrate professional **Technical Writing** practices using **DITA (Darwin Information Typing Architecture)**.

Live demo: [https://marcellfernandes.github.io/flowdesk-docs/](https://marcellfernandes.github.io/flowdesk-docs/)

---

## 📖 About the Project

This repository contains structured documentation for FlowDesk, including:

- **Conceptual topics**: Platform overview, incident lifecycle, service levels  
- **Procedures / tasks**: Creating incidents, ticket escalation, SLA configuration  
- **Reference material**: Incident states, priority & SLA matrices  
- **Reusable content**: Notes, warnings, shared snippets  

The project showcases:

- Topic-based authoring with **concepts, tasks, and references**  
- Information architecture for multi-audience documentation  
- Procedural clarity and troubleshooting workflows  
- HTML output with **custom styling** using DITA-OT  

---

## 📁 Repository Structure

```
flowdesk-docs/
├── flowDesk.ditamap        # Main DITA map (documentation structure)
├── custom.css              # Custom stylesheet for HTML output
│
├── concepts/               # Conceptual topics
│   ├── platform-overview.dita
│   ├── incident-lifecycle.dita
│   └── service-levels.dita
│
├── tasks/                  # How-to guides and procedures
│   ├── create-incident.dita
│   ├── escalate-ticket.dita
│   └── configure-sla.dita
│
├── reference/              # Reference materials
│   ├── incident-states.dita
│   ├── priority-matrix.dita
│   └── sla-matrix.dita
│
├── shared/                 # Reusable content components
│   ├── notes.dita
│   └── warnings.dita
│
└── output/                 # Generated HTML (local builds)
    └── index.html
```

---

## 🛠️ Building the Documentation

### Prerequisites
- **DITA Open Toolkit** (v4.4 or later)  
- **Java Runtime Environment** (JRE 8+)

### Local Build

```bash
# Windows (adjust path to your DITA-OT installation)
C:\dita-ot-4.4\bin\dita.bat -i flowDesk.ditamap -f html5 -o output -Dargs.css=custom.css

# Linux / macOS
~/dita-ot-4.4/bin/dita -i flowDesk.ditamap -f html5 -o output -Dargs.css=custom.css
```

After building, open `output/index.html` in your browser.

### Quick Build Script

**Windows (build.bat):**
```batch
@echo off
C:\dita-ot-4.4\bin\dita.bat -i flowDesk.ditamap -f html5 -o output -Dargs.css=custom.css
echo Build complete! Open output/index.html
```

**Linux / macOS (build.sh):**
```bash
#!/bin/bash
~/dita-ot-4.4/bin/dita -i flowDesk.ditamap -f html5 -o output -Dargs.css=custom.css
echo "Build complete! Open output/index.html"
```

---

## 🌐 Publishing

### GitHub Pages (Manual)
1. Build the HTML locally (`output/`)  
2. Copy contents of `output/` to a `docs/` folder in the repo **or** use a separate `gh-pages` branch  
3. Enable GitHub Pages in repository settings

### GitHub Pages + Actions (Automated)
Use a DITA GitHub Actions workflow template for automated builds on every push.

---

## 📝 Skills Demonstrated

| Skill                    | Application |
|---------------------------|------------|
| **DITA XML**              | Topic-based authoring (concepts, tasks, references) |
| **Information Architecture** | Structured documentation following DITA standards |
| **Technical Writing**     | Clear, concise procedures and conceptual explanations |
| **Documentation Styling** | Custom CSS for HTML output |
| **Version Control**       | Git and GitHub for documentation management |
| **Build Automation**      | DITA-OT command-line usage |

---

## 📬 Contact

**Marcell Vaz Fernandes — Technical Writer**  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcell-vaz-fernandes/)  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/marcellfernandes)  
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:marcell.fernandes56@gmail.com)  

📍 Rio de Janeiro, Brazil

---

> ⚠ **Note:** FlowDesk is a fictional portfolio project created to demonstrate technical writing, DITA, and information architecture skills.
