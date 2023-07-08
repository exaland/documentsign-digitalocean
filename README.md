# DocuSeal DigitalOcean

The deploy button on the DigitalOcean platform. [DocuSeal](https://www.docuseal.co/) is an open source DocuSign alternative

[![Deploy on DigitalOcean](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/docusealco/docuseal-digitalocean/tree/master&refcode=421d50f53990)

## How to use

- Click the DigitalOcean button 👆
- Follow the DigitalOcean instructions until the ***"Environment Variables"*** step
- Click **"Edit"** on the ***"Environment Variables"*** step
- Generate a 64 byte value for the **SECRET_KEY_BASE** environment variable. You can do this with `openssl rand -hex 64` or any other way you like
- Click the **"Encrypt"** checkbox for this environment variable. ⚠️ This is important for security
- Click **"Save"** and follow the instructions provided by the DigitalOcean platform
- You will be able to use all the features of [DocuSeal](https://www.docuseal.co/) as soon as the build is completed
