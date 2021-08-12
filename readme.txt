Steps to Implement Google Sheets API-

1. Create a new project from Google Developers Console- https://console.google.developers.com
2. Go to APIs Library- https://console.cloud.google.com/apis/library
3. Enable Google Drive and Google Sheets APIs.
4. Go to Create Credentials and choose Service Account
5. Give Editor access.
6. Click Create Key->JSON.
7. Rename the downloaded json as "creds.json" and store it in the "creds" folder.
8. Copy the "client_email" from the json file and add that email as an editor to a Google Sheet.
9. Use example.py as a starting point to write code.

P.S- Don't forget to install dependicies mentioned in the requirements.txt file.
