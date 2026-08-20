# Environmental Monitoring Dashboard

> Coursework project. This dashboard visualizes example temperature and motion telemetry from a Raspberry Pi-to-API data pipeline; it is not represented as an active production monitoring service.

A React dashboard for viewing temperature and motion trends, metric summaries, and combined environmental data visualizations.

## System context

```text
Raspberry Pi sensor logger → Flask API → React dashboard
```

Related repositories:

- [Raspberry Pi sensor logger](https://github.com/AxelDiazA2G/environmental-monitoring-raspberry-pi)
- [Flask telemetry API](https://github.com/AxelDiazA2G/environmental-monitoring-api)

## What it demonstrates

- React data visualization for temperature and motion measurements
- Metric cards, individual charts, and combined views
- HTTP integration with a Flask-backed telemetry API
- A coursework-scale sensor-to-dashboard architecture

## Run locally

```bash
npm install
npm start
```

The application starts on [http://localhost:3000](http://localhost:3000).

## Data-source note

The front end contains legacy API endpoint configuration in `src/App.js`. Deployment availability is not asserted; update those endpoints for a local or approved environment before relying on runtime data.
