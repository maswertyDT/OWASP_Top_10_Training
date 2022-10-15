## Examples:
https://owasp.org/Top10/A08_2021-Software_and_Data_Integrity_Failures/
https://pwning.owasp-juice.shop/part2/insecure-deserialization.html


https://owasp.org/Top10/A08_2021-Software_and_Data_Integrity_Failures/

## Description
Software and data integrity failures relate to code and infrastructure that does not protect against integrity violations. An example of this is where an application relies upon plugins, libraries, or modules from untrusted sources, repositories, and content delivery networks (CDNs). An insecure CI/CD pipeline can introduce the potential for unauthorized access, malicious code, or system compromise. Lastly, many applications now include auto-update functionality, where updates are downloaded without sufficient integrity verification and applied to the previously trusted application. Attackers could potentially upload their own updates to be distributed and run on all installations. Another example is where objects or data are encoded or serialized into a structure that an attacker can see and modify is vulnerable to insecure deserialization.