```code
spacegram-x/
│
├── backend/
│   ├── ingestion/
│   │   ├── nasa_apod.py
│   │   ├── spacex_api.py
│   │   └── neo_ws.py
│   │
│   ├── ai/
│   │   ├── summarizer.py
│   │   ├── classifier.py
│   │   └── embedding_engine.py
│   │
│   ├── graph/
│   │   ├── node_builder.py
│   │   ├── relation_engine.py
│   │   └── store.py
│   │
│   └── api/
│       └── main.py (FastAPI)
│
├── frontend/
│   ├── index.html
│   ├── app.js
│   ├── graph-renderer.js
│   └── styles.css
│
├── core/
│   ├── config.py
│   └── types.py
│
├── data/
│   ├── cache/
│   └── snapshots/
│
├── docs/
│   ├── architecture.md
│   └── api.md
│
├── docker-compose.yml
└── README.md
