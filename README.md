# zabbix-exim

Install

1. Enable "ServerActive" option (zabbix_agentd.conf)
2. Try "Hostname" option (zabbix_agentd.conf)
3. Install zabbix_sender
4. Install logtail
5. Set crontab */5 * * * *  root /root/scripts/zabbix-exim-stats-linux.sh

