Changelog
=========

0.2.0
----------------
New CLI!

* New Command Line: "chanjo" replaces "chanjo-autopilot"
* Ability to save a temporary JSON file when running Chanjo in parallel (avoids writing to SQLite in several instances)
* New command line option: peaking into a database
* New command line option: building a new SQLite database skeleton
* New command line option: import temporary JSON files
* New command line option: reading coverage from any interval from BAM-file
* Many small bugfixes and minor improvements
* New dependency: path.py

v0.3.0
-----------------
* NEW: API - annotate: splice sites option
* NEW: CLI - annotate: splice sites option
* UPDATE: Much improved documentation
* UPDATE: Modern setuptools only installation
* UPDATE: New cleaner banner
* NEW: travis integration