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
- jQuery 3.5.1
- jQuery UI 1.12.1 (for slider UI)
- Amcharts 4 (core, charts, animated)
- custom calculator script - calcROI

CSS files required:
- jQuery UI styles
- custom calculator styles