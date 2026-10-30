It is now possible to create yunohost backups :
1. Add a hook CONDITION_SNAPSHOT_START with ON_ERROR_CANCEL or ON_ERROR_FATAL as Error Handling.

Add this script
```
/usr/bin/yunohost backup create --methods copy -o __DATA_DIR__/yunohost
chown -R __APP__:__APP__ __DATA_DIR__/yunohost
```
You can add other options **AT THE END** of backup create command : 
  - `--system` (List of system parts to backup (or all if none given)),
  - `--apps` (List of application names to backup (or all if none given))

2. Add a hook CONDITION_SNAPSHOT_END
```
rm -Rf __DATA_DIR__/yunohost/*
```

