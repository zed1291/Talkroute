This repo is cause Talkroute does not include a version number for their Desktop app anywhere on their page.
https://talkroute.com/downloads/os_id_mac/

I have a cron job on an always on Mac that downloads Talkroute, gets the version number,
and then updates this repo (if needed), set to run every 6hrs.

This allows me to write a Talkroute install script that supports updating, because it can reference the latest
version of the app here.
