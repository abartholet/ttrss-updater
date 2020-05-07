# ttrss-updater
Bash script to automate updating Tiny Tiny RSS.

As this is more or less a convenience script for myself it does make some assumptions about updating feeds via crontab (every 5 minutes), backing up tt-rss and the database, and purging old backup (older than 60 days).

However, should anyone want to use it, create a config file using the config.sample in the same directory as the ttrss-updater script and adjust accordingly.

As I'm using mysql I have never tested the pg_dump if you're using postgresql, so it could very well be broken.
