## Dotnet 4.5 GitLab Runner Playbook
This playbook sets up a Windows 2012 R2 server to act as a GitLab build server.  

## Installation
- ansible-playbook dotnet-gitlab-runner.yaml
- find the VS_BuildTools file on the target host and install web development tools manually
- make sure the GitLab Runner service is running as a user that's an admin on the machine
- set a system-wide npm environment variable that provides the path to npm.cmd
- make sure the cypher suite settings allow NuGet packages to be restored (talk to Bob)

## Contribute
Pull requests are always welcome!

