# montd-dbpm-oracle
Oracle Database Observability
 
 ## Metrics

The following metrics are exposed currently.

```bash 
OracleDbUp - The metric equals 1 if the exporter can connect to the database otherwise it displays this: <1	ORACLE_FAST & ORACLE_NORMAL & ORACLE_SLOW
OracleInstUp - This metric equals 1 if the exporter instance is up, otherwise, it displays this: <1	ORACLE_FAST & ORACLE_NORMAL & ORACLE_SLOW
OracleWaitEvents - This metric shows labels for each wait event category and wait time	ORACLE_FAST
OracleSessLongOps	- This metric shows (in minutes) the sessions in LongOps	ORACLE_NORMAL
OracleUpTime - This metric determines for how long the session has been up	ORACLE_NORMAL
OracleSessStates - This metric visualize the actual state session, showing if its either "active" or "inactive"	ORACLE_NORMAL
OracleParameters - This metric shows one label for each parameter from oracle SPFile	ORACLE_NORMAL
OracleRedoSW - This metric shows how much redo logs switches happens each hour	ORACLE_NORMAL
OracleCPUHostUsage - This metric shows the percentage of  the host CPU Usage	ORACLE_NORMAL
OracleCPUInstUsage - This metric shows the percentage of the instance CPU Usage	ORACLE_NORMAL
OracleLongSession - This metric shows sessions that has been up for more than 2 hours	ORACLE_NORMAL
OracleFraTotal - This metric show the "Fast Recovery Area" total memory	ORACLE_SLOW
OracleFraUsed - This metric shows the used space in "Fast Recovery Area"	ORACLE_SLOW
OracleTbsUsed - This metric shows the tablespace used memory bytes by each user	ORACLE_SLOW
OracleTbsTotal - This metric shows the total size of all the tablespaces by instance	ORACLE_SLOW
OracleDbSize - This metric shows the total size of each database by instance	ORACLE_SLOW
OracleDbAlloc - This metric shows the amount of allocated bytes of each database by instance	ORACLE_SLOW
OracleInvalidObj - This metric shows the amount of invalid objects of each database by instance 	ORACLE_SLOW
OracleInvalidComp - This metric shows the amount of invalid components of each database by instance 	ORACLE_SLOW
OracleAsmTotal - This metric displays the total amount of memory available in ASM DG	ORACLE_ASM
OracleAsmRedundancy		ORACLE_ASM
OracleAsmFree - This metric displays the free amount of memory available in ASM DG	ORACLE_ASM
``` 
