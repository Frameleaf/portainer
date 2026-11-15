# Frameleaf template for Portainer

[Frameleaf](https://frameleaf.app) is a self-hosted photo and video library. This repository is a Portainer app template list with one template: the Frameleaf stack (server, machine learning and PostgreSQL).

## Use it

1. In Portainer, open **Settings → App Templates**.
2. Set the URL to `https://raw.githubusercontent.com/Frameleaf/portainer/main/templates.json` and save.
3. Open **App Templates**, choose **Frameleaf**, set a database password (letters and digits only) and deploy.
4. Open port `2283` and create the admin account in the browser.

Guide: [frameleaf.app/docs/start/other-install-methods](https://frameleaf.app/docs/start/other-install-methods/#portainer). The stack follows the latest Frameleaf release. Frameleaf is in beta: keep another copy of your photos and videos.

CI checks that each template's stack file uses only the template's variables, then starts the stack and checks the server and machine learning.

Source: [Frameleaf/frameleaf-app](https://github.com/Frameleaf/frameleaf-app) (AGPL-3.0). Questions: support@frameleaf.app.
