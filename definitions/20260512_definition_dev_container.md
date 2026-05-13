---
title: 'Dev Container'
description:
  'A Dev Container is a repository-defined development environment that tools like Daytona can build and open consistently.'
---

# Dev Container

## Definition

A Dev Container is a development environment described by files in a repository,
usually under `.devcontainer/devcontainer.json`. It defines the base image,
dependencies, editor settings, forwarded ports, and setup commands needed to
work on a project.

Dev Containers help teams avoid local setup drift. Instead of asking each
developer to manually install the right language runtime, system packages, and
extensions, the project declares the environment once and compatible tools build
it repeatably.

In Daytona, a Dev Container lets a workspace start with the same dependencies
and defaults every time. That makes it especially useful for AI engineering
workflows where the assistant needs to inspect files, run commands, and validate
changes inside a predictable project environment.
