# kopitiam

Repository related to Sinar's Mattermost platform kopitiam.sinarproject.org 

Currently running on: `thor`: `192.168.0.166:8065`

## To deploy
1. Prepare database https://docs.mattermost.com/install/prepare-mattermost-database.html. To ensure that `mmuser` has all privileges on the database, `ALTER ROLE mmuser WITH SUPERUSER`
  
2. Install Mattermost https://docs.mattermost.com/install/install-ubuntu.html
Note: Ensure that the config file edited is `/opt/mattermost/config/config.json`

3. Start the Mattermost server `sudo systemctl start mattermost`
