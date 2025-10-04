# Exposing website from local to the internet using FRP (Fast Reverse Proxy)

We'll use frps(server) and frpc(client) to expose our website to the internet.

## Launching an Instance
Create an instance on AWS with the following security groups
<img width="1918" height="1078" alt="security groups" src="https://github.com/user-attachments/assets/01fe9351-2d0c-4845-b709-d59dd699530e" />

## Install FRPS on the vm
FRPS RUNNING!
<br>

<img width="958" height="521" alt="FRPS Running" src="https://github.com/user-attachments/assets/64c92be4-9117-4c67-aa25-c07cabad3e08" />

## Running FRPS as systemd
Running as systemd
<br>

<img width="1010" height="429" alt="frps as a systemd service" src="https://github.com/user-attachments/assets/66f47aac-7f0f-4132-84e3-5d7d6d0a9e7a" />

## Install FRPC
FRPC RUNNING!
<br>

<img width="1000" height="612" alt="FRPC Running" src="https://github.com/user-attachments/assets/d5a6d6f1-7277-4d88-892d-6fcef2f8627f" />

## Checking site is hosted and ruuning on port 8080
Successful!
<br>

<img width="1088" height="348" alt="Screenshot 2025-10-04 214034" src="https://github.com/user-attachments/assets/c2ba2cb8-59a1-4a6b-86c4-ba4a6921e498" />

