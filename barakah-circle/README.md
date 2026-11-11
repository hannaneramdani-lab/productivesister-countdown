# Barakah Circle — Names of Allah reels

Instagram Reels and Stories for @productivesister, leading to each Barakah Circle book club session
(Café Yvonne, Dubai Hills · luma.com/BarakahCircle).

- `videos/` — one 26-second reel per name (67 al-Jamīl → 100 Allāh), 1080×1920, nasheed + wheel ticks.
- `schedule.json` — keyed by date (Asia/Dubai). Each date holds a list of posts, each with a `format`:
  - `reel`: `post_key`, `name`, `video_file`, `caption` (5 hashtags included). One reel per name per week
    (Sunday–Saturday), on the first day the name appears, plus the session-day reel on circle Saturdays.
  - `story`: `post_key`, `name`, `video_file` (no caption). Posted every day so the current name stays up for 24h.
  Paused for Ramadan (7 Feb – 13 Mar 2027). Published at 20:55 Dubai time by a daily scheduled task through Windsor.ai.

To change a caption or a date, edit `schedule.json`; the next run uses the new version.
