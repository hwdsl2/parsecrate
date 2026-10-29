# Changelog

Notable changes to ParseCrate are documented here.

## 2026-10-24

Release: `2026.10.1`

### Changed

- Established the first tagged source release. Docker images continue to update
  independently through existing moving tags.

## 2026-10-19

### Added

- Added a Google Colab demo for document conversion to Markdown and
  structured JSON, with sample documents and authenticated API examples.

## 2026-10-07

### Changed

- Rebranded as ParseCrate (formerly `docker-docling`); the Docker image name
  remains `hwdsl2/docling-server`.

## 2026-07-09

### Added

- Added anonymous aggregate deployment/upgrade counts. Opt out with
  `DOCLING_DISABLE_USAGE_COUNTS=1`.

## 2026-06-20

### Added

- Added automatic API-key generation for fresh installs with persistent
  storage and key retrieval through `docling_manage --getkey`. Conversion and
  chunking requests use the `X-Api-Key` header when authentication is enabled.
  Existing volumes without a key retain their previous authentication behavior.

## Earlier notable changes

- Added CPU and NVIDIA CUDA images for document conversion, with persistent
  model storage and management commands for model downloads and server info.
