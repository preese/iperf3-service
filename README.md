# iperf3-service
Add a systemctl service for the iperf3 application
only a few lines needed.

Put them into:
/etc/systemd/system/
sudo systemctl daemon-reload
sudo systemctl enable --now iperfX

