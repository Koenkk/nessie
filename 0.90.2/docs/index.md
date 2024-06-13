---
title: "Nessie 0.90.2"
---

# Nessie 0.90.2

GitHub [release page](https://github.com/projectnessie/nessie/releases/tag/nessie-0.90.2) for 0.90.2.

For all download options, refer to the [Downloads page](../downloads/index.md).


## Download options for this Nessie 0.90.2 release

### Nessie Server as Docker image

Docker images are multiplatform images for amd64, arm64, ppc64le, s390x.

=== "GitHub Container Registry"
    [![ghcr.io GitHub Container Registry](https://img.shields.io/maven-central/v/org.projectnessie.nessie/nessie?label=quay.io+Docker&logo=docker&color=3f6ec6&style=for-the-badge&logoColor=white)](https://ghcr.io/projectnessie/nessie)
    ```bash
    docker pull ghcr.io/projectnessie/nessie:0.90.2
    docker run -p 19120:19120 ghcr.io/projectnessie/nessie:0.90.2
    ```
=== "Quay.io"
    [![quay.io Quay](https://img.shields.io/maven-central/v/org.projectnessie.nessie/nessie?label=quay.io+Docker&logo=docker&color=3f6ec6&style=for-the-badge&logoColor=white)](https://quay.io/repository/projectnessie/nessie?tab=tags)
    ```bash
    docker pull quay.io/projectnessie/nessie:0.90.2
    docker run -p 19120:19120 quay.io/projectnessie/nessie:0.90.2
    ```

### Nessie Server Helm Chart

=== "Artifact Hub"
    [![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/nessie&color=3f6ec6&labelColor=&style=for-the-badge&logoColor=white)](https://artifacthub.io/packages/search?repo=nessie)
=== "Nessie Helmchart Repo"
    [https://charts.projectnessie.org/](https://charts.projectnessie.org/)
=== "Tarball"
    [Nessie 0.90.2 Helm Chart](https://github.com/projectnessie/nessie/releases/download/nessie-0.90.2/nessie-helm-0.90.2.tgz)

### Nessie Server as a standalone uber jar

Requires Java 17 or newer.

```bash
curl -L -o nessie-quarkus-0.90.2-runner.jar \
  https://github.com/projectnessie/nessie/releases/download/nessie-0.90.2/nessie-quarkus-0.90.2-runner.jar
java -jar nessie-quarkus-0.90.2-runner.jar
```

### Nessie CLI as a standalone uber jar

Requires Java 11 or newer.

```bash
curl -L -o nessie-cli-0.90.2.jar \
  https://github.com/projectnessie/nessie/releases/download/nessie-0.90.2/nessie-cli-0.90.2.jar
java -jar nessie-cli-0.90.2.jar
```

## Nessie GC Tool as Docker image

Docker images are multiplatform images for amd64, arm64, ppc64le, s390x.

=== "GitHub Container Registry"
    [![ghcr.io GitHub Container Registry](https://img.shields.io/maven-central/v/org.projectnessie.nessie/nessie?label=ghcr.io+Docker&logo=docker&color=3f6ec6&style=for-the-badge&logoColor=white)](https://github.com/projectnessie/nessie/pkgs/container/nessie-gc)
    ```bash
    docker pull ghcr.io/projectnessie/nessie-gc:0.90.2
    docker run -p 19120:19120 ghcr.io/projectnessie/nessie-gc:0.90.2 --help
    ```
=== "Quay.io"
    [![quay.io Quay](https://img.shields.io/maven-central/v/org.projectnessie.nessie/nessie?label=quay.io+Docker&logo=docker&color=3f6ec6&style=for-the-badge&logoColor=white)](https://quay.io/repository/projectnessie/nessie-gc?tab=tags)
    ```bash
    docker pull quay.io/projectnessie/nessie-gc:0.90.2
    docker run -p 19120:19120 quay.io/projectnessie/nessie-gc:0.90.2 --help
    ```

### Nessie GC Tool as a standalone uber jar

Requires Java 11, Java 17 recommended.

```bash
curl -L -o nessie-gc-0.90.2.jar \
  https://github.com/projectnessie/nessie/releases/download/nessie-0.90.2/nessie-gc-0.90.2.jar
java -jar nessie-gc-0.90.2.jar
```

### Nessie Repository Management tool as a standalone uber jar

Requires Java 17 or newer.

```bash
curl -L -o nessie-server-admin-tool-0.90.2-runner.jar \
  https://github.com/projectnessie/nessie/releases/download/nessie-0.90.2/nessie-server-admin-tool-0.90.2-runner.jar
java -jar nessie-server-admin-tool-0.90.2-runner.jar
```

### Nessie REST API

=== "View on Swagger Hub"
    [![Swagger Hub](https://img.shields.io/badge/swagger%20hub-nessie-3f6ec6?style=for-the-badge&logo=swagger&link=https%3A%2F%2Fapp.swaggerhub.com%2Fapis%2Fprojectnessie%2Fnessie)](https://app.swaggerhub.com/apis/projectnessie/nessie/0.90.2)
=== "Download"
    [OpenAPI Download](https://github.com/projectnessie/nessie/releases/download/nessie-0.90.2/nessie-openapi-0.90.2.yaml)

### Nessie artifacts on Maven Central

[![Maven Central](https://img.shields.io/maven-central/v/org.projectnessie.nessie/nessie?label=Maven%20Central&logo=apachemaven&color=3f6ec6&style=for-the-badge&logoColor=white)](https://search.maven.org/artifact/org.projectnessie.nessie/nessie)

### License Reports

License reports for this release are [available via this link (zip file)](https://github.com/projectnessie/nessie/releases/download/nessie-0.90.2/nessie-aggregated-license-report-0.90.2.zip).