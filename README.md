# SMS.net.bd Module for Perfex CRM

![SMS.net.bd + Perfex CRM](./assets/img/sms-net-bd-logo.png)

Easily integrate **[sms.net.bd](https://sms.net.bd)** with **Perfex CRM** to send SMS notifications, check balance, retrieve delivery reports, and manage SMS seamlessly.

## Features
- Send SMS directly from Perfex CRM  
- Check SMS balance  
- Retrieve delivery reports  
- Secure API-based communication  
- Easy configuration with API Key  
- Enable or disable Test Mode  
- Log sent messages for tracking  

## Prerequisites
- Perfex CRM Version 3.2.1
- SMS.net.bd module version 1.0.1
- An account on **[sms.net.bd](https://sms.net.bd/signup)**

## Installation Instructions

1. **Download the Latest Release**
   
   Get the latest `smsnetbd.zip` file from the official **sms.net.bd** module repository.

2. **Upload the Module**
   
   - Log in to your Perfex CRM admin panel.
   - Navigate to `Setup` > `Modules`.
   - Click on the `Upload Module` button.
   - Upload the `smsnetbd.zip` file you downloaded in step 1.

3. **Activate the Module**
   
   - After uploading, find the module in the list of available modules.
   - Click on the `Activate` button next to the module.

4. **Configure the Module**
   
   - Once activated, navigate to `Setup` > `Settings` > `SMS` > `sms.net.bd`.
   - Enter your API Key and configure the settings as needed.

5. **Start Using the Module**
   
   - You can now start sending SMS notifications from Perfex CRM.

## Additional Configuration

### 1. API Key Setup
   
   - Log in to your **sms.net.bd** account.
   - Navigate to `API Menu` > `+ Generate Token`.
   - Provide a token name and set the expiration date as needed.
   - Select the necessary permissions and click `Generate Token`.
   - Copy the generated token and paste it into the **API Key** field in the module configuration.

### 2. Sender ID Configuration
   
   - Log in to your **sms.net.bd** account.
   - Navigate to `SMS Settings` > `Sender ID`.
   - Add or select your approved Sender ID.
   - Copy the Sender ID and paste it into the **Sender ID** field in the module configuration.

### 3. Log Sent Messages
   
   - This module includes an option to log all sent messages.
   - Navigate to `Setup` > `Settings` > `SMS` > `sms.net.bd`.
   - Enable or disable the **Log Sent Messages** option by selecting `Yes` or `No`.
   - When enabled, sent messages will be recorded for tracking purposes.

### 4. Test Mode Selection
   
   - The module allows testing SMS sending before going live.
   - Navigate to `Setup` > `Settings` > `SMS` > `sms.net.bd`.
   - Enable or disable **Test Mode** by selecting `Yes` or `No`.
   - In test mode, SMS will not be actually sent but will be logged for testing purposes.

## Troubleshooting

If you encounter any issues during installation or usage, please check the following:

- Ensure that you have the correct permissions to upload and activate modules in Perfex CRM.
- Verify that your **sm