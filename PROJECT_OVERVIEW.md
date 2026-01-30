# Project Overview: Introduction to CodeQL

## What This Project Does

This repository is a **hands-on learning exercise** designed to teach developers how to use **GitHub CodeQL** for automated security scanning and vulnerability detection. It's part of the GitHub Skills program that provides interactive learning experiences.

## Purpose

The primary purpose of this project is to:

1. **Introduce CodeQL**: Teach users about GitHub's semantic code analysis engine
2. **Demonstrate Code Scanning**: Show how GitHub Advanced Security can automatically detect vulnerabilities
3. **Hands-on Learning**: Provide a practical example with real code and security issues
4. **Security Best Practices**: Educate developers about common vulnerabilities like SQL injection

## What's Included

### 1. Sample Application
A simple **Flask-based BookStore web application** (`/server` directory) that includes:
- **Web Server**: Flask application with routes for book management
- **Database**: SQLite database integration for storing book information
- **Templates**: HTML templates for rendering the book store UI
- **Models**: Python data models for book entities

### 2. Intentional Vulnerabilities
The application contains deliberately introduced security vulnerabilities for educational purposes:
- **SQL Injection**: Vulnerable SQL queries that concatenate user input directly
- **Insecure Code Patterns**: Examples of what NOT to do in production code

### 3. Learning Materials
Step-by-step guides in `.github/steps/` that walk through:
- Enabling GitHub Code Scanning
- Detecting vulnerabilities in pull requests
- Understanding CodeQL analysis results
- Fixing security issues

### 4. GitHub Actions Workflows
Automated workflows that:
- Run CodeQL analysis on code changes
- Provide security feedback in pull requests
- Guide learners through the exercise steps

## How It Works

1. **Enable Code Scanning**: Users activate CodeQL analysis for the repository
2. **Introduce Vulnerability**: Create a pull request with intentionally vulnerable code
3. **Automatic Detection**: CodeQL scans the code and identifies security issues
4. **Review Results**: Examine the security alerts and understand the vulnerabilities
5. **Fix Issues**: Apply the suggested fixes to remediate the vulnerabilities
6. **Learn**: Understand how to prevent similar issues in future code

## Key Learning Outcomes

After completing this exercise, users will understand:
- How to enable and configure CodeQL for their repositories
- How code scanning integrates into the pull request workflow
- How to interpret CodeQL security alerts
- Best practices for writing secure code
- How to fix common vulnerabilities like SQL injection

## Technology Stack

- **Language**: Python 3.8
- **Framework**: Flask (web application framework)
- **Database**: SQLite
- **Package Manager**: Pipenv
- **Security**: GitHub CodeQL
- **CI/CD**: GitHub Actions

## Security Note

⚠️ **Important**: This repository contains intentionally vulnerable code for educational purposes. DO NOT use this code in production environments. The vulnerabilities are designed to teach security concepts and should never be deployed to real-world applications.

## Target Audience

This project is ideal for:
- Developers new to code security scanning
- Teams adopting GitHub Advanced Security
- Anyone interested in learning about CodeQL
- Security-conscious developers wanting to improve their skills

## Related Resources

- [GitHub Code Scanning Documentation](https://docs.github.com/en/code-security/code-scanning)
- [CodeQL Documentation](https://codeql.github.com/docs/)
- [GitHub Advanced Security](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security)
- [GitHub Skills](https://learn.github.com/skills)
