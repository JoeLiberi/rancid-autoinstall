
Description:
	This peice of software will automatically install and configure RANCID (Really Awsome New Cisco Configuration Differ). It will take in a lits of groups, IP addresses, email addresses, and file locations to install RANCID quickly and cleanly.

Layout:
	Install dependancies - bash
	Download Latest version of RANCID from Shrubbery's FTP site - python
	Install RANCID, move default configuration files to ".orig" states - python
	Create .clogin and rancid.conf configuration files from user input - python
	Run "rancid-cvs" to create initial repositories - bash
	Create router.db, start-commit, pre-rev-prop files from user input - python
	Create svn sync bash script to be executed when central the central repository has been setup - bash

To Do:
	EVERYTHING

