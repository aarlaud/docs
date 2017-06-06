---
title: ""
---

Snyk's Cloud Foundry integration lets you monitor the deployed code of your Java, Node.js and Ruby Cloud Foundry applications for any known vulnerabilities found in the application's dependencies, testing at a frequency you control.

For each test, Snyk will communicate directly with Cloud Foundry to determine exactly what code is currently deployed and what dependencies are being used. Each dependency will in turn be tested against Snyk's vulnerability database to see if it contains any known vulnerabilities.

If vulnerabilities are found, you will be alerted (via email or Slack) so that you can take immediate action.

In order to turn on the Cloud Foundry integration you'll need to:

1. [Connect to Cloud Foundry](#connecting-snyk-to-cloud-foundry) from the integrations page
3. [Select the projects you want to monitor](#adding-cloud-foundry-apps-to-snyk) and click "Add to Snyk"
