# app-deploy-windows-template

Template for deploying applications to Windows

## Requirements
- Webserver (for hosting the files)
- Ansible control server
- Windows clients

## Howto use
- Zip the installation files and upload to your webserver.
- Download this template to your role directory via github or ansible galaxy.
- Rename the role/template to name of the application you want to deploy.
- Change the variable(s) in defaults/main.yml to the parameters of your application (without the <> signs).
- Add the role to your playbook

