# Security Policy

## Supported Versions

We are committed to maintaining the security of our users and their data. We will provide security updates for the latest stable version of **ZenithPDF-Document-Management-Desktop-App**. Older versions are not actively supported and may not receive security patches.

## Reporting a Vulnerability

We take all security vulnerabilities seriously. If you discover a security issue in **ZenithPDF-Document-Management-Desktop-App**, please report it to us immediately. We will acknowledge your report within 48 hours.

**Please do not disclose the vulnerability publicly until it has been addressed.**

To report a vulnerability, please send an email to:

*   `chirag.m.pathak@gmail.com` (Primary Contact)

When reporting, please provide as much detail as possible, including:

*   A clear description of the vulnerability.
*   The steps to reproduce the issue.
*   The affected version(s) of the software.
*   Any relevant logs, screenshots, or proof-of-concept code.

We will work diligently to assess the report, develop a fix, and release a patch as soon as possible. We will also credit reporters for significant vulnerabilities.

## Security Best Practices

*   **Desktop Application Security:** As this is a desktop application built with Tauri, ensure you are downloading releases only from the official GitHub repository (`https://github.com/chirag127/ZenithPDF-Document-Management-Desktop-App`) to avoid tampered versions.
*   **Client-Side Operations:** Most document processing occurs client-side, minimizing the risk of server-side data breaches. However, always be mindful of the sensitivity of the documents you are handling.
*   **TypeScript & Vite Security:** We adhere to strict TypeScript configurations and use Vite's build optimizations. Ensure you always update to the latest patch versions of these dependencies and follow their respective security guidelines.
*   **Dependency Management:** Regularly update your local dependencies using `uv` (or your preferred package manager) to include the latest security patches for all libraries.
*   **Code Review:** All code contributions are subject to a rigorous review process, with a strong emphasis on security implications.

Thank you for helping us keep **ZenithPDF-Document-Management-Desktop-App** secure!
