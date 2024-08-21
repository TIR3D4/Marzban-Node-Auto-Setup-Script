# Marzban-Node-Auto-Setup-Script
This repository contains a Python script that automates the setup and integration of a node with the Marzban panel. The script installs necessary packages, configures Docker, and sets up the node with SSL certification, streamlining the connection process to the Marzban panel.

## Prerequisites

- A server running a compatible Linux distribution (e.g., Ubuntu).
- Root or sudo access to the server.
- A valid SSL certificate in PEM format for the node.

## Installation

Download and Run the Script

Use the following command to download the Python script directly from the repository and execute it:

curl -O https://raw.githubusercontent.com/TIR3D4/Marzban-Node-Auto-Setup-Script/main/setup_marzban_node.py
sudo python3 setup_marzban_node.py

Enter SSL Certificate

During the execution of the script, you will be prompted to enter your SSL certificate. Paste the content of your certificate, including the -----BEGIN CERTIFICATE----- and -----END CERTIFICATE----- lines.

Completion

The script will automatically:

Update and upgrade the system.
Install Docker and required packages.
Clone the Marzban-node repository.
Configure Docker with the necessary settings.
Deploy the node with Docker.
Troubleshooting
Ensure your SSL certificate is in the correct PEM format.
The server should have internet access to download packages and clone the repository.
If the script fails, check the output for any errors, correct them, and re-run the script.
