# Contributing

Thank you for improving Pi-Detect.

## Development setup

```bash
git clone https://github.com/Olawalekaybee/AI-powered-IoT-security-camera.git
cd AI-powered-IoT-security-camera
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements-pi.txt
cp .env.example .env
python main.py --debug
```

For laptop development, set `USE_PICAMERA=false` in `.env`.

## Pull request checklist

- Keep secrets out of commits.
- Add or update tests for code changes.
- Update the README when behavior changes.
- Run `pytest tests/ -q` before opening a pull request.
