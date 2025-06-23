## 📊 Local Observability Lab with Podman

**Description:**

A hands-on lab for exploring observability practices by running a full Grafana stack locally with **Prometheus (metrics)**, **Loki (logs)**, **Tempo (traces)**, and **Grafana (visualization)** using **Podman**.

This project enables engineers to gain practical experience with modern observability by experimenting with metrics, logs, and traces, and learning how to correlate them to debug and understand system behavior effectively.

---

**Why Podman?**

**Podman** is an open-source, daemonless container engine that serves as a drop-in alternative to Docker. It supports rootless containers, offers strong security guarantees, and integrates well with systemd, making it ideal for local development and experimentation.

---

**Key Goals:**

* Deploy and configure Grafana, Prometheus, Loki, and Tempo containers locally using Podman.
* Learn PromQL, LogQL, and trace visualization via Grafana.
* Simulate application behaviors and troubleshoot them using observability tools.
* Correlate data across logs, metrics, and traces to gain deep system insights.

---

**Repository Structure:**

* `configs/`: Custom configuration files for Prometheus, Loki, and Tempo
* `compose/`: Podman-compatible container definitions (e.g., `podman-compose.yml`)
* `experiments/`: Scenarios and sample apps for observability learning
* `docs/`: Setup guides, query examples, and learnings
