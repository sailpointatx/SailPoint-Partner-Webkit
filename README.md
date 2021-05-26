# SailPoint Partner Webkit with Embeddable Identity Value Calculator

## SailPoint Partner Webkit (no calculator)

For the version of the webkit without the identity value calculator, please access the `/partner-webkit/index.html` file. The code is self contained within the DIV with an ID of `sp-partnerwebkit`.

Images such as the SailPoint logo and icons can be found in: `/partner-webkit/images/`.

The only external file required is `/partner-webkit/styles/sailpoint-webkit.min.css`.

&nbsp;  

## SailPoint Partner Webkit with Identity Value Calculator

For the version of the webkit that includes the identity value calculator, please access the `/partner-webkit-calculator/index.html` file. The code is self contained within the DIV with an ID of `sp-partnerwebkit`. Besides the CSS & Javascript for the page and calculator, it requires the external libraries jQuery 3.5.1, jQuery UI 1.12, and amCharts 4.

Images such as the SailPoint logo and icons can be found in: `/partner-webkit-calculator/images/`.

External CSS files required include:
- `/partner-webkit-calculator/styles/sailpoint-webkit-calculator.min.css`
- `/partner-webkit-calculator/styles/jquery-ui.css`

External Javascript files required include:
- `/partner-webkit-calculator/scripts/sailpoint-calculator.js`
- `/partner-webkit-calculator/scripts/jquery.min.js`
- `/partner-webkit-calculator/scripts/jquery-ui.min.js`
- `/partner-webkit-calculator/scripts/amcharts4.js`

The calculator can be configured with the following variables to customize the default values for the form and colors used in the chart.
- *defaultAppsCount*     (default applications count, integer, range 5-50)
- *defaultUsersCount*    (default users count, integer, range 500-10000)
- *defaultIndustry*      (default industry, integer, range 1-18)
    - 1 - Banking
    - 2 - Biotechnology & Pharma
    - 3 - Construction & Building
    - 4 - Consulting & Services
    - 5 - Education
    - 6 - Entertainment & Media
    - 7 - Federal Government
    - 8 - Finance
    - 9 - Healthcare
    - 10 - Insurance
    - 11 - Manufacturing & Wholesale
    - 12 - NPO's & Associations
    - 13 - Oil & Gas & Energy
    - 14 - Other
    - 15 - Retail & Consumer
    - 16 - Software/Internet/Technology
    - 17 - Transportation
    - 18 - Utilities
- *colorProvisioning*    (provisioning chart color, hex code)
- *colorRequests*        (access requests chart color, hex code)
- *colorPasswordResets*  (password resets chart color, hex code)
- *colorCertification*   (certifications chart color, hex code)
