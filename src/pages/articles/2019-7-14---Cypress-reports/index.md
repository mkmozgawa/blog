---
title: Cypress + {mochawesome-report-generator, allure}
date: "2019-07-14T10:00:00.000Z"
layout: post
draft: false
path: "/posts/cypress-reports/"
category: "QA"
tags:
  - "Automation"
description: "Quick setup for Cypress and {mochawesome-report-generator, allure} for test result generation"
---

Since I got back to using Cypress I've created [a simple setup for using Cypress and generating test results](https://github.com/mkmozgawa/cypress-reporter). Plug it into Jenkins/Bamboo/your favourite CI/CD tool, preferably onto a Docker-based worker with nvm, and snatch your run artifacts from `mochawesome-report/`.

Update: If you're feelin' fancy, there's also [a setup with Allure](https://github.com/mkmozgawa/cypress-allure) for more colourful test reports that your upper management is going to luv. Snatch them from `allure-report/`.
