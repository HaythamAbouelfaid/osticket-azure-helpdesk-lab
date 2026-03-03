# Hardening Checklist

- [ ] SSH key authentication enabled (no password SSH)
- [ ] Update packages regularly (apt update/upgrade)
- [ ] Firewall/NSG: restrict SSH (22) to admin IP
- [ ] HTTPS enabled with Certbot (Let’s Encrypt)
- [ ] Enforce least privilege using Roles/RBAC inside osTicket
- [ ] Remove installer directory / secure config files per osTicket guidance
- [ ] No secrets committed to repo (keys/passwords)
