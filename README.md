# kristuff/abuseipdb-client

Bootstrap for [kristuff/abuseipdb-cli](https://github.com/kristuff/abuseipdb-cli), CLI tool to check ✔️, report 🚩 IP address, download blacklists 🚫 with AbsuseIPDB API v2

This project is a bootstrap, it defines dependencies (including main program) and is used to help deploy binary files and config files. This the recommended way to install all dependencies with composer and allow to update them.

## Features

- Single IP check request **✓** 
- IP block check request **✓** 
- Blacklist request **✓** 
- Single IP report request **✓** 
- Bulk report request (send `csv` file) **✓** 
- Clear IP address request (remove your own reports) **✓**
- Auto cleaning report comments from sensitive data (email, custom ip/domain names list)  **✓** 
- Easy Fail2ban integration **✓** 
- Colored reports **✓** 

## More infos

- [Project website](https://kristuff.fr/projects/abuseipdbcli)
- [Api documentation](https://kristuff.fr/projects/abuseipdbcli/doc)
- [Config/Install guide](https://kristuff.fr/projects/abuseipdbcli/technical#configuration)
