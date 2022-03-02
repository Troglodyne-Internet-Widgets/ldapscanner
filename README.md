ldapscanner
===========

Reads a config file in the same dir (ldapscanner.cfg)
and then scans for changes since last time it was ran.

Base your config on ldapscanner.cfg.dist

Previous run data is stored in `.last.json`
Current diff data is stored in `.current_diff.json`
