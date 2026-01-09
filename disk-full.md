# Issue: Disk Full

## Symptoms
- Application not responding
- Errors in logs: "No space left on device"

## Commands to Check
df -h
du -sh /var/*

## Fix
- Delete old logs: `rm -rf /var/log/old_logs/*`
- Empty trash / temp files

## Verify
df -h
