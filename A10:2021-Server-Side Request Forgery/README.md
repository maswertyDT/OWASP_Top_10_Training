## Examples:
https://github.com/OWASP/railsgoat/wiki/R5-A10-Unvalidated-Redirects-and-Forwards-(redirect_to)
https://owasp.org/Top10/A10_2021-Server-Side_Request_Forgery_%28SSRF%29/


https://owasp.org/Top10/A10_2021-Server-Side_Request_Forgery_%28SSRF%29/

## Description
SSRF flaws occur whenever a web application is fetching a remote resource without validating the user-supplied URL. It allows an attacker to coerce the application to send a crafted request to an unexpected destination, even when protected by a firewall, VPN, or another type of network access control list (ACL).

As modern web applications provide end-users with convenient features, fetching a URL becomes a common scenario. As a result, the incidence of SSRF is increasing. Also, the severity of SSRF is becoming higher due to cloud services and the complexity of architectures.