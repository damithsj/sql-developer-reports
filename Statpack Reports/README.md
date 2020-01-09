# SQL Developer Reports based on statpack

Run these reports as SYS or PERFSTAT user

## CPU Usage
Shows CPU usage of host and % of busy CPU used by instance
- Indication of high Host CPU Usage is that host migth need more CPU
- Indication of high CPU used for Instance is that dataabse is busy

## Memory Stats
Shows SGA and PGA memory as percentage of host memory.

## Time Model System Stats
Shows DB CPU time and SQL elapsed time. Peaks in DB CPU time/Elapsed time indicates heavy operations in the database.
This has two sub reports. Click on a data point to fetch the sub report data for that particular time.
- SQL ordered by Elapsed time
- SQL ordered by CPU

These reports are based on standard statpack report rdbms/admin/spreport.sql and STATSPACK package rdbms/admin/spcpkg.sql
