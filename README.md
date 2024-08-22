# Helm Charts Repository

Welcome to my Helm Charts repository! This repository contains Helm charts for various services and applications, starting with RabbitMQ, MongoDB, and PostgreSQL. Over time, I will be adding more charts as I develop and maintain them.

## Repository Structure

The repository is organized into different folders, each representing a Helm chart for a specific service or application:

- **RabbitMQ/**: Contains the Helm chart for deploying RabbitMQ.
- **MongoDB/**: Contains the Helm chart for deploying MongoDB.
- **Postgres/**: Contains the Helm chart for deploying PostgreSQL.

More Helm charts will be added to this repository in the future.

## How to Use

To use the Helm charts from this repository, follow these steps:

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/Marzia-Jahan-Momo/Helm-Charts.git
cd helm-charts
```

### 2. Install a Helm Chart

Navigate to the directory of the Helm chart you want to install. For example, to install RabbitMQ:

```bash
cd rabbitmq
```

Run the following command to install the Helm chart:

```bash
helm install rabbitmq .
```

You can replace `rabbitmq` with your desired release name.

### 3. Customize Values

Each Helm chart comes with a `values.yaml` file that you can customize according to your needs. Modify this file before running the `helm install` command to configure the deployment to suit your environment.

### 4. Upgrade or Uninstall

To upgrade an existing release:

```bash
helm upgrade my-rabbitmq .
```

To uninstall a release:

```bash
helm uninstall my-rabbitmq
```

### 5. Adding New Charts

When new charts are added to the repository, you can follow the same steps to deploy them.

## Contributing

If you have suggestions or improvements for these Helm charts, feel free to fork the repository, make your changes, and submit a pull request.
