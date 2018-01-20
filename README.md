[![Open Issues](https://img.shields.io/github/issues/cptactionhank/docker-atlassian-jira.svg)](https://github.com/cptactionhank/docker-atlassian-jira/issues) [![Stars on GitHub](https://img.shields.io/github/stars/cptactionhank/docker-atlassian-jira.svg)](https://github.com/cptactionhank/docker-atlassian-jira/stargazers) [![Forks on GitHub](https://img.shields.io/github/forks/cptactionhank/docker-atlassian-jira.svg)](https://github.com/cptactionhank/docker-atlassian-jira/network) [![Stars on Docker Hub](https://img.shields.io/docker/stars/cptactionhank/atlassian-jira.svg)](https://hub.docker.com/r/cptactionhank/atlassian-jira/) [![Pulls on Docker Hub](https://img.shields.io/docker/pulls/cptactionhank/atlassian-jira.svg)](https://hub.docker.com/r/cptactionhank/atlassian-jira/)

# Atlassian JIRA Core in a Docker container

This is a containerized installation of Atlassian JIRA Core with Docker, and it's a match made in heaven for us all to enjoy. The aim of this image is to keep the installation as straight forward as possible, but with a few Docker related twists.

## I'm in the fast lane! Get me started

To quickly get started running a JIRA Core instance, use the following command:
```bash
docker run --detach --publish 8080:8080 cptactionhank/atlassian-jira:latest
```

Then simply navigate your preferred browser to `http://[dockerhost]:8080` and finish the configuration.
