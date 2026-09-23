# Changelog

## 1.0.0 — first release

- Create, edit, duplicate and delete SSH profiles; favorites, tags and search.
- Profiles are written as standard OpenSSH configuration and work with `ssh <alias>` in any terminal.
- Connect in Windows Terminal, PowerShell or Command Prompt; copy the ssh command.
- Identity files, IdentitiesOnly, ProxyJump with loop detection, port forwarding and connection options.
- Import simple hosts from `~/.ssh/config`; detect alias conflicts; reload or regenerate after external edits.
- Keys page: fingerprints, copy public key, generate ED25519 or RSA keys, ssh-agent status.
- Effective configuration (`ssh -G`), network check and authentication test.
- Light, dark and system themes; keyboard shortcuts; diagnostics page.
