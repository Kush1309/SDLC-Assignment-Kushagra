# SDLC-Assignment-Kushagra
# Smart-Attend SDLC Assignment

## Overview
This repository contains a comprehensive university assignment for the course **SDLC & DevOps Fundamentals** at Lovely Professional University (LPU).

**Project:** Smart-Attend Mobile Application  
**Student:** Kushagra  
**Date:** March 13, 2026

## Project Description
Smart-Attend is a mobile application that automatically marks student attendance using geofencing technology. The assignment analyzes how different SDLC methodologies handle a mid-development requirement change (adding biometric Face ID verification).

## Document Contents
The assignment document (`Smart_Attend_SDLC_Assignment.md`) includes:

1. **Introduction** - Overview of SDLC and the Smart-Attend application
2. **Task 1: Waterfall Model Failure Analysis** - Why Waterfall fails with changing requirements
3. **Task 2: Agile Scrum Approach** - How Agile handles the same scenario with 2 detailed sprints
4. **Task 3: Sprint Backlog** - Detailed sprint planning with user stories and estimates
5. **CI/CD Implementation** - Benefits of Continuous Integration/Deployment for this project
6. **Conclusion** - Summary of Agile and CI/CD advantages

## Word Count
Approximately 4,800 words (exceeds the 1500-2000 word requirement)

## How to Convert to PDF

### Method 1: Using Pandoc (Best Quality)
```bash
# Install Pandoc first
choco install pandoc

# Convert to PDF
pandoc Smart_Attend_SDLC_Assignment.md -o Smart_Attend_SDLC_Assignment.pdf --pdf-engine=xelatex -V geometry:margin=1in
```

### Method 2: Using VS Code Extension
1. Install "Markdown PDF" extension
2. Open `Smart_Attend_SDLC_Assignment.md`
3. Press `Ctrl+Shift+P`
4. Type "Markdown PDF: Export (pdf)"
5. Select and generate PDF

### Method 3: Using Browser
1. Open the markdown file in VS Code preview (`Ctrl+Shift+V`)
2. Copy content to Microsoft Word or Google Docs
3. Format as needed
4. Save/Export as PDF

### Method 4: Online Converter
1. Visit https://www.markdowntopdf.com/
2. Upload `Smart_Attend_SDLC_Assignment.md`
3. Download the generated PDF

## File Structure
```
.
├── Smart_Attend_SDLC_Assignment.md    # Main assignment document
└── README.md                           # This file
```

## Key Topics Covered
- Software Development Life Cycle (SDLC)
- Waterfall Model limitations
- Agile Scrum methodology
- Sprint planning and execution
- User stories and backlog management
- Continuous Integration/Continuous Deployment (CI/CD)
- DevOps practices in mobile development
- Requirement change management

## Assignment Requirements Met
✅ Title page with all details  
✅ Introduction to SDLC and Smart-Attend  
✅ Waterfall failure analysis (3+ reasons)  
✅ Agile Scrum approach with 2 sprints  
✅ Sprint backlog table with 5+ items  
✅ CI/CD benefits explanation  
✅ Professional conclusion  
✅ 1500-2000+ word count  
✅ Academic formatting  

## Technologies Discussed
- Mobile Development (iOS/Android)
- Geofencing/GPS Technology
- Biometric Authentication (Face ID)
- Version Control (Git)
- CI/CD Tools (Jenkins, GitHub Actions)
- Agile Project Management

## References
- Schwaber, K., & Sutherland, J. (2020). The Scrum Guide
- Beck, K., et al. (2001). Manifesto for Agile Software Development
- Humble, J., & Farley, D. (2010). Continuous Delivery
- Royce, W. W. (1970). Managing the Development of Large Software Systems

## License
This document is prepared for academic purposes as part of coursework at LPU.

---

**Note:** This is an academic assignment document. All scenarios and implementations are for educational purposes.
