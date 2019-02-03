This repo contains script (setup.sh) for installing tools for a fast build agent, to be used by both teamcity and vsts/azure devops.

1. Get a physical box with 64gb ram.
2. Supply a serverUrl, in buildAgent.properties, to your Teamcity server. After the agent has been installed, approve it in the server.
3. Generate PAT (Personal Access Token) from https://XXXXX.visualstudio.com/_usersSettings/tokens and enter it when running the setup.sh script.
