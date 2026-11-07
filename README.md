# EECE430 Assignment 6

Hassan Hashem

GitHub Actions CI/CD for the Lab 5 inventory agent.

## Run in Docker Desktop

1. Open Docker Desktop.
2. Open **Containers** and start **inventory-agent-assignment6**.
3. Open http://localhost:8000/.

## Windows runner

If the runner is stopped, open PowerShell and run:

```powershell
cd C:\actions-runner
.\run.cmd
```

Leave that window open.

Keep your Gemini key and Django secret in a local `.env` beside `manage.py`, using `.env.example` as the template. `.env` is not committed.

For deployment, keep the Windows runner running. Change the heading, commit and push, wait for GitHub Actions to pass, then refresh the page.
