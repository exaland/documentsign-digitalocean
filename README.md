# DocuSeal DigitalOcean

The deploy button on the DigitalOcean platform. [DocuSeal](https://www.docuseal.com/) is an open source DocuSign alternative

[![Deploy on DigitalOcean](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/exaland/documentsign-digitalocean/tree/master)

## How to use

- Click the DigitalOcean button 👆
- Follow the DigitalOcean instructions until the ***"Environment Variables"*** step
- Click **"Edit"** on the ***"Environment Variables"*** step
- Generate a 64 byte value for the **SECRET_KEY_BASE** environment variable. You can do this with `openssl rand -hex 64` or any other way you like
- Click the **"Encrypt"** checkbox for this environment variable. ⚠️ This is important for security
- Click **"Save"** and follow the instructions provided by the DigitalOcean platform
- You will be able to use all the features of [DocuSeal](https://www.docuseal.com/) as soon as the build is completed

## How to update?

**Step 1: Open the dashboard and select the deployed DocuSeal instance**

To begin, go to the following link to access the dashboard: `https://cloud.digitalocean.com/apps`

**Step 2: Click on the "Actions" drop-down menu**

Once you are on the dashboard, find and click on the "Actions" drop-down menu. It is typically located next to or above the listed applications.

<img src="https://github.com/docusealco/docuseal/assets/1176367/23067ba9-012d-4ba0-8df7-f4c5e2696324" width="600">

**Step 3: Click on the "Force Rebuild & Deploy" option**

From the "Actions" drop-down menu, select the "Force Rebuild & Deploy" option. This action will initiate the rebuild and deployment process for the selected DocuSeal instance.

<img src="https://github.com/docusealco/docuseal/assets/1176367/5ccf202f-4f94-41a4-8efb-f912257a7f6d" width="600">

**Step 4: Wait for the deployment process to complete**

Once you have clicked on "Force Rebuild & Deploy," the deployment process will begin. The duration of the process may vary depending on the complexity of the application and server resources.

Please be patient and allow the deployment process to complete. After completion, the DocuSeal instance will be successfully rebuilt and deployed with the latest changes. You can now use the updated version of the application.
