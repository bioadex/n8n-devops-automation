# Production-ready DevOps automation system using n8n, Docker, Jenkins, and Telegram alerts.

```text
n8n-devops-automation/
│
├── docker/
│   └── docker-compose.yml
│
├── workflows/
│   └── jenkins-alert-workflow.json
│
├── jenkins/
│   └── Jenkinsfile
│
├── docs/
│   ├── architecture.md
│   ├── setup-guide.md
│   └── screenshots/
│
├── .env.example
├── README.md
└── LICENSE
```

Architecture

Jenkins → n8n Webhook → Logic → Telegram Alerts

screenshots

<img width="1518" height="673" alt="image" src="https://github.com/user-attachments/assets/ffcf90a6-3a52-4d3f-88d4-a4e99aa6f685" />

<img width="1132" height="816" alt="image" src="https://github.com/user-attachments/assets/b8f838b2-0826-438e-bbab-d5d3f512e64c" />

<img width="1294" height="931" alt="image" src="https://github.com/user-attachments/assets/6cc4e767-951b-4258-850e-4b98bd763432" />

Telegram Screenshot

<img width="489" height="230" alt="image" src="https://github.com/user-attachments/assets/ddced5dd-adcf-4bd2-96c6-f25a0153145d" />
