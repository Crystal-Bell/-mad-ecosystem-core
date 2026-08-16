your-repo/
├── .github/
│   ├── workflows/
│   │   └── daily-agent-sync.yml    <-- The automation engine
│   └── templates/
│       ├── agent-task.md           <-- Your Agent Task Template
│       └── ecosystem-arch.md       <-- Your M.A.D./Max Ecosystem Template
├── scripts/
│   └── run_agent_task.py           <-- Execution logic (trends, email prep, text generation)
└── output/                         <-- Where daily generated files get saved
# -mad-ecosystem-core