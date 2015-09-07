# owncloud-fail2ban

This is an automated installer for fail2ban, which installs fail2ban and sets the specific owncloud configurations.

## Install
Just execute the following command and the fail2ban filter for owncloud will be activated and set up:

```curl -s "https://raw.githubusercontent.com/AykutCevik/owncloud-fail2ban/master/automated-install/install.sh" | bash```


## Version
The script has been tested with owncloud 8.1.1, 8.1.2 and Ubuntu, but may also run under other versions and distributions. If not, please let me know.

## Owncloud 8.0
You can find the working installer for all 8.0 versions in the following branch: https://github.com/AykutCevik/owncloud-fail2ban/tree/owncloud-8.0