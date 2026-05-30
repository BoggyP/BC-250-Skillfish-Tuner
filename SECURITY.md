# Security Policy

Killfish Tuner performs privileged operations for hardware management, including service configuration, boot persistence, fan control, and GPU tuning.

## Reporting Security Issues

If you discover a security issue, please report it privately before opening a public issue when possible.

Include:

- Description of the issue
- Affected version
- Steps to reproduce
- Potential impact
- Suggested fix, if known

## Privileged Operations

Killfish Tuner may call tools such as:

- systemctl
- rpm-ostree
- modprobe-related configuration
- hardware monitoring utilities
- GPU/CU management scripts

All privileged operations should be kept as narrow and explicit as possible.

## Safety Guidelines

Contributors should avoid:

- Running arbitrary shell input from the UI
- Writing to system paths without clear intent
- Silently changing boot configuration
- Hiding command failures
- Disabling safety limits without user confirmation
