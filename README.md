# tfl-status

A GitHub Action fetches London line status from the official [TfL Unified API](https://api.tfl.gov.uk) every 10 minutes (6am–midnight) and publishes it as `status.json` on the `data` branch:

https://raw.githubusercontent.com/leannechen1/tfl-status/data/status.json

Fields per line: `id`, `name`, `mode`, `status`, `severity` (10 = Good Service), `reason`, `good`.

Run it on demand from the Actions tab (**Fetch TfL status → Run workflow**).
