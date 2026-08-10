# 🛡️ WAFinity — Intelligent Web Application Firewall

WAFinity is an Advanced Web Application Firewall (WAF) designed to protect
web applications from malicious HTTP traffic.

It combines traditional signature-based detection with machine learning-based
anomaly detection to identify both known and previously unseen threats.

## 🚀 Key Features

- 🚫 Block known web attacks
- 🤖 ML-based anomaly detection
- 🛡️ Real-time HTTP request analysis
- 🔍 Detection of obfuscated and encoded attacks
- 📊 Interactive security insights
- ✨ Modern responsive interface
- ⚡ Fast request processing

## 🧠 How It Works

WAFinity uses a dual-layer detection approach:

HTTP Request
      ↓
Signature-Based Detection
      ↓
Known Attack? ── Yes → BLOCK
      ↓ No
Feature Engineering
      ↓
ML-Based Anomaly Detection
      ↓
Malicious? ── Yes → BLOCK
      ↓ No
    ALLOW

### ML Detection

The machine learning layer analyzes characteristics of incoming HTTP
requests to identify anomalous behavior.

Features include:

- Payload entropy
- Parameter length
- Special-character distribution
- Request/payload characteristics

This allows the system to detect obfuscated and previously unseen
attack patterns beyond traditional signatures.

## 🛡️ Threat Detection

### Signature-Based Detection

WAFinity detects known attack patterns such as:

- SQL Injection
- Cross-Site Scripting (XSS)
- UNION-based SQL Injection
- JavaScript injection

### ML-Based Anomaly Detection

The ML layer analyzes suspicious or obfuscated inputs, including:

- URL-encoded attacks
- Hex-encoded payloads
- Obfuscated JavaScript
- Encoded XSS payloads

## 📊 Performance

| Metric | Result |
|---|---:|
| Threat Detection Precision | 95% |
| Request Response Time | <200 ms |
| Detection Approach | Hybrid ML + Signature |

## 🖥️ Output Screenshots
<img width="777" height="447" alt="image" src="https://github.com/user-attachments/assets/097e141e-67b1-4032-8333-62a6de5614a0" />
<img width="777" height="622" alt="image" src="https://github.com/user-attachments/assets/aa10dbc0-a9fb-426c-a137-42bb11448a86" />
<img width="777" height="454" alt="image" src="https://github.com/user-attachments/assets/30635b13-112e-4fb5-9a26-654008ada889" />


## 📋 Project Management

The development of WAFinity was managed using **Jira** following an Agile/Scrum workflow.

### 🏗️ Epic
**NeuroShield: Intelligent Web Defense**

### 📌 User Stories

- **Develop ML Threat Detection Model** — Build an ML model to analyze HTTP requests and detect malicious requests in real time.
- **Implement Feature Engineering** — Extract relevant features from HTTP requests for effective anomaly detection.
- **Implement Signature-Based Detection** — Detect and block known web attacks using predefined signatures.
- **Integrate ML and Signature Detection** — Combine rule-based and ML-based detection into a dual-layered defense system.
- **Integrate Detection Engine with Flask** — Integrate the detection engine with the Flask application for real-time request analysis.
- **Evaluate and Optimize Threat Detection** — Evaluate detection accuracy and optimize response time and overall performance.

### 🔄 Agile Workflow

**Epic → User Stories → Subtasks → Sprint → To Do → In Progress → Done**

<img width="1503" height="861" alt="image" src="https://github.com/user-attachments/assets/38232572-506b-4844-82a7-9692a977f05e" />


### 📊 Sprint Metrics

- **Sprint:** SCRUM Sprint 1
- **Total Story Points:** 33
- **Methodology:** Agile/Scrum
