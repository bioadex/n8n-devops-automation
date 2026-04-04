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
