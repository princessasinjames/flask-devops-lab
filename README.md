# Flask DevOps Lab - VERSION a

## Usage
```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

Endpoints
- /api/health — Returns a JSON response showing the application is running correctly.
- /api/config — Returns the app configuration loaded from config.json, including app name and version.
- /api/report — Returns runtime system information such as hostname, Python version, and uptime.
