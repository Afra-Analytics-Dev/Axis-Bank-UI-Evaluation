# Axis Bank Internet Banking - Usability Evaluation

![Banking Interface](https://img.shields.io/badge/Subject-UI%20Evaluation-blue)
![Heuristics](https://img.shields.io/badge/Methodology-Nielsen's%2010%20Heuristics-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A detailed usability evaluation of Axis Bank's internet banking portal using Nielsen's 10 Usability Heuristics, identifying pain points and proposing design improvements.

##  Table of Contents
- [Project Overview](#-project-overview)
- [Key Findings](#-key-findings)
- [Heuristic Violations](#-heuristic-violations)
- [Task Performance Metrics](#-task-performance-metrics)
- [Proposed Improvements](#-proposed-improvements)
- [Tools Used](#-tools-used)
- [Repository Structure](#-repository-structure)
- [How to Contribute](#-how-to-contribute)
- [License](#-license)

##  Project Overview
This project evaluates the user experience of Axis Bank's internet banking portal through:
- **Nielsen's 10 Usability Heuristics** framework
- Real-user task performance measurements
- Interface wireframe analysis
- Multi-user feedback integration

**Evaluated Portal**: [Axis Bank Internet Banking](https://retail.axisbank.co.in/)

##  Key Findings
| Aspect | Strengths | Weaknesses |
|--------|-----------|------------|
| **Login** | Secure authentication | No "Show Password" option |
| **Dashboard** | Quick balance visibility | Cluttered layout |
| **Fund Transfer** | OTP security | No confirmation step |
| **Error Handling** | Clear error messages | Limited recovery guidance |

##  Heuristic Violations
### 1. Login Page
![Login Wireframe](./Wireframes/login-wireframe.png)
- **Violated Heuristics**:
  - #1: Visibility of system status
  - #5: Error prevention
- **Issues**:
  - Small input fields
  - No password visibility toggle

### 2. Dashboard
![Dashboard Wireframe](./Wireframes/dashboard-wireframe.png)
- **Violated Heuristics**:
  - #8: Aesthetic and minimalist design
  - #6: Recognition rather than recall
- **Issues**:
  - Information overload
  - Unclear menu labels

## Task Performance Metrics
| Task | Avg. Time | Success Rate | Pain Points |
|------|----------|-------------|-------------|
| Login | 30-40s | 100% | Network dependency |
| Fund Transfer | 2-3min | 85% | Complex OTP flow |
| Statement Download | 1.5-2min | 70% | Hidden menu option |

##  Proposed Improvements
### Login Page Redesign
```diff
+ Add "Show Password" toggle
+ Increase input field sizes
+ Visual loading indicators

**Tools Used**
Purpose	Tools
Documentation	Google Docs
Wireframing	wireframe.cc
Browsers	Chrome, Firefox
Reference	Nielsen's Heuristics


