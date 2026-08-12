# Jupyter Dashboard Builder
Automatically builds dashboards from https://github.com/jupyterhub/grafana-dashboards with jsonnet + applies patches.

Runs weekly via github actions.

Publishes kubernetes manifest to [manifests/grafana-dashboards-cm.yaml](manifests/grafana-dashboards-cm.yaml)
