---
title: Introduction to GitHub Actions
description: >
  Docker maintains a set of official GitHub Actions for building Docker images.
keywords: ci, github actions, gha,  build, introduction, tutorial
redirect_from:
  - /ci-cd/github-actions/
  - /build/ci/github-actions/examples/
---

GitHub Actions is a popular CI/CD platform for automating your build, test, and
deployment pipeline. Docker provides a set of official GitHub Actions for you to
use in your workflows. These official actions are reusable, easy-to-use
components for building, annotating, and pushing images.

The following GitHub Actions are available:

- [Build and push Docker images](https://github.com/marketplace/actions/build-and-push-docker-images){:target="blank" rel="noopener" class=""}:
  build and push Docker images with BuildKit.
- [Docker Login](https://github.com/marketplace/actions/docker-login){:target="blank" rel="noopener" class=""}:
  sign in to a Docker registry.
- [Docker Setup Buildx](https://github.com/marketplace/actions/docker-setup-buildx){:target="blank" rel="noopener" class=""}:
  initiates a BuildKit builder.
- [Docker Metadata action](https://github.com/marketplace/actions/docker-metadata-action){:target="blank" rel="noopener" class=""}:
  extracts metadata from Git reference and GitHub events.
- [Docker Setup QEMU](https://github.com/marketplace/actions/docker-setup-qemu){:target="blank" rel="noopener" class=""}:
  installs [QEMU](https://github.com/qemu/qemu) static binaries for multi-arch
  builds.
- [Docker Buildx Bake](https://github.com/marketplace/actions/docker-buildx-bake){:target="blank" rel="noopener" class=""}:
  enables using high-level builds with [Bake](../../bake/index.md).

Using Docker's actions provides an easy-to-use interface, while still allowing
flexibility for customizing build parameters.

## Examples

If you're looking for examples on how to use the Docker GitHub Actions,
refer to the following sections:

- [Cache management](cache.md)
- [Configuring your builder](configure-builder.md)
- [Copy image between registries](copy-image-registries.md)
- [Export to Docker](export-docker.md)
- [Local registry](local-registry.md)
- [Manage tags and labels](manage-tags-labels.md)
- [Multi-platform image](multi-platform.md)
- [Named contexts](named-contexts.md)
- [Push to multiple registries](push-multi-registries.md)
- [Secrets](secrets.md)
- [Share built image between jobs](share-image-jobs.md)
- [Test before push](test-before-push.md)
- [Update Docker Hub repository description](update-dockerhub-desc.md)

## Get started with GitHub Actions

{% include gha-tutorial.md %}

## Next steps

This tutorial has shown you how to create a simple GitHub Actions workflow,
using the official Docker actions, to build and push an image to Docker Hub.

There are many more things you can do to customize your workflow to better suit
your needs. To learn more about some of the more advanced use cases, take a look
at the advanced examples, such as [building multi-platform images](multi-platform.md),
or [using cache storage backends](cache.md) and also how to [configure your builder](configure-builder.md).
