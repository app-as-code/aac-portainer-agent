# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Upstream image tracks Portainer Agent v3.0.0 as defined in `service.yml`.

## [0.0.1]

### Added

- Initial App-as-Code service definition for the Portainer Agent on port 9001.
- Bind mounts for the Docker socket, the Docker volumes directory and the host root filesystem.
- README with configuration reference and project icon.
