# team-env

An example Coder workspace with a lot of powerful features.

Open in clean.demo.coder.com:

[![Open in Coder](https://clean.demo.coder.com/static/image/embed-button.svg)](https://clean.demo.coder.com/wac/build?template_oauth_service=625ff6b7-9e0fbb71f34a2ed66ae5a2e5&template_url=https://github.com/mtm20176/applications.git&template_ref=main&template_filepath=.coder/coder.yaml)

![Coder dashboard preview](preview.png)

## Applications

- Remote desktop from web browser (VNC + noVNC)
    - Insomnia 
- Podman (container management GUI)
- code-server (specific version)
- JupyterLab (via dev URL)

## Custom image

- Extends Coder's [VNC](https://github.com/cdr/enterprise-images/tree/main/images/vnc) image to include remote desktop support
- Custom image that installs applications, dev tools, and dependencies

## Workspace template

- See template in [.coder/coder.yaml](.coder/coder.yaml)