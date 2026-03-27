# Contributing to PicoClaw Fleet

Thank you for your interest in contributing to PicoClaw Fleet! This skill enables orchestration of remote PicoClaw workers over SSH.

## Overview

PicoClaw Fleet is an OpenClaw skill for deploying and orchestrating PicoClaw workers across multiple remote machines via SSH.

## Getting Started

### Prerequisites

- OpenClaw installed
- SSH access to target machines
- PicoClaw binary compatible with target architectures

### Development Setup

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/picoclaw-fleet.git
   cd picoclaw-fleet
   ```

3. Review the SKILL.md file for usage instructions

## How to Contribute

### Reporting Issues

- Check existing issues first
- Provide clear reproduction steps
- Include environment details (OS, architecture, OpenClaw version)
- Attach relevant logs

### Suggesting Features

- Open an issue describing the feature
- Explain the use case
- Discuss implementation approach

### Code Contributions

1. Create a feature branch:
   ```bash
   git checkout -b feature/my-feature
   ```

2. Make your changes
3. Test thoroughly on different architectures (amd64, arm64, riscv64)
4. Update documentation
5. Submit a pull request

## Areas for Contribution

### Scripts

- `scripts/deploy.sh` - Deployment improvements
- `scripts/dispatch.sh` - Task dispatching enhancements
- `scripts/fleet-status.sh` - Status checking improvements

### Configuration

- Support for additional providers
- Better configuration validation
- Template improvements

### Documentation

- Usage examples
- Troubleshooting guides
- Architecture-specific guides

## Code Style

### Shell Scripts

- Use `#!/bin/bash` with `set -euo pipefail`
- Add error handling
- Include informative error messages
- Document functions with comments

### Configuration Files

- Use JSON with clear structure
- Include comments in documentation
- Validate against schema

## Testing

- Test on multiple architectures
- Verify SSH key handling
- Check error scenarios
- Validate configuration parsing

## Pull Request Process

1. Update SKILL.md if changing behavior
2. Update README.md if adding features
3. Add tests for new functionality
4. Ensure all tests pass
5. Request review from maintainers

## Documentation

- Keep SKILL.md as the primary reference
- Update PROJECT-STATUS.md for roadmap changes
- Add examples for complex features

## Release Process

- Follow semantic versioning
- Update CHANGELOG (if created)
- Tag releases appropriately

## Questions?

Open an issue or join existing discussions.

Thank you for improving PicoClaw Fleet!
