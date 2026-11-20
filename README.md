# LocalGUST-MAC

Run `GUST-Lite.html` locally with COOP/COEP headers using Python.

## One-Line Run (macOS / Linux)
```bash
curl -L https://github.com/GabeUtz/LocalGUST-Mac/archive/refs/heads/main.zip -o gust.zip && unzip gust.zip && cd LocalGUST-Mac-main && kill $(lsof -ti:8080) 2>/dev/null; python3 server.py & sleep 1 && open "http://localhost:8080/GUST-Lite.html"


## Requirements
- Python 3
- Port 8080 must be free

----------

MIT License
