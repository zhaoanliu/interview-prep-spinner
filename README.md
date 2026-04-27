# Daily Interview Prep Spinner

A lightweight, single-file web app for daily interview prep focus.
Built as a hands-on trial project to explore Cursor AI-assisted coding.

🔗 **[Live Demo](https://zhaoanliu.github.io/interview-prep-spinner)**

## What it does

Spin three spinners to set your interview prep focus for the day:

- **LeetCode Category** — picks from 15 algorithm topics (NeetCode 150 roadmap); the result links to the matching LeetCode tag page.
- **System Design Topic** — picks from all 25 ByteByteGo system design chapters; the result text links directly to that chapter on ByteByteGo.
- **Behavioral Question** — picks from common behavioral interview prompts (wheel + legend).

## System Design topics

Covers all chapters from
[ByteByteGo System Design Interview](https://bytebytego.com/courses/system-design-interview):

Rate Limiter, Consistent Hashing, Key-value Store, Unique ID Generator,
URL Shortener, Web Crawler, Notification System, News Feed System,
Chat System, Search Autocomplete, YouTube, Google Drive,
Proximity Service, Nearby Friends, Google Maps,
Distributed Message Queue, Metrics Monitoring & Alerting,
Ad Click Event Aggregation, Hotel Reservation System,
Distributed Email Service, S3-like Object Storage,
Real-time Gaming Leaderboard, Payment System,
Digital Wallet, Stock Exchange

## How to use

Open the [live demo](https://zhaoanliu.github.io/interview-prep-spinner)
in any browser — no install, no dependencies.

Or clone and open locally:

```bash
git clone https://github.com/zhaoanliu/interview-prep-spinner.git
cd interview-prep-spinner
open index.html
```

On Linux, open `index.html` in your browser, or run a local server (for example `python3 -m http.server`) and visit the URL it prints.

## Tech

Pure HTML, CSS, and JavaScript in `index.html` — no frameworks, no build step.
