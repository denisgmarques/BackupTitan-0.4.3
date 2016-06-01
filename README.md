# BackupTitan-0.4.3
Shell Scripts for backup and restore - Titan-0.4.3

# Installation and Configuration
- Copy backup and restore scripts to TITAN_HOME/bin directory
- chmod 755 backup
- chmod 755 restore

# Backup syntax

```bash
backup <keyspace>
```
! The snapshot will be save in TITAN_HOME/backup folder !

# restore syntax

```bash 
restore <snapshot keyspace> [destination keyspace]
```
