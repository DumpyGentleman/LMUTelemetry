# LMUTelemetry

## Setup Instructions

This project uses [uv](https://docs.astral.sh/uv/) for Python environment management.

### 1. Create a Virtual Environment

```bash
uv venv --python 3.12.0
```

### 2. Activate the Virtual Environment

On Windows:
```powershell
.venv\Scripts\activate
```

On macOS/Linux:
```bash
source .venv/bin/activate
```

### 3. Sync Dependencies

```bash
uv pip sync
```