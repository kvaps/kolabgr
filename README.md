# kolabgr
This script generates a list of groups and members from Kolab's LDAP for Prosody's mod_groups

### Usage
Now script partly uses [mod_lib_ldap](https://modules.prosody.im/mod_lib_ldap.html) config, so be sure in the presence of [kolabgr section](https://github.com/kvaps/kolabgr/blob/master/ldap.cfg.lua#L6-L10) in ldap.cfg.lua

Run:
```bash
/usr/bin/lua /etc/prosody/kolabgr.lua > /etc/prosody/groups.txt
```
add this to your crontab
