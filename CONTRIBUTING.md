# Contributing to Killfish Tuner

Contributions are welcome.

Killfish Tuner is a community-focused project for the AMD BC-250 platform. Testing, bug reports, documentation, research, and code contributions are all valuable.

## Ways To Contribute

You can help by:

- Reporting bugs
- Testing new releases
- Improving documentation
- Suggesting usability improvements
- Sharing BC-250 hardware findings
- Submitting pull requests
- Improving packaging
- Adding diagnostics and hardware detection
- Translating user-facing text

## Bug Reports

When reporting a bug, please include:

- Killfish Tuner version
- Linux distribution
- Kernel version
- Whether you are using Bazzite, Fedora, or another distribution
- What you expected to happen
- What actually happened
- Relevant logs
- A generated system report if available

## Pull Requests

Before submitting a large change, consider opening an issue first so the design can be discussed.

Good pull requests should:

- Focus on one topic
- Include clear commit messages
- Avoid unrelated formatting changes
- Preserve existing safety checks
- Avoid adding unnecessary dependencies
- Keep the UI understandable for advanced users

## Hardware Safety

Changes involving voltage, overclocking, fan control, CU management, systemd services, or boot configuration should be reviewed carefully.

When in doubt, prefer safe defaults and clear user feedback.
