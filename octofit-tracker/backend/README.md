OctoFit Tracker — Backend

Quick start (backend)

1. Activate the virtualenv:

```bash
source /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/venv/bin/activate
```

2. Install requirements (if not already installed):

```bash
pip install -r /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/requirements.txt
```

3. Run migrations and start development server on port 8000:

```bash
python /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/octofit_tracker/manage.py migrate
python /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/octofit_tracker/manage.py runserver 0.0.0.0:8000
```

Notes:
- The project uses Django; the project package lives at `backend/octofit_tracker/octofit_tracker` and `manage.py` is at `backend/octofit_tracker/manage.py`.
- Forwarded public port: `8000`.
