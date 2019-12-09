# sf-backup
Simple script to backup three main files in Salesforce

## To use this file:

1. Install Python 3 on your computer and, optionally, start a virtual
   environment.
2. Unzip the file or clone the repository into a directory
3. Go to the directory and "pip install -r requirements.txt"
4. Edit the "salesforce_secrets.py" file to reflect your username,
   password, and token
4. Run "python save_tables.py"
5. The folder "stash_dir" will then have copies of the three main tables.
