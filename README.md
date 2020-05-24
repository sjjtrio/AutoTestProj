Moved to https://github.com/sjjtrio/UAAutoTest


# AutoTestProj
My personal auto testing framework. Used in real projects of company I serverd.

It supports both UI and REST API testing
This is a JAVA maven project, the foundation of UI testing is based on Selenium and API based on Rest-Assured.

UI Automation:
Based on POM (page object model), treat pages as objects, they contain properties(web elements) and functions (actions), once initial the page object with selenium driver, it can be treated and object and be used conveniently.

API Automation:
Using Rest Assured, it can simulate all methods of restful api calls and get responses in just one revoke of the RestCall class.

//....
