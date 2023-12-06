## Configuration

The following table lists the configurable parameters and their default values:

| Parameter | Description | Default |
|-----------|-------------|---------|
| `nginx.replicaCount` | Number of Nginx replicas | `1` |
| `nginx.image.repository` | Nginx image repository | `nginxinc/nginx-unprivileged` |
| `nginx.image.tag` | Nginx image tag | `1.25.3-alpine-slim` |
| `nginx.resources.requests.memory` | Memory request for Nginx | `10Mi` |
| `nginx.resources.requests.cpu` | CPU request for Nginx | `1m` |
| ... | ... | ... |

For more configuration options, refer to the [`values.yaml`](admin-dashboard/values.yaml) file.