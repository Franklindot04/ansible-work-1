# Ansible Automation Playbooks

This repository contains a **production‑style suite of Ansible playbooks** used to automate Linux server provisioning, configuration management, application deployments and operational workflows.  
The collection includes **15+ modular playbooks**, templates, variables and reusable automation patterns designed for scalable, repeatable infrastructure operations.

---

## 📌 What’s Included

### ✔ Server & System Administration  
- User and group provisioning  
- Package installation (single and multi‑package workflows)  
- Service configuration and lifecycle management  
- System maintenance and housekeeping tasks  
- Conditional logic, handlers and dynamic variable usage  

### ✔ Web Application Deployments  
- HTML application deployment  
- PHP application deployment  
- Angular application deployment  
- Apache/HTTPD provisioning and configuration  
- Sample e‑commerce and food‑delivery application rollouts  

### ✔ Templates & Variables  
- Jinja2 templates (`dynamic.j2`)  
- Static and dynamic variable patterns  
- Host inventory (`hosts.ini`) for environment targeting  

### ✔ Automation Scenarios  
- Single‑play and multi‑play orchestration  
- Logical conditions and event‑driven handlers  
- Role‑ready structure for scalable automation  
- Maintenance mode workflows (`maintenance.html`)  

---

## 📁 Repository Structure  
- `01-single-play.yml` – Basic single‑play automation  
- `02-multi-play.yml` – Multi‑play orchestration  
- `03--httpd.yml` – Apache/HTTPD setup  
- `04--ecomm.yml` – E‑commerce site deployment  
- `05--food.yml` – Food‑delivery sample site deployment  
- `06-maintenance.yml` – Maintenance mode automation  
- `07-ubuntu.yml` – Ubuntu server configuration  
- `08-multi-pkg.yml` – Multiple package installation  
- `09-multi-logical-pkg.yml` – Logical conditions example  
- `10-static.yml` – Static variable usage  
- `11-dynamic.yml` – Dynamic template rendering  
- `12-vars.yml` – Variable management  
- `13-html-app.yml` – HTML app deployment  
- `14-php-app.yml` – PHP app deployment  
- `15-angular-app.yml` – Angular app deployment  

---

## 🎯 Purpose of This Repository  
This automation suite demonstrates **infrastructure provisioning, configuration management and application deployment workflows** aligned with modern DevOps and SRE practices.  
It reflects **production‑oriented automation patterns**: idempotent tasks, modular playbooks, reusable templates, environment‑aware variables and scalable orchestration structures.
