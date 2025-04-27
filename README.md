# CS-305
Software Security

CS-305 Portfolio Artifact: Practices for Secure Software Report

Client Summary:
The client, Artemis Financial, is a financial services organization concerned about the security vulnerabilities in their software. The company requested a thorough security assessment and refactor of their application to address known vulnerabilities and enhance secure coding practices.

What I Did Well:
I successfully identified and addressed critical and high-severity vulnerabilities through static code analysis, dependency management, and secure refactoring practices. It is important to code securely because security flaws can lead to financial losses, reputational damage, or regulatory penalties. Secure software helps protect client data, maintains trust, and ensures compliance with security standards.

Challenging/Helpful Aspects:
One challenge was identifying vulnerabilities in transitive dependencies that were not obvious at first glance. The OWASP Dependency Check tool proved extremely helpful in uncovering hidden issues.

How I Increased Security:
I deployed strong encryption (SHA-256 hashing), generated SSL certificates for HTTPS, patched vulnerable dependencies, and configured secure communications. In the future, I would use both static analyzers and manual code review to prioritize mitigations based on severity, exploitability, and business risk.

Ensuring Functionality and Security:
After refactoring, I verified application functionality by manually testing all endpoints and validating SSL configuration. I re-ran the OWASP Dependency Check tool to confirm that no new vulnerabilities were introduced after changes.

Resources/Tools/Practices Used:

OWASP Dependency-Check (for vulnerability scanning)
Java Keytool (for SSL certificate creation)
Maven (for build automation and dependency management)
Secure coding guidelines from OWASP and NIST
These tools and practices are crucial for any secure software development workflow.
Future Employer Example:
I would show a future employer the full process: performing vulnerability analysis, securely refactoring code, testing functionality, and documenting the solution in a professional report. It demonstrates my ability to identify issues, fix them securely, and ensure system resilience.
