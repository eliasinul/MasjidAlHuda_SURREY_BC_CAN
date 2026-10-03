# Masjid Al-Huda website

Static homepage with the Al-Huda logo, weekly Salah and Jumuah timetable, and an Awqat popup link.

## Update the timetable

Edit `timetable.yaml`, retaining the two-space indentation inside `timetable_text`. Then ask Codex to update `index.html` from that file. The website does not automatically load YAML. Its date warning uses America/Vancouver and the schedule dates in the HTML.

## Publish

Push `index.html` and `assets` to GitHub. Under Settings > Pages, choose Deploy from a branch, select your branch and /(root), then save.

Awqat opens in a new tab because its website blocks iframe embedding. The displayed timetable is the supplied mosque schedule and is not synced with Awqat.
