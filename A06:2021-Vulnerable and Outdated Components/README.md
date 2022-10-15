Examples:
https://pwning.owasp-juice.shop/part2/vulnerable-components.html
https://github.com/OWASP/railsgoat/wiki/A9-Using-Components-with-Known-Vulnerabilities-(JQuery)


https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/

Description
You are likely vulnerable:

If you do not know the versions of all components you use (both client-side and server-side). This includes components you directly use as well as nested dependencies.

If the software is vulnerable, unsupported, or out of date. This includes the OS, web/application server, database management system (DBMS), applications, APIs and all components, runtime environments, and libraries.

If you do not scan for vulnerabilities regularly and subscribe to security bulletins related to the components you use.

If you do not fix or upgrade the underlying platform, frameworks, and dependencies in a risk-based, timely fashion. This commonly happens in environments when patching is a monthly or quarterly task under change control, leaving organizations open to days or months of unnecessary exposure to fixed vulnerabilities.

If software developers do not test the compatibility of updated, upgraded, or patched libraries.

If you do not secure the components’ configurations (see A05:2021-Security Misconfiguration).

