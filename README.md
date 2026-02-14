# Prometheus Monitoring Project

## Overview
This project is a Node.js application that integrates with Prometheus for monitoring metrics. It uses Express as the web framework and provides an endpoint to simulate user data retrieval.

## Features
- User data retrieval endpoint
- Prometheus metrics integration
- Docker support for easy deployment

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sumeetghumare4/prometheus-monitoring.git
   cd prometheus-monitoring
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application
1. Build the application:
   ```bash
   npm run build
   ```
2. Start the application:
   ```bash
   npm start
   ```
3. Access the application at `http://localhost:3000/user`

## Docker Deployment
To run the application using Docker, use the following command:
```bash
docker-compose up
```
This will start the Node.js application, Prometheus, and Grafana services.

## Accessing Prometheus and Grafana

- Access Prometheus at `http://localhost:9090`
- Access Grafana at `http://localhost:3001`

## Configuration
- The Prometheus configuration is located in `prometheus.yml`.
- The application exposes metrics that can be scraped by Prometheus.

## License
This project is licensed under the ISC License.
