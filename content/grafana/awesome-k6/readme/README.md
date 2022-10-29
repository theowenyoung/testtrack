# Awesome K6 Overview

A curated list of resources on automated load- and performance testing using k6 🗻

[🏠 Home](/README.md) · [🔥 Feed](https://test.trackawesomelist.com/grafana/awesome-k6/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 grafana/awesome-k6](https://github.com/grafana/awesome-k6) · ⭐ 285 · 🏷️ Testing

[ [Daily](/content/grafana/awesome-k6/README.md) / [Weekly](/content/grafana/awesome-k6/week/README.md) / Overview ]

---

<div align="center">
  <a href="https://k6.io/">
    <img src="https://github.com/grafana/awesome-k6/raw/main/assets/bert.png" alt="k6 mascot" width="300px">
  </a>

<!--lint disable awesome-heading-->

# Awesome k6 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!--lint enable awesome-heading-->

</div>

A collection of content by the community, on (testing with) <a href="https://k6.io/">k6</a>.

Want to help in making this list better? Yay, that's awesome! Before you get started though, please have a look at our [code of conduct](https://github.com/grafana/awesome-k6/blob/main/README.md/code_of_conduct.md) and [contribution guidelines](https://github.com/grafana/awesome-k6/blob/main/README.md/contributing.md).

## Contents

*   [Extensions](#extensions)
*   [Articles](#articles)
*   [Videos](#videos)
*   [Reference Projects](#reference-projects)
*   [Tools](#tools)
*   [CI](#ci)
*   [Stacks](#stacks)

## Extensions

*   [GitHub Topic: xk6](https://github.com/topics/xk6) - Explore k6 extensions tagged with the xk6 label.

## Articles

*   [k6 Learn](https://github.com/grafana/k6-learn) - Explanation of the principles of load testing and practical examples for how to do it with k6.

*   [Beginner's guide to load testing with k6](https://link.medium.com/npI9sjDyyjb) - Introductory guide in several parts, helping you get started with k6.

*   [Load Testing with k6](https://medium.com/@dan.ryan.emmons/qa-load-testing-with-k6-io-c11c2afced04) - Brief overview of features and capabilities of k6.

*   [Integrating k6 with Apache Kafka](https://k6.io/blog/integrating-k6-with-apache-kafka) - Sending output from k6 to Apache Kafka.

*   [Test and visualize with InfluxDB, Grafana and K6](https://medium.com/@naoko.reeves/load-test-with-k6-and-visualize-with-influxdb-and-grafana-c6097a6f6d0a) - Setting up load tests and visualizing them using grafana dashboards.

*   [Open source load testing tool review 2020](https://k6.io/blog/comparing-best-open-source-load-testing-tools) - Detailed comparison of the most popular open source load testing tools.

*   [Load Testing Your API with Swagger/OpenAPI and k6](https://k6.io/blog/load-testing-your-api-with-swagger-openapi-and-k6) - Generate k6 load test scripts from OpenAPI specifications.

*   [Load Testing Your API with Postman](https://k6.io/blog/load-testing-with-postman-collections/) - How to use Postman collections to load test your API.

*   [Load Testing & Black Friday capacity planning](https://medium.com/back-market-engineering/how-back-market-sres-prepared-for-black-friday-5f017f343408) - How Back Market prepared for Black Friday with k6 based load testing.

*   [Load Testing SQL Databases with k6](https://k6.io/blog/load-testing-sql-databases-with-k6/) - How to use the xk6-sql extension to test SQL databases directly.

*   [Introducing TestRail in your K6 tests](https://dev.to/kwidera/introducing-testrail-in-you-k6-tests-eck) - Reporting k6 output to TestRail.

*   [Beautiful Load Testing With K6 and Docker Compose](https://medium.com/swlh/beautiful-load-testing-with-k6-and-docker-compose-4454edb3a2e3) - How to run load tests using the awesome combination of Docker Compose, K6, InfluxDB and Grafana.

*   [Load Testing with Azure DevOps and k6](https://medium.com/microsoftazure/load-testing-with-azure-devops-and-k6-839be039b68a) - How to setup Azure DevOps to perform automated load tests using k6, handleCallback, and JUnit.

*   [K6 — Custom Slack Integration: Metrics are the Magic of Tests](https://medium.com/geekculture/k6-custom-slack-integration-metrics-are-the-magic-of-tests-527aaf613595) -  How to send k6 output results to Slack using the handleSummary callback.

*   [Load testing with k6](https://levelup.gitconnected.com/load-testing-with-k6-48488c7946bb) - Using k6 for load, soak, stress, spike and smoke testing.

*   [How to write three times fewer lines of code when doing load testing](https://dev.to/tarantool/how-to-write-three-times-fewer-lines-of-code-when-doing-load-testing-9lb) - Building a k6 extension in Go to test Tarantool.

*   [Load Testing. k6 + TypeScript + Azure DevOps](https://alex-klaus.com/load-test-k6-typescript-azure/)

*   [Performance testing with k6](https://blog.shanelee.name/2021/12/15/performance-testing-with-k6/) - On API performance testing, with Open API and TypeScript.

*   [k6 introduces browser automation and Prometheus support in k6 OSS](https://grafana.com/blog/2021/11/24/k6-introduces-browser-automation-and-prometheus-support-in-k6-oss/) - From the Grafana blog: feature announcements at ObservabilityCON 2021.

*   [Testing shift left observability with the Grafana Stack, OpenTelemetry, and k6](https://grafana.com/blog/2021/12/06/testing-shift-left-observability-with-the-grafana-stack-opentelemetry-and-k6/) - From the Grafana blog: a summary of Executive Director of Platform Engineering at JPMorgan Chase, Vinodh Ravi's talk at ObservabilityCON 2021.

*   [Umbraco 9 - What a Performance!](https://moriyama.co.uk/about-us/news/blog-umbraco-9-what-a-performance/) - Test the performance of Umbraco v9 on Azure against Umbraco v8 and comparing Windows vs Linux.

*   [On maintaining a k6 codebase, Part 1](https://filfreire.com/posts/k6_tricks_ep1) - Personal tips to maintain a challenging k6 load testing codebase.

*   [Distributed Load Testing With K6](https://engineering.empathy.co/distributed-load-testing-with-k6/) - Setting up distributed execution with k6-operator and Argo workflows.

## Videos

*   [k6 YouTube Channel](https://www.youtube.com/c/k6test)
*   [How to use k6 Cloud for load testing](https://www.youtube.com/watch?v=ncxCIuo5tUU\&list=PLJdv3RhAQXNGkRCp7Q0k77n5jif4qjz2o) - A series of quick videos for getting started with k6 Cloud.
*   [Intro to load testing with k6 and Grafana (k6 data source plugin and Prometheus Remote Write)](https://www.youtube.com/watch?v=tFsIgbqXbxM)
*   [From Grafana ObservabilityCON: Intro to using k6 load testing with the Grafana observability stack](https://grafana.com/go/observabilitycon/2021/k6-load-testing/)
*   [From Grafana ObservabilityCON: Building performance tests into your CI pipeline with k6 and Grafana, w/ Matthew Churcher, QA Engineer at Vonage](https://grafana.com/go/observabilitycon/2021/performance-testing-vonage/)
*   [EveryoneCanContribute cafe: Load Performance Testing with k6](https://youtu.be/_ty40gSaaw8)
*   [Playlist - What others says about k6](https://www.youtube.com/playlist?list=PLJdv3RhAQXNExTjuYN9ukawFHB7ucuejp)
    *   [What is K6 & How to get started with k6](https://www.youtube.com/watch?v=ZAq87eZ1w2U) - Tutorial using k6 Extensions for Observability by "Is it Observable?"
    *   [Website Performance + Load Testing with K6 (k6.io) in 5 MINUTES!](https://www.youtube.com/watch?v=brasMBAezJY) - Introductory overview of k6, showing how to create a test from a HAR file, by the DevOps Directive.
    *   [Performance Testing your web app with k6](https://www.youtube.com/watch?v=Hu1K2ZGJ_K4) - A walkthrough of the open-source load and performance regression testing tool, k6, and how to load test your APIs and websites, by Chris James.
    *   [Application Load Testing with k6](https://www.youtube.com/watch?v=iQmItkazLOk) - Daniel Knittl-Frank @TechTalk Days 2021, Intro to k6.
    *   [Performance testing: from zero to hero with k6 & Azure](https://www.youtube.com/watch?v=5G6zYLX9qvM) - Jose Luis Latorre Millas at Cloud Summit 2021.
    *   [Write load tests with co-pilot](https://twitter.com/yusuftayman/status/1456972872853852165) - Yusuf writing k6 tests using GitHub co-pilot.

## Reference Projects

*   [k6-circleci-example](https://github.com/li-clutter-org/k6-circleci-example) - Running k6 load tests as part of a CircleCI build.
*   [k6-jenkins-example](https://github.com/li-clutter-org/k6-jenkins-example) - Running k6 load tests as part of a Jenkins build.
*   [k6-github-actions-example](https://github.com/grafana/k6-example-github-actions) - Running k6 load tests as part of a GitHub Actions build.
*   [k6-azure-pipelines-example](https://github.com/grafana/k6-example-azure-pipelines) - Running k6 load tests as part of an Azure DevOps Pipeline.
*   [k6-bitbucket-pipelines-example](https://github.com/poponuts/k6-boilerplate) - Running k6 load tests as part of a Bitbucket Pipeline build.
*   [k6-performance-test-websocket](https://github.com/Julianhm9612/k6-performance-test-websocket) - Example of performance test for websocket with k6.
*   [k6-template-es6](https://github.com/grafana/k6-template-es6) - Template repository for bundling test projects into single test scripts runnable by k6.
*   [k6 templates](https://github.com/tom-miseur/k6-templates/) - Opinionated starter templates for k6 projects.
*   [k6-typescript-template](https://github.com/grafana/k6-template-typescript) - Template to use TypeScript with k6.
*   [example-data-generation](https://github.com/grafana/k6-example-data-generation) - Generate realistic data for k6 using faker.
*   [bounded-disturbances](https://github.com/bjartwolf/bounded-disturbances) - A .NET Chaos Engineering workshop. Using Simmy and k6.
*   [continuous-k6k8s](https://github.com/lreimer/continuous-k6k8s) - Continuously run k6 tests in Kubernetes using cronjobs.
*   [k6-multiscenario-template](https://github.com/SwissLife-OSS/K6-MultiScenario-template) - Use K6 to implement a Multi Scenario template.
*   [docker-k6-grafana-influxdb](https://github.com/luketn/docker-k6-grafana-influxdb) - Demonstrates how to run load tests with containerised instances of K6, Grafana and InfluxDB.

## Tools

*   [k6-to-junit](https://github.com/Mattihew/k6-to-junit) - Tool for converting k6 output to JUnit XML for easy use with CIs.
*   [k6-reporter](https://github.com/benc-uk/k6-reporter) - Tool for converting k6 output to HTML reports.
*   [k6-html-reporter](https://github.com/szboynono/k6-html-reporter) - Tool for generating k6 HTML reports.
*   [har-to-k6](https://github.com/grafana/har-to-k6) - Tool for converting HAR recordings to k6 test scripts.
*   [postman-to-k6](https://github.com/grafana/postman-to-k6) - Tool for converting Postman collections to k6 test scripts.
*   [k6 generator](https://github.com/OpenAPITools/openapi-generator) - Tool for converting Swagger/OpenAPI specifications to k6 test scripts.
*   [jmeter-to-k6](https://github.com/grafana/jmeter-to-k6) - Tool for converting JMeter test cases to k6 test scripts.
*   [jslib.k6.io](https://jslib.k6.io/) - Useful utility libs for k6 scripts.
*   [k6 for visual studio code](https://marketplace.visualstudio.com/items?itemName=k6.k6\&ssr=false#overview) - Marketplace Extension for running k6 directly from your IDE.
*   [k6 for IntelliJ](https://plugins.jetbrains.com/plugin/16141-k6) - IntelliJ-based Plugin to run k6 tests locally or in the [k6 Cloud](https://app.k6.io/) from your IntelliJ IDE.
*   [k6 Testkube executor](https://kubeshop.github.io/testkube/executor-k6/)
*   [k6-junit](https://github.com/simbadltd/k6-junit) - k6 JUnit summary exporter libray.
*   [k6-expect](https://github.com/simbadltd/k6-expect) - k6 library that simplifies writing tests in a functional way by providing a jest-like syntax for expectations.

## CI

*   [k6 for GitHub actions](https://github.com/marketplace/actions/k6-load-test) - Marketplace action for running k6 in GitHub Actions.
*   [k6 for Azure DevOps Pipelines](https://marketplace.visualstudio.com/items?itemName=k6.k6-load-test) - Marketplace Extension for running k6 in an Azure Devops Pipeline.
*   [k6 CircleCI Orb](https://circleci.com/developer/orbs/orb/k6io/test) - k6 Orb for running k6 in CircleCI. Supports running tests both on the CircleCI runner and in the k6 cloud SaaS service.
*   [k6 for Atlassian Bamboo](https://k6.io/blog/integrating-k6-with-bamboo/)
*   [k6 for AWS CodeBuild](https://k6.io/blog/integrating-k6-with-aws-codebuild/)
*   [k6 for Google Cloud Build](https://k6.io/blog/integrating-k6-with-google-cloud-build/)
*   [k6 for Buddy CI/CD](https://k6.io/blog/integrating-k6-with-buddy-devops/)

## Stacks

*   [CloudPosse's Load Testing Stack](https://github.com/cloudposse/load-testing) - Load testing stack using k6, Grafana and InfluxDB.
*   [Real-time stress:
    AnyCable, k6, WebSockets, and Yabeda](https://evilmartians.com/chronicles/real-time-stress-anycable-k6-websockets-and-yabeda) - Evil Martians adding "real-time stress" with k6 and WebSockets.
*   [Scaling Confidently with the Load and Fault Team](https://robinhood.engineering/scaling-confidently-with-the-load-and-fault-team-122978333d9) - Robinhood on load testing a Kubernetes system with k6.

