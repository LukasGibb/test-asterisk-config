# test-asterisk-config
Dummy Asterisk config files used to test asterisk-config-deploy Ansible role

Also includes several non-asterisk related files/folders to confirm that these files are not linked to the asterisk config directory by accident. The role should only copy files with common asterisk config file extensions (*.conf, *.ael, *.lua etc).

The repo includes a subfolder with more config files for testing the use of the asterisk_config_deploy_repo_subfolder variable.