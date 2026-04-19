# HomeSecExplorer Ansible Roles

This is the **official index** of Ansible roles maintained by **HomeSecExplorer**.

- [Ansible Galaxy](https://galaxy.ansible.com/ui/standalone/namespaces/23042/)

---

## Roles

- [pihole](https://github.com/HomeSecExplorer/ansible-role-pihole)
- [cloudflared](https://github.com/HomeSecExplorer/ansible-role-cloudflared)
- [sshaudit](https://github.com/HomeSecExplorer/ansible-role-sshaudit)
- [autoupdate](https://github.com/HomeSecExplorer/ansible-role-autoupdate)
- [gitlab](https://github.com/HomeSecExplorer/ansible-role-gitlab)

---

### pihole

[![CI](https://github.com/HomeSecExplorer/ansible-role-pihole/actions/workflows/ci.yml/badge.svg)](https://github.com/HomeSecExplorer/ansible-role-pihole/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/HomeSecExplorer/ansible-role-pihole)](https://github.com/HomeSecExplorer/ansible-role-pihole/releases)
[![Galaxy downloads](https://img.shields.io/ansible/role/d/HomeSecExplorer/pihole?label=Galaxy%20downloads)](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/pihole/)
[![Stars](https://img.shields.io/github/stars/HomeSecExplorer/ansible-role-pihole)](https://github.com/HomeSecExplorer/ansible-role-pihole/stargazers)
[![Issues](https://img.shields.io/github/issues/HomeSecExplorer/ansible-role-pihole)](https://github.com/HomeSecExplorer/ansible-role-pihole/issues)
[![PRs](https://img.shields.io/github/issues-pr/HomeSecExplorer/ansible-role-pihole)](https://github.com/HomeSecExplorer/ansible-role-pihole/pulls)

**What it does**

- Installs, configures, and manages **Pi-hole v6.x** for homelabs.
- Full lifecycle setup (service, config, and common homelab defaults).
- Works great with the [HomeSecExplorer.cloudflared](#cloudflared) role as a DoH upstream.

**Links**

- [GitHub](https://github.com/HomeSecExplorer/ansible-role-pihole)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/pihole/)

---

### cloudflared

[![CI](https://github.com/HomeSecExplorer/ansible-role-cloudflared/actions/workflows/ci.yml/badge.svg)](https://github.com/HomeSecExplorer/ansible-role-cloudflared/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/HomeSecExplorer/ansible-role-cloudflared)](https://github.com/HomeSecExplorer/ansible-role-cloudflared/releases)
[![Galaxy downloads](https://img.shields.io/ansible/role/d/HomeSecExplorer/cloudflared?label=Galaxy%20downloads)](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/cloudflared/)
[![Stars](https://img.shields.io/github/stars/HomeSecExplorer/ansible-role-cloudflared)](https://github.com/HomeSecExplorer/ansible-role-cloudflared/stargazers)
[![Issues](https://img.shields.io/github/issues/HomeSecExplorer/ansible-role-cloudflared)](https://github.com/HomeSecExplorer/ansible-role-cloudflared/issues)
[![PRs](https://img.shields.io/github/issues-pr/HomeSecExplorer/ansible-role-cloudflared)](https://github.com/HomeSecExplorer/ansible-role-cloudflared/pulls)

**What it does**

- Installs and configures **cloudflared** as a **DNS-over-HTTPS (DoH)** proxy.
- Supports **multiple instances**, each on its own port (useful for different upstreams).
- Designed to pair with Pi-hole, but works standalone too.

**Links**

- [GitHub](https://github.com/HomeSecExplorer/ansible-role-cloudflared)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/cloudflared/)

---

### sshaudit

[![CI](https://github.com/HomeSecExplorer/ansible-role-sshaudit/actions/workflows/ci.yml/badge.svg)](https://github.com/HomeSecExplorer/ansible-role-sshaudit/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/HomeSecExplorer/ansible-role-sshaudit)](https://github.com/HomeSecExplorer/ansible-role-sshaudit/releases)
[![Galaxy downloads](https://img.shields.io/ansible/role/d/HomeSecExplorer/sshaudit?label=Galaxy%20downloads)](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/sshaudit/)
[![Stars](https://img.shields.io/github/stars/HomeSecExplorer/ansible-role-sshaudit)](https://github.com/HomeSecExplorer/ansible-role-sshaudit/stargazers)
[![Issues](https://img.shields.io/github/issues/HomeSecExplorer/ansible-role-sshaudit)](https://github.com/HomeSecExplorer/ansible-role-sshaudit/issues)
[![PRs](https://img.shields.io/github/issues-pr/HomeSecExplorer/ansible-role-sshaudit)](https://github.com/HomeSecExplorer/ansible-role-sshaudit/pulls)

**What it does**

- Hardens SSH server and client configuration based on **ssh-audit** recommendations.
- Safe defaults, repeatable results, and a clean baseline for homelabs.

**Links**

- [GitHub](https://github.com/HomeSecExplorer/ansible-role-sshaudit)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/sshaudit/)

---

### autoupdate

[![CI](https://github.com/HomeSecExplorer/ansible-role-autoupdate/actions/workflows/ci.yml/badge.svg)](https://github.com/HomeSecExplorer/ansible-role-autoupdate/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/HomeSecExplorer/ansible-role-autoupdate)](https://github.com/HomeSecExplorer/ansible-role-autoupdate/releases)
[![Galaxy downloads](https://img.shields.io/ansible/role/d/HomeSecExplorer/autoupdate?label=Galaxy%20downloads)](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/autoupdate/)
[![Stars](https://img.shields.io/github/stars/HomeSecExplorer/ansible-role-autoupdate)](https://github.com/HomeSecExplorer/ansible-role-autoupdate/stargazers)
[![Issues](https://img.shields.io/github/issues/HomeSecExplorer/ansible-role-autoupdate)](https://github.com/HomeSecExplorer/ansible-role-autoupdate/issues)
[![PRs](https://img.shields.io/github/issues-pr/HomeSecExplorer/ansible-role-autoupdate)](https://github.com/HomeSecExplorer/ansible-role-autoupdate/pulls)

**What it does**

- Enables automatic updates with sensible defaults:
  - Debian/Ubuntu: `unattended-upgrades`
  - Rocky Linux: `dnf-automatic`
- Configurable schedule and reboot behavior.

**Links**

- [GitHub](https://github.com/HomeSecExplorer/ansible-role-autoupdate)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/autoupdate/)

---

### gitlab

[![CI](https://github.com/HomeSecExplorer/ansible-role-gitlab/actions/workflows/ci.yml/badge.svg)](https://github.com/HomeSecExplorer/ansible-role-gitlab/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/HomeSecExplorer/ansible-role-gitlab)](https://github.com/HomeSecExplorer/ansible-role-gitlab/releases)
[![Galaxy downloads](https://img.shields.io/ansible/role/d/HomeSecExplorer/gitlab?label=Galaxy%20downloads)](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/gitlab/)
[![Stars](https://img.shields.io/github/stars/HomeSecExplorer/ansible-role-gitlab)](https://github.com/HomeSecExplorer/ansible-role-gitlab/stargazers)
[![Issues](https://img.shields.io/github/issues/HomeSecExplorer/ansible-role-gitlab)](https://github.com/HomeSecExplorer/ansible-role-gitlab/issues)
[![PRs](https://img.shields.io/github/issues-pr/HomeSecExplorer/ansible-role-gitlab)](https://github.com/HomeSecExplorer/ansible-role-gitlab/pulls)

**What it does**

- Installs and configures **GitLab** using the official Omnibus packages.
- Manages the main GitLab configuration (`gitlab.rb`) in a reproducible way.
- Intended for homelabs and self-hosted setups.

**Links**

- [GitHub](https://github.com/HomeSecExplorer/ansible-role-gitlab)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/gitlab/)

---
