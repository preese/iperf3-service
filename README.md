# iperf3-service
Add a systemctl service for the iperf3 application
only a few lines needed.

Put them into:

sudo cp iperf3* /etc/systemd/system/

sudo systemctl daemon-reload

sudo systemctl enable --now iperf3*

Open firewall ports 5201 and 5202

