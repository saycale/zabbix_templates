# Zabbix Templates and Screens

Collections of Zabbix (http://www.zabbix.com/) templates for Microsoft Windows Server with **MS SQL** installed.

## Templates

1. "Zabbix_Template_MicrosoftSQLServer_Windows.xml" - Common monitoring counters for Windows OS.

2. "Zabbix_Template_MicrosoftSQLServer_Default_Instance.xml" - Only single **default** **MS SQL** instance. No macros are required in host properties.

3. "Zabbix_Template_MicrosoftSQLServer_Named_Instance.xml" - Only single **named** **MS SQL** instance. In host properties macro **{$MSSQL_INSTANCE}** is required with value set to local MSSQL instance.

## Screens

1. "Zabbix_Screen_MicrosoftSQLServer_Windows.xml" - Common monitoring counters for Windows OS.

2. "Zabbix_Screen_MicrosoftSQLServer_Default_Instance.xml" - Only single **default** **MS SQL** instance.

3. "Zabbix_Screen_MicrosoftSQLServer_Named_Instance.xml" - Only single **named** **MS SQL** instance.
