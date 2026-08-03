# Ansible Node.js Deployment

An automated deployment pipeline for Node.js applications using **Ansible**. This project streamlines provisioning servers, installing dependencies, configuring environments, and running Node.js applications seamlessly.

---

## 🚀 Features

* **Automated Provisioning:** Sets up the required environment on target servers.
* **Node.js & npm Setup:** Installs specified versions of Node.js and npm.
* **Application Management:** Handles code deployment, dependency installation (`npm install`), and process management (e.g., PM2).
* **Idempotent Playbooks:** Ensures safe and repeatable runs without unintended side effects.

---

## 📋 Prerequisites

Ensure you have the following installed on your local control machine:

* **Ansible** (v2.9 or higher)
* **SSH access** to your target remote server(s) configured with SSH keys.

---

