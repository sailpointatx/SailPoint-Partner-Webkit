# Embeddable Identity Value Calculator

This embeddable version of the Identity Value Calculator is meant to be included in an IFRAME on partner sites.

The PHP script is set up to receive the following GET parameters to set default value for the form and chart:
- appsCount     (default apps count, integer, range 5-50)
- usersCount    (default users count, integer, range 500-10000)
- industry      (default industry, integer, range 1-18)
- colorProv     (provisioning chart color, hex code without #)
- colorReq      (access requests chart color, hex code without #)
- colorPwResets (password resets chart color, hex code without #)
- colorCert     (certifications chart color, hex code without #)

Javascript files required:
- jquery.min.js - jQuery 3.5.1
- jquery-ui.min.js - jQuery UI 1.12.1 (for slider UI)
- amcharts4.js - amCharts 4
- sailpoint-calculator.js - SailPoint custom calculator script

CSS files required:
- jquery-ui.css - jQuery UI styles
- sailpoint-calculator.css - SailPoint custom calculator styles