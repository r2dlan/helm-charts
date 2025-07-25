# Helm Charts

Welcome to the official Helm Charts repository by **r2dlan**.

This repository contains a curated collection of production-ready Helm charts developed and maintained by the r2dlan project. Each chart is designed to be modular, configurable, and optimized for real-world Kubernetes deployments.

## Usage

You can use these charts by adding our Helm repository to your local Helm setup:

```bash
helm repo add r2dlan https://r2dlan.github.io/helm-charts/
helm repo update
```

Then install any available chart like this:

```bash
helm install <release-name> r2dlan/<chart-name>
```

## Available Charts

All charts are discoverable and documented on Artifact Hub:

➡️ [Browse our charts on Artifact Hub](https://artifacthub.io/packages/search?org=r2dlan&sort=relevance&page=1)

Each chart includes versioning, changelogs, installation guides, and configuration examples.

## Structure

All charts reside under the **charts/** directory in this repository and follow Helm best practices. We use GitHub Actions to automatically package and publish charts to GitHub Pages whenever changes are pushed to **main**.

## Contributing

Pull requests and issues are welcome!

- Fork the repo
- Create your feature branch (git checkout -b feature/my-chart)
- Commit your changes
- Submit a pull request

Please follow our existing structure and test your chart before submitting.

## License

This project is licensed under the Apache 2.0 License.
