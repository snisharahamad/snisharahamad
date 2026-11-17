<div align="center">
  <h1 align="center">Infrastructure, Networking & Security Automation</h1>
  <p align="center">
    <strong>Software & Systems Engineering | Linux, Containers & Observability</strong>
  </p>
  <p align="center">
    I build containerized infrastructures, log aggregation pipelines, and automation tools. My focus is on bridging software development and systems administration through clean code, network isolation, and practical observability.
  </p>

  <p align="center">
    <a href="https://www.linkedin.com/in/sahil-nishar-ahamad/">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </p>
</div>

<br/>

## 🛠️ Technologies & Tools

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Golang-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux_Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white" />
  <img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefik&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
</div>

<br/>

## 📁 Infrastructure & Security Projects

### 1️⃣ [Cowrie Telemetry Daemon](https://github.com/snisharahamad/sentinel-soar) | *Automated Log Parsing & Alerting*
> **Tech:** Python, SQLite, REST APIs, JSON Parsing, dotenv
* Developed a Python daemon to tail and parse Cowrie SSH honeypot logs in real time via non-blocking I/O.
* Structured local SQLite storage to archive authentication events and commands for historical queries.
* Configured an automated alerting pipeline using Discord webhooks and environment variables (`.env`) to report suspicious connection attempts.

### 2️⃣ [Honeypot Observability Stack](https://github.com/snisharahamad/sentinel-honeypott) | *Centralized Log Aggregation (PLG)*
> **Tech:** Docker Compose, Cowrie, Promtail, Loki, Grafana
* Deployed an isolated Cowrie honeypot container to capture unauthorized SSH and Telnet traffic.
* Configured a local observability pipeline using Promtail to ship container logs into Loki.
* Built Grafana dashboards to visualize connection metrics, top attacking IPs, and authentication trends over time.

### 3️⃣ [Traefik Reverse-Proxy Architecture](https://github.com/snisharahamad/architecture-microservices-docker) | *Container Routing & Isolation*
> **Tech:** Traefik, Docker Compose, Reverse Proxy, Docker Networks
* Configured a Traefik reverse-proxy to route HTTP traffic dynamically across multiple containerized services using Docker labels.
* Unified service orchestration under a single `docker-compose.yml` workflow for consistent local deployment.
* Segmented backend containers across dedicated bridge networks to prevent direct external exposure.

### 4️⃣ [Threat Intel Lookup Tool](https://github.com/snisharahamad/Threat-Intel-Analyzer) | *Automated IP & Indicator Enrichment*
> **Tech:** Python, REST APIs, OSINT, JSON
* Built a Python CLI tool that queries external threat intelligence APIs to evaluate IP reputation and indicators of compromise (IoCs).
* Automated data parsing and formatting to speed up initial triage during log analysis.

<br/>

## 📈 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=snisharahamad&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" />
</div>
