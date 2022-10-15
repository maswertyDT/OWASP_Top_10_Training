## Examples:
https://pwning.owasp-juice.shop/part2/security-misconfiguration.html


https://owasp.org/Top10/A05_2021-Security_Misconfiguration/

## Description
- The application might be vulnerable if the application is:

- Missing appropriate security hardening across any part of the application stack or improperly configured permissions on cloud services.

- Unnecessary features are enabled or installed (e.g., unnecessary ports, services, pages, accounts, or privileges).

- Default accounts and their passwords are still enabled and unchanged.

- Error handling reveals stack traces or other overly informative error messages to users.

- For upgraded systems, the latest security features are disabled or not configured securely.

- The security settings in the application servers, application frameworks (e.g., Struts, Spring, ASP.NET), libraries, databases, etc., are not set to secure values.

- The server does not send security headers or directives, or they are not set to secure values.

- The software is out of date or vulnerable (see A06:2021-Vulnerable and Outdated Components).

- Without a concerted, repeatable application security configuration process, systems are at a higher risk.