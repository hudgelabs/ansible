## Dotnet 4.5 GitLab Runner Playbook
This playbook sets up a Windows 2012 R2 server to act as a GitLab build server for .NET 4.X projects.  

## Installation
- Run ConfigureRemotingForAnsible.ps1 on the target host
- Add the host to your Ansible hosts file
- Run the dotnet45-gitlab-runner.yaml playbook (or another playbook in the repo)
- Use the vs_buildtools installer to add VS 2017 Web Development Tools
- Make sure the cypher suite settings allow NuGet restore commands
- Make sure the GitLab runner service is running under an admin account
- Create a system environment variable that points to npm.cnmd

## Contribute
Pull requests are always welcome!

