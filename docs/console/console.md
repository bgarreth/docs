---
title: Amplify Console
description: Amplify has a console within AWS that is a control center for your full-stack app.
disableTOC: true
---

<amplify-responsive-grid columns="1" class="margin-top-lg margin-bottom-lg">
  <docs-card external url="https://console.aws.amazon.com/amplify/home" class="border-radius" containertag="amplify-external-link">
    <img slot="graphic" src="~/assets/logo-dark.svg" />
    <h4 slot="heading">Amplify Console</h4>
    <p slot="description">
      Control center for your full-stack app deployments. Set up continuous deployment and hosting, create an app backend in the admin UI, and manage full-stack environments.
    </p>
  </docs-card>
</amplify-responsive-grid>

## Get started

The following tools and services are accessible from the Amplify Console, learn more about them here:

<amplify-responsive-grid columns="2" class="margin-top-lg margin-bottom-lg">
      <docs-card external url="https://docs.aws.amazon.com/amplify/latest/userguide/welcome.html" class="border-radius" containertag="amplify-external-link">
        <img slot="graphic" src="~/assets/console.png" />
        <h4 slot="heading">Amplify Hosting</h4>
        <p slot="description">
          Fully managed hosting with CI/CD for deploying static web apps.
        </p>
      </docs-card>
      <docs-card url="~/console/adminui/start.md" class="border-radius">
        <img slot="graphic" src="~/assets/cli.png" />
        <h4 slot="heading">Admin UI</h4>
        <p slot="description">
        Configure and manage your app backend outside the AWS console.
        </p>
      </docs-card>
</amplify-responsive-grid>


## Amplify Console app project

Every Amplify Console app project consists of frontend and backend environments. Environments allow you to build new features for your app without impacting production.

### Frontend environments

All frontend environments are managed by Amplify Hosting. A frontend environment corresponds to a Git branch for apps with CI/CD enabled. Each branch is deployed to a unique url (e.g. `https://main.appid.amplifyapp.com`). Launch your hosted web app from each frontend environment, or view your deployment details.

![frontend-environments](~/images/console/frontend-envs.gif)

### Backend environments

Each backend environment is a container for all of the cloud capabilities added to your app such as API, auth, and storage. Launch the Admin UI from each backend environment, or get to the underlying AWS service consoles.

![frontend-environments](~/images/console/backend-envs.gif)
