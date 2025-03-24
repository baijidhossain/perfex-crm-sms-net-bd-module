
# SMS.net.bd Module for Perfex CRM

![ALPHASMS + Perfex CRM](./assets/img/sms-net-bd-logo.png)

Easily integrate **[sms.net.bd](https://sms.net.bd)** with **Perfex CRM** to send SMS notifications, check balance, retrieve delivery reports, and manage SMS seamlessly.

## Features
- 📩 Send SMS directly from Perfex CRM
- 📊 Check SMS balance
- 📜 Retrieve delivery reports
- 🔑 Secure API-based communication
- ⚙️ Easy configuration with API Key

## Prerequisites
- Perfex CRM Version 3.2.1
- sms.net.bd sms module version 1.0.1

## Installation Instructions

1. **Download the Latest Release**

   Go to the [Releases](https://github.com/rzietkowski/Perfex-CRM-SMSAPI-Module/releases) page of this repository and download the latest `smsnetbd.zip` file.

2. **Upload the Module**

   - Log in to your Perfex CRM admin panel.
   - Navigate to `Setup` > `Modules`.
   - Click on the `Upload Module` button.
   - Upload the `smsnetbd.zip` file you downloaded in step 1.

3. **Activate the Module**

   - After uploading, find the module in the list of available modules.
   - Click on the `Activate` button next to the module.

4. **Configure the Module**

   - Once activated, navigate to `Setup` > `Settings` > `SMS` > `smsnetbd`.
   - Enter your SMSAPI credentials and configure the settings as needed.

5. **Start Using the Module**

   - You can now start sending SMS notifications from Perfex CRM.

## Additional Configuration

1. **API Key Configuration**

   - Obtain your API key from the SMSAPI panel by navigating to `Settings` > `API Settings` > `API Tokens` > `+ Generate Token`.
   - Provide a token name of your choice and set the expiration date as needed.
   - Select the SMS permission and click `Generate Token`.
   - Copy the generated token and paste it into the API Key field in the module configuration.

2. **Sender Name Configuration**

   - Choose or add a sender name from the SMSAPI panel by navigating to `SMS Messages` > `Sender Fields`.
   - Select your sender field and copy it.
   - Paste it into the Sender Name field in the module configuration.

3. **Message Logging**

   - This module includes an additional feature for logging messages.
   - When enabled, it adds a new menu item under `Reports` > `SMSAPI Log`.
   - This logs sent messages and receives notifications from SMSAPI about message statuses.

## Troubleshooting

If you encounter any issues during installation or usage, please check the following:

- Ensure that you have the correct permissions to upload and activate modules in Perfex CRM.
- Verify that your SMSAPI credentials are correct.
- Check the Perfex CRM documentation for any additional requirements or compatibility issues.

For further assistance, feel free to open an issue on the [GitHub Issues](https://github.com/rzietkowski/Perfex-CRM-SMSAPI-Module/issues) page.

## License

This project is licensed under the Apache License Version 2.0. See the [LICENSE](LICENSE) file for details.