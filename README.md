# Monster UI Accounts

Adds service plan tab to monster UI account app for v4.3

Requires [Monster UI v.4.3](https://github.com/2600hz/monster-ui)

#### Installation instructions:
1. Copy the accounts app to your apps directory. You could rename your current one if you want to change later
2. Register the accounts app
```bash
# sup crossbar_maintenance init_app PATH_TO_RATES_DIRECTORY API_ROOT
# The Kazoo user should be able to read files from accounts app directory
sup crossbar_maintenance init_app /var/www/html/monster-ui/apps/accounts https://site.com:8443/v2/
```
3. Update your common folder and subfolders with the common files downloaded
4. Activate account app in the Monster UI App Store ( `/#/apps/appstore` )

Ensure you clear your browser cache if you still don't see a service plan tab
