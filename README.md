# Harmony-Mobile-CLI-Explorer
Interactive command-line client for the Check Point Harmony Mobile API with device caching, automatic token renewal, and full hard-coded endpoint navigation

This project assumes your are using US-based portals. So, change it accordingly to the correct server. Not all the APIs are implemented
https://app.swaggerhub.com/apis-docs/Check-Point/harmony-mobile/1.0.0-oas7 

<img width="657" height="81" alt="image" src="https://github.com/user-attachments/assets/8c65f9eb-aa5e-4ec9-9a31-0d6aed7a3ad3" />

**A. Create the New API KEY.
**

<img width="1318" height="663" alt="image" src="https://github.com/user-attachments/assets/f56c3d24-d835-4f70-9f30-2010dd3b7443" />

You will get the Client ID and the Secret Key.

<img width="588" height="503" alt="image" src="https://github.com/user-attachments/assets/e640e364-e61a-43ea-b12f-feec95ad0a5a" />


**B. To install it follow the following steps in your computer.
**

git clone https://github.com/moralesaugusto/Harmony-Mobile-CLI-Explorer.git

cd Harmony-Mobile-CLI-Explorer

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt


**Open the credentials.txt file, and add the corresponding client_id and access_key
**

python3 harmony-mobile-cli-explorer.py

Authenticated successfully

Loading devices into memory...
Loaded 5 devices
Devices were already loaded in memory.
Cached fields: internal_id, status

internal_id: 6  status: 0
internal_id: 5  status: 0
internal_id: 4  status: 0
internal_id: 3  status: 0
internal_id: 2  status: 0

========== Harmony Mobile API ==========

1) Alerts
2) Devices
3) Device Registration
4) Device Risk & Security
5) Policy
6) Groups
7) Raw API Explorer
0) Exit

Select category: 


NOTE: Not all the APIs are implemented yet. Make sure you protect your API keys


