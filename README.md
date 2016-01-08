# zabbix_templates

Collections of Zabbix (http://www.zabbix.com/) templates.

1. Zabbix_Template_MicrosoftSQLServer_Default_Instance.xml - Zabbix template for Microsoft Windows Server with only single default MS SQL instance. No macros are needed in host properties.

2. Zabbix_Template_MicrosoftSQLServer_Named_Instance.xml - Zabbix template for Microsoft Windows Server with only single named MS SQL instance. In host properties you need to define macro {$MSSQL_INSTANCE} with value set to your local named instance. 
