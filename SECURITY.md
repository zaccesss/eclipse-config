# Security Policy

## Scope

This repository is IDE configuration: preference fragments, two small merge scripts, a plugin list
and guides. It contains no service and no library. In scope:

- A merge script that writes outside the workspace's settings folder, follows a crafted path
  somewhere unexpected or runs content from a fragment as code
- An update site in `plugins.txt` that points at a different or malicious plugin
- A setup instruction that would leave insecure file permissions behind

## Out of scope

- A vulnerability in Eclipse itself or in a listed plugin, report that upstream

## Reporting a vulnerability

> [!IMPORTANT]
> Report privately, not in a public issue. Email contact@isaacadjei.me with details and
> reproduction steps. Expect an acknowledgement within a few days.
