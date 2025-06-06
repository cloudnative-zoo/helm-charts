# Helm Charts

This repository contains a collection of Helm charts maintained by the CloudNative Zoo team. Helm charts help you define, install, and upgrade Kubernetes applications.

## Repository Structure

- Each directory contains a separate Helm chart.
- Charts follow the [Helm best practices](https://helm.sh/docs/chart_best_practices/).

## Usage

1. **Add the repository:**
   ```sh
   helm repo add cloudnative-zoo https://github.com/cloudnative-zoo/helm-charts
   ```

2. **Install a chart:**
   ```sh
   helm install <release-name> cloudnative-zoo/<chart-name>
   ```

3. **Upgrade a chart:**
   ```sh
   helm upgrade <release-name> cloudnative-zoo/<chart-name>
   ```

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a clear description of your changes.

## License

This repository is licensed under the MIT License.
