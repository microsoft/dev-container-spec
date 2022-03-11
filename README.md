# Development Containers

This repository is for issues to shape the direction of development containers and the development container CLI.

A development container allows you to use a Docker container as a full-featured development environment. It can be used to run an application, to separate tools, libraries, or runtimes needed for working with a codebase, and to aid in continuous integration and testing.

The Development Containers Specification seeks to find ways to enrich existing formats with common development specific settings, tools, and configuration while still providing a simplified, un-orchestrated single container option – so that they can be used as coding environments or for continuous integration and testing.

The first format in the specification, devcontainer.json, was born out of necessity. It is a structured metadata format that tools can use to store any needed configuration required to develop inside of local or cloud-based containerized coding. While this metadata can be persisted in a devcontainer.json today, we envision that this same structured data can be embedded in images and other formats – all while retaining a common object model for consistent processing.

Beyond repeatable setup, these same development containers provide consistency to avoid environment specific problems across developers and centralized build and test automation services. The open-source CLI reference implementation can either be used directly or integrated into product experience to use the structured metadata to deliver these benefits. It currently supports integrating with Docker Compose and a simplified, un-orchestrated single container option – so that they can be used as coding environments or for continuous integration and testing.

## Contributing and Feedback

If you are interested in contributing, please check out the [How to Contribute](contributing.md) document.

Issues related to dev container definitions can be reported in the [vscode-dev-containers repository](https://aka.ms/vscode-dev-containers).

If you have a question, you may connect with the community using any of these social platforms:

[![Twitter](docs/images/Twitter_Social_Icon_24x24.png)](https://twitter.com/code) [![Stack Overflow](docs/images/so-image-24x24.png)](https://stackoverflow.com/questions/tagged/vscode) [![VS Code Dev Community Slack](docs/images/Slack_Mark-24x24.png)](https://aka.ms/vscode-dev-community) [![VS CodeGitter](docs/images/gitter-icon-24x24.png)](https://gitter.im/Microsoft/vscode)

# License

License for this repository:

Copyright © Microsoft Corporation All rights reserved.<br />
Creative Commons Attribution 4.0 License (International): https://creativecommons.org/licenses/by/4.0/legalcode
