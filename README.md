# PowerShell-Script-Page-Load-Time-Monitor

Features
Measures page load time in milliseconds

Handles multiple URLs

Configurable interval between tests

Optional duration for how long to run

Timeout for slow-loading pages

Logs to CSV for easy analysis

Error handling for failed requests

Tracks response size


Run it with required parameters, for example:
.\PageLoadTimeMonitor.ps1 -Urls "https://example.com","https://google.com" -Interval 30 -Duration 120
