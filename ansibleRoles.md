# HomeSecExplorer Ansible Roles

This is the **official index** of Ansible roles maintained by **HomeSecExplorer**.

- [Ansible Galaxy](https://galaxy.ansible.com/ui/standalone/namespaces/23042/)

---

## Roles

- [pihole](https://github.com/HomeSecExplorer/ansible-role-pihole)
- [cloudflared](https://github.com/HomeSecExplorer/ansible-role-cloudflared)
- [sshaudit](https://github.com/HomeSecExplorer/ansible-role-sshaudit)
- [autoupdate](https://github.com/HomeSecExplorer/ansible-role-autoupdate)

---

### pihole

**What it does**

- Installs, configures, and manages **Pi-hole v6.x** for homelabs.
- Full lifecycle setup (service, config, and common homelab defaults).
- Works great with the [HomeSecExplorer.cloudflared](#cloudflared) role as a DoH upstream.

**Links**

- [GitHub](https://github.com/HomeSecExplorer/ansible-role-pihole)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/pihole/)

---

### cloudflared

**What it does**

- Installs and configures **cloudflared** as a **DNS-over-HTTPS (DoH)** proxy.
- Supports **multiple instances**, each on its own port (useful for different upstreams).
- Designed to pair with Pi-hole, but works standalone too.

**Links**

- [GitHub](https://github.com/HomeSecExplorer/ansible-role-cloudflared)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/cloudflared/)

---

### sshaudit

**What it does**
- Hardens SSH server and client configuration based on **ssh-audit** recommendations.
- Safe defaults, repeatable results, and a clean baseline for homelabs.

**Links**
- [GitHub](https://github.com/HomeSecExplorer/ansible-role-sshaudit)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/sshaudit/)

---

### autoupdate

**What it does**
- Enables automatic updates with sensible defaults:
  - Debian/Ubuntu: `unattended-upgrades`
  - Rocky Linux: `dnf-automatic`
- Configurable schedule and reboot behavior.

**Links**
- [GitHub](https://github.com/HomeSecExplorer/ansible-role-autoupdate)
- [Galaxy](https://galaxy.ansible.com/ui/standalone/roles/HomeSecExplorer/autoupdate/)

---
