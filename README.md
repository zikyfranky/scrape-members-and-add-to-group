# HOW TO USE

## Create a Telegram App and Get Your Credentialss

1. Go to my.telegram.org and log in.

   ![Login](./assets/login.png)

2. Click on API development tools and fill the required fields.

   ![Create App](./assets/desc.png)

3. You can choose any name for your app. After submitting, you will receive api_id and api_hash. Save them somewhere. You will use these credentials to login to Telegram API.

   ![Input Fields](./assets/last.png)

4. Update all auth variable in `secrets.py`

5. Install Telethon

   You can install telethon using pip: `pip install telethon`

6. Run `python get_users.py` to get users from a group, this creates a `.csv` file.

7. Run `py add_users.py path/to/csv_file.csv`
