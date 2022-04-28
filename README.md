# shadowd.service

This script wraps your "friendly" binary into systemd unit. Blends in with other unit files and start on boot as any normal systemd service
Also script restore mtime atime of affected files and folders as it was before intrusion. 


TODO:
  fix debugfs ctime
