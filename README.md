# PDB-Assignmement
PL work

Name: Sugira Ghislain

ID: 27776
# Report: Creating and Managing a Pluggable Database in Oracle

## 1. Overview of the Task

The main objective of this work was to:

•	Create a new Pluggable Database (PDB) in Oracle Database 23c Free (23ai).

•	Configure user access within the new PDB.

•	Understand and resolve common connection and configuration issues.

•	Verify the database state and ensure it runs correctly through SQL*Plus.

We worked with the following Oracle components:

•	Container Database (CDB): CDB$ROOT

•	Default PDB: FREEPDB1

•	New PDB created: GH_PDB_27776

•	User account: ghislain_plsqlauca_27776

## Encountered issues:
		
•	ORA-12514: Service XE is not registered with the listener		.

	Started the database with STARTUP and ran ALTER SYSTEM REGISTER.

•	ORA-28009: connection as SYS should be as SYSDBA.

	Used AS SYSDBA during connection.

To avoid repeating manual steps after every restart.

ALTER PLUGGABLE DATABASE ALL SAVE STATE;
		
