# Lab 2 — Observing Tor Client Traffic (Safe)

## Objective
Understand how Tor builds circuits and anonymizes traffic.

## Steps
1. On your VM, install Tor (`sudo apt install tor`).
2. Run Tor Browser in the VM.
3. Open Wireshark on the VM.
4. Observe encrypted TLS traffic — note: you cannot see content, only encrypted packets.
5. Identify multiple hops in Tor circuits using logs:  
   `cat /var/log/tor/log`

## Deliverable
Short note describing differences between normal HTTP traffic and Tor traffic.
