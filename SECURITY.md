# Security Policy

This policy applies to every repository in the VortX organization, unless a repo carries its own.

## Supported versions

The latest release only. Sideloaded and self-built apps have no auto-update, so check the app's About screen, which flags when a newer release exists.

## Reporting a vulnerability

Please use GitHub's private vulnerability reporting (a repository's **Security** tab, then **Report a vulnerability**) rather than opening a public issue, especially for anything touching:

- a bundled or embedded streaming server and its local surface
- account tokens or credential storage
- the release and build pipeline

You will get a response within a few days. Verified reports are credited in the release notes unless you prefer otherwise.

## Verifying releases

Releases are built from source on GitHub's runners and ship with SHA-256 checksums alongside the maintainer's build, so you can confirm a downloaded binary matches the public code.
