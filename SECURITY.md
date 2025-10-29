# 🔒 Rust-lt3S Security Policy

### Reporting Vulnerabilities
If you discover a security issue, **do not create a public issue**.
Instead, please report it privately via:
- 📧 security@r3c-foundation.org (planned)
- or GitHub Security Advisories (once enabled)

---

### Supported Versions
| Version | Supported Until | Notes |
|:--|:--|:--|
| 1.70.x-LT3S | 2030+ | Core long-term build |
| 1.71+ | Not guaranteed | May diverge upstream |

---

### Verification
Every released artifact includes:
- `.sha256` checksum file  
- Optional `.sig` (PGP signature)  
- Verified builds from reproducible environments

Always verify integrity before deployment:
```bash
sha256sum -c rust-lt3s-${OS}.sha256
