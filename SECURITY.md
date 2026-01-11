# Security Policy

<br />

## Reporting Security Vulnerabilities

We take security seriously and appreciate responsible disclosure.

If you discover a **security vulnerability** in this project, **do not open a public issue
or disclose it publicly**. Instead, report it privately using one of the following
channels:

- **Email:** [security@arthur.place](mailto:security@arthur.place)
- **Direct message on X:**
  [https://twitter.com/arthurfiorette](https://twitter.com/arthurfiorette)

Public disclosure of exploitable issues before a fix is released may put users at risk and
is strongly discouraged.

### What to Include

To help us investigate efficiently, please include:

- A clear description of the vulnerability
- Steps to reproduce the issue
- The potential impact (who/what is affected and how)
- (Optional) Suggested mitigations or fixes

You may suggest a reasonable disclosure timeline if you plan to publish details after
reporting. We consider that fair and will make a good-faith effort to respond within that
window.

<br />

## Response Process

### Investigation & Validation

We will acknowledge receipt of your report and investigate the issue. We may contact you
for clarification or additional information.

### Resolution & Patch Deployment

If the issue is confirmed to be a security vulnerability, we will prioritize remediation
based on severity and impact. While timelines vary, fixes are typically released within a
few days of confirmation when feasible.

### Responsible Disclosure

Once a fix has been implemented and deployed, we may coordinate a public disclosure if
appropriate. We ask that vulnerability details remain private until this process is
complete.

<br />

## Scope and Expectations

### What Counts as a Security Issue

Security issues include, but are not limited to:

- Authentication or authorization bypasses
- Privilege escalation
- Sensitive data exposure
- Remote code execution
- Injection vulnerabilities
- Cryptographic failures that materially reduce security guarantees

### Design Tradeoffs and Non-Issues

Not all concerns framed as “security issues” are vulnerabilities. This project makes
intentional design tradeoffs between security, usability, and complexity.

We reject absolutist or binary claims such as “never use X.” Security exists on a
spectrum, and maximizing for security alone does not necessarily produce a usable or
correct system.

If you believe a design decision introduces unacceptable risk, you **must** articulate
your critique constructively and in good faith. Specifically, you are expected to:

- Acknowledge the likely reason the decision was made
- Identify the benefits it provides
- Explain the downside or risk
- Argue clearly why existing mitigations are insufficient

Example structure:

> “X appears to be used because of benefit **A**, and its downside **B** is partially
> mitigated by **C**. However, I believe this is insufficient because of **D**.”

We do not tolerate reports or discussions that waste maintainer time by ignoring this
nuance. If something is unclear, asking for clarification is always acceptable.

<br />

## Contact

For all security-related matters, contact:

📧 **[security@arthur.place](mailto:security@arthur.place)**

Thank you for helping keep this project and its users secure through responsible
disclosure.

<br />
