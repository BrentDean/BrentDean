# Brent Dean

**Linux infrastructure · Cloud automation · Reliability · Security**

I build Linux-based systems and work on making them repeatable, observable, secure, and recoverable. My recent work spans AWS infrastructure, Python automation, containerized applications, security validation, and hands-on computing hardware.

I earned a **B.S. in Computer Science from Brooklyn College** (cum laude; departmental honors) after an earlier career in enterprise technology and technical operations.

> **Portfolio note:** Public project repositories are curated release snapshots rather than mirrors of day-to-day development history, so public commit history is intentionally minimal where appropriate.

## Selected projects

### [Cloud Infrastructure Automation](https://github.com/BrentDean/cloud-infrastructure-automation)

A rebuildable **AWS three-tier infrastructure lab** using Terraform and Ansible. Provisions networking and EC2 hosts, deploys a Flask/PostgreSQL application, validates allowed and denied network paths, and destroys billable resources after verification. Supports both a Gunicorn/systemd runtime and an opt-in, single-node **k3s** runtime.

**AWS · Terraform · Ansible · Linux · Docker · k3s · Python · PostgreSQL · CI**

### [Porter — Local-First AI & Automation Control Plane](https://github.com/BrentDean/porter)

A Python-based local-first automation project that uses deterministic tools before model inference. Includes policy-controlled provider routing, SQLite-backed state, Linux service/storage actions, FastAPI and desktop interfaces, tests, and operational metrics. Built to explore AI integration as part of a conventional, observable software system.

**Python · Linux · FastAPI · SQLite · Ollama · Docker · Prometheus · Grafana**

### [TorKit — Private Onion Service Platform](https://github.com/BrentDean/torKit)

An OnionShare-derived Linux platform for persistent private onion services with a host-side operator layer, Docker isolation, SQLite-backed Board state, CI validation, encrypted Restic backup/restore, and optional Terraform-managed AWS S3 recovery infrastructure.

**Python · Linux · Tor · OnionShare · Docker · SQLite · Restic · Terraform · AWS S3 · GitHub Actions**

### [Splunk LabOps — Security Telemetry Engineering](https://github.com/BrentDean/splunk-labops)

A containerized Splunk Enterprise security telemetry lab with Python collectors for genuine SSH and Fail2Ban events from an Internet-facing Hetzner VPS. Uses authenticated HTTPS HEC ingestion, five-minute systemd automation, persistent collection state, index retention controls, structured authentication fields, and automated tests.

**Splunk Enterprise · Python · Linux · Docker · HEC · Fail2Ban · systemd · Security telemetry**

### [HoneyNet](https://github.com/BrentDean/tpot-honeynet-analysis)

Analysis of telemetry from an Internet-facing T-Pot multi-honeypot deployment. Investigates credential attacks, scanning, service probes, and post-login behavior using Cowrie and Suricata data.

**Linux · T-Pot · Suricata · Networking · Security telemetry**

### [Cisco IOS XE Network Change Validation](https://github.com/BrentDean/cisco-network-automation)

Python automation for live Cisco IOS XE state validation, drift detection, guarded configuration changes, and rollback verification. Uses RESTCONF, NETCONF/YANG, and pyATS/Genie to collect and cross-check device state, apply narrowly scoped changes, validate expected outcomes, and confirm restoration to the original baseline.

**Cisco IOS XE · Python · RESTCONF · NETCONF · YANG · pyATS · Genie · Network automation · CI**

## Professional technical work

At the **Icahn School of Medicine at Mount Sinai**, I built Linux/container-based automation for REDCap upgrade validation and security testing in a regulated research environment. The work coordinated database restoration, application upgrades, API and authenticated-browser checks, regression testing, and reproducible evidence generation. I also developed and evaluated Caddy/Coraza WAF controls based on external penetration-test findings.

## What I work with

- **Infrastructure & cloud:** Linux, AWS, Hetzner Cloud, Terraform, Ansible, Docker, Podman, k3s, networking, SSH, DNS, and TLS
- **Automation & applications:** Python, Bash, SQL, GitHub Actions, pytest, REST APIs, FastAPI, MariaDB, PostgreSQL, and SQLite
- **Reliability & security:** Prometheus, Grafana, Splunk Enterprise, security telemetry, health/readiness checks, backups and recovery, Caddy/Coraza WAF, Suricata, Wireshark, and tcpdump

More project write-ups and technical notes: **[LaunchShell.org](https://launchshell.org/)** · [LinkedIn](https://www.linkedin.com/in/brentdean/)
