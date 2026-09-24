# Brent Dean

**Linux infrastructure · Cloud automation · Reliability · Security**

I build Linux-based systems and work on making them repeatable, observable, secure, and recoverable. My recent work spans AWS infrastructure, Python automation, containerized applications, security validation, and hands-on computing hardware.

I earned a **B.S. in Computer Science from Brooklyn College** (cum laude; departmental honors) after an earlier career in enterprise technology and technical operations.

## Selected projects

### [Cloud Infrastructure Automation](https://github.com/BrentDean/cloud-infrastructure-automation)

A rebuildable **AWS three-tier infrastructure lab** using Terraform and Ansible. Provisions networking and EC2 hosts, deploys a Flask/PostgreSQL application, validates allowed and denied network paths, and destroys billable resources after verification. Supports both a Gunicorn/systemd runtime and an opt-in, single-node **k3s** runtime.

**AWS · Terraform · Ansible · Linux · Docker · k3s · Python · PostgreSQL · CI**

### [HoneyNet](https://github.com/BrentDean/HoneyNet)

Analysis of telemetry from an Internet-facing T-Pot multi-honeypot deployment. Investigates credential attacks, scanning, service probes, and post-login behavior using Cowrie and Suricata data.

**Linux · T-Pot · Suricata · Networking · Security telemetry**

### [8-Bit Computer](https://github.com/BrentDean/8-Bit)

A custom-PCB 8-bit computer project with Python assembly/ROM tooling and an Arduino-based EEPROM programming workflow. An exploration of how software, control logic, buses, and physical hardware meet.

**Computer architecture · Python · Digital logic · KiCad · Embedded hardware**

### Porter — Local-First AI & Automation Control Plane

A Python-based local-first automation project that uses deterministic tools before model inference. Includes policy-controlled provider routing, SQLite-backed state, Linux service/storage actions, FastAPI and desktop interfaces, tests, and operational metrics. Built to explore AI integration as part of a conventional, observable software system.

**Python · Linux · FastAPI · SQLite · Ollama · Docker · Prometheus · Grafana**

## Professional technical work

At the **Icahn School of Medicine at Mount Sinai**, I built Linux/container-based automation for REDCap upgrade validation and security testing in a regulated research environment. The work coordinated database restoration, application upgrades, API and authenticated-browser checks, regression testing, and reproducible evidence generation. I also developed and evaluated Caddy/Coraza WAF controls based on external penetration-test findings.

## What I work with

- **Infrastructure & cloud:** Linux, AWS, Hetzner Cloud, Terraform, Ansible, Docker, Podman, k3s, networking, SSH, DNS, and TLS
- **Automation & applications:** Python, Bash, SQL, GitHub Actions, pytest, REST APIs, FastAPI, MariaDB, PostgreSQL, and SQLite
- **Reliability & security:** Prometheus, Grafana, health/readiness checks, backups and recovery, Caddy/Coraza WAF, Suricata, Wireshark, and tcpdump

More project write-ups and technical notes: **[LaunchShell.org](https://launchshell.org/)** · [LinkedIn](https://www.linkedin.com/in/brentdean/)
