# You can create yunohost backups and push them using backrest to your restic repo :

1. Add `/home/yunohost.backup/unpacked/` to backup PATHS when you add a plan.
2. Add a hook CONDITION_SNAPSHOT_START with ON_ERROR_CANCEL or ON_ERROR_FATAL as Error Handling.

Add this script : it will create an uncompressed backup in "/home/yunohost.backup/unpacked/" and fix its ownership so Backrest can have access to it :
```
/usr/bin/yunohost backup create --methods copy -o /home/yunohost.backup/unpacked/
chown -R __APP__:__APP__ /home/yunohost.backup/unpacked/
```
You can add other options **AT THE END** of backup create command : 
  - `--system` (List of system parts to backup (or all if none given)),
  - `--apps` (List of application names to backup (or all if none given))

3. Add a hook CONDITION_SNAPSHOT_END : this will clean the local backup :
```
rm -Rf /home/yunohost.backup/unpacked/*
```

# How to restore :
TODO
