```
marras 05 19:27:58 annina-PH sudo[5489]:   annina : TTY=pts/0 ; PWD=/home/annina ; USER=root ; COMMAND=/usr/bin/journalctl --grep caddy -n 30
marras 05 19:27:15 annina-PH sudo[5484]:   annina : TTY=pts/0 ; PWD=/home/annina ; USER=root ; COMMAND=/usr/bin/journalctl --grep caddy -n 30
marras 05 19:25:16 annina-PH sudo[5467]:   annina : TTY=pts/0 ; PWD=/home/annina ; USER=root ; COMMAND=/usr/bin/journalctl --grep caddy -n 30
marras 05 19:25:02 annina-PH sudo[5461]:   annina : TTY=pts/0 ; PWD=/home/annina ; USER=root ; COMMAND=/usr/bin/journalctl --grep caddy n 30
marras 05 18:46:19 annina-PH sudo[4625]:   annina : TTY=pts/0 ; PWD=/usr/share/caddy ; USER=root ; COMMAND=/usr/bin/editor -- /usr/share/caddy/index.html
marras 05 18:44:39 annina-PH systemd[1]: Started caddy.service - Caddy.
marras 05 18:44:39 annina-PH caddy[4591]: {"level":"info","ts":1793897079.5655692,"msg":"autosaved config (load with --resume flag)","file":"/var/lib/caddy/.config/caddy/autosave.json"}
marras 05 18:44:39 annina-PH caddy[4591]: {"level":"info","ts":1793897079.5611932,"logger":"tls","msg":"cleaning storage unit","description":"FileStorage:/var/lib/caddy/.local/share/caddy"}
marras 05 18:44:39 annina-PH caddy[4591]: {"level":"info","ts":1793897079.5460167,"msg":"using provided configuration","config_file":"/etc/caddy/Caddyfile","config_adapter":""}
marras 05 18:44:39 annina-PH caddy[4591]: MEMORY_PRESSURE_WATCH=/sys/fs/cgroup/system.slice/caddy.service/memory.pressure
marras 05 18:44:39 annina-PH caddy[4591]: HOME=/var/lib/caddy
marras 05 18:44:39 annina-PH caddy[4591]: LOGNAME=caddy
marras 05 18:44:39 annina-PH caddy[4591]: USER=caddy
marras 05 18:44:39 annina-PH caddy[4591]: caddy.Version=2.6.2
marras 05 18:44:39 annina-PH caddy[4591]: caddy.ConfigAutosavePath=/var/lib/caddy/.config/caddy/autosave.json
marras 05 18:44:39 annina-PH caddy[4591]: caddy.AppConfigDir=/var/lib/caddy/.config/caddy
marras 05 18:44:39 annina-PH caddy[4591]: caddy.AppDataDir=/var/lib/caddy/.local/share/caddy
marras 05 18:44:39 annina-PH caddy[4591]: caddy.HomeDir=/var/lib/caddy
marras 05 18:44:39 annina-PH systemd[1]: Starting caddy.service - Caddy...
marras 05 18:44:39 annina-PH systemd[1]: Stopped caddy.service - Caddy.
marras 05 18:44:39 annina-PH systemd[1]: caddy.service: Deactivated successfully.
marras 05 18:44:39 annina-PH systemd[1]: Stopping caddy.service - Caddy...
marras 05 18:44:39 annina-PH sudo[4583]:   annina : TTY=pts/0 ; PWD=/etc/caddy ; USER=root ; COMMAND=/usr/bin/systemctl restart caddy
marras 05 18:43:58 annina-PH sudo[4577]:   annina : TTY=pts/0 ; PWD=/etc/caddy ; USER=root ; COMMAND=/usr/bin/editor -- Caddyfile
marras 05 18:41:04 annina-PH sudo[4534]:   annina : TTY=pts/0 ; PWD=/etc/caddy ; USER=root ; COMMAND=/usr/bin/editor -- /usr/share/caddy/index.html
marras 05 18:38:23 annina-PH sudo[4156]:   annina : TTY=pts/0 ; PWD=/etc/caddy ; USER=root ; COMMAND=/usr/bin/editor -- /usr/share/caddy/index.html
marras 05 18:37:20 annina-PH systemd[1]: Started caddy.service - Caddy.
marras 05 18:37:20 annina-PH caddy[4144]: {"level":"info","ts":1793896640.0400398,"msg":"autosaved config (load with --resume flag)","file":"/var/lib/caddy/.config/caddy/autosave.json"}
marras 05 18:37:20 annina-PH caddy[4144]: {"level":"info","ts":1793896640.036139,"logger":"tls","msg":"cleaning storage unit","description":"FileStorage:/var/lib/caddy/.local/share/caddy"}
marras 05 18:37:20 annina-PH caddy[4144]: {"level":"info","ts":1793896640.0202334,"msg":"using provided configuration","config_file":"/etc/caddy/Caddyfile","config_adapter":""}
```
