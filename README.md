# FamilyVisaBot
Get notified about potential timeslots available in VFS Global. Written in Python language.

Below steps assume you have Python and Google Chrome installed. Tested with Python version 3.10.5 and Google Chrome version 116.

Step 1: Download the chromedriver.exe compatible with your Chrome version. Check links at https://googlechromelabs.github.io/chrome-for-testing/#stable. Store chromedriver.exe in the FamilyVisaBot project folder.

Step 2: Install bot dependencies from requirements.txt file by running command pip install -r requirements.txt

Step 3: Set-up a telegram bot and open file scrapper.py. Replace value for variables telegram_token and telegram_chatid by bot token and group chat id respectively.

Final step: Run script by executing scrapper.py
