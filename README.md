# hnkƶ

Cybersecurity Engineer with a background in platform security. These days I
work across a broader range of security topics. Linux kernel research and
upstream contributions are one part of that work.

## Security research

| Achievement | Published severity | Impact |
| --- | --- | --- |
| [CVE-2026-89970](https://www.cve.org/CVERecord?id=CVE-2026-89970) | **CVSS 9.8 · Critical** | A pre-auth network client could race NVMe-oF authentication teardown with timeout work, causing a kernel use-after-free and memory corruption on an exposed target. |
| [CVE-2026-97931](https://www.cve.org/CVERecord?id=CVE-2026-97931) | **CVSS 7.0 · High** | With affected TASCAM hardware attached and access to its hwdep node, a local user could upgrade a read mapping and access adjacent kernel pages or trigger incorrect page freeing. |

I discovered, reproduced, and developed the upstream fixes for both issues.
The scores above are from their published Linux CVE records; practical exposure
depends on the affected hardware or service being present.

I have also privately reported vulnerabilities to several blockchain projects.
Those reports remain non-public.

## Selected projects

- [hjkl](https://github.com/kazuki-hanai/hjkl): a small Rust keyboard remapper for a semicolon-based navigation layer on macOS and Windows
- [gh-create-github-app-token](https://github.com/kazuki-hanai/gh-create-github-app-token): generate a GitHub token from a GitHub App private key
- [dotfiles](https://github.com/kazuki-hanai/dotfiles): a [mise](https://mise.jdx.dev/)-based macOS and Ubuntu setup with one config for runtimes, tools, symlinks, and provisioning
