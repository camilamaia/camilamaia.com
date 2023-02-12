---
layout: post
at: DjangoCon EU 2022
type: workshop
title: "ScanAPI: Automated Integration Testing and Live Documentation for your
Django APIs"
date: 2022-09-23
categories:
  [
    "workshop",
    "djangocon",
    "djangocon-europe",
    "scanapi",
    "python",
    "api",
    "tests",
    "integration-tests",
    "documentation",
    "open-source",
  ]
---

Workshop at [DjangoCon EU 2022][djangocon-eu-2022] about [ScanAPI][scanapi]
framework.

[https://pretalx.evolutio.pt/djangocon-europe-2022/talk/AFYRWB/][workshop]

<script async class="speakerdeck-embed" data-id="95fb69e56ca84bb8847a703aa7647ce9" data-ratio="1.77725118483412" src="//speakerdeck.com/assets/embed.js"></script>

<br>

#### Details

One of the most common use cases of Django is to create REST APIs, especially using the Django REST framework. When creating APIs, we need to ensure the endpoints are working properly, as expected. To ensure they do, in fact, what they should do.

ScanAPI is an open-source Python library that was created to help in this task. ScanAPI provides an easy way to create integration tests for REST APIs via configuration files. Given an API specification, written by the user in YAML/JSON format, the library hits the specified endpoints, runs the test cases, and generates a detailed report of this execution - that can be also used as the API documentation itself.

After a short intro of what ScanAPI is and what was the motivation to create it (5 min), we go over the following topics

* Short Intro about the API we will test and document
* Setup - Installation + configure the project name
* Document and test the first endpoint
* How to use environment variables
* How to hide sensitive information in the reports
* How to chain requests
* How to use nested endpoints
* How to use default values
* How to split the specification file into multiple files
* Quick overview about how to use custom reports
* Quick overview about how to add ScanAPI to a pipeline

ScanAPI Links:

* GitHub Organization: [https://github.com/scanapi][org]
* Website: [https://scanapi.dev][website]
* Twitter: [http://twitter.com/scanapi_][twitter]

[djangocon-eu-2022]: https://2022.djangocon.eu
[org]: https://github.com/scanapi
[scanapi]: https://github.com/scanapi/scanapi
[twitter]: http://twitter.com/scanapi_
[website]: https://scanapi.dev
[workshop]: https://pretalx.evolutio.pt/djangocon-europe-2022/talk/AFYRWB/
