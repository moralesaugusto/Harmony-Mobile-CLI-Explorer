# Harmony-Mobile-CLI-Explorer
Interactive command-line client for the Check Point Harmony Mobile API with device caching, automatic token renewal, and hard-coded API navigation.

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


See below an example:


<img width="708" height="381" alt="image" src="https://github.com/user-attachments/assets/753f3473-015e-4f2d-a2e5-d525ed383e56" />

