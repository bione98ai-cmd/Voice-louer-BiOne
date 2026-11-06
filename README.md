# Voice-louer-BiOne
bione-voice-intelligence/
│
├── app/
│   ├── api/
│   │   ├── voice.py
│   │   ├── agents.py
│   │   ├── sessions.py
│   │   └── tools.py
│   │
│   ├── core/
│   │   ├── orchestrator.py
│   │   ├── agent_registry.py
│   │   ├── intent_classifier.py
│   │   ├── task_planner.py
│   │   └── verification_engine.py
│   │
│   ├── agents/
│   │   ├── chatx/
│   │   ├── lexexpert/
│   │   ├── mmde/
│   │   └── research/
│   │
│   ├── voice/
│   │   ├── elevenlabs_client.py
│   │   ├── speech_engine.py
│   │   └── voice_sessions.py
│   │
│   ├── memory/
│   │   ├── session_memory.py
│   │   ├── user_memory.py
│   │   └── shared_memory.py
│   │
│   ├── security/
│   │   ├── permissions.py
│   │   ├── approvals.py
│   │   └── audit.py
│   │
│   └── protocols/
│       └── bacp.py
│
├── tests/
├── migrations/
├── Dockerfile
├── requirements.txt
└── README.md
