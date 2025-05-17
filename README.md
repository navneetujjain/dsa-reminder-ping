## Daily Ping Workflow

This GitHub Actions workflow sends scheduled GET requests to the [DSA Reminder App](https://dsa-reminder-app.onrender.com) to keep it active.

- **Schedule:** Runs several times daily via cron.
- **Retries:** Up to 3 attempts per run if the request fails.
- **Logs:** Outputs HTTP status and response for each attempt.

No manual action needed—runs automatically, or trigger it via "Run workflow" in Actions.
