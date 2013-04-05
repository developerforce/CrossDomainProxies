<h1>Cross Domain Proxies</h1>
This repository is meant to serve as a centralized location for code which can be used as proxy, in particular for when developing JavaScript based applications that need to work within the cross domain security policy of the typical JavaScript security sandbox.

* PHP: A modified version of "Cowboy" Ben Alman's original proxy.php fitted to work easily against the Salesforce Platform's internal proxy
* Node.js: A node.js application which allows for calls to be sent back to the Salesforce Platform via a /proxy route.

These are currently being used in the https://github.com/developerforce/MobilePack-AngularJS and https://github.com/developerforce/MobilePack-BackboneJS repositories.