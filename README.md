# secure-code-review-framework
Secure Code Review Framework implementing OWASP, SANS, and CERT guidelines using SonarQube, Semgrep, and CI/CD pipelines for automated vulnerability detection.
# Secure Code Review Framework

## Overview
This project implements a secure code review framework using open-source tools to detect vulnerabilities, code issues, and security risks.

## Tools Used
- SonarQube (Code Quality)
- Semgrep (Static Analysis)
- Gitleaks (Secret Detection)

## Features
- Automated code scanning using GitHub Actions
- Detection of vulnerabilities (e.g., hardcoded passwords)
- Custom rule support
- CI/CD integration

## Workflow
1. Developer pushes code
2. GitHub Actions triggers scan
3. Semgrep analyzes code
4. Vulnerabilities reported

## Example Issue
Hardcoded password detected in app.py

## Conclusion
This framework improves code security and automates vulnerability detection.
