# LocalGUST-MAC

Run `GUST-Lite.html` locally with COOP/COEP headers using Python.

## One-Line Run (macOS / Linux)
```rm -rf LocalGUST-Mac LocalGUST-Mac-main gust.zip && \
curl -L https://github.com/GabeUtz/LocalGUST-Mac/archive/refs/heads/main.zip -o gust.zip && \
unzip -o gust.zip && \
mv LocalGUST-Mac-main LocalGUST-Mac && \
kill $(lsof -ti:8080) 2>/dev/null; \
python3 LocalGUST-Mac/server.py & sleep 2 && \
open "http://localhost:8080/GUST-Lite.html"
```

## Requirements
- Python 3
- Port 8080 must be free

----------

MIT License
