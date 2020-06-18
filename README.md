#  Trader Lite - UI for IBM Cloud Pak for Integration

The IBM Trader Lite application is a simple stock trading sample where you can create various stock portfolios and add shares of stock to each for a commission. The app is used to illustrate concepts in IBM Cloud Pak for Integration workshop taught by IBM Client Developer Advocacy

![Architectural Diagram](architecture.png)

**Tradr** is a Node.js+jQuery UI for the Trader Lite app. It handles all user interactions:

  * Creating new portfolios
  * Buying and selling stocks
  * Portfolio summary and ROI

## Building the UI app

This is a Node.js app built and tested with Node 8.17. Enter the following command from the root of the repo to install the required prereqs:

```
npm install
```

The prereqs will be installed in the **node-modules** folder.

The included [Dockerfile](Dockerfile) can be used to create an image for deployment to Kubernetes.

## Deploying the UI app

Refer to the IBM Cloud Pak for Integration workshop instructions on how this app is deployed as part of the Trader Lite app.
