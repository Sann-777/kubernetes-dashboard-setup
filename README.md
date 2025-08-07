# Kubernetes Advanced Concepts Setup and Practice 🚀

This repository documents my hands-on learning and setup of key **Kubernetes administration and configuration** concepts. The goal was to build a robust understanding of managing and monitoring workloads in a real-world cluster environment.

---

## 📌 What I Learned

### 🧩 Kubernetes Dashboard
- Installed and accessed the Kubernetes Web UI (Dashboard) for cluster-wide visibility.
- Secured access using **service account tokens** and **RBAC** roles.

### 🔐 RBAC (Role-Based Access Control)
- Configured custom roles and role bindings.
- Restricted access for users and services based on the principle of least privilege.

### 🩺 Probes (Liveness & Readiness)
- Implemented `livenessProbe` and `readinessProbe` in pod definitions to:
  - Automatically restart unresponsive containers.
  - Ensure traffic is routed only to healthy pods.

### ⚠️ Taints and Tolerations
- Applied **taints** to nodes to restrict pod scheduling.
- Used **tolerations** in pod specs to override those taints when necessary.

### 📈 Horizontal Pod Autoscaler (HPA)
- Configured HPA to automatically scale pods based on CPU usage and custom metrics.

### 📉 Vertical Pod Autoscaler (VPA)
- Deployed VPA to monitor and suggest/adjust resource requests and limits based on pod usage.

### 🧲 Node Affinity
- Set up **required** and **preferred** node affinity rules for intelligent pod scheduling.

### 📊 Monitoring
- Integrated tools like **Prometheus** and **Grafana** for real-time cluster and application monitoring.

### 📝 Logging
- Enabled centralized logging using **EFK (Elasticsearch, Fluentd, Kibana)** or **Loki + Grafana** stack.
