# Welcome to the interLink organization home!

This organization is the home for the interLink project, an initiative focused on bridging the gap between Kubernetes and diverse remote resource management systems. Our goal is to simplify the process of extending Kubernetes workloads beyond traditional cluster boundaries, enabling seamless execution of pods on a variety of infrastructures.

## About interLink

interLink serves as an abstraction layer that makes it easier to run Kubernetes pods on remote resources capable of managing container lifecycles. By providing a generic API between VirtualKubelet and provider-specific logic, we aim to:

* **Simplify Plugin Development:** Empower resource providers to integrate with VirtualKubelet without deep knowledge of Kubernetes internals.
* **Enable Broad Resource Integration:** Facilitate the connection of Kubernetes with a wide range of platforms, as demonstrated by our example plugins for Docker and Singularity (targeting remote SLURM systems).
* **Foster Extensibility:** Encourage the development of new plugins to support an ever-growing ecosystem of resource providers.


## Explore Our Repositories

Our primary project is:

* **[interLink](https://github.com/interlink-hq/interLink)**: The core repository containing the source code for the interLink abstraction layer, API definitions, and example plugins.

We encourage you to explore the interLink repository to learn more about its architecture, examine the example plugins, and understand how you can leverage it to integrate your resource management system with Kubernetes.

## Get Involved

We believe in the power of open collaboration and welcome contributions from the community. If you are interested in getting involved, please:

* Read our [Contributing Guidelines](https://github.com/interTwin-eu/interLink/blob/main/CONTRIBUTING.md) to understand how you can contribute to the project.
* Check our [Issue Tracker](https://github.com/interTwin-eu/interLink/issues) for existing issues and opportunities to contribute.
* Consider submitting bug reports, suggesting new features, or contributing code changes.

## License

All projects within the interTwin-eu organization, including interLink, are released under the permissive [Apache-2.0 License](https://github.com/interTwin-eu/interLink/blob/main/LICENSE). This license allows for broad use, modification, and distribution of our software.

## Maintainers

The interLink project is actively maintained by the [interTwin-eu](https://github.com/interTwin-eu) organization. For specific maintainer information, please refer to the [MAINTAINERS.md](https://github.com/interTwin-eu/interLink/blob/main/MAINTAINERS.md) file within the interLink repository. We also appreciate the contributions of our [community members](https://github.com/interTwin-eu/interLink/graphs/contributors).

## Support

While we are continuously working on improving our documentation and support resources, the best way to seek assistance at this time is to:

* **Open an issue** on the relevant repository (e.g., [interLink Issues](https://github.com/interTwin-eu/interLink/issues)) to report bugs or ask questions.
* Check the project website ([https://intertwin-eu.github.io/interLink/](https://intertwin-eu.github.io/interLink/)) for any potential updates or contact information.

## Stay Connected

We encourage you to stay updated on the latest developments and announcements related to the interLink project and the interTwin-eu organization. You can do this by:

* **Watching** the [interLink repository](https://github.com/interTwin-eu/interLink).
* Checking the [interTwin-eu website](https://intertwin-eu.github.io/interLink/) for news and updates.

