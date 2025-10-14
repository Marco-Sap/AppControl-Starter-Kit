# AppControl-Starter-Kit
Starter Kit for App Control for Business and Applocker

![alt text](https://github.com/Marco-Sap/AppControl-Starter-Kit/blob/main/Src/Slide1.PNG?raw=true)

![alt text](https://github.com/Marco-Sap/AppControl-Starter-Kit/blob/main/Src/Slide3.PNG?raw=true)

Changelog:
* Removed individual Apps from B3 and used wildcards
* Removed redundant Apps from A1
* Added Explicit Deny B4
* Added AppLocker Audit files under Applocker/ApplockerAudit with custom csp name "AppControlAudit"

Backlog:
* Cleanup of Certificates in B3
* Example B4 DenyAll for App Control process of adding Software
* Enforce HVCI
* Remove "Enabled:Advanced Boot Options Menu" in all B policy
* Remove "Enabled:Boot Audit On Failure" in all B policy
* Add COM Object option to all B policy
