---
layout: post
at: Red Hat
type: talk
title: "ScanAPI: Automated Integration Testing and Live Documentation for your API"
date: 2020-10-29
categories:
  [
    "talk",
    "scanapi",
    "python",
    "api",
    "tests",
    "integration-tests",
    "documentation",
    "open-source",
  ]
---

Internal tech talk at [RedHat](https://www.redhat.com/pt-br) about [ScanAPI](https://scanapi.dev) framework.

<script async class="speakerdeck-embed" data-id="a40377f817f645a095c70e3e13e1f576" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>

<blockquote class="twitter-tweet"><p lang="pt" dir="ltr">Demorei pra enviar esta mensagem, mas aqui vai: obrigadissimo <a href="https://twitter.com/cmaiacd?ref_src=twsrc%5Etfw">@cmaiacd</a> pela palestra super genial que ela deu sobre ScanAPI para a minha equipe de Software Quality Engineers na semana passada. Sen-sa-cio-nal!</p>&mdash; OgMaciel 🗽 (@OgMaciel) <a href="https://twitter.com/OgMaciel/status/1324474265295609857?ref_src=twsrc%5Etfw">November 5, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br>

#### Talk description

In the current IT scenario, the use of APIs is, without question, widely vast, popular, and significant. It seems at least prudent to ensure they are working properly, as expected. To guarantee the quality of the data that is being consumed or used. To ensure that communication between services is occurring as expected. To ensure the system does, in fact, what it should do.

ScanAPI is an open-source library that was created to solve all these points. ScanAPI provides an easy way to create integration tests for REST APIs via configuration files.

The three main reasons that led me to the creation of this library were:

1. To be a firefighter in a scenario where most of the reported bugs were directly related to some API contract being broken or some endpoint having a behavior different from that expected by the consumer.

2. To need to deal with APIs with outdated or mistaken documentation.

3. To need to debug an endpoint in the middle of a "chain" of other endpoints. Where I needed to recreate a state that depends on the action of other endpoints.

Given a fictitious example: debug an endpoint to reserve seats on an airplane, which depends directly on the previous call of an endpoint for user registration.

The ScanAPI is open-source and written in Python. However, it can be used in APIs created in any other programming language, since the tests provided by it are integration tests.

With ScanAPI you can:

- Use environment variables
- Create variables
- Chaining requests - making a request from a result of previous responses
- Hide sensitive information of the requests and responses in the generated report
- Write Python code - if you want, it's not necessary :)

Topics I intend to address in this talk:

- Motivation to create the library
- What problems the library solves
- How to test an API using a ScanAPI
- Show the documentation generated by ScanAPI
- An overview of how it is implemented
- Where it is currently being used
- Next steps

[https://scanapi.dev](https://scanapi.dev)
