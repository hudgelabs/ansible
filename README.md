## Ansible Playbooks
This project is a collection of Ansible playbooks that I have written throughout my career. 

## Motivation
Ansible is one of my favorite tools for infrastructure automation and I thought other DevOps Engineers might find these playbooks useful.

## Features
Automate the configuration of a self-hosted .NET 4.X GitLab Runner with the dotnet45-gitlab-runner.yaml playbook.

## Installation
[Installing Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## How to use?
- Run ConfigureRemotingForAnsible.ps1 on the target host
- Add the host to your Ansible hosts file
- Run the dotnet45-gitlab-runner.yaml playbook (or another playbook in the repo)
- Use the vs_buildtools installer to add VS 2017 Web Development Tools
- Make sure the cypher suite settings allow NuGet restore commands
- Make sure the GitLab runner service is running under an admin account
- Create a system environment variable that points to npm.cnmd

## Contribute
Pull requests are always welcome!

## Credits
Shout out to Jeff Puckett for inspiring me to learn Ansible.
