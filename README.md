# kubernetes-datascience-launcher

Deploys a data science tool suite to a local Kubernetes distributed compute cluster by helping to integrate a broad spectrum of high quality opensource software. Each tool is made available depending on use case, without requiring the end user to seek out, individually install, configure, update, and integrate disparate tooling into new or existing analysis workflows.

Each component dependency is pulled from each respective upstream project and/or docker repository, and no upstream code is ever modified. Different industries and user roles have varied needs; as such the platform is fully customizable in that analytic containers can be added, removed, or rolled back to earlier versions depending on host infrastructure and the applicable template.
