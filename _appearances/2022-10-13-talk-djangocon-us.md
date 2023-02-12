---
layout: post
at: DjangoCon US 2022
type: talk
title: "factory_boy: testing like a pro"
date: 2022-10-13
categories:
  [
    "talk",
    "djangocon",
    "djangocon-us",
    "documentation",
    "factory_boy",
    "open-source",
    "python",
    "tests",
  ]
---

Talk at [DjangoCon US 2022][djangocon-us-2022] about best practices using
[factory_boy][factory_boy].

[https://2022.djangocon.us/talks/factory-boy-testing-like-a-pro/][talk]

<iframe width="560" height="315" src="https://www.youtube.com/embed/OR-HwCPdFxo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<br>

<script async class="speakerdeck-embed" data-id="26bca231f5ae4c81bf05d93cfd4b101b" data-ratio="1.77725118483412" src="//speakerdeck.com/assets/embed.js"></script>

<br>

#### Details

After working using the factory_boy library for over 3 years on a Django monolith containing +230 tables, +2200 relevant files, and +75k relevant lines of code, I've collected and listed all my biggest learnings.

In this presentation, I try to share some of my experiences, showing what I consider to be good practices in using factory_boy in complex systems.

Content:

* A short introduction of myself
factory_boy: what is it? - the definition and the purpose of the tool
* Example application - a quick overview of the application we will use to demonstrate the best practices
* How to install factory_boy
* How to use factory_boy
* Best Practices:
  1. Factories must represent their models
  2. Do not rely on defaults from factories
  3. Factories must have only the required data. if the field is nullable -> under traits.
  4. Build over create
  5. If FK is in the table -> SubFactory. If FK is in the other table -> RelatedFactory + trait
  6. Fixtures only to wrap factories in the test file
  7. Avoid using fixtures on shared files like conftest
* Wrapping up

Repository: [github.com/camilamaia/factory-boy-best-practices][repo]

[djangocon-us-2022]: https://2022.djangocon.us
[factory_boy]: https://factoryboy.readthedocs.io/en/stable/
[repo]: https://github.com/camilamaia/factory-boy-best-practices
[talk]: https://2022.djangocon.us/talks/factory-boy-testing-like-a-pro/
