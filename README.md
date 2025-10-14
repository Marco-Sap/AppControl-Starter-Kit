# AppControl-Starter-Kit
Starter Kit for App Control for Business and Applocker

![alt text](https://github.com/Marco-Sap/AppControl-Starter-Kit/blob/main/Src/Slide1.PNG?raw=true)

![alt text](https://github.com/Marco-Sap/AppControl-Starter-Kit/blob/main/Src/Slide3.PNG?raw=true)

Rules:
* For an Process/Application to be allowed to run it must be defined in ALL Policy verticals (B and B+A and Applocker) either explicit or by wildcards.
* Explicit Deny will overrule Allow, so by putting a explicit block for App A in B4 and wildcard Allow C:\* in B3, App A will still be blocked.
* B1 is no longer necessary at it is automatically appplied on all current Windows 11 builds.
* Supplemental Policies can only contain Allow rules.
* For Device-wide Allow/Block rules use Appcontrol (B+A), for Group/User based Allow/Block rules use Applocker.

Changelog:
* Removed individual Apps from B3 and used wildcards
* Removed redundant Apps from A1
* Added Explicit Deny B4 policy with the Downloads folder as example
* Added Audit B5 policy with C:\Users as example
* Added AppLocker Audit files under Applocker/ApplockerAudit with custom CSP name "AppControlAudit"

Backlog:
* Cleanup of Certificates in B3
* Enforce HVCI in all B policy
* Remove "Enabled:Advanced Boot Options Menu" in all B policy
* Remove "Enabled:Boot Audit On Failure" in all B policy
* Add COM Object option to all B policy
