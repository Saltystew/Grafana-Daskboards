# Grafana Daskboards

Some json files for several Grafana dashboards I threw together, gathering metrics through [telegraf](https://portal.influxdata.com/downloads), as well as one powershell script that grabs cyberpower ups data, and pushing them to [InfluxDB](https://portal.influxdata.com/downloads).

# Cyberpower UPS powershell script

To make this script work you need to have their [PowerPanel Business Edition](https://www.cyberpowersystems.com/products/software/power-panel-business/) software installed and then make sure the third line in the powershell script reflects the IP:Port of your powerpanel install, as well as edit the second to last line in the powershell script to reflect the IP:Port of your influxDB. Set the script up as a schedule task or cronjob and you're good to go.

Also quick note, I didn't write this powershell script someone on reddit did if I remember correctly. But it appears they've deleted their post now and or their account, it was [here](https://www.reddit.com/r/homelab/comments/52048o/cyberpower_ups_and_grafanainfluxdb/) before.