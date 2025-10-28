# Silent Web Oasis – Quality Assurance Case Study

## Overview
This repository contains the Quality Assurance (QA) documentation and test findings for the **Silent Web Oasis** web application.  
The analysis identifies key functional, security, and user experience issues found during manual testing.

The purpose of this report is to assess the app’s **authentication flow**, **form validation**, **session handling**, and **UI responsiveness** — and recommend fixes to improve reliability and user trust.

##Files Included

| File | Description |
| **QAI_MATERIAL.docx** | Detailed table of issues with reproduction steps, expected vs. actual results, and severity ratings. |
| **QAI_DOC.pdf** | Final formatted QA report including findings, recommendations, and test coverage summary. |
| **demo/silent-web-oasis.mp4** | Screen recording demonstrating key bugs and issues identified during testing. |

##Summary of Key Findings

| Category | Issue | Severity |
| **Functional / Security** | No error on wrong login, blank field submission allowed, no session validation, destructive delete without confirmation | High |
| **UX / Design** | Weak password accepted, no feedback after register, missing "Forgot Password" | Medium |
| **Responsive Design** | Input overlap on small screens | Low |

Total: **8 issues** (4 High, 3 Medium, 1 Low)

##Recommended Fixes

- Add **form validation** on frontend & backend  
- Protect `/home` route using session or JWT authentication  
- Display **feedback messages** for login/register actions  
- Add **confirmation modal** before destructive actions  
- Implement **password strength checker**  
- Add “Forgot Password” recovery flow  
- Improve **responsive layout** for mobile screens

---

##Test Coverage
- Registration and Login validation  
- Session handling and logout flow  
- Direct URL access restriction  
- Account deletion safety  
- Cross-browser check on mobile and desktop  

##Conclusion
Fixing the high-severity issues — especially broken validation, missing feedback, and weak access control — will significantly improve the security and usability of the application.  
The documentation and video evidence provided in this repo demonstrate clear testing methodology and professional QA practices.

## Author
**Sarveshwararam M (21BCB0161)**  
VIT Vellore  
Manual QA and Functional Testing Report
