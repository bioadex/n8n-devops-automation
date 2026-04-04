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
