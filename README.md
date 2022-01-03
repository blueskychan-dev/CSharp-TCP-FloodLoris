# CSharp-TCP-FloodLoris
TCP Flood Connect and keep all connection.
# Overview
[overview]("https://media.discordapp.net/attachments/879939876181647380/927581867249631322/unknown.png?width=980&height=461")
* Tag FloodLoris DDoS SSH port (22) make target server is overload!
# How did work?
* Normally Flood program just send many raw packet and big size 
* but FloodLoris will send many Connection but NO send many raw or message to target.
* This working from port check (or check this port open or close) just send many so much!
# Normal Flood VS FloodLoris
* Some Flood Program eg. Python Flood is connect and exit or some packet is connect forever.
* But FloodLoris is send many connection without many raw message to target and faster to connection.
(Use Ngrok to checking)
# How to install!
* For Windows Just Downloads and run.
* For Linux you need wine and wine-mono to run
```
wine Connect_flood.exe
```
* NOTICE MONO Connect_flood.exe is WONT WORKING! (work but cannot flood ~~uwu~~)
# WARNING
* Keep it on legal.
# Issues or Q&A?
* Ask in Issues.
# Donate
* SOON!
