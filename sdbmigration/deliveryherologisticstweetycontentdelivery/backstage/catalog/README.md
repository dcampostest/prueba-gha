# Developer Portal Software Catalog

> The Developer Portal Software Catalog is a centralized system that keeps track of ownership and metadata for all the software in the Delivery Hero's ecosystem (services, websites, libraries, data pipelines, etc). The catalog is built around the concept of metadata YAML files stored together with the code, which are then harvested and visualized on the Developer Portal.

Each YAML file contains one or more `kinds` that are describing the software to be illustrated on the Developer Portal. The teams responsible for maintaining these files are declaratively annotating the software information, expressing it, and thus making it understandable to the Developer Portal.

This folder contains the `kinds` that are available in the Developer Portal terminology and they are describing the surrounding sourcecode. Based on the value provided for the `kind` the corresponding entity will be managed by the Developer Portal.
