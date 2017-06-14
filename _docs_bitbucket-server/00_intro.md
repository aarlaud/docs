---
title: ""
---

Snyk's Bitbucket Server integration lets you monitor the source code of your Node.js and Rubygems repos for any known vulnerabilities found in the application's dependencies, testing at a frequency you control.

This integration will works only for publicly available Bitbucket Server instances and not for bitbucket.org.

For each test, Snyk will communicate directly with Bitbucket Server to determine exactly what code is currently pushed and what dependencies are being used. Each dependency will in turn be tested against Snyk's vulnerability database to see if it contains any known vulnerabilities. 

If vulnerabilities are found, you will be alerted (via email or Slack) so that you can take immediate action.

In order to turn on the Bitbucket Server integration you'll need to:

1. [Connect to Bitbucket Server](#connecting-snyk-to-bitbucket-server) from the integrations page
2. [Add your Bitbucket Server account credentials](#generating-your-bitbucket-user) to Snyk
3. [Select the projects you want to monitor](#adding-bitbucket-server-repos) and click "Add to Snyk"
