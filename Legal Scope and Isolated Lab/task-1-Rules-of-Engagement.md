# Rules of Engagement — Ethical Hacking Practice Lab

## 1. Purpose

This document defines the rules and scope for security testing performed in my local cybersecurity practice laboratory.

The lab is intended only for educational and authorized security testing.

## 2. Authorized Target

The only authorized target is:

- Application: OWASP Juice Shop
- Deployment: Docker container
- Address: 127.0.0.1:3000
- Controller: Tester

No other systems are included in the testing scope.

## 3. Allowed Techniques

The following activities are permitted against the authorized target:

- Local reconnaissance
- Port and service enumeration
- Web application testing
- Vulnerability scanning
- Manual security testing
- Analysis of HTTP requests and responses
- Controlled exploitation within the laboratory
- Documentation of security findings

## 4. Exclusions

The following are explicitly out of scope:

- Public websites
- Third-party systems
- Systems without explicit authorization
- Real user accounts
- Real personal or confidential data
- External networks and services
- Social engineering of real individuals
- Malware deployment outside the laboratory
- Denial-of-service attacks against external systems

## 5. Scope Boundary

Testing is restricted to:

127.0.0.1:3000

No testing will be intentionally performed against systems outside this authorized target.

## 6. Stop Conditions

Testing must immediately stop if:

- Traffic is unintentionally directed toward an external system.
- A system outside the authorized scope is discovered.
- The target becomes unstable or unavailable.
- Real personal or confidential information is encountered.
- Testing could negatively affect a system outside the laboratory.

## 7. Evidence Handling

Screenshots, logs, and observations collected during testing will be used for educational and portfolio documentation.

Sensitive information will not intentionally be collected or published.

## 8. Tester Declaration

I confirm that I understand the importance of authorization and will perform security testing only within the scope defined in this document.

I will not test systems that I do not own or have explicit permission to test.

**Tester:** Haleema

**Signature:** Haleema

**Date:** 04 September 2026
