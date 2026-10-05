# hnkƶ

Cybersecurity Engineer with a background in platform security. These days I
work across a broader range of security topics. Linux kernel research and
upstream contributions are one part of that work.

`Platform security` · `Security engineering` · `Vulnerability research` · `Rust` · `Go` · `C`

## Security research

| Achievement | Published severity | Impact |
| --- | --- | --- |
| [CVE-2026-89970](https://www.cve.org/CVERecord?id=CVE-2026-89970): Linux NVMe target authentication timeout-work UAF ([upstream fix](https://git.kernel.org/linus/eaa948c0e19b1bb2d93262207bca0c3d19cc3406), [patch](https://lore.kernel.org/all/20260830131105.680566-1-hnkz.64@gmail.com/)) | **CVSS 9.8 · Critical** | A pre-auth network client could race NVMe-oF authentication teardown with timeout work, causing a kernel use-after-free and memory corruption on an exposed target. |
| [CVE-2026-97931](https://www.cve.org/CVERecord?id=CVE-2026-97931): Linux ALSA US122L mmap permission upgrade ([upstream fix](https://git.kernel.org/linus/71c610aeb1770302ac9c9e0b9a4ecd37f1311928), [patch](https://lore.kernel.org/all/20260908110053.2950767-1-hnkz.64@gmail.com/)) | **CVSS 7.0 · High** | With affected TASCAM hardware attached and access to its hwdep node, a local user could upgrade a read mapping and access adjacent kernel pages or trigger incorrect page freeing. |

I discovered, reproduced, and developed the upstream fixes for both issues.
The scores above are from their published Linux CVE records; practical exposure
depends on the affected hardware or service being present.

## Selected projects

- [hjkl](https://github.com/kazuki-hanai/hjkl): a small Rust keyboard remapper for a semicolon-based navigation layer on macOS and Windows
- [gh-create-github-app-token](https://github.com/kazuki-hanai/gh-create-github-app-token): generate a GitHub token from a GitHub App private key
- [dotfiles](https://github.com/kazuki-hanai/dotfiles): my development environment
