# Docker image for MetaCubeX/mihomo

This repository provides a GitHub Actions workflow for building container images from [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo).

- Release builds run weekly and follow the latest upstream release tag. Images are published as `ghcr.io/[owner]/mihomo:release-[version]` and `ghcr.io/[owner]/mihomo:latest`.
- Alpha builds are manual only and use the latest upstream `Alpha` branch commit. Images are published as `ghcr.io/[owner]/mihomo:alpha-[sha]`, where `sha` is the first 7 characters of the commit SHA.
- Each image is built for `linux/amd64`, `linux/arm/v6`, `linux/arm/v7`, and `linux/arm64`.
