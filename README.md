# Flask DevOps Lab - Version A

## Usage

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

### API Endpoints

- **/api/health** – Returns the application's health status.
- **/api/config** – Returns the configuration stored in `config.json`.
- **/api/report** – Returns the hostname, Python version, and application uptime.
