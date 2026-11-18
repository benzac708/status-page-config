# status-page-config

Kustomize base and Argo CD application for the status page. Argo CD watches this repo.

- `base/` — Deployment, Service, RBAC, Kustomization
- `app.yaml` — Argo CD Application pointing at `base/`

Image tag updates come from CI in the status-page repo.