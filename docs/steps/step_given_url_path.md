
Given URL path "{url_path}"
=============================================================================================================

Usage example
-------------

```
Feature: zato-apitest docs

Scenario: Given URL path "{url_path}"

    Given address "http://apitest-demo.zato.io"
    Given URL path "/demo/json"
    Given format "JSON"

    When the URL is invoked

    Then status is "200"
```

Discussion
----------

If not provided, the default URL path is "/".