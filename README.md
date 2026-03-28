# RedSwitch

**The failsafe for autonomous AI agents.**

Your AI agent runs 24/7 — but what happens if you can't supervise it? RedSwitch is the dead man's switch that prevents runaway API costs, zombie agents, and chaos for your family.

## 🚀 Quick Start

```bash
pip install redswitch
```

```python
from redswitch import RedSwitch

rs = RedSwitch(
    agent_id='my-agent',
    human_id='you@email.com',
    platform='openclaw'
)

rs.register()
rs.heartbeat()  # Call this periodically
```

## 📦 Projects

| Repo | Description |
|------|-------------|
| [sdk](https://github.com/Redswitch-Ai/sdk) | Python SDK for RedSwitch integration |

## 🔗 Links

- 🌐 [Website](https://redswitch.ai)
- 📖 [Documentation](https://redswitch.ai/docs)
- 📊 [Dashboard](https://redswitch.ai/dashboard)
- 🐍 [PyPI Package](https://pypi.org/project/redswitch/)

## 💡 Why RedSwitch?

- **Open Protocol** — MIT licensed, free forever
- **5 Minute Setup** — pip install and go
- **Family Protection** — Plain-English reports for non-technical loved ones
- **Multi-Channel Alerts** — Email, Telegram, SMS

---

*Built by [Evan Hubert](https://github.com/evanhubert) in Missouri, USA*