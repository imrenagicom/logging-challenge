# Logging challenge starter

This repository is intentionally a minimal HTTP service for the software
instrumentation course. The observability implementation is part of the
course exercises; do not expect the challenge solutions in this branch.

Run the starter service with:

```bash
go run main.go
```

It listens on `127.0.0.1:8080`. Try it with:

```bash
curl 'http://127.0.0.1:8080/?name=Alice'
```

Follow the course instructions to add logging, metrics, tracing, and the
local observability infrastructure step by step. Keep credentials and local
`.env` files out of version control.
