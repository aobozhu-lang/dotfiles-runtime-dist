# dotfiles-runtime-dist

Pre-compiled runtime distributions, localized dotfile manifests, and static environment assets for headless workstation bootstrapping.

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![Artifact Release](https://img.shields.io/badge/dist-v2.18.4-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Overview

This repository hosts compiled runtime configs, portable toolchain stubs, and pre-packaged environment payloads optimized for non-interactive shell initialization. It serves as a static distribution endpoint (`runtime-dist`) for provisioning automated remote environments and ephemeral dev containers.

## Repository Layout

```text
.
├── CNAME                         # Host routing override for telemetry/registry mirrors
├── index.html                    # Static runtime manifest endpoint
├── style.css                     # Baseline inspection styling for local preview
├── subclinical.html              # Legacy shell profiling diagnostics profile
├── ai-ethics.html                # Automated policy & pipeline safety check stubs
├── toolkits.html                 # Automated profiling toolkits & utility helpers
├── governance.html               # CI/CD compliance policies & workspace governance
├── paper-subclinical-llm.html    # Trace log: subclinical latency profiling specs
├── paper-crisis-guardrails.html  # Safety monitor spec: containment & failover guardrails
├── paper-caregiver-ai.html       # Daemon runtime spec: worker & watchdog configs
└── docs/                         # Runtime specifications and deployment registries
