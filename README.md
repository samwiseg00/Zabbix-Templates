# Zabbix-Templates
Some tested templates for zabbix
### Repo to link from zabbix share : https://share.zabbix.com
Full description on Zabbix share

### Hereby a brief list of templates
- Printers_Template.xml : A generic template to monitor printers and retrieve/follow printers supplies level
- Ruckus_ZD1200_Template.xml : A template (tested on ZD1200) to monitor a Ruckus ZD1200 and associated AP and WLAN
- Ruckus_ZD1200_mappings.xml : Separate file for mappings table (included in template)
- HP_ILO4_SNMP_Agentless.xml : Generic SNMP template to request HW information through HP iLO4 interface. Monitors System health.

### Notes
- All template need to have the 2 following MACROS set :
  - {#SNMP_COMMUNITY}
  - {#SNMP_PORT}
  As they are defined with these macro to be easily portable.
