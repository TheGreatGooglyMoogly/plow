# 🚜 The Plow

An efficient Chia Plot mover.

Uses `inotify` to watch for new Chia plots and then fires off `rsync` to move
them to their final destination.

It can do many in parallel, one at a time, one per source, or one per destination.

Forked in the hope I can get it to update destinations (to add/remove drives) without restarting.
