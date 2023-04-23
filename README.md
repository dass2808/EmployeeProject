# EmployeeProject

## How To Use

Run the following command in Package Manager console to restore db and tables

```bash
$ Update-Database
````

Setup email configuration in appsettings to send out email

```bash
"MailKitEmailSender": {
    "Address": "<your-smtp-address>",
    "Port": "<your-port>",
    "Account": "<your-email-id",
    "Password": "<your-email-password>",
    "SenderEmail": "<your-email-id>",
    "SenderName": "<your-sender-name>"
}
````
