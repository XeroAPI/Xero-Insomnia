# Xero-Insomnia
An Insomnia collection for authenticating to and calling many of the Xero API endpoints.

## Steps to get up and running
Follow these steps to quickly get up and running with the Xero API and Insomnia:

> ~13 min tutorial on setting up Insomnia from scratch: https://www.youtube.com/watch?v=H_k8Z8Zq99s

### 1. Download Insomnia Client
Visit Insomnia and download the desktop client

### 2. Create an app at https://developer.xero.com/myapps
Go to the Xero developer portal and create an API app

If you haven't already signed up for a xero account you can do so [here](https://www.xero.com/signup/api/).

### 3. Add your client_id key and client_secret to the environment variables in Insomnia
Copy the keys from your app into the environment variables section in Insomnia.

### 4. Get an access_token
Authorize and get back an access_token

### 5. Paste the access_token back into your environment variables
Once you have an access_token plugged in, you will be able to make API calls

### 7. Refresh token for continued access
You can continually visit the `Authentication` route to refresh a token

*NOTE* you will still need to manually copy/paste a refreshed access_token back into the env variables section