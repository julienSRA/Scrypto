# Scrypto
🚀 Un pipeline Python modulaire pour collecter, stocker, exporter et analyser des métriques crypto en temps réel. Il s’appuie sur plusieurs API publiques (Coingecko, Bybit, DefiLlama, Mempool, Alternative.me, etc.) et enregistre les données dans une base SQLite locale, avec export automatique en CSV et génération de rapports. 

Pipeline Python de collecte & signaux crypto, + orchestrateur multi-agents AI.

Structure:
- collectors/: collectors de flux WS / REST
- core/: base_collector, storage
- pipeline/: orchestration et signals
- utils/: helpers (ws client)
- tests/: pytest tests
- data/: stockage local (gitignore)
