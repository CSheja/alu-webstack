# Web Server Scripts

This directory contains scripts for the web server tasks, including 0-transfer_file.
## 3-redirection

This Bash script configures a fresh Ubuntu 16.04 machine with Nginx
and sets up a permanent 301 redirect from `/redirect_me` to:

https://www.youtube.com/watch?v=QH2-TGUlwu4

It uses `sed` to modify the default Nginx site configuration and
reloads Nginx without using `systemctl`.
