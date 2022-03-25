# openvscodedocker
Testing a docker file for Open VS Code, Theia and default gitpod

The link below constructs an OpenVSCode image to edit this Github project. The image was already created, it reuses already installed components.  It also tests images of Theia and default gitPod editor.

The image could be executed locally using Docker directly.

<a href="https://gitpod.io/from-referrer" rel="nofollow"><img src="https://camo.githubusercontent.com/6d5cc21f7c63bda76f682cd92905510feedb519f8af7b37b83e732eed068bbdc/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f476974706f642d72656164792d2d746f2d2d636f64652d3930386138353f6c6f676f3d676974706f64" alt="Gitpod ready-to-code" data-canonical-src="https://img.shields.io/badge/Gitpod-ready--to--code-908a85?logo=gitpod" style="max-width: 100%;"></a>

# Overview

It creates a docker image based on a docker file (.gitpod.Dockerfile_full) of OpenVSCode server. It uses an existing image of Open VS Code. 

The **gitpod.yml** and the **docker file(s)** can be configured to add any kind of extension supported by the GitPod execution server or to specify which components need to be installed.

It edits the workspace defined in the Github repository. This workspace has this README file, but it could be any supported workspace (Java, C, Python, C++, etc.)

After the file is edited, it should be commited back to Github.

A self-hosted git pod would be needed if additional functionalities are required, or to keep 'control' over the repository.

*Note:*  the overview section was edited and commited using the created VS Code instance.





