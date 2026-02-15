# ansible-lab
Automated infrastructure with Ansible and OpenLDAP

# 🚀 Ansible Lab - Automated Infrastructure Project

## 📋 Descrizione
Progetto di automazione infrastruttura con Ansible su 3 server Ubuntu:
- **Autenticazione centralizzata** con OpenLDAP
- **Monitoraggio** con Prometheus + Grafana
- **Automazione completa** tramite playbook Ansible

## 🏗️ Architettura

| Server | IP | Ruolo |
|--------|-----|-------|
| ansible-control | 10.0.0.1 | Centro comando Ansible |
| ldap-server | 10.0.0.2 | OpenLDAP (dc=lab,dc=local) |
| monitoring-server | 10.0.0.3 | Prometheus + Grafana |

## ✅ Fase completate

- [x] **Fase 1**: Base Ansible + SSH keys
- [x] **Fase 2.1**: OpenLDAP installato
- [ ] **Fase 2.2**: Popolamento LDAP (users, groups)
- [ ] **Fase 3**: Stack monitoring
- [ ] **Fase 4**: Automazione avanzata
- [ ] **Fase 5**: Hardening sicurezza

## 🚀 Quick Start

### Prerequisiti
- 3 VM Ubuntu Server (VirtualBox)
- Rete interna 10.0.0.0/24
- Ansible installato su control node

### Setup

1. **Clone repository**
```bash
git clone https://github.com/YOUR_USERNAME/ansible-lab-project.git
cd ansible-lab-project
