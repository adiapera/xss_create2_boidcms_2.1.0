# XSS in BoidCMS 2.1.0 (/admin -> Create)
**Software link:** BoidCMS 2.1.0 [https://boidcms.github.io/#/] -> Download

**@author:** Antonio Díaz Pérez.

**Description:** Cross-site scripting (XSS) vulnerability in the Create section of the Admin Page of BoidCMS 2.1.0 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into 'Content' parameter.

**CVE:** CVE-2024-32343.

## PoC
### Admin Page -> Create (CVE-2024-32343)
1. Enter to Create section of Admin Page, set the payload in 'Content' parameter and click on the Create button:

![image](https://github.com/adiapera/xss_create2_boidcms_2.1.0/assets/165512291/79ac6e20-aaf9-4434-9ca3-9a2b7aebee81)
![image](https://github.com/adiapera/xss_create2_boidcms_2.1.0/assets/165512291/d4074120-f924-4ae2-8795-3a3a6d3f97f9)

2. Show Dashboard page and click on the link to the new page you have created:

![image](https://github.com/adiapera/xss_create2_boidcms_2.1.0/assets/165512291/a5d85777-427c-4a61-982b-a2b53828eb95)
![image](https://github.com/adiapera/xss_create2_boidcms_2.1.0/assets/165512291/6a06b5de-29e3-4fe4-9d14-626c1fe1870d)

