# BlueMatrix sell-side platform templates (STAND-IN)

Shared GitHub Actions reusable workflows generated, unedited, by Dagly `helio_catalog_artifact_v1` (converter e9375be354df) from the BlueMatrix GoCD templates DockerAppBuildTemplate, DockerAppDeployTemplate and ManualGatewayTemplate.

* `catalog-build.yml`: build once, push the image, record the immutable artifact.
* `catalog-deploy.yml`: Ansible deploy per catalog environment (qa, preprod, production), Helio-governed gates.

Helio registers catalog templates from its central repository, so the same bytes are published to `helloangular/helio-client-capacity-20260916` branch `bm-sellside-20261028` (tag `bm-sellside-20261028-v1`); the application callers pin that commit.
Stand-in values and how to swap them: `helio-test` branch `bm-sellside-standin-20261028`, `scripts/bluematrix/bm_sellside_20261028/mapping/`.
