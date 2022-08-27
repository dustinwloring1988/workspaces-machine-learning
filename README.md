# Kasm Workspaces Machine Learning

This project provides a desktop environment geared for machine learning development. It is meant as an example to using DevOps to provide a secure working environment for machine learning using the Kasm Workspaces platform.


# GPU Support

Kasm Workspaces (formally Kasm Server) version 1.9.0 and higher supports NVIDIA GPUs. The following requirements must be met.
* NVIDIA GPUs with Architecture >= Kepler (or compute capability 3.0)
* NVIDIA container toolkit must be installed on the host

The agent component will report to the API service the number of GPUs and if the Docker daemon is showing the "nvidia" runtime is available. In the Admin panel the Agents view will list all available compute (Agents) available along with the number of GPUs they are reporting. The following screenshot shows a deployment with two Agents, one with a GPU and one without.

# Docker Hub

The docker hub for this project is here: https://hub.docker.com/repository/docker/kasmcommunity/machine-learning
