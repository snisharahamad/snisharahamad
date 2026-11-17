<div align="center">
  <h1 align="center">Infrastructure Automation & Observability</h1>
  <p align="center">
    <strong>Software Engineer | Systems & Infrastructure Operations</strong>
  </p>
  <p align="center">
    I build and manage local infrastructure, focusing on automation, logging pipelines, and configuration management. My current stack revolves around containerization, Linux systems, and building custom tooling in Go and Python.
  </p>
<p align="center">
    <a href="https://www.linkedin.com/in/sahil-nishar-ahamad/">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </p>
</div>
<br/>
🛠️ Technologies & Tools
<div align="center">
  <img src="https://img.shields.io/badge/Golang-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux_Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefik&logoColor=white" />
</div>
<br/>
📁 Core Infrastructure Projects
1️⃣ linux-policy-agent (In Development) | System Configuration Daemon
> **Tech:** Golang, Linux iptables, JSON
Building a system agent in Go to automate Linux configuration management.
Implementing JSON-based state parsing and file caching mechanisms.
Developing programmatic workflows to update local network policies (iptables) autonomously.
2️⃣ cowrie-telemetry-daemon | Log Parsing & Alerting
> **Tech:** Python, SQLite, REST APIs
Built a lightweight Python daemon to parse Cowrie honeypot logs via non-blocking I/O.
Configured local SQLite ingestion for historical queries of SSH authentication events.
Implemented an asynchronous webhook pipeline to trigger real-time alerts on specific log patterns.
3️⃣ observability-plg-stack | Metrics & Log Visualization
> **Tech:** Docker Compose, Promtail, Loki, Grafana
Deployed a local containerized stack to aggregate system logs and SSH metrics.
Configured Promtail to scrape local log files and forward them to Loki.
Built Grafana dashboards to monitor container health and visualize authentication attempts over time.
4️⃣ docker-traefik-proxy | Container Routing
> **Tech:** Traefik, Docker Compose, HTTP Routing
Configured a Traefik reverse-proxy to manage incoming traffic for multiple Docker services.
Defined local routing rules and exposed endpoints dynamically based on container labels.
Isolated backend services on dedicated Docker networks to restrict direct access.
<br/>
📈 GitHub Activity
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=snisharahamad&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" />
</div>
