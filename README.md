# helm-pull-postgresql

Mirror Bitnami PostgreSQL Helm chart images to Artifactory via reusable workflows from `adrian91ro/cicd-templates`.

## Required GitHub secrets

- `ARTIFACTORY_CONTAINER_REGISTRY_HOST`
- `ARTIFACTORY_HELM_REGISTRY_HOST`
- `ARTIFACTORY_CONTAINER_REPO`
- `ARTIFACTORY_USERNAME`
- `ARTIFACTORY_TOKEN`
- `RELEASE_API_TOKEN`

## Workflows

- `Helm Chart Mirror (main)`
- `Create New Release` (runs after mirror success)
